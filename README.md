<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>گروه سرود ابناءالحسن</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap');
        body {
            font-family: 'Vazirmatn', sans-serif;
            color: #1f2937;
            text-align: right;
            direction: rtl;
        }

        /* Stronger primary colors */
        .text-orange-600 { color: #EA580C; }
        .bg-orange-600 { background-color: #EA580C; }
        .bg-green-800 { background-color: #065F46; }
        .ring-orange-600:focus { --tw-ring-color: #EA580C; }
        .text-green-900 { color: #064E3B; }

        .btn {
            @apply px-8 py-4 rounded-full font-bold transition-all duration-300 transform hover:scale-105 shadow-lg hover:shadow-xl;
        }
        .member-card {
            transition: all 0.3s ease-in-out;
        }
        .member-card:hover {
            transform: translateY(-8px) scale(1.03);
            box-shadow: 0 15px 30px rgba(0,0,0,0.15);
        }
    </style>
</head>
<body class="antialiased bg-orange-200">
<!-- Header Section -->
<header class="bg-white shadow-lg sticky top-0 z-50">
    <div class="container mx-auto px-4 py-4 flex flex-col md:flex-row justify-between items-center">
        <div class="text-green-800 text-3xl font-bold mb-4 md:mb-0">
            گروه سرود <span class="text-orange-600">ابناءالحسن</span>
        </div>
        <nav class="flex flex-col md:flex-row items-center space-y-2 md:space-y-0 md:space-x-4 md:space-x-reverse">
            <a href="#about" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">درباره ما</a>
            <a href="#achievements" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">دستاوردها</a>
            <a href="#news" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">اخبار</a>
            <a href="#events" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">برنامه‌ها</a>
            <a href="#gallery" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">گالری</a>
            <a href="#faq" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">سوالات متداول</a>
            <a href="#register" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">ثبت نام</a>
            <a href="#contact" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">تماس با ما</a>
            <a href="#admin-login" class="text-gray-700 hover:text-orange-600 font-semibold transition-colors duration-200">ورود مدیر</a>
        </nav>
    </div>
</header>
<!-- Hero Section -->
<main class="py-20 text-center bg-gradient-to-b from-orange-500 to-green-300">
    <div class="container mx-auto px-4">
        <h1 class="text-5xl md:text-6xl font-extrabold text-green-900 leading-tight mb-4">
            صدای <span class="text-orange-600">همدلی</span>، <br>
            نغمه‌های <span class="text-orange-600">عشق</span>
        </h1>
        <p class="text-xl md:text-2xl text-gray-600 mb-8">
            گروه سرود ابناءالحسن، آوای رسالت و هنر
        </p>
        <a href="#register" class="bg-orange-600 btn text-white hover:bg-orange-700">ثبت نام کنید</a>
    </div>
</main>
<!-- About Section -->
<section id="about" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 flex flex-col md:flex-row items-center gap-12">
        <div class="md:w-1/2">
            <img src="https://uploadkon.ir/uploads/cec114_25abna-1-2-1-.png"
                 class="w-full h-auto rounded-3xl shadow-2xl transform transition-transform duration-500 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
        </div>
        <div class="md:w-1/2 text-right">
            <h2 class="text-4xl font-bold text-green-900 mb-4">درباره ما</h2>
            <p class="text-gray-600 text-lg leading-loose text-justify">
                گروه سرود ابناءالحسن، مجموعه‌ای از نوجوانان و جوانان هنرمند است که با هدف ترویج فرهنگ و ارزش‌های دینی از طریق هنر سرود تشکیل شده است. تحت هدایت استاد حسین درویش، ما تلاش می‌کنیم با اجراهای پرشور و معنوی، پیام‌های ارزشمندی را به جامعه منتقل کنیم. افتخار ما حضور در برنامه‌های مختلف و اجرای سرودهای به یادماندنی است.
            </p>
        </div>
    </div>
</section>
<!-- Achievements Section -->
<section id="achievements" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">دستاوردها</h2>
        <p class="text-gray-600 text-lg mb-8">
            دستاورد های بزرگ گروه سرود ابناءالحسن
        </p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">رتبه اول مسابقات مداحی کشوری</h3>
                <p class="text-gray-600 mb-2">سال ۱۴۰۴ </p>
                <p class="text-sm text-gray-500">کسب رتبه های برتر در مسابقات مداحی دانش‌آموزی</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">اجرا در حرم امام رضا (ع)</h3>
                <p class="text-gray-600 mb-2">سال ۱۴۰۳</p>
                <p class="text-sm text-gray-500">افتخار اجرای سرود در مراسم نوروزی صحن جامع حرم</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">اجرا در برنامه تلوزیونی حسینیه معلی</h3>
                <p class="text-gray-600 mb-2">بهمن ۱۴۰۴</p>
                <p class="text-sm text-gray-500">اجرا در پربیننده برنامه تلوزیونی کشور </p>
            </div>
        </div>
    </div>
</section>
<!-- News Section -->
<section id="news" class="py-20 bg-orange-200">
    <div class="container mx-auto px-4">
        <h2 class="text-4xl font-bold text-green-900 text-center mb-12">اخبار گروه</h2>
        <div id="news-list" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- News will be dynamically loaded here -->
        </div>
        <!-- Button to load news -->
        <div class="flex justify-center mt-8">
            <button id="load-news-btn" onclick="fetchNews()" class="px-6 py-3 rounded-full font-bold text-sm transition-all duration-300 transform hover:scale-105 shadow-md bg-green-800 text-white hover:bg-green-900">
                بارگذاری اخبار جدید
            </button>
        </div>
    </div>
</section>
<!-- Events Section -->
<section id="events" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">برنامه‌ها و رویدادهای پیش‌رو</h2>
        <p class="text-gray-600 text-lg mb-8">
            با ما در رویدادهای آینده همراه شوید.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">جشن عید غدیر خم</h3>
                <p class="text-gray-600 mb-2">زمان: جمعه، ۲۱ تیر ۱۴۰۳</p>
                <p class="text-gray-600 mb-4">مکان: تهران، میدان امام حسین (ع)، حسینیه هنر</p>
                <p class="text-sm text-gray-500">اجرای سرودهای ویژه عید غدیر و برنامه‌های شاد.</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">همایش نوجوانان عاشورایی</h3>
                <p class="text-gray-600 mb-2">زمان: پنجشنبه، ۱۰ مرداد ۱۴۰۳</p>
                <p class="text-gray-600 mb-4">مکان: قم، حرم حضرت معصومه (س)، صحن فاطمی</p>
                <p class="text-sm text-gray-500">اجرای سرودهای حماسی و عاشورایی.</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-xl hover:shadow-2xl transition-shadow duration-300">
                <h3 class="text-2xl font-bold text-green-900 mb-2">اجرای ویژه شهادت</h3>
                <p class="text-gray-600 mb-2">زمان: دوشنبه، ۱۵ مرداد ۱۴۰۳</p>
                <p class="text-gray-600 mb-4">مکان: تهران، مهدیه تهران</p>
                <p class="text-sm text-gray-500">مراسم بزرگداشت و اجرای سرودهای ویژه.</p>
            </div>
        </div>
    </div>
</section>
<!-- Gallery Section -->
<section id="gallery" class="py-20 bg-orange-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">گالری تصاویر</h2>
        <p class="text-gray-600 text-lg mb-8">
            لحظاتی از اجراها و فعالیت‌های گروه
        </p>
        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4">
            <img src="https://uploadkon.ir/uploads/4ab713_25photo20796287083.jpg" alt="اجرا 1" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/42cd13_25photo20771497987.jpg" alt="تمرین 2" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/67fa13_25photo20704490776.jpg" alt="اجرا 3" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/6db413_25photo20704473684.jpg" alt="تمرین 4" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/d5d513_25photo20704415303.jpg" alt="گروه 5" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/314313_25photo20704172149-1-.jpg" alt="اجرا 6" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/7ae614_25Untitled.jpeg" alt="اجرای موفق در مسابقات" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
            <img src="https://uploadkon.ir/uploads/975514_25Untitled.jpeg" alt="عکس گروهی" class="w-full h-64 object-cover rounded-2xl shadow-lg transition-transform duration-300 hover:scale-105"
                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">
        </div>
    </div>
</section>
<!-- FAQ Section -->
<section id="faq" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">سوالات متداول</h2>
        <p class="text-gray-600 text-lg mb-8">
            پاسخ به برخی از سوالات رایج شما.
        </p>
        <div class="max-w-3xl mx-auto space-y-6 text-right">
            <div class="bg-white p-6 rounded-2xl shadow-lg">
                <h3 class="text-xl font-semibold text-green-900 mb-2">شرایط سنی برای ثبت‌نام چیست؟</h3>
                <p class="text-gray-600 text-justify">گروه ما از نوجوانان و جوانان در رده‌های سنی ۳ تا ۱۷ سال ثبت‌نام می‌کند. با این حال، برای استعدادهای ویژه امکان استثنا نیز وجود دارد.</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-lg">
                <h3 class="text-xl font-semibold text-green-900 mb-2">هزینه عضویت و آموزش چقدر است؟</h3>
                <p class="text-gray-600 text-justify">هزینه عضویت و آموزش ها 800 هزار تومان می باشد و هزینه لباس هم 400 تومان می باشد و هزینه اردو ها هم به جز اردو های رابگان متغیر است.</p>
            </div>
            <div class="bg-white p-6 rounded-2xl shadow-lg">
                <h3 class="text-xl font-semibold text-green-900 mb-2">چه روزهایی تمرین دارید؟</h3>
                <p class="text-gray-600 text-justify">تمرینات گروه به صورت هفتگی و روزهای چهارشنبه برگزار می‌شود. اطلاعات دقیق‌تر پس از ثبت‌نام به اطلاع شما خواهد رسید.</p>
            </div>
        </div>
    </div>
</section>
<!-- Registration Section -->
<section id="register" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">به جمع ما بپیوندید</h2>
        <p class="text-gray-600 text-lg mb-8">
            برای ثبت‌نام در دوره‌های آموزشی و عضویت در گروه، فرم زیر را تکمیل کنید.
        </p>
        <div class="max-w-xl mx-auto bg-white p-8 rounded-2xl shadow-lg">
            <form onsubmit="event.preventDefault(); submitRegistration();">
                <div class="mb-4">
                    <input type="text" id="reg-name" placeholder="نام و نام خانوادگی" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <div class="mb-4">
                    <input type="tel" id="reg-phone" placeholder="شماره تلفن" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <div class="mb-4">
                    <input type="number" id="reg-age" placeholder="سن" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <div class="mb-6">
                    <textarea id="reg-message" placeholder="پیام یا توضیحات بیشتر (اختیاری)" rows="5" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200"></textarea>
                </div>
                <button type="submit" class="w-full bg-orange-600 btn text-white hover:bg-orange-700">
                    ثبت نام
                </button>
            </form>
            <div id="registration-status-message" class="mt-4 font-semibold hidden"></div>
        </div>
    </div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">تماس با ما</h2>
        <p class="text-gray-600 text-lg mb-8">
            برای ارسال پیام به گروه، از فرم زیر استفاده کنید.
        </p>
        <div class="max-w-2xl mx-auto bg-white p-8 rounded-2xl shadow-lg text-right">
            <form onsubmit="event.preventDefault(); sendContactMessage();">
                <div class="mb-4">
                    <input type="text" id="contact-name" placeholder="نام و نام خانوادگی" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <div class="mb-4">
                    <input type="email" id="contact-email" placeholder="ایمیل" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <div class="mb-6">
                    <textarea id="contact-message" placeholder="متن پیام" rows="5" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200"></textarea>
                </div>
                <button type="submit" class="w-full bg-green-800 btn text-white hover:bg-green-900">
                    ارسال پیام
                </button>
            </form>
            <div id="contact-status-message" class="mt-4 font-semibold hidden"></div>
        </div>
    </div>
</section>
<!-- Admin Panel Section -->
<section id="admin-panel" class="py-20 bg-orange-200 hidden">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">پنل مدیریت</h2>
        <p class="text-gray-600 text-lg mb-8">
            از این بخش می‌توانید اخبار و ثبت‌نام‌ها را مدیریت کنید.
        </p>
        <div class="flex flex-col lg:flex-row gap-8 justify-center">
            <!-- News Management Panel -->
            <div class="flex-1 bg-white p-8 rounded-2xl shadow-lg">
                <h3 class="text-2xl font-bold text-green-900 mb-4">مدیریت اخبار</h3>
                <form onsubmit="event.preventDefault(); addNews();">
                    <div class="mb-6">
                        <input type="text" id="news-title" placeholder="عنوان خبر" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                    </div>
                    <div class="mb-6">
                        <textarea id="news-content" placeholder="محتوای خبر" rows="6" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200"></textarea>
                    </div>
                    <div class="mb-6">
                        <input type="url" id="image-url" placeholder="URL تصویر (اختیاری)" oninput="updateImagePreview()" class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                        <img id="image-preview" class="hidden mt-4 rounded-lg shadow-md" style="max-height: 200px;">
                    </div>
                    <button type="button" id="generate-news-btn" onclick="generateNewsContent()" class="w-full mb-4 bg-gray-500 btn text-white hover:bg-gray-600">
                        ✨ساخت متن خبر✨
                    </button>
                    <button type="submit" class="w-full bg-green-800 btn text-white hover:bg-green-900">
                        انتشار خبر
                    </button>
                </form>
                <div id="news-status-message" class="mt-4 hidden font-semibold"></div>
            </div>
            <!-- Registration Management Panel -->
            <div class="flex-1 bg-white p-8 rounded-2xl shadow-lg">
                <h3 class="text-2xl font-bold text-green-900 mb-4">مدیریت ثبت‌نام‌ها</h3>
                <div id="registrations-list" class="mt-6 text-sm text-right">
                    <!-- Registrations will be dynamically loaded here -->
                </div>
            </div>
        </div>
    </div>
</section>
<!-- Admin Login Section -->
<section id="admin-login" class="py-20 bg-green-200">
    <div class="container mx-auto px-4 text-center">
        <h2 class="text-4xl font-bold text-green-900 mb-4">ورود به پنل مدیریت</h2>
        <div class="max-w-xl mx-auto bg-white p-8 rounded-2xl shadow-lg">
            <p class="text-gray-600 mb-4">لطفاً رمز عبور را وارد کنید.</p>
            <form onsubmit="event.preventDefault(); attemptAdminLogin();">
                <div class="mb-6">
                    <input type="password" id="admin-password-input" placeholder="رمز عبور" required class="w-full p-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-green-800 focus:border-transparent transition-colors duration-200">
                </div>
                <button type="submit" class="w-full bg-green-800 btn text-white hover:bg-green-900">
                    ورود
                </button>
            </form>
            <div id="admin-login-status" class="mt-4 font-semibold hidden"></div>
        </div>
    </div>
</section>
<!-- Registration View Modal -->
<div id="registration-modal" class="fixed inset-0 bg-gray-600 bg-opacity-50 overflow-y-auto h-full w-full flex justify-center items-center z-50 hidden">
    <div class="relative p-8 border w-96 md:w-1/2 lg:w-1/3 shadow-lg rounded-2xl bg-white text-right">
        <h3 class="text-2xl font-bold text-green-900 mb-4">جزئیات ثبت‌نام</h3>
        <button onclick="closeRegistrationModal()" class="absolute top-4 left-4 text-gray-500 hover:text-gray-800 text-3xl font-bold">
            &times;
        </button>
        <div id="modal-content" class="text-gray-700 space-y-4">
            <!-- Content will be injected here -->
        </div>
        <div class="mt-6 text-center">
            <button onclick="closeRegistrationModal()" class="px-6 py-3 rounded-full font-bold bg-gray-300 text-gray-800 hover:bg-gray-400 transition-colors duration-200">
                بستن
            </button>
        </div>
    </div>
</div>
<!-- Reusable Confirmation Modal -->
<div id="confirmation-modal" class="fixed inset-0 bg-gray-600 bg-opacity-50 overflow-y-auto h-full w-full flex justify-center items-center z-50 hidden">
    <div class="relative p-5 border w-96 shadow-lg rounded-md bg-white text-right">
        <h3 class="text-lg font-bold text-green-900 mb-4" id="confirmation-modal-title"></h3>
        <p class="text-gray-600 mb-6" id="confirmation-modal-text"></p>
        <div class="flex justify-end space-x-2 space-x-reverse">
            <button id="confirmation-cancel-btn" class="px-4 py-2 bg-gray-300 text-gray-800 rounded-lg hover:bg-gray-400">لغو</button>
            <button id="confirmation-confirm-btn" class="px-4 py-2 bg-red-600 text-white rounded-lg hover:bg-red-700">تأیید</button>
        </div>
    </div>
</div>
<!-- Footer Section -->
<footer class="bg-green-900 text-white py-8">
    <div class="container mx-auto px-4 text-center">
        <p class="text-sm">
            تمامی حقوق این وب‌سایت متعلق به گروه سرود ابناءالحسن می‌باشد.
        </p>
    </div>
</footer>
<script>
    // Constants and functions for the password and local storage
    const ADMIN_PASSWORD = "1235";
    const ADMIN_LOGGED_IN_KEY = "is_admin_logged_in";
    const NEWS_STORAGE_KEY = "abna_al_hasan_news";
    const REGISTRATIONS_STORAGE_KEY = "abna_al_hasan_registrations";

    // Reusable function for confirmation modals
    const showConfirmationModal = (title, text, onConfirm) => {
        const modal = document.getElementById('confirmation-modal');
        document.getElementById('confirmation-modal-title').textContent = title;
        document.getElementById('confirmation-modal-text').textContent = text;
        modal.classList.remove('hidden');

        const confirmBtn = document.getElementById('confirmation-confirm-btn');
        const cancelBtn = document.getElementById('confirmation-cancel-btn');

        const hideModal = () => modal.classList.add('hidden');

        confirmBtn.onclick = () => {
            onConfirm();
            hideModal();
        };

        cancelBtn.onclick = () => {
            hideModal();
        };
    };

    window.attemptAdminLogin = () => {
        const passwordInput = document.getElementById('admin-password-input');
        const loginStatus = document.getElementById('admin-login-status');
        const adminPanel = document.getElementById('admin-panel');
        const adminLoginSection = document.getElementById('admin-login');

        if (passwordInput.value === ADMIN_PASSWORD) {
            // ورود موفق، وضعیت را در sessionStorage ذخیره کنید
            sessionStorage.setItem(ADMIN_LOGGED_IN_KEY, 'true');
            
            adminPanel.classList.remove('hidden');
            adminLoginSection.classList.add('hidden');
            loginStatus.textContent = 'ورود با موفقیت انجام شد! پنل مدیریت فعال شد.';
            loginStatus.className = 'mt-4 font-semibold text-green-600 block';
            fetchRegistrations(); // بارگذاری ثبت‌نام‌ها پس از ورود موفق
        } else {
            loginStatus.textContent = 'رمز عبور نادرست است.';
            loginStatus.className = 'mt-4 font-semibold text-red-500 block';
        }
    };

    window.updateImagePreview = () => {
        const imageUrl = document.getElementById('image-url').value;
        const imagePreview = document.getElementById('image-preview');
        if (imageUrl) {
            imagePreview.src = imageUrl;
            imagePreview.classList.remove('hidden');
        } else {
            imagePreview.classList.add('hidden');
        }
    };

    // Add a new news item to Local Storage
    window.addNews = () => {
        const titleInput = document.getElementById('news-title');
        const contentInput = document.getElementById('news-content');
        const imageUrlInput = document.getElementById('image-url');
        const newsStatusMessage = document.getElementById('news-status-message');
        
        const title = titleInput.value;
        const content = contentInput.value;
        const imageUrl = imageUrlInput.value || null;

        if (!title || !content) {
            newsStatusMessage.textContent = 'لطفاً عنوان و محتوای خبر را وارد کنید.';
            newsStatusMessage.className = 'mt-4 font-semibold text-red-500 block';
            return;
        }

        const news = JSON.parse(localStorage.getItem(NEWS_STORAGE_KEY) || '[]');
        const newNews = {
            id: Date.now(), // Use timestamp as a simple unique ID
            title,
            content,
            imageUrl,
            timestamp: Date.now()
        };
        
        news.push(newNews);
        localStorage.setItem(NEWS_STORAGE_KEY, JSON.stringify(news));

        titleInput.value = '';
        contentInput.value = '';
        imageUrlInput.value = '';
        updateImagePreview();
        newsStatusMessage.textContent = 'خبر با موفقیت منتشر شد!';
        newsStatusMessage.className = 'mt-4 font-semibold text-green-600 block';

        fetchNews(); // Update the displayed news list
    };

    // Delete a news item from Local Storage
    window.deleteNews = (id) => {
        showConfirmationModal('حذف خبر', 'آیا مطمئن هستید که می‌خواهید این خبر را حذف کنید؟', () => {
            let news = JSON.parse(localStorage.getItem(NEWS_STORAGE_KEY) || '[]');
            news = news.filter(item => item.id !== parseInt(id, 10)); // استفاده از مقایسه قوی‌تر
            localStorage.setItem(NEWS_STORAGE_KEY, JSON.stringify(news));
            fetchNews(); // Update the displayed news list
        });
    };

    // Manually load news from Local Storage
    window.fetchNews = () => {
        const newsList = document.getElementById('news-list');
        const loadButton = document.getElementById('load-news-btn');
        
        loadButton.textContent = 'در حال بارگذاری...';
        loadButton.disabled = true;

        const newsItems = JSON.parse(localStorage.getItem(NEWS_STORAGE_KEY) || '[]');
        newsList.innerHTML = ''; // Clear the list before displaying new ones

        if (newsItems.length === 0) {
            newsList.innerHTML = '<p class="text-gray-500 text-center col-span-full">در حال حاضر خبری وجود ندارد.</p>';
            loadButton.textContent = 'بارگذاری اخبار جدید';
            loadButton.disabled = false;
            return;
        }

        // Sort by timestamp (newest first)
        newsItems.sort((a, b) => b.timestamp - a.timestamp);

        const isAdmin = sessionStorage.getItem(ADMIN_LOGGED_IN_KEY) === 'true';

        newsItems.forEach(newsItem => {
            const newsElement = document.createElement('div');
            newsElement.className = 'bg-white p-6 rounded-2xl shadow-xl transition-all duration-300 hover:shadow-2xl';
            let imageHtml = newsItem.imageUrl ? `<img src="${newsItem.imageUrl}" alt="${newsItem.title}" class="w-full h-48 object-cover rounded-xl mb-4" onerror="this.onerror=null;this.src='https://placehold.co/600x400/cccccc/333333?text=تصویر+یافت+نشد';">` : '';
            let deleteButton = isAdmin ? `<button onclick="deleteNews('${newsItem.id}')" class="mt-4 px-4 py-2 rounded-full font-bold text-sm bg-red-600 text-white hover:bg-red-700">حذف</button>` : '';

            newsElement.innerHTML = `
                ${imageHtml}
                <h3 class="text-2xl font-bold text-green-700 mb-2">${newsItem.title}</h3>
                <p class="text-gray-600">${newsItem.content}</p>
                ${deleteButton}
            `;
            newsList.appendChild(newsElement);
        });

        loadButton.textContent = 'بارگذاری اخبار جدید';
        loadButton.disabled = false;
    };

    // --- Integrate with Gemini API for content generation ---
    window.generateNewsContent = async () => {
        const newsContentInput = document.getElementById('news-content');
        const generateButton = document.getElementById('generate-news-btn');
        const newsStatusMessage = document.getElementById('news-status-message');
        const userPrompt = newsContentInput.value.trim();

        if (!userPrompt) {
            newsStatusMessage.textContent = 'لطفا یک متن کوتاه برای تولید خبر وارد کنید.';
            newsStatusMessage.className = 'mt-4 font-semibold text-red-500 block';
            return;
        }

        generateButton.textContent = 'در حال تولید...';
        generateButton.disabled = true;
        newsStatusMessage.textContent = 'در حال تولید محتوا توسط هوش مصنوعی...';
        newsStatusMessage.className = 'mt-4 font-semibold text-gray-500 block';
        
        const apiKey = "";
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;
        const prompt = `با فرض اینکه یک خبرنگار برای گروه سرود ابناءالحسن هستی، متن کوتاه زیر را به یک خبر کامل و رسمی تبدیل کن و جزئیات بیشتری به آن اضافه کن. متن کوتاه: "${userPrompt}"`;
        
        const payload = {
            contents: [{ parts: [{ text: prompt }] }],
            systemInstruction: {
                parts: [{ text: "شما یک هوش مصنوعی خبرنویس برای یک گروه سرود مذهبی هستید. لحن شما باید رسمی، معنوی و انگیزشی باشد." }]
            }
        };

        let retryCount = 0;
        const maxRetries = 3;
        const baseDelay = 1000;

        const makeApiCall = async () => {
            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    if (response.status === 429 && retryCount < maxRetries) {
                        const delay = baseDelay * Math.pow(2, retryCount);
                        retryCount++;
                        await new Promise(res => setTimeout(res, delay));
                        return makeApiCall();
                    }
                    throw new Error(`API error: ${response.status}`);
                }
                
                const result = await response.json();
                const text = result?.candidates?.[0]?.content?.parts?.[0]?.text;
                
                if (text) {
                    newsContentInput.value = text;
                    newsStatusMessage.textContent = 'خبر با موفقیت تولید شد! می‌توانید آن را ویرایش و منتشر کنید.';
                    newsStatusMessage.className = 'mt-4 font-semibold text-green-600 block';
                } else {
                    throw new Error("Failed to generate content.");
                }
            } catch (error) {
                console.error("Error generating news content:", error);
                newsStatusMessage.textContent = 'خطا در تولید خبر. لطفا دوباره تلاش کنید.';
                newsStatusMessage.className = 'mt-4 font-semibold text-red-500 block';
            } finally {
                generateButton.textContent = '✨ساخت متن خبر✨';
                generateButton.disabled = false;
            }
        };
        makeApiCall();
    };

    // --- Registration Management Functions ---
    window.submitRegistration = () => {
        const statusMessage = document.getElementById('registration-status-message');
        const nameInput = document.getElementById('reg-name');
        const phoneInput = document.getElementById('reg-phone');
        const ageInput = document.getElementById('reg-age');
        const messageInput = document.getElementById('reg-message');

        const registration = {
            id: Date.now(),
            name: nameInput.value,
            phone: phoneInput.value,
            age: ageInput.value,
            message: messageInput.value || 'بدون پیام'
        };

        if (!registration.name || !registration.phone || !registration.age) {
            statusMessage.textContent = 'لطفاً تمامی فیلدهای اجباری را پر کنید.';
            statusMessage.className = 'mt-4 font-semibold text-red-500 block';
            return;
        }

        const registrations = JSON.parse(localStorage.getItem(REGISTRATIONS_STORAGE_KEY) || '[]');
        registrations.push(registration);
        localStorage.setItem(REGISTRATIONS_STORAGE_KEY, JSON.stringify(registrations));
        
        statusMessage.textContent = 'ثبت‌نام شما با موفقیت انجام شد. به زودی با شما تماس خواهیم گرفت.';
        statusMessage.className = 'mt-4 font-semibold text-green-600 block';

        // Reset form fields
        nameInput.value = '';
        phoneInput.value = '';
        ageInput.value = '';
        messageInput.value = '';
    };

    window.fetchRegistrations = () => {
        const registrationsList = document.getElementById('registrations-list');
        const registrations = JSON.parse(localStorage.getItem(REGISTRATIONS_STORAGE_KEY) || '[]');

        // Clear previous content
        registrationsList.innerHTML = '';

        if (registrations.length === 0) {
            registrationsList.innerHTML = '<p class="text-gray-500 text-center">در حال حاضر هیچ ثبت‌نامی وجود ندارد.</p>';
            return;
        }
        
        // Create header row for desktop view
        const headerRow = document.createElement('div');
        headerRow.className = 'hidden md:grid grid-cols-5 font-bold p-2 mb-2 border-b border-gray-300';
        headerRow.innerHTML = `
            <div class="col-span-1">نام و نام خانوادگی</div>
            <div class="col-span-1">شماره تلفن</div>
            <div class="col-span-1">سن</div>
            <div class="col-span-1">پیام</div>
            <div class="col-span-1">عملیات</div>
        `;
        registrationsList.appendChild(headerRow);

        // Sort by timestamp (newest first)
        registrations.sort((a, b) => b.id - a.id);

        registrations.forEach(reg => {
            const regElement = document.createElement('div');
            // Responsive design for the grid
            regElement.className = 'grid grid-cols-1 md:grid-cols-5 gap-4 md:gap-2 p-4 border-b border-gray-200 hover:bg-gray-50';
            regElement.innerHTML = `
                <div class="col-span-1 font-bold md:font-normal">نام: <span class="md:hidden font-normal">${reg.name}</span></div>
                <div class="col-span-1 font-bold md:font-normal">تلفن: <span class="md:hidden font-normal">${reg.phone}</span></div>
                <div class="col-span-1 font-bold md:font-normal">سن: <span class="md:hidden font-normal">${reg.age}</span></div>
                <div class="col-span-1 font-bold md:font-normal">پیام: <span class="md:hidden font-normal truncate max-w-xs">${reg.message}</span></div>
                <div class="col-span-1 flex items-center space-x-2 space-x-reverse mt-2 md:mt-0">
                    <button onclick="viewRegistrationDetails('${reg.id}')" class="flex-1 px-3 py-1 rounded-full text-xs font-bold bg-blue-600 text-white hover:bg-blue-700 transition-colors duration-200">مشاهده</button>
                    <button onclick="deleteRegistration('${reg.id}')" class="flex-1 px-3 py-1 rounded-full text-xs font-bold bg-red-600 text-white hover:bg-red-700 transition-colors duration-200">حذف</button>
                </div>
            `;
            registrationsList.appendChild(regElement);
        });
    };

    window.viewRegistrationDetails = (id) => {
        const registrations = JSON.parse(localStorage.getItem(REGISTRATIONS_STORAGE_KEY) || '[]');
        const registration = registrations.find(reg => reg.id === parseInt(id, 10)); // Using `parseInt` for robust comparison
        
        if (!registration) return;

        const modalContent = document.getElementById('modal-content');
        modalContent.innerHTML = `
            <div class="flex items-center mb-2">
                <span class="font-bold w-1/3">نام و نام خانوادگی:</span>
                <span class="w-2/3">${registration.name}</span>
            </div>
            <div class="flex items-center mb-2">
                <span class="font-bold w-1/3">شماره تلفن:</span>
                <span class="w-2/3">${registration.phone}</span>
            </div>
            <div class="flex items-center mb-2">
                <span class="font-bold w-1/3">سن:</span>
                <span class="w-2/3">${registration.age}</span>
            </div>
            <div class="flex items-center mb-2">
                <span class="font-bold w-1/3">پیام:</span>
                <span class="w-2/3">${registration.message}</span>
            </div>
        `;

        document.getElementById('registration-modal').classList.remove('hidden');
    };
    
    window.closeRegistrationModal = () => {
        document.getElementById('registration-modal').classList.add('hidden');
    };

    window.deleteRegistration = (id) => {
        showConfirmationModal('حذف ثبت‌نام', 'آیا مطمئن هستید که می‌خواهید این ثبت‌نام را حذف کنید؟', () => {
            let registrations = JSON.parse(localStorage.getItem(REGISTRATIONS_STORAGE_KEY) || '[]');
            registrations = registrations.filter(item => item.id !== parseInt(id, 10)); // Using `parseInt` for robust comparison
            localStorage.setItem(REGISTRATIONS_STORAGE_KEY, JSON.stringify(registrations));
            fetchRegistrations();
        });
    };

    // --- Dummy functions for forms as there's no backend ---
    window.sendContactMessage = () => {
        const contactStatusMessage = document.getElementById('contact-status-message');
        const name = document.getElementById('contact-name').value;
        const email = document.getElementById('contact-email').value;
        const message = document.getElementById('contact-message').value;
        if (!name || !email || !message) {
            contactStatusMessage.textContent = 'لطفاً تمامی فیلدها را پر کنید.';
            contactStatusMessage.className = 'mt-4 font-semibold text-red-500 block';
            return;
        }
        contactStatusMessage.textContent = 'پیام شما با موفقیت ارسال شد. از شما متشکریم!';
        contactStatusMessage.className = 'mt-4 font-semibold text-green-600 block';
        // Reset form fields
        document.getElementById('contact-name').value = '';
        document.getElementById('contact-email').value = '';
        document.getElementById('contact-message').value = '';
    };

    window.onload = () => {
        // بارگذاری اخبار در زمان بارگذاری صفحه
        fetchNews();
        
        // بررسی وضعیت ورود مدیر از sessionStorage و نمایش پنل در صورت نیاز
        if (sessionStorage.getItem(ADMIN_LOGGED_IN_KEY) === 'true') {
            document.getElementById('admin-panel').classList.remove('hidden');
            document.getElementById('admin-login').classList.add('hidden');
            fetchRegistrations(); // بارگذاری اطلاعات ثبت‌نام
        }
    };
</script>
</body>
</html>
