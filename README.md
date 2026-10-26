<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SIM TAILOR | Nhà May Đo Cao Cấp Phố Cổ Hội An</title>
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,400&family=Inter:wght@300;400;500;600;700&family=Playfair+Display:ital,wght@0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

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
        /* Ép cứng chia 2 cột trên giao diện điện thoại cho Sản phẩm, Lookbook và Thẻ danh mục */
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
        /* Căn đều danh mục trên máy tính vào gọn bên trong khung trang */
        .desktop-category-bar {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 0.625rem;
            width: 100%;
        }
        @media (min-width: 640px) {
            .desktop-category-bar {
                grid-template-columns: repeat(3, minmax(0, 1fr));
            }
        }
        @media (min-width: 1024px) {
            .desktop-category-bar {
                grid-template-columns: repeat(6, minmax(0, 1fr));
                gap: 0.875rem;
            }
        }
        /* Lưới 3 ảnh Google Drive cân đối trên cả máy tính và điện thoại */
        .drive-three-cols {
            display: grid;
            grid-template-columns: repeat(1, minmax(0, 1fr));
            gap: 1rem;
            width: 100%;
        }
        @media (min-width: 640px) {
            .drive-three-cols {
                grid-template-columns: repeat(3, minmax(0, 1fr));
                gap: 1.5rem;
            }
        }
    </style>
