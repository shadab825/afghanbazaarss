<!DOCTYPE html>
<html lang="en" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shadab Ghazi Zadeh - Online Marketplace</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
            direction: rtl;
        }
        
        .language-selector {
            background-color: #f8f9fa;
            border: 1px solid #dee2e6;
        }
        
        .search-box {
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        
        .category-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        
        .product-card:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        
        .cart-badge {
            top: -10px;
            right: -10px;
        }
        
        .dropdown:hover .dropdown-menu {
            display: block;
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        
        ::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 4px;
        }
        
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Top Bar -->
    <div class="bg-black text-white py-2 px-4 hidden md:block">
        <div class="container mx-auto flex justify-between items-center">
            <div class="flex space-x-4 space-x-reverse">
                <a href="#" class="text-sm hover:text-yellow-400"><i class="fas fa-map-marker-alt mr-1"></i> کابل، افغانستان</a>
                <a href="#" class="text-sm hover:text-yellow-400"><i class="fas fa-phone-alt mr-1"></i> 0776275744</a>
                <a href="#" class="text-sm hover:text-yellow-400"><i class="fas fa-envelope mr-1"></i> shadabakbry420@gmail.com</a>
            </div>
            <div class="flex space-x-4 space-x-reverse">
                <diخحخحclass="language-selector px-2 py-1 rounded text-sm">
               خح   <seleخحct class="bg-transparent text-white outline-none">
                        <option value="fa">دری</option>
                        <optخion value="en">English</option>
                        <option value="ps">پشتو</option>
                    </select>
                </div>
                <a href="#" class="text-sm hover:text-yellow-400"><i class="fas fa-user mr-1"></i> حساب کاربری</a>
                <a href="#" class="text-sm hover:text-yellow-400"><i class="fas fa-store mr-1"></i> فروشنده شوید</a>
            </div>
        </div>
    </div>

    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3">
            <div class="flex flex-col md:flex-row md:items-center justify-between">
                <!-- Logo -->
                <div class="flex items-center justify-between">
                    <a href="#" class="text-2xl font-bold text-blue-600">
                        <span class="text-orange-500">Shadab</span>Market
                    </a>
                    <button class="md:hidden text-gray-600" id="mobile-menu-button">
                        <i class="fas fa-bars text-2xl"></i>
                    </button>
                </div>

                <!-- Search -->
                <div class="mt-4 md:mt-0 md:w-1/2 relative">
                    <div class="search-box flex rounded-md overflow-hidden border border-gray-300">
                        <input type="text" placeholder="جستجوی محصولات..." class="px-4 py-2 w-full outline-none">
                        <select class="border-r border-gray-300 px-2 outline-none bg-gray-100 hidden md:block">
                            <option>همه دسته‌بندی‌ها</option>
                            <option>الکترونیک</option>
                            <option>پوشاک</option>
                            <option>خانه و آشپزخانه</option>
                            <option>کتاب و لوازم تحریر</option>
                        </select>
                        <button class="bg-orange-500 text-white px-4 py-2 hover:bg-orange-600">
                            <i class="fas fa-search"></i>
                        </button>
                    </div>
                </div>

                <!-- User Actions -->
                <div class="hidden md:flex items-center space-x-4 space-x-reverse mt-4 md:mt-0">
                    <a href="#" class="relative">
                        <i class="fas fa-heart text-2xl text-gray-600 hover:text-orange-500"></i>
                        <span class="cart-badge absolute bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">3</span>
                    </a>
                    <a href="#" class="relative">
                        <i class="fas fa-shopping-cart text-2xl text-gray-600 hover:text-orange-500"></i>
                        <span class="cart-badge absolute bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">5</span>
                    </a>
                    <a href="#" class="flex items-center space-x-1 space-x-reverse">
                        <i class="fas fa-user-circle text-2xl text-gray-600 hover:text-orange-500"></i>
                        <span class="text-sm">ورود / ثبت‌نام</span>
                    </a>
                </div>
            </div>
        </div>

        <!-- Mobile Menu -->
        <div class="md:hidden bg-white border-t hidden" id="mobile-menu">
            <div class="container mx-auto px-4 py-3">
                <a href="#" class="block py-2"><i class="fas fa-home mr-2"></i> صفحه اصلی</a>
                <a href="#" class="block py-2"><i class="fas fa-th-large mr-2"></i> دسته‌بندی‌ها</a>
                <a href="#" class="block py-2"><i class="fas fa-user mr-2"></i> حساب کاربری</a>
                <a href="#" class="block py-2"><i class="fas fa-shopping-cart mr-2"></i> سبد خرید</a>
                <a href="#" class="block py-2"><i class="fas fa-heart mr-2"></i> علاقه‌مندی‌ها</a>
                <a href="#" class="block py-2"><i class="fas fa-store mr-2"></i> فروشنده شوید</a>
            </div>
        </div>
    </header>

    <!-- Navigation -->
    <nav class="bg-blue-600 text-white hidden md:block">
        <div class="container mx-auto px-4">
            <div class="flex items-center">
                <div class="dropdown relative">
                    <button class="px-4 py-3 font-medium hover:bg-blue-700 flex items-center">
                        <i class="fas fa-bars ml-2"></i>
                        همه دسته‌بندی‌ها
                    </button>
                    <div class="dropdown-menu absolute right-0 mt-0 w-56 bg-white text-gray-800 shadow-lg rounded-b-lg hidden z-50">
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100 border-b">الکترونیک</a>
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100 border-b">پوشاک</a>
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100 border-b">خانه و آشپزخانه</a>
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100 border-b">کتاب و لوازم تحریر</a>
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100 border-b">لوازم آرایشی</a>
                        <a href="#" class="block px-4 py-2 hover:bg-gray-100">اسباب بازی</a>
                    </div>
                </div>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">صفحه اصلی</a>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">پرفروش‌ترین‌ها</a>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">تخفیف‌ها</a>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">فروشنده شوید</a>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">درباره ما</a>
                <a href="#" class="px-4 py-3 font-medium hover:bg-blue-700">تماس با ما</a>
            </div>
        </div>
    </nav>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-6">
        <!-- Hero Slider -->
        <div class="bg-gray-200 rounded-lg overflow-hidden mb-8 h-64 md:h-96 relative">
            <div class="absolute inset-0 flex items-center justify-center">
                <div class="text-center p-4 bg-black bg-opacity-50 text-white rounded-lg">
                    <h1 class="text-3xl md:text-5xl font-bold mb-4">به بازار آنلاین شاداب خوش آمدید</h1>
                    <p class="text-lg md:text-xl mb-6">خرید آسان و مطمئن از بزرگترین فروشگاه اینترنتی افغانستان</p>
                    <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-6 rounded-full">
                        شروع خرید
                    </button>
                </div>
            </div>
        </div>

        <!-- Categories -->
        <div class="mb-8">
            <h2 class="text-xl md:text-2xl font-bold mb-4 border-b pb-2">دسته‌بندی‌ها</h2>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Electronics" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">الکترونیک</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Clothing" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">پوشاک</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Home" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">خانه و آشپزخانه</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Books" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">کتاب و لوازم تحریر</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Beauty" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">لوازم آرایشی</span>
                </a>
                <a href="#" class="category-card bg-white rounded-lg shadow p-4 text-center hover:shadow-md">
                    <div class="w-16 h-16 mx-auto mb-2">
                        <img src="https://via.placeholder.com/64" alt="Toys" class="w-full h-full object-contain">
                    </div>
                    <span class="font-medium">اسباب بازی</span>
                </a>
            </div>
        </div>

        <!-- Featured Products -->
        <div class="mb-8">
            <div class="flex justify-between items-center mb-4 border-b pb-2">
                <h2 class="text-xl md:text-2xl font-bold">پرفروش‌ترین محصولات</h2>
                <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">مشاهده همه</a>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">20% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">گوشی موبایل سامسونگ گلکسی A23 128GB</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(42)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">25,000 افغانی</span>
                                <div class="text-orange-500 font-bold">20,000 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">لپ تاپ دل اینسپایرون 15 3520</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(18)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <div class="text-orange-500 font-bold">45,000 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">10% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">هدفون بلوتوثی بیس مدل Q20</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(65)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">1,500 افغانی</span>
                                <div class="text-orange-500 font-bold">1,350 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">ماشین لباسشویی سامسونگ 8 کیلویی</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(27)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <div class="text-orange-500 font-bold">32,000 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 5 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">15% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">کتاب داستان‌های مثنوی معنوی</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(12)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">800 افغانی</span>
                                <div class="text-orange-500 font-bold">680 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Discount Products -->
        <div class="mb-8">
            <div class="flex justify-between items-center mb-4 border-b pb-2">
                <h2 class="text-xl md:text-2xl font-bold">تخفیف‌های ویژه</h2>
                <a href="#" class="text-blue-600 hover:text-blue-800 text-sm">مشاهده همه</a>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4">
                <!-- Product 1 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">30% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">کفش ورزشی مردانه آدیداس</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(38)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">3,500 افغانی</span>
                                <div class="text-orange-500 font-bold">2,450 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 2 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">25% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">ساعت هوشمند شیائومی می بند 6</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(24)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">4,800 افغانی</span>
                                <div class="text-orange-500 font-bold">3,600 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 3 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">40% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">چادر زنانه مدل ترکمنی</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(56)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">2,000 افغانی</span>
                                <div class="text-orange-500 font-bold">1,200 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 4 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">15% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">مخلوط کن برقی فیلیپس</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(19)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">1,800 افغانی</span>
                                <div class="text-orange-500 font-bold">1,530 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Product 5 -->
                <div class="product-card bg-white rounded-lg shadow overflow-hidden">
                    <div class="relative">
                        <img src="https://via.placeholder.com/300" alt="Product" class="w-full h-40 object-contain">
                        <div class="absolute top-2 left-2 bg-red-500 text-white text-xs px-2 py-1 rounded">20% تخفیف</div>
                    </div>
                    <div class="p-3">
                        <h3 class="font-medium text-sm mb-1 line-clamp-2">عینک آفتابی ری بن مدل Aviator</h3>
                        <div class="flex items-center mb-1">
                            <div class="text-yellow-400 text-xs">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="far fa-star"></i>
                            </div>
                            <span class="text-gray-500 text-xs mr-1">(31)</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div>
                                <span class="text-gray-500 line-through text-xs">1,200 افغانی</span>
                                <div class="text-orange-500 font-bold">960 افغانی</div>
                            </div>
                            <button class="text-gray-500 hover:text-orange-500">
                                <i class="fas fa-shopping-cart"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Features -->
        <div class="bg-white rounded-lg shadow p-6 mb-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <div class="text-center">
                    <div class="w-16 h-16 mx-auto mb-3 bg-blue-100 rounded-full flex items-center justify-center text-blue-600">
                        <i class="fas fa-truck text-2xl"></i>
                    </div>
                    <h3 class="font-bold mb-1">تحویل سریع</h3>
                    <p class="text-gray-600 text-sm">تحویل در کابل در همان روز</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 mx-auto mb-3 bg-green-100 rounded-full flex items-center justify-center text-green-600">
                        <i class="fas fa-shield-alt text-2xl"></i>
                    </div>
                    <h3 class="font-bold mb-1">پرداخت امن</h3>
                    <p class="text-gray-600 text-sm">پرداخت در محل یا آنلاین</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 mx-auto mb-3 bg-orange-100 rounded-full flex items-center justify-center text-orange-600">
                        <i class="fas fa-headset text-2xl"></i>
                    </div>
                    <h3 class="font-bold mb-1">پشتیبانی 24/7</h3>
                    <p class="text-gray-600 text-sm">پشتیبانی تلفنی و آنلاین</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 mx-auto mb-3 bg-purple-100 rounded-full flex items-center justify-center text-purple-600">
                        <i class="fas fa-undo text-2xl"></i>
                    </div>
                    <h3 class="font-bold mb-1">بازگشت کالا</h3>
                    <p class="text-gray-600 text-sm">7 روز ضمانت بازگشت</p>
                </div>
            </div>
        </div>

        <!-- Brands -->
        <div class="mb-8">
            <h2 class="text-xl md:text-2xl font-bold mb-4 border-b pb-2">برندهای معتبر</h2>
            <div class="bg-white rounded-lg shadow p-4">
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-4">
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Samsung" class="h-8 object-contain">
                    </div>
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Apple" class="h-8 object-contain">
                    </div>
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Xiaomi" class="h-8 object-contain">
                    </div>
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Nike" class="h-8 object-contain">
                    </div>
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Adidas" class="h-8 object-contain">
                    </div>
                    <div class="p-3 border rounded-lg flex items-center justify-center">
                        <img src="https://via.placeholder.com/100x50" alt="Philips" class="h-8 object-contain">
                    </div>
                </div>
            </div>
        </div>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white pt-10 pb-6">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">درباره شاداب مارکت</h3>
                    <p class="text-gray-400 mb-4">بزرگترین بازار آنلاین افغانستان با هدف ارائه بهترین خدمات به مشتریان و ایجاد بستری امن برای خرید و فروش آنلاین.</p>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">لینک‌های مفید</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">صفحه اصلی</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">درباره ما</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">تماس با ما</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">حریم خصوصی</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">قوانین و مقررات</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">خدمات مشتریان</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">پرسش‌های متداول</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">شرایط بازگشت کالا</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">روش‌های پرداخت</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">راهنمای خرید</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">پیگیری سفارش</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">تماس با ما</h3>
                    <ul class="space-y-2">
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt mt-1 ml-2 text-gray-400"></i>
                            <span class="text-gray-400">کابل، افغانستان</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt ml-2 text-gray-400"></i>
                            <span class="text-gray-400">0776275744</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope ml-2 text-gray-400"></i>
                            <span class="text-gray-400">shadabakbry420@gmail.com</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 pt-6">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <p class="text-gray-400 mb-4 md:mb-0">© 2023 ShadabMarket. تمامی حقوق محفوظ است.</p>
                    <div class="flex space-x-4 space-x-reverse">
                        <img src="https://via.placeholder.com/40" alt="Payment" class="h-8">
                        <img src="https://via.placeholder.com/40" alt="Payment" class="h-8">
                        <img src="https://via.placeholder.com/40" alt="Payment" class="h-8">
                        <img src="https://via.placeholder.com/40" alt="Payment" class="h-8">
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating Action Button -->
    <div class="fixed bottom-6 left-6 z-50">
        <button class="bg-blue-600 text-white w-14 h-14 rounded-full shadow-lg flex items-center justify-center hover:bg-blue-700">
            <i class="fas fa-headset text-2xl"></i>
        </button>
    </div>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Product carousel functionality would go here
        // This is just a placeholder for the actual implementation
        console.log('E-commerce site for Shadab Ghazi Zadeh');
        
        // Language selector
        const languageSelector = document.querySelector('.language-selector select');
        languageSelector.addEventListener('change', function() {
            console.log('Language changed to:', this.value);
            // Here you would implement language switching logic
        });
    </script>
</body>
</html>
