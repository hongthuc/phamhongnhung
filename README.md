<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH MỘT THÀNH VIÊN PHẠM HỒNG NHUNG | Máy May Công Nghiệp & Phụ Tùng Đà Nẵng - phamhongnhung.com</title>
    <meta name="description" content="Công Ty TNHH MTV Phạm Hồng Nhung (phamhongnhung.com) chuyên cung cấp máy may công nghiệp mới và cũ: Jack, Juki, Pegasus, Siruba, Brother, Hashima, Okito, Bruce, phụ tùng ngành may tại Đà Nẵng. Hotline: 0905.335.457 - 0902.833.811">
    
    <!-- Open Graph / Thumbnail là ảnh logo & thực tế công ty khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://phamhongnhung.com/">
    <meta property="og:title" content="CÔNG TY TNHH MỘT THÀNH VIÊN PHẠM HỒNG NHUNG - phamhongnhung.com">
    <meta property="og:description" content="Chuyên phân phối, sửa chữa, cho thuê máy may công nghiệp & phụ tùng chính hãng tại Đà Nẵng. Đ/c: 34 Phạm Nhữ Tăng & 34 Tôn Đức Thắng. ĐT: 0905.335.457 - 0902.833.811">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w1200">
    <link rel="icon" type="image/jpeg" href="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#0b4f8a',      /* Màu xanh công nghiệp chủ đạo theo bảng hiệu/logo */
                            dark: '#073660',      /* Xanh đậm thanh menu Flatsome */
                            light: '#eef6ff',     /* Nền xanh nhạt */
                            red: '#d91f26',       /* Đỏ điểm nhấn logo & giá giảm */
                            gold: '#f59e0b',      /* Vàng cam nổi bật */
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px',
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f4f6f9;
            color: #1e293b;
            -webkit-text-size-adjust: 100%;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .container-1500 {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-1500 {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu thanh danh mục máy tính: tên danh mục viết liền trên 1 hàng, chữ nhỏ gọn, không bị gãy dòng trong tên */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-start;
            gap: 2px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: -0.01em;
            padding: 9px 9px;
            color: #ffffff;
            transition: background-color 0.2s ease, color 0.2s ease;
            border-radius: 4px;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            line-height: 1.2;
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            background-color: #d91f26;
            color: #ffffff;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown-parent {
            position: relative;
        }
        .nav-dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            border-top: 3px solid #d91f26;
            border-radius: 0 0 6px 6px;
            z-index: 100;
            padding: 6px 0;
        }
        .nav-dropdown-parent:hover .nav-dropdown-menu {
            display: block;
        }
        .nav-dropdown-menu a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .nav-dropdown-menu a:last-child {
            border-bottom: none;
        }
        .nav-dropdown-menu a:hover {
            background-color: #eef6ff;
            color: #0b4f8a;
            padding-left: 18px;
        }

        /* 2 Banner tự trượt kích thước bằng nhau tuyệt đối, tối ưu chữ trên điện thoại không tràn viền */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            height: 215px;
            overflow: hidden;
            border-radius: 8px;
            background: #073660;
        }
        @media (min-width: 640px) {
            .hero-slider-wrapper {
                height: 290px;
            }
        }
        @media (min-width: 1024px) {
            .hero-slider-wrapper {
                height: 380px;
            }
        }
        .hero-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.6s ease-in-out, visibility 0.6s ease-in-out;
        }
        .hero-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 15;
            width: 40px;
            height: 40px;
            border-radius: 9999px;
            background-color: #d91f26;
            color: #ffffff;
            font-weight: 800;
            font-size: 11.5px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 31, 38, 0.35);
            line-height: 1;
            pointer-events: none;
        }
        @media (min-width: 768px) {
            .flatsome-sale-badge {
                width: 44px;
                height: 44px;
                font-size: 12.5px;
            }
        }

        /* Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ (...) hay tràn viền */
        .product-title-full {
            display: block;
            width: 100%;
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Tiêu đề Section kiểu Flatsome */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0b4f8a;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
            overflow: hidden;
        }
        .flatsome-title-tab {
            background: linear-gradient(135deg, #0b4f8a 0%, #073660 100%);
            color: #ffffff;
            padding: 10px 16px;
            font-weight: 800;
            font-size: 13.5px;
            text-transform: uppercase;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            position: relative;
        }
        @media (min-width: 768px) {
            .flatsome-title-tab {
                font-size: 15px;
                padding: 11px 22px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(217, 31, 38, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 31, 38, 0); }
            100% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(217, 31, 38, 0); }
        }
        .floating-pulse-red {
            animation: pulse-ring 2s infinite;
        }
        @keyframes pulse-blue {
            0% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(11, 79, 138, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(11, 79, 138, 0); }
            100% { transform: scale(0.92); box-shadow: 0 0 0 0 rgba(11, 79, 138, 0); }
        }
        .floating-pulse-blue {
            animation: pulse-blue 2.2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         TOP BAR CHUẨN FLATSOME (KHÔNG CÓ THANH UXBUILDER)
         ========================================== -->
    <div class="bg-brand-dark text-white text-xs border-b border-blue-900">
        <div class="container-1500 py-1.5 flex flex-col sm:flex-row items-center justify-between gap-1">
            <div class="flex flex-wrap items-center justify-center sm:justify-start gap-x-4 gap-y-1 text-[11.5px]">
                <span class="font-semibold text-amber-300">
                    <i class="fa-solid fa-building mr-1"></i>CÔNG TY TNHH MTV PHẠM HỒNG NHUNG (phamhongnhung.com)
                </span>
                <span class="hidden xl:inline text-blue-200">|</span>
                <span class="text-blue-100">
                    <i class="fa-solid fa-location-dot text-red-400 mr-1"></i>Trụ sở: 34 Phạm Nhữ Tăng, P. Thanh Khê, TP. Đà Nẵng
                </span>
                <span class="hidden lg:inline text-blue-200">|</span>
                <span class="text-blue-100">
                    <i class="fa-solid fa-store text-amber-400 mr-1"></i>VP: 34 Tôn Đức Thắng, P. Hòa Khánh, TP. Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-3 text-[11.5px]">
                <a href="https://maps.app.goo.gl/agFRWwZTB3tXkSYQ7" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition flex items-center gap-1">
                    <i class="fa-solid fa-map-location-dot text-emerald-400"></i> Bản đồ chỉ đường
                </a>
                <span class="text-blue-300">|</span>
                <a href="https://www.facebook.com/ton.danh.1460" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 transition flex items-center gap-1">
                    <i class="fa-brands fa-facebook text-sky-400"></i> Fanpage Facebook
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (LOGO GỌN NHỎ, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ========================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40">
        <div class="container-1500 py-2.5">
            <div class="flex items-center justify-between gap-2 md:gap-5">
                
                <!-- Nút mở menu trên điện thoại -->
                <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden flex items-center justify-center w-9 h-9 rounded bg-brand-blue text-white shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- LOGO MỚI CHUYÊN NGHIỆP CHỈNH GỌN NHỎ LẠI DỰA VÀO ẢNH THỰC TẾ CÔNG TY -->
                <a href="#top" class="flex items-center gap-2.5 shrink-0 group max-w-[78%] sm:max-w-none">
                    <div class="relative w-11 h-11 sm:w-12 sm:h-12 rounded-lg overflow-hidden border-2 border-brand-blue shadow-sm shrink-0 bg-white flex items-center justify-center">
                        <!-- Ảnh logo / thực tế công ty thu gọn kết hợp biểu tượng PHN -->
                        <img 
                            src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w300" 
                            alt="Logo Công Ty TNHH MTV Phạm Hồng Nhung"
                            class="w-full h-full object-cover"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF=w300';"
                        >
                        <span class="absolute bottom-0 inset-x-0 bg-brand-red text-white text-[8px] font-extrabold text-center leading-tight py-0.5 tracking-wider">PHN</span>
                    </div>
                    <div class="leading-tight min-w-0">
                        <div class="text-[10px] sm:text-[11px] font-bold text-brand-red uppercase tracking-tight truncate">
                            CÔNG TY TNHH MTV
                        </div>
                        <div class="text-sm sm:text-base md:text-lg font-extrabold text-brand-blue tracking-tight truncate">
                            PHẠM HỒNG NHUNG
                        </div>
                        <div class="text-[10px] text-slate-500 font-medium truncate">
                            phamhongnhung.com • Máy May & Phụ Tùng
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm ở giữa (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-2">
                    <form id="desktopSearchForm" class="w-full flex rounded-md overflow-hidden border-2 border-brand-blue bg-white">
                        <select id="searchCategorySelect" aria-label="Chọn danh mục" class="bg-slate-50 text-slate-700 text-xs font-semibold px-2.5 border-r border-slate-200 focus:outline-none">
                            <option value="all">Tất cả danh mục</option>
                            <option value="jack">Máy May JACK</option>
                            <option value="juki">Máy May JUKI</option>
                            <option value="pegasus">Máy May PEGASUS</option>
                            <option value="siruba">Máy May SIRUBA</option>
                            <option value="brother">Máy May BROTHER</option>
                            <option value="hashima">Máy Cắt HASHIMA</option>
                            <option value="okito">Máy May OKITO - BRUCE</option>
                            <option value="may-cu">Máy May Cũ & Phụ Tùng</option>
                        </select>
                        <input 
                            id="searchInput" 
                            type="text" 
                            placeholder="Tìm máy 1 kim, vắt sổ, trần đè, máy cắt, phụ tùng..." 
                            class="w-full px-3 py-2 text-xs text-slate-800 focus:outline-none"
                        >
                        <button type="submit" class="bg-brand-blue hover:bg-brand-red text-white px-4 text-xs font-bold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>
                </div>

                <!-- Cam kết dịch vụ kiểu maymaydanang.com (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="hidden xl:flex items-center gap-4 shrink-0">
                    <div class="flex items-center gap-2">
                        <div class="w-8 h-8 rounded-full bg-blue-50 text-brand-blue flex items-center justify-center text-sm shrink-0">
                            <i class="fa-solid fa-truck-fast"></i>
                        </div>
                        <div class="text-[11px] leading-tight">
                            <div class="font-bold text-slate-800">GIAO HÀNG TẬN NƠI</div>
                            <div class="text-slate-500">Đà Nẵng & Toàn Quốc</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-2">
                        <div class="w-8 h-8 rounded-full bg-red-50 text-brand-red flex items-center justify-center text-sm shrink-0">
                            <i class="fa-solid fa-shield-halved"></i>
                        </div>
                        <div class="text-[11px] leading-tight">
                            <div class="font-bold text-slate-800">BẢO HÀNH UY TÍN</div>
                            <div class="text-slate-500">Hỗ trợ kỹ thuật 24/7</div>
                        </div>
                    </div>
                </div>

                <!-- Nút nhảy tới Form Báo Giá nhỏ gọn trên mobile/tablet -->
                <a href="#bao-gia" class="lg:hidden bg-brand-light border border-brand-blue/30 text-brand-blue text-[11px] font-bold px-2.5 py-1.5 rounded shrink-0">
                    Báo giá
                </a>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="mt-2 md:hidden">
                <form id="mobileSearchForm" class="flex w-full rounded border border-brand-blue overflow-hidden bg-white">
                    <input 
                        id="mobileSearchInput" 
                        type="text" 
                        placeholder="Tìm kiếm máy may Jack, Juki, Pegasus, phụ tùng..." 
                        class="w-full px-3 py-1.5 text-xs focus:outline-none"
                    >
                    <button type="submit" aria-label="Tìm kiếm" class="bg-brand-blue text-white px-3 text-xs font-bold shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </form>
            </div>
        </div>

        <!-- ==========================================
             THANH MENU DANH MỤC TRÊN MÁY TÍNH
             (Tên danh mục viết liền trên 1 hàng chữ nhỏ lại, nằm trên 1 hàng hoặc xuống hàng 2, không gãy tên danh mục)
             ========================================== -->
        <nav class="hidden lg:block bg-brand-blue border-t border-blue-800 shadow-inner">
            <div class="container-1500 py-1">
                <ul class="desktop-nav-list">
                    <li>
                        <a href="#top" class="desktop-nav-item active">
                            <i class="fa-solid fa-house text-[11px]"></i> TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="desktop-nav-item">GIỚI THIỆU</a>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-okito" class="desktop-nav-item">
                            BRUCE <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-okito">Máy 1 kim BRUCE</a>
                            <a href="#sec-okito">Máy vắt sổ BRUCE</a>
                            <a href="#sec-okito">Máy chuyên dụng BRUCE</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-jack" class="desktop-nav-item">
                            JACK <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-jack">Máy May 1 Kim Jack</a>
                            <a href="#sec-jack">Máy Vắt Sổ Jack</a>
                            <a href="#sec-jack">Máy Trần Đè Jack</a>
                            <a href="#sec-jack">Máy Chuyên Dùng Jack</a>
                            <a href="#sec-jack">Motor Tiết Kiệm Điện Jack</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-juki" class="desktop-nav-item">
                            JUKI <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-juki">Máy 1 kim điện tử Juki</a>
                            <a href="#sec-juki">Máy 2 kim Juki</a>
                            <a href="#sec-juki">Máy thùa khuy & đính bọ Juki</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-pegasus" class="desktop-nav-item">
                            PEGASUS <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-pegasus">Máy chuyên dụng Pegasus</a>
                            <a href="#sec-pegasus">Máy trần đè Pegasus</a>
                            <a href="#sec-pegasus">Máy tự động Pegasus</a>
                            <a href="#sec-pegasus">Máy vắt sổ Pegasus</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-siruba" class="desktop-nav-item">
                            SIRUBA <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-siruba">Máy một kim Siruba</a>
                            <a href="#sec-siruba">Máy hai kim Siruba</a>
                            <a href="#sec-siruba">Máy khuy, bọ, nút Siruba</a>
                            <a href="#sec-siruba">Máy móc xích & trần đè Siruba</a>
                            <a href="#sec-siruba">Máy vắt sổ Siruba</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-brother" class="desktop-nav-item">
                            BROTHER <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-brother">Máy một kim Brother</a>
                            <a href="#sec-brother">Máy hai kim Brother</a>
                            <a href="#sec-brother">Máy cuốn sườn & đính bọ</a>
                            <a href="#sec-brother">Máy lập trình điện tử Brother</a>
                            <a href="#sec-brother">Máy thùa khuy Brother</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-hashima" class="desktop-nav-item">
                            MÁY CÔNG NGHIỆP HÓA <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-hashima">Máy cắt vải Hashima</a>
                            <a href="#sec-hashima">Máy cắt vòng Hashima</a>
                            <a href="#sec-hashima">Máy dò kim Hashima</a>
                            <a href="#sec-hashima">Máy in sơ đồ & cắt rập</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-okito" class="desktop-nav-item">
                            OKITO <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-okito">Máy May Okito</a>
                            <a href="#sec-okito">Máy Vắt Sổ Okito</a>
                            <a href="#sec-okito">Máy Trần Đè Okito</a>
                            <a href="#sec-okito">Máy Ép Mếch & Nồi Hơi</a>
                        </div>
                    </li>
                    <li class="nav-dropdown-parent">
                        <a href="#sec-may-cu" class="desktop-nav-item">
                            MÁY MAY CŨ <i class="fa-solid fa-angle-down text-[10px]"></i>
                        </a>
                        <div class="nav-dropdown-menu">
                            <a href="#sec-may-cu">Máy may cũ Jack, Juki</a>
                            <a href="#sec-may-cu">Máy may cũ Siruba, Brother</a>
                            <a href="#sec-may-cu">Máy may cũ Okito, Britex</a>
                        </div>
                    </li>
                    <li>
                        <a href="#sec-may-cu" class="desktop-nav-item">THIẾT BỊ PHỤ TÙNG</a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="desktop-nav-item">THU MUA - CHO THUÊ MÁY</a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="desktop-nav-item">TIN TỨC</a>
                    </li>
                    <li>
                        <a href="#lien-he-map" class="desktop-nav-item">LIÊN HỆ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh cuộn nhanh danh mục trên Điện Thoại (nhỏ gọn, không tràn viền) -->
        <div class="lg:hidden bg-brand-blue text-white border-t border-blue-800">
            <div class="container-1500 py-1.5 flex items-center gap-1.5 overflow-x-auto no-scrollbar text-[11px] font-bold">
                <a href="#danh-muc-trang-chu" class="whitespace-nowrap px-2.5 py-1 rounded bg-brand-red text-white shrink-0">Danh mục</a>
                <a href="#sec-jack" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">JACK</a>
                <a href="#sec-juki" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">JUKI</a>
                <a href="#sec-pegasus" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">PEGASUS</a>
                <a href="#sec-siruba" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">SIRUBA</a>
                <a href="#sec-brother" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">BROTHER</a>
                <a href="#sec-hashima" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">HASHIMA</a>
                <a href="#sec-okito" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">OKITO</a>
                <a href="#sec-may-cu" class="whitespace-nowrap px-2.5 py-1 rounded bg-white/10 hover:bg-white/20 shrink-0">MÁY CŨ & PHỤ TÙNG</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         DRAWER MENU DANH MỤC ĐIỆN THOẠI
         ========================================== -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div id="mobileDrawerBackdrop" class="absolute inset-0 bg-slate-900/60"></div>
        <div class="relative w-72 max-w-[82vw] h-full bg-white shadow-2xl flex flex-col z-10 overflow-y-auto">
            <div class="p-3.5 bg-brand-blue text-white flex items-center justify-between">
                <div class="font-extrabold text-xs uppercase tracking-wide">DANH MỤC PHẠM HỒNG NHUNG</div>
                <button id="closeMobileMenuBtn" type="button" class="w-7 h-7 rounded bg-white/15 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
                <a href="#top" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50 text-brand-blue font-bold"><i class="fa-solid fa-house w-5"></i> Trang chủ</a>
                <a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-building w-5 text-brand-blue"></i> Giới thiệu công ty</a>
                <a href="#sec-jack" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May JACK</a>
                <a href="#sec-juki" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May JUKI</a>
                <a href="#sec-pegasus" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May PEGASUS</a>
                <a href="#sec-siruba" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May SIRUBA</a>
                <a href="#sec-brother" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May BROTHER</a>
                <a href="#sec-hashima" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-scissors w-5 text-brand-blue"></i> Máy Cắt & Công Nghiệp Hóa HASHIMA</a>
                <a href="#sec-okito" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-gears w-5 text-brand-blue"></i> Máy May OKITO & BRUCE</a>
                <a href="#sec-may-cu" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-screwdriver-wrench w-5 text-brand-blue"></i> Máy May Cũ & Thiết Bị Phụ Tùng</a>
                <a href="#bao-gia" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-file-invoice-dollar w-5 text-brand-red"></i> Thu Mua - Cho Thuê & Báo Giá</a>
                <a href="#doi-tac" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-handshake w-5 text-brand-blue"></i> Đối tác thương hiệu</a>
                <a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-newspaper w-5 text-brand-blue"></i> Tin tức ngành may</a>
                <a href="#lien-he-map" class="mobile-nav-link block px-4 py-3 hover:bg-blue-50"><i class="fa-solid fa-map-location-dot w-5 text-brand-red"></i> Bản đồ & Fanpage</a>
            </div>
            <div class="mt-auto p-3.5 bg-slate-50 border-t border-slate-200 text-[11px] space-y-1.5 text-slate-600">
                <div class="font-bold text-brand-blue">HOTLINE HỖ TRỢ 24/7:</div>
                <div><i class="fa-solid fa-phone text-brand-red mr-1.5"></i><a href="tel:0905335457" class="font-bold text-slate-800">0905.335.457</a></div>
                <div><i class="fa-solid fa-phone text-brand-red mr-1.5"></i><a href="tel:0902833811" class="font-bold text-slate-800">0902.833.811</a></div>
                <div><i class="fa-solid fa-location-dot text-brand-blue mr-1.5"></i>34 Phạm Nhữ Tăng, Thanh Khê, Đà Nẵng</div>
                <div><i class="fa-solid fa-store text-brand-blue mr-1.5"></i>34 Tôn Đức Thắng, Hòa Khánh, Đà Nẵng</div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         MAIN CONTENT (CHUẨN KHUNG 1500PX FLATSOME)
         ========================================== -->
    <main id="top" class="container-1500 py-3 sm:py-5 space-y-6">

        <!-- 1. 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             (Chữ nhỏ gọn nằm hết trong ảnh banner, không tràn viền trên điện thoại) -->
        <section aria-label="Banner chính">
            <div class="hero-slider-wrapper shadow-md border border-slate-200">
                
                <!-- SLIDE 1 -->
                <div class="hero-slide active" data-slide="0">
                    <div class="w-full h-full grid grid-cols-12 bg-gradient-to-r from-[#062c50] via-[#0b4f8a] to-[#1264ac] text-white relative overflow-hidden">
                        <!-- Phần chữ bên trái: được chỉnh nhỏ gọn để nằm trọn trong ảnh trên cả điện thoại -->
                        <div class="col-span-7 sm:col-span-7 flex flex-col justify-center pl-3.5 pr-2 py-3 sm:p-6 lg:p-10 z-10">
                            <div class="inline-block bg-amber-400 text-slate-900 font-extrabold text-[9px] sm:text-xs px-2 py-0.5 rounded w-fit mb-1 sm:mb-2 uppercase tracking-wide">
                                UY TÍN TẠI ĐÀ NẴNG • PHAMHONGNHUNG.COM
                            </div>
                            <h1 class="text-[12.5px] sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug sm:leading-tight uppercase tracking-tight text-white">
                                CÔNG TY TNHH MTV PHẠM HỒNG NHUNG
                            </h1>
                            <p class="text-[10px] sm:text-xs md:text-sm text-blue-100 mt-1 sm:mt-2 leading-snug">
                                Chuyên phân phối Máy May Công Nghiệp Mới & Cũ: Jack, Juki, Pegasus, Siruba, Brother, Hashima, Okito & Phụ Tùng Chính Hãng.
                            </p>
                            <div class="mt-1.5 sm:mt-3 pt-1.5 sm:pt-2 border-t border-white/20 text-[9.5px] sm:text-xs text-amber-200 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-location-dot mr-1"></i>Đ/c: 34 Phạm Nhữ Tăng - VP: 34 Tôn Đức Thắng, Đà Nẵng</div>
                                <div class="font-bold text-white"><i class="fa-solid fa-phone-volume mr-1 text-amber-300"></i>ĐT: 0905.335.457 - 0902.833.811</div>
                            </div>
                        </div>
                        <!-- Phần hình ảnh thực tế bên phải -->
                        <div class="col-span-5 sm:col-span-5 relative h-full flex items-center justify-center p-2 sm:p-4 bg-white/5">
                            <div class="w-full h-[86%] rounded-lg overflow-hidden border border-white/30 shadow-lg bg-white flex items-center justify-center">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w1000" 
                                    alt="Cửa hàng Công Ty TNHH MTV Phạm Hồng Nhung" 
                                    class="w-full h-full object-cover"
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF=w1000';"
                                >
                            </div>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau tuyệt đối với Slide 1) -->
                <div class="hero-slide" data-slide="1">
                    <div class="w-full h-full grid grid-cols-12 bg-gradient-to-r from-[#7f1116] via-[#b91c1c] to-[#0b4f8a] text-white relative overflow-hidden">
                        <!-- Phần chữ bên trái nhỏ gọn nằm hết trong ảnh banner -->
                        <div class="col-span-7 sm:col-span-7 flex flex-col justify-center pl-3.5 pr-2 py-3 sm:p-6 lg:p-10 z-10">
                            <div class="inline-block bg-white text-brand-red font-extrabold text-[9px] sm:text-xs px-2 py-0.5 rounded w-fit mb-1 sm:mb-2 uppercase tracking-wide">
                                GIẢI PHÁP TOÀN DIỆN CHO XƯỞNG MAY
                            </div>
                            <h2 class="text-[12.5px] sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug sm:leading-tight uppercase tracking-tight text-white">
                                MUA BÁN - CHO THUÊ - THU MUA MÁY MAY
                            </h2>
                            <p class="text-[10px] sm:text-xs md:text-sm text-red-100 mt-1 sm:mt-2 leading-snug">
                                Cung cấp trọn gói máy 1 kim điện tử, máy vắt sổ, trần đè, thùa khuy, đính bọ, máy cắt vải, bàn ủi hơi nước & linh kiện ngành may.
                            </p>
                            <div class="mt-1.5 sm:mt-3 pt-1.5 sm:pt-2 border-t border-white/20 text-[9.5px] sm:text-xs text-amber-200 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-check-circle mr-1"></i>Bảo hành dài hạn • Đổi trả nhanh chóng • Giao tận xưởng</div>
                                <div class="font-bold text-white"><i class="fa-solid fa-headset mr-1 text-amber-300"></i>Tư vấn báo giá: 0905.335.457 - 0902.833.811</div>
                            </div>
                        </div>
                        <!-- Phần hình ảnh sản phẩm thực tế bên phải -->
                        <div class="col-span-5 sm:col-span-5 relative h-full flex items-center justify-center p-2 sm:p-4 bg-white/5">
                            <div class="w-full h-[86%] rounded-lg overflow-hidden border border-white/30 shadow-lg bg-white grid grid-cols-2 gap-1 p-1">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC&sz=w600" 
                                    alt="Máy may công nghiệp thực tế 1" 
                                    class="w-full h-full object-cover rounded"
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC=w600';"
                                >
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-&sz=w600" 
                                    alt="Máy may công nghiệp thực tế 2" 
                                    class="w-full h-full object-cover rounded"
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-=w600';"
                                >
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng 2 Banner -->
                <button id="prevSlideBtn" type="button" aria-label="Banner trước" class="absolute left-1.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs transition">
                    <i class="fa-solid fa-chevron-left"></i>
                </button>
                <button id="nextSlideBtn" type="button" aria-label="Banner tiếp" class="absolute right-1.5 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs transition">
                    <i class="fa-solid fa-chevron-right"></i>
                </button>

                <!-- Chấm chỉ báo Banner -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" data-goto="0" aria-label="Banner 1" class="slider-dot w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" data-goto="1" aria-label="Banner 2" class="slider-dot w-2 h-1.5 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- 2. DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ danh mục nhỏ gọn, đẹp trên máy tính & điện thoại, giống web mẫu) -->
        <section id="danh-muc-trang-chu" class="bg-white rounded-lg shadow-sm border border-slate-200 p-3 sm:p-4">
            <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                <h2 class="text-xs sm:text-sm font-extrabold text-brand-blue uppercase flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-brand-red"></i> DANH MỤC SẢN PHẨM
                </h2>
                <span class="text-[11px] text-slate-500">Chọn nhanh danh mục máy may chính hãng</span>
            </div>

            <div class="grid grid-cols-4 sm:grid-cols-4 md:grid-cols-8 gap-2 sm:gap-3">
                <!-- Danh mục 1: JACK -->
                <a href="#sec-jack" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC&sz=w300" alt="Jack" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Jack</span>
                </a>

                <!-- Danh mục 2: JUKI -->
                <a href="#sec-juki" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=16oOareb_FSIDc9G_2sdST1yaNgNxCDtP&sz=w300" alt="Juki" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Juki</span>
                </a>

                <!-- Danh mục 3: PEGASUS -->
                <a href="#sec-pegasus" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1PpwtKs1KcQISvwRgJNpQYpy3qyrhGTv6&sz=w300" alt="Pegasus" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Pegasus</span>
                </a>

                <!-- Danh mục 4: SIRUBA -->
                <a href="#sec-siruba" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=19DdgAGKvkgI4qsqoNIpyofSMQyvoIH2z&sz=w300" alt="Siruba" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Siruba</span>
                </a>

                <!-- Danh mục 5: BROTHER -->
                <a href="#sec-brother" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1MFpuEq0z7fZ2R_pZlJqEcoGV_I1N1Nl9&sz=w300" alt="Brother" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Brother</span>
                </a>

                <!-- Danh mục 6: HASHIMA -->
                <a href="#sec-hashima" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1O2ZcR5igNhksNwuHm2LdmyAbA323L9bo&sz=w300" alt="Hashima" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Hashima</span>
                </a>

                <!-- Danh mục 7: OKITO & BRUCE -->
                <a href="#sec-okito" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1mXSI6rR8cfsnmDj6Ms3pK-20pmYGMM1D&sz=w300" alt="Okito" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Okito - Bruce</span>
                </a>

                <!-- Danh mục 8: MÁY MAY CŨ -->
                <a href="#sec-may-cu" class="group flex flex-col items-center p-2 rounded-lg border border-slate-200 hover:border-brand-blue hover:bg-blue-50/40 transition text-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-md overflow-hidden bg-slate-50 border border-slate-100 mb-1.5 flex items-center justify-center">
                        <img src="https://drive.google.com/thumbnail?id=1DjTJ8QgGVTf-QcV6FKQ3vcxjbb1pBIoX&sz=w300" alt="Máy may cũ" class="w-full h-full object-cover group-hover:scale-105 transition">
                    </div>
                    <span class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-brand-blue whitespace-nowrap">Máy may cũ</span>
                </a>
            </div>
        </section>

        <!-- ==========================================
             3. DANH SÁCH SẢN PHẨM THỰC TẾ THEO DANH MỤC WEB MẪU
             (Chia 2 cột trên điện thoại, 4 cột trên máy tính, có % giảm giá góc trên bên trái chuẩn Flatsome, không để nhãn dán thừa, tên sản phẩm không bị cắt chữ)
             ========================================== -->
        <div id="productSectionsContainer" class="space-y-6">
            <!-- Được render tự động bằng JavaScript từ dữ liệu 12 ảnh sản phẩm thực tế Google Drive phân vào đúng danh mục -->
        </div>

        <!-- ==========================================
             4. GIỚI THIỆU THỰC TẾ CÔNG TY TNHH MTV PHẠM HỒNG NHUNG
             (Sử dụng ảnh thực tế công ty từ Google Drive 15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF)
             ========================================== -->
        <section id="gioi-thieu" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
            <div class="flatsome-section-title">
                <div class="flatsome-title-tab">
                    <i class="fa-solid fa-building-shield"></i> VỀ CÔNG TY TNHH MTV PHẠM HỒNG NHUNG
                </div>
                <span class="text-xs text-slate-500 pr-4 hidden sm:inline">MST: 0401558881 • Uy tín hàng đầu tại Đà Nẵng</span>
            </div>

            <div class="p-4 sm:p-6 grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                <!-- Ảnh thực tế công ty từ file Google Drive -->
                <div class="lg:col-span-5">
                    <div class="rounded-lg overflow-hidden border-2 border-brand-blue/20 shadow-sm bg-slate-100">
                        <img 
                            src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w1000" 
                            alt="Hình ảnh thực tế Công Ty TNHH MTV Phạm Hồng Nhung tại Đà Nẵng" 
                            class="w-full h-64 sm:h-80 object-cover"
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF=w1000';"
                        >
                    </div>
                    <p class="text-[11.5px] text-center text-slate-500 mt-2">
                        Hình ảnh thực tế Công Ty TNHH Một Thành Viên Phạm Hồng Nhung tại TP. Đà Nẵng
                    </p>
                </div>

                <!-- Nội dung giới thiệu chi tiết -->
                <div class="lg:col-span-7 space-y-3 text-xs sm:text-sm text-slate-700 leading-relaxed">
                    <h3 class="text-base sm:text-xl font-extrabold text-brand-blue uppercase">
                        CÔNG TY TNHH MỘT THÀNH VIÊN PHẠM HỒNG NHUNG
                    </h3>
                    <p>
                        <strong>Công Ty TNHH Một Thành Viên Phạm Hồng Nhung</strong> (<span class="text-brand-blue font-semibold">phamhongnhung.com</span>) là đơn vị uy tín lâu năm tại TP. Đà Nẵng và khu vực Miền Trung chuyên nhập khẩu, phân phối sỉ & lẻ các dòng <strong>máy may công nghiệp, máy chuyên dùng, thiết bị cắt ủi công nghiệp hóa và phụ tùng ngành may mặc</strong>.
                    </p>
                    <p>
                        Chúng tôi phân phối đầy đủ các thương hiệu nổi tiếng thế giới như: <strong>Juki, Jack, Pegasus, Siruba, Brother, Hashima, Okito, Bruce, Britex, Yamato...</strong> từ máy mới 100% nguyên thùng đến máy may cũ chất lượng cao được tuyển chọn và kiểm định kỹ thuật nghiêm ngặt.
                    </p>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-2">
                        <div class="p-3 rounded-lg bg-brand-light border border-blue-200">
                            <div class="font-bold text-brand-blue text-xs uppercase mb-1">
                                <i class="fa-solid fa-location-dot text-brand-red mr-1"></i> Địa chỉ Trụ sở chính
                            </div>
                            <div class="text-xs text-slate-800 font-medium">34 Phạm Nhữ Tăng, Phường Thanh Khê, Tp. Đà Nẵng</div>
                        </div>
                        <div class="p-3 rounded-lg bg-brand-light border border-blue-200">
                            <div class="font-bold text-brand-blue text-xs uppercase mb-1">
                                <i class="fa-solid fa-store text-brand-red mr-1"></i> Văn phòng & Cửa hàng trưng bày
                            </div>
                            <div class="text-xs text-slate-800 font-medium">34 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 pt-2 text-center">
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                            <div class="text-brand-red font-extrabold text-sm sm:text-base">100%</div>
                            <div class="text-[11px] text-slate-600">Linh kiện chuẩn hãng</div>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                            <div class="text-brand-blue font-extrabold text-sm sm:text-base">12 Tháng</div>
                            <div class="text-[11px] text-slate-600">Bảo hành máy mới</div>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                            <div class="text-brand-red font-extrabold text-sm sm:text-base">1 Đổi 1</div>
                            <div class="text-[11px] text-slate-600">Nếu lỗi kỹ thuật</div>
                        </div>
                        <div class="p-2.5 rounded bg-slate-50 border border-slate-200">
                            <div class="text-brand-blue font-extrabold text-sm sm:text-base">24/7</div>
                            <div class="text-[11px] text-slate-600">Sửa chữa tận xưởng</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ==========================================
             5. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ
             ========================================== -->
        <section id="bao-gia" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
            <div class="flatsome-section-title">
                <div class="flatsome-title-tab">
                    <i class="fa-solid fa-file-signature"></i> GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH
                </div>
                <span class="text-xs text-slate-500 pr-4 hidden sm:inline">Phản hồi báo giá sỉ & lẻ trong 5 phút</span>
            </div>

            <div class="p-4 sm:p-6 grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                <!-- Cột thông tin hỗ trợ báo giá -->
                <div class="lg:col-span-5 bg-gradient-to-br from-brand-blue to-brand-dark text-white rounded-lg p-4 sm:p-5 space-y-3.5">
                    <h3 class="text-sm sm:text-base font-extrabold uppercase text-amber-300">
                        NHẬN BÁO GIÁ ƯU ĐÃI TỐT NHẤT TẠI ĐÀ NẴNG
                    </h3>
                    <p class="text-xs text-blue-100 leading-relaxed">
                        Quý khách hàng, xưởng may, tổ hợp may cần báo giá máy may công nghiệp mới/cũ, mua sỉ phụ tùng, thuê máy may hoặc thanh lý máy xưởng vui lòng điền thông tin bên cạnh hoặc liên hệ trực tiếp:
                    </p>
                    <div class="space-y-2.5 text-xs pt-1">
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-phone-volume text-amber-300 mt-0.5"></i>
                            <div>
                                <div class="text-blue-200">Hotline Kinh Doanh & Kỹ Thuật:</div>
                                <div class="font-extrabold text-sm text-white">0905.335.457 - 0902.833.811</div>
                            </div>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-amber-300 mt-0.5"></i>
                            <div>
                                <div class="text-blue-200">Địa chỉ Trụ sở:</div>
                                <div class="font-semibold">34 Phạm Nhữ Tăng, Phường Thanh Khê, Tp. Đà Nẵng</div>
                            </div>
                        </div>
                        <div class="flex items-start gap-2.5">
                            <i class="fa-solid fa-building text-amber-300 mt-0.5"></i>
                            <div>
                                <div class="text-blue-200">Văn phòng / Cửa hàng:</div>
                                <div class="font-semibold">34 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Form nhập yêu cầu và báo giá -->
                <div class="lg:col-span-7">
                    <form id="quoteRequestForm" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label for="quoteName" class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng / Xưởng may *</label>
                                <input id="quoteName" type="text" required placeholder="Nhập họ và tên của bạn..." class="w-full px-3 py-2 text-xs rounded border border-slate-300 focus:border-brand-blue focus:outline-none">
                            </div>
                            <div>
                                <label for="quotePhone" class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại liên hệ (Zalo) *</label>
                                <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0905335457" class="w-full px-3 py-2 text-xs rounded border border-slate-300 focus:border-brand-blue focus:outline-none">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label for="quoteCategory" class="block text-xs font-bold text-slate-700 mb-1">Danh mục sản phẩm / Dịch vụ cần báo giá</label>
                                <select id="quoteCategory" class="w-full px-3 py-2 text-xs rounded border border-slate-300 focus:border-brand-blue focus:outline-none bg-white">
                                    <option value="Máy May Công Nghiệp Mới (Jack, Juki, Pegasus, Siruba, Brother...)">Máy May Công Nghiệp Mới (Jack, Juki, Pegasus, Siruba...)</option>
                                    <option value="Máy May Công Nghiệp Cũ Tuyển Chọn">Máy May Công Nghiệp Cũ Tuyển Chọn</option>
                                    <option value="Máy Cắt Vải, Nồi Hơi, Bàn Hút, Ép Mếch">Máy Cắt Vải, Nồi Hơi, Bàn Hút, Ép Mếch</option>
                                    <option value="Thiết Bị & Phụ Tùng Ngành May">Thiết Bị & Phụ Tùng Ngành May</option>
                                    <option value="Thuê Máy May / Thanh Lý Thu Mua Nhà Xưởng">Thuê Máy May / Thanh Lý Thu Mua Nhà Xưởng</option>
                                </select>
                            </div>
                            <div>
                                <label for="quoteProduct" class="block text-xs font-bold text-slate-700 mb-1">Tên máy hoặc số lượng dự kiến</label>
                                <input id="quoteProduct" type="text" placeholder="Ví dụ: 5 máy 1 kim Jack + 2 máy vắt sổ Pegasus" class="w-full px-3 py-2 text-xs rounded border border-slate-300 focus:border-brand-blue focus:outline-none">
                            </div>
                        </div>

                        <div>
                            <label for="quoteNote" class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
                            <textarea id="quoteNote" rows="3" placeholder="Ghi rõ dòng máy, địa chỉ giao hàng hoặc yêu cầu tư vấn kỹ thuật..." class="w-full px-3 py-2 text-xs rounded border border-slate-300 focus:border-brand-blue focus:outline-none"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                            <button type="submit" class="bg-brand-red hover:bg-red-700 text-white font-extrabold text-xs sm:text-sm px-6 py-2.5 rounded shadow transition flex items-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i> GỬI YÊU CẦU BÁO GIÁ
                            </button>
                            <span class="text-[11px] text-slate-500">
                                Hoặc kết nối Zalo nhanh: <a href="https://zalo.me/0905335457" target="_blank" rel="noopener noreferrer" class="text-brand-blue font-bold underline">0905.335.457</a>
                            </span>
                        </div>

                        <!-- Hộp thông báo gửi thành công (Không dùng alert) -->
                        <div id="quoteSuccessBox" class="hidden p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                    </form>
                </div>
            </div>
        </section>

        <!-- ==========================================
             6. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC NGÀNH MAY)
             ========================================== -->
        <section id="tin-tuc" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
            <div class="flatsome-section-title flex-wrap gap-2">
                <div class="flatsome-title-tab">
                    <i class="fa-solid fa-newspaper"></i> DANH MỤC BÀI VIẾT & TIN TỨC NỔI BẬT
                </div>
                <!-- Bộ lọc danh mục bài viết ngay ở trang chủ -->
                <div class="flex flex-wrap items-center gap-1.5 px-3 py-1.5 text-[11px] font-bold">
                    <button type="button" data-post-cat="all" class="post-cat-btn px-2.5 py-1 rounded bg-brand-blue text-white">Tất cả bài viết</button>
                    <button type="button" data-post-cat="tu-van" class="post-cat-btn px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-blue-50">Tư vấn chọn máy</button>
                    <button type="button" data-post-cat="dich-vu" class="post-cat-btn px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-blue-50">Thu mua & Cho thuê</button>
                    <button type="button" data-post-cat="ky-thuat" class="post-cat-btn px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-blue-50">Kỹ thuật & Phụ tùng</button>
                </div>
            </div>

            <div id="blogPostsGrid" class="p-3 sm:p-5 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article data-category="tu-van" class="blog-card border border-slate-200 rounded-lg overflow-hidden flex flex-col bg-white hover:shadow-md transition">
                    <div class="relative h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC&sz=w600" alt="Máy may Jack và Juki tại Đà Nẵng" class="w-full h-full object-cover">
                        <div class="absolute top-2 left-2 bg-brand-blue text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            Tư vấn chọn máy
                        </div>
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                Kinh nghiệm chọn mua máy may công nghiệp Jack, Juki tiết kiệm điện cho xưởng may mới
                            </h3>
                            <p class="text-[11.5px] text-slate-500 mt-1.5 leading-relaxed">
                                Phân tích ưu điểm dòng máy 1 kim điện tử liền trục giúp tiết kiệm 70% điện năng và tăng năng suất tại Đà Nẵng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-400">
                            <span><i class="fa-regular fa-calendar mr-1"></i>Phạm Hồng Nhung</span>
                            <a href="#bao-gia" class="text-brand-blue font-bold hover:underline">Nhận tư vấn →</a>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article data-category="dich-vu" class="blog-card border border-slate-200 rounded-lg overflow-hidden flex flex-col bg-white hover:shadow-md transition">
                    <div class="relative h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1PpwtKs1KcQISvwRgJNpQYpy3qyrhGTv6&sz=w600" alt="Cho thuê và thu mua máy may công nghiệp Đà Nẵng" class="w-full h-full object-cover">
                        <div class="absolute top-2 left-2 bg-brand-red text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            Thu mua & Cho thuê
                        </div>
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                Dịch vụ cho thuê máy may công nghiệp & thu mua máy móc nhà xưởng giá cao tại Miền Trung
                            </h3>
                            <p class="text-[11.5px] text-slate-500 mt-1.5 leading-relaxed">
                                Giải pháp tối ưu chi phí đầu tư ban đầu cho các chuyền may gia công thời vụ với chế độ bảo trì tận nơi miễn phí.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-400">
                            <span><i class="fa-regular fa-calendar mr-1"></i>0905.335.457</span>
                            <a href="#bao-gia" class="text-brand-blue font-bold hover:underline">Báo giá thuê →</a>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article data-category="ky-thuat" class="blog-card border border-slate-200 rounded-lg overflow-hidden flex flex-col bg-white hover:shadow-md transition">
                    <div class="relative h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=19DdgAGKvkgI4qsqoNIpyofSMQyvoIH2z&sz=w600" alt="Máy vắt sổ Pegasus và Siruba" class="w-full h-full object-cover">
                        <div class="absolute top-2 left-2 bg-emerald-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            Kỹ thuật & Phụ tùng
                        </div>
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                So sánh máy vắt sổ Pegasus và Siruba: Cách bảo dưỡng định kỳ giúp máy chạy êm, bền bỉ
                            </h3>
                            <p class="text-[11.5px] text-slate-500 mt-1.5 leading-relaxed">
                                Hướng dẫn kiểm tra dầu máy, chỉnh ổ, thay kim và phụ tùng chính hãng tại cửa hàng 34 Tôn Đức Thắng, Đà Nẵng.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-400">
                            <span><i class="fa-regular fa-calendar mr-1"></i>Kỹ thuật PHN</span>
                            <a href="#bao-gia" class="text-brand-blue font-bold hover:underline">Xem chi tiết →</a>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article data-category="tu-van" class="blog-card border border-slate-200 rounded-lg overflow-hidden flex flex-col bg-white hover:shadow-md transition">
                    <div class="relative h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1DjTJ8QgGVTf-QcV6FKQ3vcxjbb1pBIoX&sz=w600" alt="Máy may cũ Đà Nẵng chất lượng cao" class="w-full h-full object-cover">
                        <div class="absolute top-2 left-2 bg-brand-blue text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            Tư vấn chọn máy
                        </div>
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand-blue leading-snug">
                                Máy may công nghiệp cũ chính hãng tại Đà Nẵng – Giải pháp tiết kiệm đến 40% chi phí
                            </h3>
                            <p class="text-[11.5px] text-slate-500 mt-1.5 leading-relaxed">
                                Tất cả máy may cũ tại Công Ty TNHH MTV Phạm Hồng Nhung đều được căn chỉnh chuẩn xác, bảo hành uy tín dài hạn.
                            </p>
                        </div>
                        <div class="mt-3 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-400">
                            <span><i class="fa-regular fa-calendar mr-1"></i>0902.833.811</span>
                            <a href="#sec-may-cu" class="text-brand-blue font-bold hover:underline">Xem máy cũ →</a>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- ==========================================
             7. DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU
             ========================================== -->
        <section id="doi-tac" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
            <div class="flatsome-section-title">
                <div class="flatsome-title-tab">
                    <i class="fa-solid fa-handshake"></i> ĐỐI TÁC THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG
                </div>
                <span class="text-xs text-slate-500 pr-4 hidden sm:inline">Hợp tác cùng các hãng thiết bị ngành may hàng đầu</span>
            </div>

            <div class="p-4 sm:p-5 grid grid-cols-2 sm:grid-cols-5 lg:grid-cols-10 gap-2.5">
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-brand-blue tracking-wider">JUKI</span>
                    <span class="text-[10px] text-slate-500">Nhật Bản</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-brand-blue tracking-wider">JACK</span>
                    <span class="text-[10px] text-slate-500">Máy May Số 1</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-brand-red tracking-wider">PEGASUS</span>
                    <span class="text-[10px] text-slate-500">Chuyên Vắt Sổ</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-emerald-700 tracking-wider">SIRUBA</span>
                    <span class="text-[10px] text-slate-500">Đài Loan</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-blue-800 tracking-wider">BROTHER</span>
                    <span class="text-[10px] text-slate-500">Nhật Bản</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-brand-red tracking-wider">HASHIMA</span>
                    <span class="text-[10px] text-slate-500">Thiết Bị Cắt Ủi</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-brand-blue tracking-wider">OKITO</span>
                    <span class="text-[10px] text-slate-500">Công Nghệ Mới</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-amber-600 tracking-wider">BRUCE</span>
                    <span class="text-[10px] text-slate-500">Chính Hãng</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-indigo-700 tracking-wider">YAMATO</span>
                    <span class="text-[10px] text-slate-500">Nhật Bản</span>
                </div>
                <div class="p-3 rounded border border-slate-200 bg-slate-50 hover:border-brand-blue text-center flex flex-col items-center justify-center">
                    <span class="font-extrabold text-sm text-rose-700 tracking-wider">BRITEX</span>
                    <span class="text-[10px] text-slate-500">Máy Chuyên Dụng</span>
                </div>
            </div>
        </section>

        <!-- ==========================================
             8. ĐƯA FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ
             ========================================== -->
        <section id="lien-he-map" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
            <div class="flatsome-section-title">
                <div class="flatsome-title-tab">
                    <i class="fa-solid fa-map-location-dot"></i> BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK TRANG CHỦ
                </div>
                <span class="text-xs text-slate-500 pr-4 hidden sm:inline">Kết nối trực tiếp với Công Ty TNHH MTV Phạm Hồng Nhung</span>
            </div>

            <div class="p-4 sm:p-6 grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- Cột 1: Bản đồ Google Map thực tế ngoài trang chủ -->
                <div class="lg:col-span-7 space-y-3">
                    <div class="flex flex-wrap items-center justify-between gap-2">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand-blue uppercase">
                                <i class="fa-solid fa-location-dot text-brand-red mr-1"></i> BẢN ĐỒ CHỈ ĐƯỜNG GOOGLE MAPS
                            </h3>
                            <p class="text-[11.5px] text-slate-600">
                                Trụ sở: 34 Phạm Nhữ Tăng, P. Thanh Khê • Văn phòng: 34 Tôn Đức Thắng, P. Hòa Khánh, TP. Đà Nẵng
                            </p>
                        </div>
                        <a 
                            href="https://maps.app.goo.gl/agFRWwZTB3tXkSYQ7" 
                            target="_blank" 
                            rel="noopener noreferrer" 
                            class="bg-brand-blue hover:bg-brand-red text-white text-xs font-bold px-3 py-1.5 rounded transition inline-flex items-center gap-1.5"
                        >
                            <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps
                        </a>
                    </div>

                    <!-- Khung Google Map trực tiếp + thẻ hình ảnh địa điểm -->
                    <div class="rounded-lg overflow-hidden border border-slate-300 shadow-sm bg-slate-100">
                        <iframe 
                            title="Bản đồ Công Ty TNHH MTV Phạm Hồng Nhung Đà Nẵng"
                            src="https://maps.google.com/maps?q=34%20T%C3%B4n%20%C4%90%E1%BB%A9c%20Th%E1%BA%AFng%2C%20H%C3%B2a%20Kh%C3%A1nh%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-64 sm:h-72 border-0 block" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                        <div class="p-3 bg-slate-50 border-t border-slate-200 flex flex-col sm:flex-row sm:items-center justify-between gap-2 text-xs">
                            <div class="space-y-0.5">
                                <div class="font-bold text-slate-800"><i class="fa-solid fa-map-pin text-brand-red mr-1"></i>Trụ sở: 34 Phạm Nhữ Tăng, Phường Thanh Khê, Tp. Đà Nẵng</div>
                                <div class="font-bold text-slate-800"><i class="fa-solid fa-store text-brand-blue mr-1"></i>Văn phòng: 34 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                            </div>
                            <a href="https://maps.app.goo.gl/agFRWwZTB3tXkSYQ7" target="_blank" rel="noopener noreferrer" class="text-brand-red font-extrabold hover:underline shrink-0">
                                Xem vị trí trên Google Map →
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Cột 2: Đưa Fanpage Facebook ra ngoài trang chủ -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-brand-blue uppercase">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1"></i> FANPAGE FACEBOOK CHÍNH THỨC
                            </h3>
                            <p class="text-[11.5px] text-slate-600">Cập nhật máy may mới về kho hàng ngày</p>
                        </div>
                        <a 
                            href="https://www.facebook.com/ton.danh.1460" 
                            target="_blank" 
                            rel="noopener noreferrer" 
                            class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3 py-1.5 rounded transition inline-flex items-center gap-1.5"
                        >
                            <i class="fa-brands fa-facebook-f"></i> Truy cập Facebook
                        </a>
                    </div>

                    <!-- Thẻ Fanpage trực quan hiển thị ngay ngoài trang chủ -->
                    <div class="rounded-lg border border-slate-300 overflow-hidden shadow-sm bg-white">
                        <!-- Ảnh bìa thực tế công ty -->
                        <div class="relative h-36 bg-slate-800 overflow-hidden">
                            <img 
                                src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w800" 
                                alt="Fanpage Công Ty TNHH MTV Phạm Hồng Nhung" 
                                class="w-full h-full object-cover opacity-85"
                                onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF=w800';"
                            >
                            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                            <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w200" 
                                    alt="Avatar Fanpage" 
                                    class="w-14 h-14 rounded-lg border-2 border-white object-cover bg-white shadow shrink-0"
                                >
                                <div class="text-white min-w-0">
                                    <a href="https://www.facebook.com/ton.danh.1460" target="_blank" rel="noopener noreferrer" class="font-extrabold text-sm sm:text-base hover:underline block truncate">
                                        Máy May Phạm Hồng Nhung - Đà Nẵng
                                    </a>
                                    <div class="text-[11px] text-blue-200 truncate">facebook.com/ton.danh.1460</div>
                                </div>
                            </div>
                        </div>

                        <!-- Nội dung và nút tương tác Fanpage -->
                        <div class="p-3.5 space-y-3 text-xs">
                            <p class="text-slate-600 leading-relaxed">
                                Chuyên mua bán, sửa chữa, cho thuê máy may công nghiệp & phụ tùng chính hãng tại Đà Nẵng. Liên hệ: <strong>0905.335.457 - 0902.833.811</strong>.
                            </p>
                            <div class="grid grid-cols-3 gap-1.5">
                                <img src="https://drive.google.com/thumbnail?id=1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC&sz=w300" alt="Ảnh thực tế 1" class="w-full h-16 object-cover rounded border border-slate-200">
                                <img src="https://drive.google.com/thumbnail?id=1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-&sz=w300" alt="Ảnh thực tế 2" class="w-full h-16 object-cover rounded border border-slate-200">
                                <img src="https://drive.google.com/thumbnail?id=16oOareb_FSIDc9G_2sdST1yaNgNxCDtP&sz=w300" alt="Ảnh thực tế 3" class="w-full h-16 object-cover rounded border border-slate-200">
                            </div>
                            <div class="flex items-center gap-2 pt-1">
                                <a href="https://www.facebook.com/ton.danh.1460" target="_blank" rel="noopener noreferrer" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white font-bold py-2 px-3 rounded text-center transition">
                                    <i class="fa-brands fa-facebook mr-1"></i> Theo Dõi Trang
                                </a>
                                <a href="https://www.facebook.com/ton.danh.1460" target="_blank" rel="noopener noreferrer" class="flex-1 bg-slate-100 hover:bg-slate-200 text-slate-800 font-bold py-2 px-3 rounded text-center transition">
                                    <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i> Nhắn Tin
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </section>

    </main>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (GIỐNG MẪU MAYMAYDANANG.COM)
         ========================================== -->
    <footer class="bg-[#062846] text-white mt-8 border-t-4 border-brand-red">
        <div class="container-1500 py-8 sm:py-10 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 text-xs sm:text-sm">
            
            <!-- Cột 1: Thông tin công ty -->
            <div class="lg:col-span-5 space-y-2.5">
                <div class="flex items-center gap-2.5">
                    <img 
                        src="https://drive.google.com/thumbnail?id=15D6Z3eqoRivdqKe0n3cdIOmQq7aiIeDF&sz=w200" 
                        alt="Logo Công Ty TNHH MTV Phạm Hồng Nhung" 
                        class="w-11 h-11 rounded bg-white object-cover border border-white/30 shrink-0"
                    >
                    <div>
                        <h3 class="font-extrabold text-sm sm:text-base text-amber-300 uppercase">
                            CÔNG TY TNHH MỘT THÀNH VIÊN PHẠM HỒNG NHUNG
                        </h3>
                        <div class="text-xs text-blue-200">Website: phamhongnhung.com • MST: 0401558881</div>
                    </div>
                </div>
                <ul class="space-y-2 text-blue-100 text-xs pt-1">
                    <li>
                        <i class="fa-solid fa-location-dot text-brand-red w-5"></i>
                        <strong>Địa chỉ trụ sở:</strong> 34 Phạm Nhữ Tăng, Phường Thanh Khê, Tp. Đà Nẵng
                    </li>
                    <li>
                        <i class="fa-solid fa-store text-amber-400 w-5"></i>
                        <strong>Văn phòng:</strong> 34 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng
                    </li>
                    <li>
                        <i class="fa-solid fa-phone-volume text-emerald-400 w-5"></i>
                        <strong>Điện thoại:</strong> <a href="tel:0905335457" class="font-bold text-white hover:underline">0905.335.457</a> - <a href="tel:0902833811" class="font-bold text-white hover:underline">0902.833.811</a>
                    </li>
                    <li>
                        <i class="fa-solid fa-globe text-sky-400 w-5"></i>
                        <strong>Website:</strong> <a href="https://phamhongnhung.com" class="hover:underline">phamhongnhung.com</a>
                    </li>
                    <li>
                        <i class="fa-brands fa-facebook text-sky-400 w-5"></i>
                        <strong>Facebook:</strong> <a href="https://www.facebook.com/ton.danh.1460" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/ton.danh.1460</a>
                    </li>
                </ul>
            </div>

            <!-- Cột 2: Danh mục sản phẩm -->
            <div class="lg:col-span-4 space-y-2.5">
                <h4 class="font-extrabold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">
                    DANH MỤC SẢN PHẨM CHÍNH
                </h4>
                <div class="grid grid-cols-2 gap-1.5 text-xs text-blue-100">
                    <a href="#sec-jack" class="hover:text-amber-300">› Máy May JACK</a>
                    <a href="#sec-juki" class="hover:text-amber-300">› Máy May JUKI</a>
                    <a href="#sec-pegasus" class="hover:text-amber-300">› Máy May PEGASUS</a>
                    <a href="#sec-siruba" class="hover:text-amber-300">› Máy May SIRUBA</a>
                    <a href="#sec-brother" class="hover:text-amber-300">› Máy May BROTHER</a>
                    <a href="#sec-hashima" class="hover:text-amber-300">› Máy Cắt HASHIMA</a>
                    <a href="#sec-okito" class="hover:text-amber-300">› Máy May OKITO</a>
                    <a href="#sec-okito" class="hover:text-amber-300">› Máy May BRUCE</a>
                    <a href="#sec-may-cu" class="hover:text-amber-300">› Máy May Cũ Các Hãng</a>
                    <a href="#sec-may-cu" class="hover:text-amber-300">› Thiết Bị Phụ Tùng</a>
                </div>
            </div>

            <!-- Cột 3: Chính sách & Thống kê -->
            <div class="lg:col-span-3 space-y-2.5">
                <h4 class="font-extrabold text-sm uppercase text-amber-300 border-b border-white/15 pb-1.5">
                    DỊCH VỤ & HỖ TRỢ KHÁCH HÀNG
                </h4>
                <ul class="space-y-1.5 text-xs text-blue-100">
                    <li><a href="#bao-gia" class="hover:text-amber-300">› Cho thuê máy may công nghiệp</a></li>
                    <li><a href="#bao-gia" class="hover:text-amber-300">› Thu mua - Thanh lý máy xưởng may</a></li>
                    <li><a href="#bao-gia" class="hover:text-amber-300">› Sửa chữa bảo hành tận nơi 24/7</a></li>
                    <li><a href="https://maps.app.goo.gl/agFRWwZTB3tXkSYQ7" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300">› Chỉ đường Google Maps</a></li>
                </ul>
                <div class="p-2.5 rounded bg-white/5 border border-white/10 text-[11px] text-blue-200">
                    <div class="font-bold text-white mb-0.5">THỐNG KÊ TRUY CẬP</div>
                    <div>Đang trực tuyến: <strong class="text-emerald-400">18</strong> • Tổng truy cập: <strong class="text-amber-300">128.450</strong></div>
                </div>
            </div>

        </div>

        <div class="bg-[#041d33] py-3 text-center text-[11.5px] text-blue-200 border-t border-white/10">
            <div class="container-1500">
                Copyright 2026 © <strong>CÔNG TY TNHH MỘT THÀNH VIÊN PHẠM HỒNG NHUNG</strong> (phamhongnhung.com) - Đ/c: 34 Phạm Nhữ Tăng & 34 Tôn Đức Thắng, TP. Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         (Thiết kế gọn gàng, không làm tràn viền màn hình)
         ========================================== -->
    <div class="fixed bottom-3 left-3 z-40 flex flex-col gap-2">
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0905335457" 
            target="_blank" 
            rel="noopener noreferrer" 
            class="floating-pulse-blue flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Chat Zalo 0905.335.457"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo: 0905.335.457</span>
        </a>

        <!-- Nút Facebook nổi bật -->
        <a 
            href="https://www.facebook.com/ton.danh.1460" 
            target="_blank" 
            rel="noopener noreferrer" 
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Fanpage Facebook Công Ty Phạm Hồng Nhung"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook Phạm Hồng Nhung</span>
        </a>

        <!-- Nút Hotline 1 nổi bật -->
        <a 
            href="tel:0905335457" 
            class="floating-pulse-red flex items-center gap-2 bg-brand-red hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Gọi 0905.335.457"
        >
            <span class="w-6 h-6 rounded-full bg-white text-brand-red flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0905.335.457</span>
        </a>

        <!-- Nút Hotline 2 nổi bật -->
        <a 
            href="tel:0902833811" 
            class="flex items-center gap-2 bg-amber-600 hover:bg-amber-700 text-white px-3 py-2 rounded-full shadow-lg transition"
            title="Gọi 0902.833.811"
        >
            <span class="w-6 h-6 rounded-full bg-white text-amber-600 flex items-center justify-center text-xs shrink-0">
                <i class="fa-solid fa-phone"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0902.833.811</span>
        </a>
    </div>

    <!-- Nút lên đầu trang bên phải -->
    <a href="#top" aria-label="Lên đầu trang" class="fixed bottom-3 right-3 z-40 w-9 h-9 rounded-full bg-brand-blue hover:bg-brand-red text-white shadow-lg flex items-center justify-center text-xs transition">
        <i class="fa-solid fa-arrow-up"></i>
    </a>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SẢN PHẨM THỰC TẾ, SLIDER, TÌM KIẾM & FORM BÁO GIÁ
         ========================================== -->
    <script>
        /* Danh sách danh mục và toàn bộ 12 ảnh sản phẩm thực tế từ Google Drive
           được phân bổ chuẩn xác vào các danh mục của web mẫu maymaydanang.com */
        const PRODUCT_SECTIONS = [
            {
                id: 'sec-jack',
                code: 'jack',
                title: 'MÁY MAY JACK',
                subtitle: 'Máy 1 kim điện tử, máy vắt sổ, trần đè, thùa khuy, đính cúc Jack chính hãng',
                products: [
                    {
                        name: 'Máy May 1 Kim Điện Tử Liền Trục Tự Động Cắt Chỉ Jack Chính Hãng',
                        driveId: '1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC',
                        oldPrice: '7.500.000đ',
                        salePrice: '6.300.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy Vắt Sổ Công Nghiệp Liền Trục Tốc Độ Cao Jack E4S / C4',
                        driveId: '1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-',
                        oldPrice: '9.800.000đ',
                        salePrice: '8.200.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy Trần Đè Cắt Chỉ Tự Động & Cuốn Sườn Jack JK-T9270D / W4',
                        driveId: '16oOareb_FSIDc9G_2sdST1yaNgNxCDtP',
                        oldPrice: '12.500.000đ',
                        salePrice: '10.500.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy Đính Cúc, Di Bọ & Thùa Khuy Điện Tử Tốc Độ Cao Jack JK-1900G',
                        driveId: '1CtY-JARXIuiY8Cd2XOl505j-55THdxq8',
                        oldPrice: '21.000.000đ',
                        salePrice: '17.800.000đ',
                        discount: '-15%'
                    }
                ]
            },
            {
                id: 'sec-juki',
                code: 'juki',
                title: 'MÁY MAY JUKI',
                subtitle: 'Công nghệ Nhật Bản bền bỉ: DDL-8700, DDL-8000A, DDL-9000C Series',
                products: [
                    {
                        name: 'Máy May 1 Kim Điện Tử Juki DDL-9000C / DDL-8000A Series Chính Hãng',
                        driveId: '16oOareb_FSIDc9G_2sdST1yaNgNxCDtP',
                        oldPrice: '11.200.000đ',
                        salePrice: '9.400.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy May 1 Kim Cơ & Liền Trục Juki DDL-8700 Bền Đẹp Cho Xưởng May',
                        driveId: '1CtY-JARXIuiY8Cd2XOl505j-55THdxq8',
                        oldPrice: '6.800.000đ',
                        salePrice: '5.500.000đ',
                        discount: '-19%'
                    },
                    {
                        name: 'Máy Thùa Khuy Đầu Bằng & Đính Bọ Điện Tử Juki LBH-1790 / LK-1900',
                        driveId: '1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC',
                        oldPrice: '26.000.000đ',
                        salePrice: '21.500.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy May 2 Kim Ổ Lớn Cắt Chỉ Tự Động Juki LH-3500A Series',
                        driveId: '1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-',
                        oldPrice: '19.500.000đ',
                        salePrice: '16.200.000đ',
                        discount: '-17%'
                    }
                ]
            },
            {
                id: 'sec-pegasus',
                code: 'pegasus',
                title: 'MÁY MAY PEGASUS',
                subtitle: 'Chuyên máy vắt sổ, máy trần đè, máy chuyên dụng Pegasus EX/GX/MX/M900',
                products: [
                    {
                        name: 'Máy Vắt Sổ Công Nghiệp Pegasus M900 / MX5200 Series Động Cơ Liền Trục',
                        driveId: '1PpwtKs1KcQISvwRgJNpQYpy3qyrhGTv6',
                        oldPrice: '10.800.000đ',
                        salePrice: '8.900.000đ',
                        discount: '-18%'
                    },
                    {
                        name: 'Máy Vắt Sổ Đầu Máy Khô Tốc Độ Cao Pegasus EX5200 / GX5200 Series',
                        driveId: '19DdgAGKvkgI4qsqoNIpyofSMQyvoIH2z',
                        oldPrice: '12.500.000đ',
                        salePrice: '10.400.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Trần Đè 3 Kim 5 Chỉ Cắt Chỉ Tự Động Pegasus W500P / W600P',
                        driveId: '1MFpuEq0z7fZ2R_pZlJqEcoGV_I1N1Nl9',
                        oldPrice: '14.500.000đ',
                        salePrice: '12.100.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Chuyên Dụng Viền Thun & Kansai Pegasus Chính Hãng Bảo Hành 12 Tháng',
                        driveId: '1O2ZcR5igNhksNwuHm2LdmyAbA323L9bo',
                        oldPrice: '15.000.000đ',
                        salePrice: '12.600.000đ',
                        discount: '-16%'
                    }
                ]
            },
            {
                id: 'sec-siruba',
                code: 'siruba',
                title: 'MÁY MAY SIRUBA',
                subtitle: 'Máy 1 kim DL7200, máy vắt sổ 747K/757K, máy trần đè F007K Siruba Đài Loan',
                products: [
                    {
                        name: 'Máy May 1 Kim Tự Động Cắt Chỉ Dạng Liền Trục Siruba DL7200 / DL720',
                        driveId: '19DdgAGKvkgI4qsqoNIpyofSMQyvoIH2z',
                        oldPrice: '8.500.000đ',
                        salePrice: '7.100.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy Vắt Sổ 2 Kim 4 Chỉ & 5 Chỉ Siruba 747K / 757K Chính Hãng',
                        driveId: '1PpwtKs1KcQISvwRgJNpQYpy3qyrhGTv6',
                        oldPrice: '10.200.000đ',
                        salePrice: '8.500.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Trần Đè Móc Xích Đa Năng Siruba F007K / C007K Chuyên Hàng Thun',
                        driveId: '1mXSI6rR8cfsnmDj6Ms3pK-20pmYGMM1D',
                        oldPrice: '13.800.000đ',
                        salePrice: '11.500.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Đính Cúc, Đính Bọ & Thùa Khuy Điện Tử Siruba BT430 / LBHS-1790',
                        driveId: '1WEOI8JpZe0JBluA9x5zQE2jfwy-2WDpY',
                        oldPrice: '22.000.000đ',
                        salePrice: '18.500.000đ',
                        discount: '-16%'
                    }
                ]
            },
            {
                id: 'sec-brother',
                code: 'brother',
                title: 'MÁY MAY BROTHER',
                subtitle: 'Máy 1 kim điện tử S-7250A/S-7300A, máy 2 kim NEXIO, máy cuốn sườn Brother',
                products: [
                    {
                        name: 'Máy May 1 Kim Điện Tử Cắt Chỉ Tự Động Brother S-7250A / S-7300A',
                        driveId: '1MFpuEq0z7fZ2R_pZlJqEcoGV_I1N1Nl9',
                        oldPrice: '10.500.000đ',
                        salePrice: '8.800.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy May 2 Kim Truyền Động Trực Tiếp Brother NEXIO T-8422D / T-8722D',
                        driveId: '1O2ZcR5igNhksNwuHm2LdmyAbA323L9bo',
                        oldPrice: '21.500.000đ',
                        salePrice: '17.900.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Cuốn Sườn & Máy Lập Trình Điện Tử Khổ Nhỏ Brother Chính Hãng',
                        driveId: '1DjTJ8QgGVTf-QcV6FKQ3vcxjbb1pBIoX',
                        oldPrice: '24.000.000đ',
                        salePrice: '19.800.000đ',
                        discount: '-18%'
                    },
                    {
                        name: 'Máy Thùa Khuy Điện Tử & Đính Bọ Tốc Độ Cao Brother HE-800B / KE-430F',
                        driveId: '1aQ3B_X0ry9_qzXSbvZPiPEYQoTgE1xBS',
                        oldPrice: '27.500.000đ',
                        salePrice: '22.900.000đ',
                        discount: '-17%'
                    }
                ]
            },
            {
                id: 'sec-hashima',
                code: 'hashima',
                title: 'MÁY CÔNG NGHIỆP HÓA - HASHIMA',
                subtitle: 'Máy cắt vải đứng, máy cắt đầu bàn, máy dò kim, máy ép nhiệt, nồi hơi, bàn hút',
                products: [
                    {
                        name: 'Máy Cắt Vải Đứng Công Nghiệp Lưỡi Dao Tự Mài Hashima KM-SV Series',
                        driveId: '1O2ZcR5igNhksNwuHm2LdmyAbA323L9bo',
                        oldPrice: '7.200.000đ',
                        salePrice: '6.200.000đ',
                        discount: '-14%'
                    },
                    {
                        name: 'Máy Cắt Đầu Bàn, Máy Trải Vải & Thiết Bị Phòng Cắt Xưởng May',
                        driveId: '1mXSI6rR8cfsnmDj6Ms3pK-20pmYGMM1D',
                        oldPrice: '5.500.000đ',
                        salePrice: '4.600.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy Ép Mếch, Máy Ép Nhiệt 2 Mâm & Bàn Hút Chân Không Công Nghiệp',
                        driveId: '1WEOI8JpZe0JBluA9x5zQE2jfwy-2WDpY',
                        oldPrice: '9.500.000đ',
                        salePrice: '7.900.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Nồi Hơi Bàn Ủi Công Nghiệp & Máy Dò Kim Ngành May Mặc Hashima',
                        driveId: '1MFpuEq0z7fZ2R_pZlJqEcoGV_I1N1Nl9',
                        oldPrice: '11.000.000đ',
                        salePrice: '9.300.000đ',
                        discount: '-15%'
                    }
                ]
            },
            {
                id: 'sec-okito',
                code: 'okito',
                title: 'MÁY MAY OKITO & BRUCE',
                subtitle: 'Máy 1 kim điện tử TK-M5-D4, máy xén viền, máy cào bơi, máy vắt sổ Okito & Bruce',
                products: [
                    {
                        name: 'Máy May 1 Kim Điện Tử Liền Trục Okito TK-8700 / TK-M5-D4 Thế Hệ Mới',
                        driveId: '1mXSI6rR8cfsnmDj6Ms3pK-20pmYGMM1D',
                        oldPrice: '6.900.000đ',
                        salePrice: '5.800.000đ',
                        discount: '-16%'
                    },
                    {
                        name: 'Máy 1 Kim Xén Cạnh Điện Tử & Máy Cào Bơi Liền Trục Okito TK-5200-D3',
                        driveId: '1WEOI8JpZe0JBluA9x5zQE2jfwy-2WDpY',
                        oldPrice: '8.400.000đ',
                        salePrice: '7.100.000đ',
                        discount: '-15%'
                    },
                    {
                        name: 'Máy May 1 Kim Điện Tử & Máy Vắt Sổ Công Nghiệp Bruce R4000 / X5S-4',
                        driveId: '1DjTJ8QgGVTf-QcV6FKQ3vcxjbb1pBIoX',
                        oldPrice: '8.900.000đ',
                        salePrice: '7.400.000đ',
                        discount: '-17%'
                    },
                    {
                        name: 'Máy Chuyên Mổ Túi Quần Zip & 2 Kim Chỉ Tết Liền Trục Okito - Bruce',
                        driveId: '1aQ3B_X0ry9_qzXSbvZPiPEYQoTgE1xBS',
                        oldPrice: '16.500.000đ',
                        salePrice: '13.800.000đ',
                        discount: '-16%'
                    }
                ]
            },
            {
                id: 'sec-may-cu',
                code: 'may-cu',
                title: 'MÁY MAY CŨ & THIẾT BỊ PHỤ TÙNG',
                subtitle: 'Máy may công nghiệp cũ tuyển chọn 90-95%, mô tơ tiết kiệm điện, ghế ngồi may & phụ tùng',
                products: [
                    {
                        name: 'Máy May 1 Kim Công Nghiệp Cũ Juki / Jack / Brother Tuyển Chọn Mới 90%',
                        driveId: '1DjTJ8QgGVTf-QcV6FKQ3vcxjbb1pBIoX',
                        oldPrice: '4.500.000đ',
                        salePrice: '3.200.000đ',
                        discount: '-29%'
                    },
                    {
                        name: 'Máy Vắt Sổ & Máy Trần Đè Công Nghiệp Cũ Pegasus / Siruba Chạy Êm',
                        driveId: '1aQ3B_X0ry9_qzXSbvZPiPEYQoTgE1xBS',
                        oldPrice: '6.500.000đ',
                        salePrice: '4.800.000đ',
                        discount: '-26%'
                    },
                    {
                        name: 'Motor Servo Tiết Kiệm Điện, Đèn LED Máy May & Linh Kiện Máy 1 Kim',
                        driveId: '1qQSsxSp5fKlMg2GjmLpy98cj2PN9lCzC',
                        oldPrice: '950.000đ',
                        salePrice: '750.000đ',
                        discount: '-21%'
                    },
                    {
                        name: 'Bàn Chân Máy May Công Nghiệp, Ghế Ngồi May & Phụ Tùng Ngành May Mặc',
                        driveId: '1oCYPMhP6Lj3UdPft2IGv-5kW3x_l4hY-',
                        oldPrice: '1.200.000đ',
                        salePrice: '890.000đ',
                        discount: '-26%'
                    }
                ]
            }
        ];

        /* Hàm render toàn bộ danh mục sản phẩm trang chủ
           - Trên điện thoại: chia đúng 2 cột (grid-cols-2)
           - Trên máy tính: chia 4 cột
           - Tên sản phẩm hiển thị đầy đủ 100%, không bị tràn hoặc cắt thiếu chữ
           - Có % giảm giá góc trên bên trái chuẩn Flatsome, không để nhãn dán thừa */
        function renderProductSections(filterCategory = 'all', searchKeyword = '') {
            const container = document.getElementById('productSectionsContainer');
            const keyword = searchKeyword.trim().toLowerCase();
            let html = '';

            PRODUCT_SECTIONS.forEach(section => {
                if (filterCategory !== 'all' && section.code !== filterCategory) return;

                const filteredProducts = section.products.filter(p =>
                    !keyword ||
                    p.name.toLowerCase().includes(keyword) ||
                    section.title.toLowerCase().includes(keyword)
                );

                if (filteredProducts.length === 0) return;

                html += `
                <section id="${section.id}" class="bg-white rounded-lg shadow-sm border border-slate-200 overflow-hidden">
                    <div class="flatsome-section-title">
                        <div class="flatsome-title-tab">
                            <i class="fa-solid fa-Screwdriver-wrench"></i> ${section.title}
                        </div>
                        <a href="#bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-red pr-3 sm:pr-4 whitespace-nowrap">
                            Xem thêm <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                    <div class="px-3 sm:px-4 pt-2 text-[11.5px] text-slate-500">
                        ${section.subtitle}
                    </div>
                    <!-- SẢN PHẨM CHIA THÀNH 2 CỘT TRÊN ĐIỆN THOẠI (grid-cols-2), 4 CỘT TRÊN MÁY TÍNH -->
                    <div class="p-2.5 sm:p-4 grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4">
                        ${filteredProducts.map(prod => `
                            <div class="group bg-white rounded-lg border border-slate-200 hover:border-brand-blue hover:shadow-md transition flex flex-col overflow-hidden relative">
                                <!-- % giảm giá góc trên bên trái giống Flatsome -->
                                <div class="flatsome-sale-badge">${prod.discount}</div>

                                <!-- Khung ảnh thực tế từ Google Drive -->
                                <div class="relative w-full aspect-square bg-slate-50 overflow-hidden border-b border-slate-100">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=${prod.driveId}&sz=w700" 
                                        alt="${prod.name}" 
                                        class="w-full h-full object-cover group-hover:scale-105 transition duration-300"
                                        loading="lazy"
                                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/${prod.driveId}=w700';"
                                    >
                                </div>

                                <!-- Thông tin sản phẩm: Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ -->
                                <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                                    <h3 class="product-title-full text-xs sm:text-[13.5px] font-bold text-slate-800 group-hover:text-brand-blue">
                                        ${prod.name}
                                    </h3>

                                    <div class="mt-2.5 pt-2 border-t border-slate-100">
                                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                            <span class="text-[11px] text-slate-400 line-through">${prod.oldPrice}</span>
                                            <span class="text-xs sm:text-sm font-extrabold text-brand-red">${prod.salePrice}</span>
                                        </div>
                                        <button 
                                            type="button"
                                            onclick="selectProductForQuote('${prod.name.replace(/'/g, "\\'")}')"
                                            class="mt-2 w-full bg-brand-blue hover:bg-brand-red text-white text-[11px] sm:text-xs font-bold py-1.5 px-2 rounded transition text-center"
                                        >
                                            Nhận báo giá
                                        </button>
                                    </div>
                                </div>
                            </div>
                        `).join('')}
                    </div>
                </section>`;
            });

            if (!html) {
                html = `
                <div class="bg-white rounded-lg p-6 text-center border border-slate-200">
                    <p class="text-sm font-bold text-slate-700">Không tìm thấy sản phẩm phù hợp với từ khóa "${searchKeyword}".</p>
                    <button type="button" onclick="resetProductFilter()" class="mt-3 bg-brand-blue text-white text-xs font-bold px-4 py-2 rounded">
                        Hiển thị tất cả sản phẩm
                    </button>
                </div>`;
            }

            container.innerHTML = html;
        }

        function resetProductFilter() {
            document.getElementById('searchInput').value = '';
            document.getElementById('mobileSearchInput').value = '';
            document.getElementById('searchCategorySelect').value = 'all';
            renderProductSections('all', '');
        }

        function selectProductForQuote(productName) {
            const input = document.getElementById('quoteProduct');
            if (input) {
                input.value = productName;
            }
            const formSection = document.getElementById('bao-gia');
            if (formSection) {
                formSection.scrollIntoView({ behavior: 'smooth' });
            }
            setTimeout(() => {
                const nameField = document.getElementById('quoteName');
                if (nameField) nameField.focus();
            }, 450);
        }

        window.onload = function () {
            // 1. Render sản phẩm thực tế vào đúng các danh mục
            renderProductSections();

            // 2. Xử lý 2 Banner tự trượt chuyên nghiệp
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.slider-dot');
            let currentSlide = 0;

            function showSlide(index) {
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach((slide, i) => {
                    if (i === currentSlide) {
                        slide.classList.add('active');
                    } else {
                        slide.classList.remove('active');
                    }
                });
                dots.forEach((dot, i) => {
                    if (i === currentSlide) {
                        dot.className = 'slider-dot w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                    } else {
                        dot.className = 'slider-dot w-2 h-1.5 rounded-full bg-white/60 transition-all';
                    }
                });
            }

            let sliderTimer = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 4500);

            function restartSliderTimer() {
                clearInterval(sliderTimer);
                sliderTimer = setInterval(() => {
                    showSlide(currentSlide + 1);
                }, 4500);
            }

            document.getElementById('prevSlideBtn').addEventListener('click', () => {
                showSlide(currentSlide - 1);
                restartSliderTimer();
            });
            document.getElementById('nextSlideBtn').addEventListener('click', () => {
                showSlide(currentSlide + 1);
                restartSliderTimer();
            });
            dots.forEach(dot => {
                dot.addEventListener('click', () => {
                    showSlide(parseInt(dot.getAttribute('data-goto'), 10));
                    restartSliderTimer();
                });
            });

            // 3. Xử lý Drawer Menu trên điện thoại
            const mobileDrawer = document.getElementById('mobileDrawer');
            const openMenuBtn = document.getElementById('mobileMenuBtn');
            const closeMenuBtn = document.getElementById('closeMobileMenuBtn');
            const backdrop = document.getElementById('mobileDrawerBackdrop');

            function toggleMobileDrawer(show) {
                if (show) {
                    mobileDrawer.classList.remove('hidden');
                } else {
                    mobileDrawer.classList.add('hidden');
                }
            }
            openMenuBtn.addEventListener('click', () => toggleMobileDrawer(true));
            closeMenuBtn.addEventListener('click', () => toggleMobileDrawer(false));
            backdrop.addEventListener('click', () => toggleMobileDrawer(false));
            document.querySelectorAll('.mobile-nav-link').forEach(link => {
                link.addEventListener('click', () => toggleMobileDrawer(false));
            });

            // 4. Xử lý tìm kiếm trên máy tính và điện thoại
            document.getElementById('desktopSearchForm').addEventListener('submit', function (e) {
                e.preventDefault();
                const cat = document.getElementById('searchCategorySelect').value;
                const kw = document.getElementById('searchInput').value;
                renderProductSections(cat, kw);
                document.getElementById('productSectionsContainer').scrollIntoView({ behavior: 'smooth' });
            });

            document.getElementById('mobileSearchForm').addEventListener('submit', function (e) {
                e.preventDefault();
                const kw = document.getElementById('mobileSearchInput').value;
                renderProductSections('all', kw);
                document.getElementById('productSectionsContainer').scrollIntoView({ behavior: 'smooth' });
            });

            // 5. Bộ lọc danh mục bài viết ở trang chủ
            const postBtns = document.querySelectorAll('.post-cat-btn');
            const postCards = document.querySelectorAll('.blog-card');
            postBtns.forEach(btn => {
                btn.addEventListener('click', () => {
                    const cat = btn.getAttribute('data-post-cat');
                    postBtns.forEach(b => {
                        b.className = 'post-cat-btn px-2.5 py-1 rounded bg-slate-100 text-slate-700 hover:bg-blue-50';
                    });
                    btn.className = 'post-cat-btn px-2.5 py-1 rounded bg-brand-blue text-white';

                    postCards.forEach(card => {
                        if (cat === 'all' || card.getAttribute('data-category') === cat) {
                            card.classList.remove('hidden');
                        } else {
                            card.classList.add('hidden');
                        }
                    });
                });
            });

            // 6. Xử lý gửi Form Báo Giá Trang Chủ (không dùng alert)
            const quoteForm = document.getElementById('quoteRequestForm');
            const quoteSuccessBox = document.getElementById('quoteSuccessBox');
            quoteForm.addEventListener('submit', function (e) {
                e.preventDefault();
                const name = document.getElementById('quoteName').value.trim();
                const phone = document.getElementById('quotePhone').value.trim();
                const category = document.getElementById('quoteCategory').value;
                const prod = document.getElementById('quoteProduct').value.trim();

                quoteSuccessBox.innerHTML = `
                    <i class="fa-solid fa-circle-check mr-1"></i>
                    Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${prod || category}</strong> đã được ghi nhận.
                    Bộ phận kinh doanh <strong>Công Ty TNHH MTV Phạm Hồng Nhung</strong> sẽ liên hệ ngay qua SĐT/Zalo hoặc quý khách có thể gọi trực tiếp <strong>0905.335.457 - 0902.833.811</strong>.
                `;
                quoteSuccessBox.classList.remove('hidden');
                quoteForm.reset();
            });
        };
    </script>
</body>
</html>
