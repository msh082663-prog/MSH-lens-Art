!DOCTYPE html>
<html lang="bn" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSH LENS ART | ফটোগ্রাফি ও সিনেমাটোগ্রাফি পোর্টফোলিও</title>
    
    <!-- Google Fonts: Hind Siliguri, Cinzel, Montserrat -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=Hind+Siliguri:wght@400;500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Tailwind Configuration for Red & Pink Glow Theme -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        bengali: ['"Hind Siliguri"', 'sans-serif'],
                        editorial: ['"Cinzel"', 'serif'],
                        sans: ['"Montserrat"', '"Hind Siliguri"', 'sans-serif'],
                    },
                    colors: {
                        obsidian: '#0b0708',
                        charcoal: '#140c0e',
                        velvetRed: '#e11d48',
                        reelsPink: '#ec4899',
                    },
                    animation: {
                        'slow-zoom': 'slowZoom 20s ease-in-out infinite alternate',
                        'fade-in-up': 'fadeInUp 0.8s cubic-bezier(0.16, 1, 0.3, 1) forwards',
                    },
                    keyframes: {
                        slowZoom: {
                            '0%': { transform: 'scale(1)' },
                            '100%': { transform: 'scale(1.08)' },
                        },
                        fadeInUp: {
                            '0%': { opacity: '0', transform: 'translateY(24px)' },
                            '100%': { opacity: '1', transform: 'translateY(0)' },
                        }
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #0b0708;
            color: #f4f4f6;
            font-family: 'Hind Siliguri', sans-serif;
            overflow-x: hidden;
        }

        .film-grain {
            position: fixed;
            inset: 0;
            pointer-events: none;
            z-index: 40;
            opacity: 0.035;
            background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noiseFilter'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.8' numOctaves='3' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noiseFilter)'/%3E%3C/svg%3E");
        }

        .glass-nav {
            background: rgba(11, 7, 8, 0.82);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-bottom: 1px solid rgba(225, 29, 72, 0.15);
        }

        .reveal {
            opacity: 0;
            transform: translateY(24px);
            transition: all 0.75s cubic-bezier(0.16, 1, 0.3, 1);
        }
        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }

        .text-crimson-pink {
            background: linear-gradient(135deg, #fb7185 0%, #e11d48 50%, #ec4899 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .gallery-card img {
            transition: transform 0.7s cubic-bezier(0.16, 1, 0.3, 1), filter 0.5s ease;
        }
        .gallery-card:hover img {
            transform: scale(1.06);
            filter: brightness(0.85);
        }
    </style>
</head>
<body class="antialiased selection:bg-velvetRed/30 selection:text-pink-200">

    <!-- Cinematic Film Grain Overlay -->
    <div class="film-grain"></div>

    <!-- 1. NAVIGATION BAR -->
    <header id="navbar" class="fixed top-0 left-0 right-0 z-50 glass-nav">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Brand Logo -->
                <a href="#home" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-full border border-velvetRed/60 flex items-center justify-center bg-charcoal group-hover:border-reelsPink transition-colors shadow-[0_0_15px_rgba(225,29,72,0.3)]">
                        <svg class="w-5 h-5 text-velvetRed group-hover:text-reelsPink transition-colors" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8">
                            <circle cx="12" cy="12" r="9" />
                            <circle cx="12" cy="12" r="3" />
                            <path d="M12 3v3M12 18v3M3 12h3M18 12h3" />
                        </svg>
                    </div>
                    <div>
                        <span class="font-editorial text-lg sm:text-xl font-bold tracking-[0.18em] text-white block leading-none">
                            MSH <span class="text-crimson-pink">LENS ART</span>
                        </span>
                        <span class="text-[10px] tracking-[0.25em] text-pink-300/70 uppercase font-sans">@mshlensart</span>
                    </div>
                </a>

                <!-- Desktop Nav Navigation -->
                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">হোম</a>
                    <a href="#services" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">সেবা</a>
                    <a href="#gallery" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">গ্যালারি</a>
                    <a href="#projects" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">শো-রিল</a>
                    <a href="#about" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">আমার পরিচয়</a>
                    <a href="#contact" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">যোগাযোগ</a>
                </nav>

                <!-- Desktop CTA -->
                <div class="hidden md:flex items-center gap-4">
                    <a href="#contact" class="px-5 py-2.5 rounded-full text-xs font-semibold tracking-wider uppercase border border-velvetRed text-pink-100 hover:bg-velvetRed hover:text-white transition-all duration-300 shadow-[0_0_20px_rgba(225,29,72,0.3)]">
                        বুকিং করুন
                    </a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" aria-label="মেনু খুলুন" class="md:hidden p-2.5 rounded-xl text-zinc-300 hover:text-white hover:bg-white/5">
                    <svg id="menu-icon-open" class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M4 6h16M4 12h16M4 18h16"/>
                    </svg>
                    <svg id="menu-icon-close" class="w-6 h-6 hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.8" d="M6 18L18 6M6 6l12 12"/>
                    </svg>
                </button>
            </div>
        </div>

        <!-- Mobile Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-obsidian/95 backdrop-blur-xl border-b border-velvetRed/20 px-6 pt-3 pb-6 space-y-3">
            <a href="#home" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">হোম</a>
            <a href="#services" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">সেবা</a>
            <a href="#gallery" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-white border-b border-white/5">গ্যালারি</a>
            <a href="#projects" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">শো-রিল</a>
            <a href="#about" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">আমার পরিচয়</a>
            <a href="#contact" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed">যোগাযোগ</a>
            <div class="pt-2">
                <a href="#contact" class="mobile-link block w-full text-center py-3 rounded-xl bg-gradient-to-r from-velvetRed to-reelsPink text-white font-semibold text-sm shadow-lg">
                    সেশন বুকিং করুন
                </a>
            </div>
        </div>
    </header>

    <!-- 2. HERO SECTION -->
    <section id="home" class="relative min-h-screen flex items-center justify-center overflow-hidden pt-20">
        <div class="absolute inset-0 z-0">
            <img 
                src="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=1920&q=85" 
                onerror="this.src='https://placehold.co/1920x1080/0b0708/e11d48?text=MSH+LENS+ART'"
                alt="Cinematic Background" 
                class="w-full h-full object-cover object-center animate-slow-zoom opacity-35"
            />
            <div class="absolute inset-0 bg-gradient-to-b from-obsidian/90 via-obsidian/60 to-obsidian"></div>
            <div class="absolute inset-0 bg-gradient-to-r from-obsidian via-transparent to-obsidian"></div>
        </div>

        <div class="relative z-10 max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="inline-flex items-center gap-2.5 px-4 py-1.5 rounded-full bg-white/[0.04] border border-velvetRed/30 backdrop-blur-md mb-8 animate-fade-in-up">
                <span class="w-2.5 h-2.5 rounded-full bg-reelsPink animate-pulse"></span>
                <span class="text-xs font-sans uppercase tracking-[0.25em] text-pink-200">Cinematography & Photography &bull; @mshlensart</span>
            </div>

            <h1 class="text-3xl sm:text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight leading-[1.2] mb-6 animate-fade-in-up" style="animation-delay: 0.1s;">
                <span class="font-editorial block text-xl sm:text-2xl md:text-3xl tracking-[0.28em] text-crimson-pink mb-3 font-semibold">
                    MSH LENS ART
                </span>
                <span class="text-white">মুহূর্তগুলোকে সিনেমাটিক গল্পে রূপান্তর</span>
            </h1>

            <p class="max-w-2xl mx-auto text-base sm:text-lg md:text-xl text-zinc-300 font-light leading-relaxed mb-10 animate-fade-in-up" style="animation-delay: 0.2s;">
                আলো, ছায়া এবং আধুনিক ভিজ্যুয়ালসের নিখুঁত সংমিশ্রণে আমরা আপনার বিশেষ মুহূর্ত, পোর্ট্রেট এবং ব্র্যান্ড রিলস তুলে ধরি এক অনন্য সিনেমাটিক আবহে।
            </p>

            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 sm:gap-5 animate-fade-in-up" style="animation-delay: 0.3s;">
                <a href="#contact" class="w-full sm:w-auto px-8 py-4 rounded-full bg-gradient-to-r from-velvetRed to-reelsPink text-white font-semibold text-base tracking-wide hover:opacity-90 transition-all duration-300 shadow-[0_0_30px_rgba(225,29,72,0.4)] flex items-center justify-center gap-2">
                    <span>সরাসরি বুকিং করুন</span>
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                    </svg>
                </a>
                <a href="#gallery" class="w-full sm:w-auto px-8 py-4 rounded-full bg-white/[0.05] hover:bg-white/[0.1] text-white border border-white/15 backdrop-blur-md font-medium text-base tracking-wide transition-all duration-300">
                    পোর্টফোলিও দেখুন
                </a>
            </div>
        </div>

        <!-- Scroll Indicator -->
        <div class="absolute bottom-8 left-1/2 -translate-x-1/2 flex flex-col items-center gap-2 opacity-60">
            <span class="text-[10px] font-sans uppercase tracking-[0.3em] text-pink-300">Scroll</span>
            <div class="w-px h-10 bg-gradient-to-b from-velvetRed to-transparent"></div>
        </div>
    </section>

    <!-- 3. SERVICES SECTION -->
    <section id="services" class="py-24 sm:py-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-16 gap-6 reveal">
            <div>
                <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-2">Services & Expertise</p>
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white">আমাদের সেবাসমূহ</h2>
            </div>
            <p class="text-zinc-400 max-w-md text-sm sm:text-base">
                প্রফেশনাল কাস্টমাইজড শুটিং প্ল্যান, কালার গ্রেডিং এবং ইনস্টাগ্রাম-রেডি রিলস প্রোডাকশন সুবিধা।
            </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Service 1 -->
            <div class="group rounded-2xl bg-charcoal border border-white/10 p-7 hover:border-velvetRed/50 transition-all duration-300 flex flex-col justify-between reveal">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-velvetRed/10 border border-velvetRed/30 flex items-center justify-center text-velvetRed mb-6 group-hover:bg-velvetRed group-hover:text-white transition-colors">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z"/>
                            <circle cx="12" cy="13" r="3" stroke-width="1.7"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">পোর্ট্রেট ফটোগ্রাফি</h3>
                    <p class="text-sm text-zinc-400 leading-relaxed mb-6">
                        ব্যক্তিগত ব্র্যান্ডিং, ফ্যাশন এডিটোরিয়াল এবং আউটডোর বা স্টুডিও স্টাইলে ড্রামাটিক পোর্ট্রেট শুট।
                    </p>
                </div>
                <div class="pt-4 border-t border-white/5 flex items-center justify-between text-xs">
                    <span class="text-reelsPink font-medium">হাই-রেজোলিউশন রিটাচ</span>
                    <a href="#contact" class="text-zinc-300 hover:text-velvetRed transition-colors">বুকিং &rarr;</a>
                </div>
            </div>

            <!-- Service 2 -->
            <div class="group rounded-2xl bg-charcoal border border-white/10 p-7 hover:border-velvetRed/50 transition-all duration-300 flex flex-col justify-between reveal">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-velvetRed/10 border border-velvetRed/30 flex items-center justify-center text-velvetRed mb-6 group-hover:bg-velvetRed group-hover:text-white transition-colors">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M15 10l4.553-2.276A1 1 0 0121 8.618v6.764a1 1 0 01-1.447.894L15 14M5 18h8a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v8a2 2 0 002 2z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">সিনেমাটিক ভিডিওগ্রাফি</h3>
                    <p class="text-sm text-zinc-400 leading-relaxed mb-6">
                        ৪কে সিনেমাটিক ফ্রেম রেট, গিম্বল শট এবং ফিল্ম-গ্রেড কালার গ্রেডিংসহ প্রফেশনাল ভিডিও নির্মাণ।
                    </p>
                </div>
                <div class="pt-4 border-t border-white/5 flex items-center justify-between text-xs">
                    <span class="text-reelsPink font-medium">4K সিনেমাটিক গ্রেডিং</span>
                    <a href="#contact" class="text-zinc-300 hover:text-velvetRed transition-colors">বুকিং &rarr;</a>
                </div>
            </div>

            <!-- Service 3 -->
            <div class="group rounded-2xl bg-charcoal border border-white/10 p-7 hover:border-velvetRed/50 transition-all duration-300 flex flex-col justify-between reveal">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-velvetRed/10 border border-velvetRed/30 flex items-center justify-center text-velvetRed mb-6 group-hover:bg-velvetRed group-hover:text-white transition-colors">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">ইভেন্ট কভারেজ</h3>
                    <p class="text-sm text-zinc-400 leading-relaxed mb-6">
                        বিয়ে, সাংস্কৃতিক অনুষ্ঠান ও স্পেশাল প্রোগ্রামের প্রতিটি স্মরণীয় মুহূর্তের পূর্ণাঙ্গ ডকুমেন্টেশন।
                    </p>
                </div>
                <div class="pt-4 border-t border-white/5 flex items-center justify-between text-xs">
                    <span class="text-reelsPink font-medium">ফটো + ভিডিও ফিল্ম</span>
                    <a href="#contact" class="text-zinc-300 hover:text-velvetRed transition-colors">বুকিং &rarr;</a>
                </div>
            </div>

            <!-- Service 4 -->
            <div class="group rounded-2xl bg-charcoal border border-white/10 p-7 hover:border-velvetRed/50 transition-all duration-300 flex flex-col justify-between reveal">
                <div>
                    <div class="w-12 h-12 rounded-xl bg-velvetRed/10 border border-velvetRed/30 flex items-center justify-center text-velvetRed mb-6 group-hover:bg-velvetRed group-hover:text-white transition-colors">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.7" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"/>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold text-white mb-3">ব্র্যান্ড ভিজ্যুয়ালস & রিলস</h3>
                    <p class="text-sm text-zinc-400 leading-relaxed mb-6">
                        ইনস্টাগ্রাম রিলস, ফেসবুক প্রমোশন এবং ব্র্যান্ডের প্রচারের জন্য আই-ক্যাচিং শর্ট-ফর্ম ভিজ্যুয়াল কনটেন্ট।
                    </p>
                </div>
                <div class="pt-4 border-t border-white/5 flex items-center justify-between text-xs">
                    <span class="text-reelsPink font-medium">ট্রেন্ডিং রিলস কন্টেন্ট</span>
                    <a href="#contact" class="text-zinc-300 hover:text-velvetRed transition-colors">বুকিং &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. GALLERY SECTION -->
    <section id="gallery" class="py-24 sm:py-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-14 gap-6 reveal">
            <div>
                <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-2">Selected Works</p>
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white">নির্বাচিত পোর্টফোলিও গ্যালারি</h2>
            </div>

            <div class="flex flex-wrap items-center gap-2 sm:gap-3" id="filter-buttons">
                <button type="button" data-filter="all" class="filter-btn active px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-gradient-to-r from-velvetRed to-reelsPink text-white">
                    সব
                </button>
                <button type="button" data-filter="portrait" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">
                    পোর্ট্রেট
                </button>
                <button type="button" data-filter="cinematic" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">
                    সিনেমাটিক
                </button>
                <button type="button" data-filter="event" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">
                    ইভেন্ট
                </button>
            </div>
        </div>

        <div id="gallery-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 sm:gap-8">
            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="portrait"
                 data-title="গোধূলির আলোয় পোর্ট্রেট"
                 data-subtitle="পোর্ট্রেট ফটোগ্রাফি &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Portrait+Frame'"
                     alt="গোধূলির আলোয় পোর্ট্রেট" class="w-full h-full object-cover object-top">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">পোর্ট্রেট</span>
                    <h3 class="text-xl font-semibold text-white">গোধূলির আলোয় পোর্ট্রেট</h3>
                    <p class="text-xs text-zinc-300 mt-1">ন্যাচারাল লাইট এডিটোরিয়াল সিরিজ</p>
                </div>
            </div>

            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="cinematic"
                 data-title="নিয়ন রাতের শহর"
                 data-subtitle="সিনেমাটিক নাইট স্টিল &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Cinematic+Night'"
                     alt="নিয়ন রাতের শহর" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">সিনেমাটিক</span>
                    <h3 class="text-xl font-semibold text-white">নিয়ন রাতের শহর</h3>
                    <p class="text-xs text-zinc-300 mt-1">মুডি কালার গ্রেডিং ও স্ট্রিট ভিজ্যুয়াল</p>
                </div>
            </div>

            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="event"
                 data-title="উৎসব ও ইভেন্টের মুহূর্ত"
                 data-subtitle="ইভেন্ট ফটোগ্রাফি &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Event+Story'"
                     alt="উৎসব ও ইভেন্টের মুহূর্ত" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">ইভেন্ট</span>
                    <h3 class="text-xl font-semibold text-white">উৎসব ও ইভেন্টের মুহূর্ত</h3>
                    <p class="text-xs text-zinc-300 mt-1">আবেগঘন মুহূর্তের কভারেজ</p>
                </div>
            </div>

            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="cinematic"
                 data-title="কুয়াশাচ্ছন্ন পাহাড়ি পথ"
                 data-subtitle="সিনেমাটিক ট্রাভেল স্টিল &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Misty+Peaks'"
                     alt="কুয়াশাচ্ছন্ন পাহাড়ি পথ" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">সিনেমাটিক</span>
                    <h3 class="text-xl font-semibold text-white">কুয়াশাচ্ছন্ন পাহাড়ি পথ</h3>
                    <p class="text-xs text-zinc-300 mt-1">অ্যাটমোস্ফিয়ারিক ল্যান্ডস্কেপ</p>
                </div>
            </div>

            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="portrait"
                 data-title="ছায়া ও আলোর স্টুডিও ফ্রেম"
                 data-subtitle="স্টুডিও পোর্ট্রেট &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Studio+Portrait'"
                     alt="ছায়া ও আলোর স্টুডিও ফ্রেম" class="w-full h-full object-cover object-top">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">পোর্ট্রেট</span>
                    <h3 class="text-xl font-semibold text-white">ছায়া ও আলোর স্টুডিও ফ্রেম</h3>
                    <p class="text-xs text-zinc-300 mt-1">ড্রামাটিক কনট্রাস্ট পোর্ট্রেট</p>
                </div>
            </div>

            <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" 
                 data-category="event"
                 data-title="লাইভ কনসার্ট পারফরম্যান্স"
                 data-subtitle="লাইভ ইভেন্ট &bull; MSH Lens Art"
                 data-img="https://images.unsplash.com/photo-1501281668745-f7f57925c3b4?auto=format&fit=crop&w=1200&q=85">
                <img src="https://images.unsplash.com/photo-1501281668745-f7f57925c3b4?auto=format&fit=crop&w=800&q=80" 
                     onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=Live+Event'"
                     alt="লাইভ কনসার্ট পারফরম্যান্স" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                    <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">ইভেন্ট</span>
                    <h3 class="text-xl font-semibold text-white">লাইভ কনসার্ট পারফরম্যান্স</h3>
                    <p class="text-xs text-zinc-300 mt-1">স্টেজ লাইট ও হাই-এনার্জি কভারেজ</p>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. SHOWREEL SECTION -->
    <section id="projects" class="py-24 bg-charcoal/50 border-y border-white/5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal">
                <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-2">Cinematography Showreel</p>
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white mb-4">সিনেমাটিক প্রজেক্ট ও রিলস</h2>
                <p class="text-zinc-400 text-sm sm:text-base">গতি, সাউন্ড ডিজাইন এবং সিনেমাটিক কালার গ্রেডিংয়ের মাধ্যমে নির্মিত আমাদের বিশেষ ভিডিও প্রজেক্ট।</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                <!-- Showreel Video Card 1 -->
                <div class="video-card group relative rounded-2xl overflow-hidden bg-obsidian border border-white/10 aspect-video cursor-pointer reveal"
                     data-video-title="MSH LENS ART — অফিসিয়াল সিনেমাটোগ্রাফি শোরিল"
                     data-video-desc="৪কে রেজোলিউশনে ধারণকৃত ট্রাভেল, পোর্ট্রেট ও ইভেন্ট ফিল্মের নির্বাচিত দৃশ্যমালা।"
                     data-video-poster="https://images.unsplash.com/photo-1536440136628-849c177e76a1?auto=format&fit=crop&w=1400&q=85"
                     data-embed-url="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerBlazes.mp4"
                     data-video-duration="01:00">
                    <img src="https://images.unsplash.com/photo-1536440136628-849c177e76a1?auto=format&fit=crop&w=1200&q=80" 
                         onerror="this.src='https://placehold.co/1280x720/0b0708/e11d48?text=Cinematography+Showreel'"
                         alt="Official Cinematography Showreel" 
                         class="w-full h-full object-cover opacity-75 group-hover:scale-105 group-hover:opacity-60 transition-all duration-700">
                    
                    <div class="absolute inset-x-0 top-0 h-4 bg-black/80"></div>
                    <div class="absolute inset-x-0 bottom-0 h-4 bg-black/80"></div>

                    <div class="absolute inset-0 flex items-center justify-center">
                        <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full bg-gradient-to-r from-velvetRed to-reelsPink text-white flex items-center justify-center pl-1 shadow-[0_0_30px_rgba(225,29,72,0.5)] group-hover:scale-110 transition-transform duration-300">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 fill-current" viewBox="0 0 24 24">
                                <path d="M8 5v14l11-7z"/>
                            </svg>
                        </div>
                    </div>

                    <div class="absolute bottom-6 left-6 right-6 flex items-end justify-between">
                        <div>
                            <span class="inline-block px-2.5 py-0.5 rounded bg-black/70 border border-velvetRed/40 text-[11px] font-sans text-pink-300 mb-2">4K MASTER REEL</span>
                            <h3 class="text-lg sm:text-xl font-bold text-white">অফিসিয়াল সিনেমাটোগ্রাফি শোরিল</h3>
                        </div>
                        <span class="text-xs font-sans text-zinc-300 bg-black/70 px-3 py-1 rounded-full border border-white/10">01:00</span>
                    </div>
                </div>

                <!-- Showreel Video Card 2 -->
                <div class="video-card group relative rounded-2xl overflow-hidden bg-obsidian border border-white/10 aspect-video cursor-pointer reveal"
                     data-video-title="গল্পের খোঁজে — শর্ট রিলস ও কমার্শিয়াল ভিজ্যুয়াল"
                     data-video-desc="ইনস্টাগ্রাম ট্রেন্ডিং রিলস ও আধুনিক কমার্শিয়াল ভিডিওর একটি বিশেষ সংকলন।"
                     data-video-poster="https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&w=1400&q=85"
                     data-embed-url="https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerEscapes.mp4"
                     data-video-duration="01:15">
                    <img src="https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&w=1200&q=80" 
                         onerror="this.src='https://placehold.co/1280x720/0b0708/e11d48?text=Reels+Commercial'"
                         alt="Reels and Commercial Visuals" 
                         class="w-full h-full object-cover opacity-75 group-hover:scale-105 group-hover:opacity-60 transition-all duration-700">
                    
                    <div class="absolute inset-x-0 top-0 h-4 bg-black/80"></div>
                    <div class="absolute inset-x-0 bottom-0 h-4 bg-black/80"></div>

                    <div class="absolute inset-0 flex items-center justify-center">
                        <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full bg-white/15 backdrop-blur-md border border-white/30 text-white flex items-center justify-center pl-1 group-hover:bg-velvetRed group-hover:border-velvetRed transition-all duration-300">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 fill-current" viewBox="0 0 24 24">
                                <path d="M8 5v14l11-7z"/>
                            </svg>
                        </div>
                    </div>

                    <div class="absolute bottom-6 left-6 right-6 flex items-end justify-between">
                        <div>
                            <span class="inline-block px-2.5 py-0.5 rounded bg-black/70 border border-white/20 text-[11px] font-sans text-pink-200 mb-2">REELS & VISUALS</span>
                            <h3 class="text-lg sm:text-xl font-bold text-white">গল্পের খোঁজে — ব্র্যান্ড রিলস</h3>
                        </div>
                        <span class="text-xs font-sans text-zinc-300 bg-black/70 px-3 py-1 rounded-full border border-white/10">01:15</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. ABOUT CREATOR SECTION -->
    <section id="about" class="py-24 bg-charcoal/40 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                <div class="lg:col-span-5 reveal">
                    <div class="relative rounded-2xl overflow-hidden border border-white/10 bg-obsidian aspect-[4/5] max-w-md mx-auto">
                        <img src="https://images.unsplash.com/photo-1554048612-b6a482bc67e5?auto=format&fit=crop&w=900&q=85" 
                             onerror="this.src='https://placehold.co/800x1000/140c0e/e11d48?text=MSH+Creator'"
                             alt="MSH Lens Art Creator" 
                             class="w-full h-full object-cover object-top">
                        <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-transparent to-transparent"></div>
                        <div class="absolute bottom-5 left-5 right-5 p-4 rounded-xl bg-obsidian/85 backdrop-blur-md border border-white/10">
                            <p class="font-editorial text-sm tracking-widest text-reelsPink">MSH LENS ART</p>
                            <p class="text-xs text-zinc-300 mt-0.5">ভিজ্যুয়াল আর্টিস্ট ও সিনেমাটোগ্রাফার</p>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7 reveal">
                    <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-3">Behind The Lens</p>
                    <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white leading-tight mb-6">
                        প্রতিটি ফ্রেমে লুকিয়ে থাকে একটি অনন্য গল্প
                    </h2>
                    <p class="text-zinc-300 text-base sm:text-lg leading-relaxed mb-5 font-light">
                        <strong class="text-white font-semibold">MSH LENS ART</strong>-এর লক্ষ্য সাধারণ মুহূর্তগুলোকে অসাধারণ সিনেমাটিক রূপ দেওয়া। একটি ভালো ছবি বা ভিডিও কেবল দৃশ্য ধারণ করে না, তা দর্শকের মন জয় করে।
                    </p>
                    <p class="text-zinc-400 text-sm sm:text-base leading-relaxed mb-8">
                        নিখুঁত ফ্রেম নির্বাচন, আলোর ব্যবহার এবং আধুনিক ট্রেন্ডিং কালার গ্রেডিংয়ের মাধ্যমে আমরা প্রতিটি প্রজেক্টকে এক অনন্য স্টাইলে ফুটিয়ে তুলি।
                    </p>

                    <div class="grid grid-cols-3 gap-4 pt-6 border-t border-white/10">
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">150+</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">সম্পন্ন প্রজেক্ট</p>
                        </div>
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">4K</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">সিনেমাটিক কোয়ালিটি</p>
                        </div>
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">100%</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">ক্রিয়েটিভ প্যাশন</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. CONTACT & DIRECT SOCIAL BOOKING SECTION -->
    <section id="contact" class="py-24 sm:py-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="rounded-3xl bg-charcoal border border-white/10 p-6 sm:p-12 lg:p-16 relative overflow-hidden reveal">
            <div class="absolute -top-24 -right-24 w-72 h-72 bg-velvetRed/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 relative z-10">
                <!-- Left: Social Direct Buttons -->
                <div class="lg:col-span-5 flex flex-col justify-between">
                    <div>
                        <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-3">Direct Contact</p>
                        <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">আমাদের সাথে সরাসরি যুক্ত হোন</h2>
                        <p class="text-zinc-400 text-sm sm:text-base leading-relaxed mb-8">
                            বুকিং, কোনো প্রশ্ন বা আলোচনার জন্য নিচের বাটনে ক্লিক করে সরাসরি আমাদের ফেসবুক বা ইনস্টাগ্রামে মেসেজ পাঠান।
                        </p>

                        <div class="space-y-4">
                            <!-- Instagram Direct Link -->
                            <a href="https://www.instagram.com/mshlensart" target="_blank" rel="noopener noreferrer" 
                               class="flex items-center gap-4 p-4 rounded-2xl bg-obsidian/90 border border-white/10 hover:border-reelsPink transition-all group shadow-md">
                                <div class="w-12 h-12 rounded-xl bg-gradient-to-tr from-yellow-500 via-pink-500 to-purple-600 text-white flex items-center justify-center shrink-0">
                                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <rect x="2" y="2" width="20" height="20" rx="5" ry="5" stroke-width="2"/>
                                        <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37z" stroke-width="2"/>
                                        <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" stroke-width="2.5"/>
                                    </svg>
                                </div>
                                <div>
                                    <p class="text-xs text-pink-300/80 uppercase font-sans tracking-wider">Instagram Handle</p>
                                    <p class="text-base font-semibold text-white group-hover:text-reelsPink transition-colors">@mshlensart</p>
                                </div>
                            </a>

                            <!-- Facebook Direct Link -->
                            <a href="https://www.facebook.com/share/1LAboVL8uX/" target="_blank" rel="noopener noreferrer" 
                               class="flex items-center gap-4 p-4 rounded-2xl bg-obsidian/90 border border-white/10 hover:border-blue-500 transition-all group shadow-md">
                                <div class="w-12 h-12 rounded-xl bg-blue-600 text-white flex items-center justify-center shrink-0">
                                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                                        <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
                                    </svg>
                                </div>
                                <div>
                                    <p class="text-xs text-blue-300/80 uppercase font-sans tracking-wider">Facebook Page</p>
                                    <p class="text-base font-semibold text-white group-hover:text-blue-400 transition-colors">MSH Lens Art</p>
                                </div>
                            </a>

                            <!-- WhatsApp Direct Contact -->
                            <a href="https://wa.me/8801868942746" target="_blank" rel="noopener noreferrer" 
                               class="flex items-center gap-4 p-4 rounded-2xl bg-obsidian/90 border border-white/10 hover:border-emerald-500 transition-all group shadow-md">
                                <div class="w-12 h-12 rounded-xl bg-emerald-600 text-white flex items-center justify-center shrink-0">
                                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                                        <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981z"/>
                                    </svg>
                                </div>
                                <div>
                                    <p class="text-xs text-emerald-300/80 uppercase font-sans tracking-wider">Direct WhatsApp</p>
                                    <p class="text-base font-semibold text-white group-hover:text-emerald-400 transition-colors">+880 1868-942746</p>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Right: Quick Interactive Booking Form -->
                <div class="lg:col-span-7">
                    <form id="booking-form" class="space-y-5 bg-obsidian/70 p-6 sm:p-8 rounded-2xl border border-white/10 shadow-xl">
                        <h3 class="text-lg font-bold text-white mb-2">অনলাইন বুকিং রিকোয়েস্ট</h3>
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                            <div>
                                <label for="client-name" class="block text-xs font-medium text-zinc-300 mb-2">আপনার নাম *</label>
                                <input type="text" id="client-name" required placeholder="আপনার নাম লিখুন"
                                       class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            </div>
                            <div>
                                <label for="client-contact" class="block text-xs font-medium text-zinc-300 mb-2">ফোন নম্বর *</label>
                                <input type="text" id="client-contact" required placeholder="০১XXXXXXXXX"
                                       class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                            <div>
                                <label for="service-type" class="block text-xs font-medium text-zinc-300 mb-2">সেবার ধরন</label>
                                <select id="service-type" 
                                        class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white text-sm focus:outline-none focus:border-velvetRed transition-colors">
                                    <option value="পোর্ট্রেট ফটোগ্রাফি">পোর্ট্রেট ফটোগ্রাফি</option>
                                    <option value="সিনেমাটিক ভিডিওগ্রাফি">সিনেমাটিক ভিডিওগ্রাফি</option>
                                    <option value="ইভেন্ট কভারেজ">ইভেন্ট কভারেজ</option>
                                    <option value="ব্র্যান্ড ভিজ্যুয়ালস & রিলস">ব্র্যান্ড ভিজ্যুয়ালস & রিলস</option>
                                </select>
                            </div>
                            <div>
                                <label for="event-date" class="block text-xs font-medium text-zinc-300 mb-2">সম্ভাব্য তারিখ</label>
                                <input type="date" id="event-date"
                                       class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-zinc-200 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            </div>
                        </div>

                        <div>
                            <label for="project-details" class="block text-xs font-medium text-zinc-300 mb-2">বিস্তারিত বিবরণ (যদি থাকে)</label>
                            <textarea id="project-details" rows="3" placeholder="শুটিং লোকেশন বা বিশেষ চাহিদা থাকলে লিখুন..."
                                      class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors"></textarea>
                        </div>

                        <button type="submit" 
                                class="w-full py-4 rounded-xl bg-gradient-to-r from-velvetRed to-reelsPink text-white font-semibold text-base tracking-wide hover:opacity-95 transition-all duration-300 shadow-[0_0_20px_rgba(225,29,72,0.3)]">
                            মেসেজ ও লিঙ্ক জেনারেট করুন
                        </button>

                        <!-- Generated Quick Send Actions -->
                        <div id="form-feedback" class="hidden rounded-xl p-5 bg-obsidian border border-velvetRed/40 space-y-4">
                            <div class="flex items-start gap-3">
                                <svg class="w-5 h-5 text-reelsPink shrink-0 mt-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                                </svg>
                                <div>
                                    <p class="font-semibold text-white text-sm">আপনার বুকিং তথ্য তৈরি হয়েছে!</p>
                                    <p id="feedback-summary" class="text-xs text-zinc-300 mt-1 whitespace-pre-line font-mono bg-charcoal p-3 rounded-lg border border-white/5"></p>
                                </div>
                            </div>
                            
                            <p class="text-xs text-zinc-400 font-medium">নিচের যেকোনো বাটনে চাপ দিয়ে সরাসরি মেসেজটি পাঠান:</p>
                            
                            <div class="flex flex-col sm:flex-row gap-3">
                                <a id="wa-direct-link" href="#" target="_blank" rel="noopener noreferrer" 
                                   class="flex-1 text-center py-2.5 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white text-xs font-semibold transition-colors flex items-center justify-center gap-2">
                                    WhatsApp-এ পাঠান
                                </a>
                                <a id="fb-direct-link" href="https://www.facebook.com/share/1LAboVL8uX/" target="_blank" rel="noopener noreferrer" 
                                   class="flex-1 text-center py-2.5 rounded-xl bg-blue-600 hover:bg-blue-500 text-white text-xs font-semibold transition-colors flex items-center justify-center gap-2">
                                    Facebook-এ পাঠান
                                </a>
                                <button type="button" id="copy-summary-btn" 
                                        class="py-2.5 px-4 rounded-xl bg-white/10 hover:bg-white/20 text-white text-xs font-semibold transition-colors">
                                    কপি করুন
                                </button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="border-t border-white/10 py-10 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-4 text-center sm:text-left">
            <div>
                <span class="font-editorial text-base font-bold tracking-[0.2em] text-white">
                    MSH <span class="text-crimson-pink">LENS ART</span>
                </span>
                <p class="text-xs text-zinc-500 mt-1">&copy; ২০২৬ MSH Lens Art (@mshlensart). সর্বস্বত্ব সংরক্ষিত।</p>
            </div>
            <div class="flex items-center gap-6 text-xs text-zinc-400">
                <a href="#home" class="hover:text-velvetRed transition-colors">হোম</a>
                <a href="#services" class="hover:text-velvetRed transition-colors">সেবা</a>
                <a href="#gallery" class="hover:text-velvetRed transition-colors">গ্যালারি</a>
                <a href="https://www.instagram.com/mshlensart" target="_blank" rel="noopener noreferrer" class="text-reelsPink hover:underline font-sans">@mshlensart</a>
            </div>
        </div>
    </footer>

    <!-- LIGHTBOX MODAL -->
    <div id="lightbox-modal" class="fixed inset-0 z-50 hidden bg-black/95 backdrop-blur-xl flex items-center justify-center p-4 sm:p-8">
        <button type="button" id="close-lightbox" aria-label="বন্ধ করুন" class="absolute top-5 right-5 sm:top-8 sm:right-8 w-11 h-11 rounded-full bg-white/10 hover:bg-velvetRed text-white flex items-center justify-center transition-colors z-10">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
            </svg>
        </button>

        <div class="max-w-4xl w-full flex flex-col items-center">
            <div class="relative rounded-2xl overflow-hidden border border-white/15 bg-charcoal max-h-[75vh]">
                <img id="lightbox-img" src="" alt="" class="max-h-[75vh] w-auto object-contain mx-auto">
            </div>
            <div class="text-center mt-5">
                <h3 id="lightbox-title" class="text-xl sm:text-2xl font-bold text-white"></h3>
                <p id="lightbox-subtitle" class="text-xs sm:text-sm text-reelsPink font-sans mt-1"></p>
            </div>
        </div>
    </div>

    <!-- VIDEO MODAL PLAYER -->
    <div id="video-modal" class="fixed inset-0 z-50 hidden bg-black/95 backdrop-blur-xl flex items-center justify-center p-4 sm:p-8">
        <button type="button" id="close-video-modal" aria-label="ভিডিও বন্ধ করুন" class="absolute top-5 right-5 sm:top-8 sm:right-8 w-11 h-11 rounded-full bg-white/10 hover:bg-velvetRed text-white flex items-center justify-center transition-colors z-10">
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
            </svg>
        </button>

        <div class="max-w-4xl w-full bg-charcoal rounded-2xl overflow-hidden border border-white/15 shadow-2xl">
            <div class="relative aspect-video bg-black">
                <video id="video-player" class="w-full h-full object-cover" controls playsinline preload="metadata"></video>
            </div>
            <div class="p-6 flex flex-col sm:flex-row sm:items-center justify-between gap-4">
                <div>
                    <h3 id="video-modal-title" class="text-xl font-bold text-white"></h3>
                    <p id="video-modal-desc" class="text-sm text-zinc-400 mt-1"></p>
                </div>
                <span id="video-modal-duration" class="text-xs font-sans text-reelsPink bg-velvetRed/10 border border-velvetRed/30 px-3 py-1 rounded-full self-start sm:self-center"></span>
            </div>
        </div>
    </div>

    <!-- INTERACTIVE JAVASCRIPT -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // 1. Mobile Menu Toggle
            const mobileMenuBtn = document.getElementById('mobile-menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            const iconOpen = document.getElementById('menu-icon-open');
            const iconClose = document.getElementById('menu-icon-close');
            const mobileLinks = document.querySelectorAll('.mobile-link');

            function toggleMobileMenu() {
                const isHidden = mobileMenu.classList.contains('hidden');
                mobileMenu.classList.toggle('hidden');
                iconOpen.classList.toggle('hidden', isHidden);
                iconClose.classList.toggle('hidden', !isHidden);
            }

            mobileMenuBtn.addEventListener('click', toggleMobileMenu);
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    if (!mobileMenu.classList.contains('hidden')) toggleMobileMenu();
                });
            });

            // 2. Portfolio Category Filtering
            const filterBtns = document.querySelectorAll('.filter-btn');
            const galleryCards = document.querySelectorAll('.gallery-card');

            filterBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    filterBtns.forEach(b => {
                        b.classList.remove('bg-gradient-to-r', 'from-velvetRed', 'to-reelsPink', 'text-white');
                        b.classList.add('bg-charcoal', 'text-zinc-300', 'border', 'border-white/10');
                    });
                    btn.classList.remove('bg-charcoal', 'text-zinc-300', 'border', 'border-white/10');
                    btn.classList.add('bg-gradient-to-r', 'from-velvetRed', 'to-reelsPink', 'text-white');

                    const filterValue = btn.getAttribute('data-filter');

                    galleryCards.forEach(card => {
                        const category = card.getAttribute('data-category');
                        const matches = filterValue === 'all' || category === filterValue;

                        if (matches) {
                            card.classList.remove('hidden');
                            card.classList.add('active');
                            requestAnimationFrame(() => {
                                card.style.opacity = '1';
                                card.style.transform = 'translateY(0) scale(1)';
                            });
                        } else {
                            card.style.opacity = '0';
                            card.style.transform = 'scale(0.96)';
                            setTimeout(() => {
                                if (!card.style.opacity || card.style.opacity === '0') {
                                    card.classList.add('hidden');
                                }
                            }, 220);
                        }
                    });
                });
            });

            // 3. Lightbox Modal
            const lightboxModal = document.getElementById('lightbox-modal');
            const lightboxImg = document.getElementById('lightbox-img');
            const lightboxTitle = document.getElementById('lightbox-title');
            const lightboxSubtitle = document.getElementById('lightbox-subtitle');
            const closeLightboxBtn = document.getElementById('close-lightbox');

            galleryCards.forEach(card => {
                card.addEventListener('click', () => {
                    lightboxImg.src = card.getAttribute('data-img');
                    lightboxImg.alt = card.getAttribute('data-title');
                    lightboxTitle.textContent = card.getAttribute('data-title');
                    lightboxSubtitle.textContent = card.getAttribute('data-subtitle');
                    lightboxModal.classList.remove('hidden');
                    document.body.style.overflow = 'hidden';
                });
            });

            function closeLightbox() {
                lightboxModal.classList.add('hidden');
                lightboxImg.src = '';
                document.body.style.overflow = '';
            }

            closeLightboxBtn.addEventListener('click', closeLightbox);
            lightboxModal.addEventListener('click', (e) => {
                if (e.target === lightboxModal) closeLightbox();
            });

            // 4. Video Modal Showreel Player
            const videoCards = document.querySelectorAll('.video-card');
            const videoModal = document.getElementById('video-modal');
            const videoPlayer = document.getElementById('video-player');
            const videoModalTitle = document.getElementById('video-modal-title');
            const videoModalDesc = document.getElementById('video-modal-desc');
            const videoModalDuration = document.getElementById('video-modal-duration');
            const closeVideoModalBtn = document.getElementById('close-video-modal');

            videoCards.forEach(card => {
                card.addEventListener('click', () => {
                    const videoUrl = card.getAttribute('data-embed-url');
                    const posterUrl = card.getAttribute('data-video-poster');

                    videoModalTitle.textContent = card.getAttribute('data-video-title');
                    videoModalDesc.textContent = card.getAttribute('data-video-desc');
                    videoModalDuration.textContent = `Duration: ${card.getAttribute('data-video-duration')}`;

                    videoPlayer.poster = posterUrl;
                    videoPlayer.src = videoUrl;
                    videoModal.classList.remove('hidden');
                    document.body.style.overflow = 'hidden';
                    videoPlayer.play().catch(() => {});
                });
            });

            function closeVideoModal() {
                videoPlayer.pause();
                videoPlayer.removeAttribute('src');
                videoPlayer.load();
                videoModal.classList.add('hidden');
                document.body.style.overflow = '';
            }

            closeVideoModalBtn.addEventListener('click', closeVideoModal);
            videoModal.addEventListener('click', (e) => {
                if (e.target === videoModal) closeVideoModal();
            });

            document.addEventListener('keydown', (e) => {
                if (e.key === 'Escape') {
                    closeLightbox();
                    closeVideoModal();
                }
            });

            // 5. Booking Form Message & Direct WhatsApp Action
            const bookingForm = document.getElementById('booking-form');
            const formFeedback = document.getElementById('form-feedback');
            const feedbackSummary = document.getElementById('feedback-summary');
            const copySummaryBtn = document.getElementById('copy-summary-btn');
            const waDirectLink = document.getElementById('wa-direct-link');

            bookingForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const name = document.getElementById('client-name').value.trim();
                const contact = document.getElementById('client-contact').value.trim();
                const service = document.getElementById('service-type').value;
                const date = document.getElementById('event-date').value || 'নির্ধারিত নয়';
                const details = document.getElementById('project-details').value.trim() || 'নেই';

                const summaryText = `হ্যালো MSH LENS ART,\nআমি বুকিংয়ের জন্য তথ্য পাঠাচ্ছি:\n- নাম: ${name}\n- ফোন: ${contact}\n- সেবা: ${service}\n- তারিখ: ${date}\n- বিস্তারিত: ${details}`;
                feedbackSummary.textContent = summaryText;

                // WhatsApp Direct Link Setup
                const waEncodedText = encodeURIComponent(summaryText);
                waDirectLink.href = `https://wa.me/8801868942746?text=${waEncodedText}`;

                // Copy Action
                copySummaryBtn.textContent = 'কপি করুন';
                copySummaryBtn.onclick = () => {
                    navigator.clipboard?.writeText(summaryText).then(() => {
                        copySummaryBtn.textContent = 'কপি হয়েছে!';
                    }).catch(() => {});
                };

                formFeedback.classList.remove('hidden');
            });

            // 6. Smooth Scroll Observer
            const revealElements = document.querySelectorAll('.reveal');
            const revealObserver = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('active');
                        revealObserver.unobserve(entry.target);
                    }
                });
            }, { threshold: 0.1 });

            revealElements.forEach(el => revealObserver.observe(el));
        });
    </script>
</body>
</html>
