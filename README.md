<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sim Tailor – Bespoke Tailor Hoi An | simtailorhoian.com</title>
    <meta name="description" content="Sim Tailor (Dũng Design Bespoke Tailor) - Family bespoke design tailor made to measurements & Worldwide Shipping. 15+ years experience. Address: 23 Lê Lợi, Hội An, Đà Nẵng. Hotline/WhatsApp: 0906.440.883">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,400&family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gold: {
                            50: '#fbf8f1',
                            100: '#f5eedc',
                            200: '#ead8b4',
                            300: '#dcbe85',
                            400: '#cea059',
                            500: '#c28a3b',
                            600: '#a9702d',
                            700: '#885626',
                            800: '#704624',
                            900: '#5d3b20',
                        },
                        charcoal: {
                            800: '#1f1e1c',
                            900: '#141311',
                            950: '#0c0b0a'
                        },
                        ivory: '#faf7f2'
                    },
                    fontFamily: {
                        serif: ['"Playfair Display"', 'Georgia', 'serif'],
                        display: ['"Cormorant Garamond"', 'Georgia', 'serif'],
                        sans: ['"Inter"', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #faf7f2;
            color: #1f1e1c;
        }
        .font-serif-luxury {
            font-family: 'Playfair Display', Georgia, serif;
        }
        .font-cormorant {
            font-family: 'Cormorant Garamond', Georgia, serif;
        }
        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #faf7f2;
        }
        ::-webkit-scrollbar-thumb {
            background: #c28a3b;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #885626;
        }
        .hero-slide {
            transition: opacity 0.8s ease-in-out, transform 0.8s ease-in-out;
        }
        .card-zoom:hover .zoom-img {
            transform: scale(1.06);
        }
        .zoom-img {
            transition: transform 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94);
        }
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(194, 138, 59, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(194, 138, 59, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(194, 138, 59, 0); }
        }
        .pulse-gold {
            animation: pulse-ring 2s infinite;
        }
        
        /* Video iframe responsive container */
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            border-radius: 1rem;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body class="antialiased selection:bg-gold-500 selection:text-white">

    <!-- ================= TOP ANNOUNCEMENT & CONTACT BAR ================= -->
    <div class="bg-charcoal-950 text-gold-100 text-xs border-b border-gold-900/40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-2.5 flex flex-wrap items-center justify-between gap-2">
            <!-- Left Contact Info -->
            <div class="flex flex-wrap items-center gap-4 sm:gap-6">
                <a href="https://simtailorhoian.com" class="flex items-center gap-1.5 text-gold-400 font-semibold tracking-wide hover:text-gold-300 transition">
                    <i class="fa-solid fa-globe"></i>
                    <span>simtailorhoian.com</span>
                </a>
                <a href="#contact" class="flex items-center gap-1.5 hover:text-gold-300 transition">
                    <i class="fa-solid fa-location-dot text-gold-500"></i>
                    <span>23 Lê Lợi, Hội An, Đà Nẵng</span>
                </a>
                <a href="tel:0906440883" class="flex items-center gap-1.5 hover:text-gold-300 transition font-medium">
                    <i class="fa-solid fa-phone-volume text-gold-500"></i>
                    <span>0906.440.883 (+84 906 440 883)</span>
                </a>
            </div>

            <!-- Right Utilities: Fanpage Link & Language Toggle -->
            <div class="flex items-center gap-3 ml-auto">
                <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-blue-600/20 text-blue-300 border border-blue-500/30 hover:bg-blue-600/30 transition">
                    <i class="fa-brands fa-facebook"></i>
                    <span>FB: Sim Tailor</span>
                </a>
                <!-- Language Switcher -->
                <div class="inline-flex rounded-full bg-charcoal-800 p-0.5 border border-gold-800/50">
                    <button id="lang-en" onclick="setLanguage('en')" class="px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition bg-gold-600 text-white">EN</button>
                    <button id="lang-vi" onclick="setLanguage('vi')" class="px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition text-gold-200 hover:text-white">VI</button>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= MAIN HEADER & NAVIGATION ================= -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-gold-200/60 transition-all">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Sử dụng bố cục chia 3 phần để Menu luôn nằm chính giữa màn hình Desktop -->
            <div class="flex items-center justify-between h-20 sm:h-24">
                
                <!-- 1. Brand Logo (w-auto lg:w-64 để cân bằng với cụm Icon bên phải) -->
                <div class="flex shrink-0 w-auto lg:w-72">
                    <a href="#" class="flex items-center gap-2 sm:gap-3 group">
                        <!-- Căn tâm tuyệt đối chữ EST. 2011 bằng SVG -->
                        <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-charcoal-900 border-2 border-gold-500 flex flex-col items-center justify-center text-center shadow-md group-hover:border-gold-400 transition shrink-0">
                            <svg viewBox="0 0 64 64" class="w-full h-full block">
                                <g transform="translate(32, 25)" fill="none" stroke="#e5c17c" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round">
                                    <circle cx="-6.5" cy="-5" r="4.2"/>
                                    <circle cx="-6.5" cy="5" r="4.2"/>
                                    <line x1="-2.5" y1="-2.5" x2="9.5" y2="5.5"/>
                                    <line x1="-2.5" y1="2.5" x2="9.5" y2="-5.5"/>
                                </g>
                                <text x="32" y="47" text-anchor="middle" fill="#e5c17c" font-family="Inter, sans-serif" font-size="8.5" font-weight="800" letter-spacing="0.5">EST. 2011</text>
                            </svg>
                        </div>
                        <div class="flex flex-col">
                            <span class="font-serif-luxury text-2xl sm:text-3xl font-bold tracking-wider text-charcoal-900 leading-none mb-1">SIM TAILOR</span>
                            <p class="text-[9px] sm:text-[10px] text-stone-500 tracking-widest uppercase font-medium leading-none">
                                Bespoke Tailor Hoi An
                            </p>
                        </div>
                    </a>
                </div>

                <!-- 2. Center Desktop Navigation Menu -->
                <nav class="hidden lg:flex flex-1 items-center justify-center gap-6 xl:gap-8 text-sm font-medium text-charcoal-800 whitespace-nowrap">
                    <a href="#home" class="text-gold-600 font-semibold hover:text-gold-700 transition" data-i18n="nav_home">Home</a>
                    <a href="#about" class="hover:text-gold-600 transition" data-i18n="nav_about">About Us</a>
                    <a href="#process" class="hover:text-gold-600 transition" data-i18n="nav_process">Our Process</a>
                    
                    <!-- Cloth Shop Dropdown -->
                    <div class="relative group py-6">
                        <a href="#cloth-shop" class="flex items-center gap-1 hover:text-gold-600 transition">
                            <span data-i18n="nav_shop">Cloth Shop</span>
                            <i class="fa-solid fa-chevron-down text-[10px] text-stone-400 group-hover:rotate-180 transition-transform"></i>
                        </a>
                        <div class="absolute left-1/2 -translate-x-1/2 top-full w-60 bg-white rounded-xl shadow-xl border border-gold-200/80 py-2 opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200 transform translate-y-2 group-hover:translate-y-0 z-50">
                            <button onclick="filterShop('all'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_all">All Collection</span>
                                <i class="fa-solid fa-arrow-right text-xs text-gold-500"></i>
                            </button>
                            <button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_women">Women Luxurious</span>
                                <span class="text-[10px] bg-pink-100 text-pink-700 px-1.5 py-0.5 rounded">Silk</span>
                            </button>
                            <button onclick="filterShop('men'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_men">Men's Clothes</span>
                                <span class="text-[10px] bg-stone-100 text-stone-700 px-1.5 py-0.5 rounded">Suit</span>
                            </button>
                            <button onclick="filterShop('family'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_family">Family Sets</span>
                                <span class="text-[10px] bg-gold-100 text-gold-800 px-1.5 py-0.5 rounded">Hot</span>
                            </button>
                        </div>
                    </div>

                    <a href="#lookbook" class="hover:text-gold-600 transition" data-i18n="nav_lookbook">Lookbook</a>
                    <a href="#contact" class="hover:text-gold-600 transition" data-i18n="nav_contact">Contact</a>
                </nav>

                <!-- 3. Action Buttons (Right, cân bằng với Logo) -->
                <div class="flex items-center justify-end gap-2.5 sm:gap-3 shrink-0 w-auto lg:w-72">
                    <!-- Search Toggle -->
                    <button onclick="toggleSearchModal()" class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-stone-100 hover:bg-gold-100 text-charcoal-800 hover:text-gold-700 flex items-center justify-center transition" title="Search">
                        <i class="fa-solid fa-magnifying-glass text-sm"></i>
                    </button>

                    <!-- Custom Order Bag -->
                    <button onclick="toggleOrderDrawer()" class="relative w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-stone-100 hover:bg-gold-100 text-charcoal-800 hover:text-gold-700 flex items-center justify-center transition" title="Your Bespoke Order List">
                        <i class="fa-solid fa-bag-shopping text-sm"></i>
                        <span id="cart-badge" class="absolute -top-1 -right-1 w-4 h-4 sm:w-5 sm:h-5 rounded-full bg-gold-600 text-white text-[10px] font-bold flex items-center justify-center">0</span>
                    </button>

                    <!-- Book Fitting CTA -->
                    <a href="#contact" class="hidden sm:inline-flex items-center gap-2 px-4 py-2.5 rounded-full bg-charcoal-900 hover:bg-gold-600 text-white text-xs sm:text-sm font-semibold tracking-wide transition shadow-md whitespace-nowrap">
                        <i class="fa-regular fa-calendar-check"></i>
                        <span data-i18n="btn_book_fitting">Book Fitting</span>
                    </a>

                    <!-- Mobile Hamburger -->
                    <button onclick="toggleMobileMenu()" class="lg:hidden w-9 h-9 rounded-full bg-charcoal-900 text-gold-400 flex items-center justify-center">
                        <i id="mobile-menu-icon" class="fa-solid fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gold-200 px-4 pt-3 pb-6 space-y-2 shadow-xl">
            <a href="#home" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50 text-gold-700" data-i18n="nav_home">Home</a>
            <a href="#about" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_about">About Us</a>
            <a href="#process" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_process">Our Process</a>
            <a href="#measure" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_measure">How To Measure</a>
            <a href="#cloth-shop" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_shop">Cloth Shop (Men & Women)</a>
            <a href="#lookbook" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_lookbook">Fanpage Lookbook</a>
            <a href="#contact" onclick="toggleMobileMenu()" class="block px-3 py-2.5 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_contact">Contact</a>
            <div class="pt-3 border-t border-stone-200 flex flex-col gap-2">
                <a href="tel:0906440883" class="w-full py-3 rounded-xl bg-gold-600 text-white text-center font-semibold text-sm shadow-md">
                    <i class="fa-solid fa-phone mr-1.5"></i> Call / Zalo: 0906.440.883
                </a>
            </div>
        </div>
    </header>

    <!-- ================= HERO BANNER SLIDER (Dùng 3 ảnh thực tế) ================= -->
    <section id="home" class="relative bg-charcoal-950 overflow-hidden">
        <div class="relative h-[540px] sm:h-[620px] lg:h-[680px] w-full">
            
            <!-- Slide 1: Storefront Photo 1 -->
            <div id="slide-0" class="hero-slide absolute inset-0 opacity-100 z-10">
                <img id="hero-img-0" src="1793023383936_9033669083747217679_9033669083747217679_bb48de857bd4e29887d20a606898b847.jpg" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Sim+Tailor+Hoi+An'"
                     alt="Sim Tailor Storefront" class="w-full h-full object-cover object-center brightness-[0.6]">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/80 via-charcoal-950/50 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/30 border border-gold-400/50 text-gold-300 text-[10px] sm:text-xs uppercase tracking-widest font-semibold backdrop-blur-sm">
                            <i class="fa-solid fa-award"></i>
                            <span data-i18n="hero1_badge">MOST REASONABLE - HIGH QUALITY TAILOR IN HOI AN</span>
                        </div>
                        <h1 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight drop-shadow-xl">
                            Sim Tailor Hoi An <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl" data-i18n="hero1_sub">Family Bespoke Design Tailor</span>
                        </h1>
                        <p class="text-stone-200 text-sm sm:text-lg leading-relaxed max-w-xl drop-shadow-md" data-i18n="hero1_desc">
                            "Hello everyone, I am Sim Tailor, with 15 years of experience." Custom suits, silk dresses & family outfits made to your exact measurements in 24–48 hours at 23 Lê Lợi, Hội An & Worldwide Shipping.
                        </p>
                        <div class="flex flex-wrap items-center gap-3 sm:gap-4 pt-2">
                            <a href="#cloth-shop" class="px-6 sm:px-7 py-3 sm:py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-xs sm:text-sm tracking-wider uppercase transition shadow-lg">
                                <span data-i18n="btn_explore_shop">Explore Cloth Shop</span>
                            </a>
                            <a href="https://wa.me/84906440883" target="_blank" rel="noopener noreferrer" class="px-5 sm:px-6 py-3 sm:py-3.5 rounded-full bg-white/10 hover:bg-white/20 backdrop-blur-md border border-white/30 text-white font-semibold text-xs sm:text-sm tracking-wider uppercase transition flex items-center gap-2">
                                <i class="fa-brands fa-whatsapp text-green-400 text-lg"></i>
                                <span>0906.440.883</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2: Storefront Photo 2 -->
            <div id="slide-1" class="hero-slide absolute inset-0 opacity-0 z-0">
                <img id="hero-img-1" src="1793023383965_9033669083747217679_9033669083747217679_c3bc48103577f8384b5af84dfd7997b4.jpg" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Sim+Tailor+Silk+Dresses'"
                     alt="Sim Tailor Silk Dresses" class="w-full h-full object-cover object-center brightness-[0.6]">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/80 via-charcoal-950/50 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/30 border border-gold-400/50 text-gold-300 text-[10px] sm:text-xs uppercase tracking-widest font-semibold backdrop-blur-sm">
                            <i class="fa-solid fa-wand-magic-sparkles"></i>
                            <span>SIM BESPOKE TAILOR • #SILKDRESSES #HOIANSUIT</span>
                        </div>
                        <h2 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight drop-shadow-xl">
                            Women Luxurious <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl">Silk Dresses & Couture</span>
                        </h2>
                        <p class="text-stone-200 text-sm sm:text-lg leading-relaxed max-w-xl drop-shadow-md">
                            Handcrafted Hoi An mulberry silk gowns, top & skirt sets, and tailored women's suits designed to flatter every silhouette.
                        </p>
                        <div class="flex flex-wrap items-center gap-3 sm:gap-4 pt-2">
                            <button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="px-6 sm:px-7 py-3 sm:py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-xs sm:text-sm tracking-wider uppercase transition shadow-lg">
                                View Women's Collection
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 3: Storefront Photo 3 -->
            <div id="slide-2" class="hero-slide absolute inset-0 opacity-0 z-0">
                <img id="hero-img-2" src="1793023383976_9033669083747217679_9033669083747217679_2df43c88c6274ee173ead680ae8e18e9.jpg" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Bespoke+Tailoring+23+Le+Loi'"
                     alt="Master Tailoring at 23 Le Loi Hoi An" class="w-full h-full object-cover object-center brightness-[0.6]">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/80 via-charcoal-950/50 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/30 border border-gold-400/50 text-gold-300 text-[10px] sm:text-xs uppercase tracking-widest font-semibold backdrop-blur-sm">
                            <i class="fa-solid fa-plane-departure"></i>
                            <span>23 LÊ LỢI, HỘI AN, ĐÀ NẴNG • WORLDWIDE SHIPPING</span>
                        </div>
                        <h2 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight drop-shadow-xl">
                            Made To Measurements <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl">& Global Delivery</span>
                        </h2>
                        <p class="text-stone-200 text-sm sm:text-lg leading-relaxed max-w-xl drop-shadow-md">
                            Loved by travelers from around the world. We keep your measurement profile on file so you can reorder bespoke garments from anywhere.
                        </p>
                        <div class="flex flex-wrap items-center gap-3 sm:gap-4 pt-2">
                            <a href="#measure" class="px-6 sm:px-7 py-3 sm:py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-xs sm:text-sm tracking-wider uppercase transition shadow-lg">
                                How To Measure Online
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slider Controls (Dời sang trái để tránh bị đè bởi nút liên hệ bên phải) -->
            <div class="absolute bottom-6 left-6 z-30 flex items-center gap-3">
                <button onclick="prevSlide()" class="w-10 h-10 rounded-full bg-black/60 hover:bg-gold-600 text-white border border-white/20 flex items-center justify-center transition backdrop-blur-sm">
                    <i class="fa-solid fa-chevron-left text-sm"></i>
                </button>
                <div class="flex items-center gap-2 px-3 py-2 rounded-full bg-black/50 backdrop-blur-sm border border-white/10">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-gold-500 transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                    <button onclick="goToSlide(2)" id="dot-2" class="w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                </div>
                <button onclick="nextSlide()" class="w-10 h-10 rounded-full bg-black/60 hover:bg-gold-600 text-white border border-white/20 flex items-center justify-center transition backdrop-blur-sm">
                    <i class="fa-solid fa-chevron-right text-sm"></i>
                </button>
            </div>
        </div>
    </section>

    <!-- ================= 4 SIGNATURE PILLAR CARDS ================= -->
    <section class="relative z-20 -mt-10 sm:-mt-12 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <!-- Đã chia lưới 2 cột (grid-cols-2) cho mobile -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
            <!-- Card 1: ABOUT US -->
            <a href="#about" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-medal"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider text-gold-600 font-semibold">Sim Tailor Hoi An</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-1" data-i18n="pillar1_title">ABOUT US</h3>
                    <p class="text-[10px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar1_desc">
                        15+ years of family bespoke craftsmanship at 23 Lê Lợi. Formerly Dũng Design Tailor.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="read_more">Discover Story</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </a>

            <!-- Card 2: WHAT WE DO? -->
            <a href="#process" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-scissors"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider text-gold-600 font-semibold">Our Process</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-1" data-i18n="pillar2_title">WHAT WE DO?</h3>
                    <p class="text-[10px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar2_desc">
                        Custom suits, silk dresses tailored in 24–48 hours & worldwide shipping.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="see_process">4-Step Process</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </a>

            <!-- Card 3: HOW TO MEASURE -->
            <a href="#measure" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-ruler-combined"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider text-gold-600 font-semibold">Remote Ordering</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-1" data-i18n="pillar3_title">HOW TO MEASURE</h3>
                    <p class="text-[10px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar3_desc">
                        Interactive body measurement guide to send your size online.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="open_guide">Measurement Tool</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </a>

            <!-- Card 4: CUSTOMER LOOKBOOK -->
            <a href="#lookbook" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-camera-retro"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider text-gold-600 font-semibold">Fanpage Gallery</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-1" data-i18n="pillar4_title">LOOKBOOK</h3>
                    <p class="text-[10px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar4_desc">
                        Real photos from our happy clients around the world on Facebook.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="view_photos">View Photos</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </div>
            </a>
        </div>
    </section>

    <!-- ================= ABOUT US SECTION (Video + Images) ================= -->
    <section id="about" class="py-20 sm:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 lg:gap-12 items-center">
            
            <!-- Left Media Content (YouTube Video + Storefront Images) -->
            <div class="lg:col-span-6 space-y-4">
                <!-- Video Container -->
                <div class="video-container shadow-2xl border border-gold-300">
                    <iframe src="https://www.youtube.com/embed/DjvaeP7muno?rel=0" title="Sim Tailor Hoi An Introduction" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                
                <!-- 2 Images Grid -->
                <div class="grid grid-cols-2 gap-4">
                    <img src="1793023383936_9033669083747217679_9033669083747217679_bb48de857bd4e29887d20a606898b847.jpg" alt="Sim Tailor Hoi An Team" class="w-full h-32 sm:h-48 object-cover rounded-2xl shadow-md border border-gold-200">
                    <img src="1793023383965_9033669083747217679_9033669083747217679_c3bc48103577f8384b5af84dfd7997b4.jpg" alt="Sim Tailor Customers" class="w-full h-32 sm:h-48 object-cover rounded-2xl shadow-md border border-gold-200">
                </div>
            </div>

            <!-- Right Text Content -->
            <div class="lg:col-span-6 space-y-6">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-100 text-gold-800 text-xs font-semibold uppercase tracking-widest">
                    <i class="fa-solid fa-needle"></i>
                    <span>SIM TAILOR • FORMERLY DŨNG DESIGN TAILOR</span>
                </div>
                <h2 class="font-serif-luxury text-3xl sm:text-4xl lg:text-5xl font-bold text-charcoal-900 leading-tight" data-i18n="about_heading">
                    Crafted With Heart at <span class="text-gold-600">23 Lê Lợi, Hội An</span>
                </h2>
                <p class="text-stone-600 leading-relaxed text-sm sm:text-base" data-i18n="about_p1">
                    Led by Master Tailor <strong>Thúy Sim</strong> with over <strong>15 years of hands-on tailoring experience</strong> (established on Facebook as <em>Dũng Design Bespoke Tailor / Sim Tailor</em>), <strong>Sim Tailor</strong> is a beloved family-owned custom tailoring house right in the heart of Hoi An Ancient Town at <strong>23 Lê Lợi, Hội An, Đà Nẵng</strong>.
                </p>
                <p class="text-stone-600 leading-relaxed text-sm sm:text-base" data-i18n="about_p2">
                    Rooted in strong family values and decades of artisanal heritage, we combine superior fabrics—from breathable Hoi An mulberry silk and pure linen to Italian cashmere wool—with meticulous hand-stitching to create bespoke masterpieces. Travelers consistently choose us for flawless fits, 24–48 hour turnaround, and genuinely warm service.
                </p>

                <!-- Key Highlights Grid -->
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 pt-2">
                    <div class="flex items-start gap-3 p-4 rounded-xl bg-white border border-gold-200/70 shadow-sm">
                        <div class="w-10 h-10 rounded-lg bg-gold-100 text-gold-700 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-clock text-lg"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-sm text-charcoal-900">Express 24–48h Turnaround</h4>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">Including 2–3 personal fittings & complimentary hotel delivery in Hoi An.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-3 p-4 rounded-xl bg-white border border-gold-200/70 shadow-sm">
                        <div class="w-10 h-10 rounded-lg bg-gold-100 text-gold-700 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-earth-americas text-lg"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-sm text-charcoal-900">Worldwide Shipping</h4>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-1">We store your measurements so you can order more suits & dresses from home.</p>
                        </div>
                    </div>
                </div>

                <!-- Contact & Social Strip -->
                <div class="pt-4 flex flex-wrap items-center gap-4">
                    <a href="#cloth-shop" class="px-7 py-3.5 rounded-full bg-charcoal-900 hover:bg-gold-600 text-white text-sm font-semibold transition shadow-md">
                        Browse Bespoke Catalog
                    </a>
                    <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="px-6 py-3.5 rounded-full bg-white hover:bg-gold-50 text-charcoal-900 border border-gold-300 text-sm font-semibold transition flex items-center gap-2">
                        <i class="fa-brands fa-facebook text-blue-600"></i>
                        <span>Visit Our Facebook</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CLOTH SHOP SECTION ================= -->
    <section id="cloth-shop" class="py-20 bg-white border-y border-gold-200/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <!-- Section Header -->
            <div class="text-center max-w-3xl mx-auto space-y-3">
                <p class="text-xs uppercase tracking-widest text-gold-600 font-bold">SIM TAILOR HOI AN • BESPOKE COLLECTION</p>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold text-charcoal-900" data-i18n="shop_heading">CLOTH SHOP</h2>
                <p class="text-stone-600 text-sm sm:text-base" data-i18n="shop_sub">
                    Tailor-made to your individual posture and style preferences. Select any design below to customize fabric, lining, and measurements or book a fitting at <strong>23 Lê Lợi, Hội An</strong>.
                </p>
            </div>

            <!-- Category Tabs -->
            <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3 mt-8">
                <button onclick="filterShop('all')" id="tab-all" class="shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-charcoal-900 text-white shadow-md" data-i18n="cat_all">
                    All Collection
                </button>
                <button onclick="filterShop('men')" id="tab-men" class="shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100" data-i18n="cat_men">
                    Men's Clothes
                </button>
                <button onclick="filterShop('women')" id="tab-women" class="shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100" data-i18n="cat_women">
                    Women Luxurious
                </button>
                <button onclick="filterShop('family')" id="tab-family" class="shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100" data-i18n="cat_family">
                    Couple & Family
                </button>
            </div>

            <!-- Products Grid: 2 columns on mobile, 4 on desktop -->
            <div id="products-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6 mt-8 sm:mt-10">
                <!-- Populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- ================= FANPAGE LOOKBOOK ================= -->
    <section id="lookbook" class="py-20 bg-ivory">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-10 sm:mb-12">
                <div>
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-blue-100 text-blue-800 text-xs font-semibold mb-3">
                        <i class="fa-brands fa-facebook"></i>
                        <span>synced from facebook.com/DungDesignTailor</span>
                    </div>
                    <h2 class="font-serif-luxury text-3xl sm:text-4xl font-bold text-charcoal-900" data-i18n="lookbook_heading">
                        Customer Lookbook
                    </h2>
                    <p class="text-stone-600 text-sm sm:text-base mt-2 max-w-2xl" data-i18n="lookbook_sub">
                        Authentic creations and client feedback posted on our official fanpage <strong>Sim Tailor (Dũng Design Bespoke Tailor)</strong> at 23 Lê Lợi, Hội An.
                    </p>
                </div>
                <div class="flex flex-wrap items-center gap-3">
                    <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="px-5 py-3 rounded-full bg-charcoal-900 hover:bg-charcoal-800 text-white text-xs sm:text-sm font-semibold transition flex items-center gap-2 shadow-md">
                        <i class="fa-brands fa-facebook-f text-blue-400"></i>
                        <span>Follow @DungDesignTailor</span>
                    </a>
                </div>
            </div>

            <!-- Fanpage Posts Grid: 2 columns on mobile -->
            <div id="fanpage-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6">
                <!-- Populated by JavaScript from real Fanpage Posts -->
            </div>
        </div>
    </section>

    <!-- ================= OUR PROCESS SECTION ================= -->
    <section id="process" class="py-20 bg-charcoal-900 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto space-y-3">
                <p class="text-xs uppercase tracking-widest text-gold-400 font-semibold">HOW WE CRAFT YOUR GARMENT</p>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold" data-i18n="process_heading">Our Bespoke Process</h2>
                <p class="text-stone-300 text-sm sm:text-base" data-i18n="process_sub">
                    Whether you visit us at <strong>23 Lê Lợi, Hội An, Đà Nẵng</strong> for our 24–48 hour express service or order remotely from abroad, every piece goes through 4 rigorous stages.
                </p>
            </div>

            <!-- Process Grid: 2 columns on mobile -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6 mt-10 sm:mt-12">
                <!-- Step 1 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-4 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">01</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-swatchbook"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Style & Fabric</h3>
                    <p class="text-[10px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Choose from 500+ premium fabrics (Mulberry Silk, Wool, Linen) and customize lapels, buttons with Master Tailor Sim.
                    </p>
                </div>

                <!-- Step 2 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-4 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">02</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-ruler-vertical"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Measurement</h3>
                    <p class="text-[10px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        We take over 25 precise anatomical measurements and posture notes so your suit or dress drapes naturally.
                    </p>
                </div>

                <!-- Step 3 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-4 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">03</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Fitting Sessions</h3>
                    <p class="text-[10px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Within 12–24 hours, try on your garment at 23 Lê Lợi (or at your hotel) to refine every millimeter for a perfect fit.
                    </p>
                </div>

                <!-- Step 4 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-4 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">04</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-plane-circle-check"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Global Delivery</h3>
                    <p class="text-[10px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Collect your pressed garment in a luxury bag, enjoy free hotel drop-off, or let us ship directly via DHL/FedEx.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= INTERACTIVE HOW TO MEASURE SECTION ================= -->
    <section id="measure" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-start">
                
                <!-- Left Visual Measurement Guide -->
                <div class="lg:col-span-5 bg-ivory rounded-3xl p-6 sm:p-8 border border-gold-200 shadow-sm">
                    <span class="text-xs font-bold uppercase tracking-widest text-gold-600">REMOTE BESPOKE ORDERING</span>
                    <h3 class="font-serif-luxury text-2xl sm:text-3xl font-bold text-charcoal-900 mt-1" data-i18n="measure_heading">How To Measure Yourself</h3>
                    <p class="text-xs sm:text-sm text-stone-600 mt-2">
                        Ordering from abroad? Follow our visual anatomical checkpoints below and submit your numbers—we will verify them via WhatsApp video call (<strong class="text-charcoal-900">0906.440.883</strong>).
                    </p>

                    <div class="my-6 bg-white rounded-2xl p-6 border border-gold-200/80 flex flex-col items-center">
                        <svg viewBox="0 0 260 320" class="w-56 h-64">
                            <!-- Mannequin Stand -->
                            <line x1="130" y1="260" x2="130" y2="305" stroke="#885626" stroke-width="6"/>
                            <path d="M90 305 L170 305" stroke="#885626" stroke-width="8" stroke-linecap="round"/>
                            <!-- Neck -->
                            <path d="M115 30 L145 30 L148 52 L112 52 Z" fill="#f5eedc" stroke="#1f1e1c" stroke-width="2"/>
                            <!-- Torso -->
                            <path d="M68 65 Q130 48 192 65 L178 160 L185 255 L75 255 L82 160 Z" fill="#faf7f2" stroke="#1f1e1c" stroke-width="2.5"/>
                            <path d="M112 52 L130 135 L148 52" fill="none" stroke="#c28a3b" stroke-width="2"/>
                            <!-- 1. Shoulder -->
                            <line x1="65" y1="65" x2="195" y2="65" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <circle cx="65" cy="65" r="4" fill="#c28a3b"/>
                            <circle cx="195" cy="65" r="4" fill="#c28a3b"/>
                            <text x="130" y="60" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">1. SHOULDER</text>
                            <!-- 2. Chest -->
                            <line x1="74" y1="110" x2="186" y2="110" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="105" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">2. CHEST / BUST</text>
                            <!-- 3. Waist -->
                            <line x1="82" y1="160" x2="178" y2="160" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="155" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">3. NATURAL WAIST</text>
                            <!-- 4. Hips -->
                            <line x1="76" y1="215" x2="184" y2="215" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="210" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">4. HIPS / SEAT</text>
                            <!-- 5. Length -->
                            <line x1="48" y1="65" x2="48" y2="255" stroke="#1f1e1c" stroke-width="2" stroke-dasharray="3 3"/>
                            <text x="42" y="165" text-anchor="middle" fill="#1f1e1c" font-size="9" font-weight="bold" transform="rotate(-90 42 165)">5. TOTAL LENGTH</text>
                        </svg>
                    </div>

                    <div class="p-4 rounded-2xl bg-gold-50 border border-gold-200 text-xs text-stone-700 space-y-1.5">
                        <p class="font-bold text-charcoal-900"><i class="fa-solid fa-video text-gold-600 mr-1.5"></i> Live Assistance</p>
                        <p>Message Master Tailor Sim on WhatsApp <strong>+84 906 440 883</strong> for a guided video session.</p>
                    </div>
                </div>

                <!-- Right Form -->
                <div class="lg:col-span-7 bg-white rounded-3xl p-6 sm:p-8 border border-gold-200 shadow-lg">
                    <div class="flex flex-wrap items-center justify-between gap-4 pb-5 border-b border-stone-200">
                        <div>
                            <h3 class="font-serif-luxury text-2xl font-bold text-charcoal-900">Measurement Profile</h3>
                            <p class="text-xs text-stone-500 mt-0.5">Send directly via WhatsApp</p>
                        </div>
                        <div class="inline-flex rounded-xl bg-stone-100 p-1">
                            <button type="button" onclick="setMeasureUnit('cm')" id="unit-cm" class="px-3 py-1 rounded-lg text-xs font-bold bg-charcoal-900 text-white">CM</button>
                            <button type="button" onclick="setMeasureUnit('inch')" id="unit-inch" class="px-3 py-1 rounded-lg text-xs font-bold text-stone-600">INCH</button>
                        </div>
                    </div>

                    <form id="measure-form" onsubmit="submitMeasurements(event)" class="space-y-5 mt-6">
                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Full Name *</label>
                                <input type="text" id="m-name" required placeholder="e.g. Julie Laurent" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Garment Type *</label>
                                <select id="m-garment" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none bg-white">
                                    <option value="Men's Bespoke Suit (2 or 3 Piece)">Men's Bespoke Suit</option>
                                    <option value="Women's Silk Dress / Evening Gown">Women's Silk Dress / Gown</option>
                                    <option value="Women's Tailored Suit / Top & Skirt">Women's Suit / Top & Skirt</option>
                                    <option value="Men's Custom Business Shirt">Men's Business Shirt</option>
                                    <option value="Cashmere Winter Coat / Trench">Winter Coat / Trench</option>
                                    <option value="Couple / Family Matching Set">Couple / Family Matching Set</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">Height & Weight</label>
                                <input type="text" id="m-hw" placeholder="175cm / 70kg" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                        </div>

                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">1. Shoulder (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-shoulder" placeholder="45" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">2. Chest/Bust (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-chest" placeholder="98" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">3. Waist (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-waist" placeholder="84" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">4. Hips/Seat (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-hips" placeholder="100" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">5. Sleeve (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-sleeve" placeholder="63" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">6. Length (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-length" placeholder="74" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Fit Preference & Notes</label>
                            <textarea id="m-notes" rows="2" placeholder="e.g. Slim fit, navy mulberry silk..." class="w-full px-3.5 py-2 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center gap-3 pt-2">
                            <button type="submit" class="px-6 py-3 rounded-full bg-gold-600 hover:bg-gold-500 text-white text-sm font-semibold transition shadow-md flex items-center gap-2">
                                <i class="fa-brands fa-whatsapp text-base"></i>
                                <span>Send WhatsApp</span>
                            </button>
                            <button type="button" onclick="emailMeasurements()" class="px-5 py-3 rounded-full bg-charcoal-900 hover:bg-charcoal-800 text-white text-sm font-semibold transition flex items-center gap-2">
                                <i class="fa-regular fa-envelope"></i>
                                <span>Send Email</span>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= BLOGS SECTION ================= -->
    <section id="blogs" class="py-20 bg-ivory border-t border-gold-200/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto space-y-3 mb-12">
                <p class="text-xs uppercase tracking-widest text-gold-600 font-bold">HOI AN TAILORING JOURNAL</p>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold text-charcoal-900" data-i18n="blogs_heading">Blogs & Style Guides</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Blog 1 -->
                <article class="bg-white rounded-2xl overflow-hidden shadow-md border border-gold-200/70 flex flex-col justify-between group">
                    <div>
                        <div class="relative h-56 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80" alt="Guide" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-6">
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 group-hover:text-gold-700 transition">
                                Ultimate Guide to Getting a Custom Suit in Hoi An
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed line-clamp-3">
                                Getting tailor-made clothing during a trip to Central Vietnam merges heritage craftsmanship with efficiency...
                            </p>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <button onclick="openBlogModal(0)" class="text-xs font-bold uppercase tracking-wider text-gold-700 hover:text-gold-600 flex items-center gap-1.5">
                            <span>Read Full Article</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </article>

                <!-- Blog 2 -->
                <article class="bg-white rounded-2xl overflow-hidden shadow-md border border-gold-200/70 flex flex-col justify-between group">
                    <div>
                        <div class="relative h-56 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=800&q=80" alt="Store" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-6">
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 group-hover:text-gold-700 transition">
                                👋 How to Find Sim Tailor at 23 Lê Lợi Easily!
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed line-clamp-3">
                                As there are multiple tailor shops in Hoi An, please double check our exact sign at 23 Lê Lợi...
                            </p>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <button onclick="openBlogModal(1)" class="text-xs font-bold uppercase tracking-wider text-gold-700 hover:text-gold-600 flex items-center gap-1.5">
                            <span>Read Full Article</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </article>

                <!-- Blog 3 -->
                <article class="bg-white rounded-2xl overflow-hidden shadow-md border border-gold-200/70 flex flex-col justify-between group">
                    <div>
                        <div class="relative h-56 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80" alt="Care" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        </div>
                        <div class="p-6">
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 group-hover:text-gold-700 transition">
                                Expert Tips for Protecting Custom Silk Back Home
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed line-clamp-3">
                                When returning home with a bespoke wool suit or mulberry silk dress, follow these steps to preserve its structure...
                            </p>
                        </div>
                    </div>
                    <div class="px-6 pb-6">
                        <button onclick="openBlogModal(2)" class="text-xs font-bold uppercase tracking-wider text-gold-700 hover:text-gold-600 flex items-center gap-1.5">
                            <span>Read Full Article</span>
                            <i class="fa-solid fa-arrow-right"></i>
                        </button>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ================= REVIEWS SECTION ================= -->
    <section id="reviews" class="py-20 bg-white border-t border-gold-200/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto space-y-3 mb-12">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-green-50 border border-green-200 text-green-800 text-xs font-bold">
                    <i class="fa-solid fa-star text-amber-400"></i>
                    <span>5.0 / 5.0 RATED ON FACEBOOK & TRIPADVISOR</span>
                </div>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold text-charcoal-900" data-i18n="reviews_heading">What Our Clients Say</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Review 1 -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Incredible silk dresses!"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "Sim Tailor at 23 Lê Lợi is a gem! With 15 years of experience, Sim understood exactly what I wanted right away. She made a black evening dress that fits like a dream."
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-gold-600 text-white font-bold flex items-center justify-center text-sm">JL</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Julie Laurent 🇫🇷</p>
                        </div>
                    </div>
                </div>

                <!-- Review 2 -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Best Hoi An tailor for family!"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "We came from Iceland and ordered custom suits and coats. From the minute we walked into 23 Lê Lợi, Sim made us feel comfortable and finished in 36 hours!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-charcoal-900 text-gold-400 font-bold flex items-center justify-center text-sm">IS</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Sigurdsson Family 🇮🇸</p>
                        </div>
                    </div>
                </div>

                <!-- Review 3 -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Flawless Suit & Gown"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "True family business at 23 Lê Lợi with reasonable prices and master quality work. Looks like we found our lifelong tailor in Vietnam!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-gold-600 text-white font-bold flex items-center justify-center text-sm">AD</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Anders & Duyên 🇩🇰🇻🇳</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CONTACT SECTION ================= -->
    <section id="contact" class="py-20 bg-charcoal-950 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
                
                <!-- Left Info & Map -->
                <div class="lg:col-span-5 space-y-6">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 text-gold-300 text-xs font-semibold uppercase tracking-widest">
                        <i class="fa-solid fa-location-dot"></i>
                        <span>VISIT OUR BOUTIQUE IN HOI AN</span>
                    </div>
                    <h2 class="font-serif-luxury text-3xl sm:text-4xl font-bold text-white" data-i18n="contact_heading">
                        Sim Tailor – 23 Lê Lợi
                    </h2>
                    <p class="text-stone-300 text-sm leading-relaxed">
                        No appointment is required to walk in, or you can book a private fitting / complimentary hotel pick-up.
                    </p>

                    <div class="space-y-4 pt-2">
                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-charcoal-900 border border-gold-800/40">
                            <div class="w-10 h-10 rounded-xl bg-gold-600/20 text-gold-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-map-location-dot text-lg"></i>
                            </div>
                            <div>
                                <p class="text-xs uppercase tracking-wider text-gold-400 font-semibold">Store Address</p>
                                <p class="text-sm sm:text-base font-bold text-white mt-0.5">23 Lê Lợi, Phố Cổ Hội An, Đà Nẵng</p>
                                <p class="text-xs text-stone-400 mt-0.5">Near Japanese Covered Bridge</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-charcoal-900 border border-gold-800/40">
                            <div class="w-10 h-10 rounded-xl bg-gold-600/20 text-gold-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-phone-volume text-lg"></i>
                            </div>
                            <div>
                                <p class="text-xs uppercase tracking-wider text-gold-400 font-semibold">Hotline / WhatsApp / Zalo</p>
                                <a href="tel:0906440883" class="text-base sm:text-lg font-bold text-white hover:text-gold-400 transition block mt-0.5">0906.440.883 (+84 906 440 883)</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right Booking Form -->
                <div class="lg:col-span-7">
                    <div class="bg-charcoal-900 rounded-3xl p-6 sm:p-10 border border-gold-500/30 shadow-2xl">
                        <h3 class="font-serif-luxury text-2xl sm:text-3xl font-bold text-white">Book A Fitting</h3>
                        <p class="text-xs sm:text-sm text-stone-400 mt-1">
                            Master Tailor Sim will reply immediately via WhatsApp (<strong class="text-gold-400">0906.440.883</strong>).
                        </p>

                        <form id="contact-form" onsubmit="submitContactForm(event)" class="space-y-4 mt-6">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Your Name *</label>
                                    <input type="text" id="c-name" required placeholder="Full Name" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">WhatsApp / Phone *</label>
                                    <input type="text" id="c-contact" required placeholder="+84 / WhatsApp" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Service Type</label>
                                    <select id="c-service" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                        <option value="In-Store Fitting at 23 Lê Lợi, Hội An">In-Store Fitting at 23 Lê Lợi</option>
                                        <option value="Free Hotel Pick-up in Hoi An">Free Hotel Pick-up</option>
                                        <option value="Worldwide Shipping / Remote Order">Worldwide Shipping</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Preferred Date</label>
                                    <input type="date" id="c-date" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-300 mb-1.5">What would you like us to tailor for you?</label>
                                <textarea id="c-message" rows="3" placeholder="Tell us about the suits, silk dresses..." class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none"></textarea>
                            </div>
                            <div class="pt-2">
                                <button type="submit" class="w-full sm:w-auto px-8 py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm tracking-wider uppercase transition shadow-lg flex items-center justify-center gap-2">
                                    <i class="fa-brands fa-whatsapp text-lg"></i>
                                    <span>Send Booking via WhatsApp</span>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER ================= -->
    <footer class="bg-charcoal-950 text-stone-400 border-t border-gold-900/40 pt-14 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 pb-12 border-b border-stone-800">
                <div class="space-y-4">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-full bg-gold-600 text-white flex items-center justify-center">
                            <i class="fa-solid fa-scissors"></i>
                        </div>
                        <div>
                            <span class="font-serif-luxury text-xl font-bold text-white tracking-wider">SIM TAILOR</span>
                            <p class="text-[10px] uppercase tracking-widest text-gold-400">simtailorhoian.com</p>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-stone-400">
                        Family bespoke design tailor made to measurements & Worldwide Shipping with over 15 years of experience.
                    </p>
                </div>
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Quick Navigation</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#home" class="hover:text-gold-400 transition">Home</a></li>
                        <li><a href="#about" class="hover:text-gold-400 transition">About Us</a></li>
                        <li><a href="#process" class="hover:text-gold-400 transition">Our Process</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Cloth Shop</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#cloth-shop" class="hover:text-gold-400 transition">Men Suit</a></li>
                        <li><a href="#cloth-shop" class="hover:text-gold-400 transition">Women Silk Dresses</a></li>
                        <li><a href="#cloth-shop" class="hover:text-gold-400 transition">Family Matching Sets</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Contact Sim Tailor</h4>
                    <ul class="space-y-2.5 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-gold-500 mt-1"></i>
                            <span>23 Lê Lợi, Hội An, Đà Nẵng, Việt Nam</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-gold-500"></i>
                            <a href="tel:0906440883" class="hover:text-white font-semibold">0906.440.883</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="pt-6 flex flex-col sm:flex-row items-center justify-between text-xs text-stone-500 gap-4">
                <p>Copyright 2026 © <strong>Sim Tailor (simtailorhoian.com)</strong>. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- ================= FLOATING QUICK CONTACT BAR (Đã chỉnh sửa tâm nút Zalo, kích thước tròn đều và xếp dọc) ================= -->
    <div class="fixed bottom-5 right-5 z-40 flex flex-col items-center gap-3">
        <!-- Messenger / Fanpage -->
        <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer"
           class="w-12 h-12 rounded-full bg-[#1877F2] hover:bg-blue-600 text-white shadow-lg border-2 border-white flex items-center justify-center transition-transform hover:scale-110" title="Facebook Fanpage Sim Tailor">
            <i class="fa-brands fa-facebook-messenger text-[22px]"></i>
        </a>

        <!-- Zalo 0906.440.883 (Chỉnh lại SVG tròn hoàn hảo và text nằm chính tâm) -->
        <a href="https://zalo.me/0906440883" target="_blank" rel="noopener noreferrer"
           class="w-12 h-12 rounded-full bg-[#0088FF] hover:bg-sky-500 text-white shadow-lg border-2 border-white flex items-center justify-center transition-transform hover:scale-110" title="Chat Zalo 0906.440.883">
            <svg viewBox="0 0 32 32" class="w-6 h-6">
                <!-- Nền trắng của biểu tượng Zalo -->
                <circle cx="16" cy="16" r="15" fill="#ffffff"/>
                <!-- Chữ Zalo màu xanh căn giữa tuyệt đối -->
                <text x="16" y="19.5" text-anchor="middle" fill="#0088FF" font-family="Inter, Arial, sans-serif" font-size="9" font-weight="900" letter-spacing="-0.5">Zalo</text>
            </svg>
        </a>

        <!-- WhatsApp +84906440883 -->
        <a href="https://wa.me/84906440883" target="_blank" rel="noopener noreferrer"
           class="w-12 h-12 rounded-full bg-[#25D366] hover:bg-green-500 text-white shadow-lg border-2 border-white flex items-center justify-center transition-transform hover:scale-110" title="WhatsApp +84 906 440 883">
            <i class="fa-brands fa-whatsapp text-[26px]"></i>
        </a>

        <!-- Direct Phone Call -->
        <a href="tel:0906440883"
           class="pulse-gold flex items-center gap-2 bg-gold-600 hover:bg-gold-500 text-white px-4 h-12 rounded-full shadow-xl border-2 border-white transition-transform hover:scale-105" title="Gọi 0906.440.883">
            <i class="fa-solid fa-phone-volume text-[17px]"></i>
            <span class="text-[13px] font-bold tracking-wider">0906.440.883</span>
        </a>
    </div>

    <!-- ================= CUSTOMIZER MODAL ================= -->
    <div id="customizer-modal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
        <!-- ... existing customizer modal logic ... -->
        <div class="bg-white rounded-3xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-gold-300 p-6 sm:p-8">
            <div class="flex items-start justify-between gap-4 pb-4 border-b border-stone-200">
                <div>
                    <span class="text-[11px] font-bold uppercase tracking-widest text-gold-600">SIM TAILOR BESPOKE</span>
                    <h3 id="modal-product-title" class="font-serif-luxury text-2xl font-bold text-charcoal-900 mt-0.5">Title</h3>
                    <p id="modal-product-price" class="text-sm font-bold text-gold-700 mt-0.5">Price</p>
                </div>
                <button onclick="closeCustomizerModal()" class="w-9 h-9 rounded-full bg-stone-100 hover:bg-stone-200 flex items-center justify-center text-stone-600">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="space-y-4 mt-5">
                <button onclick="addCustomizedToBag()" class="w-full py-3 rounded-full bg-charcoal-900 text-white text-sm font-semibold">Add to Bag</button>
            </div>
        </div>
    </div>

    <!-- ================= BESPOKE ORDER BAG DRAWER ================= -->
    <div id="order-drawer" class="fixed inset-0 z-50 hidden bg-black/60 backdrop-blur-sm flex justify-end">
        <div class="bg-white w-full max-w-md h-full shadow-2xl flex flex-col justify-between p-6">
            <div>
                <div class="flex items-center justify-between pb-4 border-b border-stone-200">
                    <div>
                        <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900">Your Bespoke Bag</h3>
                    </div>
                    <button onclick="toggleOrderDrawer()" class="w-8 h-8 rounded-full bg-stone-100 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>
                <div id="bag-items" class="mt-4 space-y-3 max-h-[60vh] overflow-y-auto"></div>
            </div>
            <div class="pt-4 border-t border-stone-200">
                <button onclick="checkoutBagWhatsApp()" class="w-full py-3.5 rounded-full bg-gold-600 text-white font-semibold text-sm flex items-center justify-center gap-2 shadow-lg">
                    <i class="fa-brands fa-whatsapp text-lg"></i> Send via WhatsApp
                </button>
            </div>
        </div>
    </div>

    <!-- ================= TOAST NOTIFICATION ================= -->
    <div id="toast" class="fixed bottom-6 left-6 z-50 hidden bg-charcoal-900 text-white px-5 py-3.5 rounded-2xl shadow-2xl border border-gold-500 flex items-center gap-3 text-xs sm:text-sm">
        <i class="fa-solid fa-circle-check text-gold-400 text-lg"></i>
        <span id="toast-msg">Notification</span>
    </div>

    <!-- ================= JAVASCRIPT ================= -->
    <script>
        const products = [
            { id: 'p1', title: 'Three Pieces Navy Men Suit', category: 'men', price: 'From $145', badge: 'Bestseller', desc: 'Classic bespoke 3-piece suit.', image: 'https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80' },
            { id: 'p2', title: 'Black Cocktail & Evening Dress', category: 'women', price: 'From $85', badge: 'Fanpage Hit', desc: 'Beautiful black dress.', image: 'https://images.unsplash.com/photo-1539008835657-9e8e9680c956?auto=format&fit=crop&w=800&q=80' },
            { id: 'p3', title: 'Hoi An Mulberry Silk Dress', category: 'women', price: 'From $90', badge: '#silkdresses', desc: '100% natural silk dress.', image: '1793023383965_9033669083747217679_9033669083747217679_c3bc48103577f8384b5af84dfd7997b4.jpg' },
            { id: 'p4', title: 'Double Breasted Men Suit', category: 'men', price: 'From $140', badge: 'Sartorial', desc: 'Sharp peak lapels.', image: 'https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80' }
        ];

        // Gắn 3 ảnh mới vào các bài đăng Lookbook mặc định
        const fanpagePosts = [
            {
                id: 'fp1', title: 'Custom Suit For Our Client',
                caption: 'Thanks for trusting Sim Tailor 🪡 📍 23 Le Loi Hoi An',
                tag: 'New • FB: Sim Tailor', image: '1793023383936_9033669083747217679_9033669083747217679_bb48de857bd4e29887d20a606898b847.jpg'
            },
            {
                id: 'fp2', title: 'Silk Dresses for lovely ladies',
                caption: 'Handmade with love in Hoi An 🧵🌸',
                tag: '2d • FB: Sim Tailor', image: '1793023383965_9033669083747217679_9033669083747217679_c3bc48103577f8384b5af84dfd7997b4.jpg'
            },
            {
                id: 'fp3', title: 'Welcome to Sim Tailor',
                caption: 'Master tailoring for everyone at 23 Le Loi, Hoi An ✨',
                tag: '1w • Custom Suits', image: '1793023383976_9033669083747217679_9033669083747217679_2df43c88c6274ee173ead680ae8e18e9.jpg'
            },
            {
                id: 'fp4', title: 'Top & Skirt Set',
                caption: 'Top & skirt made by us 🙏☺️✨',
                tag: '5w • Women Couture', image: 'https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=800&q=80'
            }
        ];

        let bag = [];
        let activeProductForModal = null;

        function renderProducts(category = 'all') {
            const grid = document.getElementById('products-grid');
            const filtered = category === 'all' ? products : products.filter(p => p.category === category);
            
            // Xóa style nút hiện tại, cập nhật lại tab
            ['all', 'men', 'women', 'family'].forEach(cat => {
                const btn = document.getElementById('tab-' + cat);
                if (btn) btn.className = cat === category 
                    ? 'shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-charcoal-900 text-white shadow-md' 
                    : 'shop-tab px-4 sm:px-5 py-2 sm:py-2.5 rounded-full text-xs sm:text-sm font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100';
            });

            grid.innerHTML = filtered.map(item => `
                <div class="bg-ivory rounded-2xl overflow-hidden border border-gold-200/80 shadow-sm flex flex-col justify-between group">
                    <div>
                        <div class="relative h-40 sm:h-72 overflow-hidden bg-stone-200">
                            <img src="${item.image}" alt="${item.title}" class="w-full h-full object-cover">
                            <span class="absolute top-2 left-2 px-2 py-0.5 rounded-full bg-charcoal-900/85 text-gold-300 text-[10px] font-semibold">${item.badge}</span>
                        </div>
                        <div class="p-3 sm:p-5">
                            <div class="flex items-center justify-between text-[10px] sm:text-xs text-gold-700 font-bold uppercase">
                                <span class="truncate pr-2">${item.category === 'men' ? "Men" : "Women"}</span>
                                <span class="text-xs sm:text-sm text-charcoal-900 whitespace-nowrap">${item.price}</span>
                            </div>
                            <h3 class="font-serif-luxury text-xs sm:text-lg font-bold text-charcoal-900 mt-1 line-clamp-2 leading-snug">${item.title}</h3>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-5 sm:pb-5 pt-1">
                        <button onclick="openCustomizerModal('${item.id}')" class="w-full py-2 sm:py-2.5 rounded-xl bg-charcoal-900 hover:bg-gold-600 text-white text-[10px] sm:text-xs font-semibold uppercase flex items-center justify-center gap-1.5 transition">
                            <i class="fa-solid fa-sliders"></i> Customize
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function filterShop(category) { renderProducts(category); }

        function renderFanpageLookbook() {
            const grid = document.getElementById('fanpage-grid');
            grid.innerHTML = fanpagePosts.map(post => `
                <div class="bg-white rounded-2xl overflow-hidden border border-gold-200/80 shadow-sm flex flex-col justify-between group">
                    <div>
                        <div class="relative h-40 sm:h-72 overflow-hidden bg-stone-200">
                            <img src="${post.image}" alt="${post.title}" class="w-full h-full object-cover">
                            <div class="absolute top-2 left-2 bg-blue-600/90 text-white text-[9px] sm:text-[10px] font-semibold px-2 py-0.5 rounded-full flex items-center gap-1">
                                <i class="fa-brands fa-facebook"></i>
                                <span class="truncate max-w-[100px]">${post.tag}</span>
                            </div>
                        </div>
                        <div class="p-3 sm:p-4">
                            <h4 class="font-serif-luxury font-bold text-xs sm:text-base text-charcoal-900 line-clamp-2 leading-snug">${post.title}</h4>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between text-[10px] sm:text-[11px] text-gold-700 font-semibold border-t border-stone-100 mt-2">
                        <span>📍 23 Lê Lợi</span>
                    </div>
                </div>
            `).join('');
        }

        // Hero Slider
        let currentSlide = 0; const totalSlides = 3;
        function goToSlide(index) {
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById('slide-' + i);
                const dot = document.getElementById('dot-' + i);
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0'); slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-gold-500 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10'); slide.classList.add('opacity-0', 'z-0');
                    dot.className = 'w-2 h-2 rounded-full bg-white/50 transition-all';
                }
            }
            currentSlide = index;
        }
        function nextSlide() { goToSlide((currentSlide + 1) % totalSlides); }
        function prevSlide() { goToSlide((currentSlide - 1 + totalSlides) % totalSlides); }

        function openCustomizerModal(id) {
            activeProductForModal = products.find(p => p.id === id);
            document.getElementById('modal-product-title').textContent = activeProductForModal.title;
            document.getElementById('customizer-modal').classList.remove('hidden');
        }
        function closeCustomizerModal() { document.getElementById('customizer-modal').classList.add('hidden'); }
        function addCustomizedToBag() { bag.push(activeProductForModal); updateBagUI(); closeCustomizerModal(); showToast('Added to bag!'); }
        function toggleOrderDrawer() { document.getElementById('order-drawer').classList.toggle('hidden'); }
        function updateBagUI() { document.getElementById('cart-badge').textContent = bag.length; }
        
        function showToast(msg) {
            const t = document.getElementById('toast');
            document.getElementById('toast-msg').textContent = msg;
            t.classList.remove('hidden');
            setTimeout(() => t.classList.add('hidden'), 3000);
        }
        function toggleMobileMenu() { document.getElementById('mobile-menu').classList.toggle('hidden'); }
        function scrollToSection(id) { document.getElementById(id).scrollIntoView({ behavior: 'smooth' }); }

        window.onload = function() {
            renderProducts('all');
            renderFanpageLookbook();
            setInterval(nextSlide, 6000);
        };
    </script>
</body>
</html>
