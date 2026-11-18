<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH - vietbach.com</title>
  <meta name="description" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH chuyên Thiết kế - Xây dựng - Nội thất Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng. Địa chỉ: 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng. Hotline: 0927.000.001" />

  <!-- Open Graph Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="vietbach.com - Xây Dựng Việt Bách" />
  <meta property="og:url" content="https://vietbach.com/" />
  <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH | vietbach.com" />
  <meta property="og:description" content="Chuyên Tư Vấn Thiết Kế Kiến Trúc - Thi Công Xây Dựng Trọn Gói - Hoàn Thiện Nội Thất tại Đà Nẵng. Địa chỉ: 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng. ĐT: 0927.000.001" />
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w1200" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH Tư Vấn Thiết Kế Và Xây Dựng Việt Bách" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w1200" />
  <link rel="icon" href="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w200" />

  <!-- Google Font Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

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
            vbBlue: '#0b3b75',
            vbBlueDark: '#072852',
            vbBlueLight: '#1656a3',
            vbGold: '#d97706',
            vbGoldLight: '#f59e0b',
          }
        }
      }
    }
  </script>

  <style>
    /* Chống tràn viền tuyệt đối và không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #f8fafc;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .container-95 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .container-95 {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Tối ưu thanh danh mục (menu) trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng từ */
    .nav-cat-list {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      gap: 2px 6px;
    }
    .nav-cat-item {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      line-height: 1.4;
      padding: 6px 8px;
      border-radius: 6px;
      transition: all 0.2s ease;
      position: relative;
    }
    @media (min-width: 1280px) {
      .nav-cat-item {
        font-size: 12.5px;
        padding: 7px 10px;
      }
    }
    .nav-cat-item:hover {
      background-color: rgba(255, 255, 255, 0.14);
      color: #fbbf24;
    }

    /* Dropdown Submenu kiểu Flatsome */
    .has-dropdown:hover .ux-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }
    .ux-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
      z-index: 60;
    }

    /* Tiêu đề Section chuẩn Flatsome (Section Title Container) */
    .flatsome-title-wrap {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1.25rem;
      width: 100%;
    }
    .flatsome-title-line {
      flex: 1;
      height: 2px;
      background-color: #cbd5e1;
    }
    .flatsome-title-main {
      padding: 0 14px;
      font-weight: 800;
      text-transform: uppercase;
      color: #0b3b75;
      text-align: center;
      letter-spacing: 0.02em;
    }

    /* Tên sản phẩm / công trình hiển thị đầy đủ, không bị tràn hoặc thiếu chữ */
    .product-title-safe {
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
      line-height: 1.4;
    }

    /* Hiệu ứng nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 119, 6, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 119, 6, 0); }
    }
    .floating-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body>

  <!-- ================= WRAPPER CHUẨN FLATSOME ================= -->
  <div id="wrapper" class="w-full overflow-x-hidden">

    <!-- ================= TOP BAR ================= -->
    <div id="top-bar" class="bg-vbBlueDark text-slate-200 text-xs py-1.5 border-b border-white/10">
      <div class="container-95 flex flex-wrap items-center justify-between gap-2">
        <div class="flex items-center gap-3 flex-wrap">
          <span class="inline-flex items-center gap-1.5 font-medium text-amber-400">
            <i class="fa-solid fa-building"></i>
            <span>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH</span>
          </span>
          <span class="hidden md:inline text-slate-400">|</span>
          <span class="hidden sm:inline-flex items-center gap-1 text-slate-200">
            <i class="fa-solid fa-location-dot text-amber-400"></i>
            <span>1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng</span>
          </span>
        </div>
        <div class="flex items-center gap-3 text-[11px] sm:text-xs">
          <span class="inline-flex items-center gap-1">
            <i class="fa-solid fa-globe text-amber-400"></i>
            <strong class="text-white">vietbach.com</strong>
          </span>
          <span class="text-slate-400">|</span>
          <a href="tel:0927000001" class="inline-flex items-center gap-1 text-amber-300 font-semibold hover:underline">
            <i class="fa-solid fa-phone-volume"></i>
            <span>0927.000.001</span>
          </a>
        </div>
      </div>
    </div>

    <!-- ================= HEADER (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header id="header" class="sticky top-0 z-40 bg-white shadow-md border-b border-slate-200">
      <div class="header-wrapper">
        <!-- Header Main: Logo nhỏ gọn + Tên công ty -->
        <div class="header-main py-2.5 bg-white">
          <div class="container-95 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#wrapper" class="flex items-center gap-2.5 min-w-0 group">
              <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center shrink-0 shadow-sm overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w400"
                  data-drive-id="1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf"
                  alt="Logo Xây Dựng Việt Bách"
                  class="w-full h-full object-contain"
                  onerror="handleDriveImgError(this, 'VIỆT BÁCH')"
                />
              </div>
              <div class="min-w-0">
                <div class="text-xs sm:text-sm md:text-base font-extrabold text-vbBlue leading-tight tracking-tight truncate sm:whitespace-normal">
                  CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH
                </div>
                <div class="text-[11px] sm:text-xs text-slate-600 font-medium flex flex-wrap items-center gap-x-2">
                  <span class="text-vbGold font-semibold">vietbach.com</span>
                  <span class="hidden sm:inline">•</span>
                  <span class="truncate">Thiết Kế Kiến Trúc – Thi Công Xây Dựng – Nội Thất Đà Nẵng</span>
                </div>
              </div>
            </a>

            <!-- Nút mở Menu trên Điện Thoại (Không để nút gọi ngay trên header) -->
            <button
              type="button"
              onclick="toggleMobileMenu()"
              aria-label="Mở danh mục"
              class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-vbBlue text-white text-xs font-semibold shrink-0 hover:bg-vbBlueDark focus:outline-none"
            >
              <i class="fa-solid fa-bars text-sm"></i>
              <span>DANH MỤC</span>
            </button>
          </div>
        </div>

        <!-- Header Bottom: Thanh Danh Mục Trên Máy Tính (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, không đứt chữ) -->
        <div class="header-bottom hidden lg:block bg-vbBlue text-white border-t border-vbBlueLight">
          <div class="container-95 py-1">
            <nav aria-label="Danh mục chính">
              <ul class="nav-cat-list">
                <li>
                  <a href="#wrapper" class="nav-cat-item text-amber-300">
                    <i class="fa-solid fa-house mr-1"></i>TRANG CHỦ
                  </a>
                </li>
                <li>
                  <a href="#gioi-thieu" class="nav-cat-item">GIỚI THIỆU</a>
                </li>
                <!-- Danh mục lấy từ web mẫu tintruongthinh.com -->
                <li class="has-dropdown relative">
                  <a href="#cong-trinh-thuc-te" class="nav-cat-item inline-flex items-center gap-1">
                    <span>CÔNG TRÌNH THỰC TẾ</span>
                    <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                  </a>
                  <ul class="ux-dropdown absolute left-0 top-full mt-1 w-60 bg-white text-slate-800 rounded-lg shadow-xl border border-slate-200 py-1.5 text-xs font-medium">
                    <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san')" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a></li>
                    <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Biệt thự</a></li>
                    <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Nhà phố</a></li>
                    <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Văn phòng</a></li>
                  </ul>
                </li>
                <li>
                  <a href="#du-an-da-nang" class="nav-cat-item">DỰ ÁN TẠI ĐÀ NẴNG</a>
                </li>
                <li class="has-dropdown relative">
                  <a href="#linh-vuc-hoat-dong" class="nav-cat-item inline-flex items-center gap-1">
                    <span>LĨNH VỰC HOẠT ĐỘNG</span>
                    <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                  </a>
                  <ul class="ux-dropdown absolute left-0 top-full mt-1 w-56 bg-white text-slate-800 rounded-lg shadow-xl border border-slate-200 py-1.5 text-xs font-medium">
                    <li><a href="#linh-vuc-hoat-dong" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a></li>
                    <li><a href="#linh-vuc-hoat-dong" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Thi công phần thô</a></li>
                    <li><a href="#linh-vuc-hoat-dong" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Thi công hoàn thiện</a></li>
                    <li><a href="#linh-vuc-hoat-dong" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Thi công nội thất</a></li>
                  </ul>
                </li>
                <li class="has-dropdown relative">
                  <a href="#mau-thiet-ke" class="nav-cat-item inline-flex items-center gap-1">
                    <span>MẪU THIẾT KẾ</span>
                    <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                  </a>
                  <ul class="ux-dropdown absolute left-0 top-full mt-1 w-52 bg-white text-slate-800 rounded-lg shadow-xl border border-slate-200 py-1.5 text-xs font-medium">
                    <li><a href="#mau-thiet-ke" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Mẫu thiết kế nhà phố</a></li>
                    <li><a href="#mau-thiet-ke" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Mẫu thiết kế biệt thự</a></li>
                    <li><a href="#mau-thiet-ke" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Mẫu thiết kế nội thất</a></li>
                  </ul>
                </li>
                <li class="has-dropdown relative">
                  <a href="#bang-bao-gia" class="nav-cat-item inline-flex items-center gap-1">
                    <span>BÁO GIÁ</span>
                    <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
                  </a>
                  <ul class="ux-dropdown absolute left-0 top-full mt-1 w-56 bg-white text-slate-800 rounded-lg shadow-xl border border-slate-200 py-1.5 text-xs font-medium">
                    <li><a href="#bang-bao-gia" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Báo giá thiết kế kiến trúc</a></li>
                    <li><a href="#bang-bao-gia" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Báo giá thi công phần thô</a></li>
                    <li><a href="#bang-bao-gia" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Báo giá thi công hoàn thiện</a></li>
                    <li><a href="#bang-bao-gia" class="block px-3.5 py-2 hover:bg-slate-100 hover:text-vbBlue whitespace-nowrap">Báo giá thi công trọn gói</a></li>
                  </ul>
                </li>
                <li>
                  <a href="#doi-tac" class="nav-cat-item">ĐỐI TÁC</a>
                </li>
                <li>
                  <a href="#tin-tuc" class="nav-cat-item">TIN TỨC</a>
                </li>
                <li>
                  <a href="#lien-he-ban-do" class="nav-cat-item">LIÊN HỆ</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>

        <!-- Thanh danh mục rút gọn hiển thị trên Điện Thoại (2 hàng gọn đẹp, không tràn viền) -->
        <div class="lg:hidden bg-vbBlue text-white border-t border-vbBlueLight px-2 py-1.5">
          <div class="flex flex-wrap items-center justify-center gap-1">
            <a href="#cong-trinh-thuc-te" class="px-2 py-1 rounded bg-white/10 text-[11px] font-semibold whitespace-nowrap">Công Trình Thực Tế</a>
            <a href="#du-an-da-nang" class="px-2 py-1 rounded bg-white/10 text-[11px] font-semibold whitespace-nowrap">Dự Án Đà Nẵng</a>
            <a href="#linh-vuc-hoat-dong" class="px-2 py-1 rounded bg-white/10 text-[11px] font-semibold whitespace-nowrap">Lĩnh Vực</a>
            <a href="#bang-bao-gia" class="px-2 py-1 rounded bg-white/10 text-[11px] font-semibold whitespace-nowrap">Báo Giá</a>
            <a href="#doi-tac" class="px-2 py-1 rounded bg-white/10 text-[11px] font-semibold whitespace-nowrap">Đối Tác</a>
            <a href="#form-bao-gia" class="px-2 py-1 rounded bg-vbGold text-white text-[11px] font-semibold whitespace-nowrap">Tư Vấn</a>
          </div>
        </div>
      </div>

      <!-- Menu Drawer trên Điện thoại -->
      <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-xl">
        <div class="container-95 py-3">
          <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-slate-700">
            <a href="#wrapper" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-vbBlue whitespace-nowrap"><i class="fa-solid fa-house mr-1.5"></i>Trang chủ</a>
            <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-circle-info mr-1.5"></i>Giới thiệu</a>
            <a href="#cong-trinh-thuc-te" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-helmet-safety mr-1.5"></i>Công trình thực tế</a>
            <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-city mr-1.5"></i>Dự án Đà Nẵng</a>
            <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-layer-group mr-1.5"></i>Lĩnh vực hoạt động</a>
            <a href="#mau-thiet-ke" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-compass-drafting mr-1.5"></i>Mẫu thiết kế</a>
            <a href="#bang-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-file-invoice-dollar mr-1.5"></i>Báo giá xây dựng</a>
            <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-handshake mr-1.5"></i>Đối tác</a>
            <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-newspaper mr-1.5"></i>Tin tức</a>
            <a href="#lien-he-ban-do" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 hover:text-vbBlue whitespace-nowrap"><i class="fa-solid fa-map-location-dot mr-1.5"></i>Bản đồ & Liên hệ</a>
          </div>
          <!-- Danh mục con trên điện thoại -->
          <div class="mt-2.5 pt-2.5 border-t border-slate-200">
            <div class="text-[11px] font-bold text-vbBlue uppercase mb-1.5">Danh mục công trình & dịch vụ:</div>
            <div class="flex flex-wrap gap-1.5 text-[11px]">
              <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san'); toggleMobileMenu();" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Khách sạn - Căn hộ - Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu'); toggleMobileMenu();" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Biệt thự</a>
              <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho'); toggleMobileMenu();" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Nhà phố</a>
              <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong'); toggleMobileMenu();" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Văn phòng</a>
              <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Thi công phần thô</a>
              <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="px-2.5 py-1 rounded-full border border-slate-300 text-slate-700">Thi công trọn gói</a>
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- ================= MAIN CONTENT CHUẨN FLATSOME ================= -->
    <main id="main" class="w-full">

      <!-- ================= 1. SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU ================= -->
      <!-- Hình ảnh và chữ nằm gọn bên trong hết banner, chữ cách xa viền ảnh banner, không bị thiếu chữ trên ĐT & Máy tính -->
      <section class="section py-3 sm:py-4">
        <div class="container-95">
          <div class="ux-slider-wrapper relative w-full h-[270px] sm:h-[350px] md:h-[420px] lg:h-[470px] rounded-xl overflow-hidden shadow-lg bg-vbBlueDark">

            <!-- SLIDE 1 -->
            <div id="banner-slide-0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
              <img
                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1600"
                data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                alt="Banner Thiết Kế Thi Công Xây Dựng Việt Bách 1"
                class="w-full h-full object-cover object-center"
                onerror="handleDriveImgError(this, 'VIET BACH BANNER 1')"
              />
              <!-- Lớp phủ kiến trúc tối màu giúp chữ nổi bật tuyệt đối -->
              <div class="absolute inset-0 bg-gradient-to-r from-vbBlueDark/90 via-vbBlueDark/75 to-vbBlueDark/60"></div>

              <!-- Nội dung chữ cách xa viền ảnh banner (px-8 sm:px-14 md:px-20 lg:px-24 py-6) -->
              <div class="absolute inset-0 flex items-center justify-center px-8 sm:px-14 md:px-20 lg:px-28 py-6">
                <div class="w-full max-w-4xl text-center text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-1.5 sm:mb-2">
                    WEBSITE CHÍNH THỨC: VIETBACH.COM
                  </p>
                  <h1 class="text-sm sm:text-xl md:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-3 text-white drop-shadow">
                    CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-slate-100 max-w-2xl mx-auto leading-relaxed mb-3 sm:mb-5">
                    Chuyên Thiết Kế Kiến Trúc – Thi Công Xây Dựng Trọn Gói – Hoàn Thiện Nội Thất Khách Sạn, Biệt Thự, Nhà Phố, Căn Hộ & Văn Phòng tại Đà Nẵng.
                  </p>
                  <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3 text-[11px] sm:text-xs md:text-sm">
                    <span class="px-3 py-1.5 rounded-lg bg-vbGold text-white font-bold shadow">
                      <i class="fa-solid fa-phone mr-1"></i>Hotline: 0927.000.001
                    </span>
                    <span class="px-3 py-1.5 rounded-lg bg-white/15 backdrop-blur-sm border border-white/30 text-white font-medium">
                      <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng
                    </span>
                  </div>
                </div>
              </div>
            </div>

            <!-- SLIDE 2 (Kích thước bằng nhau 100% với Slide 1) -->
            <div id="banner-slide-1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none">
              <img
                src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                alt="Banner Thiết Kế Thi Công Xây Dựng Việt Bách 2"
                class="w-full h-full object-cover object-center"
                onerror="handleDriveImgError(this, 'VIET BACH BANNER 2')"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-slate-900/90 via-vbBlueDark/80 to-vbBlueDark/65"></div>

              <!-- Nội dung chữ cách xa viền ảnh banner -->
              <div class="absolute inset-0 flex items-center justify-center px-8 sm:px-14 md:px-20 lg:px-28 py-6">
                <div class="w-full max-w-4xl text-center text-white">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-300 mb-1.5 sm:mb-2">
                    AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – TỐI ƯU CHI PHÍ
                  </p>
                  <h2 class="text-sm sm:text-xl md:text-3xl lg:text-4xl font-extrabold leading-snug sm:leading-tight mb-2 sm:mb-3 text-white drop-shadow">
                    KIẾN TẠO CÔNG TRÌNH BỀN VỮNG TẠI ĐÀ NẴNG & MIỀN TRUNG
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-slate-100 max-w-2xl mx-auto leading-relaxed mb-3 sm:mb-5">
                    Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm thực chiến – Cam kết vật tư chính hãng, giám sát chặt chẽ và bảo hành dài hạn.
                  </p>
                  <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3 text-[11px] sm:text-xs md:text-sm">
                    <a href="#form-bao-gia" class="px-3.5 py-1.5 rounded-lg bg-vbGold hover:bg-amber-600 text-white font-bold shadow transition">
                      <i class="fa-solid fa-calculator mr-1"></i>Nhận Báo Giá Miễn Phí
                    </a>
                    <a href="#du-an-da-nang" class="px-3.5 py-1.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-medium transition">
                      <i class="fa-solid fa-eye mr-1"></i>Xem Dự Án Tại Đà Nẵng
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- Nút điều hướng trái / phải nằm gọn bên trong banner -->
            <button
              type="button"
              onclick="changeBannerSlide(-1)"
              aria-label="Banner trước"
              class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-vbGold text-white flex items-center justify-center transition"
            >
              <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
            </button>
            <button
              type="button"
              onclick="changeBannerSlide(1)"
              aria-label="Banner tiếp theo"
              class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-vbGold text-white flex items-center justify-center transition"
            >
              <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
            </button>

            <!-- Chấm tròn chỉ báo Slide -->
            <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
              <button type="button" onclick="goToBannerSlide(0)" id="banner-dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
              <button type="button" onclick="goToBannerSlide(1)" id="banner-dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 2. LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (GIỐNG MẪU TINTRUONGTHINH.COM) ================= -->
      <!-- Sản phẩm/dịch vụ chia 2 cột trên điện thoại, không để nhãn dán ở trang chủ -->
      <section id="linh-vuc-hoat-dong" class="section py-6 sm:py-8 bg-white border-y border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">LĨNH VỰC HOẠT ĐỘNG CHÍNH</h2>
            <span class="flatsome-title-line"></span>
          </div>
          <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
            Hệ thống danh mục dịch vụ chuẩn của <strong>Việt Bách (vietbach.com)</strong> đáp ứng trọn gói nhu cầu từ Tư vấn thiết kế đến Thi công hoàn thiện công trình.
          </p>

          <!-- Chia 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="row grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
            <!-- Dịch vụ 1 -->
            <div class="col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-200 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800"
                  data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
                  alt="Thiết kế Kiến trúc – Nội thất"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'THIET KE KIEN TRUC')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue mb-1">
                    Thiết Kế Kiến Trúc – Nội Thất
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Thiết kế bản vẽ kiến trúc, kết cấu, điện nước M&E và phối cảnh 3D nội ngoại thất nhà phố, biệt thự, khách sạn.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] sm:text-xs font-bold text-vbGold hover:underline">
                  <span>Yêu cầu tư vấn</span>
                  <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
              </div>
            </div>

            <!-- Dịch vụ 2 -->
            <div class="col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-200 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800"
                  data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                  alt="Thi công phần thô"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'THI CONG PHAN THO')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue mb-1">
                    Thi Công Phần Thô & Nhân Công Hoàn Thiện
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Thi công móng, khung bê tông cốt thép, xây tô tường đúng tiêu chuẩn kỹ thuật, đảm bảo kết cấu bền vững lâu dài.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] sm:text-xs font-bold text-vbGold hover:underline">
                  <span>Yêu cầu tư vấn</span>
                  <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
              </div>
            </div>

            <!-- Dịch vụ 3 -->
            <div class="col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-200 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
                  data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                  alt="Thi công hoàn thiện trọn gói"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'THI CONG HOAN THIEN')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue mb-1">
                    Thi Công Xây Nhà Trọn Gói – Chìa Khóa Trao Tay
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Giải pháp trọn gói từ xin phép xây dựng, thiết kế đến thi công hoàn thiện đồng bộ, cam kết không phát sinh chi phí.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] sm:text-xs font-bold text-vbGold hover:underline">
                  <span>Yêu cầu tư vấn</span>
                  <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
              </div>
            </div>

            <!-- Dịch vụ 4 -->
            <div class="col bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-200 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800"
                  data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                  alt="Thi công nội thất"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'THI CONG NOI THAT')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue mb-1">
                    Thiết Kế & Thi Công Hoàn Thiện Nội Thất
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Sản xuất và lắp đặt nội thất gỗ công nghiệp An Cường, gỗ tự nhiên cho phòng khách, bếp, phòng ngủ, văn phòng.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] sm:text-xs font-bold text-vbGold hover:underline">
                  <span>Yêu cầu tư vấn</span>
                  <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 3. GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH (THEO MẪU TINTRUONGTHINH.COM) ================= -->
      <section id="gioi-thieu" class="section py-7 sm:py-10 bg-slate-50">
        <div class="container-95">
          <div class="row grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-6 md:p-8 rounded-2xl border border-slate-200 shadow-sm">
            <div class="col lg:col-span-7">
              <div class="text-xs font-bold uppercase tracking-wider text-vbGold mb-1">
                VỀ CHÚNG TÔI • VIETBACH.COM
              </div>
              <h2 class="text-base sm:text-xl md:text-2xl font-extrabold text-vbBlue mb-3 leading-snug">
                CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH
              </h2>
              <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                <strong>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH</strong> chuyên Tư vấn Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất các công trình <strong>Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố</strong> và Hạ tầng kỹ thuật tại thành phố Đà Nẵng và khu vực miền Trung.
              </p>
              <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                Với phương châm <em>“An Toàn – Chất Lượng – Tiến Độ – Sự Hài Lòng Của Khách Hàng”</em>, Việt Bách luôn đặt chữ <strong>TÂM</strong> và chữ <strong>TÍN</strong> lên hàng đầu trong từng bản vẽ thiết kế, từng hạng mục đổ bê tông, xây trát và hoàn thiện công trình.
              </p>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs bg-slate-50 p-3.5 rounded-xl border border-slate-200">
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-location-dot text-vbGold mt-0.5"></i>
                  <span><strong>Địa chỉ:</strong> 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng</span>
                </div>
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-phone text-vbGold mt-0.5"></i>
                  <span><strong>Hotline:</strong> <a href="tel:0927000001" class="text-vbBlue font-bold">0927.000.001</a></span>
                </div>
                <div class="flex items-start gap-2">
                  <i class="fa-solid fa-globe text-vbGold mt-0.5"></i>
                  <span><strong>Website:</strong> vietbach.com</span>
                </div>
                <div class="flex items-start gap-2">
                  <i class="fa-brands fa-facebook text-vbGold mt-0.5"></i>
                  <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100057402851576" target="_blank" rel="noopener" class="text-vbBlue hover:underline">Xây Dựng Việt Bách</a></span>
                </div>
              </div>
            </div>

            <div class="col lg:col-span-5">
              <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3] bg-slate-100">
                <img
                  src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                  data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                  alt="Công trình tiêu biểu Công ty Xây Dựng Việt Bách"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'VIET BACH CONSTRUCTION')"
                />
              </div>
            </div>
          </div>

          <!-- 6 Thế mạnh của Việt Bách (Chia 2 cột trên điện thoại, 3 cột trên máy tính) -->
          <div class="mt-7">
            <div class="flatsome-title-wrap">
              <span class="flatsome-title-line"></span>
              <h3 class="flatsome-title-main text-sm sm:text-lg md:text-xl">THẾ MẠNH CỦA XÂY DỰNG VIỆT BÁCH</h3>
              <span class="flatsome-title-line"></span>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4">
              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-user-tie text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">1. Đội ngũ KTS, Kỹ sư chuyên nghiệp</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư giám sát hiện trường giàu kinh nghiệm và thợ lành nghề.</p>
              </div>

              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-compass-drafting text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">2. Cập nhật xu hướng kiến trúc hiện đại</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Tối ưu công năng thông gió, ánh sáng tự nhiên và ứng dụng vật liệu chống thấm bền bỉ cho khí hậu Đà Nẵng.</p>
              </div>

              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-calendar-check text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">3. Giám sát tiến độ chuẩn xác</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Báo cáo nhật ký thi công kèm hình ảnh thực tế hàng ngày để Chủ đầu tư dễ dàng theo dõi từ xa.</p>
              </div>

              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-shield-halved text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">4. Bảo hành công trình lâu dài</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Cam kết bảo hành kết cấu dài hạn và bảo trì hoàn thiện nhanh chóng theo phương châm “Gọi đâu có đó”.</p>
              </div>

              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-hand-holding-dollar text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">5. Chi phí hợp lý – Minh bạch vật tư</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Dự toán bóc tách rõ ràng từng hạng mục vật tư chính hãng, cân đối ngân sách hiệu quả nhất cho khách hàng.</p>
              </div>

              <div class="bg-white p-3.5 sm:p-4 rounded-xl border border-slate-200 shadow-sm">
                <div class="w-9 h-9 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center mb-2">
                  <i class="fa-solid fa-headset text-base"></i>
                </div>
                <h4 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1">6. Hỗ trợ tư vấn & khảo sát 24/7</h4>
                <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Khảo sát thực địa tại Đà Nẵng, tư vấn phương án thiết kế và thủ tục cấp phép xây dựng hoàn toàn miễn phí.</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 4. HÌNH ẢNH & SẢN PHẨM THI CÔNG THỰC TẾ (9 FILE GOOGLE DRIVE) ================= -->
      <!-- Chia 2 cột trên điện thoại, không để các nhãn dán ở trang chủ, tên sản phẩm không bị tràn hoặc thiếu chữ -->
      <section id="cong-trinh-thuc-te" class="section py-7 sm:py-10 bg-white border-t border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">HÌNH ẢNH & HẠNG MỤC THI CÔNG XÂY DỰNG THỰC TẾ</h2>
            <span class="flatsome-title-line"></span>
          </div>

          <!-- Bộ lọc danh mục nhỏ gọn viết liền trên 1 hàng -->
          <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-5">
            <button type="button" onclick="filterConstruction('all')" id="filter-btn-all" class="filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-vbBlue text-white">
              Tất cả hạng mục
            </button>
            <button type="button" onclick="filterConstruction('khach-san')" id="filter-btn-khach-san" class="filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-slate-200">
              Khách sạn – Căn hộ – Phòng trọ
            </button>
            <button type="button" onclick="filterConstruction('biet-thu')" id="filter-btn-biet-thu" class="filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-slate-200">
              Biệt thự
            </button>
            <button type="button" onclick="filterConstruction('nha-pho')" id="filter-btn-nha-pho" class="filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-slate-200">
              Nhà phố & Phần thô
            </button>
            <button type="button" onclick="filterConstruction('van-phong')" id="filter-btn-van-phong" class="filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-slate-200">
              Văn phòng & Nội thất
            </button>
          </div>

          <!-- Grid 9 ảnh thực tế thi công: 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính -->
          <div id="construction-grid" class="row grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">

            <!-- Ảnh thực tế 1: 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w900"
                  data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                  alt="Thi Công Phần Thô Và Kết Cấu Khung Bê Tông Cốt Thép Nhà Phố"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'THI CONG PHAN THO 01')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Thi công phần thô – Nhà phố</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Phần Thô & Kết Cấu Khung Bê Tông Cốt Thép Nhà Phố Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 2: 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                  data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                  alt="Thi Công Xây Dựng Trọn Gói Biệt Thự Phố Hiện Đại 3 Tầng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'BIET THU HIEN DAI 02')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Biệt thự – Thi công trọn gói</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Xây Dựng Trọn Gói Biệt Thự Phố Hiện Đại 3 Tầng Tại Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 3: 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w900"
                  data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                  alt="Thi Công Khách Sạn Và Căn Hộ Cho Thuê Cao Tầng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'KHACH SAN CAN HO 03')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thiết Kế & Thi Công Tòa Nhà Khách Sạn – Căn Hộ Dịch Vụ Cho Thuê
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 4: 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w900"
                  data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                  alt="Thi Công Hoàn Thiện Mặt Tiền Nhà Phố Hiện Đại"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'HOAN THIEN NHA PHO 04')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Nhà phố – Thi công hoàn thiện</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Hoàn Thiện Kiến Trúc Mặt Tiền Nhà Phố Hiện Đại Lệch Tầng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 5: 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w900"
                  data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                  alt="Thi Công Móng Băng Và Cốt Thép Sàn Công Trình Dân Dụng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'KET CAU MONG SAN 05')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Thi công phần thô – Kết cấu</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Lắp Đặt Cốt Thép Móng & Đổ Bê Tông Sàn Công Trình Dân Dụng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 6: 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w900"
                  data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                  alt="Thi Công Hoàn Thiện Nội Thất Phòng Khách Và Phòng Bếp"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'HOAN THIEN NOI THAT 06')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Thi công nội thất hoàn thiện</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Hoàn Thiện Không Gian Nội Thất Phòng Khách – Bếp Cao Cấp
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 7: 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900"
                  data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                  alt="Thi Công Tòa Nhà Văn Phòng Công Ty Kết Hợp Kinh Doanh"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'TOA NHA VAN PHONG 07')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Văn phòng – Tòa nhà thương mại</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thiết Kế & Thi Công Xây Dựng Tòa Nhà Văn Phòng Kết Hợp Kinh Doanh
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 8: 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w900"
                  data-drive-id="1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT"
                  alt="Thi Công Căn Hộ Cho Thuê Và Phòng Trọ Cao Cấp"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'CAN HO CHO THUE 08')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Khách sạn – Căn hộ – Phòng trọ</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thi Công Hoàn Thiện Căn Hộ Cho Thuê & Homestay Nghỉ Dưỡng Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

            <!-- Ảnh thực tế 9: 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
            <div class="col construction-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w900"
                  data-drive-id="1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn"
                  alt="Thiết Kế Kiến Trúc Và Thi Công Biệt Thự Sân Vườn"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'BIET THU SAN VUON 09')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 font-medium mb-1">Danh mục: Biệt thự – Thiết kế & Thi công</div>
                  <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-bold text-vbBlue">
                    Thiết Kế Kiến Trúc & Thi Công Hoàn Thiện Biệt Thự Sân Vườn Sang Trọng
                  </h3>
                </div>
                <div class="mt-2 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs">
                  <span class="text-vbGold font-bold">Việt Bách Thi Công</span>
                  <a href="#form-bao-gia" class="text-vbBlue font-semibold hover:underline">Báo giá</a>
                </div>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- ================= 5. DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG VÀO TRANG CHỦ (10 FILE GOOGLE DRIVE) ================= -->
      <!-- Chia 2 cột trên điện thoại, không để các nhãn dán ở trang chủ, tên dự án đầy đủ không bị thiếu chữ -->
      <section id="du-an-da-nang" class="section py-7 sm:py-10 bg-slate-50 border-t border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">DANH MỤC CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
            <span class="flatsome-title-line"></span>
          </div>
          <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
            Tổng hợp các dự án Nhà phố, Biệt thự, Khách sạn – Căn hộ và Văn phòng do <strong>Công Ty TNHH Tư Vấn Thiết Kế Và Xây Dựng Việt Bách</strong> triển khai tại Đà Nẵng.
          </p>

          <!-- Chia 2 cột trên điện thoại (grid-cols-2), 5 cột trên màn hình lớn -->
          <div class="row grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">

            <!-- Dự án Đà Nẵng 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                  data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                  alt="Dự Án Nhà Phố Hiện Đại Nguyễn Tất Thành – Thanh Khê, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 01')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Thanh Khê, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Nhà Phố Hiện Đại 3 Tầng Nguyễn Tất Thành – Thanh Khê, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế & Thi công trọn gói
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                  data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                  alt="Dự Án Căn Hộ Cho Thuê Và Khách Sạn Sơn Trà, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 02')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Sơn Trà, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Tổ Hợp Căn Hộ Cho Thuê & Khách Sạn Biển Sơn Trà, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế & Thi công trọn gói
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800"
                  data-drive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                  alt="Dự Án Biệt Thự Khu Đô Thị Hòa Xuân, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 03')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">KĐT Hòa Xuân, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Biệt Thự Nghỉ Dưỡng Sinh Thái Khu Đô Thị Hòa Xuân, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế & Thi công hoàn thiện
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800"
                  data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k"
                  alt="Dự Án Tòa Nhà Văn Phòng Liên Chiểu, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 04')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Liên Chiểu, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Tòa Nhà Văn Phòng & Showroom Thương Mại Liên Chiểu, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thi công kết cấu & Hoàn thiện
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800"
                  data-drive-id="1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N"
                  alt="Dự Án Nhà Phố 2 Mặt Tiền Khu Nam Việt Á, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 05')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Ngũ Hành Sơn, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Nhà Phố 2 Mặt Tiền Khu Đô Thị Nam Việt Á – Ngũ Hành Sơn, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế & Thi công trọn gói
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800"
                  data-drive-id="1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML"
                  alt="Dự Án Căn Hộ Dịch Vụ Cao Cấp Hải Châu, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 06')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Hải Châu, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Căn Hộ Dịch Vụ Cao Cấp View Sông Hàn – Hải Châu, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thi công trọn gói & Nội thất
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800"
                  data-drive-id="1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF"
                  alt="Dự Án Biệt Thự Hiện Đại Khu Đô Thị FPT City, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 07')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">KĐT FPT City, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Biệt Thự Phố Hiện Đại Khu Đô Thị FPT City – Ngũ Hành Sơn, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế kiến trúc & Thi công
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800"
                  data-drive-id="1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A"
                  alt="Dự Án Nhà Phố Gia Đình Quận Cẩm Lệ, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 08')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Cẩm Lệ, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Thiết Kế & Thi Công Trọn Gói Nhà Phố Gia Đình Cẩm Lệ, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Xây nhà trọn gói chìa khóa trao tay
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800"
                  data-drive-id="1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80"
                  alt="Dự Án Hoàn Thiện Nội Thất Biệt Thự Euro Village, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 09')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Euro Village, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Cải Tạo & Hoàn Thiện Nội Thất Biệt Thự Euro Village, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Hoàn thiện & Nội thất cao cấp
                </div>
              </div>
            </div>

            <!-- Dự án Đà Nẵng 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
            <div class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800"
                  data-drive-id="1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4"
                  alt="Dự Án Khu Phức Hợp Văn Phòng Và Nhà Ở Thanh Khê, Đà Nẵng"
                  class="w-full h-full object-cover hover:scale-105 transition duration-500"
                  onerror="handleDriveImgError(this, 'DU AN DA NANG 10')"
                />
              </div>
              <div class="box-text p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                <div>
                  <div class="text-[11px] text-slate-500 mb-0.5">Quận Thanh Khê, Đà Nẵng</div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">
                    Dự Án Khu Phức Hợp Thương Mại & Văn Phòng Thanh Khê, Đà Nẵng
                  </h3>
                </div>
                <div class="mt-2 pt-1.5 border-t border-slate-100 text-[11px] text-vbGold font-semibold">
                  Thiết kế & Giám sát thi công
                </div>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- ================= 6. MẪU THIẾT KẾ & BẢNG BÁO GIÁ (THEO MẪU TINTRUONGTHINH.COM) ================= -->
      <!-- Chia 2 cột trên điện thoại, không để các nhãn dán ở trang chủ -->
      <section id="mau-thiet-ke" class="section py-7 sm:py-10 bg-white border-t border-slate-200">
        <div class="container-95">
          <div id="bang-bao-gia" class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">MẪU THIẾT KẾ & BÁO GIÁ XÂY DỰNG VIỆT BÁCH</h2>
            <span class="flatsome-title-line"></span>
          </div>
          <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
            Đơn giá tham khảo chuẩn kỹ thuật tại Đà Nẵng. Liên hệ Hotline <strong>0927.000.001</strong> để nhận bảng bóc tách khối lượng chi tiết theo diện tích thực tế.
          </p>

          <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="row grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-extrabold text-vbBlue mb-1.5">
                  Báo Giá Thiết Kế Kiến Trúc & Nội Thất
                </h3>
                <div class="text-sm sm:text-lg font-extrabold text-vbGold mb-2">
                  120.000đ – 180.000đ/m²
                </div>
                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                  <li>• Hồ sơ bản vẽ kiến trúc & phối cảnh 3D mặt tiền</li>
                  <li>• Hồ sơ kết cấu, điện nước M&E chi tiết</li>
                  <li>• Bản vẽ xin phép xây dựng tại Đà Nẵng</li>
                  <li>• Giảm 50% - 100% phí thiết kế khi thi công trọn gói</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-vbBlue text-white text-xs font-bold hover:bg-vbBlueDark transition">
                Nhận Báo Giá Thiết Kế
              </a>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-extrabold text-vbBlue mb-1.5">
                  Báo Giá Thi Công Phần Thô & Nhân Công
                </h3>
                <div class="text-sm sm:text-lg font-extrabold text-vbGold mb-2">
                  3.500.000đ – 3.900.000đ/m²
                </div>
                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                  <li>• Vật tư phần thô chuẩn: Thép Hòa Phát, Xi măng Hà Tiên/Sông Gianh</li>
                  <li>• Thi công móng, dầm, sàn, cột bê tông cốt thép</li>
                  <li>• Xây tô tường trong ngoài, lắp đặt hệ thống điện nước âm</li>
                  <li>• Bảo hành kết cấu công trình dài hạn</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-vbBlue text-white text-xs font-bold hover:bg-vbBlueDark transition">
                Nhận Báo Giá Phần Thô
              </a>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-extrabold text-vbBlue mb-1.5">
                  Báo Giá Thi Công Hoàn Thiện Công Trình
                </h3>
                <div class="text-sm sm:text-lg font-extrabold text-vbGold mb-2">
                  2.200.000đ – 3.200.000đ/m²
                </div>
                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                  <li>• Ốp lát gạch nền, gạch tường, đá cầu thang</li>
                  <li>• Sơn nước bả matit trong ngoài chống thấm</li>
                  <li>• Lắp đặt cửa nhôm Xingfa, lan can, trần thạch cao</li>
                  <li>• Lắp đặt thiết bị vệ sinh, đèn chiếu sáng hoàn chỉnh</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-vbBlue text-white text-xs font-bold hover:bg-vbBlueDark transition">
                Nhận Báo Giá Hoàn Thiện
              </a>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <h3 class="product-title-safe text-xs sm:text-sm md:text-base font-extrabold text-vbBlue mb-1.5">
                  Báo Giá Xây Nhà Trọn Gói – Chìa Khóa Trao Tay
                </h3>
                <div class="text-sm sm:text-lg font-extrabold text-vbGold mb-2">
                  5.600.000đ – 7.200.000đ/m²
                </div>
                <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5">
                  <li>• Trọn gói từ xin phép xây dựng, thiết kế 3D đến hoàn thiện</li>
                  <li>• Cam kết đúng chủng loại vật tư trong hợp đồng</li>
                  <li>• Giám sát kỹ thuật trực tiếp tại công trình Đà Nẵng</li>
                  <li>• Bàn giao nhà sạch đẹp đúng tiến độ cam kết</li>
                </ul>
              </div>
              <a href="#form-bao-gia" class="mt-3 block text-center py-2 px-3 rounded-lg bg-vbGold text-white text-xs font-bold hover:bg-amber-600 transition">
                Đăng Ký Trọn Gói
              </a>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 7. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ================= -->
      <section id="form-bao-gia" class="section py-8 sm:py-10 bg-vbBlue text-white">
        <div class="container-95">
          <div class="row grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
            <!-- Cột thông tin hỗ trợ -->
            <div class="col lg:col-span-5">
              <div class="text-xs font-bold uppercase tracking-wider text-amber-300 mb-1">
                MIỄN PHÍ TƯ VẤN & KHẢO SÁT TẠI ĐÀ NẴNG
              </div>
              <h2 class="text-lg sm:text-2xl font-extrabold text-white mb-3 leading-snug">
                ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ XÂY DỰNG
              </h2>
              <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-4">
                Quý khách hàng có nhu cầu Thiết kế kiến trúc, Thi công phần thô, Xây nhà trọn gói hoặc Hoàn thiện nội thất tại Đà Nẵng vui lòng điền thông tin bên cạnh. Kỹ sư trưởng của <strong>Việt Bách</strong> sẽ liên hệ tư vấn và gửi bảng dự toán chi tiết trong vòng 15 phút.
              </p>
              <div class="space-y-2.5 text-xs sm:text-sm bg-white/10 p-4 rounded-xl border border-white/15">
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-phone-volume text-amber-300 text-base"></i>
                  <span><strong>Hotline / Zalo 24/7:</strong> <a href="tel:0927000001" class="text-amber-300 font-extrabold">0927.000.001</a></span>
                </div>
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-location-dot text-amber-300 text-base"></i>
                  <span><strong>Văn phòng:</strong> 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng</span>
                </div>
                <div class="flex items-center gap-2.5">
                  <i class="fa-solid fa-globe text-amber-300 text-base"></i>
                  <span><strong>Website:</strong> vietbach.com</span>
                </div>
              </div>
            </div>

            <!-- Cột Form Yêu Cầu & Báo Giá (Giống cấu trúc form tintruongthinh.com) -->
            <div class="col lg:col-span-7">
              <div class="bg-white text-slate-800 rounded-2xl p-4 sm:p-6 shadow-xl border border-slate-200">
                <h3 class="text-sm sm:text-base font-extrabold text-vbBlue uppercase mb-3 border-b border-slate-200 pb-2">
                  <i class="fa-solid fa-file-signature text-vbGold mr-1.5"></i>FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH
                </h3>

                <form id="quote-request-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                  <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                    <div>
                      <label for="customerName" class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                      <input
                        id="customerName"
                        type="text"
                        required
                        placeholder="Nhập họ và tên của bạn"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-vbBlue"
                      />
                    </div>
                    <div>
                      <label for="customerPhone" class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại liên hệ *</label>
                      <input
                        id="customerPhone"
                        type="tel"
                        required
                        placeholder="Ví dụ: 0927.000.001"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-vbBlue"
                      />
                    </div>
                  </div>

                  <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                    <div>
                      <label for="projectType" class="block text-xs font-bold text-slate-700 mb-1">Loại công trình cần tư vấn</label>
                      <select
                        id="projectType"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-vbBlue"
                      >
                        <option value="Nhà phố">Nhà phố (Thiết kế & Thi công)</option>
                        <option value="Biệt thự">Biệt thự phố / Biệt thự nghỉ dưỡng</option>
                        <option value="Khách sạn – Căn hộ – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                        <option value="Văn phòng">Tòa nhà Văn phòng / Showroom</option>
                        <option value="Thi công phần thô">Thi công phần thô & Nhân công</option>
                        <option value="Thi công nội thất">Thiết kế & Thi công nội thất</option>
                        <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa – Chống thấm</option>
                      </select>
                    </div>
                    <div>
                      <label for="budgetLevel" class="block text-xs font-bold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                      <select
                        id="budgetLevel"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:outline-none focus:border-vbBlue"
                      >
                        <option value="Chưa xác định">Chưa xác định (Cần tư vấn dự toán)</option>
                        <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                        <option value="1 - 2 tỷ">Từ 1 tỷ – 2 tỷ</option>
                        <option value="2 - 3 tỷ">Từ 2 tỷ – 3 tỷ</option>
                        <option value="3 - 5 tỷ">Từ 3 tỷ – 5 tỷ</option>
                        <option value="Trên 5 tỷ">Trên 5 tỷ</option>
                      </select>
                    </div>
                  </div>

                  <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                    <div>
                      <label for="customerEmail" class="block text-xs font-bold text-slate-700 mb-1">Email (Nếu có)</label>
                      <input
                        id="customerEmail"
                        type="email"
                        placeholder="Nhập địa chỉ email"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-vbBlue"
                      />
                    </div>
                    <div>
                      <label for="projectArea" class="block text-xs font-bold text-slate-700 mb-1">Khu vực & Diện tích đất (m²)</label>
                      <input
                        id="projectArea"
                        type="text"
                        placeholder="VD: Thanh Khê, Đà Nẵng - 5x20m (3 tầng)"
                        class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-vbBlue"
                      />
                    </div>
                  </div>

                  <div>
                    <label for="projectNote" class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
                    <textarea
                      id="projectNote"
                      rows="2"
                      placeholder="Nhập yêu cầu về số tầng, công năng mong muốn hoặc thời gian dự kiến khởi công..."
                      class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs sm:text-sm focus:outline-none focus:border-vbBlue"
                    ></textarea>
                  </div>

                  <button
                    type="submit"
                    class="w-full py-2.5 px-4 rounded-lg bg-vbGold hover:bg-amber-600 text-white font-extrabold text-xs sm:text-sm uppercase tracking-wide shadow transition"
                  >
                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                  </button>
                </form>

                <!-- Hộp thông báo kết quả gửi form (Không dùng alert) -->
                <div id="quote-form-message" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs"></div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 8. DANH MỤC CÁC ĐỐI TÁC (ĐỐI TÁC & VẬT TƯ CHÍNH HÃNG) ================= -->
      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <section id="doi-tac" class="section py-7 sm:py-9 bg-white border-t border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">ĐỐI TÁC & NHÀ CUNG CẤP VẬT TƯ ĐỒNG HÀNH</h2>
            <span class="flatsome-title-line"></span>
          </div>
          <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-5">
            <strong>Xây Dựng Việt Bách</strong> hợp tác trực tiếp với các thương hiệu vật liệu xây dựng & nội thất uy tín hàng đầu nhằm đảm bảo chất lượng bền vững cho mọi công trình.
          </p>

          <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="row grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-4 gap-3 sm:gap-4">
            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">HP</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Thép Xây Dựng Hòa Phát</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác cung ứng thép kết cấu chính hãng</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">HT</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Xi Măng Hà Tiên & Sông Gianh</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác bê tông & xi măng tiêu chuẩn cao</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">DL</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Sơn Dulux & Jotun Chính Hãng</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác sơn ngoại thất & chống thấm miền Trung</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">AC</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Gỗ Công Nghiệp An Cường</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác vật liệu nội thất cao cấp</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">PN</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Thiết Bị Điện Panasonic & Cadivi</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác hệ thống cơ điện M&E an toàn</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">IN</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Thiết Bị Vệ Sinh Inax & Toto</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác thiết bị phòng tắm chính hãng</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">XF</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Hệ Nhôm Kính Xingfa Quảng Đông</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác hệ cửa nhôm kính cường lực</p>
            </div>

            <div class="col bg-slate-50 rounded-xl border border-slate-200 p-3.5 text-center hover:border-vbBlue transition">
              <div class="w-10 h-10 mx-auto mb-2 rounded-lg bg-vbBlue/10 text-vbBlue flex items-center justify-center font-extrabold text-sm">ĐT</div>
              <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue">Gạch Ốp Lát Đồng Tâm & Vietceramics</h3>
              <p class="text-[11px] text-slate-500 mt-0.5">Đối tác gạch đá hoàn thiện công trình</p>
            </div>
          </div>
        </div>
      </section>

      <!-- ================= 9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG) ================= -->
      <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
      <section id="tin-tuc" class="section py-7 sm:py-10 bg-slate-50 border-t border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">TIN TỨC & KINH NGHIỆM XÂY DỰNG</h2>
            <span class="flatsome-title-line"></span>
          </div>

          <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="row grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
            <!-- Bài viết 1 -->
            <article class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w700"
                  data-drive-id="1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO"
                  alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng cách"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'BAO DUONG BE TONG')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1.5">
                    Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Quy Chuẩn Kỹ Thuật
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Trong quá trình thi công xây dựng, bảo dưỡng bê tông móng và sàn đúng độ ẩm giúp công trình đạt cường độ chịu lực tối đa và hạn chế nứt sàn.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] font-bold text-vbGold hover:underline">
                  Xem chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
              </div>
            </article>

            <!-- Bài viết 2 -->
            <article class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w700"
                  data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                  alt="03 Nỗi lo lớn nhất khi xây nhà mà Chủ đầu tư thường gặp"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'KINH NGHIEM XAY NHA')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1.5">
                    03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Cần Lưu Ý Tại Đà Nẵng
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Cách kiểm soát chi phí phát sinh, lựa chọn vật tư phần thô chất lượng và giám sát tiến độ thi công hiệu quả khi xây nhà trọn gói.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] font-bold text-vbGold hover:underline">
                  Xem chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
              </div>
            </article>

            <!-- Bài viết 3 -->
            <article class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w700"
                  data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                  alt="Thiết kế nội thất là gì và tầm quan trọng đối với không gian sống"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'THIET KE NOI THAT')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1.5">
                    Thiết Kế Nội Thất Là Gì? Giải Pháp Tối Ưu Không Gian Nhà Phố & Căn Hộ
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Sự kết hợp hài hòa giữa kiến trúc, ánh sáng và vật liệu nội thất giúp nâng tầm tiện nghi sử dụng và giá trị thẩm mỹ cho ngôi nhà.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] font-bold text-vbGold hover:underline">
                  Xem chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
              </div>
            </article>

            <!-- Bài viết 4 -->
            <article class="col bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
              <div class="box-image aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w700"
                  data-drive-id="1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF"
                  alt="Quy trình xin giấy phép xây dựng tại Đà Nẵng"
                  class="w-full h-full object-cover"
                  onerror="handleDriveImgError(this, 'GIAY PHEP XAY DUNG')"
                />
              </div>
              <div class="box-text p-3 sm:p-4 flex-1 flex flex-col justify-between">
                <div>
                  <h3 class="product-title-safe text-xs sm:text-sm font-bold text-vbBlue mb-1.5">
                    Hồ Sơ Xin Phép Xây Dựng & Quy Trình Thi Công Nhà Ở Tại Đà Nẵng
                  </h3>
                  <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                    Tổng hợp đầy đủ các giấy tờ pháp lý, quy chuẩn lùi xây dựng, chiều cao tầng và quy trình thẩm tra thiết kế tại Đà Nẵng.
                  </p>
                </div>
                <a href="#form-bao-gia" class="mt-2.5 inline-flex items-center text-[11px] font-bold text-vbGold hover:underline">
                  Xem chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
              </div>
            </article>
          </div>
        </div>
      </section>

      <!-- ================= 10. ĐƯA ẢNH GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ ================= -->
      <section id="lien-he-ban-do" class="section py-7 sm:py-10 bg-white border-t border-slate-200">
        <div class="container-95">
          <div class="flatsome-title-wrap">
            <span class="flatsome-title-line"></span>
            <h2 class="flatsome-title-main text-base sm:text-xl md:text-2xl">BẢN ĐỒ GOOGLE MAPS & FANPAGE TRÊN TRANG CHỦ</h2>
            <span class="flatsome-title-line"></span>
          </div>

          <div class="row grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
            <!-- Cột Google Map ngoài trang chủ: 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng -->
            <div class="col lg:col-span-7 bg-slate-50 rounded-2xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <div class="flex flex-wrap items-center justify-between gap-2 mb-3">
                  <div>
                    <h3 class="text-sm sm:text-base font-extrabold text-vbBlue">
                      <i class="fa-solid fa-map-location-dot text-vbGold mr-1.5"></i>VỊ TRÍ TRÊN GOOGLE MAPS
                    </h3>
                    <p class="text-xs text-slate-600 mt-0.5">
                      Địa chỉ: <strong>1169 Nguyễn Tất Thành, Quận Thanh Khê, TP. Đà Nẵng</strong>
                    </p>
                  </div>
                  <a
                    href="https://www.google.com/maps/search/?api=1&query=1169+Nguyen+Tat+Thanh+Thanh+Khe+Da+Nang"
                    target="_blank"
                    rel="noopener"
                    class="px-3 py-1.5 rounded-lg bg-vbBlue text-white text-xs font-semibold hover:bg-vbBlueDark transition"
                  >
                    <i class="fa-solid fa-diamond-turn-right mr-1"></i>Chỉ đường Google Maps
                  </a>
                </div>

                <!-- Bản đồ Google Maps nhúng trực tiếp ra ngoài trang chủ -->
                <div class="w-full h-[260px] sm:h-[320px] rounded-xl overflow-hidden border border-slate-300 bg-slate-200">
                  <iframe
                    title="Bản đồ 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng"
                    src="https://maps.google.com/maps?q=1169%20Nguy%E1%BB%85n%20T%E1%BA%A5t%20Th%C3%A0nh,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                    class="w-full h-full border-0"
                    loading="lazy"
                    referrerpolicy="no-referrer-when-downgrade"
                  ></iframe>
                </div>
              </div>

              <div class="mt-3 pt-3 border-t border-slate-200 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-700">
                <span><i class="fa-solid fa-location-crosshairs text-vbGold mr-1"></i>Tuyến đường biển Nguyễn Tất Thành, Quận Thanh Khê, TP. Đà Nẵng</span>
                <span class="font-bold text-vbBlue">Hotline: 0927.000.001</span>
              </div>
            </div>

            <!-- Cột Fanpage Facebook đưa ra ngoài trang chủ -->
            <div class="col lg:col-span-5 bg-slate-50 rounded-2xl border border-slate-200 p-3.5 sm:p-5 flex flex-col justify-between shadow-sm">
              <div>
                <div class="flex items-center justify-between gap-2 mb-3">
                  <div>
                    <h3 class="text-sm sm:text-base font-extrabold text-vbBlue">
                      <i class="fa-brands fa-facebook text-blue-600 mr-1.5"></i>FANPAGE FACEBOOK CHÍNH THỨC
                    </h3>
                    <p class="text-xs text-slate-600 mt-0.5">
                      Kết nối trực tiếp qua Fanpage Công Ty Xây Dựng Việt Bách
                    </p>
                  </div>
                </div>

                <!-- Khung hiển thị Fanpage trực quan + Plugin Facebook ngoài trang chủ -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm">
                  <!-- Ảnh bìa & Logo Fanpage -->
                  <div class="relative h-28 bg-vbBlueDark overflow-hidden">
                    <img
                      src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                      data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                      alt="Ảnh bìa Fanpage Việt Bách"
                      class="w-full h-full object-cover opacity-65"
                      onerror="handleDriveImgError(this, 'FANPAGE VIET BACH')"
                    />
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                    <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                      <div class="w-12 h-12 rounded-lg bg-white p-1 shadow border border-slate-200 shrink-0">
                        <img
                          src="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w200"
                          data-drive-id="1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf"
                          alt="Logo Fanpage Việt Bách"
                          class="w-full h-full object-contain"
                          onerror="handleDriveImgError(this, 'VB')"
                        />
                      </div>
                      <div class="text-white min-w-0">
                        <a
                          href="https://www.facebook.com/profile.php?id=100057402851576"
                          target="_blank"
                          rel="noopener"
                          class="font-bold text-xs sm:text-sm hover:underline block truncate"
                        >
                          CÔNG TY TNHH TV TK & XD VIỆT BÁCH
                        </a>
                        <span class="text-[11px] text-slate-200 block">Thiết Kế & Thi Công Xây Dựng Đà Nẵng</span>
                      </div>
                    </div>
                  </div>

                  <!-- Nhúng Facebook Page Plugin + Nút tương tác trực tiếp -->
                  <div class="p-3">
                    <div class="w-full overflow-hidden rounded-lg border border-slate-100 bg-slate-50 mb-3 flex justify-center">
                      <iframe
                        title="Fanpage Xây Dựng Việt Bách"
                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100057402851576&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                        width="340"
                        height="180"
                        style="border:none;overflow:hidden;max-width:100%;"
                        scrolling="no"
                        frameborder="0"
                        allowfullscreen="true"
                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                      ></iframe>
                    </div>

                    <div class="grid grid-cols-2 gap-2 text-xs">
                      <a
                        href="https://www.facebook.com/profile.php?id=100057402851576"
                        target="_blank"
                        rel="noopener"
                        class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-center transition"
                      >
                        <i class="fa-brands fa-facebook-f mr-1"></i>Xem Fanpage
                      </a>
                      <a
                        href="https://www.facebook.com/profile.php?id=100057402851576"
                        target="_blank"
                        rel="noopener"
                        class="py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-vbBlue font-bold text-center transition"
                      >
                        <i class="fa-brands fa-facebook-messenger mr-1"></i>Nhắn Tin Ngay
                      </a>
                    </div>
                  </div>
                </div>
              </div>

              <div class="mt-3 pt-3 border-t border-slate-200 text-xs text-slate-600 flex items-center justify-between">
                <span>Cập nhật hình ảnh công trình mới nhất trên Fanpage</span>
                <a href="https://www.facebook.com/profile.php?id=100057402851576" target="_blank" rel="noopener" class="text-blue-600 font-bold hover:underline">Theo dõi</a>
              </div>
            </div>
          </div>
        </div>
      </section>

    </main>

    <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
    <footer id="footer" class="bg-vbBlueDark text-slate-200 pt-8 pb-6 border-t-4 border-vbGold">
      <div class="container-95">
        <div class="row grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">

          <!-- Cột 1: Thông tin công ty -->
          <div class="col lg:col-span-5">
            <div class="flex items-center gap-3 mb-3">
              <div class="w-11 h-11 rounded-lg bg-white p-1 shrink-0 flex items-center justify-center">
                <img
                  src="https://drive.google.com/thumbnail?id=1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf&sz=w300"
                  data-drive-id="1mZeiWTqscCstowqW2Ah4UCY12PbY-cpf"
                  alt="Logo Công Ty TNHH Tư Vấn Thiết Kế Và Xây Dựng Việt Bách"
                  class="w-full h-full object-contain"
                  onerror="handleDriveImgError(this, 'VB')"
                />
              </div>
              <div>
                <h3 class="text-xs sm:text-sm font-extrabold text-white leading-snug">
                  CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH
                </h3>
                <p class="text-[11px] text-amber-400 font-semibold">Website: vietbach.com</p>
              </div>
            </div>
            <ul class="space-y-2 text-xs text-slate-300">
              <li class="flex items-start gap-2">
                <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                <span><strong>Địa chỉ:</strong> 1169 Nguyễn Tất Thành, Quận Thanh Khê, TP. Đà Nẵng</span>
              </li>
              <li class="flex items-start gap-2">
                <i class="fa-solid fa-phone-volume text-amber-400 mt-1"></i>
                <span><strong>Số điện thoại / Hotline:</strong> <a href="tel:0927000001" class="text-amber-300 font-bold">0927.000.001</a></span>
              </li>
              <li class="flex items-start gap-2">
                <i class="fa-solid fa-globe text-amber-400 mt-1"></i>
                <span><strong>Website:</strong> <a href="https://vietbach.com" class="hover:underline">https://vietbach.com</a></span>
              </li>
              <li class="flex items-start gap-2">
                <i class="fa-brands fa-facebook text-amber-400 mt-1"></i>
                <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100057402851576" target="_blank" rel="noopener" class="hover:underline">facebook.com/profile.php?id=100057402851576</a></span>
              </li>
            </ul>
          </div>

          <!-- Cột 2: Lĩnh vực hoạt động & Công trình -->
          <div class="col lg:col-span-4">
            <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase mb-3 tracking-wide border-l-4 border-vbGold pl-2.5">
              DANH MỤC SẢN PHẨM & DỊCH VỤ
            </h4>
            <div class="grid grid-cols-2 gap-2 text-xs text-slate-300">
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Khách sạn – Căn hộ</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Thi công Biệt thự</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Thi công Nhà phố</a>
              <a href="#cong-trinh-thuc-te" class="hover:text-amber-300">• Thi công Văn phòng</a>
              <a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thiết kế Kiến trúc</a>
              <a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công phần thô</a>
              <a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công hoàn thiện</a>
              <a href="#linh-vuc-hoat-dong" class="hover:text-amber-300">• Thi công nội thất</a>
              <a href="#du-an-da-nang" class="hover:text-amber-300">• Dự án tại Đà Nẵng</a>
              <a href="#bang-bao-gia" class="hover:text-amber-300">• Báo giá xây nhà trọn gói</a>
            </div>
          </div>

          <!-- Cột 3: Cam kết chất lượng -->
          <div class="col lg:col-span-3">
            <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase mb-3 tracking-wide border-l-4 border-vbGold pl-2.5">
              CAM KẾT TỪ VIỆT BÁCH
            </h4>
            <ul class="space-y-2 text-xs text-slate-300">
              <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Khảo sát & Tư vấn thiết kế tận nơi</li>
              <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Sử dụng đúng 100% vật tư hợp đồng</li>
              <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Không bán thầu, trực tiếp chỉ huy thi công</li>
              <li><i class="fa-solid fa-check text-amber-400 mr-1.5"></i>Bảo hành kết cấu & chống thấm chu đáo</li>
            </ul>
          </div>

        </div>

        <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400 text-center sm:text-left">
          <div>
            Copyright 2026 © <strong>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH (vietbach.com)</strong>. All rights reserved.
          </div>
          <div>
            Địa chỉ: 1169 Nguyễn Tất Thành, Thanh Khê, Đà Nẵng | ĐT: 0927.000.001
          </div>
        </div>
      </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed bottom-4 right-3 sm:bottom-5 sm:right-4 z-50 flex flex-col items-end gap-2.5">
      <!-- Nút Fanpage Facebook -->
      <a
        href="https://www.facebook.com/profile.php?id=100057402851576"
        target="_blank"
        rel="noopener"
        aria-label="Chat Facebook Fanpage Việt Bách"
        class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
      >
        <span class="w-6 h-6 rounded-full bg-white text-blue-600 flex items-center justify-center font-bold text-xs shrink-0">
          <i class="fa-brands fa-facebook-f"></i>
        </span>
        <span class="text-xs font-bold pr-1">Facebook</span>
      </a>

      <!-- Nút Chat Zalo -->
      <a
        href="https://zalo.me/0927000001"
        target="_blank"
        rel="noopener"
        aria-label="Chat Zalo 0927.000.001"
        class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
      >
        <span class="w-6 h-6 rounded-full bg-white text-sky-600 flex items-center justify-center font-extrabold text-[10px] shrink-0">
          Zalo
        </span>
        <span class="text-xs font-bold pr-1">Chat Zalo</span>
      </a>

      <!-- Nút Gọi Hotline Nổi Bật -->
      <a
        href="tel:0927000001"
        aria-label="Gọi Hotline 0927.000.001"
        class="floating-pulse flex items-center gap-2 bg-vbGold hover:bg-amber-600 text-white px-3.5 py-2.5 rounded-full shadow-xl transition"
      >
        <span class="w-6 h-6 rounded-full bg-white text-vbGold flex items-center justify-center text-xs shrink-0">
          <i class="fa-solid fa-phone-volume"></i>
        </span>
        <span class="text-xs sm:text-sm font-extrabold pr-1">0927.000.001</span>
      </a>
    </div>

  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ SLIDER, BỘ LỌC, FORM & TẢI ẢNH GOOGLE DRIVE ================= -->
  <script>
    // 1. Cơ chế tự động chuyển đổi link dự phòng cho ảnh Google Drive để đảm bảo hiển thị 100%
    function handleDriveImgError(imgEl, fallbackLabel) {
      const fileId = imgEl.getAttribute('data-drive-id');
      const retryStage = parseInt(imgEl.getAttribute('data-retry-stage') || '0', 10);

      if (fileId && retryStage === 0) {
        imgEl.setAttribute('data-retry-stage', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId;
      } else if (fileId && retryStage === 1) {
        imgEl.setAttribute('data-retry-stage', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else {
        imgEl.onerror = null;
        const encodedText = encodeURIComponent(fallbackLabel || 'VIET BACH');
        imgEl.src = 'https://placehold.co/800x600/0b3b75/ffffff?text=' + encodedText;
      }
    }

    // 2. Đóng/Mở Menu trên điện thoại
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobile-menu-drawer');
      if (drawer) {
        drawer.classList.toggle('hidden');
      }
    }

    // 3. Điều khiển 2 Ảnh Banner Tự Trượt Chuyên Nghiệp
    let currentBannerIndex = 0;
    const totalBanners = 2;
    let bannerInterval = null;

    function showBannerSlide(index) {
      for (let i = 0; i < totalBanners; i++) {
        const slide = document.getElementById('banner-slide-' + i);
        const dot = document.getElementById('banner-dot-' + i);
        if (!slide || !dot) continue;

        if (i === index) {
          slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
          slide.classList.add('opacity-100', 'z-10');
          dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
          dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
        }
      }
      currentBannerIndex = index;
    }

    function changeBannerSlide(step) {
      const nextIndex = (currentBannerIndex + step + totalBanners) % totalBanners;
      showBannerSlide(nextIndex);
      resetBannerTimer();
    }

    function goToBannerSlide(index) {
      showBannerSlide(index);
      resetBannerTimer();
    }

    function resetBannerTimer() {
      if (bannerInterval) clearInterval(bannerInterval);
      bannerInterval = setInterval(function () {
        const nextIndex = (currentBannerIndex + 1) % totalBanners;
        showBannerSlide(nextIndex);
      }, 5000);
    }

    // 4. Lọc danh mục Công trình thực tế
    function filterConstruction(category) {
      const cards = document.querySelectorAll('.construction-card');
      cards.forEach(function (card) {
        const cardCat = card.getAttribute('data-category');
        if (category === 'all' || cardCat === category) {
          card.classList.remove('hidden');
        } else {
          card.classList.add('hidden');
        }
      });

      const categories = ['all', 'khach-san', 'biet-thu', 'nha-pho', 'van-phong'];
      categories.forEach(function (cat) {
        const btn = document.getElementById('filter-btn-' + cat);
        if (!btn) return;
        if (cat === category) {
          btn.className = 'filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-vbBlue text-white';
        } else {
          btn.className = 'filter-tab-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-slate-200';
        }
      });
    }

    // 5. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
    function submitQuoteForm(event) {
      event.preventDefault();
      const name = document.getElementById('customerName').value.trim();
      const phone = document.getElementById('customerPhone').value.trim();
      const projectType = document.getElementById('projectType').value;
      const budgetLevel = document.getElementById('budgetLevel').value;
      const msgBox = document.getElementById('quote-form-message');

      if (msgBox) {
        msgBox.classList.remove('hidden');
        msgBox.innerHTML =
          '<strong><i class="fa-solid fa-circle-check mr-1"></i>Đã tiếp nhận yêu cầu báo giá thành công!</strong><br/>' +
          'Cảm ơn Quý khách <strong>' + name + '</strong> (' + phone + '). Bộ phận Kỹ thuật & Dự toán của <strong>CÔNG TY TNHH TƯ VẤN THIẾT KẾ VÀ XÂY DỰNG VIỆT BÁCH</strong> sẽ liên hệ tư vấn hạng mục <strong>' +
          projectType + '</strong> (Mức đầu tư: ' + budgetLevel + ') trong thời gian sớm nhất. Hotline hỗ trợ trực tiếp: <strong>0927.000.001</strong>.';
      }
      document.getElementById('quote-request-form').reset();
    }

    window.onload = function () {
      resetBannerTimer();
    };
  </script>
</body>
</html>
