<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>KIẾN HƯNG HOME - Gạch Ốp Lát & Thiết Bị Vệ Sinh Trọn Gói Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG KIẾN HƯNG HOME - Nhà phân phối Gạch ốp lát, Gạch giả gỗ, Thiết bị vệ sinh, Tấm tường cacbon chính hãng tại 162 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng. Hotline: 0938.758.175">
    
    <!-- Open Graph / Thumbnail là Logo công ty khi chia sẻ link website kienhunghome.com -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://kienhunghome.com/">
    <meta property="og:title" content="KIẾN HƯNG HOME - Gạch Ốp Lát & Thiết Bị Vệ Sinh Cao Cấp Đà Nẵng">
    <meta property="og:description" content="Showroom Gạch ốp lát & Thiết bị vệ sinh trọn gói tại 162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng. Hotline: 0938.758.175">
    <meta property="og:image" content="https://placehold.co/1200x630/0f2942/d49a35?text=KIEN+HUNG+HOME+-+kienhunghome.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://placehold.co/1200x630/0f2942/d49a35?text=KIEN+HUNG+HOME+-+kienhunghome.com">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            navy: '#0f2942',      /* Màu xanh đậm chủ đạo theo Logo */
                            navyLight: '#173b5e', /* Màu xanh nhạt hover */
                            gold: '#c88a2e',      /* Màu vàng đồng kiến trúc theo Logo */
                            goldLight: '#e3a84f',
                            redSale: '#d92626'    /* Màu đỏ giảm giá chuẩn Flatsome */
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền ngang, không lệch phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn 95% chiều ngang màn hình máy tính, căn giữa tuyệt đối */
        .container-95 {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 768px) {
            .container-95 {
                width: 96%;
                max-width: 96%;
            }
        }

        /* Tiêu đề Section chuẩn UX Builder Flatsome (Line + Title Center) */
        .flatsome-section-title {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 1.25rem;
            padding-bottom: 0.5rem;
        }
        .flatsome-section-title-main {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0f2942;
            letter-spacing: 0.02em;
        }
        .flatsome-section-title-main::after {
            content: '';
            position: absolute;
            bottom: -0.6rem;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #c88a2e;
        }

        /* Huy hiệu % Giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-badge-sale {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d92626;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            width: 38px;
            height: 38px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 38, 38, 0.35);
            line-height: 1;
        }

        /* Card sản phẩm chuẩn Flatsome */
        .flatsome-product-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 6px;
            overflow: hidden;
            transition: all 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .flatsome-product-box:hover {
            box-shadow: 0 10px 20px -5px rgba(15, 41, 66, 0.12);
            border-color: #c88a2e;
            transform: translateY(-2px);
        }

        /* Danh mục không xuống dòng bên trong tên */
        .nav-cat-item {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            transition: all 0.2s ease;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 138, 46, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 138, 46, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 138, 46, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- =====================================================================
         [FLATSOME TOP BAR] - Đơn giản, chuẩn khách hàng xem (Không có thanh UX Builder)
    ====================================================================== -->
    <div class="bg-brand-navy text-white text-xs py-1.5 border-b border-brand-navyLight">
        <div class="container-95 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center space-x-4 truncate">
                <span class="inline-flex items-center">
                    <i class="fa-solid fa-building-columns text-brand-gold mr-1.5"></i>
                    <strong class="font-semibold">CÔNG TY TNHH TM & XD KIẾN HƯNG HOME</strong>
                </span>
                <span class="hidden md:inline-flex items-center text-slate-200">
                    <i class="fa-solid fa-location-dot text-brand-gold mr-1.5"></i>
                    162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center space-x-3 sm:space-x-4 text-[11px] sm:text-xs">
                <a href="#ve-chung-toi" class="hover:text-brand-goldLight transition">Hồ sơ năng lực</a>
                <span class="text-slate-500">|</span>
                <a href="#du-an" class="hover:text-brand-goldLight transition">Dự án</a>
                <span class="text-slate-500">|</span>
                <a href="#tin-tuc" class="hover:text-brand-goldLight transition">Kiến thức xây dựng</a>
                <span class="text-slate-500">|</span>
                <a href="#lien-he-map" class="hover:text-brand-goldLight transition font-semibold text-brand-goldLight">
                    <i class="fa-solid fa-globe mr-1"></i>kienhunghome.com
                </a>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         [FLATSOME HEADER] - Logo gọn nhỏ + Tìm kiếm + Menu Danh mục (Không có nút Gọi ngay tránh tràn viền)
    ====================================================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <!-- Header Main -->
        <div class="container-95 py-2.5 flex items-center justify-between gap-3">
            <!-- Nút mở Menu trên Điện thoại -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-md text-brand-navy hover:bg-slate-100 focus:outline-none">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>

            <!-- LOGO CÔNG TY THIẾT KẾ MỚI CHUYÊN NGHIỆP - GỌN NHỎ LẠI -->
            <a href="#" class="flex items-center gap-2.5 group shrink-0">
                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-brand-navy flex items-center justify-center border border-brand-gold shadow-sm shrink-0">
                    <!-- Biểu tượng SVG Kiến Hưng Home (Mái nhà kiến trúc & Viên gạch kim cương KH) -->
                    <svg class="w-6 h-6 sm:w-7 sm:h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M32 6L8 24V56H22V38H42V56H56V24L32 6Z" stroke="#c88a2e" stroke-width="4" stroke-linejoin="round"/>
                        <path d="M32 14L16 26.5V50H24V34H40V50H48V26.5L32 14Z" fill="#c88a2e" fill-opacity="0.2"/>
                        <rect x="27" y="21" width="10" height="10" transform="rotate(45 32 21)" fill="#e3a84f"/>
                    </svg>
                </div>
                <div class="flex flex-col">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-navy leading-none">
                        KIẾN HƯNG <span class="text-brand-gold">HOME</span>
                    </span>
                    <span class="text-[9px] sm:text-[10px] font-medium text-slate-500 tracking-wider uppercase mt-0.5">
                        Gạch Ốp Lát & TBVệ Sinh
                    </span>
                </div>
            </a>

            <!-- Thanh Tìm kiếm sản phẩm chuẩn Flatsome -->
            <div class="hidden md:flex flex-1 max-w-xl mx-4">
                <div class="relative w-full flex items-center">
                    <input id="searchInput" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm gạch lát nền 60x60, 80x80, gạch giả gỗ, thiết bị vệ sinh..." 
                        class="w-full pl-3.5 pr-10 py-1.5 text-xs sm:text-sm bg-slate-50 border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy focus:bg-white transition">
                    <button onclick="filterProductsBySearch(document.getElementById('searchInput').value)" class="absolute right-1 top-1 bottom-1 px-3 bg-brand-navy text-white rounded hover:bg-brand-gold transition text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Thông tin địa chỉ & Giờ mở cửa ngắn gọn (Không để nút gọi ngay trên Header để tránh tràn viền) -->
            <div class="hidden xl:flex items-center space-x-5 text-xs text-slate-600 shrink-0">
                <div class="flex items-center gap-2">
                    <div class="w-7 h-7 rounded-full bg-amber-50 border border-amber-200 flex items-center justify-center text-brand-gold">
                        <i class="fa-solid fa-location-dot text-xs"></i>
                    </div>
                    <div class="leading-tight">
                        <p class="font-bold text-brand-navy text-[11px]">Showroom Đà Nẵng</p>
                        <p class="text-[11px] text-slate-500">162 Trần Đại Nghĩa, Ngũ Hành Sơn</p>
                    </div>
                </div>
                <div class="flex items-center gap-2">
                    <div class="w-7 h-7 rounded-full bg-slate-100 border border-slate-200 flex items-center justify-center text-brand-navy">
                        <i class="fa-regular fa-clock text-xs"></i>
                    </div>
                    <div class="leading-tight">
                        <p class="font-bold text-brand-navy text-[11px]">Giờ làm việc</p>
                        <p class="text-[11px] text-slate-500">07:00 - 17:30 (T2 - CN)</p>
                    </div>
                </div>
            </div>

            <!-- Nút bật ô tìm kiếm nhanh trên Mobile -->
            <button onclick="toggleMobileSearch()" aria-label="Tìm kiếm" class="md:hidden p-2 rounded-md text-brand-navy hover:bg-slate-100">
                <i class="fa-solid fa-magnifying-glass text-lg"></i>
            </button>
        </div>

        <!-- Ô tìm kiếm phụ trên điện thoại -->
        <div id="mobileSearchBar" class="hidden md:hidden bg-slate-50 px-3 py-2 border-t border-slate-200">
            <div class="relative flex items-center">
                <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Nhập tên hoặc mã sản phẩm cần tìm..." 
                    class="w-full pl-3 pr-9 py-1.5 text-xs bg-white border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy">
                <i class="fa-solid fa-magnifying-glass absolute right-3 text-slate-400 text-xs"></i>
            </div>
        </div>

        <!-- Thanh Danh Mục Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng (whitespace-nowrap), tự xuống hàng 2 nguyên cụm nếu màn hình nhỏ, tuyệt đối không gãy chữ -->
        <nav class="hidden lg:block bg-brand-navy text-white border-t border-brand-navyLight">
            <div class="container-95">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1 gap-y-1 py-1.5 text-[12px] font-semibold">
                    <li>
                        <a href="#" onclick="filterCategory('all'); return false;" class="nav-cat-item px-2.5 py-1 rounded bg-brand-gold text-white">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Gạch lát nền')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            GẠCH LÁT NỀN
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Gạch ốp tường')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            GẠCH ỐP TƯỜNG
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Gạch giả gỗ')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            GẠCH GIẢ GỖ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Gạch lát sân vườn')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            GẠCH LÁT SÂN VƯỜN
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Thiết bị vệ sinh')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            THIẾT BỊ VỆ SINH
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Tấm tường cacbon')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            TẤM TƯỜNG CACBON
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham-chinh" onclick="filterCategory('Bếp điện từ & Tranh đá')" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            BẾP ĐIỆN TỪ & TRANH ĐÁ
                        </a>
                    </li>
                    <li>
                        <a href="#du-an" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            DỰ ÁN
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            TIN TỨC
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            BÁO GIÁ
                        </a>
                    </li>
                    <li>
                        <a href="#lien-he-map" class="nav-cat-item px-2.5 py-1 rounded hover:bg-brand-navyLight hover:text-brand-goldLight">
                            LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh mục trên Điện thoại (Drawer gọn đẹp) -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="container-95 py-3">
                <p class="text-[11px] font-bold uppercase text-slate-400 mb-2 tracking-wider">Danh mục sản phẩm</p>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-brand-navy">
                    <a href="#san-pham-chinh" onclick="filterCategory('all'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Tất cả sản phẩm</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Gạch lát nền'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Gạch lát nền</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Gạch ốp tường'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Gạch ốp tường</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Gạch giả gỗ'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Gạch giả gỗ</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Gạch lát sân vườn'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Gạch lát sân vườn</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Thiết bị vệ sinh'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Thiết bị vệ sinh</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Tấm tường cacbon'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Tấm tường cacbon</a>
                    <a href="#san-pham-chinh" onclick="filterCategory('Bếp điện từ & Tranh đá'); toggleMobileMenu();" class="px-3 py-2 rounded bg-slate-100 hover:bg-brand-gold hover:text-white transition whitespace-nowrap">Bếp từ & Tranh đá</a>
                    <a href="#bao-gia" onclick="toggleMobileMenu();" class="px-3 py-2 rounded bg-amber-50 text-brand-gold border border-amber-200 whitespace-nowrap">Yêu cầu báo giá</a>
                    <a href="#lien-he-map" onclick="toggleMobileMenu();" class="px-3 py-2 rounded bg-amber-50 text-brand-navy border border-slate-200 whitespace-nowrap">Bản đồ & Liên hệ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         [UX SLIDER - 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU]
         Thiết kế hình ảnh và chữ nằm gọn bên trong banner, cách xa viền, không bị mất chữ trên cả ĐT & Máy tính
    ====================================================================== -->
    <section class="py-3 sm:py-4">
        <div class="container-95">
            <div class="relative w-full h-[230px] sm:h-[310px] md:h-[380px] lg:h-[420px] rounded-xl overflow-hidden shadow-md bg-brand-navy">
                
                <!-- SLIDE 1: GẠCH ỐP LÁT CAO CẤP & NHẬP KHẨU -->
                <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                    <!-- Nền Kiến trúc & Ảnh sản phẩm thực tế nằm gọn bên trong -->
                    <div class="w-full h-full bg-gradient-to-r from-[#0a1e32] via-[#113152] to-[#1a3e63] flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10">
                        <!-- Khối Chữ: Cách xa viền banner (px-7 đến px-20) để không bao giờ bị cắt chữ -->
                        <div class="w-full md:w-7/12 text-white space-y-1.5 sm:space-y-3 pr-2">
                            <p class="text-[10px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-brand-goldLight">
                                CÔNG TY TNHH TM & XD KIẾN HƯNG HOME
                            </p>
                            <h1 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                                NHÀ PHÂN PHỐI GẠCH ỐP LÁT &amp; ĐÁ NHẬP KHẨU TRỌN GÓI
                            </h1>
                            <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 max-w-xl leading-relaxed">
                                Chuyên cung cấp Gạch lát nền 60x60, 80x80, 60x120, Gạch giả gỗ, Gạch sân vườn &amp; Tấm tường Cacbon chính hãng tại Đà Nẵng và Miền Trung.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs">
                                <a href="#san-pham-chinh" class="px-3.5 sm:px-5 py-1.5 sm:py-2.5 rounded-md bg-brand-gold hover:bg-brand-goldLight text-white font-bold shadow transition">
                                    Xem Mẫu Gạch Mới
                                </a>
                                <span class="text-slate-200 font-medium hidden sm:inline">
                                    <i class="fa-solid fa-location-dot text-brand-goldLight mr-1"></i>162 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng
                                </span>
                            </div>
                        </div>

                        <!-- Khối Hình ảnh thực tế nằm gọn bên trong phải Banner -->
                        <div class="hidden md:flex md:w-5/12 h-full items-center justify-end pl-4">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[360px] p-3 bg-white/10 backdrop-blur-sm rounded-xl border border-white/20">
                                <img src="https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w600" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600';"
                                     alt="Gạch ốp lát Kiến Hưng Home" class="w-full h-28 lg:h-36 object-cover rounded-lg border border-brand-gold/50">
                                <img src="https://lh3.googleusercontent.com/d/11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP=w600" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w600';"
                                     alt="Gạch vân đá cao cấp" class="w-full h-28 lg:h-36 object-cover rounded-lg border border-brand-gold/50">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2: THIẾT BỊ VỆ SINH & GIẢI PHÁP NỘI THẤT HIỆN ĐẠI (KÍCH THƯỚC BẰNG HỆT SLIDE 1) -->
                <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                    <div class="w-full h-full bg-gradient-to-r from-[#132a42] via-[#1c3d5e] to-[#0f2942] flex items-center justify-between px-7 sm:px-14 md:px-20 py-6 sm:py-10">
                        <!-- Khối Chữ: Cách xa viền banner đảm bảo không mất chữ trên Mobile & Desktop -->
                        <div class="w-full md:w-7/12 text-white space-y-1.5 sm:space-y-3 pr-2">
                            <p class="text-[10px] sm:text-xs md:text-sm font-bold uppercase tracking-widest text-brand-goldLight">
                                SHOWROOM KIẾN HƯNG HOME - KIENKUNGHOME.COM
                            </p>
                            <h2 class="text-base sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-tight text-white">
                                THIẾT BỊ VỆ SINH CAO CẤP &amp; TẤM TƯỜNG CACBON
                            </h2>
                            <p class="text-[11px] sm:text-xs md:text-sm text-slate-200 max-w-xl leading-relaxed">
                                Trọn gói Bồn cầu nguyên khối, Chậu Lavabo đá, Bồn tắm Ovan, Sen vòi cao cấp. Giao hàng tận công trình - Chiết khấu ưu đãi đến 30%.
                            </p>
                            <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2 sm:gap-3 text-[11px] sm:text-xs">
                                <a href="#bao-gia" class="px-3.5 sm:px-5 py-1.5 sm:py-2.5 rounded-md bg-brand-gold hover:bg-brand-goldLight text-white font-bold shadow transition">
                                    Nhận Báo Giá Trọn Gói
                                </a>
                                <span class="text-slate-200 font-medium">
                                    <i class="fa-solid fa-phone-volume text-brand-goldLight mr-1"></i>Hotline: 0938.758.175
                                </span>
                            </div>
                        </div>

                        <!-- Khối Hình ảnh thực tế nằm gọn bên trong phải Banner -->
                        <div class="hidden md:flex md:w-5/12 h-full items-center justify-end pl-4">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[360px] p-3 bg-white/10 backdrop-blur-sm rounded-xl border border-white/20">
                                <img src="https://lh3.googleusercontent.com/d/17YrxXteZmzhvVRYgfaklNGC2hKjN09N8=w600" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w600';"
                                     alt="Thiết bị vệ sinh Kiến Hưng Home" class="w-full h-28 lg:h-36 object-cover rounded-lg border border-brand-gold/50">
                                <img src="https://lh3.googleusercontent.com/d/1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf=w600" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf&sz=w600';"
                                     alt="Bồn tắm cao cấp" class="w-full h-28 lg:h-36 object-cover rounded-lg border border-brand-gold/50">
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Trái/Phải nằm sát mép ngoài phần chữ -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-1.5 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-1.5 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm tròn báo vị trí Banner -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center space-x-2">
                    <button id="bannerDot0" onclick="goToSlide(0)" aria-label="Banner 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                    <button id="bannerDot1" onclick="goToSlide(1)" aria-label="Banner 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [4 Ô CAM KẾT DỊCH VỤ CHUẨN FLATSOME ICON BOX]
    ====================================================================== -->
    <section class="py-2">
        <div class="container-95">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4">
                <div class="bg-white p-3 sm:p-4 rounded-lg border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-medal text-sm sm:text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy">Chính Hãng 100%</h3>
                        <p class="text-[11px] text-slate-500">Cam kết chuẩn chất lượng nhà máy</p>
                    </div>
                </div>
                <div class="bg-white p-3 sm:p-4 rounded-lg border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-truck-fast text-sm sm:text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy">Giao Hàng Tận Nơi</h3>
                        <p class="text-[11px] text-slate-500">Đúng tiến độ tại Đà Nẵng &amp; toàn quốc</p>
                    </div>
                </div>
                <div class="bg-white p-3 sm:p-4 rounded-lg border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-tags text-sm sm:text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy">Giá Kho Tốt Nhất</h3>
                        <p class="text-[11px] text-slate-500">Chiết khấu cao cho nhà thầu &amp; chủ nhà</p>
                    </div>
                </div>
                <div class="bg-white p-3 sm:p-4 rounded-lg border border-slate-200 flex items-center gap-3 shadow-sm">
                    <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-full bg-brand-navy text-brand-goldLight flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-arrows-rotate text-sm sm:text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy">Đổi Trả Linh Hoạt</h3>
                        <p class="text-[11px] text-slate-500">Hỗ trợ đổi trả gạch dư nguyên hộp</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [DANH MỤC SẢN PHẨM TRANG CHỦ] - Giống mẫu quanghungceramic.vn
         Chữ danh mục nhỏ gọn, viết liền trên 1 hàng, tối ưu đẹp mắt trên máy tính và điện thoại
    ====================================================================== -->
    <section class="py-5">
        <div class="container-95">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                    DANH MỤC SẢN PHẨM
                </h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
            </div>

            <!-- Lưới danh mục: 2 cột trên ĐT nhỏ, 4 cột trên Tablet, 8 cột trên Máy tính chữ nhỏ gọn trên 1 hàng -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <!-- Danh mục 1 -->
                <button onclick="filterCategory('Gạch lát nền')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w400';"
                             alt="Gạch lát nền" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Gạch lát nền</span>
                </button>

                <!-- Danh mục 2 -->
                <button onclick="filterCategory('Gạch ốp tường')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w400';"
                             alt="Gạch ốp tường" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Gạch ốp tường</span>
                </button>

                <!-- Danh mục 3 -->
                <button onclick="filterCategory('Gạch giả gỗ')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w400';"
                             alt="Gạch giả gỗ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Gạch giả gỗ</span>
                </button>

                <!-- Danh mục 4 -->
                <button onclick="filterCategory('Gạch lát sân vườn')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP&sz=w400';"
                             alt="Gạch lát sân vườn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Gạch lát sân vườn</span>
                </button>

                <!-- Danh mục 5 -->
                <button onclick="filterCategory('Thiết bị vệ sinh')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/17YrxXteZmzhvVRYgfaklNGC2hKjN09N8=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17YrxXteZmzhvVRYgfaklNGC2hKjN09N8&sz=w400';"
                             alt="Thiết bị vệ sinh" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Thiết bị vệ sinh</span>
                </button>

                <!-- Danh mục 6 -->
                <button onclick="filterCategory('Tấm tường cacbon')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w400';"
                             alt="Tấm tường cacbon" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Tấm tường cacbon</span>
                </button>

                <!-- Danh mục 7 -->
                <button onclick="filterCategory('Bếp điện từ & Tranh đá')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w400"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w400';"
                             alt="Tranh đá & Bếp từ" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Tranh đá &amp; Bếp từ</span>
                </button>

                <!-- Danh mục 8 -->
                <button onclick="filterCategory('all')" class="group bg-white p-2.5 rounded-lg border border-slate-200 hover:border-brand-gold shadow-sm flex flex-col items-center text-center transition">
                    <div class="w-full aspect-square rounded-md overflow-hidden mb-2 bg-brand-navy flex flex-col items-center justify-center text-brand-goldLight p-2">
                        <i class="fa-solid fa-layer-group text-2xl sm:text-3xl mb-1"></i>
                        <span class="text-[10px] text-white font-semibold">19+ Mẫu Thực Tế</span>
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-brand-navy group-hover:text-brand-gold whitespace-nowrap">Xem tất cả</span>
                </button>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [PHẦN SẢN PHẨM TRANG CHỦ - TÍCH HỢP ĐẦY ĐỦ 19 ẢNH THỰC TẾ TỪ GOOGLE DRIVE]
         - Chia đúng 2 cột trên điện thoại (grid-cols-2)
         - Tên sản phẩm đầy đủ không bị tràn hay mất chữ
         - Có giá giảm & huy hiệu % giảm giá góc trên bên trái chuẩn Flatsome
    ====================================================================== -->
    <section id="san-pham-chinh" class="py-4">
        <div class="container-95 space-y-8">

            <!-- Thanh lọc nhanh trên đầu danh sách sản phẩm -->
            <div class="bg-white p-3 rounded-lg border border-slate-200 flex flex-wrap items-center justify-between gap-2">
                <div class="flex flex-wrap items-center gap-1.5" id="categoryFilterPills">
                    <button onclick="filterCategory('all')" data-cat="all" class="cat-pill px-3 py-1 rounded text-xs font-bold bg-brand-navy text-white whitespace-nowrap transition">
                        Tất cả (19 sản phẩm thực tế)
                    </button>
                    <button onclick="filterCategory('Gạch lát nền')" data-cat="Gạch lát nền" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Gạch lát nền (60x60, 80x80, 90x180)
                    </button>
                    <button onclick="filterCategory('Gạch ốp tường')" data-cat="Gạch ốp tường" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Gạch ốp tường (30x60, 40x80)
                    </button>
                    <button onclick="filterCategory('Gạch giả gỗ')" data-cat="Gạch giả gỗ" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Gạch giả gỗ
                    </button>
                    <button onclick="filterCategory('Gạch lát sân vườn')" data-cat="Gạch lát sân vườn" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Gạch lát sân vườn
                    </button>
                    <button onclick="filterCategory('Thiết bị vệ sinh')" data-cat="Thiết bị vệ sinh" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Thiết bị vệ sinh HiMic &amp; Dova
                    </button>
                    <button onclick="filterCategory('Tấm tường cacbon')" data-cat="Tấm tường cacbon" class="cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition">
                        Tấm tường cacbon &amp; Tranh đá
                    </button>
                </div>
                <div id="filterStatusText" class="text-xs font-medium text-slate-500">
                    Hiển thị 19 sản phẩm thực tế
                </div>
            </div>

            <!-- KHU VỰC RENDER CÁC NHÓM DANH MỤC SẢN PHẨM CHUẨN QUANG HƯNG CERAMIC -->
            <div id="productSectionsContainer" class="space-y-8">
                <!-- Được render tự động từ mảng 19 sản phẩm Google Drive bên dưới -->
            </div>

        </div>
    </section>

    <!-- =====================================================================
         [DỰ ÁN TIÊU BIỂU ĐÃ CUNG CẤP] - Giống mẫu quanghungceramic.vn
    ====================================================================== -->
    <section id="du-an" class="py-6 bg-white border-y border-slate-200">
        <div class="container-95">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                    CÔNG TRÌNH &amp; DỰ ÁN TIÊU BIỂU
                </h2>
                <a href="#bao-gia" class="text-xs font-bold text-brand-navy hover:text-brand-gold whitespace-nowrap">
                    Đăng ký cấp mẫu công trình <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 group">
                    <div class="aspect-[4/3] overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600';"
                             alt="Biệt thự biển Ngũ Hành Sơn" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug">Khu Biệt Thự Ven Biển Ngũ Hành Sơn – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1">Cung cấp gạch khổ lớn 90x180 &amp; Thiết bị vệ sinh trọn gói</p>
                    </div>
                </div>

                <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 group">
                    <div class="aspect-[4/3] overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w600';"
                             alt="Khách sạn & Căn hộ Đà Nẵng" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug">Tổ Hợp Khách Sạn &amp; Căn Hộ Dịch Vụ Ven Sông Hàn</h3>
                        <p class="text-[11px] text-slate-500 mt-1">Hạng mục gạch lát nền Porcelain 80x80 &amp; Tấm tường Cacbon</p>
                    </div>
                </div>

                <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 group">
                    <div class="aspect-[4/3] overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w600';"
                             alt="Resort nghỉ dưỡng" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug">Khu Nghỉ Dưỡng Sinh Thái &amp; Villa Hội An - Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1">Hạng mục sàn đá giả gỗ chống trơn &amp; gạch sân vườn</p>
                    </div>
                </div>

                <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-50 group">
                    <div class="aspect-[4/3] overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w600';"
                             alt="Nhà phố hiện đại" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3">
                        <h3 class="text-xs sm:text-sm font-bold text-brand-navy leading-snug">Chuỗi Nhà Phố Thương Mại Nam Hòa Xuân – Đà Nẵng</h3>
                        <p class="text-[11px] text-slate-500 mt-1">Cung cấp trọn gói gạch ốp lát Á Mỹ &amp; thiết bị phòng tắm</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ]
    ====================================================================== -->
    <section id="bao-gia" class="py-7">
        <div class="container-95">
            <div class="bg-gradient-to-br from-brand-navy via-[#133252] to-brand-navy rounded-xl p-5 sm:p-8 shadow-lg border border-brand-gold/40 text-white">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    
                    <!-- Cột thông tin ưu đãi báo giá -->
                    <div class="lg:col-span-5 space-y-3">
                        <span class="inline-block px-3 py-1 rounded bg-brand-gold text-white text-xs font-bold uppercase tracking-wider">
                            Báo Giá Nhanh Trong 5 Phút
                        </span>
                        <h2 class="text-lg sm:text-2xl font-extrabold leading-snug">
                            ĐĂNG KÝ NHẬN BÁO GIÁ SỈ &amp; CATALOGUE MẪU MỚI NHẤT
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                            Quý khách hàng, Chủ đầu tư, Kiến trúc sư &amp; Nhà thầu xây dựng tại Đà Nẵng cần báo giá trọn gói Gạch ốp lát và Thiết bị vệ sinh vui lòng để lại thông tin. Kiến Hưng Home cam kết mức chiết khấu tốt nhất thị trường.
                        </p>
                        <ul class="space-y-2 text-xs sm:text-sm text-slate-100 pt-1">
                            <li class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-brand-goldLight"></i>
                                <span>Miễn phí tư vấn phối màu 3D &amp; tính toán khối lượng gạch</span>
                            </li>
                            <li class="flex items-center gap-2">
                                <i class="fa-solid fa-circle-check text-brand-goldLight"></i>
                                <span>Hỗ trợ vận chuyển tận chân công trình tại Đà Nẵng &amp; Quảng Nam</span>
                            </li>
                            <li class="flex items-center gap-2">
                                <i class="fa-solid fa-phone-volume text-brand-goldLight"></i>
                                <span>Hotline/Zalo trực tiếp: <strong class="text-brand-goldLight text-base">0938.758.175</strong></span>
                            </li>
                        </ul>
                    </div>

                    <!-- Cột Form nhập thông tin -->
                    <div class="lg:col-span-7">
                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-xl shadow-md space-y-3.5">
                            <h3 class="text-sm sm:text-base font-extrabold text-brand-navy border-b border-slate-200 pb-2">
                                FORM YÊU CẦU TƯ VẤN &amp; NHẬN BÁO GIÁ
                            </h3>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                    <input type="text" id="custName" required placeholder="Nhập họ và tên..." 
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="custPhone" required placeholder="Ví dụ: 0938758175" 
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục quan tâm</label>
                                    <select id="custCategory" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy bg-white">
                                        <option value="Trọn gói Gạch ốp lát & Thiết bị vệ sinh">Trọn gói Gạch ốp lát &amp; TBVệ Sinh</option>
                                        <option value="Gạch lát nền 60x60 / 80x80 / 60x120">Gạch lát nền (60x60, 80x80, 60x120)</option>
                                        <option value="Gạch ốp tường & Gạch trang trí">Gạch ốp tường &amp; Gạch trang trí</option>
                                        <option value="Gạch giả gỗ & Gạch sân vườn">Gạch giả gỗ &amp; Gạch sân vườn</option>
                                        <option value="Thiết bị vệ sinh phòng tắm">Thiết bị vệ sinh phòng tắm</option>
                                        <option value="Tấm tường cacbon gia cường">Tấm tường cacbon gia cường</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình</label>
                                    <input type="text" id="custAddress" placeholder="Quận/Huyện tại Đà Nẵng hoặc tỉnh thành..." 
                                           class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú nhu cầu (Mã sản phẩm, diện tích m2...)</label>
                                <textarea id="custNote" rows="2" placeholder="Nhập mã gạch bạn quan tâm hoặc diện tích cần tư vấn..." 
                                          class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded-md focus:outline-none focus:border-brand-navy"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="w-full sm:w-auto px-6 py-2.5 bg-brand-gold hover:bg-brand-goldLight text-white font-bold text-xs sm:text-sm rounded-md shadow transition flex items-center justify-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                                </button>
                                <span class="text-[11px] text-slate-500">
                                    Hoặc kết nối nhanh qua Zalo: <a href="https://zalo.me/0938758175" target="_blank" rel="noopener noreferrer" class="font-bold text-brand-navy underline">0938.758.175</a>
                                </span>
                            </div>

                            <!-- Thông báo gửi thành công -->
                            <div id="quoteSuccessMsg" class="hidden p-3 rounded-md bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium">
                                <i class="fa-solid fa-circle-check mr-1.5 text-emerald-600"></i>
                                Cảm ơn quý khách! Yêu cầu báo giá đã được ghi nhận. Bộ phận kinh doanh Kiến Hưng Home (0938.758.175) sẽ liên hệ ngay.
                            </div>
                        </form>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [DANH MỤC CÁC BÀI VIẾT TRANG CHỦ - TIN TỨC & KIẾN THỨC XÂY DỰNG]
    ====================================================================== -->
    <section id="tin-tuc" class="py-6">
        <div class="container-95">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                    TIN TỨC TIÊU ĐIỂM &amp; KIẾN THỨC XÂY DỰNG
                </h2>
                <a href="#bao-gia" class="text-xs font-bold text-brand-navy hover:text-brand-gold whitespace-nowrap">
                    Xem tất cả bài viết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1X31hmhpLVVORV-tmMSZYzBO-qtpyusry=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1X31hmhpLVVORV-tmMSZYzBO-qtpyusry&sz=w600';"
                             alt="Kinh nghiệm chọn gạch lát nền" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 bg-brand-navy text-white text-center px-2 py-1 rounded leading-tight">
                            <span class="block text-xs font-extrabold">15</span>
                            <span class="block text-[10px] text-brand-goldLight">Th11</span>
                        </div>
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-gold">Kiến thức xây dựng</span>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy mt-1 leading-snug hover:text-brand-gold transition">
                                Kinh nghiệm chọn gạch lát nền 80x80 và 60x120 chuẩn đẹp cho nhà phố hiện đại
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Gạch khổ lớn giúp không gian phòng khách trở nên sang trọng, ít đường ron vữa và dễ dàng vệ sinh lau chùi...
                            </p>
                        </div>
                        <a href="#bao-gia" class="inline-block mt-3 text-[11px] font-bold text-brand-navy hover:text-brand-gold">
                            Đọc tiếp <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh&sz=w600';"
                             alt="Tấm tường cacbon gia cường" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 bg-brand-navy text-white text-center px-2 py-1 rounded leading-tight">
                            <span class="block text-xs font-extrabold">10</span>
                            <span class="block text-[10px] text-brand-goldLight">Th11</span>
                        </div>
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-gold">Vật liệu mới</span>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy mt-1 leading-snug hover:text-brand-gold transition">
                                Tấm Tường Cacbon Gia Cường: Ưu điểm vượt trội và ứng dụng trong nội thất cao cấp
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Giải pháp ốp tường chống ẩm mốc, chống cháy lan, thi công nhanh gọn thay thế đá tự nhiên và gỗ truyền thống...
                            </p>
                        </div>
                        <a href="#bao-gia" class="inline-block mt-3 text-[11px] font-bold text-brand-navy hover:text-brand-gold">
                            Đọc tiếp <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/115IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_&sz=w600';"
                             alt="Thiết bị vệ sinh Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 bg-brand-navy text-white text-center px-2 py-1 rounded leading-tight">
                            <span class="block text-xs font-extrabold">05</span>
                            <span class="block text-[10px] text-brand-goldLight">Th11</span>
                        </div>
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-gold">Tư vấn phòng tắm</span>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy mt-1 leading-snug hover:text-brand-gold transition">
                                Bí quyết chọn trọn bộ Thiết bị vệ sinh Bồn cầu 1 khối &amp; Tủ chậu Lavabo bền đẹp
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Lựa chọn men sứ kháng khuẩn Nano chống bám bẩn cùng sen vòi đồng thau giúp phòng tắm luôn sáng bóng...
                            </p>
                        </div>
                        <a href="#bao-gia" class="inline-block mt-3 text-[11px] font-bold text-brand-navy hover:text-brand-gold">
                            Đọc tiếp <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c=w600"
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c&sz=w600';"
                             alt="Gạch giả gỗ lát phòng ngủ" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        <div class="absolute top-2.5 left-2.5 bg-brand-navy text-white text-center px-2 py-1 rounded leading-tight">
                            <span class="block text-xs font-extrabold">01</span>
                            <span class="block text-[10px] text-brand-goldLight">Th11</span>
                        </div>
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-gold">Xu hướng nội thất</span>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy mt-1 leading-snug hover:text-brand-gold transition">
                                Tại sao Gạch giả gỗ ngày càng được ưa chuộng thay thế sàn gỗ công nghiệp tại Đà Nẵng?
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Khắc phục hoàn toàn nhược điểm mối mọt, cong vênh do thời tiết nồm ẩm miền Trung mà vẫn giữ trọn vẻ ấm cúng...
                            </p>
                        </div>
                        <a href="#bao-gia" class="inline-block mt-3 text-[11px] font-bold text-brand-navy hover:text-brand-gold">
                            Đọc tiếp <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU]
    ====================================================================== -->
    <section class="py-6 bg-white border-t border-slate-200">
        <div class="container-95">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                    ĐỐI TÁC &amp; THƯƠNG HIỆU PHÂN PHỐI
                </h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Hợp tác cùng các nhà máy sản xuất hàng đầu</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">AMY GRUPO</span>
                    <span class="text-[10px] text-slate-500">Gạch Á Mỹ</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">CMC TILES</span>
                    <span class="text-[10px] text-slate-500">Gạch Ốp Lát CMC</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">HIMIC</span>
                    <span class="text-[10px] text-slate-500">Thiết Bị Vệ Sinh</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">DOVA</span>
                    <span class="text-[10px] text-slate-500">Sứ Vệ Sinh Cao Cấp</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">VIGLACERA</span>
                    <span class="text-[10px] text-slate-500">Gạch &amp; Sứ Vệ Sinh</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">PRIME</span>
                    <span class="text-[10px] text-slate-500">Tập Đoàn Prime</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">ĐỒNG TÂM</span>
                    <span class="text-[10px] text-slate-500">Gạch Đồng Tâm</span>
                </div>
                <div class="h-16 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center p-2 hover:border-brand-gold transition">
                    <span class="text-xs sm:text-sm font-black text-brand-navy tracking-wider">NHẬP KHẨU</span>
                    <span class="text-[10px] text-slate-500">Ấn Độ - Trung Quốc</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         [ĐƯA BẢN ĐỒ GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ]
         Địa chỉ: 162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng
         Link Map: https://share.google/f4VTtNo05hj6HXN5B
         SĐT: 0938.758.175
    ====================================================================== -->
    <section id="lien-he-map" class="py-7 bg-slate-100 border-t border-slate-200">
        <div class="container-95">
            <div class="flatsome-section-title">
                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                    SHOWROOM, BẢN ĐỒ GOOGLE MAPS &amp; FANPAGE CHÍNH THỨC
                </h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- Cột 1: Thông tin liên hệ trực tiếp + Bản đồ Google Map ngoài trang chủ (7 cột) -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between space-y-3">
                    <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-3">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-brand-navy">
                                SHOWROOM KIẾN HƯNG HOME ĐÀ NẴNG
                            </h3>
                            <p class="text-xs text-slate-600 mt-0.5">
                                <i class="fa-solid fa-location-dot text-brand-gold mr-1"></i>
                                <strong>Địa chỉ:</strong> 162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng
                            </p>
                            <p class="text-xs text-slate-600 mt-0.5">
                                <i class="fa-solid fa-phone-volume text-brand-gold mr-1"></i>
                                <strong>Hotline / Zalo:</strong> <a href="tel:0938758175" class="font-bold text-brand-navy hover:underline">0938.758.175</a>
                            </p>
                        </div>
                        <a href="https://share.google/f4VTtNo05hj6HXN5B" target="_blank" rel="noopener noreferrer" 
                           class="px-3.5 py-2 rounded-md bg-brand-navy hover:bg-brand-gold text-white text-xs font-bold transition inline-flex items-center gap-1.5 shadow-sm shrink-0">
                            <i class="fa-solid fa-map-location-dot"></i> Mở Google Maps Chỉ Đường
                        </a>
                    </div>

                    <!-- Bản đồ Google Maps nhúng trực tiếp ngoài trang chủ -->
                    <div class="w-full h-[270px] sm:h-[310px] rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
                        <iframe 
                            title="Bản đồ Showroom Kiến Hưng Home 162 Trần Đại Nghĩa, Ngũ Hành Sơn, Đà Nẵng"
                            src="https://maps.google.com/maps?q=162%20Tr%E1%BA%A7n%20%C4%90%E1%BA%A1i%20Ngh%C4%A9a,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột 2: Đưa Fanpage Facebook ra ngoài trang chủ (5 cột) -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between space-y-3">
                    <div class="border-b border-slate-100 pb-2.5 flex items-center justify-between">
                        <h3 class="text-sm sm:text-base font-extrabold text-brand-navy flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-lg"></i> FANPAGE KIẾN HƯNG HOME
                        </h3>
                        <span class="text-[11px] text-emerald-600 font-semibold flex items-center gap-1">
                            <span class="w-2 h-2 rounded-full bg-emerald-500 inline-block"></span> Đang trực tuyến
                        </span>
                    </div>

                    <!-- Khung giao diện Fanpage trực quan ngoài trang chủ -->
                    <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50 flex-1 flex flex-col justify-between">
                        <!-- Ảnh bìa Fanpage -->
                        <div class="relative h-36 bg-gradient-to-r from-brand-navy via-[#173b5e] to-brand-navy p-4 flex items-end">
                            <img src="https://lh3.googleusercontent.com/d/1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY=w600"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w600';"
                                 alt="Fanpage Kiến Hưng Home" class="absolute inset-0 w-full h-full object-cover opacity-30">
                            <div class="relative z-10 flex items-center gap-3">
                                <div class="w-14 h-14 rounded-lg bg-brand-navy border-2 border-white shadow-md flex items-center justify-center shrink-0">
                                    <span class="text-brand-gold font-black text-base">KH</span>
                                </div>
                                <div class="text-white">
                                    <h4 class="text-sm font-extrabold leading-tight">Kiến Hưng Home - Gạch Ốp Lát &amp; TBVệ Sinh Đà Nẵng</h4>
                                    <p class="text-[11px] text-slate-200 mt-0.5">CÔNG TY TNHH TM &amp; XD KIẾN HƯNG HOME • 4.9 ★</p>
                                </div>
                            </div>
                        </div>

                        <!-- Nội dung Fanpage -->
                        <div class="p-3.5 space-y-2.5 text-xs text-slate-600">
                            <p class="leading-relaxed">
                                Chuyên phân phối sỉ &amp; lẻ Gạch ốp lát, Đá nung kết, Gạch giả gỗ, Thiết bị vệ sinh phòng tắm cao cấp tại Đà Nẵng. Cập nhật mẫu thực tế mới mỗi ngày!
                            </p>
                            <div class="grid grid-cols-3 gap-2 pt-1">
                                <img src="https://lh3.googleusercontent.com/d/171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O=w300"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w300';"
                                     alt="Ảnh thực tế 1" class="w-full h-16 object-cover rounded border border-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP=w300"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP&sz=w300';"
                                     alt="Ảnh thực tế 2" class="w-full h-16 object-cover rounded border border-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h=w300"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h&sz=w300';"
                                     alt="Ảnh thực tế 3" class="w-full h-16 object-cover rounded border border-slate-200">
                            </div>
                        </div>

                        <!-- Nút tương tác Fanpage -->
                        <div class="p-3 bg-white border-t border-slate-200 flex items-center justify-between gap-2">
                            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" 
                               class="flex-1 py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold text-center transition">
                                <i class="fa-brands fa-facebook-f mr-1"></i> Theo Dõi Fanpage
                            </a>
                            <a href="https://zalo.me/0938758175" target="_blank" rel="noopener noreferrer" 
                               class="flex-1 py-2 px-3 rounded bg-slate-100 hover:bg-brand-gold hover:text-white text-brand-navy text-xs font-bold text-center transition">
                                <i class="fa-solid fa-comment-dots mr-1"></i> Nhắn Tin Tư Vấn
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         [FOOTER CHUẨN FLATSOME QUANG HƯNG CERAMIC]
    ====================================================================== -->
    <footer id="ve-chung-toi" class="bg-brand-navy text-slate-200 pt-10 pb-6 border-t-4 border-brand-gold">
        <div class="container-95">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-brand-navyLight">
                
                <!-- Cột 1: Thông tin pháp nhân Công ty (5 cột) -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center border border-brand-gold shrink-0">
                            <svg class="w-6 h-6" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M32 6L8 24V56H22V38H42V56H56V24L32 6Z" stroke="#e3a84f" stroke-width="4" stroke-linejoin="round"/>
                                <rect x="27" y="21" width="10" height="10" transform="rotate(45 32 21)" fill="#e3a84f"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white leading-tight">
                                CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG KIẾN HƯNG HOME
                            </h3>
                            <p class="text-[11px] text-brand-goldLight font-medium">Website chính thức: kienhunghome.com</p>
                        </div>
                    </div>

                    <ul class="space-y-2 text-xs text-slate-300 pt-1">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-brand-goldLight mt-1 shrink-0"></i>
                            <span><strong>Địa chỉ Showroom:</strong> 162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-brand-goldLight shrink-0"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0938758175" class="text-white font-bold hover:text-brand-goldLight">0938.758.175</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-brand-goldLight shrink-0"></i>
                            <span><strong>Website:</strong> <a href="https://kienhunghome.com" class="text-white hover:text-brand-goldLight">https://kienhunghome.com</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-map-pin text-brand-goldLight shrink-0"></i>
                            <span><strong>Google Map:</strong> <a href="https://share.google/f4VTtNo05hj6HXN5B" target="_blank" rel="noopener noreferrer" class="text-brand-goldLight underline">Xem vị trí trên Google Maps</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-regular fa-clock text-brand-goldLight shrink-0"></i>
                            <span><strong>Thời gian làm việc:</strong> 07h00 – 17h30 (Thứ 2 – Chủ Nhật)</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm (3 cột) -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-brand-gold/40 pb-1.5 inline-block">
                        DANH MỤC SẢN PHẨM
                    </h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Gạch lát nền')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Gạch lát nền 60x60, 80x80</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Gạch lát nền')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Gạch khổ lớn 60x120, 90x180</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Gạch ốp tường')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Gạch ốp tường 30x60, 40x80</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Gạch giả gỗ')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Gạch giả gỗ - Sàn đá vân gỗ</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Gạch lát sân vườn')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Gạch lát sân vườn chống trơn</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Thiết bị vệ sinh')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Thiết bị vệ sinh Đà Nẵng</a></li>
                        <li><a href="#san-pham-chinh" onclick="filterCategory('Tấm tường cacbon')" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Tấm tường cacbon gia cường</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Điều khoản (4 cột) -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-brand-gold/40 pb-1.5 inline-block">
                        CHÍNH SÁCH KHÁCH HÀNG
                    </h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Chính sách Giao – Nhận hàng tận công trình</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Chính sách Bảo hành chính hãng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Chính sách Đổi / Trả gạch dư nguyên hộp</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Chính sách Chiết khấu nhà thầu &amp; đại lý</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition"><i class="fa-solid fa-angle-right text-[10px] mr-1.5 text-brand-gold"></i>Hướng dẫn mua hàng &amp; thanh toán</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
                <p>© Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ XÂY DỰNG KIẾN HƯNG HOME</strong> (kienhunghome.com).</p>
                <p>162 Trần Đại Nghĩa, Phường Ngũ Hành Sơn, TP Đà Nẵng • ĐT: 0938.758.175</p>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         [CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE]
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
    ====================================================================== -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-50 flex flex-col items-end space-y-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" 
           aria-label="Chat Facebook"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white p-2.5 sm:px-3.5 sm:py-2 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-messenger text-lg sm:text-base"></i>
            <span class="hidden sm:inline text-xs font-bold">Messenger</span>
        </a>

        <!-- Nút Chat Zalo 0938.758.175 -->
        <a href="https://zalo.me/0938758175" target="_blank" rel="noopener noreferrer" 
           aria-label="Chat Zalo 0938.758.175"
           class="group flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white p-2.5 sm:px-3.5 sm:py-2 rounded-full shadow-lg transition">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068ff] font-black text-[11px] flex items-center justify-center shrink-0">Z</span>
            <span class="hidden sm:inline text-xs font-bold">Zalo: 0938.758.175</span>
        </a>

        <!-- Nút Gọi Hotline nổi bật -->
        <a href="tel:0938758175" 
           aria-label="Gọi Hotline 0938.758.175"
           class="pulse-btn flex items-center gap-2 bg-brand-redSale hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-wide">0938.758.175</span>
        </a>
    </div>

    <!-- =====================================================================
         [MODAL XEM CHI TIẾT SẢN PHẨM & BÁO GIÁ NHANH]
    ====================================================================== -->
    <div id="productModal" class="fixed inset-0 z-50 hidden bg-black/65 flex items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200 animate-fadeIn">
            <div class="flex items-center justify-between px-4 py-3 bg-brand-navy text-white">
                <h3 id="modalTitle" class="text-xs sm:text-sm font-bold pr-4">Chi tiết sản phẩm</h3>
                <button onclick="closeProductModal()" class="w-7 h-7 rounded-full bg-white/10 hover:bg-brand-gold text-white flex items-center justify-center">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5 grid grid-cols-1 sm:grid-cols-2 gap-4 items-center">
                <div class="relative aspect-square rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                    <div id="modalDiscountBadge" class="flatsome-badge-sale">-20%</div>
                    <img id="modalImg" src="" alt="Ảnh sản phẩm thực tế" class="w-full h-full object-cover">
                </div>
                <div class="space-y-2.5 text-xs sm:text-sm">
                    <span id="modalCategory" class="inline-block px-2.5 py-0.5 rounded bg-slate-100 text-brand-navy font-semibold text-[11px]">Danh mục</span>
                    <h4 id="modalName" class="text-base sm:text-lg font-extrabold text-brand-navy leading-snug"></h4>
                    <div class="flex items-baseline gap-2 pt-1">
                        <span id="modalOldPrice" class="text-xs text-slate-400 line-through"></span>
                        <span id="modalSalePrice" class="text-base sm:text-lg font-extrabold text-brand-redSale"></span>
                    </div>
                    <p id="modalSpec" class="text-xs text-slate-600 leading-relaxed bg-slate-50 p-2.5 rounded border border-slate-200"></p>
                    <div class="pt-2 space-y-2">
                        <a href="tel:0938758175" class="w-full py-2.5 px-4 rounded-md bg-brand-navy hover:bg-brand-gold text-white font-bold text-xs flex items-center justify-center gap-2 transition">
                            <i class="fa-solid fa-phone-volume"></i> Gọi Báo Giá Sỉ: 0938.758.175
                        </a>
                        <div class="grid grid-cols-2 gap-2">
                            <a href="https://zalo.me/0938758175" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-md bg-[#0068ff] text-white font-bold text-xs text-center">
                                Nhắn Zalo
                            </a>
                            <a id="modalDriveLink" href="#" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-md bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-xs text-center">
                                Xem Ảnh Gốc Drive
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         [JAVASCRIPT: DỮ LIỆU 19 ẢNH GOOGLE DRIVE THỰC TẾ & TƯƠNG TÁC TRANG CHỦ]
    ====================================================================== -->
    <script>
        // Danh sách 19 sản phẩm lấy trực tiếp từ 19 file Google Drive của bạn, phân loại đúng theo danh mục mẫu quanghungceramic.vn
        const PRODUCTS_DATA = [
            // --- NHÓM 1: GẠCH LÁT NỀN & GẠCH NHẬP KHẨU (6 Sản phẩm) ---
            {
                id: 1,
                driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                name: 'Gạch ốp lát nhập khẩu 90x180 SR918131HM Vân Đá Marble',
                category: 'Gạch lát nền',
                oldPrice: '780.000₫/m²',
                salePrice: '624.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 900x1800mm • Xương đá Porcelain siêu bóng • Phù hợp lát phòng khách biệt thự, sảnh lớn.'
            },
            {
                id: 2,
                driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
                name: 'Gạch nhập khẩu cao cấp 90x180 918YB09R Vân Đá Tự Nhiên',
                category: 'Gạch lát nền',
                oldPrice: '750.000₫/m²',
                salePrice: '615.000₫/m²',
                discountPercent: '-18%',
                spec: 'Kích thước: 900x1800mm • Bề mặt phủ men kim cương chống trầy • Phân phối tại Kiến Hưng Home.'
            },
            {
                id: 3,
                driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
                name: 'Gạch lát nền Porcelain 80x80 BH918091 Bóng Kiếng Toàn Phần',
                category: 'Gạch lát nền',
                oldPrice: '340.000₫/m²',
                salePrice: '272.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 800x800mm • Xương đá Granite chống thấm • Độ bền uốn cao, ít mạch vữa.'
            },
            {
                id: 4,
                driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
                name: 'Gạch lát nền 80x80 SR918156HM Vân Đá Khói Hiện Đại',
                category: 'Gạch lát nền',
                oldPrice: '320.000₫/m²',
                salePrice: '265.000₫/m²',
                discountPercent: '-17%',
                spec: 'Kích thước: 800x800mm • Công nghệ in kỹ thuật số 5D sắc nét • Sang trọng cho nhà phố & căn hộ.'
            },
            {
                id: 5,
                driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                name: 'Gạch lát nền 60x60 Á Mỹ 22.C.660.5162 Vân Đá Sáng Bóng',
                category: 'Gạch lát nền',
                oldPrice: '245.000₫/m²',
                salePrice: '196.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 600x600mm • Thương hiệu Á Mỹ chính hãng • Dễ dàng phối màu nội thất.'
            },
            {
                id: 6,
                driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                name: 'Gạch lát nền 60x120 Khổ Lớn Vân Đá Cẩm Thạch Mã 10001',
                category: 'Gạch lát nền',
                oldPrice: '450.000₫/m²',
                salePrice: '360.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 600x1200mm • Tạo hiệu ứng không gian liền mạch, rộng thoáng cho phòng khách.'
            },

            // --- NHÓM 2: GẠCH ỐP TƯỜNG (4 Sản phẩm) ---
            {
                id: 7,
                driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                name: 'Gạch ốp tường nhập khẩu 400x800mm Mã 480272 Men Matt',
                category: 'Gạch ốp tường',
                oldPrice: '310.000₫/m²',
                salePrice: '248.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 400x800mm • Bề mặt men Matt mịn chống bám bẩn • Chuyên ốp phòng tắm & bếp.'
            },
            {
                id: 8,
                driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
                name: 'Gạch ốp tường cao cấp 30x60 Mã 1649 Vân Đá Sáng',
                category: 'Gạch ốp tường',
                oldPrice: '215.000₫/m²',
                salePrice: '172.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 300x600mm • Mài cạnh sắc nét • Chống thấm ẩm tường tuyệt đối.'
            },
            {
                id: 9,
                driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
                name: 'Gạch ốp tường 30x60 Mã 1648 Men Matt Phun Sần Cao Cấp',
                category: 'Gạch ốp tường',
                oldPrice: '220.000₫/m²',
                salePrice: '176.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 300x600mm • Bề mặt gạch men matt phun sần sang trọng, dễ vệ sinh.'
            },
            {
                id: 10,
                driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
                name: 'Gạch ốp tường điểm trang trí 30x60 Mã 1647 Họa Tiết Nổi',
                category: 'Gạch ốp tường',
                oldPrice: '235.000₫/m²',
                salePrice: '188.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 300x600mm • Tạo điểm nhấn nghệ thuật cho phòng tắm, mặt tiền và phòng ăn.'
            },

            // --- NHÓM 3: GẠCH GIẢ GỖ & GẠCH LÁT SÂN VƯỜN (4 Sản phẩm) ---
            {
                id: 11,
                driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                name: 'Gạch giả gỗ thanh 20x100 Chống Trầy Tự Nhiên Mã 3354',
                category: 'Gạch giả gỗ',
                oldPrice: '295.000₫/m²',
                salePrice: '236.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 200x1000mm • Vân gỗ sồi tự nhiên • Chống mối mọt, chống nước 100%.'
            },
            {
                id: 12,
                driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                name: 'Sàn đá giả gỗ cao cấp 15x80 Mã 3318 Vân Gỗ Ấm Cúng',
                category: 'Gạch giả gỗ',
                oldPrice: '260.000₫/m²',
                salePrice: '215.000₫/m²',
                discountPercent: '-17%',
                spec: 'Kích thước: 150x800mm • Phù hợp lát phòng ngủ, phòng thờ, khách sạn và resort.'
            },
            {
                id: 13,
                driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                name: 'Gạch lát sân vườn chống trơn 50x50 Mã 3193 Bề Mặt Định Hình',
                category: 'Gạch lát sân vườn',
                oldPrice: '195.000₫/m²',
                salePrice: '156.000₫/m²',
                discountPercent: '-20%',
                spec: 'Kích thước: 500x500mm • Chịu lực xe ô tô tải trọng lớn, chống rêu mốc sân thượng & sân vườn.'
            },
            {
                id: 14,
                driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                name: 'Gạch lát sân vườn giả đá tự nhiên Mã 3428 Siêu Bền',
                category: 'Gạch lát sân vườn',
                oldPrice: '210.000₫/m²',
                salePrice: '168.000₫/m²',
                discountPercent: '-20%',
                spec: 'Xương Porcelain cứng chắc • Chống trơn trượt mùa mưa • Độ bền màu vĩnh cửu ngoài trời.'
            },

            // --- NHÓM 4: THIẾT BỊ VỆ SINH HIMIC & DOVA (3 Sản phẩm) ---
            {
                id: 15,
                driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                name: 'Chậu rửa mặt Lavabo bàn đá hiện đại Dova D8229 & Bồn Cầu D8360',
                category: 'Thiết bị vệ sinh',
                oldPrice: '4.600.000₫',
                salePrice: '3.680.000₫',
                discountPercent: '-20%',
                spec: 'Men sứ phủ Nano kháng khuẩn chống ố vàng • Xả xoáy êm mạnh mẽ • Bảo hành men sứ 10 năm.'
            },
            {
                id: 16,
                driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                name: 'Bồn tắm Ovan Cạnh Thẳng Cao Cấp HiMic-2402 & Sen Cây Nóng Lạnh',
                category: 'Thiết bị vệ sinh',
                oldPrice: '18.571.000₫',
                salePrice: '14.850.000₫',
                discountPercent: '-20%',
                spec: 'Chất liệu Acrylic ngọc trai chống bám bẩn • Giữ nhiệt lâu, thiết kế chuẩn Spa tại gia.'
            },
            {
                id: 17,
                driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                name: 'Bộ Tủ Chậu Lavabo Phòng Tắm Kèm Gương LED Cảm Ứng HM-T5199',
                category: 'Thiết bị vệ sinh',
                oldPrice: '6.400.000₫',
                salePrice: '4.990.000₫',
                discountPercent: '-22%',
                spec: 'Tủ nhựa PVC đặc chống nước tuyệt đối • Gương LED cảm ứng sấy khô chống mờ sương.'
            },

            // --- NHÓM 5: TẤM TƯỜNG CACBON GIA CƯỜNG & TRANH ĐÁ (2 Sản phẩm) ---
            {
                id: 18,
                driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                name: 'Tấm tường Cacbon gia cường Á Mỹ Charcoal Ash 32F.TM.080.0022',
                category: 'Tấm tường cacbon',
                oldPrice: '680.000₫/tấm',
                salePrice: '544.000₫/tấm',
                discountPercent: '-20%',
                spec: 'Kích thước: 1220x2800mm • Độ dày 8mm • Chống ẩm, cách âm, thi công ốp vách tivi & sảnh cực nhanh.'
            },
            {
                id: 19,
                driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
                name: 'Tranh đá đối xứng & Gạch khổ lớn trang trí phòng khách JX918014G',
                category: 'Bếp điện từ & Tranh đá',
                oldPrice: '1.250.000₫/m²',
                salePrice: '950.000₫/m²',
                discountPercent: '-24%',
                spec: 'Họa tiết vân đá đối xứng sang trọng • Điểm nhấn đẳng cấp cho vách Tivi và sảnh đón khách.'
            }
        ];

        // Tạo HTML cho 1 thẻ sản phẩm chuẩn Flatsome
        // Chia 2 cột trên điện thoại (grid-cols-2), tên sản phẩm hiển thị đầy đủ không bị cắt hay tràn chữ
        function createProductCardHTML(product) {
            const primaryImg = `https://lh3.googleusercontent.com/d/${product.driveId}=w600`;
            const backupImg = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w600`;
            const placeholderImg = `https://placehold.co/600x600/0f2942/e3a84f?text=Kien+Hung+Home`;

            return `
                <div class="flatsome-product-box group cursor-pointer" onclick="openProductModal(${product.id})">
                    <!-- Khung ảnh vuông có huy hiệu % giảm giá góc trên bên trái chuẩn Flatsome -->
                    <div class="relative aspect-square w-full bg-slate-100 overflow-hidden">
                        <div class="flatsome-badge-sale">${product.discountPercent}</div>
                        <img src="${primaryImg}" 
                             onerror="if(this.src!=='${backupImg}'){this.src='${backupImg}';}else{this.src='${placeholderImg}';}"
                             alt="${product.name}" 
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>

                    <!-- Khung nội dung sản phẩm: Tên sản phẩm tự động xuống dòng mượt, không bị tràn hoặc thiếu chữ -->
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wide mb-0.5">${product.category}</p>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${product.name}
                            </h3>
                        </div>

                        <div class="mt-2.5 pt-2 border-t border-slate-100">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-[11px] text-slate-400 line-through">${product.oldPrice}</span>
                                <span class="text-xs sm:text-sm font-extrabold text-brand-redSale">${product.salePrice}</span>
                            </div>
                            <div class="mt-2 flex items-center justify-between gap-1.5">
                                <span class="w-full py-1.5 px-2 rounded bg-slate-100 group-hover:bg-brand-navy group-hover:text-white text-brand-navy font-bold text-[11px] text-center transition">
                                    Xem &amp; Báo Giá
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            `;
        }

        // Render danh sách sản phẩm theo từng Section giống trang chủ quanghungceramic.vn
        function renderProductSections(filterCat = 'all', searchKeyword = '') {
            const container = document.getElementById('productSectionsContainer');
            const statusText = document.getElementById('filterStatusText');
            const keyword = searchKeyword.trim().toLowerCase();

            // Lọc sản phẩm
            const filtered = PRODUCTS_DATA.filter(item => {
                const matchCat = (filterCat === 'all') || (item.category === filterCat) || 
                                 (filterCat === 'Tấm tường cacbon' && (item.category === 'Tấm tường cacbon' || item.category === 'Bếp điện từ & Tranh đá'));
                const matchKeyword = !keyword || item.name.toLowerCase().includes(keyword) || item.category.toLowerCase().includes(keyword) || item.spec.toLowerCase().includes(keyword);
                return matchCat && matchKeyword;
            });

            statusText.textContent = `Hiển thị ${filtered.length} sản phẩm thực tế`;

            if (filtered.length === 0) {
                container.innerHTML = `
                    <div class="bg-white p-8 rounded-xl border border-slate-200 text-center space-y-3">
                        <p class="text-sm font-bold text-brand-navy">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}"</p>
                        <button onclick="filterCategory('all')" class="px-4 py-2 bg-brand-gold text-white text-xs font-bold rounded-md">
                            Xem toàn bộ 19 sản phẩm
                        </button>
                    </div>
                `;
                return;
            }

            // Nếu đang xem Tất cả và không tìm kiếm -> Chia theo từng Section Danh mục giống hệt web mẫu quanghungceramic.vn
            if (filterCat === 'all' && !keyword) {
                const groups = [
                    { title: 'GẠCH LÁT NỀN & GẠCH NHẬP KHẨU CAO CẤP', sub: 'Kích thước 60x60 • 80x80 • 60x120 • 90x180', cats: ['Gạch lát nền'] },
                    { title: 'GẠCH ỐP TƯỜNG & GẠCH MEN MATT PHUN SẦN', sub: 'Kích thước 30x60 • 40x80 • Chống thấm ẩm', cats: ['Gạch ốp tường'] },
                    { title: 'GẠCH GIẢ GỖ & GẠCH LÁT SÂN VƯỜN CHỐNG TRƠN', sub: 'Sàn đá giả gỗ 15x80, 20x100 • Gạch sân vườn 50x50', cats: ['Gạch giả gỗ', 'Gạch lát sân vườn'] },
                    { title: 'THIẾT BỊ VỆ SINH CAO CẤP & TẤM TƯỜNG CACBON GIA CƯỜNG', sub: 'Bồn cầu 1 khối • Tủ chậu Lavabo • Bồn tắm • Tấm tường Á Mỹ', cats: ['Thiết bị vệ sinh', 'Tấm tường cacbon', 'Bếp điện từ & Tranh đá'] }
                ];

                container.innerHTML = groups.map(group => {
                    const groupItems = PRODUCTS_DATA.filter(p => group.cats.includes(p.category));
                    return `
                        <div class="space-y-3">
                            <div class="flatsome-section-title">
                                <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                                    ${group.title}
                                </h2>
                                <span class="text-xs text-slate-500 hidden md:inline">${group.sub}</span>
                            </div>
                            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4-5 cột máy tính -->
                            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
                                ${groupItems.map(item => createProductCardHTML(item)).join('')}
                            </div>
                        </div>
                    `;
                }).join('');
            } else {
                // Khi lọc theo 1 danh mục cụ thể hoặc tìm kiếm
                const titleText = filterCat === 'all' ? `KẾT QUẢ TÌM KIẾM (${filtered.length} SẢN PHẨM)` : `DANH MỤC: ${filterCat.toUpperCase()}`;
                container.innerHTML = `
                    <div class="space-y-3">
                        <div class="flatsome-section-title">
                            <h2 class="flatsome-section-title-main text-sm sm:text-base md:text-lg">
                                ${titleText}
                            </h2>
                            <button onclick="filterCategory('all')" class="text-xs font-bold text-brand-gold hover:underline">
                                <i class="fa-solid fa-rotate-left mr-1"></i>Xem tất cả danh mục
                            </button>
                        </div>
                        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-2.5 sm:gap-4">
                            ${filtered.map(item => createProductCardHTML(item)).join('')}
                        </div>
                    </div>
                `;
            }
        }

        // Lọc theo danh mục
        let currentCategory = 'all';
        function filterCategory(catName) {
            currentCategory = catName;
            const searchInput = document.getElementById('searchInput');
            if (searchInput) searchInput.value = '';

            // Cập nhật trạng thái nút lọc
            document.querySelectorAll('.cat-pill').forEach(btn => {
                if (btn.getAttribute('data-cat') === catName) {
                    btn.className = 'cat-pill px-3 py-1 rounded text-xs font-bold bg-brand-navy text-white whitespace-nowrap transition';
                } else {
                    btn.className = 'cat-pill px-3 py-1 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-brand-gold hover:text-white whitespace-nowrap transition';
                }
            });

            renderProductSections(catName, '');
        }

        // Tìm kiếm sản phẩm theo từ khóa
        function filterProductsBySearch(keyword) {
            renderProductSections('all', keyword);
        }

        // Mở Modal xem chi tiết sản phẩm thực tế
        function openProductModal(productId) {
            const product = PRODUCTS_DATA.find(p => p.id === productId);
            if (!product) return;

            const modal = document.getElementById('productModal');
            const modalImg = document.getElementById('modalImg');
            const primaryImg = `https://lh3.googleusercontent.com/d/${product.driveId}=w800`;
            const backupImg = `https://drive.google.com/thumbnail?id=${product.driveId}&sz=w800`;

            modalImg.src = primaryImg;
            modalImg.onerror = function() {
                this.onerror = null;
                this.src = backupImg;
            };

            document.getElementById('modalTitle').textContent = product.name;
            document.getElementById('modalCategory').textContent = product.category;
            document.getElementById('modalName').textContent = product.name;
            document.getElementById('modalOldPrice').textContent = product.oldPrice;
            document.getElementById('modalSalePrice').textContent = product.salePrice;
            document.getElementById('modalDiscountBadge').textContent = product.discountPercent;
            document.getElementById('modalSpec').textContent = product.spec;
            document.getElementById('modalDriveLink').href = `https://drive.google.com/file/d/${product.driveId}/view?usp=sharing`;

            modal.classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productModal').classList.add('hidden');
        }

        // Đóng modal khi click ra nền ngoài
        document.getElementById('productModal').addEventListener('click', function(e) {
            if (e.target === this) closeProductModal();
        });

        // Điều khiển Menu & Tìm kiếm trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }
        function toggleMobileSearch() {
            const bar = document.getElementById('mobileSearchBar');
            bar.classList.toggle('hidden');
        }

        // Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const msg = document.getElementById('quoteSuccessMsg');
            msg.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
            setTimeout(() => {
                msg.classList.add('hidden');
            }, 7000);
        }

        // Điều khiển 2 Banner Tự Trượt (Auto Slider) kích thước bằng nhau
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function showSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            for (let i = 0; i < totalSlides; i++) {
                const slideEl = document.getElementById(`bannerSlide${i}`);
                const dotEl = document.getElementById(`bannerDot${i}`);
                if (i === currentSlide) {
                    slideEl.classList.remove('opacity-0', 'z-0');
                    slideEl.classList.add('opacity-100', 'z-10');
                    dotEl.className = 'w-6 h-2 rounded-full bg-brand-gold transition-all';
                } else {
                    slideEl.classList.remove('opacity-100', 'z-10');
                    slideEl.classList.add('opacity-0', 'z-0');
                    dotEl.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5000);
        }

        // Khởi chạy khi tải trang
        window.onload = function() {
            renderProductSections('all', '');
            resetSlideTimer();
        };
    </script>
</body>
</html>
