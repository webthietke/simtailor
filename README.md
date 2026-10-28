<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sim Tailor – Bespoke Tailor Hoi An | simtailorhoian.com</title>
    <meta name="description" content="Sim Tailor (Dũng Design Bespoke Tailor) - Family bespoke design tailor made to measurements & Worldwide Shipping. 15+ years experience. Address: 23 Lê Lợi, Hội An, Đà Nẵng. Hotline/WhatsApp: 0906.440.883">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Playfair Display for Bespoke Luxury Headings & Inter for Clean UI -->
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
            overflow-x: hidden;
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
        /* Subtle stitched border effect for bespoke tailor feel */
        .stitch-border {
            background-image: repeating-linear-gradient(90deg, #c28a3b, #c28a3b 6px, transparent 6px, transparent 12px);
            background-position: bottom;
            background-size: 100% 1px;
            background-repeat: no-repeat;
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
        /* Chia 2 cột trên điện thoại và căn đều 4 cột chuẩn bên trong khung máy tính */
        .mobile-two-cols {
            display: grid !important;
            grid-template-columns: repeat(2, minmax(0, 1fr)) !important;
            gap: 0.75rem !important;
            width: 100% !important;
            box-sizing: border-box !important;
        }
        @media (min-width: 640px) {
            .mobile-two-cols {
                gap: 1.25rem !important;
            }
        }
        @media (min-width: 1024px) {
            .mobile-two-cols {
                grid-template-columns: repeat(4, minmax(0, 1fr)) !important;
                gap: 1.5rem !important;
            }
        }
        /* Đảm bảo thanh danh mục trên máy tính nhỏ gọn, phân bổ đều, không bao giờ tràn dưới nút giỏ hàng */
        .desktop-nav-even {
            display: none;
        }
        @media (min-width: 1024px) {
            .desktop-nav-even {
                display: flex !important;
                flex: 1 1 auto !important;
                align-items: center !important;
                justify-content: space-between !important;
                gap: 0.15rem !important;
                margin-left: 0.75rem !important;
                margin-right: 0.75rem !important;
                font-size: clamp(10px, 0.78vw, 12.5px) !important;
            }
        }
        @media (min-width: 1280px) {
            .desktop-nav-even {
                margin-left: 1.5rem !important;
                margin-right: 1.5rem !important;
            }
        }
        /* Ép 3 ảnh nằm gọn trên 1 hàng ngang trên cả điện thoại và máy tính */
        .three-photos-row {
            display: grid !important;
            grid-template-columns: repeat(3, minmax(0, 1fr)) !important;
            gap: 0.5rem !important;
            width: 100% !important;
        }
        @media (min-width: 640px) {
            .three-photos-row {
                gap: 1rem !important;
            }
        }
    </style>
</head>
<body class="antialiased selection:bg-gold-500 selection:text-white">

    <!-- ================= TOP ANNOUNCEMENT & CONTACT BAR ================= -->
    <div class="bg-charcoal-950 text-gold-100 text-[11px] sm:text-xs border-b border-gold-900/40">
        <div class="max-w-7xl mx-auto px-3 sm:px-6 lg:px-8 py-2 flex items-center justify-between gap-2">
            <!-- Left Contact Info -->
            <div class="flex flex-wrap items-center gap-x-3 sm:gap-x-6 gap-y-1">
                <a href="https://simtailorhoian.com" class="inline-flex items-center gap-1.5 text-gold-400 font-semibold tracking-wide hover:text-gold-300 transition">
                    <i class="fa-solid fa-globe text-[11px]"></i>
                    <span>simtailorhoian.com</span>
                </a>
                <a href="#contact" class="inline-flex items-center gap-1.5 hover:text-gold-300 transition">
                    <i class="fa-solid fa-location-dot text-gold-500 text-[11px]"></i>
                    <span>23 Lê Lợi, Hội An</span>
                </a>
                <a href="tel:0906440883" class="inline-flex items-center gap-1.5 hover:text-gold-300 transition font-medium">
                    <i class="fa-solid fa-phone-volume text-gold-500 text-[11px]"></i>
                    <span>0906.440.883</span>
                </a>
                <a href="mailto:v.thuysim@gmail.com" class="hidden md:inline-flex items-center gap-1.5 hover:text-gold-300 transition">
                    <i class="fa-solid fa-envelope text-gold-500"></i>
                    <span>v.thuysim@gmail.com</span>
                </a>
            </div>

            <!-- Right Utilities: Fanpage Link & Language Toggle -->
            <div class="flex items-center gap-2.5 shrink-0">
                <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex items-center gap-1.5 px-2.5 py-1 rounded-full bg-blue-600/20 text-blue-300 border border-blue-500/30 hover:bg-blue-600/30 transition">
                    <i class="fa-brands fa-facebook"></i>
                    <span>FB: Sim Tailor (Dũng Design)</span>
                </a>
                <!-- Language Switcher -->
                <div class="inline-flex items-center rounded-full bg-charcoal-800 p-0.5 border border-gold-500/40">
                    <button id="lang-en" onclick="setLanguage('en')" class="px-2.5 py-0.5 rounded-full text-[10px] sm:text-[11px] font-semibold transition bg-gold-600 text-white">EN</button>
                    <button id="lang-vi" onclick="setLanguage('vi')" class="px-2.5 py-0.5 rounded-full text-[10px] sm:text-[11px] font-semibold transition text-gold-200 hover:text-white">VI</button>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= MAIN HEADER & NAVIGATION (CĂN ĐỀU TRONG KHUNG MÁY TÍNH) ================= -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-gold-200/60 transition-all">
        <div class="max-w-7xl mx-auto px-3 sm:px-5 lg:px-6">
            <div class="flex items-center justify-between h-14 sm:h-16 gap-2">

                <!-- Brand Logo (Thu nhỏ gọn gàng trên máy tính) -->
                <a href="#" class="inline-flex items-center gap-1.5 sm:gap-2 group shrink-0">
                    <div class="w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-charcoal-900 border border-gold-500 flex items-center justify-center shadow-sm group-hover:border-gold-400 transition shrink-0">
                        <svg viewBox="0 0 64 64" class="w-4 h-4 sm:w-5 sm:h-5 block">
                            <circle cx="32" cy="32" r="28" fill="none" stroke="#c28a3b" stroke-width="1" stroke-dasharray="3 2.5" opacity="0.75"/>
                            <circle cx="32" cy="32" r="24" fill="none" stroke="#cea059" stroke-width="0.6" opacity="0.4"/>
                            <g transform="translate(32, 32)" fill="none" stroke="#e5c17c" stroke-width="2.6" stroke-linecap="round" stroke-linejoin="round">
                                <circle cx="-7" cy="-6" r="4.8"/>
                                <circle cx="-7" cy="6" r="4.8"/>
                                <line x1="-2.5" y1="-3" x2="11" y2="6.5"/>
                                <line x1="-2.5" y1="3" x2="11" y2="-6.5"/>
                                <circle cx="1.5" cy="0" r="1.2" fill="#e5c17c" stroke="none"/>
                            </g>
                        </svg>
                    </div>
                    <div class="flex flex-col justify-center">
                        <span class="font-serif-luxury text-xs sm:text-sm xl:text-[15px] font-bold tracking-wider text-charcoal-900 whitespace-nowrap leading-none">SIM TAILOR</span>
                        <div class="flex items-center gap-1 mt-0.5">
                            <span class="w-1.5 h-[1px] bg-gold-500"></span>
                            <span class="text-[6.5px] sm:text-[7px] uppercase tracking-[0.1em] text-gold-700 font-bold whitespace-nowrap leading-none">HỘI AN • EST. 2011</span>
                        </div>
                    </div>
                </a>

                <!-- Desktop Navigation Menu (Nhỏ gọn, tự động căn đều, không bao giờ nằm dưới nút giỏ hàng) -->
                <nav class="desktop-nav-even font-medium text-charcoal-800 whitespace-nowrap">
                    <a href="#home" class="px-1 py-1 rounded text-gold-600 font-semibold hover:text-gold-700 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_home">Home</a>
                    <a href="#about" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_about">About Us</a>
                    <a href="#media-showcase" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition flex items-center gap-1 shrink-0">
                        <i class="fa-solid fa-circle-play text-gold-600 text-[9px]"></i>
                        <span data-i18n="nav_video">Video & Gallery</span>
                    </a>
                    <a href="#process" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_process">Our Process</a>
                    <a href="#measure" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_measure">How To Measure</a>

                    <!-- Cloth Shop Dropdown -->
                    <div class="relative group py-3 shrink-0">
                        <a href="#cloth-shop" class="px-1 py-1 rounded flex items-center gap-1 hover:text-gold-600 hover:bg-gold-50/70 transition">
                            <span data-i18n="nav_shop">Cloth Shop</span>
                            <i class="fa-solid fa-chevron-down text-[7px] text-stone-400 group-hover:rotate-180 transition-transform"></i>
                        </a>
                        <div class="absolute left-1/2 -translate-x-1/2 top-full w-60 bg-white rounded-xl shadow-xl border border-gold-200/80 py-2 opacity-0 invisible group-hover:opacity-100 group-hover:visible transition-all duration-200 transform translate-y-2 group-hover:translate-y-0 z-50">
                            <button onclick="filterShop('all'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_all">All Bespoke Collection</span>
                                <i class="fa-solid fa-arrow-right text-xs text-gold-500"></i>
                            </button>
                            <button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_women">Women Luxurious Clothes</span>
                                <span class="text-[10px] bg-pink-100 text-pink-700 px-1.5 py-0.5 rounded">Silk & Dress</span>
                            </button>
                            <button onclick="filterShop('men'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_men">Men's Clothes</span>
                                <span class="text-[10px] bg-stone-100 text-stone-700 px-1.5 py-0.5 rounded">Suits & Shirts</span>
                            </button>
                            <button onclick="filterShop('family'); scrollToSection('cloth-shop')" class="w-full text-left px-4 py-2.5 text-sm hover:bg-gold-50 hover:text-gold-700 flex items-center justify-between">
                                <span data-i18n="cat_family">Couple & Family Sets</span>
                                <span class="text-[10px] bg-gold-100 text-gold-800 px-1.5 py-0.5 rounded">Fanpage Hit</span>
                            </button>
                        </div>
                    </div>

                    <a href="#lookbook" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_lookbook">Lookbook</a>
                    <a href="#blogs" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_blogs">Blogs</a>
                    <a href="#reviews" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_reviews">Reviews</a>
                    <a href="#contact" class="px-1 py-1 rounded hover:text-gold-600 hover:bg-gold-50/70 transition shrink-0" data-i18n="nav_contact">Contact</a>
                </nav>

                <!-- Action Buttons: Search, Bespoke Bag & Book Appointment (Nhỏ gọn, tách biệt bên phải) -->
                <div class="flex items-center gap-1.5 shrink-0">
                    <!-- Search Toggle -->
                    <button onclick="toggleSearchModal()" class="w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-stone-100 hover:bg-gold-100 text-charcoal-800 hover:text-gold-700 flex items-center justify-center transition border border-stone-200/80" title="Search">
                        <i class="fa-solid fa-magnifying-glass text-[10px] sm:text-[11px]"></i>
                    </button>

                    <!-- Custom Order Bag -->
                    <button onclick="toggleOrderDrawer()" class="relative w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-stone-100 hover:bg-gold-100 text-charcoal-800 hover:text-gold-700 flex items-center justify-center transition border border-stone-200/80" title="Your Bespoke Order List">
                        <i class="fa-solid fa-bag-shopping text-[10px] sm:text-[11px]"></i>
                        <span id="cart-badge" class="absolute -top-1 -right-1 w-3.5 h-3.5 rounded-full bg-gold-600 text-white text-[8px] font-bold flex items-center justify-center shadow">0</span>
                    </button>

                    <!-- Book Fitting CTA -->
                    <a href="#contact" class="hidden sm:inline-flex items-center gap-1 px-2.5 py-1.5 rounded-full bg-charcoal-900 hover:bg-gold-600 text-white text-[10px] xl:text-[11px] font-semibold tracking-wide transition shadow-md whitespace-nowrap">
                        <i class="fa-regular fa-calendar-check"></i>
                        <span data-i18n="btn_book_fitting">Book Fitting</span>
                    </a>

                    <!-- Mobile Hamburger -->
                    <button onclick="toggleMobileMenu()" class="lg:hidden w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-charcoal-900 text-gold-400 flex items-center justify-center shadow-sm">
                        <i id="mobile-menu-icon" class="fa-solid fa-bars text-xs"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gold-200 px-4 pt-3 pb-6 space-y-2 shadow-xl">
            <a href="#home" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50 text-gold-700" data-i18n="nav_home">Home</a>
            <a href="#about" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_about">About Us</a>
            <a href="#media-showcase" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50 text-gold-700" data-i18n="nav_video">Video & Gallery</a>
            <a href="#process" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_process">Our Process</a>
            <a href="#measure" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_measure">How To Measure</a>
            <a href="#cloth-shop" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_shop">Cloth Shop (Men & Women)</a>
            <a href="#lookbook" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_lookbook">Fanpage Lookbook</a>
            <a href="#blogs" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_blogs">Blogs</a>
            <a href="#reviews" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_reviews">Reviews</a>
            <a href="#contact" onclick="toggleMobileMenu()" class="block px-3 py-2 rounded-lg font-medium hover:bg-gold-50" data-i18n="nav_contact">Contact</a>
            <div class="pt-3 border-t border-stone-200 flex flex-col gap-2">
                <a href="tel:0906440883" class="w-full py-2.5 rounded-xl bg-gold-600 text-white text-center font-semibold text-sm">
                    <i class="fa-solid fa-phone mr-1.5"></i> Call / Zalo: 0906.440.883
                </a>
            </div>
        </div>
    </header>

    <!-- ================= HERO BANNER SLIDER (SIMON THE TAILOR STYLE) ================= -->
    <section id="home" class="relative bg-charcoal-950 overflow-hidden">
        <div class="relative h-[540px] sm:h-[620px] lg:h-[680px] w-full">

            <!-- Slide 1: Bespoke Suits & Master Tailor Sim -->
            <div id="slide-0" class="hero-slide absolute inset-0 opacity-100 z-10">
                <img id="hero-img-0" src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Sim+Tailor+Hoi+An'"
                     alt="Sim Tailor Bespoke Suit Hoi An" class="w-full h-full object-cover object-center brightness-50">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/90 via-charcoal-950/60 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/20 border border-gold-400/50 text-gold-300 text-xs uppercase tracking-widest font-semibold">
                            <i class="fa-solid fa-award"></i>
                            <span data-i18n="hero1_badge">MOST REASONABLE - HIGH QUALITY TAILOR IN HOI AN</span>
                        </div>
                        <h1 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight">
                            Sim Tailor Hoi An <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl" data-i18n="hero1_sub">Family Bespoke Design Tailor</span>
                        </h1>
                        <p class="text-stone-200 text-base sm:text-lg leading-relaxed max-w-xl" data-i18n="hero1_desc">
                            "Hello everyone, I am Sim Tailor, with 15 years of experience." Custom suits, silk dresses & family outfits made to your exact measurements in 24–48 hours at 23 Lê Lợi, Hội An, Đà Nẵng & Worldwide Shipping.
                        </p>
                        <div class="flex flex-wrap items-center gap-3 sm:gap-4 pt-2">
                            <a href="#cloth-shop" class="px-6 sm:px-7 py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm tracking-wider uppercase transition shadow-lg shadow-gold-900/50">
                                <span data-i18n="btn_explore_shop">Explore Cloth Shop</span>
                            </a>
                            <a href="#media-showcase" class="px-5 sm:px-6 py-3.5 rounded-full bg-white/15 hover:bg-white/25 backdrop-blur-md border border-gold-400/60 text-white font-semibold text-sm tracking-wider uppercase transition flex items-center gap-2">
                                <i class="fa-brands fa-youtube text-red-500 text-lg"></i>
                                <span>Watch Video & 3 Photos</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 2: Women's Luxurious Silk Dresses & Evening Wear -->
            <div id="slide-1" class="hero-slide absolute inset-0 opacity-0 z-0">
                <img id="hero-img-1" src="https://images.unsplash.com/photo-1566174053879-31528523f8ae?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Sim+Tailor+Silk+Dresses'"
                     alt="Sim Tailor Silk Dresses" class="w-full h-full object-cover object-center brightness-50">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/90 via-charcoal-950/60 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/20 border border-gold-400/50 text-gold-300 text-xs uppercase tracking-widest font-semibold">
                            <i class="fa-solid fa-wand-magic-sparkles"></i>
                            <span>SIM BESPOKE TAILOR • #SILKDRESSES #HOIANSUIT</span>
                        </div>
                        <h2 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight">
                            Women Luxurious <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl">Silk Dresses & Couture</span>
                        </h2>
                        <p class="text-stone-200 text-base sm:text-lg leading-relaxed max-w-xl">
                            🌱 "A beautiful girl in a black dress, made by Sim Tailor 🪡🧵🌸" — Handcrafted Hoi An mulberry silk gowns, top & skirt sets, and tailored women's suits designed to flatter every silhouette.
                        </p>
                        <div class="flex flex-wrap items-center gap-4 pt-2">
                            <button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="px-7 py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm tracking-wider uppercase transition shadow-lg">
                                View Women's Collection
                            </button>
                            <a href="#lookbook" class="px-6 py-3.5 rounded-full bg-white/10 hover:bg-white/20 backdrop-blur-md border border-white/30 text-white font-semibold text-sm tracking-wider uppercase transition">
                                See Fanpage Lookbook
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slide 3: Family, Couple & Worldwide Shipping -->
            <div id="slide-2" class="hero-slide absolute inset-0 opacity-0 z-0">
                <img id="hero-img-2" src="https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=1920&q=85" 
                     onerror="this.src='https://placehold.co/1920x1080/1f1e1c/c28a3b?text=Bespoke+Tailoring+23+Le+Loi'"
                     alt="Master Tailoring at 23 Le Loi Hoi An" class="w-full h-full object-cover object-center brightness-50">
                <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950/90 via-charcoal-950/60 to-transparent"></div>
                <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-full flex items-center">
                    <div class="max-w-2xl text-white space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/20 border border-gold-400/50 text-gold-300 text-xs uppercase tracking-widest font-semibold">
                            <i class="fa-solid fa-plane-departure"></i>
                            <span>23 LÊ LỢI, HỘI AN, ĐÀ NẴNG • WORLDWIDE SHIPPING</span>
                        </div>
                        <h2 class="font-serif-luxury text-4xl sm:text-5xl lg:text-6xl font-bold leading-tight">
                            Made To Measurements <br>
                            <span class="text-gold-400 font-cormorant italic font-normal text-3xl sm:text-5xl">& Global Delivery</span>
                        </h2>
                        <p class="text-stone-200 text-base sm:text-lg leading-relaxed max-w-xl">
                            Loved by travelers from France 🇫🇷, Iceland 🇮🇸, Denmark 🇩🇰, Australia 🇦🇺 & beyond. We keep your measurement profile on file so you can reorder bespoke garments from anywhere in the world.
                        </p>
                        <div class="flex flex-wrap items-center gap-4 pt-2">
                            <a href="#measure" class="px-7 py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm tracking-wider uppercase transition shadow-lg">
                                How To Measure Online
                            </a>
                            <a href="#contact" class="px-6 py-3.5 rounded-full bg-white/10 hover:bg-white/20 backdrop-blur-md border border-white/30 text-white font-semibold text-sm tracking-wider uppercase transition">
                                Visit 23 Lê Lợi, Hội An
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Slider Controls -->
            <div class="absolute bottom-14 sm:bottom-16 left-4 sm:left-8 z-30 flex items-center gap-2.5">
                <button onclick="prevSlide()" class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-black/50 hover:bg-gold-600 text-white border border-white/25 flex items-center justify-center transition backdrop-blur-sm">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <div class="flex items-center gap-2 px-3 py-2 rounded-full bg-black/45 backdrop-blur-sm border border-white/15">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-gold-500 transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                    <button onclick="goToSlide(2)" id="dot-2" class="w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                </div>
                <button onclick="nextSlide()" class="w-9 h-9 sm:w-10 sm:h-10 rounded-full bg-black/50 hover:bg-gold-600 text-white border border-white/25 flex items-center justify-center transition backdrop-blur-sm">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
            </div>
        </div>
    </section>

    <!-- ================= 4 SIGNATURE PILLAR CARDS (CĂN ĐỀU TRONG KHUNG MÁY TÍNH) ================= -->
    <section class="relative z-20 -mt-10 sm:-mt-12 max-w-7xl mx-auto px-3 sm:px-6 lg:px-8">
        <div class="mobile-two-cols grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
            <!-- Card 1: ABOUT US -->
            <a href="#about" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between h-full">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-medal"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider sm:tracking-widest text-gold-600 font-semibold">Sim Tailor Hoi An</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-0.5 sm:mt-1" data-i18n="pillar1_title">ABOUT US</h3>
                    <p class="text-[11px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar1_desc">
                        15+ years of family bespoke craftsmanship at 23 Lê Lợi, Hội An. Formerly Dũng Design Bespoke Tailor.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2.5 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="read_more">Discover Our Story</span>
                    <i class="fa-solid fa-arrow-right text-[10px] sm:text-xs"></i>
                </div>
            </a>

            <!-- Card 2: WHAT WE DO? -->
            <a href="#process" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between h-full">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-scissors"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider sm:tracking-widest text-gold-600 font-semibold">Our Process</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-0.5 sm:mt-1" data-i18n="pillar2_title">WHAT WE DO?</h3>
                    <p class="text-[11px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar2_desc">
                        Custom suits, silk dresses & ensembles tailored in 24–48 hours with multiple fittings & worldwide shipping.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2.5 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="see_process">See 4-Step Process</span>
                    <i class="fa-solid fa-arrow-right text-[10px] sm:text-xs"></i>
                </div>
            </a>

            <!-- Card 3: HOW TO MEASURE -->
            <a href="#measure" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between h-full">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-ruler-combined"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider sm:tracking-widest text-gold-600 font-semibold">Remote & In-Store</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-0.5 sm:mt-1" data-i18n="pillar3_title">HOW TO MEASURE</h3>
                    <p class="text-[11px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar3_desc">
                        Interactive body measurement guide to send your exact size online for worldwide custom tailoring.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2.5 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="open_guide">Open Measurement Tool</span>
                    <i class="fa-solid fa-arrow-right text-[10px] sm:text-xs"></i>
                </div>
            </a>

            <!-- Card 4: CUSTOMER LOOKBOOK -->
            <a href="#lookbook" class="group bg-white rounded-2xl p-3.5 sm:p-6 shadow-xl border border-gold-200/70 hover:border-gold-500 transition-all flex flex-col justify-between h-full">
                <div>
                    <div class="w-9 h-9 sm:w-12 sm:h-12 rounded-xl bg-gold-50 text-gold-600 flex items-center justify-center text-base sm:text-xl mb-2.5 sm:mb-4 group-hover:bg-gold-600 group-hover:text-white transition">
                        <i class="fa-solid fa-camera-retro"></i>
                    </div>
                    <p class="text-[10px] sm:text-xs uppercase tracking-wider sm:tracking-widest text-gold-600 font-semibold">Fanpage Gallery</p>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-charcoal-900 mt-0.5 sm:mt-1" data-i18n="pillar4_title">CUSTOMER LOOKBOOK</h3>
                    <p class="text-[11px] sm:text-xs text-stone-600 mt-1.5 sm:mt-2 leading-snug sm:leading-relaxed" data-i18n="pillar4_desc">
                        Real photos & stories from our Facebook page: happy clients from France, Iceland, Denmark & Vietnam.
                    </p>
                </div>
                <div class="mt-3 sm:mt-4 pt-2.5 sm:pt-3 border-t border-stone-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-gold-700 group-hover:translate-x-1 transition-transform">
                    <span data-i18n="view_photos">View Fanpage Photos</span>
                    <i class="fa-solid fa-arrow-right text-[10px] sm:text-xs"></i>
                </div>
            </a>
        </div>
    </section>

    <!-- ================= ABOUT US SECTION (SIM TAILOR STORY) ================= -->
    <section id="about" class="py-20 sm:py-24 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
            <!-- Left Image Collage from Fanpage Identity -->
            <div class="lg:col-span-6 relative">
                <div class="grid grid-cols-2 gap-4">
                    <div class="space-y-4">
                        <div class="relative rounded-2xl overflow-hidden shadow-lg border-2 border-gold-200 group">
                            <img id="fanpage-about-1" src="https://drive.google.com/thumbnail?id=1GxtnLxagsL82-9aOn260VjMYYsouZH9J&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1GxtnLxagsL82-9aOn260VjMYYsouZH9J=w1200';"
                                 alt="Sim Tailor Bespoke Studio 23 Le Loi" class="w-full h-64 object-cover">
                        </div>
                        <div class="bg-charcoal-900 text-white p-5 rounded-2xl shadow-lg border border-gold-500/40">
                            <div class="flex items-center gap-3">
                                <span class="text-3xl font-serif-luxury font-bold text-gold-400">15+</span>
                                <span class="text-xs uppercase tracking-wider text-stone-300 leading-snug">Years of Master Bespoke Tailoring in Hoi An</span>
                            </div>
                        </div>
                    </div>
                    <div class="space-y-4 pt-6">
                        <div class="bg-gold-600 text-white p-5 rounded-2xl shadow-lg">
                            <p class="font-serif-luxury italic text-base">"Sim Tailor is a family bespoke design tailor made to measurements & Worldwide Shipping."</p>
                            <p class="text-[11px] uppercase tracking-widest mt-2 text-gold-100">— 📍 23 Lê Lợi, Hội An</p>
                        </div>
                        <div class="relative rounded-2xl overflow-hidden shadow-lg border-2 border-gold-200">
                            <img id="fanpage-about-2" src="https://drive.google.com/thumbnail?id=1Um7tl2Nfbkq5-lXckZV5Rx3nphV-w9jI&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Um7tl2Nfbkq5-lXckZV5Rx3nphV-w9jI=w1200';"
                                 alt="Custom Suit Fitting at Sim Tailor" class="w-full h-64 object-cover">
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right Content (SimonTheTailor Layout + DungDesignTailor Bio) -->
            <div class="lg:col-span-6 space-y-6">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-100 text-gold-800 text-xs font-semibold uppercase tracking-widest">
                    <i class="fa-solid fa-scissors"></i>
                    <span>SIM TAILOR • FORMERLY DŨNG DESIGN TAILOR</span>
                </div>
                <h2 class="font-serif-luxury text-3xl sm:text-4xl lg:text-5xl font-bold text-charcoal-900 leading-tight" data-i18n="about_heading">
                    Crafted With Heart at <span class="text-gold-600">23 Lê Lợi, Hội An</span>
                </h2>
                <p class="text-stone-600 leading-relaxed text-base" data-i18n="about_p1">
                    Led by Master Tailor <strong>Thúy Sim</strong> with over <strong>15 years of hands-on tailoring experience</strong> (established on Facebook as <em>Dũng Design Bespoke Tailor / Sim Tailor</em>), <strong>Sim Tailor</strong> is a beloved family-owned custom tailoring house right in the heart of Hoi An Ancient Town at <strong>23 Lê Lợi, Hội An, Đà Nẵng</strong>.
                </p>
                <p class="text-stone-600 leading-relaxed text-base" data-i18n="about_p2">
                    Rooted in strong family values and decades of artisanal heritage, we combine superior fabrics—from breathable Hoi An mulberry silk and pure linen to Italian cashmere wool—with meticulous hand-stitching to create bespoke masterpieces. Travelers from France, Iceland, Denmark, Australia, and around the world consistently choose us for flawless fits, 24–48 hour turnaround, and genuinely warm, non-pushy service.
                </p>

                <!-- Key Highlights Grid -->
                <div class="grid grid-cols-2 gap-2.5 sm:gap-4 pt-2">
                    <div class="flex items-start gap-2.5 sm:gap-3 p-3 sm:p-3.5 rounded-xl bg-white border border-gold-200/70 shadow-sm">
                        <div class="w-8 h-8 sm:w-9 sm:h-9 rounded-lg bg-gold-100 text-gold-700 flex items-center justify-center shrink-0 mt-0.5">
                            <i class="fa-solid fa-clock text-xs sm:text-sm"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-xs sm:text-sm text-charcoal-900">Express 24–48h Turnaround</h4>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-0.5">Including 2–3 personal fittings & complimentary hotel delivery in Hoi An.</p>
                        </div>
                    </div>
                    <div class="flex items-start gap-2.5 sm:gap-3 p-3 sm:p-3.5 rounded-xl bg-white border border-gold-200/70 shadow-sm">
                        <div class="w-8 h-8 sm:w-9 sm:h-9 rounded-lg bg-gold-100 text-gold-700 flex items-center justify-center shrink-0 mt-0.5">
                            <i class="fa-solid fa-earth-americas text-xs sm:text-sm"></i>
                        </div>
                        <div>
                            <h4 class="font-semibold text-xs sm:text-sm text-charcoal-900">Worldwide Shipping</h4>
                            <p class="text-[11px] sm:text-xs text-stone-500 mt-0.5">We store your measurements so you can order more suits & dresses from home.</p>
                        </div>
                    </div>
                </div>

                <!-- Contact & Social Strip -->
                <div class="pt-4 flex flex-wrap items-center gap-4">
                    <a href="#cloth-shop" class="px-6 py-3 rounded-full bg-charcoal-900 hover:bg-gold-600 text-white text-sm font-semibold transition shadow-md">
                        Browse Bespoke Catalog
                    </a>
                    <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="px-5 py-3 rounded-full bg-white hover:bg-gold-50 text-charcoal-900 border border-gold-300 text-sm font-semibold transition flex items-center gap-2">
                        <i class="fa-brands fa-facebook text-blue-600"></i>
                        <span>Visit Our Facebook Fanpage</span>
                    </a>
                </div>
            </div>
        </div>

        <!-- ================= VIDEO YOUTUBE & 3 ẢNH GOOGLE DRIVE SHOWCASE ================= -->
        <div id="media-showcase" class="mt-20 pt-16 border-t border-gold-200/80">
            <div class="max-w-3xl mb-10">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-100 text-gold-800 text-xs font-semibold uppercase tracking-widest mb-2">
                    <i class="fa-solid fa-film text-gold-600"></i>
                    <span>SIM TAILOR STUDIO MEDIA • 23 LÊ LỢI, HỘI AN</span>
                </div>
                <h3 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-charcoal-900" data-i18n="media_heading">
                    Official Video & 3 Featured Studio Photos
                </h3>
                <p class="text-stone-600 text-sm sm:text-base mt-1.5" data-i18n="media_sub">
                    Explore our authentic bespoke tailoring studio video at <strong>Sim Tailor (23 Lê Lợi, Hội An)</strong> alongside 3 featured photos from our official collection.
                </p>
            </div>

            <!-- Main Layout: Left/Top YouTube Video (XQ1tiNhU2KQ) + Right/Bottom 3 Real Google Drive Photos -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-stretch">
                <!-- YouTube Video Player Card (https://www.youtube.com/watch?v=XQ1tiNhU2KQ) -->
                <div class="lg:col-span-5 bg-charcoal-900 rounded-3xl p-4 sm:p-5 border border-gold-500/40 shadow-xl flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 mb-3">
                            <span class="inline-flex items-center gap-1.5 text-xs font-bold uppercase tracking-wider text-gold-400">
                                <i class="fa-brands fa-youtube text-red-500 text-base"></i>
                                <span>Sim Tailor Official Video</span>
                            </span>
                            <a href="https://www.youtube.com/watch?v=XQ1tiNhU2KQ" target="_blank" rel="noopener noreferrer" class="text-[11px] text-stone-300 hover:text-gold-300 underline flex items-center gap-1">
                                <span>Watch on YouTube</span>
                                <i class="fa-solid fa-arrow-up-right-from-square text-[9px]"></i>
                            </a>
                        </div>
                        <div class="relative w-full overflow-hidden rounded-2xl bg-black aspect-video sm:aspect-[16/10] border border-gold-500/30 shadow-inner">
                            <iframe 
                                class="w-full h-full"
                                src="https://www.youtube.com/embed/XQ1tiNhU2KQ?rel=0&modestbranding=1&playsinline=1" 
                                title="Sim Tailor Hoi An Official Video"
                                frameborder="0" 
                                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                                referrerpolicy="strict-origin-when-cross-origin"
                                allowfullscreen>
                            </iframe>
                        </div>
                    </div>
                    <div class="mt-4 pt-3 border-t border-stone-800 flex items-center justify-between gap-3 text-xs text-stone-300">
                        <div>
                            <p class="font-serif-luxury font-bold text-white text-sm">Sim Tailor – 23 Lê Lợi, Hội An</p>
                            <p class="text-[11px] text-stone-400">Bespoke Suits, Silk Dresses & Custom Tailoring</p>
                        </div>
                        <a href="https://wa.me/84906440883" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-xl bg-gold-600 hover:bg-gold-500 text-white font-semibold text-xs shrink-0 transition">
                            <i class="fa-brands fa-whatsapp mr-1"></i>0906.440.883
                        </a>
                    </div>
                </div>

                <!-- 3 Real Photos Loaded Directly from the 3 Provided Google Drive Links (1 Row on Mobile & Desktop) -->
                <div class="lg:col-span-7 flex flex-col justify-between">
                    <div id="drive-three-cards" class="three-photos-row h-full">
                        <!-- Photo 1: 1LfhNHNeeI7qhBAoyD6siRucBAz_7_dvU -->
                        <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                            <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                                <img id="drive-img-0" 
                                     src="https://drive.google.com/thumbnail?id=1LfhNHNeeI7qhBAoyD6siRucBAz_7_dvU&sz=w1200" 
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1LfhNHNeeI7qhBAoyD6siRucBAz_7_dvU=w1200';"
                                     alt="Sim Tailor Studio Photo 1" 
                                     class="zoom-img w-full h-full object-cover">
                                <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                    Photo 01
                                </span>
                            </div>
                            <div class="p-2 sm:p-3.5 bg-white">
                                <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Gallery #1</p>
                                <p class="text-[9px] sm:text-[11px] text-stone-500 truncate">23 Lê Lợi, Hội An</p>
                            </div>
                        </div>

                        <!-- Photo 2: 1RTw4FMaED7girFamAKt56bNogrPfERBK -->
                        <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                            <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                                <img id="drive-img-1" 
                                     src="https://drive.google.com/thumbnail?id=1RTw4FMaED7girFamAKt56bNogrPfERBK&sz=w1200" 
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1RTw4FMaED7girFamAKt56bNogrPfERBK=w1200';"
                                     alt="Sim Tailor Studio Photo 2" 
                                     class="zoom-img w-full h-full object-cover">
                                <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                    Photo 02
                                </span>
                            </div>
                            <div class="p-2 sm:p-3.5 bg-white">
                                <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Gallery #2</p>
                                <p class="text-[9px] sm:text-[11px] text-stone-500 truncate">Sim Tailor Couture</p>
                            </div>
                        </div>

                        <!-- Photo 3: 1hqePF8Kpppqv8KshkWzRuJATsUp4FP9f -->
                        <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                            <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                                <img id="drive-img-2" 
                                     src="https://drive.google.com/thumbnail?id=1hqePF8Kpppqv8KshkWzRuJATsUp4FP9f&sz=w1200" 
                                     onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1hqePF8Kpppqv8KshkWzRuJATsUp4FP9f=w1200';"
                                     alt="Sim Tailor Studio Photo 3" 
                                     class="zoom-img w-full h-full object-cover">
                                <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                    Photo 03
                                </span>
                            </div>
                            <div class="p-2 sm:p-3.5 bg-white">
                                <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Gallery #3</p>
                                <p class="text-[9px] sm:text-[11px] text-stone-500 truncate">Made to Measure</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Bộ Sưu Tập Đồ Cưới May Đo (Bespoke Wedding Gallery - Chuẩn 3 Cột Trên Điện Thoại) -->
            <div class="mt-10 sm:mt-12 pt-8 border-t border-gold-200/60">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-5">
                    <div>
                        <div class="inline-flex items-center gap-1.5 px-2.5 py-0.5 rounded-full bg-gold-100 text-gold-800 text-[10px] sm:text-xs font-semibold uppercase tracking-wider mb-1">
                            <i class="fa-solid fa-rings-wedding text-gold-600"></i>
                            <span data-i18n="wedding_badge">BESPOKE WEDDING & BRIDAL COLLECTION</span>
                        </div>
                        <h4 class="font-serif-luxury text-xl sm:text-2xl font-bold text-charcoal-900" data-i18n="wedding_heading">
                            Bespoke Wedding Suits & Bridal Dresses
                        </h4>
                    </div>
                    <a href="https://wa.me/84906440883?text=Hello%20Sim%20Tailor!%20I%20would%20like%20to%20inquire%20about%20Bespoke%20Wedding%20Outfits." target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 text-xs font-semibold text-gold-700 hover:text-gold-600">
                        <i class="fa-brands fa-whatsapp text-green-600 text-sm"></i>
                        <span data-i18n="wedding_cta">Book Wedding Fitting (0906.440.883)</span>
                        <i class="fa-solid fa-arrow-right text-[10px]"></i>
                    </a>
                </div>

                <!-- Lưới 3 cột tối ưu trên điện thoại và máy tính -->
                <div id="wedding-gallery-grid" class="three-photos-row">
                    <!-- Wedding Photo 1: 1Xyt0PwCW80x-22nhQd2YkxjXlnTUqC5a -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-0" 
                                 src="https://drive.google.com/thumbnail?id=1Xyt0PwCW80x-22nhQd2YkxjXlnTUqC5a&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1Xyt0PwCW80x-22nhQd2YkxjXlnTUqC5a=w1200';"
                                 alt="Sim Tailor Wedding Collection 1" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 01
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #1</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Bridal & Groom</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 2: 1WCTf-vjqjI-4swjQw93shwKDw5f6KeCt -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-1" 
                                 src="https://drive.google.com/thumbnail?id=1WCTf-vjqjI-4swjQw93shwKDw5f6KeCt&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1WCTf-vjqjI-4swjQw93shwKDw5f6KeCt=w1200';"
                                 alt="Sim Tailor Wedding Collection 2" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 02
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #2</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Tailored Suit & Gown</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 3: 1stw4bo0sPWSZujr1C9VxteOK-LE5r9To -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-2" 
                                 src="https://drive.google.com/thumbnail?id=1stw4bo0sPWSZujr1C9VxteOK-LE5r9To&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1stw4bo0sPWSZujr1C9VxteOK-LE5r9To=w1200';"
                                 alt="Sim Tailor Wedding Collection 3" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 03
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #3</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">23 Lê Lợi, Hội An</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 4: 10GtDgMR-O7AW80z9mGehgoxQwOIKfjN_ -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-3" 
                                 src="https://drive.google.com/thumbnail?id=10GtDgMR-O7AW80z9mGehgoxQwOIKfjN_&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/10GtDgMR-O7AW80z9mGehgoxQwOIKfjN_=w1200';"
                                 alt="Sim Tailor Wedding Collection 4" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 04
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #4</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Groom & Groomsmen</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 5: 1R42Yos9D85Jomlh8AC2yCZ9kyOebRmfv -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-4" 
                                 src="https://drive.google.com/thumbnail?id=1R42Yos9D85Jomlh8AC2yCZ9kyOebRmfv&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1R42Yos9D85Jomlh8AC2yCZ9kyOebRmfv=w1200';"
                                 alt="Sim Tailor Wedding Collection 5" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 05
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #5</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Luxury Silk & Wool</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 6: 1B42GsM2ht4NvvzBAl-Gk-cXqiO4_c7R8 -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-5" 
                                 src="https://drive.google.com/thumbnail?id=1B42GsM2ht4NvvzBAl-Gk-cXqiO4_c7R8&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1B42GsM2ht4NvvzBAl-Gk-cXqiO4_c7R8=w1200';"
                                 alt="Sim Tailor Wedding Collection 6" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 06
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #6</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Sim Tailor Couture</p>
                        </div>
                    </div>

                    <!-- Wedding Photo 7: 1TDL4NOJvgZpeVHqrHDuyObszhtUZfm0N -->
                    <div class="card-zoom bg-white rounded-xl sm:rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col justify-between group min-w-0">
                        <div class="relative h-36 sm:h-72 overflow-hidden bg-stone-100">
                            <img id="wedding-img-6" 
                                 src="https://drive.google.com/thumbnail?id=1TDL4NOJvgZpeVHqrHDuyObszhtUZfm0N&sz=w1200" 
                                 onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1TDL4NOJvgZpeVHqrHDuyObszhtUZfm0N=w1200';"
                                 alt="Sim Tailor Wedding Collection 7" 
                                 class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-1.5 left-1.5 sm:top-2.5 sm:left-2.5 px-1.5 sm:px-2.5 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[8px] sm:text-[10px] font-semibold backdrop-blur-sm">
                                Wedding 07
                            </span>
                        </div>
                        <div class="p-1.5 sm:p-3.5 bg-white">
                            <p class="font-serif-luxury font-bold text-charcoal-900 text-[10px] sm:text-sm truncate">Bespoke Wedding #7</p>
                            <p class="text-[8.5px] sm:text-[11px] text-stone-500 truncate">Made to Measure</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CLOTH SHOP SECTION (DANH MỤC NHỎ GỌN & CĂN ĐỀU TRONG TRANG WEB) ================= -->
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

            <!-- Category Tabs (Nhỏ gọn & căn đều 4 cột bằng nhau bên trong khung trang web trên máy tính) -->
            <div class="max-w-3xl mx-auto grid grid-cols-2 sm:grid-cols-4 gap-2 sm:gap-3 mt-7">
                <button onclick="filterShop('all')" id="tab-all" class="shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-charcoal-900 text-white shadow-md text-center truncate" data-i18n="cat_all">
                    All Collection
                </button>
                <button onclick="filterShop('men')" id="tab-men" class="shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100 text-center truncate" data-i18n="cat_men">
                    Men's Clothes
                </button>
                <button onclick="filterShop('women')" id="tab-women" class="shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100 text-center truncate" data-i18n="cat_women">
                    Women Luxurious Clothes
                </button>
                <button onclick="filterShop('family')" id="tab-family" class="shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100 text-center truncate" data-i18n="cat_family">
                    Couple & Family Sets
                </button>
            </div>

            <!-- Products Grid (Rendered dynamically via JS for filtering - 2 columns on mobile, 4 even columns on desktop) -->
            <div id="products-grid" class="mobile-two-cols grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6 mt-8 sm:mt-10">
                <!-- Populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- ================= FANPAGE LOOKBOOK & LIVE FEED (DUNG DESIGN TAILOR / SIM TAILOR) ================= -->
    <section id="lookbook" class="py-20 bg-ivory">
        <div class="max-w-7xl mx-auto px-3 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-10 sm:mb-12">
                <div>
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-blue-100 text-blue-800 text-xs font-semibold mb-3">
                        <i class="fa-brands fa-facebook"></i>
                        <span>synced from facebook.com/DungDesignTailor</span>
                    </div>
                    <h2 class="font-serif-luxury text-3xl sm:text-4xl font-bold text-charcoal-900" data-i18n="lookbook_heading">
                        Customer Lookbook & Fanpage Moments
                    </h2>
                    <p class="text-stone-600 text-sm sm:text-base mt-2 max-w-2xl" data-i18n="lookbook_sub">
                        Authentic creations and client feedback posted on our official fanpage <strong>Sim Tailor (Dũng Design Bespoke Tailor)</strong> at 23 Lê Lợi, Hội An.
                    </p>
                </div>
                <div class="flex flex-wrap items-center gap-3">
                    <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="px-4 py-2.5 rounded-full bg-charcoal-900 hover:bg-charcoal-800 text-white text-xs sm:text-sm font-semibold transition flex items-center gap-2">
                        <i class="fa-brands fa-facebook-f text-blue-400"></i>
                        <span>Follow @DungDesignTailor</span>
                    </a>
                </div>
            </div>

            <!-- Fanpage Posts Grid (2 columns on mobile, 4 even columns on desktop) -->
            <div id="fanpage-grid" class="mobile-two-cols grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6">
                <!-- Populated by JavaScript from real Fanpage Posts -->
            </div>
        </div>
    </section>

    <!-- ================= OUR PROCESS SECTION (4 STEPS IN 24-48H) ================= -->
    <section id="process" class="py-20 bg-charcoal-900 text-white relative overflow-hidden">
        <div class="max-w-7xl mx-auto px-3 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto space-y-3">
                <p class="text-xs uppercase tracking-widest text-gold-400 font-semibold">HOW WE CRAFT YOUR GARMENT</p>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold" data-i18n="process_heading">Our Bespoke Process</h2>
                <p class="text-stone-300 text-sm sm:text-base" data-i18n="process_sub">
                    Whether you visit us at <strong>23 Lê Lợi, Hội An, Đà Nẵng</strong> for our 24–48 hour express service or order remotely from abroad, every piece goes through 4 rigorous stages.
                </p>
            </div>

            <div class="mobile-two-cols grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-6 mt-10 sm:mt-12">
                <!-- Step 1 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-3 sm:top-4 sm:right-5 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">01</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-swatchbook"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Style & Fabric Consultation</h3>
                    <p class="text-[11px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Choose from 500+ premium fabrics (Mulberry Silk, Cashmere Wool, Linen, Egyptian Cotton) and customize lapels, buttons, linings, and monograms with Master Tailor Sim.
                    </p>
                </div>

                <!-- Step 2 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-3 sm:top-4 sm:right-5 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">02</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-ruler-vertical"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">25-Point Body Measurement</h3>
                    <p class="text-[11px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        We take over 25 precise anatomical measurements and posture notes so your suit or dress drapes naturally around your shoulders and waist.
                    </p>
                </div>

                <!-- Step 3 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-3 sm:top-4 sm:right-5 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">03</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-user-tie"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">First & Second Fittings</h3>
                    <p class="text-[11px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Within 12–24 hours, try on your garment at 23 Lê Lợi (or at your hotel). Master Tailor Sim pins and refines every millimeter for a second-skin fit.
                    </p>
                </div>

                <!-- Step 4 -->
                <div class="bg-charcoal-800/90 border border-gold-500/30 rounded-2xl p-4 sm:p-6 relative group hover:border-gold-400 transition">
                    <span class="absolute top-3 right-3 sm:top-4 sm:right-5 font-serif-luxury text-2xl sm:text-4xl font-bold text-gold-500/20 group-hover:text-gold-500/40 transition">04</span>
                    <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-xl bg-gold-500/20 text-gold-400 flex items-center justify-center text-base sm:text-xl mb-3 sm:mb-5">
                        <i class="fa-solid fa-plane-circle-check"></i>
                    </div>
                    <h3 class="font-serif-luxury text-sm sm:text-xl font-bold text-white">Pickup or Worldwide Delivery</h3>
                    <p class="text-[11px] sm:text-xs text-stone-300 mt-1.5 sm:mt-2.5 leading-snug sm:leading-relaxed">
                        Collect your pressed garment in a luxury suit bag, enjoy free hotel drop-off, or let us ship directly to your home country via DHL/FedEx.
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

                    <!-- SVG Anatomical Tailor Mannequin Diagram -->
                    <div class="my-6 bg-white rounded-2xl p-6 border border-gold-200/80 flex flex-col items-center">
                        <svg viewBox="0 0 260 320" class="w-56 h-64">
                            <!-- Mannequin Stand -->
                            <line x1="130" y1="260" x2="130" y2="305" stroke="#885626" stroke-width="6"/>
                            <path d="M90 305 L170 305" stroke="#885626" stroke-width="8" stroke-linecap="round"/>
                            <!-- Neck -->
                            <path d="M115 30 L145 30 L148 52 L112 52 Z" fill="#f5eedc" stroke="#1f1e1c" stroke-width="2"/>
                            <!-- Torso / Suit Silhouette -->
                            <path d="M68 65 Q130 48 192 65 L178 160 L185 255 L75 255 L82 160 Z" fill="#faf7f2" stroke="#1f1e1c" stroke-width="2.5"/>
                            <!-- Lapel lines -->
                            <path d="M112 52 L130 135 L148 52" fill="none" stroke="#c28a3b" stroke-width="2"/>
                            <!-- Measurement Lines -->
                            <!-- 1. Shoulder -->
                            <line x1="65" y1="65" x2="195" y2="65" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <circle cx="65" cy="65" r="4" fill="#c28a3b"/>
                            <circle cx="195" cy="65" r="4" fill="#c28a3b"/>
                            <text x="130" y="60" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">1. SHOULDER</text>

                            <!-- 2. Chest / Bust -->
                            <line x1="74" y1="110" x2="186" y2="110" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="105" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">2. CHEST / BUST</text>

                            <!-- 3. Waist -->
                            <line x1="82" y1="160" x2="178" y2="160" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="155" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">3. NATURAL WAIST</text>

                            <!-- 4. Hips -->
                            <line x1="76" y1="215" x2="184" y2="215" stroke="#c28a3b" stroke-width="2.5" stroke-dasharray="4 2"/>
                            <text x="130" y="210" text-anchor="middle" fill="#885626" font-size="10" font-weight="bold">4. HIPS / SEAT</text>

                            <!-- 5. Jacket / Dress Length -->
                            <line x1="48" y1="65" x2="48" y2="255" stroke="#1f1e1c" stroke-width="2" stroke-dasharray="3 3"/>
                            <text x="42" y="165" text-anchor="middle" fill="#1f1e1c" font-size="9" font-weight="bold" transform="rotate(-90 42 165)">5. TOTAL LENGTH</text>
                        </svg>
                        <p class="text-[11px] text-stone-500 text-center mt-2">
                            Tip: Keep one finger between the tape and your body for a comfortable bespoke allowance.
                        </p>
                    </div>

                    <div class="p-4 rounded-2xl bg-gold-50 border border-gold-200 text-xs text-stone-700 space-y-1.5">
                        <p class="font-bold text-charcoal-900"><i class="fa-solid fa-video text-gold-600 mr-1.5"></i> Free Live Video Measurement Assistance</p>
                        <p>Not sure about your measurements? Message Master Tailor Sim on WhatsApp <strong>+84 906 440 883</strong> for a 10-minute guided session.</p>
                    </div>
                </div>

                <!-- Right Interactive Measurement Form -->
                <div class="lg:col-span-7 bg-white rounded-3xl p-6 sm:p-8 border border-gold-200 shadow-lg">
                    <div class="flex flex-wrap items-center justify-between gap-4 pb-5 border-b border-stone-200">
                        <div>
                            <h3 class="font-serif-luxury text-2xl font-bold text-charcoal-900">Submit Your Measurement Profile</h3>
                            <p class="text-xs text-stone-500 mt-0.5">Save your measurements & send directly to Sim Tailor via WhatsApp or Email</p>
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
                                <input type="text" id="m-hw" placeholder="e.g. 175cm / 70kg" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                        </div>

                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-4">
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">1. Shoulder Width (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-shoulder" placeholder="45" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">2. Chest / Bust (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-chest" placeholder="98" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">3. Natural Waist (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-waist" placeholder="84" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">4. Hips / Seat (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-hips" placeholder="100" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">5. Sleeve Length (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-sleeve" placeholder="63" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-stone-700 mb-1">6. Jacket / Dress Length (<span class="unit-label">cm</span>)</label>
                                <input type="number" step="0.5" id="m-length" placeholder="74" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-stone-700 mb-1">Fit Preference & Fabric Notes</label>
                            <textarea id="m-notes" rows="2" placeholder="e.g. Slim European fit, navy mulberry silk or charcoal wool, shipping to France..." class="w-full px-3.5 py-2 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center gap-3 pt-2">
                            <button type="submit" class="px-6 py-3 rounded-full bg-gold-600 hover:bg-gold-500 text-white text-sm font-semibold transition shadow-md flex items-center gap-2">
                                <i class="fa-brands fa-whatsapp text-base"></i>
                                <span>Send Measurements via WhatsApp (0906.440.883)</span>
                            </button>
                            <button type="button" onclick="emailMeasurements()" class="px-5 py-3 rounded-full bg-charcoal-900 hover:bg-charcoal-800 text-white text-sm font-semibold transition flex items-center gap-2">
                                <i class="fa-regular fa-envelope"></i>
                                <span>Send via Email</span>
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= BLOGS SECTION (MATCHING SIMONTHETAILOR.COM) ================= -->
    <section id="blogs" class="py-20 bg-ivory border-t border-gold-200/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto space-y-3 mb-12">
                <p class="text-xs uppercase tracking-widest text-gold-600 font-bold">HOI AN TAILORING JOURNAL</p>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold text-charcoal-900" data-i18n="blogs_heading">Blogs & Style Guides</h2>
                <p class="text-stone-600 text-sm sm:text-base">
                    Hoi An is famous for its lanterns, and bringing home a custom-made bespoke suit or silk dress from <strong>Sim Tailor (23 Lê Lợi)</strong> is the ultimate travel memory.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Blog 1 -->
                <article class="bg-white rounded-2xl overflow-hidden shadow-md border border-gold-200/70 flex flex-col justify-between group">
                    <div>
                        <div class="relative h-56 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80" alt="Custom Suit Guide Hoi An" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-charcoal-900/90 text-gold-400 rounded-xl px-3 py-1.5 text-center leading-tight border border-gold-500/40">
                                <span class="block text-lg font-bold font-serif-luxury">01</span>
                                <span class="text-[10px] uppercase tracking-wider">Oct</span>
                            </div>
                        </div>
                        <div class="p-6">
                            <span class="text-[11px] font-semibold uppercase tracking-widest text-gold-600">Sim Tailor Guide</span>
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 mt-1 group-hover:text-gold-700 transition">
                                Ultimate Guide to Getting a Custom Suit & Silk Dress in Hoi An (2026)
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed">
                                Getting tailor-made clothing during a trip to Central Vietnam merges heritage artisanal craftsmanship with unmatched 24–48 hour turnaround efficiency...
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
                            <img src="https://images.unsplash.com/photo-1559592413-7cec4d0cae2b?auto=format&fit=crop&w=800&q=80" alt="23 Le Loi Hoi An Ancient Town" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-charcoal-900/90 text-gold-400 rounded-xl px-3 py-1.5 text-center leading-tight border border-gold-500/40">
                                <span class="block text-lg font-bold font-serif-luxury">12</span>
                                <span class="text-[10px] uppercase tracking-wider">Aug</span>
                            </div>
                        </div>
                        <div class="p-6">
                            <span class="text-[11px] font-semibold uppercase tracking-widest text-gold-600">Store Directions</span>
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 mt-1 group-hover:text-gold-700 transition">
                                👋 Visiting Us Soon? Here’s How to Find Sim Tailor at 23 Lê Lợi Easily!
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed">
                                Dear valued guests, as there are multiple tailor shops located in Hoi An Ancient Town, please double check our exact sign: <strong>Sim Tailor / Dũng Design Tailor at 23 Lê Lợi</strong>...
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
                            <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80" alt="Protecting Your Custom Suit" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="absolute top-4 left-4 bg-charcoal-900/90 text-gold-400 rounded-xl px-3 py-1.5 text-center leading-tight border border-gold-500/40">
                                <span class="block text-lg font-bold font-serif-luxury">10</span>
                                <span class="text-[10px] uppercase tracking-wider">Mar</span>
                            </div>
                        </div>
                        <div class="p-6">
                            <span class="text-[11px] font-semibold uppercase tracking-widest text-gold-600">Garment Care</span>
                            <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900 mt-1 group-hover:text-gold-700 transition">
                                Expert Tips from Sim Tailor for Protecting Your Custom Suit & Silk Back Home
                            </h3>
                            <p class="text-xs text-stone-600 mt-2.5 leading-relaxed">
                                When returning home from Hoi An with a bespoke wool suit or mulberry silk dress, follow these simple steps to preserve its structure and luster for years...
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

    <!-- ================= REVIEWS SECTION (TRIPADVISOR & FACEBOOK REVIEWS) ================= -->
    <section id="reviews" class="py-20 bg-white border-t border-gold-200/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto space-y-3 mb-12">
                <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-green-50 border border-green-200 text-green-800 text-xs font-bold">
                    <i class="fa-solid fa-star text-amber-400"></i>
                    <span>5.0 / 5.0 RATED BY INTERNATIONAL TRAVELERS ON FACEBOOK & TRIPADVISOR</span>
                </div>
                <h2 class="font-serif-luxury text-3xl sm:text-5xl font-bold text-charcoal-900" data-i18n="reviews_heading">What Our Clients Say</h2>
                <p class="text-stone-600 text-sm sm:text-base">
                    Feedback from our lovely clients visiting <strong>23 Lê Lợi, Hội An</strong> from France, Iceland, Denmark, Australia & Vietnam.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Review 1: Julie from France -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                            <span class="text-[11px] font-semibold px-2.5 py-0.5 rounded-full bg-blue-100 text-blue-800">
                                <i class="fa-brands fa-facebook mr-1"></i>Facebook Verified
                            </span>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Incredible silk dresses & warm family service!"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "Sim Tailor at 23 Lê Lợi is a gem in Hoi An! With 15 years of experience, Sim understood exactly what I wanted right away. She made a black evening dress and a top & skirt set for me that fit like a dream. Merci beaucoup!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-gold-600 text-white font-bold flex items-center justify-center text-sm">JL</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Julie Laurent 🇫🇷</p>
                            <p class="text-[11px] text-stone-500">Paris, France • Repeat Client</p>
                        </div>
                    </div>
                </div>

                <!-- Review 2: Family from Iceland -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                            <span class="text-[11px] font-semibold px-2.5 py-0.5 rounded-full bg-green-100 text-green-800">
                                <i class="fa-solid fa-check-circle mr-1"></i>TripAdvisor / FB
                            </span>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Best Hoi An tailor for our whole family!"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "We came as a family from Iceland and ordered custom suits, winter coats, and matching sets for brother & sister. From the minute we walked into 23 Lê Lợi, Sim made us feel comfortable, was never pushy, and finished everything in 36 hours!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-charcoal-900 text-gold-400 font-bold flex items-center justify-center text-sm">IS</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Sigurdsson Family 🇮🇸</p>
                            <p class="text-[11px] text-stone-500">Reykjavik, Iceland • Family Order</p>
                        </div>
                    </div>
                </div>

                <!-- Review 3: Couple Suit & Dress Order -->
                <div class="bg-ivory rounded-2xl p-6 border border-gold-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-4">
                            <div class="flex text-amber-400 text-sm gap-0.5">
                                <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                            </div>
                            <span class="text-[11px] font-semibold px-2.5 py-0.5 rounded-full bg-amber-100 text-amber-800">
                                <i class="fa-solid fa-award mr-1"></i>Top Pick 2026
                            </span>
                        </div>
                        <h4 class="font-serif-luxury font-bold text-lg text-charcoal-900">"Flawless Three-Piece Navy Suit & Silk Gown"</h4>
                        <p class="text-xs sm:text-sm text-stone-600 mt-2 leading-relaxed italic">
                            "One suit was made and I was so happy I got a second one made! True family business at 23 Lê Lợi with very reasonable prices and master quality work. Looks like we found our lifelong tailor in Vietnam!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 mt-6 pt-4 border-t border-gold-200/60">
                        <div class="w-10 h-10 rounded-full bg-gold-600 text-white font-bold flex items-center justify-center text-sm">AD</div>
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">Anders & Duyên 🇩🇰🇻🇳</p>
                            <p class="text-[11px] text-stone-500">Copenhagen & Hoi An • Couple Set</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= CONTACT & STORE LOCATION SECTION ================= -->
    <section id="contact" class="py-20 bg-charcoal-950 text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">

                <!-- Left Info & Hoi An Ancient Town Map Card -->
                <div class="lg:col-span-5 space-y-6">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 text-gold-300 text-xs font-semibold uppercase tracking-widest">
                        <i class="fa-solid fa-location-dot"></i>
                        <span>VISIT OUR BOUTIQUE IN HOI AN</span>
                    </div>
                    <h2 class="font-serif-luxury text-3xl sm:text-4xl font-bold text-white" data-i18n="contact_heading">
                        Sim Tailor – 23 Lê Lợi
                    </h2>
                    <p class="text-stone-300 text-sm leading-relaxed">
                        No appointment is required to walk in, or you can book a private fitting / complimentary hotel pick-up below.
                    </p>

                    <div class="space-y-4 pt-2">
                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-charcoal-900 border border-gold-800/40">
                            <div class="w-10 h-10 rounded-xl bg-gold-600/20 text-gold-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-map-location-dot text-lg"></i>
                            </div>
                            <div>
                                <p class="text-xs uppercase tracking-wider text-gold-400 font-semibold">Store Address</p>
                                <p class="text-sm sm:text-base font-bold text-white mt-0.5">23 Lê Lợi, Phố Cổ Hội An, Đà Nẵng, Việt Nam</p>
                                <p class="text-xs text-stone-400 mt-0.5">Right in the center of Hoi An Ancient Town (Near Japanese Covered Bridge & Thu Bon River)</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-charcoal-900 border border-gold-800/40">
                            <div class="w-10 h-10 rounded-xl bg-gold-600/20 text-gold-400 flex items-center justify-center shrink-0">
                                <i class="fa-solid fa-phone-volume text-lg"></i>
                            </div>
                            <div>
                                <p class="text-xs uppercase tracking-wider text-gold-400 font-semibold">Hotline / WhatsApp / Zalo (24/7)</p>
                                <a href="tel:0906440883" class="text-base sm:text-lg font-bold text-white hover:text-gold-400 transition block mt-0.5">0906.440.883 (+84 906 440 883)</a>
                                <p class="text-xs text-stone-400 mt-0.5">Email: v.thuysim@gmail.com • Web: simtailorhoian.com</p>
                            </div>
                        </div>

                        <div class="flex items-start gap-4 p-4 rounded-2xl bg-charcoal-900 border border-gold-800/40">
                            <div class="w-10 h-10 rounded-xl bg-gold-600/20 text-gold-400 flex items-center justify-center shrink-0">
                                <i class="fa-brands fa-instagram text-lg"></i>
                            </div>
                            <div>
                                <p class="text-xs uppercase tracking-wider text-gold-400 font-semibold">Official Social Channels</p>
                                <p class="text-sm font-semibold text-white mt-0.5">FB: Sim Tailor (DungDesignTailor)</p>
                                <p class="text-xs text-stone-400 mt-0.5">Instagram: @sim_tailor_hoi_an</p>
                            </div>
                        </div>
                    </div>

                    <!-- Interactive Stylized Map of 23 Le Loi, Hoi An -->
                    <div class="rounded-2xl overflow-hidden border border-gold-500/40 bg-charcoal-900 p-4">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-xs font-semibold text-gold-300"><i class="fa-solid fa-compass mr-1"></i> Hoi An Ancient Town Guide Map</span>
                            <a href="https://www.google.com/maps/search/?api=1&query=23+Le+Loi+Hoi+An" target="_blank" rel="noopener noreferrer" class="text-[11px] text-gold-400 underline hover:text-white">Open Google Maps</a>
                        </div>
                        <div class="relative h-44 rounded-xl bg-[#e8dfc8] text-charcoal-900 overflow-hidden p-3 flex items-center justify-center">
                            <svg viewBox="0 0 400 180" class="w-full h-full">
                                <!-- Roads -->
                                <rect width="400" height="180" fill="#efe6d5"/>
                                <!-- Thu Bon River -->
                                <path d="M0 155 Q200 140 400 160 L400 180 L0 180 Z" fill="#9cc0d6"/>
                                <text x="200" y="172" text-anchor="middle" fill="#2c5a78" font-size="9" font-weight="bold">THU BỒN RIVER (BẠCH ĐẰNG ST.)</text>
                                <!-- Horizontal Streets -->
                                <line x1="0" y1="50" x2="400" y2="50" stroke="#fff" stroke-width="10"/>
                                <text x="70" y="47" fill="#706554" font-size="8" font-weight="bold">TRẦN PHÚ STREET</text>
                                <line x1="0" y1="105" x2="400" y2="105" stroke="#fff" stroke-width="8"/>
                                <text x="70" y="102" fill="#706554" font-size="8" font-weight="bold">NGUYỄN THÁI HỌC STREET</text>
                                <!-- Vertical Street: LÊ LỢI -->
                                <line x1="210" y1="0" x2="210" y2="155" stroke="#f7c873" stroke-width="14"/>
                                <text x="210" y="25" text-anchor="middle" fill="#5d3b20" font-size="9" font-weight="bold">LÊ LỢI STREET</text>
                                <!-- Pin for 23 Lê Lợi -->
                                <circle cx="210" cy="78" r="14" fill="#c28a3b" opacity="0.3"/>
                                <circle cx="210" cy="78" r="7" fill="#b91c1c" stroke="#fff" stroke-width="2"/>
                                <rect x="222" y="64" width="145" height="28" rx="6" fill="#141311"/>
                                <text x="294" y="76" text-anchor="middle" fill="#f5eedc" font-size="9" font-weight="bold">📍 SIM TAILOR</text>
                                <text x="294" y="87" text-anchor="middle" fill="#cea059" font-size="8">23 Lê Lợi, Hội An</text>
                            </svg>
                        </div>
                    </div>
                </div>

                <!-- Right Booking & Inquiry Form -->
                <div class="lg:col-span-7">
                    <div class="bg-charcoal-900 rounded-3xl p-6 sm:p-10 border border-gold-500/30 shadow-2xl">
                        <h3 class="font-serif-luxury text-2xl sm:text-3xl font-bold text-white">Book A Fitting or Request A Quote</h3>
                        <p class="text-xs sm:text-sm text-stone-400 mt-1">
                            Fill in the form below and Master Tailor Sim will reply immediately via WhatsApp / Zalo (<strong class="text-gold-400">0906.440.883</strong>) or Email.
                        </p>

                        <form id="contact-form" onsubmit="submitContactForm(event)" class="space-y-4 mt-6">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Your Name *</label>
                                    <input type="text" id="c-name" required placeholder="Full Name" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">WhatsApp / Phone / Email *</label>
                                    <input type="text" id="c-contact" required placeholder="+84 / WhatsApp or Email" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Service Type</label>
                                    <select id="c-service" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                        <option value="In-Store Fitting at 23 Lê Lợi, Hội An">In-Store Fitting at 23 Lê Lợi, Hội An</option>
                                        <option value="Free Hotel Pick-up in Hoi An">Free Hotel Pick-up in Hoi An</option>
                                        <option value="Worldwide Shipping / Remote Order">Worldwide Shipping / Remote Order</option>
                                        <option value="Wedding / Group / Family Package">Wedding / Group / Family Package</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-stone-300 mb-1.5">Preferred Date / Arrival in Hoi An</label>
                                    <input type="date" id="c-date" class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-stone-300 mb-1.5">What would you like us to tailor for you?</label>
                                <textarea id="c-message" rows="4" placeholder="Tell us about the suits, silk dresses, linen shirts, or family outfits you have in mind..." class="w-full px-4 py-3 rounded-xl bg-charcoal-800 border border-stone-700 text-white text-sm focus:border-gold-500 focus:outline-none"></textarea>
                            </div>

                            <div class="pt-2 flex flex-wrap items-center gap-3">
                                <button type="submit" class="w-full sm:w-auto px-8 py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm tracking-wider uppercase transition shadow-lg flex items-center justify-center gap-2">
                                    <i class="fa-brands fa-whatsapp text-lg"></i>
                                    <span>Send Booking to Sim Tailor</span>
                                </button>
                                <a href="tel:0906440883" class="w-full sm:w-auto px-6 py-3.5 rounded-full bg-white/10 hover:bg-white/20 text-white font-semibold text-sm text-center transition">
                                    Call Direct: 0906.440.883
                                </a>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ================= FOOTER (SIMONTHETAILOR STYLE) ================= -->
    <footer class="bg-charcoal-950 text-stone-400 border-t border-gold-900/40 pt-14 pb-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-10 pb-12 border-b border-stone-800">
                <!-- Col 1 -->
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
                        Sim Tailor (formerly Dũng Design Bespoke Tailor) is a family bespoke design tailor made to measurements & Worldwide Shipping with over 15 years of experience in Hoi An.
                    </p>
                    <div class="flex items-center gap-3 pt-1">
                        <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-full bg-charcoal-800 hover:bg-blue-600 text-white flex items-center justify-center transition">
                            <i class="fa-brands fa-facebook-f text-sm"></i>
                        </a>
                        <a href="https://www.youtube.com/watch?v=XQ1tiNhU2KQ" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-full bg-charcoal-800 hover:bg-red-600 text-white flex items-center justify-center transition" title="Sim Tailor YouTube">
                            <i class="fa-brands fa-youtube text-sm"></i>
                        </a>
                        <a href="https://wa.me/84906440883" target="_blank" rel="noopener noreferrer" class="w-9 h-9 rounded-full bg-charcoal-800 hover:bg-green-600 text-white flex items-center justify-center transition">
                            <i class="fa-brands fa-whatsapp text-sm"></i>
                        </a>
                        <a href="mailto:v.thuysim@gmail.com" class="w-9 h-9 rounded-full bg-charcoal-800 hover:bg-gold-600 text-white flex items-center justify-center transition">
                            <i class="fa-regular fa-envelope text-sm"></i>
                        </a>
                    </div>
                </div>

                <!-- Col 2: Quick Links -->
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Quick Navigation</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#home" class="hover:text-gold-400 transition">Home</a></li>
                        <li><a href="#about" class="hover:text-gold-400 transition">About Us (15 Years Experience)</a></li>
                        <li><a href="#media-showcase" class="hover:text-gold-400 transition">Official Video & 3 Drive Photos</a></li>
                        <li><a href="#process" class="hover:text-gold-400 transition">Our Process (24–48h Turnaround)</a></li>
                        <li><a href="#measure" class="hover:text-gold-400 transition">How To Measure Online</a></li>
                        <li><a href="#lookbook" class="hover:text-gold-400 transition">Fanpage Customer Lookbook</a></li>
                        <li><a href="#blogs" class="hover:text-gold-400 transition">Blogs & Style Tips</a></li>
                    </ul>
                </div>

                <!-- Col 3: Cloth Shop Categories -->
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Cloth Shop</h4>
                    <ul class="space-y-2 text-xs">
                        <li><button onclick="filterShop('men'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Three Pieces Navy Men Suit</button></li>
                        <li><button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Women Luxurious Silk Dresses</button></li>
                        <li><button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Black Evening & Cocktail Dress</button></li>
                        <li><button onclick="filterShop('men'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Double Breasted Men Suit & Tuxedo</button></li>
                        <li><button onclick="filterShop('women'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Bespoke Top & Skirt Sets</button></li>
                        <li><button onclick="filterShop('family'); scrollToSection('cloth-shop')" class="hover:text-gold-400 transition">Sister & Brother / Family Matching Sets</button></li>
                    </ul>
                </div>

                <!-- Col 4: Contact Details -->
                <div>
                    <h4 class="font-serif-luxury text-base font-bold text-white mb-4">Contact Sim Tailor</h4>
                    <ul class="space-y-2.5 text-xs">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-gold-500 mt-1"></i>
                            <span>23 Lê Lợi, Hội An, Đà Nẵng, Việt Nam</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-gold-500"></i>
                            <a href="tel:0906440883" class="hover:text-white font-semibold">0906.440.883 (+84 906 440 883)</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-envelope text-gold-500"></i>
                            <a href="mailto:v.thuysim@gmail.com" class="hover:text-white">v.thuysim@gmail.com</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-gold-500"></i>
                            <a href="https://simtailorhoian.com" class="hover:text-white text-gold-400">www.simtailorhoian.com</a>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-regular fa-clock text-gold-500"></i>
                            <span>Open Daily: 08:00 AM – 09:30 PM</span>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="pt-6 flex flex-col sm:flex-row items-center justify-between text-xs text-stone-500 gap-4">
                <p>Copyright 2026 © <strong>Sim Tailor (simtailorhoian.com)</strong> – 23 Lê Lợi, Hội An, Đà Nẵng. All Rights Reserved.</p>
                <p>Inspired by Hoi An Bespoke Heritage • Fanpage: <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" class="text-gold-400 hover:underline">fb.com/DungDesignTailor</a></p>
            </div>
        </div>
    </footer>

    <!-- ================= FLOATING QUICK CONTACT BAR ================= -->
    <div class="fixed bottom-4 right-3.5 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
        <!-- Messenger / Fanpage -->
        <a href="https://www.facebook.com/DungDesignTailor/" target="_blank" rel="noopener noreferrer"
           class="group relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-gradient-to-tr from-blue-700 to-blue-500 text-white shadow-lg shadow-blue-950/30 border-2 border-white/90 flex items-center justify-center hover:scale-110 transition-transform"
           title="Facebook Fanpage Sim Tailor">
            <i class="fa-brands fa-facebook-messenger text-lg sm:text-xl leading-none"></i>
            <span class="pointer-events-none absolute right-full mr-3 px-3 py-1.5 rounded-xl bg-charcoal-900/95 text-white text-xs font-semibold whitespace-nowrap opacity-0 translate-x-2 group-hover:opacity-100 group-hover:translate-x-0 transition-all shadow-md hidden sm:block">
                FB: Sim Tailor
            </span>
        </a>

        <!-- Zalo 0906.440.883 -->
        <a href="https://zalo.me/0906440883" target="_blank" rel="noopener noreferrer"
           class="group relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-gradient-to-tr from-sky-600 to-cyan-400 text-white shadow-lg shadow-sky-950/30 border-2 border-white/90 flex items-center justify-center hover:scale-110 transition-transform"
           title="Chat Zalo 0906.440.883">
            <svg viewBox="0 0 40 40" class="w-7 h-7 sm:w-8 sm:h-8 block">
                <path d="M20 5C11.2 5 4 11.1 4 18.6c0 4.2 2.3 8 5.9 10.5-.3 1.6-1.1 3.7-1.2 3.9-.2.4.2.7.6.5 1.7-.7 4.4-2.1 5.8-2.9 1.5.4 3.2.6 4.9.6 8.8 0 16-6.1 16-13.6S28.8 5 20 5z" fill="#ffffff"/>
                <text x="20" y="22.5" text-anchor="middle" fill="#0284c7" font-family="Inter, Arial, sans-serif" font-size="10.5" font-weight="800" letter-spacing="-0.3">Zalo</text>
            </svg>
            <span class="pointer-events-none absolute right-full mr-3 px-3 py-1.5 rounded-xl bg-charcoal-900/95 text-white text-xs font-semibold whitespace-nowrap opacity-0 translate-x-2 group-hover:opacity-100 group-hover:translate-x-0 transition-all shadow-md hidden sm:block">
                Zalo: 0906.440.883
            </span>
        </a>

        <!-- WhatsApp +84906440883 -->
        <a href="https://wa.me/84906440883" target="_blank" rel="noopener noreferrer"
           class="group relative w-11 h-11 sm:w-12 sm:h-12 rounded-full bg-gradient-to-tr from-emerald-600 to-green-500 text-white shadow-lg shadow-green-950/30 border-2 border-white/90 flex items-center justify-center hover:scale-110 transition-transform"
           title="WhatsApp +84 906 440 883">
            <i class="fa-brands fa-whatsapp text-xl sm:text-2xl leading-none"></i>
            <span class="pointer-events-none absolute right-full mr-3 px-3 py-1.5 rounded-xl bg-charcoal-900/95 text-white text-xs font-semibold whitespace-nowrap opacity-0 translate-x-2 group-hover:opacity-100 group-hover:translate-x-0 transition-all shadow-md hidden sm:block">
                WhatsApp: +84 906 440 883
            </span>
        </a>

        <!-- Direct Phone Call -->
        <a href="tel:0906440883"
           class="pulse-gold flex items-center gap-2 bg-gradient-to-r from-charcoal-900 via-charcoal-800 to-charcoal-900 hover:from-gold-700 hover:to-gold-500 text-white pl-1.5 pr-3.5 py-1.5 rounded-full shadow-xl border-2 border-gold-400 transition-all">
            <span class="w-8 h-8 rounded-full bg-gold-500 text-white flex items-center justify-center shrink-0 shadow">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <div class="flex flex-col leading-tight text-left">
                <span class="text-[8px] uppercase tracking-widest text-gold-300 font-semibold">Hotline 24/7</span>
                <span class="text-xs font-bold tracking-wider text-white">0906.440.883</span>
            </div>
        </a>
    </div>

    <!-- ================= BESPOKE CUSTOMIZER & ORDER MODAL ================= -->
    <div id="customizer-modal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-gold-300 p-6 sm:p-8">
            <div class="flex items-start justify-between gap-4 pb-4 border-b border-stone-200">
                <div>
                    <span class="text-[11px] font-bold uppercase tracking-widest text-gold-600">SIM TAILOR BESPOKE STUDIO</span>
                    <h3 id="modal-product-title" class="font-serif-luxury text-2xl font-bold text-charcoal-900 mt-0.5">Three Pieces Navy Men Suit</h3>
                    <p id="modal-product-price" class="text-sm font-bold text-gold-700 mt-0.5">From $145</p>
                </div>
                <button onclick="closeCustomizerModal()" class="w-9 h-9 rounded-full bg-stone-100 hover:bg-stone-200 flex items-center justify-center text-stone-600">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>

            <div class="space-y-4 mt-5">
                <div>
                    <label class="block text-xs font-semibold text-stone-700 mb-1.5">1. Select Preferred Fabric</label>
                    <select id="cust-fabric" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none bg-white">
                        <option value="Hoi An Mulberry Silk (100% Natural)">Hoi An Mulberry Silk (100% Natural)</option>
                        <option value="Italian Super 130s Merino Wool">Italian Super 130s Merino Wool</option>
                        <option value="Premium Pure Hoi An Linen">Premium Pure Hoi An Linen</option>
                        <option value="Cashmere & Wool Winter Blend">Cashmere & Wool Winter Blend</option>
                        <option value="Egyptian Breathable Cotton">Egyptian Breathable Cotton</option>
                    </select>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-semibold text-stone-700 mb-1.5">2. Preferred Color / Shade</label>
                        <input type="text" id="cust-color" placeholder="e.g. Midnight Navy, Emerald, Black, Ivory..." class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-stone-700 mb-1.5">3. Fitting Option</label>
                        <select id="cust-fitting" class="w-full px-3.5 py-2.5 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none bg-white">
                            <option value="Visit 23 Lê Lợi, Hội An (24-48h Express)">Visit 23 Lê Lợi, Hội An (24-48h Express)</option>
                            <option value="Send Measurements Online (Worldwide Shipping)">Send Measurements Online (Worldwide Shipping)</option>
                            <option value="Free Hotel Pick-up & Fitting in Hoi An">Free Hotel Pick-up & Fitting in Hoi An</option>
                        </select>
                    </div>
                </div>

                <div>
                    <label class="block text-xs font-semibold text-stone-700 mb-1.5">4. Special Styling Notes (Lapel, Neckline, Length, Monogram)</label>
                    <textarea id="cust-notes" rows="2" placeholder="Any specific details or reference from our Facebook fanpage..." class="w-full px-3.5 py-2 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none"></textarea>
                </div>

                <div class="pt-3 flex flex-wrap items-center justify-end gap-3 border-t border-stone-200">
                    <button onclick="addCustomizedToBag()" class="px-5 py-2.5 rounded-full bg-charcoal-900 hover:bg-charcoal-800 text-white text-xs sm:text-sm font-semibold transition flex items-center gap-2">
                        <i class="fa-solid fa-bag-shopping"></i>
                        <span>Add to Bespoke Bag</span>
                    </button>
                    <button onclick="orderDirectWhatsApp()" class="px-6 py-2.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white text-xs sm:text-sm font-semibold transition shadow-md flex items-center gap-2">
                        <i class="fa-brands fa-whatsapp text-base"></i>
                        <span>Order Now via WhatsApp (0906.440.883)</span>
                    </button>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= BESPOKE ORDER BAG DRAWER ================= -->
    <div id="order-drawer" class="fixed inset-0 z-50 hidden bg-black/60 backdrop-blur-sm flex justify-end">
        <div class="bg-white w-full max-w-md h-full shadow-2xl flex flex-col justify-between p-6">
            <div>
                <div class="flex items-center justify-between pb-4 border-b border-stone-200">
                    <div>
                        <h3 class="font-serif-luxury text-xl font-bold text-charcoal-900">Your Bespoke Order Bag</h3>
                        <p class="text-xs text-stone-500">Sim Tailor • 23 Lê Lợi, Hội An (0906.440.883)</p>
                    </div>
                    <button onclick="toggleOrderDrawer()" class="w-8 h-8 rounded-full bg-stone-100 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>
                <div id="bag-items" class="mt-4 space-y-3 max-h-[60vh] overflow-y-auto">
                    <!-- Dynamic items -->
                </div>
            </div>
            <div class="pt-4 border-t border-stone-200 space-y-3">
                <button onclick="checkoutBagWhatsApp()" class="w-full py-3.5 rounded-full bg-gold-600 hover:bg-gold-500 text-white font-semibold text-sm flex items-center justify-center gap-2 shadow-lg">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                    <span>Send Full Order via WhatsApp (0906.440.883)</span>
                </button>
            </div>
        </div>
    </div>

    <!-- ================= SEARCH MODAL ================= -->
    <div id="search-modal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-start justify-center pt-24 p-4">
        <div class="bg-white rounded-2xl max-w-xl w-full p-6 shadow-2xl border border-gold-300">
            <div class="flex items-center justify-between mb-3">
                <span class="text-xs font-bold uppercase tracking-widest text-gold-600">Search Sim Tailor Catalog</span>
                <button onclick="toggleSearchModal()" class="text-stone-400 hover:text-charcoal-900"><i class="fa-solid fa-xmark"></i></button>
            </div>
            <div class="relative">
                <input type="text" id="search-input" oninput="performSearch(this.value)" placeholder="Search suits, silk dresses, tuxedo, winter coat, linen..." class="w-full pl-10 pr-4 py-3 rounded-xl border border-stone-300 text-sm focus:border-gold-600 focus:outline-none">
                <i class="fa-solid fa-magnifying-glass absolute left-3.5 top-3.5 text-stone-400"></i>
            </div>
            <div id="search-results" class="mt-4 max-h-64 overflow-y-auto divide-y divide-stone-100"></div>
        </div>
    </div>

    <!-- ================= BLOG READER MODAL ================= -->
    <div id="blog-modal" class="fixed inset-0 z-50 hidden bg-black/70 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-2xl w-full max-h-[85vh] overflow-y-auto p-6 sm:p-8 shadow-2xl border border-gold-300">
            <div class="flex items-start justify-between gap-4 pb-4 border-b border-stone-200">
                <h3 id="blog-modal-title" class="font-serif-luxury text-2xl font-bold text-charcoal-900"></h3>
                <button onclick="closeBlogModal()" class="w-9 h-9 rounded-full bg-stone-100 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="blog-modal-body" class="mt-4 text-sm text-stone-700 space-y-3 leading-relaxed"></div>
        </div>
    </div>

    <!-- ================= TOAST NOTIFICATION ================= -->
    <div id="toast" class="fixed bottom-6 left-6 z-50 hidden bg-charcoal-900 text-white px-5 py-3.5 rounded-2xl shadow-2xl border border-gold-500 flex items-center gap-3 text-xs sm:text-sm">
        <i class="fa-solid fa-circle-check text-gold-400 text-lg"></i>
        <span id="toast-msg">Notification</span>
    </div>

    <!-- ================= JAVASCRIPT LOGIC ================= -->
    <script>
        // Danh sách 3 File ID ảnh thực tế từ Google Drive đã được cung cấp
        const DRIVE_PHOTO_IDS = [
            '1LfhNHNeeI7qhBAoyD6siRucBAz_7_dvU',
            '1RTw4FMaED7girFamAKt56bNogrPfERBK',
            '1hqePF8Kpppqv8KshkWzRuJATsUp4FP9f'
        ];

        // Danh sách 7 File ID ảnh Đồ Cưới (Bespoke Wedding Collection) từ Google Drive
        const WEDDING_DRIVE_PHOTO_IDS = [
            '1Xyt0PwCW80x-22nhQd2YkxjXlnTUqC5a',
            '1WCTf-vjqjI-4swjQw93shwKDw5f6KeCt',
            '1stw4bo0sPWSZujr1C9VxteOK-LE5r9To',
            '10GtDgMR-O7AW80z9mGehgoxQwOIKfjN_',
            '1R42Yos9D85Jomlh8AC2yCZ9kyOebRmfv',
            '1B42GsM2ht4NvvzBAl-Gk-cXqiO4_c7R8',
            '1TDL4NOJvgZpeVHqrHDuyObszhtUZfm0N'
        ];

        // Gắn trực tiếp ảnh thực tế từ Google Drive vào các thẻ ảnh mà không bị lỗi CORS
        function loadDriveFolderImages() {
            DRIVE_PHOTO_IDS.forEach((fileId, index) => {
                const imgEl = document.getElementById('drive-img-' + index);
                if (imgEl) {
                    imgEl.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1200`;
                    imgEl.onerror = function() {
                        this.onerror = function() {
                            this.src = `https://drive.google.com/uc?export=view&id=${fileId}`;
                        };
                        this.src = `https://lh3.googleusercontent.com/d/${fileId}=w1200`;
                    };
                }
            });

            WEDDING_DRIVE_PHOTO_IDS.forEach((fileId, index) => {
                const imgEl = document.getElementById('wedding-img-' + index);
                if (imgEl) {
                    imgEl.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w1200`;
                    imgEl.onerror = function() {
                        this.onerror = function() {
                            this.src = `https://drive.google.com/uc?export=view&id=${fileId}`;
                        };
                        this.src = `https://lh3.googleusercontent.com/d/${fileId}=w1200`;
                    };
                }
            });
        }

        // 1. Cloth Shop Catalog (Combining simonthetailor.com items + DungDesignTailor fanpage specialties)
        const defaultProducts = [
            {
                id: 'p1',
                title: 'Three Pieces Navy Men Suit',
                category: 'men',
                price: 'From $145',
                badge: 'Bestseller',
                desc: 'Classic bespoke 3-piece suit (jacket, vest, trousers) crafted in breathable wool with custom silk lining.',
                image: 'https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p2',
                title: 'Black Cocktail & Evening Dress',
                category: 'women',
                price: 'From $85',
                badge: 'Fanpage Hit 🌱',
                desc: '🌱 "A beautiful girl in a black dress, made by Sim Tailor 🪡🧵🌸" — Tailored to flatter your exact silhouette.',
                image: 'https://images.unsplash.com/photo-1539008835657-9e8e9680c956?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p3',
                title: 'Hoi An Mulberry Silk Dress',
                category: 'women',
                price: 'From $90',
                badge: '#silkdresses',
                desc: '100% natural Hoi An mulberry silk dress, fluid drape, custom neckline, ideal for weddings & summer evenings.',
                image: 'https://images.unsplash.com/photo-1566174053879-31528523f8ae?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p4',
                title: 'Double Breasted Men Suit',
                category: 'men',
                price: 'From $140',
                badge: 'Sartorial',
                desc: 'Sharp peak lapels and structured shoulders inspired by Italian bespoke tailoring, finished in 24–48 hours.',
                image: 'https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p5',
                title: 'Bespoke Top & Skirt Set',
                category: 'women',
                price: 'From $95',
                badge: 'Fanpage New ✨',
                desc: '✨ "Top & skirt made by us 🙏☺️ Bespoke Tailor" — Elegant two-piece co-ord set in premium linen or silk.',
                image: 'https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p6',
                title: 'Dinner Tuxedo',
                category: 'men',
                price: 'From $160',
                badge: 'Black Tie',
                desc: 'Satin shawl or peak lapel tuxedo crafted for grooms and gala dinners with hand-finished details.',
                image: 'https://images.unsplash.com/photo-1555069519-127aadedf1ee?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p7',
                title: 'Women Tailored Power Suit',
                category: 'women',
                price: 'From $120',
                badge: 'Women Suit',
                desc: 'Bespoke women blazer and high-waisted trousers tailored in fine wool, linen, or silk blend.',
                image: 'https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p8',
                title: 'Men Business Shirt',
                category: 'men',
                price: 'From $35',
                badge: 'Custom Collar',
                desc: '100% Egyptian cotton or pure Hoi An linen shirt with complimentary monogrammed initials on cuff.',
                image: 'https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p9',
                title: 'Cashmere & Wool Winter Coat',
                category: 'men',
                price: 'From $150',
                badge: 'Winter Coats',
                desc: 'Warm, structured bespoke overcoat tailored for both men and women traveling back to colder climates.',
                image: 'https://images.unsplash.com/photo-1544022613-e87ca75a784a?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p10',
                title: 'Summer Linen Dress',
                category: 'women',
                price: 'From $75',
                badge: 'Tropical',
                desc: 'Breathable, lightweight Hoi An linen summer dress made to measurements in under 24 hours.',
                image: 'https://images.unsplash.com/photo-1496747611176-843222e1e57c?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p11',
                title: 'Sister & Brother Matching Set',
                category: 'family',
                price: 'From $110',
                badge: 'Fanpage Favorite 🫶',
                desc: '🫶 "Matching set for sister & brother ✨" — Coordinated bespoke family outfits in matching fabrics.',
                image: 'https://images.unsplash.com/photo-1511895426328-dc8714191300?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'p12',
                title: 'Couple Bespoke Suit & Dress 🇻🇳🇩🇰',
                category: 'family',
                price: 'From $210',
                badge: 'Pinned Post ❤️',
                desc: 'Inspired by our pinned fanpage post "Cặp đôi hoàn cảnh 🇻🇳🇩🇰" — Coordinated suit and dress for couples.',
                image: 'https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80'
            }
        ];

        // 2. Authentic Fanpage Posts extracted from https://www.facebook.com/DungDesignTailor/
        const defaultFanpagePosts = [
            {
                id: 'fp1',
                title: 'Black Evening Dress by Sim Tailor',
                caption: '🌱 A beautiful girl in a black dress, made by 𝙎𝙞𝙢 𝙩𝙖𝙞𝙡𝙤𝙧🪡🧵🌸 📍 23 Le Loi Hoi An Viet Nam 📞+84906440883 #hoiansuit #simtailor',
                tag: '8h • Public • FB: Sim Tailor',
                image: 'https://images.unsplash.com/photo-1539008835657-9e8e9680c956?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp2',
                title: '15 Years of Bespoke Experience',
                caption: '𝙃𝙚𝙡𝙡𝙤 𝙚𝙫𝙚𝙧𝙮𝙤𝙣𝙚, 𝙄 𝙖𝙢 𝙎𝙞𝙢 𝙩𝙖𝙞𝙡𝙤𝙧, 𝙬𝙞𝙩𝙝 15 𝙮𝙚𝙖𝙧𝙨 𝙤𝙛 𝙚𝙭𝙥𝙚𝙧𝙞𝙚𝙣𝙘𝙚. 🪡🧵🌸 📍 23 Le Loi Hoi An 📞+84906440883 #simbespoketailorhoian',
                tag: '5d • Public • Master Tailor Sim',
                image: 'https://images.unsplash.com/photo-1556905055-8f358a7a47b2?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp3',
                title: 'Tailor Made Suits By Us ✨',
                caption: 'Tailor made suits by us ✨✨✨ 🪡🧵 Sim Bespoke Tailor Hoi An 📍 23 Le Loi Hoi An Viet Nam 🇻🇳 #simtailor #hoiansuit #suit #custom',
                tag: '2w • Public • Custom Suits',
                image: 'https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp4',
                title: 'Top & Skirt Set Made By Us 🙏☺️',
                caption: 'Top & skirt made by us 🙏☺️✨✨✨ 🪡 Bespoke Tailor 🧵 📍 23 Le Loi Hoi An Viet Nam 🇻🇳 📞+84906440883 #simtailor #dresses',
                tag: '5w • Public • Women Couture',
                image: 'https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp5',
                title: 'Thank You Julie from France 🇫🇷',
                caption: 'Thank you, Julie come from the beautiful country France 🇫🇷. Thank you for your continued support. I\'m very grateful for it. 🙏❤️🫶🇻🇳',
                tag: '12w • Client Feedback • France',
                image: 'https://images.unsplash.com/photo-1566174053879-31528523f8ae?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp6',
                title: 'Matching Set for Sister & Brother 🫶',
                caption: 'Matching set for sister & brother 🫶🫶🫶✨✨✨ 🪡 Dung Design Bespoke Tailor 🧵 📍 23 Le Loi Hoi An #hoiancustomclothing',
                tag: '12w • Family Bespoke',
                image: 'https://images.unsplash.com/photo-1511895426328-dc8714191300?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp7',
                title: 'Lovely Family from Iceland 🇮🇸',
                caption: '𝙏𝙝𝙖𝙣𝙠 𝙮𝙤𝙪 𝙩𝙝𝙚 𝙛𝙖𝙢𝙞𝙡𝙮 𝙛𝙧𝙤𝙢 𝐈𝐜𝐞𝐥𝐚𝐧𝐝 🇮🇸. 𝙎𝙤 𝙜𝙡𝙖𝙙 𝙛𝙤𝙧 𝙘𝙝𝙤𝙤𝙨𝙚 𝙪𝙨 𝙩𝙤 𝙤𝙧𝙙𝙚𝙧 𝙘𝙡𝙤𝙩𝙝𝙚𝙨. 🧵🪡🙏☘️🌹 📍 23 Le Loi Hoi An',
                tag: '12w • Client Feedback • Iceland',
                image: 'https://images.unsplash.com/photo-1529156069898-49953e39b3ac?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 'fp8',
                title: 'Cặp Đôi Hoàn Cảnh 🇻🇳🇩🇰 (Pinned)',
                caption: '📌 Pinned Post: Cặp đôi hoàn cảnh 🇻🇳🇩🇰 — Custom couple outfits tailored at Sim Tailor 23 Lê Lợi, Hội An 📞 +84906440883',
                tag: 'Pinned Post • Couple Collection',
                image: 'https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=800&q=80'
            }
        ];

        let products = [...defaultProducts];
        let fanpagePosts = [...defaultFanpagePosts];
        let bag = [];
        let currentCategory = 'all';
        let activeProductForModal = null;

        // Render Cloth Shop Products
        function renderProducts(category = 'all') {
            currentCategory = category;
            const grid = document.getElementById('products-grid');
            const filtered = category === 'all' ? products : products.filter(p => p.category === category);

            // Update tab styles (nhỏ gọn & căn đều 4 nút danh mục)
            ['all', 'men', 'women', 'family'].forEach(cat => {
                const btn = document.getElementById('tab-' + cat);
                if (btn) {
                    if (cat === category) {
                        btn.className = 'shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-charcoal-900 text-white shadow-md text-center truncate';
                    } else {
                        btn.className = 'shop-tab w-full px-3 py-2 rounded-full text-[11px] sm:text-xs font-semibold transition bg-stone-100 text-charcoal-800 hover:bg-gold-100 text-center truncate';
                    }
                }
            });

            grid.innerHTML = filtered.map(item => `
                <div class="card-zoom bg-ivory rounded-2xl overflow-hidden border border-gold-200/80 shadow-sm hover:shadow-xl transition-all flex flex-col justify-between group min-w-0">
                    <div>
                        <div class="relative h-40 sm:h-72 overflow-hidden bg-stone-200">
                            <img id="prod-img-${item.id}" src="${item.image}" 
                                 onerror="this.src='https://placehold.co/600x750/1f1e1c/c28a3b?text=${encodeURIComponent(item.title)}'"
                                 alt="${item.title}" class="zoom-img w-full h-full object-cover">
                            <span class="absolute top-2 left-2 sm:top-3 sm:left-3 px-2 sm:px-3 py-0.5 sm:py-1 rounded-full bg-charcoal-900/85 text-gold-300 text-[9px] sm:text-[11px] font-semibold backdrop-blur-sm">
                                ${item.badge}
                            </span>
                        </div>
                        <div class="p-2.5 sm:p-5">
                            <div class="flex flex-wrap items-center justify-between gap-1 text-[9px] sm:text-xs text-gold-700 font-bold uppercase tracking-wider">
                                <span class="truncate">${item.category === 'men' ? "Men's" : item.category === 'women' ? "Women's" : "Family"}</span>
                                <span class="text-[11px] sm:text-sm text-charcoal-900 font-extrabold">${item.price}</span>
                            </div>
                            <h3 class="font-serif-luxury text-xs sm:text-lg font-bold text-charcoal-900 mt-1 leading-snug line-clamp-2">${item.title}</h3>
                            <p class="text-[10px] sm:text-xs text-stone-600 mt-1 sm:mt-2 leading-snug sm:leading-relaxed line-clamp-2">${item.desc}</p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-5 sm:pb-5 pt-1 flex items-center">
                        <button onclick="openCustomizerModal('${item.id}')" class="w-full py-2 sm:py-2.5 px-2 rounded-xl bg-charcoal-900 hover:bg-gold-600 text-white text-[10px] sm:text-xs font-semibold tracking-normal sm:tracking-wider uppercase transition flex items-center justify-center gap-1">
                            <i class="fa-solid fa-sliders"></i>
                            <span class="truncate">Customize & Order</span>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        function filterShop(category) {
            renderProducts(category);
        }

        // Render Fanpage Lookbook Grid
        function renderFanpageLookbook() {
            const grid = document.getElementById('fanpage-grid');
            grid.innerHTML = fanpagePosts.map(post => `
                <div class="bg-white rounded-2xl overflow-hidden border border-gold-200/80 shadow-sm hover:shadow-xl transition flex flex-col justify-between group">
                    <div>
                        <div class="relative h-44 sm:h-72 overflow-hidden bg-stone-200">
                            <img id="fp-img-${post.id}" src="${post.image}" 
                                 onerror="this.src='https://placehold.co/600x750/1f1e1c/c28a3b?text=Sim+Tailor+Fanpage'"
                                 alt="${post.title}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <div class="absolute top-2 left-2 sm:top-3 sm:left-3 bg-blue-600/90 text-white text-[9px] sm:text-[10px] font-semibold px-2 sm:px-2.5 py-0.5 sm:py-1 rounded-full flex items-center gap-1 backdrop-blur-sm max-w-[90%]">
                                <i class="fa-brands fa-facebook shrink-0"></i>
                                <span class="truncate">${post.tag}</span>
                            </div>
                        </div>
                        <div class="p-3 sm:p-4">
                            <h4 class="font-serif-luxury font-bold text-xs sm:text-base text-charcoal-900 leading-snug line-clamp-2">${post.title}</h4>
                            <p class="text-[11px] sm:text-xs text-stone-600 mt-1 sm:mt-1.5 leading-snug sm:leading-relaxed line-clamp-3">${post.caption}</p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-2 border-t border-stone-100 flex items-center justify-between text-[10px] sm:text-[11px] text-gold-700 font-semibold">
                        <span class="truncate">📍 23 Lê Lợi</span>
                        <a href="https://wa.me/84906440883?text=${encodeURIComponent('Hi Sim Tailor! I love this outfit from your Fanpage: ' + post.title)}" target="_blank" class="hover:underline flex items-center gap-1 text-green-700 shrink-0">
                            <i class="fa-brands fa-whatsapp"></i> Order
                        </a>
                    </div>
                </div>
            `).join('');
        }

        // Hero Slider Logic
        let currentSlide = 0;
        const totalSlides = 3;

        function goToSlide(index) {
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById('slide-' + i);
                const dot = document.getElementById('dot-' + i);
                if (i === index) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-gold-500 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                    dot.className = 'w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                }
            }
            currentSlide = index;
        }

        function nextSlide() {
            goToSlide((currentSlide + 1) % totalSlides);
        }
        function prevSlide() {
            goToSlide((currentSlide - 1 + totalSlides) % totalSlides);
        }

        // Customizer Modal Logic
        function openCustomizerModal(productId) {
            const prod = products.find(p => p.id === productId);
            if (!prod) return;
            activeProductForModal = prod;
            document.getElementById('modal-product-title').textContent = prod.title;
            document.getElementById('modal-product-price').textContent = prod.price;
            document.getElementById('customizer-modal').classList.remove('hidden');
        }

        function closeCustomizerModal() {
            document.getElementById('customizer-modal').classList.add('hidden');
        }

        function addCustomizedToBag() {
            if (!activeProductForModal) return;
            const fabric = document.getElementById('cust-fabric').value;
            const color = document.getElementById('cust-color').value || 'Tailor Recommendation';
            const fitting = document.getElementById('cust-fitting').value;
            const notes = document.getElementById('cust-notes').value;

            bag.push({
                title: activeProductForModal.title,
                price: activeProductForModal.price,
                fabric,
                color,
                fitting,
                notes
            });
            updateBagUI();
            closeCustomizerModal();
            showToast(`Added "${activeProductForModal.title}" to your Bespoke Bag!`);
        }

        function orderDirectWhatsApp() {
            if (!activeProductForModal) return;
            const fabric = document.getElementById('cust-fabric').value;
            const color = document.getElementById('cust-color').value || 'Standard';
            const fitting = document.getElementById('cust-fitting').value;
            const notes = document.getElementById('cust-notes').value;

            const text = `Hello Sim Tailor (23 Lê Lợi, Hội An)!%0AI would like to order from simtailorhoian.com:%0A- Item: ${activeProductForModal.title} (${activeProductForModal.price})%0A- Fabric: ${fabric}%0A- Color: ${color}%0A- Fitting: ${fitting}%0A- Notes: ${notes}`;
            window.open(`https://wa.me/84906440883?text=${text}`, '_blank');
        }

        function updateBagUI() {
            document.getElementById('cart-badge').textContent = bag.length;
            const container = document.getElementById('bag-items');
            if (bag.length === 0) {
                container.innerHTML = `<p class="text-xs text-stone-500 py-8 text-center">Your bespoke order bag is currently empty. Select any garment from our Cloth Shop to customize.</p>`;
                return;
            }
            container.innerHTML = bag.map((item, idx) => `
                <div class="p-3.5 rounded-xl bg-ivory border border-gold-200 flex items-start justify-between gap-2">
                    <div>
                        <h4 class="font-bold text-xs text-charcoal-900">${item.title} <span class="text-gold-700">(${item.price})</span></h4>
                        <p class="text-[11px] text-stone-600 mt-0.5">Fabric: ${item.fabric} • Color: ${item.color}</p>
                        <p class="text-[10px] text-stone-500">${item.fitting}</p>
                    </div>
                    <button onclick="removeBagItem(${idx})" class="text-stone-400 hover:text-red-600 text-xs">
                        <i class="fa-solid fa-trash"></i>
                    </button>
                </div>
            `).join('');
        }

        function removeBagItem(idx) {
            bag.splice(idx, 1);
            updateBagUI();
        }

        function toggleOrderDrawer() {
            updateBagUI();
            document.getElementById('order-drawer').classList.toggle('hidden');
        }

        function checkoutBagWhatsApp() {
            if (bag.length === 0) {
                showToast('Please add at least one garment to your bag first.');
                return;
            }
            let summary = `Hello Sim Tailor (23 Lê Lợi, Hội An - 0906.440.883)!%0AI would like to place a bespoke order on simtailorhoian.com:%0A`;
            bag.forEach((it, i) => {
                summary += `%0A${i + 1}. ${it.title} (${it.price}) - Fabric: ${it.fabric}, Color: ${it.color}, Option: ${it.fitting}`;
            });
            window.open(`https://wa.me/84906440883?text=${summary}`, '_blank');
        }

        // Measurement Tool Logic
        let currentUnit = 'cm';
        function setMeasureUnit(unit) {
            currentUnit = unit;
            document.querySelectorAll('.unit-label').forEach(el => el.textContent = unit);
            document.getElementById('unit-cm').className = unit === 'cm' ? 'px-3 py-1 rounded-lg text-xs font-bold bg-charcoal-900 text-white' : 'px-3 py-1 rounded-lg text-xs font-bold text-stone-600';
            document.getElementById('unit-inch').className = unit === 'inch' ? 'px-3 py-1 rounded-lg text-xs font-bold bg-charcoal-900 text-white' : 'px-3 py-1 rounded-lg text-xs font-bold text-stone-600';
        }

        function getMeasurementSummary() {
            const name = document.getElementById('m-name').value;
            const garment = document.getElementById('m-garment').value;
            const hw = document.getElementById('m-hw').value;
            const shoulder = document.getElementById('m-shoulder').value;
            const chest = document.getElementById('m-chest').value;
            const waist = document.getElementById('m-waist').value;
            const hips = document.getElementById('m-hips').value;
            const sleeve = document.getElementById('m-sleeve').value;
            const length = document.getElementById('m-length').value;
            const notes = document.getElementById('m-notes').value;

            return `Bespoke Measurement Profile for Sim Tailor (simtailorhoian.com):
- Client: ${name} (${hw})
- Garment: ${garment}
- Shoulder: ${shoulder} ${currentUnit} | Chest/Bust: ${chest} ${currentUnit}
- Waist: ${waist} ${currentUnit} | Hips: ${hips} ${currentUnit}
- Sleeve: ${sleeve} ${currentUnit} | Total Length: ${length} ${currentUnit}
- Notes: ${notes}`;
        }

        function submitMeasurements(e) {
            e.preventDefault();
            const msg = encodeURIComponent(getMeasurementSummary());
            showToast('Opening WhatsApp to send your measurements to Master Tailor Sim...');
            window.open(`https://wa.me/84906440883?text=${msg}`, '_blank');
        }

        function emailMeasurements() {
            const name = document.getElementById('m-name').value || 'Valued Guest';
            const body = encodeURIComponent(getMeasurementSummary());
            window.location.href = `mailto:v.thuysim@gmail.com?subject=${encodeURIComponent('Bespoke Measurements - ' + name)}&body=${body}`;
        }

        // Contact Form Submission
        function submitContactForm(e) {
            e.preventDefault();
            const name = document.getElementById('c-name').value;
            const contact = document.getElementById('c-contact').value;
            const service = document.getElementById('c-service').value;
            const date = document.getElementById('c-date').value;
            const message = document.getElementById('c-message').value;

            const text = encodeURIComponent(`Hello Sim Tailor (23 Lê Lợi, Hội An)!
Booking / Inquiry from simtailorhoian.com:
- Name: ${name}
- Contact: ${contact}
- Service: ${service}
- Date: ${date || 'Flexible'}
- Details: ${message}`);

            showToast('Đang kết nối tới WhatsApp 0906.440.883 của Sim Tailor...');
            window.open(`https://wa.me/84906440883?text=${text}`, '_blank');
        }

        // Search Modal
        function toggleSearchModal() {
            const modal = document.getElementById('search-modal');
            modal.classList.toggle('hidden');
            if (!modal.classList.contains('hidden')) {
                document.getElementById('search-input').focus();
                performSearch('');
            }
        }

        function performSearch(query) {
            const q = query.toLowerCase().trim();
            const res = document.getElementById('search-results');
            const matches = products.filter(p => p.title.toLowerCase().includes(q) || p.desc.toLowerCase().includes(q));
            res.innerHTML = matches.map(m => `
                <div class="py-2.5 flex items-center justify-between gap-3">
                    <div class="flex items-center gap-3">
                        <img src="${m.image}" class="w-11 h-11 rounded-lg object-cover">
                        <div>
                            <p class="text-xs font-bold text-charcoal-900">${m.title}</p>
                            <p class="text-[11px] text-gold-700 font-semibold">${m.price}</p>
                        </div>
                    </div>
                    <button onclick="toggleSearchModal(); openCustomizerModal('${m.id}')" class="px-3 py-1.5 rounded-full bg-charcoal-900 text-white text-[11px] font-semibold">Select</button>
                </div>
            `).join('');
        }

        // Blog Articles Modal
        const blogArticles = [
            {
                title: 'Ultimate Guide to Getting a Custom Suit & Silk Dress at Sim Tailor Hoi An (2026)',
                body: `
                    <p>Hoi An is world-famous for its lantern-lit streets and centuries-old tailoring heritage. At <strong>Sim Tailor (formerly Dũng Design Bespoke Tailor)</strong> at <strong>23 Lê Lợi, Hội An, Đà Nẵng</strong>, Master Tailor Thúy Sim brings over 15 years of dedicated craftsmanship to every stitch.</p>
                    <h4 class="font-bold text-charcoal-900 mt-3">1. How Long Does It Take?</h4>
                    <p>Most bespoke suits, silk dresses, and top & skirt sets take <strong>24 to 48 hours</strong> from initial measurement to final pressing, including 2 to 3 personal fittings to guarantee a flawless silhouette.</p>
                    <h4 class="font-bold text-charcoal-900 mt-3">2. Worldwide Re-Ordering</h4>
                    <p>Once your measurements are perfected in our shop at 23 Lê Lợi, we archive your pattern so you can message us anytime on WhatsApp (<strong>+84 906 440 883</strong>) to have new garments tailored and shipped straight to your doorstep.</p>
                `
            },
            {
                title: '👋 Visiting Us Soon? Here’s How to Find Sim Tailor at 23 Lê Lợi Easily!',
                body: `
                    <p>Dear valued guests, as there are multiple tailor shops located in Hoi An Ancient Town, please double-check our address before walking in so you arrive at the genuine family shop:</p>
                    <ul class="list-disc pl-5 space-y-1 mt-2">
                        <li><strong>Shop Name:</strong> Sim Tailor (Dũng Design Bespoke Tailor)</li>
                        <li><strong>Exact Address:</strong> 23 Lê Lợi, Phố Cổ Hội An, Đà Nẵng</li>
                        <li><strong>Hotline / WhatsApp / Zalo:</strong> 0906.440.883 (+84 906 440 883)</li>
                    </ul>
                    <p class="mt-3">If you are staying at a hotel or resort in Hoi An or Da Nang, simply message us on WhatsApp and we will arrange complimentary pick-up or meet you right at 23 Lê Lợi!</p>
                `
            },
            {
                title: 'Expert Tips from Master Tailor Sim for Protecting Your Custom Suit & Silk Back Home',
                body: `
                    <p>To keep your bespoke Hoi An suit and mulberry silk dresses looking brand new for years:</p>
                    <ul class="list-disc pl-5 space-y-1.5 mt-2">
                        <li><strong>Hang with Contoured Wooden Hangers:</strong> Preserve the natural shoulder roll of your suit jacket.</li>
                        <li><strong>Steam Instead of Ironing:</strong> Use a garment steamer to release travel creases from wool and pure Hoi An mulberry silk.</li>
                        <li><strong>Gentle Hand Wash for Silk:</strong> Mulberry silk thrives with cool water and mild silk detergent; never wring dry.</li>
                    </ul>
                `
            }
        ];

        function openBlogModal(idx) {
            const art = blogArticles[idx];
            if (!art) return;
            document.getElementById('blog-modal-title').textContent = art.title;
            document.getElementById('blog-modal-body').innerHTML = art.body;
            document.getElementById('blog-modal').classList.remove('hidden');
        }
        function closeBlogModal() {
            document.getElementById('blog-modal').classList.add('hidden');
        }

        // Bilingual Support (EN / VI)
        const translations = {
            en: {
                nav_home: 'Home',
                nav_about: 'About Us',
                nav_video: 'Video & Gallery',
                nav_process: 'Our Process',
                nav_measure: 'How To Measure',
                nav_shop: 'Cloth Shop',
                nav_lookbook: 'Lookbook',
                nav_blogs: 'Blogs',
                nav_reviews: 'Reviews',
                nav_contact: 'Contact',
                btn_book_fitting: 'Book Fitting',
                hero1_badge: 'MOST REASONABLE - HIGH QUALITY TAILOR IN HOI AN',
                hero1_sub: 'Family Bespoke Design Tailor',
                hero1_desc: '"Hello everyone, I am Sim Tailor, with 15 years of experience." Custom suits, silk dresses & family outfits made to your exact measurements in 24–48 hours at 23 Lê Lợi, Hội An, Đà Nẵng & Worldwide Shipping.',
                btn_explore_shop: 'Explore Cloth Shop',
                pillar1_title: 'ABOUT US',
                pillar1_desc: '15+ years of family bespoke craftsmanship at 23 Lê Lợi, Hội An. Formerly Dũng Design Bespoke Tailor.',
                pillar2_title: 'WHAT WE DO?',
                pillar2_desc: 'Custom suits, silk dresses & ensembles tailored in 24–48 hours with multiple fittings & worldwide shipping.',
                pillar3_title: 'HOW TO MEASURE',
                pillar3_desc: 'Interactive body measurement guide to send your exact size online for worldwide custom tailoring.',
                pillar4_title: 'CUSTOMER LOOKBOOK',
                pillar4_desc: 'Real photos & stories from our Facebook page: happy clients from France, Iceland, Denmark & Vietnam.',
                media_heading: 'Official Video & 3 Featured Studio Photos',
                media_sub: 'Watch our real bespoke tailoring studio video at 23 Lê Lợi, Hội An alongside 3 featured photos from our official Google Drive gallery.',
                shop_heading: 'CLOTH SHOP',
                lookbook_heading: 'Customer Lookbook & Fanpage Moments',
                process_heading: 'Our Bespoke Process',
                measure_heading: 'How To Measure Yourself',
                blogs_heading: 'Blogs & Style Guides',
                reviews_heading: 'What Our Clients Say',
                contact_heading: 'Sim Tailor – 23 Lê Lợi',
                cat_all: 'All Collection',
                cat_men: "Men's Clothes",
                cat_women: 'Women Luxurious Clothes',
                cat_family: 'Couple & Family Sets'
            },
            vi: {
                nav_home: 'Trang Chủ',
                nav_about: 'Về Chúng Tôi',
                nav_video: 'Video & 3 Ảnh',
                nav_process: 'Quy Trình May',
                nav_measure: 'Cách Lấy Số Đo',
                nav_shop: 'Cửa Hàng May Đo',
                nav_lookbook: 'Ảnh Fanpage',
                nav_blogs: 'Cẩm Nang',
                nav_reviews: 'Đánh Giá',
                nav_contact: 'Liên Hệ',
                btn_book_fitting: 'Đặt Lịch May',
                hero1_badge: 'NHÀ MAY ĐO CAO CẤP & GIÁ HỢP LÝ NHẤT TẠI HỘI AN',
                hero1_sub: 'Nhà May Gia Đình Truyền Thống & Ship Quốc Tế',
                hero1_desc: '"Xin chào, tôi là Sim Tailor với hơn 15 năm kinh nghiệm may đo." Chuyên may đo Vest nam nữ, đầm lụa Hội An, đồ gia đình lấy nhanh trong 24–48h tại 23 Lê Lợi, Hội An, Đà Nẵng & Giao hàng toàn cầu.',
                btn_explore_shop: 'Khám Phá Bộ Sưu Tập',
                pillar1_title: 'VỀ SIM TAILOR',
                pillar1_desc: 'Hơn 15 năm kinh nghiệm may đo truyền thống tại 23 Lê Lợi, Hội An (tiền thân Dũng Design Bespoke Tailor).',
                pillar2_title: 'DỊCH VỤ CỦA CHÚNG TÔI',
                pillar2_desc: 'May đo Vest, đầm lụa, sơ mi hoàn thiện trong 24–48 giờ và lưu số đo gửi hàng đi toàn thế giới.',
                pillar3_title: 'HƯỚNG DẪN ĐO ONLINE',
                pillar3_desc: 'Công cụ nhập số đo trực tuyến tiện lợi để đặt may từ xa qua WhatsApp/Zalo 0906.440.883.',
                pillar4_title: 'ALBUM FANPAGE',
                pillar4_desc: 'Hình ảnh thực tế từ Fanpage Sim Tailor: khách hàng từ Pháp, Iceland, Đan Mạch và Việt Nam.',
                media_heading: 'Video Thực Tế & Bộ 3 Ảnh Nổi Bật Tại Sim Tailor',
                media_sub: 'Khám phá video thực tế tại tiệm may Sim Tailor (23 Lê Lợi, Hội An) cùng bộ 3 hình ảnh nổi bật từ thư mục Google Drive chính thức.',
                shop_heading: 'CỬA HÀNG MAY ĐO (CLOTH SHOP)',
                lookbook_heading: 'Album Khách Hàng & Bài Đăng Fanpage Sim Tailor',
                process_heading: 'Quy Trình May Đo 4 Bước Chuẩn Mực',
                measure_heading: 'Hướng Dẫn Tự Lấy Số Đo Tại Nhà',
                blogs_heading: 'Cẩm Nang May Đo Hội An',
                reviews_heading: 'Khách Hàng Quốc Tế Đánh Giá',
                contact_heading: 'Sim Tailor – 23 Lê Lợi, Hội An',
                cat_all: 'Tất Cả Bộ Sưu Tập',
                cat_men: 'Trang Phục Nam',
                cat_women: 'Trang Phục Nữ (Đầm Lụa)',
                cat_family: 'Set Gia Đình & Cặp Đôi'
            }
        };

        function setLanguage(lang) {
            const dict = translations[lang];
            if (!dict) return;
            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (dict[key]) el.textContent = dict[key];
            });
            document.getElementById('lang-en').className = lang === 'en'
                ? 'px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition bg-gold-600 text-white'
                : 'px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition text-gold-200 hover:text-white';
            document.getElementById('lang-vi').className = lang === 'vi'
                ? 'px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition bg-gold-600 text-white'
                : 'px-2.5 py-0.5 rounded-full text-[11px] font-semibold transition text-gold-200 hover:text-white';
            showToast(lang === 'vi' ? 'Đã chuyển sang Tiếng Việt' : 'Switched to English');
        }

        // Utility Functions
        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function scrollToSection(id) {
            const el = document.getElementById(id);
            if (el) el.scrollIntoView({ behavior: 'smooth' });
        }

        function showToast(message) {
            const toast = document.getElementById('toast');
            document.getElementById('toast-msg').textContent = message;
            toast.classList.remove('hidden');
            clearTimeout(window.toastTimer);
            window.toastTimer = setTimeout(() => {
                toast.classList.add('hidden');
            }, 3500);
        }

        // Initialize on Window Load
        window.onload = function() {
            renderProducts('all');
            renderFanpageLookbook();
            loadDriveFolderImages();
            // Auto advance hero slider every 6 seconds
            setInterval(nextSlide, 6000);
        };
    </script>
</body>
</html>
