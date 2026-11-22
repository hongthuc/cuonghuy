<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY | Thiết Kế & Thi Công Xây Dựng Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY (cuonghuy.com) - Chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện trọn gói nhà phố, biệt thự, khách sạn, căn hộ tại Đà Nẵng. Hotline: 0905.381.458.">

    <!-- Open Graph / Thumbnail Logo khi chia sẻ link website trên Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY - cuonghuy.com">
    <meta property="og:description" content="Thiết kế kiến trúc, thi công xây dựng trọn gói nhà phố, biệt thự, khách sạn, căn hộ chuyên nghiệp tại Đà Nẵng. Địa chỉ: 37 Phan Bá Phiến, P. Sơn Trà, TP. Đà Nẵng.">
    <meta property="og:url" content="https://cuonghuy.com">
    <!-- Khi đưa lên WordPress/Flatsome (Yoast SEO / RankMath), tải ảnh Logo Công ty Cường Huy lên Thư viện Media và gắn link vào thẻ og:image bên dưới -->
    <meta property="og:image" content="https://cuonghuy.com/wp-content/uploads/logo-cuong-huy-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng chuyên nghiệp tại Đà Nẵng - Hotline: 0905.381.458">
    <meta name="twitter:image" content="https://cuonghuy.com/wp-content/uploads/logo-cuong-huy-thumbnail.png">

    <!-- Favicon sử dụng biểu tượng Logo Cường Huy -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C59'/%3E%3Cpath d='M14 30L32 14L50 30H44V48H36V35H28V48H20V30H14Z' fill='%23E59819'/%3E%3Crect x='28' y='24' width='8' height='6' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2C59',
                            navyDark: '#091E3F',
                            navyLight: '#1A407A',
                            gold: '#D98A1B',
                            goldLight: '#F0A83C',
                            goldDark: '#B8710E',
                            bg: '#F6F8FB'
                        }
                    }
                }
            }
        };
    </script>

    <style>
        /* Reset chuẩn đảm bảo không tràn viền ngang và không lệch phải trên mọi màn hình */
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
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chuẩn 95% chiều ngang màn hình máy tính, căn giữa tuyệt đối */
        .ch-container {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .ch-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }
        @media (min-width: 1024px) {
            .ch-container {
                width: 95%;
                max-width: 1720px;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Đường gạch chân tiêu đề phong cách Flatsome */
        .flatsome-divider {
            width: 56px;
            height: 3px;
            background-color: #D98A1B;
            margin: 10px auto 0;
            border-radius: 999px;
        }
        .flatsome-divider-left {
            width: 56px;
            height: 3px;
            background-color: #D98A1B;
            margin: 10px 0 0;
            border-radius: 999px;
        }

        /* Menu dropdown Flatsome đơn giản, mượt */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Tab danh mục: Không xuống dòng trong tên danh mục */
        .cat-tab-btn {
            white-space: nowrap;
            transition: all 0.2s ease;
        }
        .cat-tab-btn.active {
            background-color: #0F2C59;
            color: #FFFFFF;
            border-color: #0F2C59;
        }

        /* Thanh cuộn ngang mượt cho danh mục trên mobile nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Banner slider kích thước đồng đều 100% giữa 2 slide */
        .banner-track {
            display: flex;
            transition: transform 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
            will-change: transform;
        }
        .banner-slide {
            min-width: 100%;
            width: 100%;
            flex-shrink: 0;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(217, 138, 27, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(217, 138, 27, 0); }
            100% { box-shadow: 0 0 0 0 rgba(217, 138, 27, 0); }
        }
        .hotline-pulse {
            animation: softPulse 2.2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800">

    <!-- ==================== UX BUILDER: TOP BAR ==================== -->
    <div class="bg-brand-navy text-white text-xs py-2 border-b border-white/10">
        <div class="ch-container flex flex-col sm:flex-row items-center justify-between gap-1.5">
            <div class="flex flex-wrap items-center justify-center sm:justify-start gap-x-4 gap-y-1 text-slate-200">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-brand-goldLight"></i>
                    <span>37 Phan Bá Phiến, Phường Sơn Trà, TP Đà Nẵng</span>
                </span>
                <span class="hidden md:inline text-white/30">|</span>
                <a href="mailto:info@cuonghuy.com" class="hidden md:inline-flex items-center gap-1.5 hover:text-brand-goldLight transition">
                    <i class="fa-solid fa-envelope text-brand-goldLight"></i>
                    <span>info@cuonghuy.com</span>
                </a>
            </div>
            <div class="flex items-center gap-3">
                <a href="tel:0905381458" class="inline-flex items-center gap-1.5 font-semibold text-brand-goldLight hover:text-white transition">
                    <i class="fa-solid fa-phone"></i>
                    <span>Hotline: 0905.381.458</span>
                </a>
                <span class="text-white/30">|</span>
                <span class="text-slate-200 font-medium">cuonghuy.com</span>
            </div>
        </div>
    </div>

    <!-- ==================== UX BUILDER: HEADER (KHÔNG CÓ NÚT GỌI NGAY, LOGO GỌN NHỎ, MENU 1 HÀNG) ==================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="ch-container h-16 lg:h-[70px] flex items-center justify-between gap-3">

            <!-- Logo Công ty Cường Huy chuyên nghiệp, gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY">
                <svg class="w-9 h-9 lg:w-10 lg:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="10" fill="#0F2C59"/>
                    <path d="M12 31L32 13L52 31" stroke="#E59819" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M19 29V49H28V37H36V49H45V29" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                    <rect x="29" y="23" width="6" height="6" rx="1" fill="#E59819"/>
                    <line x1="14" y1="53" x2="50" y2="53" stroke="#E59819" stroke-width="3" stroke-linecap="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm lg:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition">CƯỜNG HUY</div>
                    <div class="text-[9.5px] lg:text-[10px] font-semibold tracking-wider text-brand-gold uppercase">Xây Dựng &amp; Thương Mại</div>
                </div>
            </a>

            <!-- Menu Desktop: Viết liền trên 1 hàng, chữ nhỏ gọn, không xuống dòng, không tràn viền -->
            <nav class="hidden lg:flex items-center justify-end flex-1 gap-1 xl:gap-2" aria-label="Menu chính">
                <a href="#trang-chu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-gold whitespace-nowrap transition">Trang chủ</a>
                <a href="#gioi-thieu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Giới thiệu</a>

                <!-- Dropdown: Công trình thực tế -->
                <div class="relative nav-item">
                    <a href="#cong-trinh-thuc-te" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap inline-flex items-center gap-1 transition">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5">
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('khach-san-can-ho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('biet-thu-nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Biệt thự &amp; Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('van-phong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Văn phòng – Thương mại</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="relative nav-item">
                    <a href="#dich-vu" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap inline-flex items-center gap-1 transition">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
                        <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-1.5">
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('thiet-ke')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('phan-tho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Thi công phần thô</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('hoan-thien')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Thi công hoàn thiện</a>
                            <a href="#cong-trinh-thuc-te" onclick="selectProductCategory('thiet-ke')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-bg hover:text-brand-navy">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Dự án Đà Nẵng</a>
                <a href="#bao-gia" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Báo giá</a>
                <a href="#doi-tac" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Đối tác</a>
                <a href="#tin-tuc" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Tin tức</a>
                <a href="#lien-he" class="px-2 xl:px-2.5 py-2 text-[12.5px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-gold whitespace-nowrap transition">Liên hệ</a>
            </nav>

            <!-- Nút Mở Menu Mobile -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-100 transition" aria-label="Mở menu">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Drawer Menu Mobile -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="ch-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-medium">
                <a href="#trang-chu" class="mobile-nav-link py-2.5 text-brand-navy font-semibold">Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link py-2.5 text-slate-700">Giới thiệu</a>
                <a href="#dich-vu" class="mobile-nav-link py-2.5 text-slate-700">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 text-slate-700">Công trình thực tế &amp; Sản phẩm</a>
                <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 text-slate-700">Các dự án tại Đà Nẵng</a>
                <a href="#doi-tac" class="mobile-nav-link py-2.5 text-slate-700">Đối tác</a>
                <a href="#bao-gia" class="mobile-nav-link py-2.5 text-slate-700">Yêu cầu &amp; Báo giá</a>
                <a href="#tin-tuc" class="mobile-nav-link py-2.5 text-slate-700">Tin tức &amp; Bài viết</a>
                <a href="#lien-he" class="mobile-nav-link py-2.5 text-slate-700">Bản đồ &amp; Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- ==================== UX BUILDER: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU, CHỮ CÁCH XA VIỀN) ==================== -->
    <section id="trang-chu" class="py-3 sm:py-4 lg:py-5 bg-brand-bg">
        <div class="ch-container">
            <div id="heroSlider" class="relative overflow-hidden rounded-xl shadow-md bg-brand-navy select-none">
                <div id="bannerTrack" class="banner-track">

                    <!-- BANNER 1 -->
                    <div class="banner-slide relative bg-gradient-to-br from-brand-navyDark via-brand-navy to-brand-navyLight">
                        <!-- Lề an toàn lớn trên cả điện thoại và máy tính để hình và chữ nằm trọn bên trong, cách xa viền -->
                        <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-6 lg:gap-10 px-7 sm:px-12 md:px-16 lg:px-20 py-9 sm:py-12 lg:py-14 min-h-[380px] sm:min-h-[410px] lg:min-h-[450px]">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-[0.18em] text-brand-goldLight">
                                    CUONGHUY.COM &bull; UY TÍN TẠI ĐÀ NẴNG
                                </p>
                                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                    CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY
                                </h1>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                    Chuyên Thiết kế Kiến trúc – Thi công phần thô – Thi công hoàn thiện trọn gói Nhà phố, Biệt thự, Khách sạn và Căn hộ với tiêu chuẩn kỹ thuật cao và tiến độ cam kết.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3">
                                    <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold shadow transition">
                                        Nhận Báo Giá Miễn Phí
                                    </a>
                                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-xs sm:text-sm font-semibold transition">
                                        Xem Dự Án Đà Nẵng
                                    </a>
                                </div>
                            </div>
                            <div class="lg:col-span-5">
                                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-xl aspect-[16/10] bg-slate-800">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1200"
                                        data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                                        onerror="handleDriveError(this)"
                                        alt="Thi công xây dựng thực tế Công ty Cường Huy"
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 (Cấu trúc và chiều cao đồng nhất 100% với Banner 1) -->
                    <div class="banner-slide relative bg-gradient-to-br from-brand-navy via-brand-navyLight to-brand-navyDark">
                        <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-6 lg:gap-10 px-7 sm:px-12 md:px-16 lg:px-20 py-9 sm:py-12 lg:py-14 min-h-[380px] sm:min-h-[410px] lg:min-h-[450px]">
                            <div class="lg:col-span-7 text-white space-y-3 sm:space-y-4">
                                <p class="text-[11px] sm:text-xs font-semibold uppercase tracking-[0.18em] text-brand-goldLight">
                                    GIẢI PHÁP XÂY DỰNG TOÀN DIỆN &bull; BẢO HÀNH DÀI HẠN
                                </p>
                                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                                    KIẾN TẠO CÔNG TRÌNH BỀN VỮNG TẠI ĐÀ NẴNG
                                </h2>
                                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed max-w-2xl">
                                    Đội ngũ kỹ sư và thợ lành nghề trực tiếp giám sát từng hạng mục. Minh bạch vật tư, tối ưu chi phí đầu tư, đảm bảo an toàn và thẩm mỹ vượt thời gian.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-3">
                                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold shadow transition">
                                        Xem Công Trình Thực Tế
                                    </a>
                                    <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-xs sm:text-sm font-semibold transition">
                                        Liên Hệ Tư Vấn
                                    </a>
                                </div>
                            </div>
                            <div class="lg:col-span-5">
                                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-xl aspect-[16/10] bg-slate-800">
                                    <img
                                        src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1200"
                                        data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                                        onerror="handleDriveError(this)"
                                        alt="Dự án tiêu biểu tại Đà Nẵng - Công ty Cường Huy"
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng banner gọn gàng hai bên (chỉ hiện rõ khi hover trên desktop, không che chữ) -->
                <button id="prevBanner" type="button" aria-label="Banner trước" class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/30 hover:bg-brand-gold text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button id="nextBanner" type="button" aria-label="Banner sau" class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/30 hover:bg-brand-gold text-white items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chỉ báo 2 slide ở đáy -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                    <button type="button" class="banner-dot w-7 h-2 rounded-full bg-brand-gold transition-all" data-index="0" aria-label="Slide 1"></button>
                    <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" data-index="1" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: DỊCH VỤ TIÊU BIỂU (THEO MẪU TINTRUONGTHINH.COM) ==================== -->
    <section id="dich-vu" class="py-10 sm:py-12 bg-white">
        <div class="ch-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">Dịch Vụ Tiêu Biểu</h2>
                <div class="flatsome-divider"></div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Dịch vụ 1 -->
                <div class="group rounded-xl border border-slate-200 bg-white overflow-hidden hover:shadow-lg hover:border-brand-gold/50 transition">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1000" data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR" onerror="handleDriveError(this)" alt="Thiết kế kiến trúc và nội thất" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 sm:p-5 text-center">
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase">Thiết Kế Kiến Trúc</h3>
                        <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">Lập phương án mặt bằng công năng, phối cảnh 3D hiện đại, hồ sơ kỹ thuật thi công chi tiết cho nhà phố, biệt thự, khách sạn.</p>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="group rounded-xl border border-slate-200 bg-white overflow-hidden hover:shadow-lg hover:border-brand-gold/50 transition">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000" data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv" onerror="handleDriveError(this)" alt="Thi công xây dựng phần thô và trọn gói" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 sm:p-5 text-center">
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase">Thi Công Xây Dựng</h3>
                        <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay, đảm bảo kết cấu vững chắc, đúng tiến độ.</p>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="group rounded-xl border border-slate-200 bg-white overflow-hidden hover:shadow-lg hover:border-brand-gold/50 transition">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w1000" data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_" onerror="handleDriveError(this)" alt="Thi công nội thất và thương mại vật liệu" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                    </div>
                    <div class="p-4 sm:p-5 text-center">
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy uppercase">Hoàn Thiện &amp; Nội Thất</h3>
                        <p class="mt-2 text-xs sm:text-sm text-slate-600 leading-relaxed">Thi công hoàn thiện nội ngoại thất, gia công cơ khí xây dựng và cung ứng vật liệu xây dựng chất lượng cao giá xưởng.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: GIỚI THIỆU CÔNG TY & THẾ MẠNH ==================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-bg border-y border-slate-200/70">
        <div class="ch-container">
            <!-- Phần Giới thiệu -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10 sm:mb-12">
                <div class="lg:col-span-6 space-y-3.5">
                    <div>
                        <p class="text-xs font-bold uppercase tracking-wider text-brand-gold">Về Chúng Tôi</p>
                        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy leading-snug mt-1">
                            CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY
                        </h2>
                        <div class="flatsome-divider-left"></div>
                    </div>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY</strong> (Mã số thuế: <strong>0402166728</strong>) là đơn vị chuyên sâu trong lĩnh vực Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất và Thương mại vật tư cho các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại khu vực Đà Nẵng &amp; Miền Trung.
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Với phương châm <strong>“An Toàn – Chất Lượng – Tiến Độ – Tận Tâm”</strong>, Cường Huy đặt uy tín lên hàng đầu trong từng hạng mục thi công. Mọi công trình đều được kỹ sư giám sát chặt chẽ, sử dụng vật liệu đúng chủng loại cam kết và hưởng chính sách bảo hành dài hạn minh bạch.
                    </p>
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="rounded-lg bg-white p-3 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Đúng tiến độ</div>
                        </div>
                        <div class="rounded-lg bg-white p-3 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-gold">50+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình Đà Nẵng</div>
                        </div>
                        <div class="rounded-lg bg-white p-3 border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">24/7</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Hỗ trợ tận tâm</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-6">
                    <div class="grid grid-cols-2 gap-3">
                        <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w1000" data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO" onerror="handleDriveError(this)" alt="Thi công thực tế tại công trường Cường Huy" class="w-full h-full object-cover">
                        </div>
                        <div class="rounded-xl overflow-hidden shadow-sm border border-slate-200 aspect-[4/3] bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w1000" data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t" onerror="handleDriveError(this)" alt="Giám sát kỹ thuật xây dựng Cường Huy" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>

            <!-- Thế mạnh của chúng tôi (6 điểm nổi bật giống tintruongthinh.com) -->
            <div class="text-center mb-7">
                <h3 class="text-base sm:text-xl font-extrabold text-brand-navy uppercase">Thế Mạnh Của Cường Huy</h3>
                <div class="flatsome-divider"></div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-helmet-safety text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Đội ngũ kỹ sư chuyên nghiệp</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư hiện trường và tổ đội thi công lành nghề, giàu kinh nghiệm thực chiến.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-compass-drafting text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Giải pháp thi công hiện đại</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Liên tục cập nhật xu hướng kiến trúc mới, vật liệu bền vững và biện pháp thi công tối ưu công năng sử dụng.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-clipboard-check text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Báo cáo tiến độ công trường định kỳ bằng hình ảnh thực tế giúp chủ đầu tư yên tâm theo dõi mọi lúc, mọi nơi.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-halved text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Bảo hành công trình dài lâu</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Cam kết bảo hành kết cấu và hạng mục hoàn thiện rõ ràng, có mặt xử lý nhanh chóng khi khách hàng cần hỗ trợ.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Chi phí hợp lý, không phát sinh</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Dự toán bóc tách khối lượng rõ ràng từng hạng mục, cân đối ngân sách hợp lý nhất theo nhu cầu chủ đầu tư.</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl p-5 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-10 h-10 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-headset text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold text-brand-navy">Tư vấn &amp; khảo sát miễn phí</h4>
                        <p class="text-xs text-slate-600 mt-1 leading-relaxed">Hỗ trợ khảo sát thực địa, tư vấn pháp lý xin phép xây dựng và lên dự toán sơ bộ hoàn toàn miễn phí 24/7.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: DANH MỤC SẢN PHẨM & CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH DRIVE THỰC TẾ) ==================== -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
        <div class="ch-container">
            <div class="text-center mb-5 sm:mb-7">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">Danh Mục Sản Phẩm &amp; Thi Công Thực Tế</h2>
                <div class="flatsome-divider"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5">Hình ảnh thi công thực tế và các hạng mục dịch vụ xây dựng của Công ty Cường Huy</p>
            </div>

            <!-- Thanh Danh Mục: Chữ nhỏ gọn, viết liền trên 1 hàng không xuống dòng tên danh mục, đẹp trên PC & Mobile -->
            <div id="productCategoryTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
                <button type="button" data-cat="all" class="cat-tab-btn active px-3 py-1.5 rounded-md border border-slate-200 text-[11.5px] sm:text-[12.5px] font-semibold">Tất cả</button>
                <button type="button" data-cat="phan-tho" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Thi công phần thô</button>
                <button type="button" data-cat="hoan-thien" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Thi công hoàn thiện</button>
                <button type="button" data-cat="thiet-ke" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Thiết kế Kiến trúc - Nội thất</button>
                <button type="button" data-cat="khach-san-can-ho" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Khách sạn - Căn hộ</button>
                <button type="button" data-cat="biet-thu-nha-pho" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Biệt thự - Nhà phố</button>
                <button type="button" data-cat="van-phong" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Văn phòng</button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3-4 cột trên máy tính, tên hiển thị đầy đủ không thiếu chữ, không có nhãn dán -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu được render tự động từ 9 ảnh Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG (10 ẢNH DRIVE DỰ ÁN ĐÀ NẴNG) ==================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-bg border-y border-slate-200/70">
        <div class="ch-container">
            <div class="text-center mb-5 sm:mb-7">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">Các Dự Án Tiêu Biểu Tại Đà Nẵng</h2>
                <div class="flatsome-divider"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5">Tổng hợp công trình nhà ở, biệt thự, khách sạn, căn hộ do Cường Huy thực hiện tại Đà Nẵng</p>
            </div>

            <!-- Thanh Danh Mục Dự Án Đà Nẵng: Gọn đẹp, không xuống dòng tên danh mục -->
            <div id="projectCategoryTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8">
                <button type="button" data-proj="all" class="cat-tab-btn active px-3 py-1.5 rounded-md border border-slate-200 text-[11.5px] sm:text-[12.5px] font-semibold">Tất cả dự án</button>
                <button type="button" data-proj="nha-pho-dn" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Nhà phố Đà Nẵng</button>
                <button type="button" data-proj="khach-san-dn" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Khách sạn - Căn hộ</button>
                <button type="button" data-proj="biet-thu-dn" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Biệt thự - Homestay</button>
                <button type="button" data-proj="van-phong-dn" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 text-slate-700 hover:border-brand-navy text-[11.5px] sm:text-[12.5px] font-semibold">Văn phòng - Thương mại</button>
            </div>

            <!-- Lưới Dự án Đà Nẵng: 2 cột trên mobile, 4-5 cột trên desktop -->
            <div id="daNangProjectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Dữ liệu được render tự động từ 10 ảnh Drive dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: DANH MỤC CÁC ĐỐI TÁC ==================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white">
        <div class="ch-container">
            <div class="text-center mb-7">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">Đối Tác &amp; Thương Hiệu Đồng Hành</h2>
                <div class="flatsome-divider"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5">Cam kết cung ứng vật tư chính hãng từ các thương hiệu xây dựng uy tín hàng đầu</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">HÒA PHÁT STEEL</div>
                    <div class="text-[11px] text-slate-500 mt-1">Thép xây dựng tiêu chuẩn</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XI MĂNG SÔNG GIANH</div>
                    <div class="text-[11px] text-slate-500 mt-1">Vật liệu kết cấu bền vững</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">DULUX PAINT</div>
                    <div class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất cao cấp</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">NHÔM XINGFA</div>
                    <div class="text-[11px] text-slate-500 mt-1">Hệ cửa nhôm kính chính hãng</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">ĐỒNG TÂM GROUP</div>
                    <div class="text-[11px] text-slate-500 mt-1">Gạch ốp lát &amp; ngói màu</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">PANASONIC</div>
                    <div class="text-[11px] text-slate-500 mt-1">Thiết bị điện dân dụng</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">GỖ AN CƯỜNG</div>
                    <div class="text-[11px] text-slate-500 mt-1">Vật liệu gỗ nội thất</div>
                </div>
                <div class="rounded-xl border border-slate-200 bg-brand-bg/50 px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">TÔN HOA SEN</div>
                    <div class="text-[11px] text-slate-500 mt-1">Tôn lợp &amp; ống thép mạ kẽm</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
        <div class="ch-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột thông tin tư vấn -->
                <div class="lg:col-span-5 space-y-4">
                    <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight">Tư Vấn Miễn Phí 24/7</p>
                    <h2 class="text-xl sm:text-3xl font-extrabold leading-snug">GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ XÂY DỰNG</h2>
                    <div class="flatsome-divider-left"></div>
                    <p class="text-sm text-slate-200 leading-relaxed">
                        Quý khách đang có kế hoạch xây mới nhà phố, biệt thự, khách sạn, căn hộ hay cải tạo công trình tại Đà Nẵng? Hãy để lại thông tin, đội ngũ kỹ sư Công ty Cường Huy sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
                    </p>
                    <div class="space-y-2.5 pt-2 text-sm text-slate-100">
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-goldLight shrink-0"><i class="fa-solid fa-phone"></i></span>
                            <span>Hotline / Zalo: <strong class="text-brand-goldLight">0905.381.458</strong></span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-goldLight shrink-0"><i class="fa-solid fa-location-dot"></i></span>
                            <span>37 Phan Bá Phiến, Phường Sơn Trà, TP Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-goldLight shrink-0"><i class="fa-solid fa-globe"></i></span>
                            <span>Website: cuonghuy.com</span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form Báo Giá (Giống cấu trúc tintruongthinh.com) -->
                <div class="lg:col-span-7">
                    <form id="quoteForm" class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của quý khách" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại *</label>
                                <input id="qPhone" type="tel" required placeholder="VD: 0905.xxx.xxx" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Khách sạn – Căn hộ – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Văn phòng – Thương mại">Văn phòng – Thương mại</option>
                                    <option value="Thi công phần thô">Thi công phần thô</option>
                                    <option value="Thi công hoàn thiện trọn gói">Thi công hoàn thiện trọn gói</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ - 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email (không bắt buộc)</label>
                            <input id="qEmail" type="email" placeholder="Nhập email nhận bảng báo giá" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy">
                        </div>

                        <div>
                            <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết (Diện tích, số tầng, khu vực...)</label>
                            <textarea id="qNote" rows="3" placeholder="VD: Xây nhà phố 3 tầng diện tích 5x20m tại quận Sơn Trà, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-navy focus:ring-1 focus:ring-brand-navy"></textarea>
                        </div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm uppercase tracking-wide shadow transition">
                            Gửi Yêu Cầu Nhận Báo Giá
                        </button>

                        <!-- Thông báo phản hồi trực tiếp không dùng alert() -->
                        <div id="quoteFeedback" class="hidden rounded-lg p-3.5 text-sm font-medium"></div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
        <div class="ch-container">
            <div class="text-center mb-7">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">Tin Tức &amp; Kinh Nghiệm Xây Dựng</h2>
                <div class="flatsome-divider"></div>
                <p class="text-xs sm:text-sm text-slate-500 mt-2.5">Chia sẻ kiến thức kỹ thuật thi công, phong thủy và kinh nghiệm tối ưu chi phí xây dựng</p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="blogGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render bài viết qua JS để hỗ trợ đọc chi tiết mượt mà -->
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: GOOGLE MAP & FANPAGE NGOÀI TRANG CHỦ ==================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-bg border-t border-slate-200">
        <div class="ch-container">
            <div class="text-center mb-7">
                <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage</h2>
                <div class="flatsome-divider"></div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột Google Maps trực tiếp ra ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-sm font-bold text-brand-navy">
                            <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                            <span>Trụ sở: 37 Phan Bá Phiến, Phường Sơn Trà, TP Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=37+Phan+Ba+Phien,+Son+Tra,+Da+Nang" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-gold hover:underline whitespace-nowrap">
                            Mở trên Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                        </a>
                    </div>
                    <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty TNHH Xây Dựng và Thương Mại Cường Huy - 37 Phan Bá Phiến, Sơn Trà, Đà Nẵng"
                            src="https://maps.google.com/maps?q=37+Phan+Ba+Phien,+Son+Tra,+Da+Nang&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage trực tiếp ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="px-4 py-3 border-b border-slate-100 flex items-center justify-between">
                        <div class="flex items-center gap-2 text-sm font-bold text-brand-navy">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                            <span>Fanpage Chính Thức</span>
                        </div>
                        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-[#1877F2] hover:underline">
                            Theo dõi ngay
                        </a>
                    </div>

                    <!-- Khối hiển thị Fanpage chuẩn Flatsome (Khi đưa lên WordPress có thể dán mã Facebook Page Plugin vào khối này) -->
                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <!-- Ảnh bìa & Avatar Fanpage -->
                        <div class="rounded-lg border border-slate-200 overflow-hidden">
                            <div class="relative h-32 sm:h-36 bg-brand-navy overflow-hidden">
                                <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800" data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff" onerror="handleDriveError(this)" alt="Ảnh bìa Fanpage Công ty Cường Huy" class="w-full h-full object-cover opacity-80">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white flex items-center justify-center shrink-0 shadow">
                                        <svg class="w-9 h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M12 31L32 13L52 31" stroke="#E59819" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M19 29V49H28V37H36V49H45V29" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                                            <rect x="29" y="23" width="6" height="6" rx="1" fill="#E59819"/>
                                        </svg>
                                    </div>
                                    <div class="text-white min-w-0">
                                        <div class="text-sm font-bold leading-tight truncate">Xây Dựng &amp; Thương Mại Cường Huy</div>
                                        <div class="text-[11px] text-slate-200 mt-0.5">Công ty Xây dựng tại Đà Nẵng &bull; cuonghuy.com</div>
                                    </div>
                                </div>
                            </div>

                            <!-- Thanh hành động Fanpage -->
                            <div class="p-3 bg-slate-50 flex items-center justify-between gap-2 border-t border-slate-200">
                                <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2 px-3 rounded-md bg-[#1877F2] hover:bg-[#145DBF] text-white text-xs font-semibold transition">
                                    <i class="fa-solid fa-thumbs-up"></i>
                                    <span>Thích Trang</span>
                                </a>
                                <a href="https://m.me/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2 px-3 rounded-md bg-white border border-slate-300 hover:bg-slate-100 text-slate-700 text-xs font-semibold transition">
                                    <i class="fa-brands fa-facebook-messenger text-[#0084FF]"></i>
                                    <span>Nhắn Tin</span>
                                </a>
                            </div>
                        </div>

                        <!-- Hoạt động cập nhật gần đây trên Fanpage -->
                        <div class="space-y-2.5 text-xs text-slate-600">
                            <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-brand-bg">
                                <i class="fa-solid fa-circle-check text-brand-gold mt-0.5 shrink-0"></i>
                                <div>
                                    <strong class="text-brand-navy">Cập nhật tiến độ công trường hàng ngày:</strong> Hình ảnh thực tế thi công móng, đổ sàn và hoàn thiện nội thất tại Đà Nẵng.
                                </div>
                            </div>
                            <div class="flex items-start gap-2.5 p-2.5 rounded-lg bg-brand-bg">
                                <i class="fa-solid fa-circle-check text-brand-gold mt-0.5 shrink-0"></i>
                                <div>
                                    <strong class="text-brand-navy">Tư vấn trực tuyến nhanh chóng:</strong> Nhắn tin trực tiếp qua Fanpage hoặc Zalo <strong class="text-brand-navy">0905.381.458</strong> để nhận bảng giá mới nhất.
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== UX BUILDER: FOOTER ==================== -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-6 border-t-4 border-brand-gold">
        <div class="ch-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="10" fill="#1A407A"/>
                            <path d="M12 31L32 13L52 31" stroke="#E59819" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M19 29V49H28V37H36V49H45V29" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>
                            <rect x="29" y="23" width="6" height="6" rx="1" fill="#E59819"/>
                        </svg>
                        <div>
                            <div class="text-sm font-extrabold text-white">CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY</div>
                            <div class="text-[11px] text-brand-goldLight">CUONG HUY CONSTRUCTION &amp; TRADING CO., LTD</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm pt-1">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-goldLight mt-1 shrink-0"></i>
                            <span>Trụ sở: 37 Phan Bá Phiến, Phường Sơn Trà, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-goldLight shrink-0"></i>
                            <a href="tel:0905381458" class="hover:text-white transition">Hotline / Zalo: <strong>0905.381.458</strong></a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-goldLight shrink-0"></i>
                            <span>Website: cuonghuy.com</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-file-contract text-brand-goldLight shrink-0"></i>
                            <span>Mã số thuế: 0402166728</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide">Lĩnh Vực Hoạt Động</h4>
                    <div class="w-10 h-0.5 bg-brand-gold"></div>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('thiet-ke')" class="hover:text-brand-goldLight transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('phan-tho')" class="hover:text-brand-goldLight transition">Thi công xây dựng phần thô</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="selectProductCategory('hoan-thien')" class="hover:text-brand-goldLight transition">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition">Dự án nhà phố &amp; biệt thự Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition">Báo giá thi công xây dựng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide">Cam Kết Chất Lượng</h4>
                    <div class="w-10 h-0.5 bg-brand-gold"></div>
                    <p class="text-xs sm:text-sm leading-relaxed text-slate-300">
                        Cường Huy cam kết mang đến công trình bền vững, thẩm mỹ cao, minh bạch vật tư và bảo hành dài hạn cho mọi khách hàng tại Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <div class="flex items-center gap-2.5 pt-1">
                        <a href="https://zalo.me/0905381458" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-[#0068FF] hover:bg-[#0055D4] text-white text-xs font-semibold transition">
                            Chat Zalo
                        </a>
                        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded-lg bg-[#1877F2] hover:bg-[#145DBF] text-white text-xs font-semibold transition">
                            Facebook
                        </a>
                        <a href="tel:0905381458" class="px-3.5 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs font-semibold transition">
                            0905.381.458
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright 2026 &copy; <strong>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI CƯỜNG HUY</strong> (cuonghuy.com). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH PC & MOBILE) ==================== -->
    <div class="fixed right-3 sm:right-4 bottom-4 sm:bottom-5 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905381458" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Zalo 0905.381.458" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[11px] shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Facebook Cường Huy" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#145DBF] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-sm shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0905381458" aria-label="Gọi Hotline 0905.381.458" class="hotline-pulse group flex items-center gap-2 bg-brand-gold hover:bg-brand-goldDark text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition">
            <span class="w-6 h-6 rounded-full bg-white text-brand-goldDark flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="hidden sm:inline text-xs font-bold pr-1">0905.381.458</span>
        </a>
    </div>

    <!-- ==================== MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT ==================== -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden bg-black/65 backdrop-blur-xs items-center justify-center p-3 sm:p-5">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="sticky top-0 bg-white px-4 sm:px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
                <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-navy leading-snug"></h3>
                <button id="closeModalBtn" type="button" class="w-8 h-8 rounded-lg hover:bg-slate-100 text-slate-500 flex items-center justify-center shrink-0" aria-label="Đóng">
                    <i class="fa-solid fa-xmark text-base"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5 space-y-4">
                <div class="rounded-lg overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img id="modalImg" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div id="modalMeta" class="text-xs font-semibold text-brand-gold uppercase tracking-wide"></div>
                <div id="modalDesc" class="text-sm text-slate-600 leading-relaxed space-y-2"></div>
                <div class="pt-2 flex flex-wrap items-center gap-2.5 border-t border-slate-100">
                    <a href="#bao-gia" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs sm:text-sm font-semibold transition">Yêu cầu báo giá hạng mục này</a>
                    <a href="tel:0905381458" class="px-4 py-2 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white text-xs sm:text-sm font-semibold transition">Gọi 0905.381.458</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        /* ==================== XỬ LÝ TẢI ẢNH GOOGLE DRIVE AN TOÀN (CÓ FALLBACK ĐA TẦNG) ==================== */
        function getDriveThumb(id, size = 'w1000') {
            return `https://drive.google.com/thumbnail?id=${id}&sz=${size}`;
        }

        function handleDriveError(img) {
            const driveId = img.getAttribute('data-drive-id');
            const step = parseInt(img.getAttribute('data-err-step') || '0', 10);
            if (step === 0 && driveId) {
                img.setAttribute('data-err-step', '1');
                img.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/800x600/0F2C59/FFFFFF?text=Cuong+Huy+Construction';
            }
        }

        /* ==================== DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG ==================== */
        const constructionProducts = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                name: 'Thi Công Kết Cấu Phần Thô Nhà Phố Hiện Đại',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                desc: 'Hạng mục thi công móng, khung cột, dầm sàn bê tông cốt thép chuẩn kỹ thuật, đảm bảo mác bê tông và hệ thép chịu lực theo hồ sơ kết cấu tại công trường Công ty Cường Huy.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                name: 'Thiết Kế & Thi Công Mặt Tiền Nhà Phố Trọn Gói',
                category: 'biet-thu-nha-pho',
                categoryLabel: 'Biệt thự - Nhà phố',
                desc: 'Giải pháp thiết kế và thi công trọn gói nhà phố hiện đại, tối ưu ánh sáng tự nhiên, chống thấm và độ bền mặt tiền phù hợp khí hậu ven biển Đà Nẵng.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                name: 'Thi Công Hệ Khung Bê Tông Cốt Thép Công Trình',
                category: 'phan-tho',
                categoryLabel: 'Thi công phần thô',
                desc: 'Thi công lắp dựng cốp pha, gia công cốt thép sàn và đổ bê tông đúng quy trình kỹ thuật, có kỹ sư giám sát nghiệm thu từng giai đoạn.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                name: 'Thi Công Hoàn Thiện Ốp Lát & Sơn Nước Nội Ngoại Thất',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                desc: 'Hoàn thiện tường xây tô phẳng mịn, chống thấm triệt để khu vực ẩm ướt, ốp lát gạch men và sơn hoàn thiện sắc nét từng chi tiết.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                name: 'Thi Công Xây Dựng Khách Sạn & Căn Hộ Dịch Vụ',
                category: 'khach-san-can-ho',
                categoryLabel: 'Khách sạn - Căn hộ',
                desc: 'Tổng thầu xây dựng và hoàn thiện hệ thống căn hộ cho thuê, khách sạn mini với công năng tối ưu doanh thu và hệ thống kỹ thuật MEP đồng bộ.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                name: 'Thi Công Lắp Đặt Hạ Tầng Điện Nước & Cơ Khí Xây Dựng',
                category: 'hoan-thien',
                categoryLabel: 'Thi công hoàn thiện',
                desc: 'Triển khai hệ thống cấp thoát nước, điện âm tường an toàn, kết cấu khung thép và gia công cơ khí công trình đạt chuẩn nghiệm thu.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                name: 'Thiết Kế Kiến Trúc & Thi Công Nội Thất Đồng Bộ',
                category: 'thiet-ke',
                categoryLabel: 'Thiết kế Kiến trúc - Nội thất',
                desc: 'Thiết kế không gian sống sang trọng, bố trí nội thất gỗ công nghiệp và tự nhiên cao cấp, đảm bảo tính thẩm mỹ cao và tiện nghi tối đa.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                name: 'Thi Công Văn Phòng Làm Việc & Không Gian Thương Mại',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                desc: 'Thiết kế và thi công trọn gói văn phòng công ty, showroom thương mại với tiến độ nhanh, không gian chuyên nghiệp, nâng tầm hình ảnh doanh nghiệp.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                name: 'Cải Tạo Nâng Tầng & Hoàn Thiện Biệt Thự Cao Cấp',
                category: 'biet-thu-nha-pho',
                categoryLabel: 'Biệt thự - Nhà phố',
                desc: 'Khảo sát hiện trạng kết cấu, gia cố móng cột và thi công cải tạo nâng tầng, làm mới hoàn toàn diện mạo kiến trúc cho nhà ở và biệt thự.'
            }
        ];

        /* ==================== DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG ==================== */
        const daNangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                name: 'Nhà Phố 3 Tầng Hiện Đại – Sơn Trà, Đà Nẵng',
                category: 'nha-pho-dn',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Công trình nhà phố 3 tầng do Công ty Cường Huy thiết kế và thi công trọn gói tại quận Sơn Trà, Đà Nẵng. Không gian thoáng đãng, vật liệu hoàn thiện cao cấp.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                name: 'Khách Sạn Ven Biển – Mỹ Khê, Đà Nẵng',
                category: 'khach-san-dn',
                categoryLabel: 'Khách sạn - Căn hộ',
                desc: 'Dự án thi công xây dựng và hoàn thiện khách sạn gần biển Mỹ Khê, đáp ứng tiêu chuẩn lưu trú du lịch hiện đại, vận hành ổn định.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                name: 'Căn Hộ Dịch Vụ Cao Cấp – Hải Châu, Đà Nẵng',
                category: 'khach-san-dn',
                categoryLabel: 'Khách sạn - Căn hộ',
                desc: 'Tòa căn hộ cho thuê nhiều tầng tại trung tâm quận Hải Châu, tối ưu số phòng khai thác, trang bị hệ thống PCCC và điện nước đồng bộ.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                name: 'Biệt Thự 2 Mặt Tiền – Khu Đô Thị Hòa Xuân',
                category: 'biet-thu-dn',
                categoryLabel: 'Biệt thự - Homestay',
                desc: 'Biệt thự góc 2 mặt tiền sang trọng tại Hòa Xuân, Đà Nẵng với hình khối kiến trúc khỏe khoắn, sân vườn xanh mát và nội thất tinh tế.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                name: 'Nhà Phố Thương Mại – Quận Ngũ Hành Sơn',
                category: 'nha-pho-dn',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Công trình nhà phố kết hợp kinh doanh tại Ngũ Hành Sơn, thi công đúng tiến độ cam kết, mặt tiền nổi bật và bền đẹp.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                name: 'Văn Phòng Công Ty – Quận Thanh Khê, Đà Nẵng',
                category: 'van-phong-dn',
                categoryLabel: 'Văn phòng - Thương mại',
                desc: 'Thiết kế và thi công hoàn thiện trụ sở văn phòng hiện đại tại Thanh Khê, tối ưu ánh sáng, cách âm và nhận diện thương hiệu.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                name: 'Homestay & Căn Hộ Lưu Trú – Phước Mỹ, Sơn Trà',
                category: 'biet-thu-dn',
                categoryLabel: 'Biệt thự - Homestay',
                desc: 'Dự án xây dựng homestay phong cách nghỉ dưỡng gần biển Phước Mỹ, sử dụng vật liệu chống ăn mòn hơi muối biển hiệu quả.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                name: 'Nhà Phố Gia Đình – Khu Nam Việt Á, Đà Nẵng',
                category: 'nha-pho-dn',
                categoryLabel: 'Nhà phố Đà Nẵng',
                desc: 'Thi công phần thô và hoàn thiện trọn gói nhà phố gia đình tại Khu Nam Việt Á, bàn giao đúng hẹn với chất lượng hoàn thiện sắc sảo.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                name: 'Biệt Thự Sân Vườn – Khu Đô Thị Hòa Quý',
                category: 'biet-thu-dn',
                categoryLabel: 'Biệt thự - Homestay',
                desc: 'Biệt thự vườn thiết kế mở kết nối thiên nhiên tại Hòa Quý, Đà Nẵng, thi công kết cấu bền vững cùng hệ cửa nhôm kính cách âm cao cấp.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                name: 'Tòa Nhà Văn Phòng & Căn Hộ – Liên Chiểu',
                category: 'van-phong-dn',
                categoryLabel: 'Văn phòng - Thương mại',
                desc: 'Công trình đa năng kết hợp văn phòng và căn hộ dịch vụ tại quận Liên Chiểu, tối ưu chi phí đầu tư và hiệu suất vận hành lâu dài.'
            }
        ];

        /* ==================== DỮ LIỆU BÀI VIẾT TRANG CHỦ ==================== */
        const blogPosts = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật khi xây nhà',
                date: '15/11/2026',
                excerpt: 'Bảo dưỡng bê tông móng đúng thời điểm giúp tăng cường độ chịu lực, hạn chế nứt bề mặt và kéo dài tuổi thọ công trình.',
                content: 'Sau khi đổ bê tông móng khoảng 4 đến 6 tiếng, bề mặt bê tông bắt đầu ninh kết và cần được giữ ẩm liên tục trong 7 ngày đầu. Đội ngũ kỹ sư Cường Huy luôn che phủ bao bố ướt và tưới nước định kỳ theo tiêu chuẩn TCVN để bê tông đạt cường độ thiết kế cao nhất.'
            },
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Kinh nghiệm xây nhà trọn gói tại Đà Nẵng không phát sinh chi phí',
                date: '10/11/2026',
                excerpt: 'Chuẩn bị hồ sơ thiết kế chi tiết, lựa chọn chủng loại vật tư rõ ràng ngay từ đầu là chìa khóa kiểm soát ngân sách hiệu quả.',
                content: 'Để tránh phát sinh chi phí ngoài dự kiến khi xây nhà trọn gói tại Đà Nẵng, chủ đầu tư nên chốt kỹ bản vẽ công năng 2D, phối cảnh 3D và bảng phụ lục vật tư hoàn thiện trước khi khởi công. Công ty Cường Huy luôn lập bảng bóc tách khối lượng minh bạch giúp khách hàng dễ dàng kiểm soát ngân sách.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Những lưu ý chống thấm quan trọng cho nhà phố khu vực ven biển',
                date: '04/11/2026',
                excerpt: 'Khí hậu mưa bão và hơi muối biển đòi hỏi quy trình xử lý chống thấm sàn mái, tường ngoài và ban công thật bài bản.',
                content: 'Các khu vực như Sơn Trà, Ngũ Hành Sơn chịu tác động lớn từ gió bão và độ ẩm cao. Vì vậy, khâu chống thấm cổ ống, sàn vệ sinh, sân thượng và sơn lót kháng kiềm mặt ngoài cần được thi công đúng định mức và ngâm thử nước nghiệm thu tối thiểu 48 giờ.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Xu hướng thiết kế kiến trúc và nội thất nhà phố tối giản năm 2026',
                date: '28/10/2026',
                excerpt: 'Không gian mở, ưu tiên thông gió tự nhiên, giếng trời xanh mát và nội thất tinh gọn đang được nhiều gia đình Đà Nẵng ưa chuộng.',
                content: 'Kiến trúc nhà phố hiện đại tập trung vào sự thông thoáng bằng hệ giếng trời trung tâm, lam chắn nắng mặt tiền và bảng màu trung tính sang trọng. Thiết kế hợp lý không chỉ nâng tầm thẩm mỹ mà còn giúp tiết kiệm điện năng làm mát suốt mùa hè miền Trung.'
            }
        ];

        /* ==================== RENDER LƯỚI SẢN PHẨM (2 CỘT MOBILE, 3-4 CỘT DESKTOP, KHÔNG NHÃN DÁN, KHÔNG THIẾU CHỮ) ==================== */
        function renderProducts(filterCat = 'all') {
            const grid = document.getElementById('productGrid');
            const filtered = filterCat === 'all'
                ? constructionProducts
                : constructionProducts.filter(item => item.category === filterCat);

            grid.innerHTML = filtered.map((item) => `
                <article onclick="openDetailModal('${item.name.replace(/'/g, "\\'")}', '${item.categoryLabel}', '${item.id}', '${item.desc.replace(/'/g, "\\'")}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:shadow-md hover:border-brand-gold/60 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveThumb(item.id, 'w800')}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveError(this)"
                            alt="${item.name}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[10.5px] sm:text-[11px] font-semibold text-brand-gold uppercase tracking-wide mb-1">${item.categoryLabel}</div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition">
                                ${item.name}
                            </h3>
                        </div>
                        <div class="pt-1.5 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs font-semibold text-slate-600">
                            <span>Liên hệ báo giá</span>
                            <span class="text-brand-navy group-hover:text-brand-gold">Chi tiết &rarr;</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== RENDER LƯỚI DỰ ÁN ĐÀ NẴNG (2 CỘT MOBILE, 5 CỘT DESKTOP) ==================== */
        function renderDaNangProjects(filterCat = 'all') {
            const grid = document.getElementById('daNangProjectGrid');
            const filtered = filterCat === 'all'
                ? daNangProjects
                : daNangProjects.filter(item => item.category === filterCat);

            grid.innerHTML = filtered.map((item) => `
                <article onclick="openDetailModal('${item.name.replace(/'/g, "\\'")}', '${item.categoryLabel} • Đà Nẵng', '${item.id}', '${item.desc.replace(/'/g, "\\'")}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:shadow-md hover:border-brand-gold/60 transition flex flex-col">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveThumb(item.id, 'w800')}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveError(this)"
                            alt="${item.name}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-1.5">
                        <div>
                            <div class="text-[10px] sm:text-[11px] font-semibold text-brand-gold uppercase mb-1">${item.categoryLabel}</div>
                            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition">
                                ${item.name}
                            </h3>
                        </div>
                        <div class="text-[11px] text-slate-500 flex items-center gap-1 pt-1">
                            <i class="fa-solid fa-location-dot text-brand-gold text-[10px]"></i>
                            <span>TP. Đà Nẵng</span>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== RENDER BÀI VIẾT TRANG CHỦ ==================== */
        function renderBlogs() {
            const grid = document.getElementById('blogGrid');
            grid.innerHTML = blogPosts.map((post) => `
                <article onclick="openDetailModal('${post.title.replace(/'/g, "\\'")}', 'Tin tức xây dựng • ${post.date}', '${post.id}', '${post.content.replace(/'/g, "\\'")}')"
                    class="group cursor-pointer bg-white rounded-xl border border-slate-200 overflow-hidden hover:shadow-md hover:border-brand-gold/60 transition flex flex-col">
                    <div class="aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="${getDriveThumb(post.id, 'w800')}"
                            data-drive-id="${post.id}"
                            onerror="handleDriveError(this)"
                            alt="${post.title}"
                            loading="lazy"
                            class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <div class="text-[10.5px] text-slate-400 font-medium mb-1">
                                <i class="fa-regular fa-calendar mr-1 text-brand-gold"></i>${post.date}
                            </div>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy leading-snug break-words group-hover:text-brand-gold transition">
                                ${post.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 mt-1.5 leading-relaxed">${post.excerpt}</p>
                        </div>
                        <div class="text-[11px] sm:text-xs font-semibold text-brand-gold pt-1">Đọc tiếp &rarr;</div>
                    </div>
                </article>
            `).join('');
        }

        /* ==================== LỌC DANH MỤC TỪ MENU HOẶC TAB ==================== */
        function selectProductCategory(cat) {
            const tabs = document.querySelectorAll('#productCategoryTabs .cat-tab-btn');
            tabs.forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
            renderProducts(cat);
        }

        document.querySelectorAll('#productCategoryTabs .cat-tab-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                selectProductCategory(btn.getAttribute('data-cat'));
            });
        });

        document.querySelectorAll('#projectCategoryTabs .cat-tab-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('#projectCategoryTabs .cat-tab-btn').forEach(b => b.classList.remove('active'));
                btn.classList.add('active');
                renderDaNangProjects(btn.getAttribute('data-proj'));
            });
        });

        /* ==================== SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT MOBILE ==================== */
        (function initBannerSlider() {
            const track = document.getElementById('bannerTrack');
            const dots = document.querySelectorAll('.banner-dot');
            const prevBtn = document.getElementById('prevBanner');
            const nextBtn = document.getElementById('nextBanner');
            const slider = document.getElementById('heroSlider');
            let currentSlide = 0;
            const totalSlides = 2;
            let autoTimer = null;

            function goToSlide(index) {
                currentSlide = (index + totalSlides) % totalSlides;
                track.style.transform = `translateX(-${currentSlide * 100}%)`;
                dots.forEach((dot, idx) => {
                    if (idx === currentSlide) {
                        dot.classList.remove('w-2.5', 'bg-white/50');
                        dot.classList.add('w-7', 'bg-brand-gold');
                    } else {
                        dot.classList.remove('w-7', 'bg-brand-gold');
                        dot.classList.add('w-2.5', 'bg-white/50');
                    }
                });
            }

            function startAuto() {
                stopAuto();
                autoTimer = setInterval(() => goToSlide(currentSlide + 1), 5500);
            }

            function stopAuto() {
                if (autoTimer) clearInterval(autoTimer);
            }

            prevBtn.addEventListener('click', () => { goToSlide(currentSlide - 1); startAuto(); });
            nextBtn.addEventListener('click', () => { goToSlide(currentSlide + 1); startAuto(); });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    goToSlide(parseInt(dot.getAttribute('data-index'), 10));
                    startAuto();
                });
            });

            // Hỗ trợ vuốt cảm ứng trên điện thoại
            let touchStartX = 0;
            slider.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
                stopAuto();
            }, { passive: true });

            slider.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
                }
                startAuto();
            }, { passive: true });

            slider.addEventListener('mouseenter', stopAuto);
            slider.addEventListener('mouseleave', startAuto);

            startAuto();
        })();

        /* ==================== MENU MOBILE ==================== */
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
        });

        /* ==================== MODAL XEM CHI TIẾT ==================== */
        const detailModal = document.getElementById('detailModal');
        const closeModalBtn = document.getElementById('closeModalBtn');

        function openDetailModal(title, meta, driveId, desc) {
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalMeta').textContent = meta;
            const img = document.getElementById('modalImg');
            img.removeAttribute('data-err-step');
            img.setAttribute('data-drive-id', driveId);
            img.src = getDriveThumb(driveId, 'w1200');
            img.onerror = function () { handleDriveError(this); };
            img.alt = title;
            document.getElementById('modalDesc').textContent = desc;
            detailModal.classList.remove('hidden');
            detailModal.classList.add('flex');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            detailModal.classList.add('hidden');
            detailModal.classList.remove('flex');
            document.body.style.overflow = '';
        }

        closeModalBtn.addEventListener('click', closeModal);
        detailModal.addEventListener('click', (e) => {
            if (e.target === detailModal) closeModal();
        });

        /* ==================== XỬ LÝ FORM YÊU CẦU BÁO GIÁ (KHÔNG DÙNG ALERT) ==================== */
        document.getElementById('quoteForm').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const feedback = document.getElementById('quoteFeedback');

            if (!name || !phone) {
                feedback.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để kỹ sư Cường Huy liên hệ tư vấn.';
                feedback.classList.remove('hidden');
                return;
            }

            feedback.className = 'rounded-lg p-3.5 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
            feedback.innerHTML = `Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${type}</strong> đã được tiếp nhận. Kỹ sư Công ty Cường Huy sẽ liên hệ qua số <strong>${phone}</strong> trong thời gian sớm nhất.`;
            feedback.classList.remove('hidden');
            this.reset();
        });

        /* ==================== KHỞI TẠO DỮ LIỆU KHI TẢI TRANG ==================== */
        renderProducts('all');
        renderDaNangProjects('all');
        renderBlogs();
    </script>
</body>
</html>