</head>
<body class="antialiased selection:bg-gold-500 selection:text-white">

    <!-- Thông báo đầu trang (Top Announcement Bar) -->
    <div class="bg-charcoal-950 text-gold-200 text-xs sm:text-sm py-2.5 px-4 border-b border-gold-800/40">
        <div class="max-w-7xl mx-auto flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2">
                <i class="fa-solid fa-scissors text-gold-400"></i>
                <span><strong>SIM TAILOR HỘI AN</strong> — 15+ Năm Kinh Nghiệm May Đo Cao Cấp (Hoàn thiện nhanh trong 24h)</span>
            </div>
            <div class="hidden md:flex items-center gap-5 text-xs text-gold-100">
                <span><i class="fa-solid fa-location-dot text-gold-400 mr-1.5"></i>23A Lê Lợi, Phố Cổ Hội An</span>
                <span><i class="fa-solid fa-clock text-gold-400 mr-1.5"></i>09:00 – 21:00 (Mỗi ngày)</span>
                <a href="tel:0906440883" class="text-gold-300 hover:text-white font-medium transition">
                    <i class="fa-solid fa-phone-volume mr-1"></i>0906 440 883
                </a>
            </div>
        </div>
    </div>

    <!-- Thanh Điều Hướng Chính (Header căn đều bên trong khung trang) -->
    <header class="sticky top-0 z-40 bg-ivory/95 backdrop-blur-md stitch-border shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20 gap-4">
                <!-- Logo -->
                <a href="#trang-chu" class="flex items-center gap-3 shrink-0 group">
                    <div class="w-11 h-11 rounded-full bg-charcoal-900 border-2 border-gold-500 flex items-center justify-center text-gold-400 font-serif-luxury text-xl font-bold shadow-md group-hover:bg-gold-600 group-hover:text-white transition">
                        S
                    </div>
                    <div>
                        <span class="font-serif-luxury text-xl sm:text-2xl font-bold tracking-wider text-charcoal-900 block leading-none">SIM TAILOR</span>
                        <span class="font-cormorant text-xs sm:text-sm tracking-[0.22em] text-gold-700 uppercase block mt-0.5">Bespoke Hoi An</span>
                    </div>
                </a>

                <!-- Danh mục Menu trên Máy Tính: Căn đều bên trong khung max-w-7xl -->
                <nav class="hidden lg:flex items-center justify-center flex-1 max-w-3xl mx-auto">
                    <ul class="grid grid-cols-6 w-full text-center items-center bg-white/80 border border-gold-200/80 rounded-full p-1 shadow-sm">
                        <li>
                            <a href="#trang-chu" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                Trang Chủ
                            </a>
                        </li>
                        <li>
                            <a href="#danh-muc" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                Danh Mục
                            </a>
                        </li>
                        <li>
                            <a href="#san-pham" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                Bộ Sưu Tập
                            </a>
                        </li>
                        <li>
                            <a href="#anh-thuc-te" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                3 Ảnh Mới
                            </a>
                        </li>
                        <li>
                            <a href="#video-xuong-may" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                Video Thực Tế
                            </a>
                        </li>
                        <li>
                            <a href="#lookbook" class="block py-2 px-2 rounded-full text-xs xl:text-sm font-medium text-charcoal-800 hover:bg-gold-500 hover:text-white transition whitespace-nowrap">
                                Lookbook
                            </a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút Đặt Lịch & Menu Mobile -->
                <div class="flex items-center gap-2.5 shrink-0">
                    <a href="#dat-lich" class="hidden sm:inline-flex items-center gap-2 bg-charcoal-900 hover:bg-gold-600 text-white text-xs sm:text-sm font-medium px-4 py-2.5 rounded-full transition shadow-sm">
                        <i class="fa-regular fa-calendar-check text-gold-300"></i>
                        <span>Đặt Lịch Đo</span>
                    </a>
                    <button id="mobile-menu-btn" onclick="toggleMobileMenu()" class="lg:hidden w-10 h-10 rounded-full border border-gold-300 bg-white flex items-center justify-center text-charcoal-900 hover:bg-gold-50 transition" aria-label="Mở menu">
                        <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Menu Điện Thoại -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-gold-200 px-4 pt-3 pb-5 shadow-xl">
            <div class="grid grid-cols-2 gap-2 text-sm font-medium">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-solid fa-house text-gold-600"></i> Trang Chủ
                </a>
                <a href="#danh-muc" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-gold-600"></i> Danh Mục
                </a>
                <a href="#san-pham" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-solid fa-shirt text-gold-600"></i> Bộ Sưu Tập
                </a>
                <a href="#anh-thuc-te" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-brands fa-google-drive text-gold-600"></i> 3 Ảnh Mới
                </a>
                <a href="#video-xuong-may" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-brands fa-youtube text-red-600"></i> Video Thực Tế
                </a>
                <a href="#lookbook" onclick="toggleMobileMenu()" class="p-2.5 rounded-xl bg-gold-50 text-charcoal-900 flex items-center gap-2">
                    <i class="fa-solid fa-camera-retro text-gold-600"></i> Lookbook
                </a>
            </div>
            <a href="#dat-lich" onclick="toggleMobileMenu()" class="mt-3 w-full inline-flex items-center justify-center gap-2 bg-gold-600 text-white font-medium py-3 rounded-xl shadow">
                <i class="fa-regular fa-calendar-check"></i> Đặt Lịch May Đo Ngay
            </a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section id="trang-chu" class="relative bg-charcoal-950 text-white overflow-hidden">
        <!-- Hình nền chuyển cảnh -->
        <div class="relative min-h-[540px] sm:min-h-[620px] flex items-center">
            <div id="hero-slide-0" class="hero-slide absolute inset-0 opacity-100 scale-100">
                <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=1800&q=85" alt="Sim Tailor Bespoke Suit" class="w-full h-full object-cover object-center opacity-40" onerror="this.src='https://placehold.co/1600x900/141311/c28a3b?text=SIM+TAILOR+HOI+AN'">
            </div>
            <div id="hero-slide-1" class="hero-slide absolute inset-0 opacity-0 scale-105 pointer-events-none">
                <img src="https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=1800&q=85" alt="May Đo Thủ Công Hội An" class="w-full h-full object-cover object-center opacity-40" onerror="this.src='https://placehold.co/1600x900/1f1e1c/ead8b4?text=BESPOKE+TAILORING'">
            </div>
            <div id="hero-slide-2" class="hero-slide absolute inset-0 opacity-0 scale-105 pointer-events-none">
                <img src="https://images.unsplash.com/photo-1556905055-8f358a7a47b2?auto=format&fit=crop&w=1800&q=85" alt="Vải Cao Cấp Nhập Khẩu" class="w-full h-full object-cover object-center opacity-40" onerror="this.src='https://placehold.co/1600x900/141311/c28a3b?text=LUXURY+FABRICS'">
            </div>
            <div class="absolute inset-0 bg-gradient-to-r from-charcoal-950 via-charcoal-950/80 to-transparent"></div>

            <!-- Nội dung Hero -->
            <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24 w-full">
                <div class="max-w-2xl">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-gold-500/20 border border-gold-400/40 text-gold-300 text-xs sm:text-sm uppercase tracking-widest mb-5">
                        <i class="fa-solid fa-award text-gold-400"></i>
                        <span>Tinh Hoa May Đo Phố Cổ Hội An</span>
                    </div>
                    <h1 class="font-serif-luxury text-3xl sm:text-5xl lg:text-6xl font-bold leading-tight text-white">
                        Chuẩn Mực <span class="text-gold-400 italic font-normal">Bespoke</span> Dành Riêng Cho Bạn
                    </h1>
                    <p class="mt-5 text-sm sm:text-lg text-gray-300 leading-relaxed">
                        Tại <strong>Sim Tailor (23A Lê Lợi, Hội An)</strong>, mỗi bộ Suit, Đầm dạ hội và Áo dài đều được cắt may thủ công tỉ mỉ theo số đo độc bản của từng khách hàng với hơn 15 năm kinh nghiệm.
                    </p>
                    <div class="mt-8 flex flex-wrap items-center gap-3.5">
                        <a href="#san-pham" class="inline-flex items-center gap-2.5 bg-gold-500 hover:bg-gold-600 text-white font-semibold px-6 py-3.5 rounded-full shadow-lg transition">
                            <span>Khám Phá Bộ Sưu Tập</span>
                            <i class="fa-solid fa-arrow-right text-sm"></i>
                        </a>
                        <a href="#video-xuong-may" class="inline-flex items-center gap-2.5 bg-white/10 hover:bg-white/20 text-white border border-gold-300/40 font-medium px-6 py-3.5 rounded-full backdrop-blur-sm transition">
                            <i class="fa-solid fa-play text-gold-400"></i>
                            <span>Xem Video Sim Tailor</span>
                        </a>
                        <a href="#anh-thuc-te" class="inline-flex items-center gap-2 bg-charcoal-800/90 hover:bg-charcoal-800 text-gold-200 border border-gold-500/40 text-xs sm:text-sm font-medium px-4 py-3 rounded-full transition">
                            <i class="fa-brands fa-google-drive text-gold-400"></i>
                            <span>Xem 3 Ảnh Mới</span>
                        </a>
                    </div>

                    <!-- Thống kê nổi bật -->
                    <div class="mt-10 pt-8 border-t border-white/15 grid grid-cols-3 gap-4 sm:gap-8">
                        <div>
                            <div class="font-serif-luxury text-2xl sm:text-3xl font-bold text-gold-400">15+ Năm</div>
                            <div class="text-xs sm:text-sm text-gray-300 mt-0.5">Kinh nghiệm may đo</div>
                        </div>
                        <div>
                            <div class="font-serif-luxury text-2xl sm:text-3xl font-bold text-gold-400">24 Giờ</div>
                            <div class="text-xs sm:text-sm text-gray-300 mt-0.5">Hoàn thiện lấy nhanh</div>
                        </div>
                        <div>
                            <div class="font-serif-luxury text-2xl sm:text-3xl font-bold text-gold-400">4.8 ★</div>
                            <div class="text-xs sm:text-sm text-gray-300 mt-0.5">Đánh giá tại Hội An</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- DANH MỤC MAY ĐO (Sửa căn đều bên trong khung trang trên máy tính & 2 cột trên điện thoại) -->
    <section id="danh-muc" class="py-14 sm:py-20 bg-ivory stitch-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-10">
                <span class="font-cormorant text-sm sm:text-base uppercase tracking-[0.25em] text-gold-700 font-semibold block">Danh Mục Dịch Vụ</span>
                <h2 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-charcoal-900 mt-1">Danh Mục May Đo Cao Cấp</h2>
                <div class="w-20 h-0.5 bg-gold-500 mx-auto mt-3"></div>
                <p class="text-xs sm:text-sm text-gray-600 mt-3">
                    Tất cả danh mục được bố trí cân đối bên trong khung trang máy tính và chia 2 cột rõ ràng trên điện thoại.
                </p>
            </div>

            <!-- Thanh nút danh mục xem trên máy tính: Chia đều 6 cột bằng nhau 100% bên trong khung max-w-7xl -->
            <div class="desktop-category-bar mb-8">
                <button onclick="filterProducts('all')" data-cat-btn="all" class="cat-pill active-cat flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-charcoal-900 text-white border-charcoal-900">
                    <i class="fa-solid fa-border-all text-gold-400"></i>
                    <span>Tất Cả Danh Mục</span>
                </button>
                <button onclick="filterProducts('suit')" data-cat-btn="suit" class="cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500">
                    <i class="fa-solid fa-user-tie text-gold-600"></i>
                    <span>Vest & Suit Nam</span>
                </button>
                <button onclick="filterProducts('dress')" data-cat-btn="dress" class="cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500">
                    <i class="fa-solid fa-wand-magic-sparkles text-gold-600"></i>
                    <span>Đầm & Váy Thiết Kế</span>
                </button>
                <button onclick="filterProducts('aodai')" data-cat-btn="aodai" class="cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500">
                    <i class="fa-solid fa-fan text-gold-600"></i>
                    <span>Áo Dài Truyền Thống</span>
                </button>
                <button onclick="filterProducts('shirt')" data-cat-btn="shirt" class="cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500">
                    <i class="fa-solid fa-shirt text-gold-600"></i>
                    <span>Sơ Mi & Quần Âu</span>
                </button>
                <button onclick="filterProducts('coat')" data-cat-btn="coat" class="cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500">
                    <i class="fa-solid fa-vest-patches text-gold-600"></i>
                    <span>Áo Khoác & Măng Tô</span>
                </button>
            </div>

            <!-- 4 Thẻ Danh Mục Chính: 2 cột trên điện thoại, 4 cột đều nhau 100% trên máy tính (.mobile-two-cols) -->
            <div class="mobile-two-cols">
                <!-- Thẻ danh mục 1 -->
                <div onclick="filterAndScroll('suit')" class="card-zoom group cursor-pointer relative rounded-2xl overflow-hidden shadow-md border border-gold-200/80 bg-charcoal-900 aspect-[3/4]">
                    <img src="https://images.unsplash.com/photo-1593030761757-71fae45fa0e7?auto=format&fit=crop&w=800&q=80" alt="Vest & Suit Bespoke" class="zoom-img w-full h-full object-cover opacity-85" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Suit+Bespoke'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950 via-charcoal-950/30 to-transparent"></div>
                    <div class="absolute bottom-0 inset-x-0 p-3.5 sm:p-5 text-white">
                        <span class="text-[10px] sm:text-xs uppercase tracking-widest text-gold-300 block">Bespoke Menswear</span>
                        <h3 class="font-serif-luxury text-base sm:text-xl font-bold mt-0.5">Vest & Suit Quý Ông</h3>
                        <p class="text-[11px] sm:text-xs text-gray-300 mt-1 line-clamp-2">Cắt may chuẩn form châu Á & châu Âu, vải Wool Ý & Anh cao cấp.</p>
                        <span class="inline-flex items-center gap-1.5 text-xs text-gold-300 font-medium mt-2 group-hover:translate-x-1 transition">
                            Xem mẫu <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </div>

                <!-- Thẻ danh mục 2 -->
                <div onclick="filterAndScroll('dress')" class="card-zoom group cursor-pointer relative rounded-2xl overflow-hidden shadow-md border border-gold-200/80 bg-charcoal-900 aspect-[3/4]">
                    <img src="https://images.unsplash.com/photo-1566174053879-31528523f8ae?auto=format&fit=crop&w=800&q=80" alt="Đầm Dạ Hội & Váy Thiết Kế" class="zoom-img w-full h-full object-cover opacity-85" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Evening+Dress'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950 via-charcoal-950/30 to-transparent"></div>
                    <div class="absolute bottom-0 inset-x-0 p-3.5 sm:p-5 text-white">
                        <span class="text-[10px] sm:text-xs uppercase tracking-widest text-gold-300 block">Couture & Ladies</span>
                        <h3 class="font-serif-luxury text-base sm:text-xl font-bold mt-0.5">Đầm Dạ Hội & Vest Nữ</h3>
                        <p class="text-[11px] sm:text-xs text-gray-300 mt-1 line-clamp-2">Tôn dáng thanh lịch với lụa tơ tằm, satin và vải tuyết mưa tuyển chọn.</p>
                        <span class="inline-flex items-center gap-1.5 text-xs text-gold-300 font-medium mt-2 group-hover:translate-x-1 transition">
                            Xem mẫu <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </div>

                <!-- Thẻ danh mục 3 -->
                <div onclick="filterAndScroll('aodai')" class="card-zoom group cursor-pointer relative rounded-2xl overflow-hidden shadow-md border border-gold-200/80 bg-charcoal-900 aspect-[3/4]">
                    <img src="https://images.unsplash.com/photo-1583391733956-3750e0ff4e8b?auto=format&fit=crop&w=800&q=80" alt="Áo Dài Hội An" class="zoom-img w-full h-full object-cover opacity-85" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Ao+Dai+Viet+Nam'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950 via-charcoal-950/30 to-transparent"></div>
                    <div class="absolute bottom-0 inset-x-0 p-3.5 sm:p-5 text-white">
                        <span class="text-[10px] sm:text-xs uppercase tracking-widest text-gold-300 block">Vietnamese Heritage</span>
                        <h3 class="font-serif-luxury text-base sm:text-xl font-bold mt-0.5">Áo Dài Lụa Tơ Tằm</h3>
                        <p class="text-[11px] sm:text-xs text-gray-300 mt-1 line-clamp-2">Áo dài cưới, áo dài truyền thống và cách tân may đo chuẩn từng đường kim.</p>
                        <span class="inline-flex items-center gap-1.5 text-xs text-gold-300 font-medium mt-2 group-hover:translate-x-1 transition">
                            Xem mẫu <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </div>

                <!-- Thẻ danh mục 4 -->
                <div onclick="filterAndScroll('coat')" class="card-zoom group cursor-pointer relative rounded-2xl overflow-hidden shadow-md border border-gold-200/80 bg-charcoal-900 aspect-[3/4]">
                    <img src="https://images.unsplash.com/photo-1544441893-675973e31985?auto=format&fit=crop&w=800&q=80" alt="Sơ Mi & Măng Tô Cashmere" class="zoom-img w-full h-full object-cover opacity-85" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Cashmere+Overcoat'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950 via-charcoal-950/30 to-transparent"></div>
                    <div class="absolute bottom-0 inset-x-0 p-3.5 sm:p-5 text-white">
                        <span class="text-[10px] sm:text-xs uppercase tracking-widest text-gold-300 block">Tailored Essentials</span>
                        <h3 class="font-serif-luxury text-base sm:text-xl font-bold mt-0.5">Măng Tô & Sơ Mi</h3>
                        <p class="text-[11px] sm:text-xs text-gray-300 mt-1 line-clamp-2">Áo khoác dạ Cashmere, Trench Coat và sơ mi Cotton Ai Cập thoáng mát.</p>
                        <span class="inline-flex items-center gap-1.5 text-xs text-gold-300 font-medium mt-2 group-hover:translate-x-1 transition">
                            Xem mẫu <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- KHU VỰC 3 ẢNH THỰC TẾ TỪ GOOGLE DRIVE -->
    <section id="anh-thuc-te" class="py-14 sm:py-20 bg-white stitch-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 gap-4">
                <div>
                    <div class="inline-flex items-center gap-2 text-gold-700 text-xs sm:text-sm font-semibold uppercase tracking-widest">
                        <i class="fa-brands fa-google-drive text-gold-600"></i>
                        <span>Thư Viện Hình Ảnh Thực Tế</span>
                    </div>
                    <h2 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-charcoal-900 mt-1">
                        3 Hình Ảnh Nổi Bật Tại Sim Tailor
                    </h2>
                    <p class="text-xs sm:text-sm text-gray-600 mt-1.5">
                        Bộ 3 hình ảnh thực tế từ thư mục Google Drive của cửa hàng Sim Tailor Hội An.
                    </p>
                </div>

                <!-- Nút mở thư mục Google Drive & Nút Dán/Đổi 3 Ảnh từ Drive -->
                <div class="flex flex-wrap items-center gap-2.5">
                    <button onclick="openDriveModal()" class="inline-flex items-center gap-2 bg-gold-500 hover:bg-gold-600 text-white text-xs sm:text-sm font-medium px-4 py-2.5 rounded-full shadow-sm transition">
                        <i class="fa-solid fa-cloud-arrow-up"></i>
                        <span>Gắn Link / Đổi 3 Ảnh Drive</span>
                    </button>
                    <a href="https://drive.google.com/drive/u/0/folders/1d2uH9OV0NutWcHhJxGDi_81ee0q8hmTt" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-charcoal-900 hover:bg-charcoal-800 text-gold-200 text-xs sm:text-sm font-medium px-4 py-2.5 rounded-full shadow-sm transition">
                        <i class="fa-brands fa-google-drive text-gold-400"></i>
                        <span>Mở Thư Mục Drive Gốc</span>
                        <i class="fa-solid fa-arrow-up-right-from-square text-[11px]"></i>
                    </a>
                </div>
            </div>

            <!-- Khung 3 Ảnh Chia Đều 3 Cột Trên Máy Tính -->
            <div class="drive-three-cols">
                <!-- Ảnh Drive 1 -->
                <div class="card-zoom group bg-ivory rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col">
                    <div class="relative aspect-[4/5] overflow-hidden bg-charcoal-900">
                        <img id="drive-img-0" src="https://images.unsplash.com/photo-1598808503746-f34c53b9323e?auto=format&fit=crop&w=1000&q=85" alt="Hình ảnh thực tế Sim Tailor 01" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/800x1000/1f1e1c/c28a3b?text=Anh+Sim+Tailor+01'">
                        <div class="absolute top-3 left-3 bg-charcoal-950/80 backdrop-blur-sm text-gold-300 text-xs font-medium px-3 py-1 rounded-full border border-gold-400/30">
                            <i class="fa-brands fa-google-drive mr-1"></i>Ảnh Thực Tế #01
                        </div>
                        <button onclick="openLightbox(0)" class="absolute bottom-3 right-3 w-9 h-9 rounded-full bg-white/90 hover:bg-gold-500 text-charcoal-900 hover:text-white flex items-center justify-center shadow transition" title="Phóng to ảnh">
                            <i class="fa-solid fa-expand text-xs"></i>
                        </button>
                    </div>
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] uppercase tracking-widest text-gold-700 font-semibold">Sim Tailor Showcase</span>
                            <h3 id="drive-title-0" class="font-serif-luxury text-lg font-bold text-charcoal-900 mt-0.5">Không Gian & Tác Phẩm May Đo #1</h3>
                            <p class="text-xs text-gray-600 mt-1">Thiết kế cắt may thủ công chuẩn form dáng, đường kim mũi chỉ sắc nét tại 23A Lê Lợi, Hội An.</p>
                        </div>
                        <div class="mt-4 pt-3 border-t border-gold-200/60 flex items-center justify-between text-xs">
                            <a href="https://drive.google.com/drive/u/0/folders/1d2uH9OV0NutWcHhJxGDi_81ee0q8hmTt" target="_blank" rel="noopener noreferrer" class="text-gold-700 hover:text-gold-900 font-medium inline-flex items-center gap-1">
                                <i class="fa-brands fa-google-drive"></i> Xem trong Drive
                            </a>
                            <label class="cursor-pointer text-charcoal-800 hover:text-gold-600 font-medium inline-flex items-center gap-1">
                                <i class="fa-solid fa-camera"></i> Chọn tệp ảnh
                                <input type="file" accept="image/*" class="hidden" onchange="uploadLocalDriveImg(event, 0)">
                            </label>
                        </div>
                    </div>
                </div>

                <!-- Ảnh Drive 2 -->
                <div class="card-zoom group bg-ivory rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col">
                    <div class="relative aspect-[4/5] overflow-hidden bg-charcoal-900">
                        <img id="drive-img-1" src="https://images.unsplash.com/photo-1617137984095-74e4e5e3613f?auto=format&fit=crop&w=1000&q=85" alt="Hình ảnh thực tế Sim Tailor 02" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/800x1000/1f1e1c/c28a3b?text=Anh+Sim+Tailor+02'">
                        <div class="absolute top-3 left-3 bg-charcoal-950/80 backdrop-blur-sm text-gold-300 text-xs font-medium px-3 py-1 rounded-full border border-gold-400/30">
                            <i class="fa-brands fa-google-drive mr-1"></i>Ảnh Thực Tế #02
                        </div>
                        <button onclick="openLightbox(1)" class="absolute bottom-3 right-3 w-9 h-9 rounded-full bg-white/90 hover:bg-gold-500 text-charcoal-900 hover:text-white flex items-center justify-center shadow transition" title="Phóng to ảnh">
                            <i class="fa-solid fa-expand text-xs"></i>
                        </button>
                    </div>
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] uppercase tracking-widest text-gold-700 font-semibold">Bespoke Fitting</span>
                            <h3 id="drive-title-1" class="font-serif-luxury text-lg font-bold text-charcoal-900 mt-0.5">Fitting & Thử Đồ Trực Tiếp #2</h3>
                            <p class="text-xs text-gray-600 mt-1">Khách hàng thử form trực tiếp cùng thợ cả, tinh chỉnh từng chi tiết vai, eo và độ rủ tự nhiên của vải.</p>
                        </div>
                        <div class="mt-4 pt-3 border-t border-gold-200/60 flex items-center justify-between text-xs">
                            <a href="https://drive.google.com/drive/u/0/folders/1d2uH9OV0NutWcHhJxGDi_81ee0q8hmTt" target="_blank" rel="noopener noreferrer" class="text-gold-700 hover:text-gold-900 font-medium inline-flex items-center gap-1">
                                <i class="fa-brands fa-google-drive"></i> Xem trong Drive
                            </a>
                            <label class="cursor-pointer text-charcoal-800 hover:text-gold-600 font-medium inline-flex items-center gap-1">
                                <i class="fa-solid fa-camera"></i> Chọn tệp ảnh
                                <input type="file" accept="image/*" class="hidden" onchange="uploadLocalDriveImg(event, 1)">
                            </label>
                        </div>
                    </div>
                </div>

                <!-- Ảnh Drive 3 -->
                <div class="card-zoom group bg-ivory rounded-2xl overflow-hidden border border-gold-200 shadow-md flex flex-col">
                    <div class="relative aspect-[4/5] overflow-hidden bg-charcoal-900">
                        <img id="drive-img-2" src="https://images.unsplash.com/photo-1555069519-127aadedf1ee?auto=format&fit=crop&w=1000&q=85" alt="Hình ảnh thực tế Sim Tailor 03" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/800x1000/1f1e1c/c28a3b?text=Anh+Sim+Tailor+03'">
                        <div class="absolute top-3 left-3 bg-charcoal-950/80 backdrop-blur-sm text-gold-300 text-xs font-medium px-3 py-1 rounded-full border border-gold-400/30">
                            <i class="fa-brands fa-google-drive mr-1"></i>Ảnh Thực Tế #03
                        </div>
                        <button onclick="openLightbox(2)" class="absolute bottom-3 right-3 w-9 h-9 rounded-full bg-white/90 hover:bg-gold-500 text-charcoal-900 hover:text-white flex items-center justify-center shadow transition" title="Phóng to ảnh">
                            <i class="fa-solid fa-expand text-xs"></i>
                        </button>
                    </div>
                    <div class="p-4 sm:p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] uppercase tracking-widest text-gold-700 font-semibold">Premium Fabrics</span>
                            <h3 id="drive-title-2" class="font-serif-luxury text-lg font-bold text-charcoal-900 mt-0.5">Chất Liệu Vải Tuyển Chọn #3</h3>
                            <p class="text-xs text-gray-600 mt-1">Hơn 500+ mẫu vải Wool, Cashmere, Linen và Lụa cao cấp sẵn sàng phục vụ quý khách tại cửa hàng.</p>
                        </div>
                        <div class="mt-4 pt-3 border-t border-gold-200/60 flex items-center justify-between text-xs">
                            <a href="https://drive.google.com/drive/u/0/folders/1d2uH9OV0NutWcHhJxGDi_81ee0q8hmTt" target="_blank" rel="noopener noreferrer" class="text-gold-700 hover:text-gold-900 font-medium inline-flex items-center gap-1">
                                <i class="fa-brands fa-google-drive"></i> Xem trong Drive
                            </a>
                            <label class="cursor-pointer text-charcoal-800 hover:text-gold-600 font-medium inline-flex items-center gap-1">
                                <i class="fa-solid fa-camera"></i> Chọn tệp ảnh
                                <input type="file" accept="image/*" class="hidden" onchange="uploadLocalDriveImg(event, 2)">
                            </label>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- VIDEO THỰC TẾ SIM TAILOR (YouTube: DjvaeP7muno) -->
    <section id="video-xuong-may" class="py-14 sm:py-20 bg-charcoal-900 text-white stitch-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-12 items-center">
                <!-- Cột Thông Tin Video (5 cột) -->
                <div class="lg:col-span-5">
                    <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-gold-500/20 border border-gold-400/40 text-gold-300 text-xs uppercase tracking-widest mb-4">
                        <i class="fa-brands fa-youtube text-red-500"></i>
                        <span>Video Thực Tế Tại Cửa Hàng</span>
                    </div>
                    <h2 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-white leading-snug">
                        Trải Nghiệm Nghệ Thuật May Đo Tại <span class="text-gold-400">Sim Tailor</span>
                    </h2>
                    <p class="text-gray-300 text-xs sm:text-sm leading-relaxed mt-4">
                        Khám phá không gian tiệm may, bảng màu vải phong phú và quy trình đo cắt thủ công trực tiếp tại <strong>Sim Tailor Hội An</strong> qua thước phim thực tế.
                    </p>

                    <div class="mt-6 space-y-3 text-xs sm:text-sm text-gray-200">
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-check text-xs"></i>
                            </div>
                            <span>Tư vấn form dáng và chất liệu vải phù hợp với từng sự kiện.</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-check text-xs"></i>
                            </div>
                            <span>Lấy số đo chi tiết hơn 25 điểm trên cơ thể đảm bảo độ vừa vặn tuyệt đối.</span>
                        </div>
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0 mt-0.5">
                                <i class="fa-solid fa-check text-xs"></i>
                            </div>
                            <span>Hỗ trợ giao hàng tận khách sạn tại Hội An, Đà Nẵng và ship toàn quốc / quốc tế.</span>
                        </div>
                    </div>

                    <!-- Tuỳ chọn khung hình Video & Mở trực tiếp trên YouTube -->
                    <div class="mt-7 flex flex-wrap items-center gap-3">
                        <a href="https://www.youtube.com/watch?v=DjvaeP7muno" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-medium px-5 py-3 rounded-full shadow-lg transition">
                            <i class="fa-brands fa-youtube text-base"></i>
                            <span>Xem Trực Tiếp Trên YouTube</span>
                        </a>
                        <button onclick="toggleVideoAspect()" id="aspect-toggle-btn" class="inline-flex items-center gap-2 bg-white/10 hover:bg-white/20 text-gold-200 border border-gold-400/30 text-xs sm:text-sm font-medium px-4 py-3 rounded-full transition">
                            <i class="fa-solid fa-mobile-screen-button"></i>
                            <span>Đổi Khung Dọc / Ngang</span>
                        </button>
                    </div>
                </div>

                <!-- Cột Trình Phát Video YouTube Nhúng (7 cột) -->
                <div class="lg:col-span-7 flex justify-center">
                    <div id="video-wrapper" class="w-full max-w-3xl rounded-2xl overflow-hidden border-2 border-gold-500/50 shadow-2xl bg-charcoal-950 relative aspect-video transition-all duration-300">
                        <iframe
                            id="yt-iframe"
                            class="w-full h-full"
                            src="https://www.youtube.com/embed/DjvaeP7muno?rel=0&modestbranding=1&playsinline=1"
                            title="Sim Tailor Video Thực Tế"
                            frameborder="0"
                            referrerpolicy="strict-origin-when-cross-origin"
                            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BỘ SƯU TẬP SẢN PHẨM (2 cột trên điện thoại, 4 cột đều nhau trên máy tính) -->
    <section id="san-pham" class="py-14 sm:py-20 bg-ivory stitch-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col sm:flex-row sm:items-end justify-between mb-8 gap-4">
                <div>
                    <span class="font-cormorant text-sm sm:text-base uppercase tracking-[0.25em] text-gold-700 font-semibold block">Bespoke Collection</span>
                    <h2 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-charcoal-900 mt-1">Thiết Kế May Đo Tiêu Biểu</h2>
                </div>
                <div class="text-xs sm:text-sm text-gray-600">
                    Đang hiển thị: <strong id="active-filter-label" class="text-gold-700">Tất Cả Danh Mục (8 mẫu)</strong>
                </div>
            </div>

            <!-- Lưới sản phẩm dùng class .mobile-two-cols -->
            <div id="product-grid" class="mobile-two-cols">
                <!-- Sản phẩm sẽ được render bằng JS bên dưới -->
            </div>
        </div>
    </section>

    <!-- LOOKBOOK KHÁCH HÀNG (2 cột trên điện thoại, 4 cột trên máy tính) -->
    <section id="lookbook" class="py-14 sm:py-20 bg-white stitch-border">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-10">
                <span class="font-cormorant text-sm sm:text-base uppercase tracking-[0.25em] text-gold-700 font-semibold block">Client Lookbook</span>
                <h2 class="font-serif-luxury text-2xl sm:text-4xl font-bold text-charcoal-900 mt-1">Khoảnh Khắc Khách Hàng Tại Sim Tailor</h2>
                <div class="w-20 h-0.5 bg-gold-500 mx-auto mt-3"></div>
            </div>

            <div class="mobile-two-cols">
                <div class="card-zoom relative rounded-2xl overflow-hidden shadow-md border border-gold-200 aspect-[3/4] bg-charcoal-900">
                    <img src="https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80" alt="Lookbook 1" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Lookbook+01'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950/80 via-transparent to-transparent flex items-end p-3.5 sm:p-5">
                        <div class="text-white">
                            <span class="text-[10px] uppercase tracking-widest text-gold-300">Wedding Suit</span>
                            <h4 class="font-serif-luxury text-sm sm:text-base font-semibold">Suit Cưới Navy 3 Mảnh</h4>
                        </div>
                    </div>
                </div>

                <div class="card-zoom relative rounded-2xl overflow-hidden shadow-md border border-gold-200 aspect-[3/4] bg-charcoal-900">
                    <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?auto=format&fit=crop&w=800&q=80" alt="Lookbook 2" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Lookbook+02'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950/80 via-transparent to-transparent flex items-end p-3.5 sm:p-5">
                        <div class="text-white">
                            <span class="text-[10px] uppercase tracking-widest text-gold-300">Business Bespoke</span>
                            <h4 class="font-serif-luxury text-sm sm:text-base font-semibold">Blazer Xám Charcoal Ý</h4>
                        </div>
                    </div>
                </div>

                <div class="card-zoom relative rounded-2xl overflow-hidden shadow-md border border-gold-200 aspect-[3/4] bg-charcoal-900">
                    <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80" alt="Lookbook 3" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Lookbook+03'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950/80 via-transparent to-transparent flex items-end p-3.5 sm:p-5">
                        <div class="text-white">
                            <span class="text-[10px] uppercase tracking-widest text-gold-300">Silk Couture</span>
                            <h4 class="font-serif-luxury text-sm sm:text-base font-semibold">Đầm Lụa Tơ Tằm Hội An</h4>
                        </div>
                    </div>
                </div>

                <div class="card-zoom relative rounded-2xl overflow-hidden shadow-md border border-gold-200 aspect-[3/4] bg-charcoal-900">
                    <img src="https://images.unsplash.com/photo-1617127365659-c47fa864d8bc?auto=format&fit=crop&w=800&q=80" alt="Lookbook 4" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Lookbook+04'">
                    <div class="absolute inset-0 bg-gradient-to-t from-charcoal-950/80 via-transparent to-transparent flex items-end p-3.5 sm:p-5">
                        <div class="text-white">
                            <span class="text-[10px] uppercase tracking-widest text-gold-300">Summer Linen</span>
                            <h4 class="font-serif-luxury text-sm sm:text-base font-semibold">Suit Linen Kem Tự Nhiên</h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ĐẶT LỊCH HẸN MAY ĐO & LIÊN HỆ -->
    <section id="dat-lich" class="py-14 sm:py-20 bg-ivory">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-charcoal-900 text-white rounded-3xl overflow-hidden shadow-2xl border border-gold-500/30 grid grid-cols-1 lg:grid-cols-12">
                <!-- Thông tin tiệm -->
                <div class="lg:col-span-5 p-6 sm:p-10 bg-charcoal-950 flex flex-col justify-between">
                    <div>
                        <span class="text-xs uppercase tracking-[0.25em] text-gold-400 font-semibold">Book An Appointment</span>
                        <h3 class="font-serif-luxury text-2xl sm:text-3xl font-bold mt-2">Đặt Lịch Đo & Tư Vấn Trực Tiếp</h3>
                        <p class="text-xs sm:text-sm text-gray-300 mt-3 leading-relaxed">
                            Đặt lịch trước để thợ cả tại <strong>Sim Tailor</strong> chuẩn bị sẵn bảng mẫu vải và phục vụ quý khách chu đáo nhất mà không phải chờ đợi.
                        </p>

                        <div class="mt-8 space-y-4 text-xs sm:text-sm">
                            <div class="flex items-start gap-3.5">
                                <div class="w-9 h-9 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-location-dot"></i>
                                </div>
                                <div>
                                    <div class="text-gold-300 font-semibold">Địa chỉ cửa hàng</div>
                                    <div class="text-gray-300 mt-0.5">23A Lê Lợi, Phường Minh An, Phố Cổ Hội An</div>
                                </div>
                            </div>
                            <div class="flex items-start gap-3.5">
                                <div class="w-9 h-9 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-phone-volume"></i>
                                </div>
                                <div>
                                    <div class="text-gold-300 font-semibold">Hotline / Zalo / WhatsApp</div>
                                    <a href="tel:0906440883" class="text-gray-300 hover:text-white mt-0.5 block">+84 906 440 883</a>
                                </div>
                            </div>
                            <div class="flex items-start gap-3.5">
                                <div class="w-9 h-9 rounded-full bg-gold-500/20 text-gold-400 flex items-center justify-center shrink-0">
                                    <i class="fa-solid fa-clock"></i>
                                </div>
                                <div>
                                    <div class="text-gold-300 font-semibold">Giờ mở cửa</div>
                                    <div class="text-gray-300 mt-0.5">09:00 – 21:00 (Thứ Hai – Chủ Nhật)</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-8 pt-6 border-t border-white/10 flex items-center justify-between text-xs text-gray-400">
                        <span>Miễn phí chỉnh sửa trọn đời</span>
                        <span class="text-gold-400 font-medium">Lấy nhanh 24h</span>
                    </div>
                </div>

                <!-- Form Đặt Lịch -->
                <div class="lg:col-span-7 p-6 sm:p-10">
                    <form id="booking-form" onsubmit="submitBooking(event)" class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs text-gold-200 uppercase tracking-wider mb-1.5">Họ và Tên *</label>
                                <input type="text" id="cust-name" required placeholder="Nhập họ và tên của bạn" class="w-full rounded-xl bg-charcoal-800 border border-gold-500/30 px-4 py-3 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gold-400">
                            </div>
                            <div>
                                <label class="block text-xs text-gold-200 uppercase tracking-wider mb-1.5">Số Điện Thoại / Zalo *</label>
                                <input type="tel" id="cust-phone" required placeholder="Ví dụ: 0906 440 883" class="w-full rounded-xl bg-charcoal-800 border border-gold-500/30 px-4 py-3 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gold-400">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs text-gold-200 uppercase tracking-wider mb-1.5">Danh Mục Quan Tâm</label>
                                <select id="cust-service" class="w-full rounded-xl bg-charcoal-800 border border-gold-500/30 px-4 py-3 text-sm text-white focus:outline-none focus:border-gold-400">
                                    <option value="Vest & Suit Nam Bespoke">Vest & Suit Nam Bespoke</option>
                                    <option value="Đầm Dạ Hội / Váy Thiết Kế">Đầm Dạ Hội / Váy Thiết Kế</option>
                                    <option value="Áo Dài Lụa Tơ Tằm">Áo Dài Lụa Tơ Tằm</option>
                                    <option value="Sơ Mi & Quần Âu">Sơ Mi & Quần Âu</option>
                                    <option value="Áo Khoác Măng Tô Cashmere">Áo Khoác Măng Tô Cashmere</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs text-gold-200 uppercase tracking-wider mb-1.5">Ngày Hẹn Dự Kiến</label>
                                <input type="date" id="cust-date" class="w-full rounded-xl bg-charcoal-800 border border-gold-500/30 px-4 py-3 text-sm text-white focus:outline-none focus:border-gold-400">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs text-gold-200 uppercase tracking-wider mb-1.5">Ghi Chú Thêm (Số đo, màu sắc, thời gian nhận đồ...)</label>
                            <textarea id="cust-note" rows="3" placeholder="Ví dụ: Mình muốn may 1 bộ Suit cưới màu Navy lấy trong 24h..." class="w-full rounded-xl bg-charcoal-800 border border-gold-500/30 px-4 py-3 text-sm text-white placeholder-gray-400 focus:outline-none focus:border-gold-400"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-gold-500 hover:bg-gold-600 text-white font-semibold py-3.5 px-6 rounded-xl shadow-lg transition flex items-center justify-center gap-2">
                            <i class="fa-regular fa-paper-plane"></i>
                            <span>Xác Nhận Đặt Lịch Hẹn Tại Sim Tailor</span>
                        </button>
                    </form>

                    <!-- Hộp thông báo xác nhận -->
                    <div id="booking-toast" class="hidden mt-4 p-4 rounded-xl bg-emerald-900/60 border border-emerald-400/50 text-emerald-100 text-xs sm:text-sm"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="bg-charcoal-950 text-gray-400 py-12 border-t border-gold-800/30 text-xs sm:text-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 pb-8 border-b border-white/10">
                <div>
                    <div class="font-serif-luxury text-xl font-bold text-white tracking-wider">SIM TAILOR HỘI AN</div>
                    <p class="mt-2 text-gray-400 leading-relaxed">
                        Nhà may đo thủ công cao cấp với hơn 15 năm kinh nghiệm tại Phố cổ Hội An. Chuyên Suit cưới, Tuxedo, Áo dài, Đầm dạ hội và Măng tô lấy nhanh trong 24h.
                    </p>
                </div>
                <div>
                    <div class="text-gold-300 font-semibold uppercase tracking-wider mb-3">Liên Kết Nhanh</div>
                    <div class="grid grid-cols-2 gap-2">
                        <a href="#danh-muc" class="hover:text-gold-300 transition">Danh Mục May Đo</a>
                        <a href="#san-pham" class="hover:text-gold-300 transition">Bộ Sưu Tập</a>
                        <a href="#anh-thuc-te" class="hover:text-gold-300 transition">3 Ảnh Thực Tế Drive</a>
                        <a href="#video-xuong-may" class="hover:text-gold-300 transition">Video YouTube</a>
                        <a href="#lookbook" class="hover:text-gold-300 transition">Lookbook</a>
                        <a href="#dat-lich" class="hover:text-gold-300 transition">Đặt Lịch Hẹn</a>
                    </div>
                </div>
                <div>
                    <div class="text-gold-300 font-semibold uppercase tracking-wider mb-3">Thông Tin Liên Hệ</div>
                    <p><i class="fa-solid fa-location-dot text-gold-400 mr-2"></i>23A Lê Lợi, Phố Cổ Hội An, Việt Nam</p>
                    <p class="mt-1.5"><i class="fa-solid fa-phone text-gold-400 mr-2"></i>0906 440 883</p>
                    <p class="mt-1.5">
                        <i class="fa-brands fa-youtube text-red-500 mr-2"></i>
                        <a href="https://www.youtube.com/watch?v=DjvaeP7muno" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">Kênh YouTube Sim Tailor</a>
                    </p>
                </div>
            </div>
            <div class="pt-6 text-center text-xs text-gray-500">
                © 2026 SIM TAILOR HỘI AN. Bảo lưu mọi quyền.
            </div>
        </div>
    </footer>

    <!-- NÚT NỔI GỌI NHANH (.pulse-gold) -->
    <div class="fixed bottom-5 right-5 z-40 flex flex-col gap-3">
        <a href="tel:0906440883" class="pulse-gold w-12 h-12 sm:w-14 sm:h-14 rounded-full bg-gold-500 hover:bg-gold-600 text-white flex items-center justify-center shadow-xl transition" title="Gọi ngay 0906 440 883">
            <i class="fa-solid fa-phone-volume text-lg sm:text-xl"></i>
        </a>
    </div>

    <!-- MODAL CẬP NHẬT LINK 3 ẢNH GOOGLE DRIVE -->
    <div id="drive-modal" class="fixed inset-0 z-50 hidden bg-black/75 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-lg w-full p-6 shadow-2xl border border-gold-300">
            <div class="flex items-center justify-between pb-3 border-b border-gray-200">
                <div class="flex items-center gap-2">
                    <i class="fa-brands fa-google-drive text-gold-600 text-xl"></i>
                    <h3 class="font-serif-luxury text-lg sm:text-xl font-bold text-charcoal-900">Gắn Link 3 Ảnh Từ Google Drive</h3>
                </div>
                <button onclick="closeDriveModal()" class="w-8 h-8 rounded-full hover:bg-gray-100 flex items-center justify-center text-gray-500">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <p class="text-xs text-gray-600 mt-3 leading-relaxed">
                Mở <a href="https://drive.google.com/drive/u/0/folders/1d2uH9OV0NutWcHhJxGDi_81ee0q8hmTt" target="_blank" rel="noopener noreferrer" class="text-gold-700 font-semibold underline">Thư mục Google Drive của bạn</a>, bấm chuột phải vào từng ảnh chọn <strong>"Sao chép đường liên kết" (Copy link)</strong> rồi dán vào 3 ô bên dưới. Hệ thống sẽ tự động chuyển đổi sang link hiển thị trực tiếp:
            </p>
            <div class="mt-4 space-y-3">
                <div>
                    <label class="block text-xs font-semibold text-charcoal-800 mb-1">Link Ảnh Google Drive #1</label>
                    <input type="text" id="drive-input-0" placeholder="Dán link ảnh 1 (VD: https://drive.google.com/file/d/.../view)" class="w-full rounded-xl border border-gray-300 px-3.5 py-2.5 text-xs focus:outline-none focus:border-gold-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-charcoal-800 mb-1">Link Ảnh Google Drive #2</label>
                    <input type="text" id="drive-input-1" placeholder="Dán link ảnh 2 (VD: https://drive.google.com/file/d/.../view)" class="w-full rounded-xl border border-gray-300 px-3.5 py-2.5 text-xs focus:outline-none focus:border-gold-500">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-charcoal-800 mb-1">Link Ảnh Google Drive #3</label>
                    <input type="text" id="drive-input-2" placeholder="Dán link ảnh 3 (VD: https://drive.google.com/file/d/.../view)" class="w-full rounded-xl border border-gray-300 px-3.5 py-2.5 text-xs focus:outline-none focus:border-gold-500">
                </div>
            </div>
            <div class="mt-6 flex items-center justify-end gap-2.5">
                <button onclick="closeDriveModal()" class="px-4 py-2.5 rounded-xl border border-gray-300 text-xs font-medium text-gray-700 hover:bg-gray-100">
                    Đóng
                </button>
                <button onclick="applyDriveLinks()" class="px-5 py-2.5 rounded-xl bg-gold-500 hover:bg-gold-600 text-xs font-semibold text-white shadow">
                    Lưu & Hiển Thị 3 Ảnh
                </button>
            </div>
        </div>
    </div>

    <!-- LIGHTBOX XEM ẢNH PHÓNG TO -->
    <div id="lightbox-modal" onclick="closeLightbox()" class="fixed inset-0 z-50 hidden bg-black/90 backdrop-blur-sm flex items-center justify-center p-4">
        <button onclick="closeLightbox()" class="absolute top-5 right-5 w-10 h-10 rounded-full bg-white/15 text-white flex items-center justify-center hover:bg-gold-500 transition">
            <i class="fa-solid fa-xmark text-lg"></i>
        </button>
        <img id="lightbox-img" src="" alt="Phóng to" class="max-h-[88vh] max-w-[92vw] rounded-2xl shadow-2xl border border-gold-400/40 object-contain">
    </div>

    <!-- JAVASCRIPT XỬ LÝ TƯƠNG TÁC -->
    <script>
        // Danh sách 8 sản phẩm tiêu biểu tại Sim Tailor
        const products = [
            {
                id: 1,
                name: 'Suit Cưới Bespoke Navy Ý',
                category: 'suit',
                categoryLabel: 'Vest & Suit Nam',
                price: 'Từ 3.800.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1594938298603-c8148c4dae35?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 2,
                name: 'Tuxedo Đen Dự Tiệc Sang Trọng',
                category: 'suit',
                categoryLabel: 'Vest & Suit Nam',
                price: 'Từ 4.200.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1507679799987-c73779587ccf?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 3,
                name: 'Đầm Dạ Hội Lụa Satin Cao Cấp',
                category: 'dress',
                categoryLabel: 'Đầm & Váy Thiết Kế',
                price: 'Từ 1.950.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1566174053879-31528523f8ae?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 4,
                name: 'Vest Nữ Thanh Lịch Công Sở',
                category: 'dress',
                categoryLabel: 'Đầm & Váy Thiết Kế',
                price: 'Từ 2.600.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 5,
                name: 'Áo Dài Lụa Tơ Tằm Hội An',
                category: 'aodai',
                categoryLabel: 'Áo Dài Truyền Thống',
                price: 'Từ 1.800.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1583391733956-3750e0ff4e8b?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 6,
                name: 'Áo Dài Cưới Thêu Tay Tinh Xảo',
                category: 'aodai',
                categoryLabel: 'Áo Dài Truyền Thống',
                price: 'Từ 2.900.000đ',
                time: 'Hoàn thiện 24h–48h',
                img: 'https://images.unsplash.com/photo-1534528741775-53994a69daeb?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 7,
                name: 'Sơ Mi Cotton Ai Cập May Đo',
                category: 'shirt',
                categoryLabel: 'Sơ Mi & Quần Âu',
                price: 'Từ 650.000đ',
                time: 'Hoàn thiện 12h–24h',
                img: 'https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf?auto=format&fit=crop&w=800&q=80'
            },
            {
                id: 8,
                name: 'Áo Khoác Măng Tô Dạ Cashmere',
                category: 'coat',
                categoryLabel: 'Áo Khoác & Măng Tô',
                price: 'Từ 3.500.000đ',
                time: 'Hoàn thiện 24h',
                img: 'https://images.unsplash.com/photo-1544441893-675973e31985?auto=format&fit=crop&w=800&q=80'
            }
        ];

        // Render danh sách sản phẩm
        function renderProducts(category = 'all') {
            const grid = document.getElementById('product-grid');
            const filtered = category === 'all' ? products : products.filter(p => p.category === category);

            const labelMap = {
                all: `Tất Cả Danh Mục (${filtered.length} mẫu)`,
                suit: `Vest & Suit Nam (${filtered.length} mẫu)`,
                dress: `Đầm & Váy Thiết Kế (${filtered.length} mẫu)`,
                aodai: `Áo Dài Truyền Thống (${filtered.length} mẫu)`,
                shirt: `Sơ Mi & Quần Âu (${filtered.length} mẫu)`,
                coat: `Áo Khoác & Măng Tô (${filtered.length} mẫu)`
            };
            document.getElementById('active-filter-label').textContent = labelMap[category] || labelMap.all;

            grid.innerHTML = filtered.map(item => `
                <div class="card-zoom bg-white rounded-2xl overflow-hidden border border-gold-200/80 shadow-sm hover:shadow-xl transition flex flex-col">
                    <div class="relative aspect-[3/4] overflow-hidden bg-charcoal-900">
                        <img src="${item.img}" alt="${item.name}" class="zoom-img w-full h-full object-cover" onerror="this.src='https://placehold.co/600x800/1f1e1c/c28a3b?text=Sim+Tailor'">
                        <span class="absolute top-2.5 left-2.5 bg-charcoal-950/80 backdrop-blur-sm text-gold-300 text-[10px] sm:text-xs px-2.5 py-1 rounded-full">
                            ${item.time}
                        </span>
                    </div>
                    <div class="p-3.5 sm:p-5 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10px] sm:text-xs text-gold-700 uppercase tracking-wider font-medium">${item.categoryLabel}</div>
                            <h3 class="font-serif-luxury text-sm sm:text-lg font-bold text-charcoal-900 mt-0.5 line-clamp-2">${item.name}</h3>
                        </div>
                        <div class="mt-3 pt-3 border-t border-gold-100 flex items-center justify-between gap-2">
                            <span class="text-xs sm:text-sm font-bold text-gold-700">${item.price}</span>
                            <a href="#dat-lich" onclick="selectService('${item.categoryLabel}')" class="text-[11px] sm:text-xs font-semibold bg-charcoal-900 hover:bg-gold-600 text-white px-3 py-1.5 rounded-full transition">
                                Đặt May
                            </a>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Lọc sản phẩm theo danh mục
        function filterProducts(category) {
            document.querySelectorAll('.cat-pill').forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === category) {
                    btn.className = 'cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-charcoal-900 text-white border-charcoal-900';
                } else {
                    btn.className = 'cat-pill flex items-center justify-center gap-2 py-3 px-3 rounded-xl font-medium text-xs sm:text-sm border transition shadow-sm bg-white text-charcoal-800 border-gold-200 hover:border-gold-500';
                }
            });
            renderProducts(category);
        }

        function filterAndScroll(category) {
            filterProducts(category);
            document.getElementById('san-pham').scrollIntoView({ behavior: 'smooth' });
        }

        function selectService(serviceName) {
            const select = document.getElementById('cust-service');
            if (select) {
                for (let i = 0; i < select.options.length; i++) {
                    if (select.options[i].value.includes(serviceName.split(' ')[0])) {
                        select.selectedIndex = i;
                        break;
                    }
                }
            }
        }

        // Chuyển đổi khung dọc/ngang cho Video YouTube (hỗ trợ cả YouTube Shorts và Video ngang)
        let isVerticalVideo = false;
        function toggleVideoAspect() {
            const wrapper = document.getElementById('video-wrapper');
            isVerticalVideo = !isVerticalVideo;
            if (isVerticalVideo) {
                wrapper.className = 'w-full max-w-[360px] mx-auto rounded-2xl overflow-hidden border-2 border-gold-500/50 shadow-2xl bg-charcoal-950 relative aspect-[9/16] transition-all duration-300';
            } else {
                wrapper.className = 'w-full max-w-3xl rounded-2xl overflow-hidden border-2 border-gold-500/50 shadow-2xl bg-charcoal-950 relative aspect-video transition-all duration-300';
            }
        }

        // Chuyển đổi link chia sẻ Google Drive sang link ảnh nhúng trực tiếp
        function convertDriveUrl(url) {
            if (!url) return '';
            const trimmed = url.trim();
            // Bắt ID từ dạng /file/d/FILE_ID/ hoặc id=FILE_ID
            const matchFile = trimmed.match(/\/file\/d\/([a-zA-Z0-9_-]+)/);
            const matchId = trimmed.match(/[?&]id=([a-zA-Z0-9_-]+)/);
            const fileId = (matchFile && matchFile[1]) || (matchId && matchId[1]);
            if (fileId) {
                return `https://lh3.googleusercontent.com/d/${fileId}=w1600`;
            }
            return trimmed;
        }

        function openDriveModal() {
            document.getElementById('drive-modal').classList.remove('hidden');
        }

        function closeDriveModal() {
            document.getElementById('drive-modal').classList.add('hidden');
        }

        function applyDriveLinks() {
            for (let i = 0; i < 3; i++) {
                const rawInput = document.getElementById(`drive-input-${i}`).value;
                if (rawInput && rawInput.trim() !== '') {
                    const directUrl = convertDriveUrl(rawInput);
                    const imgEl = document.getElementById(`drive-img-${i}`);
                    imgEl.src = directUrl;
                    try {
                        localStorage.setItem(`sim_tailor_drive_img_${i}`, directUrl);
                    } catch (e) {}
                }
            }
            closeDriveModal();
        }

        // Hỗ trợ chọn trực tiếp 3 ảnh từ máy tính/điện thoại
        function uploadLocalDriveImg(event, index) {
            const file = event.target.files && event.target.files[0];
            if (!file) return;
            const reader = new FileReader();
            reader.onload = function(e) {
                const dataUrl = e.target.result;
                document.getElementById(`drive-img-${index}`).src = dataUrl;
                try {
                    localStorage.setItem(`sim_tailor_drive_img_${index}`, dataUrl);
                } catch (err) {}
            };
            reader.readAsDataURL(file);
        }

        // Lightbox phóng to ảnh
        function openLightbox(index) {
            const src = document.getElementById(`drive-img-${index}`).src;
            document.getElementById('lightbox-img').src = src;
            document.getElementById('lightbox-modal').classList.remove('hidden');
        }

        function closeLightbox() {
            document.getElementById('lightbox-modal').classList.add('hidden');
        }

        // Menu điện thoại
        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            const icon = document.getElementById('mobile-menu-icon');
            menu.classList.toggle('hidden');
            icon.className = menu.classList.contains('hidden') ? 'fa-solid fa-bars text-lg' : 'fa-solid fa-xmark text-lg';
        }

        // Xử lý đặt lịch hẹn không dùng alert()
        function submitBooking(event) {
            event.preventDefault();
            const name = document.getElementById('cust-name').value;
            const phone = document.getElementById('cust-phone').value;
            const service = document.getElementById('cust-service').value;
            const toast = document.getElementById('booking-toast');
            toast.innerHTML = `<i class="fa-solid fa-circle-check text-emerald-400 mr-1.5"></i> Cảm ơn <strong>${name}</strong>! Lịch hẹn tư vấn <strong>${service}</strong> (SĐT: ${phone}) đã được ghi nhận. Sim Tailor (0906 440 883) sẽ liên hệ xác nhận ngay với bạn.`;
            toast.classList.remove('hidden');
            document.getElementById('booking-form').reset();
        }

        // Hero Slider tự động chuyển ảnh
        let currentSlide = 0;
        function nextHeroSlide() {
            const prev = document.getElementById(`hero-slide-${currentSlide}`);
            if (prev) {
                prev.classList.remove('opacity-100', 'scale-100');
                prev.classList.add('opacity-0', 'scale-105', 'pointer-events-none');
            }
            currentSlide = (currentSlide + 1) % 3;
            const next = document.getElementById(`hero-slide-${currentSlide}`);
            if (next) {
                next.classList.remove('opacity-0', 'scale-105', 'pointer-events-none');
                next.classList.add('opacity-100', 'scale-100');
            }
        }

        window.onload = function() {
            renderProducts('all');
            // Khôi phục 3 ảnh Drive nếu đã lưu trước đó
            for (let i = 0; i < 3; i++) {
                try {
                    const saved = localStorage.getItem(`sim_tailor_drive_img_${i}`);
                    if (saved) {
                        document.getElementById(`drive-img-${i}`).src = saved;
                    }
                } catch (e) {}
            }
            setInterval(nextHeroSlide, 5000);
        };
    </script>
</body>
</html>
