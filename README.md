<MSH Lens Art>
<html lang="bn" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSH LENS ART | ফটোগ্রাফি ও সিনেমাটোগ্রাফি পোর্টফোলিও</title>
    <meta name="description" content="MSH LENS ART — আপনার প্রতিটি মুহূর্তকে সিনেমাটিক গল্পে রূপ দিই। পোর্ট্রেট ফটোগ্রাফি, সিনেমাটিক ভিডিওগ্রাফি, ইভেন্ট কভারেজ ও ব্র্যান্ড রিলস। এখনই বুকিং করুন।">
    <meta name="theme-color" content="#0b0708">

    <!-- Social share preview (ছবিটি পরে আপনার নিজের একটি সেরা ছবির লিঙ্ক দিয়ে বদলে নিন) -->
    <meta property="og:type" content="website">
    <meta property="og:locale" content="bn_BD">
    <meta property="og:site_name" content="MSH LENS ART">
    <meta property="og:title" content="MSH LENS ART | মুহূর্তগুলোকে সিনেমাটিক গল্পে রূপান্তর">
    <meta property="og:description" content="পোর্ট্রেট, সিনেমাটিক ভিডিও, ইভেন্ট কভারেজ ও ব্র্যান্ড রিলস — আপনার গল্প আমাদের ফ্রেমে।">
    <meta property="og:image" content="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?auto=format&fit=crop&w=1200&q=80">
    <meta name="twitter:card" content="summary_large_image">

    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 24 24' fill='none' stroke='%23e11d48' stroke-width='1.8'%3E%3Ccircle cx='12' cy='12' r='9'/%3E%3Ccircle cx='12' cy='12' r='3'/%3E%3Cpath d='M12 3v3M12 18v3M3 12h3M18 12h3'/%3E%3C/svg%3E">

    <!-- Structured data for Google -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "ProfessionalService",
      "name": "MSH LENS ART",
      "description": "ফটোগ্রাফি ও সিনেমাটোগ্রাফি সেবা — পোর্ট্রেট, ইভেন্ট, সিনেমাটিক ভিডিও ও ব্র্যান্ড রিলস",
      "email": "mshlensart@gmail.com",
      "telephone": "+8801868942746",
      "sameAs": [
        "https://www.instagram.com/mshlensart",
        "https://www.facebook.com/share/1LAboVL8uX/"
      ]
    }
    </script>

    <!-- Google Fonts: Hind Siliguri, Cinzel, Montserrat -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700;800&family=Hind+Siliguri:wght@400;500;600;700&family=Montserrat:wght@400;500;600;700&display=swap" rel="stylesheet">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

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
        html { scroll-padding-top: 80px; }
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

        /* ---------- Booking slip (রিকোয়েস্ট স্লিপ) ---------- */
        #slip-card { -webkit-print-color-adjust: exact; print-color-adjust: exact; }
        .slip-row {
            display: flex; justify-content: space-between; gap: 14px;
            padding: 9px 0; border-bottom: 1px dashed rgba(255,255,255,.10);
            font-size: 14px; line-height: 1.5;
        }
        .slip-row:last-child { border-bottom: 0; }
        .slip-row .k { color: #f9a8d4; flex-shrink: 0; }
        .slip-row .v { color: #fff; text-align: right; font-weight: 500; word-break: break-word; max-width: 62%; }
        .slip-row .v.small { font-size: 11.5px; font-weight: 400; color: #d4d4d8; }

        @media print {
            body * { visibility: hidden !important; }
            #slip-modal, #slip-modal * { visibility: visible !important; }
            #slip-modal { position: absolute !important; inset: 0 auto auto 0 !important; width: 100%; background: #fff !important; overflow: visible !important; display: block !important; }
            #slip-actions, #slip-close, .film-grain { display: none !important; }
            #slip-card { margin: 0 auto; box-shadow: none !important; }
        }
    </style>
</head>
<body class="antialiased selection:bg-velvetRed/30 selection:text-pink-200">

    <div class="film-grain"></div>

    <!-- 1. NAVIGATION BAR -->
    <header id="navbar" class="fixed top-0 left-0 right-0 z-50 glass-nav">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
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

                <nav class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">হোম</a>
                    <a href="#services" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">সেবা</a>
                    <a href="#gallery" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">গ্যালারি</a>
                    <a href="#projects" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">শো-রিল</a>
                    <a href="#about" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">আমার পরিচয়</a>
                    <a href="#contact" class="text-sm font-medium text-zinc-300 hover:text-velvetRed transition-colors">যোগাযোগ</a>
                </nav>

                <div class="hidden md:flex items-center gap-4">
                    <a href="#contact" class="px-5 py-2.5 rounded-full text-xs font-semibold tracking-wider uppercase border border-velvetRed text-pink-100 hover:bg-velvetRed hover:text-white transition-all duration-300 shadow-[0_0_20px_rgba(225,29,72,0.3)]">
                        বুকিং করুন
                    </a>
                </div>

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

        <div id="mobile-menu" class="hidden md:hidden bg-obsidian/95 backdrop-blur-xl border-b border-velvetRed/20 px-6 pt-3 pb-6 space-y-3">
            <a href="#home" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">হোম</a>
            <a href="#services" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">সেবা</a>
            <a href="#gallery" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-white border-b border-white/5">গ্যালারি</a>
            <a href="#projects" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">শো-রিল</a>
            <a href="#about" class="mobile-link block py-2.5 text-base font-medium text-zinc-200 hover:text-velvetRed border-b border-white/5">আমার পরিচয়</a>
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
                alt="MSH LENS ART সিনেমাটিক ব্যাকগ্রাউন্ড"
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

            <h1 class="text-3xl sm:text-5xl md:text-6xl lg:text-7xl font-bold tracking-tight leading-[1.25] mb-6 animate-fade-in-up" style="animation-delay: 0.1s;">
                <span class="font-editorial block text-xl sm:text-2xl md:text-3xl tracking-[0.28em] text-crimson-pink mb-3 font-semibold">
                    MSH LENS ART
                </span>
                <span class="text-white">আপনার প্রতিটি মুহূর্ত হোক একটি <span class="text-crimson-pink">সিনেমা</span></span>
            </h1>

            <p class="max-w-2xl mx-auto text-base sm:text-lg md:text-xl text-zinc-300 font-light leading-relaxed mb-10 animate-fade-in-up" style="animation-delay: 0.2s;">
                একটি হাসি, একটি চাহনি, এক ফালি সোনালি আলো — ছোট ছোট এই মুহূর্তগুলোই জীবনের সবচেয়ে সুন্দর গল্প। আমরা সেগুলোকে ফ্রেমে বন্দি করি, যেন বছর পরেও ছবিটা দেখলে মন আবার সেই দিনে ফিরে যায়।
            </p>

            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 sm:gap-5 animate-fade-in-up" style="animation-delay: 0.3s;">
                <a href="#contact" class="w-full sm:w-auto px-8 py-4 rounded-full bg-gradient-to-r from-velvetRed to-reelsPink text-white font-semibold text-base tracking-wide hover:opacity-90 transition-all duration-300 shadow-[0_0_30px_rgba(225,29,72,0.4)] flex items-center justify-center gap-2">
                    <span>আপনার গল্প বুক করুন</span>
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                    </svg>
                </a>
                <a href="#gallery" class="w-full sm:w-auto px-8 py-4 rounded-full bg-white/[0.05] hover:bg-white/[0.1] text-white border border-white/15 backdrop-blur-md font-medium text-base tracking-wide transition-all duration-300">
                    আমাদের কাজ দেখুন
                </a>
            </div>
        </div>

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
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white">যে গল্পগুলো আমরা বলি</h2>
            </div>
            <p class="text-zinc-400 max-w-md text-sm sm:text-base leading-relaxed">
                আপনার স্বপ্নের ফ্রেমটা কেমন? আমরা মন দিয়ে শুনি, ভাবি — তারপর আলো আর রঙের জাদুতে সেটাকে সত্যি করে তুলি।
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
                        আপনি যেমন, ঠিক তেমনই — তবে আরও উজ্জ্বল, আরও আত্মবিশ্বাসী। আলো-ছায়ার ছোঁয়ায় আপনার ব্যক্তিত্বকে ফুটিয়ে তোলে ড্রামাটিক পোর্ট্রেট।
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
                        প্রতিটি ফ্রেম যেন সিনেমার একেকটি দৃশ্য। ৪কে কোয়ালিটি, মসৃণ গিম্বল শট আর ফিল্ম-গ্রেড কালারে আপনার গল্প হয়ে উঠুক পর্দার গল্প।
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
                        বিয়ের আনন্দ, প্রিয়জনের হাসি, উৎসবের উচ্ছ্বাস — যে মুহূর্ত আর ফিরে আসে না, সেগুলোকেই আমরা যত্নে তুলে রাখি আজীবনের স্মৃতি করে।
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
                        স্ক্রল থামিয়ে দেওয়ার মতো রিলস! ট্রেন্ডি, আকর্ষণীয় ভিজ্যুয়ালে আপনার ব্র্যান্ড বসে যাক মানুষের মনে।
                    </p>
                </div>
                <div class="pt-4 border-t border-white/5 flex items-center justify-between text-xs">
                    <span class="text-reelsPink font-medium">ট্রেন্ডিং রিলস কন্টেন্ট</span>
                    <a href="#contact" class="text-zinc-300 hover:text-velvetRed transition-colors">বুকিং &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. GALLERY SECTION (ছবি বদলাতে নিচের স্ক্রিপ্টে GALLERY তালিকা দেখুন) -->
    <section id="gallery" class="py-24 sm:py-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="flex flex-col md:flex-row md:items-end justify-between mb-14 gap-6 reveal">
            <div>
                <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-2">Selected Works</p>
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white">মন ছুঁয়ে যাওয়া ফ্রেমগুলো</h2>
            </div>

            <div class="flex flex-wrap items-center gap-2 sm:gap-3" id="filter-buttons">
                <button type="button" data-filter="all" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-gradient-to-r from-velvetRed to-reelsPink text-white">সব</button>
                <button type="button" data-filter="portrait" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">পোর্ট্রেট</button>
                <button type="button" data-filter="cinematic" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">সিনেমাটিক</button>
                <button type="button" data-filter="event" class="filter-btn px-5 py-2.5 rounded-full text-sm font-medium transition-all duration-300 bg-charcoal text-zinc-300 border border-white/10 hover:border-velvetRed/50">ইভেন্ট</button>
            </div>
        </div>

        <div id="gallery-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 sm:gap-8"></div>
    </section>

    <!-- 5. SHOWREEL SECTION (ভিডিও বদলাতে নিচের স্ক্রিপ্টে VIDEOS তালিকা দেখুন) -->
    <section id="projects" class="py-24 bg-charcoal/50 border-y border-white/5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16 reveal">
                <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-2">Cinematography Showreel</p>
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-white mb-4">পর্দায় ফুটে ওঠা গল্প</h2>
                <p class="text-zinc-400 text-sm sm:text-base leading-relaxed">আলো, সুর আর রঙের মিশেলে তৈরি আমাদের কিছু প্রিয় কাজ — দেখুন, আর কল্পনা করুন আপনার নিজের গল্পটাও।</p>
            </div>

            <div id="video-grid" class="grid grid-cols-1 lg:grid-cols-2 gap-8"></div>
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
                             alt="MSH Lens Art ক্রিয়েটর"
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
                        প্রতিটি ফ্রেমে লুকিয়ে থাকে <span class="text-crimson-pink">একটি গল্প</span>
                    </h2>
                    <p class="text-zinc-300 text-base sm:text-lg leading-relaxed mb-5 font-light">
                        <strong class="text-white font-semibold">MSH LENS ART</strong>-এ আমরা বিশ্বাস করি, সাধারণ বলে কিছু নেই — প্রতিটি মুহূর্তই অসাধারণ হয়ে ওঠার অপেক্ষায় থাকে। একটি ভালো ছবি শুধু দৃশ্য দেখায় না, হারিয়ে যাওয়া অনুভূতিটাকেও ফিরিয়ে আনে।
                    </p>
                    <p class="text-zinc-400 text-sm sm:text-base leading-relaxed mb-8">
                        নিখুঁত ফ্রেম, আলোর সূক্ষ্ম খেলা আর আধুনিক কালার গ্রেডিংয়ে আমরা আপনার গল্পটাকে দিই এক অনন্য সিনেমাটিক ছোঁয়া — যেন প্রতিবার দেখলেই নতুন করে ভালো লাগে।
                    </p>

                    <div class="grid grid-cols-3 gap-4 pt-6 border-t border-white/10">
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">150+</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">সম্পন্ন প্রজেক্ট</p>
                        </div>
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">4K</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">সিনেমাটিক কোয়ালিটি</p>
                        </div>
                        <div>
                            <p class="font-editorial text-2xl sm:text-3xl font-bold text-crimson-pink">100%</p>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1">ক্রিয়েটিভ প্যাশন</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 7. CONTACT & BOOKING SECTION -->
    <section id="contact" class="py-24 sm:py-32 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="rounded-3xl bg-charcoal border border-white/10 p-6 sm:p-12 lg:p-16 relative overflow-hidden reveal">
            <div class="absolute -top-24 -right-24 w-72 h-72 bg-velvetRed/10 rounded-full blur-3xl pointer-events-none"></div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 relative z-10">
                <!-- Left: Direct contact -->
                <div class="lg:col-span-5 flex flex-col justify-between">
                    <div>
                        <p class="text-xs font-sans uppercase tracking-[0.25em] text-reelsPink mb-3">Let's Create Together</p>
                        <h2 class="text-3xl sm:text-4xl font-bold text-white mb-4">চলুন, আপনার গল্পটা <span class="text-crimson-pink">একসাথে লিখি</span></h2>
                        <p class="text-zinc-400 text-sm sm:text-base leading-relaxed mb-8">
                            একটি মেসেজ, একটি ফর্ম — আর আপনার স্বপ্নের ফ্রেমের পথচলা শুরু। যেভাবে সুবিধা, সেভাবেই আমাদের সাথে কথা বলুন।
                        </p>

                        <div class="space-y-4">
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
                                    <p class="text-xs text-pink-300/80 uppercase font-sans tracking-wider">Instagram</p>
                                    <p class="text-base font-semibold text-white group-hover:text-reelsPink transition-colors">@mshlensart</p>
                                </div>
                            </a>

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

                            <a href="https://wa.me/8801868942746" target="_blank" rel="noopener noreferrer"
                               class="flex items-center gap-4 p-4 rounded-2xl bg-obsidian/90 border border-white/10 hover:border-emerald-500 transition-all group shadow-md">
                                <div class="w-12 h-12 rounded-xl bg-emerald-600 text-white flex items-center justify-center shrink-0">
                                    <svg class="w-6 h-6 fill-current" viewBox="0 0 24 24">
                                        <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981z"/>
                                    </svg>
                                </div>
                                <div>
                                    <p class="text-xs text-emerald-300/80 uppercase font-sans tracking-wider">WhatsApp</p>
                                    <p class="text-base font-semibold text-white group-hover:text-emerald-400 transition-colors">+880 1868-942746</p>
                                </div>
                            </a>

                            <a href="mailto:mshlensart@gmail.com"
                               class="flex items-center gap-4 p-4 rounded-2xl bg-obsidian/90 border border-white/10 hover:border-velvetRed transition-all group shadow-md">
                                <div class="w-12 h-12 rounded-xl bg-velvetRed text-white flex items-center justify-center shrink-0">
                                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <rect x="3" y="5" width="18" height="14" rx="2" stroke-width="1.8"/>
                                        <path d="M3 7l9 6 9-6" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/>
                                    </svg>
                                </div>
                                <div>
                                    <p class="text-xs text-pink-300/80 uppercase font-sans tracking-wider">Email</p>
                                    <p class="text-base font-semibold text-white group-hover:text-reelsPink transition-colors break-all">mshlensart@gmail.com</p>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Right: Booking form -->
                <div class="lg:col-span-7">
                    <form id="booking-form" class="space-y-5 bg-obsidian/70 p-6 sm:p-8 rounded-2xl border border-white/10 shadow-xl">
                        <div>
                            <h3 class="text-xl font-bold text-white">আপনার বুকিং রিকোয়েস্ট ✨</h3>
                            <p class="text-xs sm:text-sm text-zinc-400 mt-1.5 leading-relaxed">ফর্মটি পূরণ করুন — আমরা তথ্য পেয়েই যোগাযোগ করব, আর আপনি পাবেন একটি সুন্দর বুকিং স্লিপ।</p>
                        </div>

                        <!-- স্প্যাম আটকানোর লুকানো ঘর -->
                        <input type="checkbox" id="botcheck" class="hidden" tabindex="-1" autocomplete="off">

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                            <div>
                                <label for="client-name" class="block text-xs font-medium text-zinc-300 mb-2">আপনার নাম <span class="text-velvetRed">*</span></label>
                                <input type="text" id="client-name" required placeholder="আপনার নাম লিখুন" autocomplete="name"
                                       class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            </div>
                            <div>
                                <label for="client-contact" class="block text-xs font-medium text-zinc-300 mb-2">ফোন নম্বর <span class="text-velvetRed">*</span></label>
                                <input type="tel" id="client-contact" required inputmode="tel" placeholder="০১XXXXXXXXX" autocomplete="tel"
                                       pattern="[0-9০-৯+\s\-]{10,16}" title="সঠিক ফোন নম্বর দিন (কমপক্ষে ১০ সংখ্যা)"
                                       class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            </div>
                        </div>

                        <div>
                            <label for="client-email" class="block text-xs font-medium text-zinc-300 mb-2">ইমেইল <span class="text-zinc-500 font-normal">(ঐচ্ছিক)</span></label>
                            <input type="email" id="client-email" placeholder="আপনার ইমেইল (থাকলে)" autocomplete="email"
                                   class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
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

                        <!-- লোকেশন: ডিটেইলস (বাধ্যতামূলক) + গুগল ম্যাপ লিঙ্ক (ঐচ্ছিক) -->
                        <div>
                            <label for="location-details" class="block text-xs font-medium text-zinc-300 mb-2">📍 শুটিং লোকেশন ডিটেইলস <span class="text-velvetRed">*</span></label>
                            <textarea id="location-details" rows="3" required
                                      placeholder="ভেন্যুর নাম, এলাকা ও ল্যান্ডমার্ক লিখুন&#10;যেমন: হোটেল ডিলাক্স, গুলশান ২, ঢাকা (ডিসিসি মার্কেটের পাশে)"
                                      class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors"></textarea>
                        </div>

                        <div>
                            <label for="map-link" class="block text-xs font-medium text-zinc-300 mb-2">🗺️ গুগল ম্যাপ লিঙ্ক <span class="text-zinc-500 font-normal">(ঐচ্ছিক)</span></label>
                            <input type="url" id="map-link" placeholder="https://maps.app.goo.gl/..."
                                   class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors">
                            <div class="flex flex-wrap items-center gap-3 mt-3">
                                <a href="https://www.google.com/maps" target="_blank" rel="noopener noreferrer"
                                   class="inline-flex items-center gap-1.5 px-4 py-2 rounded-full border border-reelsPink/60 text-pink-200 text-xs font-semibold hover:bg-reelsPink hover:text-white transition-colors">
                                    Google Maps খুলুন ↗
                                </a>
                                <span id="map-status" class="text-xs" aria-live="polite"></span>
                            </div>
                            <p class="text-[11px] sm:text-xs text-zinc-500 mt-2 leading-relaxed">
                                Google Maps-এ জায়গাটি খুঁজুন → <b class="text-zinc-400">Share</b> চাপুন → <b class="text-zinc-400">Copy link</b> → এখানে পেস্ট করুন।
                            </p>
                        </div>

                        <div>
                            <label for="project-details" class="block text-xs font-medium text-zinc-300 mb-2">আপনার ভাবনা বা বিশেষ চাহিদা <span class="text-zinc-500 font-normal">(ঐচ্ছিক)</span></label>
                            <textarea id="project-details" rows="3" placeholder="কেমন ছবি বা ভিডিও চান, কী উপলক্ষ — যা মনে আসে লিখুন..."
                                      class="w-full px-4 py-3 rounded-xl bg-charcoal border border-white/10 text-white placeholder-zinc-500 text-sm focus:outline-none focus:border-velvetRed transition-colors"></textarea>
                        </div>

                        <button type="submit" id="submit-btn"
                                class="w-full py-4 rounded-xl bg-gradient-to-r from-velvetRed to-reelsPink text-white font-semibold text-base tracking-wide hover:opacity-95 transition-all duration-300 shadow-[0_0_20px_rgba(225,29,72,0.3)] disabled:opacity-60 disabled:cursor-wait">
                            বুকিং রিকোয়েস্ট পাঠান ✨
                        </button>
                        <p id="form-error" class="hidden text-xs text-red-400 text-center"></p>
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
                <p class="text-xs text-pink-200/70 mt-1">প্রতিটি মুহূর্ত, একটি সিনেমা।</p>
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
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
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
            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
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

    <!-- BOOKING SLIP MODAL (বুকিং রিকোয়েস্ট স্লিপ) -->
    <div id="slip-modal" class="fixed inset-0 z-[60] hidden overflow-y-auto bg-black/90 backdrop-blur-xl p-4 flex">
        <div class="m-auto w-full max-w-[420px] py-8 flex flex-col items-center">
            <button type="button" id="slip-close" aria-label="বন্ধ করুন" class="self-end mb-3 w-10 h-10 rounded-full bg-white/10 hover:bg-velvetRed text-white flex items-center justify-center transition-colors">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>

            <!-- স্লিপ কার্ড (এটাই ছবি/PDF হয়ে ডাউনলোড হবে) -->
            <div id="slip-card" style="width:100%;background:#140c0e;border:1px solid rgba(225,29,72,.5);border-radius:22px;overflow:hidden;color:#f4f4f6;font-family:'Hind Siliguri',sans-serif;box-shadow:0 0 40px rgba(225,29,72,.25);">
                <div style="padding:24px 24px 18px;text-align:center;background:linear-gradient(135deg,#2a0b14 0%,#140c0e 55%,#2a0b1f 100%);">
                    <svg width="38" height="38" viewBox="0 0 24 24" fill="none" stroke="#e11d48" stroke-width="1.7" style="display:inline-block">
                        <circle cx="12" cy="12" r="9"/><circle cx="12" cy="12" r="3"/><path d="M12 3v3M12 18v3M3 12h3M18 12h3"/>
                    </svg>
                    <div style="font-family:'Cinzel',serif;letter-spacing:.2em;font-weight:700;font-size:20px;margin-top:8px;color:#fff;">MSH <span style="color:#fb7185">LENS ART</span></div>
                    <div style="font-family:'Montserrat',sans-serif;font-size:10px;letter-spacing:.32em;color:#f9a8d4;margin-top:5px;">BOOKING REQUEST SLIP</div>
                </div>

                <div style="border-top:2px dashed rgba(255,255,255,.2);margin:0 16px;"></div>

                <div style="padding:20px 24px 8px;text-align:center;">
                    <div style="font-size:12px;color:#f9a8d4;letter-spacing:.08em;">আপনার বুকিং আইডি</div>
                    <div id="sl-id" style="font-family:'Montserrat',sans-serif;font-weight:700;font-size:24px;letter-spacing:.08em;color:#fb7185;margin-top:4px;"></div>
                    <div style="display:inline-block;margin-top:12px;padding:6px 16px;border-radius:999px;background:rgba(236,72,153,.15);border:1px solid rgba(236,72,153,.5);color:#fbcfe8;font-size:13px;font-weight:600;">✔ রিকোয়েস্ট গৃহীত হয়েছে</div>
                </div>

                <div style="padding:8px 24px 6px;">
                    <div class="slip-row"><span class="k">নাম</span><span class="v" id="sl-name"></span></div>
                    <div class="slip-row"><span class="k">ফোন</span><span class="v" id="sl-phone"></span></div>
                    <div class="slip-row" id="sl-email-row"><span class="k">ইমেইল</span><span class="v small" id="sl-email"></span></div>
                    <div class="slip-row"><span class="k">সেবা</span><span class="v" id="sl-service"></span></div>
                    <div class="slip-row"><span class="k">সম্ভাব্য তারিখ</span><span class="v" id="sl-date"></span></div>
                    <div class="slip-row"><span class="k">লোকেশন</span><span class="v" id="sl-location"></span></div>
                    <div class="slip-row" id="sl-map-row"><span class="k">ম্যাপ লিঙ্ক</span><span class="v small" id="sl-map"></span></div>
                    <div class="slip-row" id="sl-details-row"><span class="k">আপনার ভাবনা</span><span class="v" id="sl-details"></span></div>
                    <div class="slip-row"><span class="k">আবেদনের সময়</span><span class="v small" id="sl-time"></span></div>
                </div>

                <div style="border-top:2px dashed rgba(255,255,255,.2);margin:6px 16px 0;"></div>

                <div style="padding:18px 24px 24px;text-align:center;background:linear-gradient(180deg,#140c0e 0%,#1c0d14 100%);">
                    <div style="font-size:16px;font-weight:700;color:#fff;">ধন্যবাদ, আপনার গল্পের অংশ হতে পেরে আমরা আনন্দিত! 💖</div>
                    <div style="font-size:12.5px;color:#d4d4d8;margin-top:8px;line-height:1.7;">আপনার রিকোয়েস্ট আমরা পেয়েছি। তারিখ ও বিস্তারিত যাচাই করে শীঘ্রই আপনার সাথে যোগাযোগ করব।<br>(এটি বুকিং নিশ্চিতকরণ নয়, শুধু রিকোয়েস্ট স্লিপ।)</div>
                    <div style="font-family:'Montserrat',sans-serif;font-size:11.5px;color:#f9a8d4;margin-top:12px;line-height:1.8;">
                        WhatsApp: +880 1868-942746<br>@mshlensart &bull; mshlensart@gmail.com
                    </div>
                </div>
            </div>

            <!-- স্ট্যাটাস + বাটন -->
            <div id="slip-actions" class="w-full mt-5 space-y-3">
                <p id="slip-send-status" class="text-center text-xs leading-relaxed"></p>

                <a id="slip-wa-link" href="#" target="_blank" rel="noopener noreferrer"
                   class="w-full flex items-center justify-center gap-2 py-3.5 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white text-sm font-semibold transition-colors">
                    💬 WhatsApp-এ জানিয়ে দিন
                </a>

                <div class="grid grid-cols-3 gap-2.5">
                    <button type="button" id="dl-png" class="py-3 rounded-xl bg-white/10 hover:bg-white/20 text-white text-xs font-semibold transition-colors">📥 ছবি (PNG)</button>
                    <button type="button" id="dl-pdf" class="py-3 rounded-xl bg-white/10 hover:bg-white/20 text-white text-xs font-semibold transition-colors">📄 PDF</button>
                    <button type="button" id="dl-print" class="py-3 rounded-xl bg-white/10 hover:bg-white/20 text-white text-xs font-semibold transition-colors">🖨️ প্রিন্ট</button>
                </div>
                <p class="text-center text-[11px] text-zinc-500">ছবি গ্যালারিতে না পেলে স্ক্রিনশট নিয়ে রাখুন।</p>
            </div>
        </div>
    </div>

    <!-- স্লিপ ডাউনলোডের লাইব্রেরি (ছবি ও PDF বানানোর জন্য) -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js" defer></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js" defer></script>

    <script>
        /* =====================================================================
           ⚙️  সেটিংস — শুধু এই অংশটুকু প্রয়োজনে বদলাবেন
           ===================================================================== */
        const CONFIG = {
            whatsapp: '8801868942746',           // দেশের কোডসহ, + ছাড়া
            email: 'mshlensart@gmail.com',

            // 👉 web3forms.com থেকে পাওয়া Access Key এখানে বসান (ফাঁকা থাকলে ইমেইল যাবে না)
            web3formsKey: '',

            // 👉 ঐচ্ছিক: নিজের WhatsApp-এ অটো নোটিফিকেশন (CallMeBot-এর API Key)
            callMeBotKey: '',
            callMeBotPhone: '+8801868942746'
        };

        /* 📸 গ্যালারির ছবি — নিজের ছবির লিঙ্ক/ফাইলের নাম বসিয়ে দিন (যেমন: 'images/p1.jpg')
           cat: portrait | cinematic | event      top: true দিলে ছবির উপরের অংশ ফোকাস হবে */
        const GALLERY = [
            { cat: 'portrait',  title: 'গোধূলির আলোয় পোর্ট্রেট',  sub: 'ন্যাচারাল লাইট এডিটোরিয়াল সিরিজ', top: true,
              thumb: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=1200&q=85' },
            { cat: 'cinematic', title: 'নিয়ন রাতের শহর',           sub: 'মুডি কালার গ্রেডিং ও স্ট্রিট ভিজ্যুয়াল',
              thumb: 'https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1514565131-fce0801e5785?auto=format&fit=crop&w=1200&q=85' },
            { cat: 'event',     title: 'উৎসব ও ইভেন্টের মুহূর্ত',   sub: 'আবেগঘন মুহূর্তের কভারেজ',
              thumb: 'https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=1200&q=85' },
            { cat: 'cinematic', title: 'কুয়াশাচ্ছন্ন পাহাড়ি পথ',    sub: 'অ্যাটমোস্ফিয়ারিক ল্যান্ডস্কেপ',
              thumb: 'https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1200&q=85' },
            { cat: 'portrait',  title: 'ছায়া ও আলোর স্টুডিও ফ্রেম', sub: 'ড্রামাটিক কনট্রাস্ট পোর্ট্রেট', top: true,
              thumb: 'https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=1200&q=85' },
            { cat: 'event',     title: 'লাইভ কনসার্ট পারফরম্যান্স',  sub: 'স্টেজ লাইট ও হাই-এনার্জি কভারেজ',
              thumb: 'https://images.unsplash.com/photo-1501281668745-f7f57925c3b4?auto=format&fit=crop&w=800&q=80',
              full:  'https://images.unsplash.com/photo-1501281668745-f7f57925c3b4?auto=format&fit=crop&w=1200&q=85' }
        ];

        /* 🎬 শো-রিলের ভিডিও — src-তে নিজের MP4 ফাইলের লিঙ্ক বসান (এখন ডেমো ভিডিও আছে) */
        const VIDEOS = [
            { tag: '4K MASTER REEL', title: 'অফিসিয়াল সিনেমাটোগ্রাফি শোরিল', dur: '01:00',
              desc: '৪কে রেজোলিউশনে ধারণকৃত ট্রাভেল, পোর্ট্রেট ও ইভেন্ট ফিল্মের নির্বাচিত দৃশ্যমালা।',
              poster: 'https://images.unsplash.com/photo-1536440136628-849c177e76a1?auto=format&fit=crop&w=1200&q=80',
              src: 'https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerBlazes.mp4' },
            { tag: 'REELS & VISUALS', title: 'গল্পের খোঁজে — ব্র্যান্ড রিলস', dur: '01:15',
              desc: 'ইনস্টাগ্রাম ট্রেন্ডিং রিলস ও আধুনিক কমার্শিয়াল ভিডিওর একটি বিশেষ সংকলন।',
              poster: 'https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&w=1200&q=80',
              src: 'https://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerEscapes.mp4' }
        ];
    </script>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const $ = (id) => document.getElementById(id);
            const CAT_LABEL = { portrait: 'পোর্ট্রেট', cinematic: 'সিনেমাটিক', event: 'ইভেন্ট' };
            const FALLBACK = "this.onerror=null;this.src='https://placehold.co/800x1000/140c0e/e11d48?text=MSH+LENS+ART'";

            // ---------- 1. Mobile menu ----------
            const mobileMenu = $('mobile-menu');
            const iconOpen = $('menu-icon-open');
            const iconClose = $('menu-icon-close');
            function toggleMobileMenu() {
                const wasHidden = mobileMenu.classList.contains('hidden');
                mobileMenu.classList.toggle('hidden');
                iconOpen.classList.toggle('hidden', wasHidden);
                iconClose.classList.toggle('hidden', !wasHidden);
            }
            $('mobile-menu-btn').addEventListener('click', toggleMobileMenu);
            document.querySelectorAll('.mobile-link').forEach(l => l.addEventListener('click', () => {
                if (!mobileMenu.classList.contains('hidden')) toggleMobileMenu();
            }));

            // ---------- 2. Gallery render + filter + lightbox ----------
            $('gallery-grid').innerHTML = GALLERY.map((g, i) => `
                <div class="gallery-card group relative rounded-2xl overflow-hidden bg-charcoal border border-white/10 aspect-[4/5] cursor-pointer reveal" data-category="${g.cat}" data-index="${i}">
                    <img src="${g.thumb}" loading="lazy" onerror="${FALLBACK}" alt="${g.title}" class="w-full h-full object-cover ${g.top ? 'object-top' : ''}">
                    <div class="absolute inset-0 bg-gradient-to-t from-obsidian via-obsidian/20 to-transparent opacity-80 sm:opacity-0 sm:group-hover:opacity-95 transition-opacity duration-500 flex flex-col justify-end p-6">
                        <span class="text-xs font-sans uppercase tracking-widest text-reelsPink mb-1">${CAT_LABEL[g.cat] || ''}</span>
                        <h3 class="text-xl font-semibold text-white">${g.title}</h3>
                        <p class="text-xs text-zinc-300 mt-1">${g.sub}</p>
                    </div>
                </div>`).join('');

            const galleryCards = document.querySelectorAll('.gallery-card');
            const filterBtns = document.querySelectorAll('.filter-btn');
            const activeCls = ['bg-gradient-to-r', 'from-velvetRed', 'to-reelsPink', 'text-white'];
            const idleCls = ['bg-charcoal', 'text-zinc-300', 'border', 'border-white/10'];

            filterBtns.forEach(btn => btn.addEventListener('click', () => {
                filterBtns.forEach(b => { b.classList.remove(...activeCls); b.classList.add(...idleCls); });
                btn.classList.remove(...idleCls); btn.classList.add(...activeCls);
                const f = btn.getAttribute('data-filter');
                galleryCards.forEach(card => {
                    const show = f === 'all' || card.getAttribute('data-category') === f;
                    card.classList.toggle('hidden', !show);
                    if (show) card.classList.add('active');
                });
            }));

            const lightbox = $('lightbox-modal');
            galleryCards.forEach(card => card.addEventListener('click', () => {
                const g = GALLERY[Number(card.getAttribute('data-index'))];
                $('lightbox-img').src = g.full;
                $('lightbox-img').alt = g.title;
                $('lightbox-title').textContent = g.title;
                $('lightbox-subtitle').textContent = `${CAT_LABEL[g.cat] || ''} • MSH Lens Art`;
                lightbox.classList.remove('hidden');
                document.body.style.overflow = 'hidden';
            }));
            function closeLightbox() { lightbox.classList.add('hidden'); $('lightbox-img').src = ''; syncScroll(); }
            $('close-lightbox').addEventListener('click', closeLightbox);
            lightbox.addEventListener('click', e => { if (e.target === lightbox) closeLightbox(); });

            // ---------- 3. Showreel render + player ----------
            $('video-grid').innerHTML = VIDEOS.map((v, i) => `
                <div class="video-card group relative rounded-2xl overflow-hidden bg-obsidian border border-white/10 aspect-video cursor-pointer reveal" data-index="${i}">
                    <img src="${v.poster}" loading="lazy" onerror="this.onerror=null;this.src='https://placehold.co/1280x720/0b0708/e11d48?text=MSH+LENS+ART'" alt="${v.title}"
                         class="w-full h-full object-cover opacity-75 group-hover:scale-105 group-hover:opacity-60 transition-all duration-700">
                    <div class="absolute inset-x-0 top-0 h-4 bg-black/80"></div>
                    <div class="absolute inset-x-0 bottom-0 h-4 bg-black/80"></div>
                    <div class="absolute inset-0 flex items-center justify-center">
                        <div class="w-16 h-16 sm:w-20 sm:h-20 rounded-full bg-gradient-to-r from-velvetRed to-reelsPink text-white flex items-center justify-center pl-1 shadow-[0_0_30px_rgba(225,29,72,0.5)] group-hover:scale-110 transition-transform duration-300">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 fill-current" viewBox="0 0 24 24"><path d="M8 5v14l11-7z"/></svg>
                        </div>
                    </div>
                    <div class="absolute bottom-6 left-6 right-6 flex items-end justify-between">
                        <div>
                            <span class="inline-block px-2.5 py-0.5 rounded bg-black/70 border border-velvetRed/40 text-[11px] font-sans text-pink-300 mb-2">${v.tag}</span>
                            <h3 class="text-lg sm:text-xl font-bold text-white">${v.title}</h3>
                        </div>
                        <span class="text-xs font-sans text-zinc-300 bg-black/70 px-3 py-1 rounded-full border border-white/10">${v.dur}</span>
                    </div>
                </div>`).join('');

            const videoModal = $('video-modal');
            const player = $('video-player');
            document.querySelectorAll('.video-card').forEach(card => card.addEventListener('click', () => {
                const v = VIDEOS[Number(card.getAttribute('data-index'))];
                $('video-modal-title').textContent = v.title;
                $('video-modal-desc').textContent = v.desc;
                $('video-modal-duration').textContent = `Duration: ${v.dur}`;
                player.poster = v.poster;
                player.src = v.src;
                videoModal.classList.remove('hidden');
                document.body.style.overflow = 'hidden';
                player.play().catch(() => {});
            }));
            function closeVideoModal() {
                player.pause(); player.removeAttribute('src'); player.load();
                videoModal.classList.add('hidden'); syncScroll();
            }
            $('close-video-modal').addEventListener('click', closeVideoModal);
            videoModal.addEventListener('click', e => { if (e.target === videoModal) closeVideoModal(); });

            // ---------- 4. Booking form ----------
            const form = $('booking-form');
            const dateInput = $('event-date');
            const mapInput = $('map-link');
            const mapStatus = $('map-status');
            const formError = $('form-error');
            const submitBtn = $('submit-btn');

            // আজকের আগের তারিখ বন্ধ
            const t = new Date();
            dateInput.min = `${t.getFullYear()}-${String(t.getMonth() + 1).padStart(2, '0')}-${String(t.getDate()).padStart(2, '0')}`;

            const mapsPattern = /^https?:\/\/(www\.)?(google\.[a-z.]+\/maps|maps\.google\.[a-z.]+|maps\.app\.goo\.gl|goo\.gl\/maps)/i;
            mapInput.addEventListener('input', () => {
                const v = mapInput.value.trim();
                if (!v) { mapStatus.textContent = ''; return; }
                if (mapsPattern.test(v)) { mapStatus.textContent = '✅ ম্যাপ লিঙ্ক যুক্ত হয়েছে'; mapStatus.className = 'text-xs text-emerald-400'; }
                else { mapStatus.textContent = 'এটি Google Maps লিঙ্ক মনে হচ্ছে না — চাইলে খালি রাখুন'; mapStatus.className = 'text-xs text-amber-400'; }
            });

            function makeBookingId() {
                const d = new Date();
                const yy = String(d.getFullYear()).slice(2);
                const mm = String(d.getMonth() + 1).padStart(2, '0');
                const dd = String(d.getDate()).padStart(2, '0');
                const rnd = String(Math.floor(1000 + Math.random() * 9000));
                
