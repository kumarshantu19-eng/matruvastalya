<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Care Foundation | Empowering Communities & Nature</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-50 text-slate-800 font-sans">

    <!-- Top Announcement Bar -->
    <div class="bg-emerald-700 text-white text-xs sm:text-sm py-2 px-4 text-center">
        <span>📢 Join our upcoming Community Health & Tree Plantation Drive this Saturday! <a href="get-involved.html" class="underline font-semibold ml-1">Sign up now</a></span>
    </div>

    <!-- Navigation Bar -->
    <nav class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex items-center space-x-2">
                    <i class="fa-solid fa-hands-holding-child text-emerald-600 text-2xl"></i>
                    <span class="font-bold text-xl text-slate-900 tracking-tight">Global Care</span>
                </div>
                <div class="hidden md:flex space-x-8 items-center font-medium">
                    <a href="index.html" class="text-emerald-600 border-b-2 border-emerald-600 pb-1">Home</a>
                    <a href="causes.html" class="text-slate-600 hover:text-emerald-600 transition">Our Causes</a>
                    <a href="get-involved.html" class="text-slate-600 hover:text-emerald-600 transition">Get Involved</a>
                    <a href="donate.html" class="bg-emerald-600 text-white px-5 py-2 rounded-full hover:bg-emerald-700 transition shadow-sm">Donate Now</a>
                </div>
                <!-- Mobile Menu Button -->
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-slate-700 focus:outline-none">
                        <i class="fa-solid fa-bars text-2xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu Dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t px-4 pt-2 pb-4 space-y-3">
            <a href="index.html" class="block text-emerald-600 font-medium">Home</a>
            <a href="causes.html" class="block text-slate-600">Our Causes</a>
            <a href="get-involved.html" class="block text-slate-600">Get Involved</a>
            <a href="donate.html" class="block bg-emerald-600 text-white text-center py-2 rounded-lg">Donate Now</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative bg-slate-900 text-white overflow-hidden">
        <div class="absolute inset-0 opacity-40 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1532629345422-7515f3d16bb9?auto=format&fit=crop&q=80&w=1600');"></div>
        <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-28 sm:py-36 text-center">
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight mb-6">Empowering Lives, Protecting Our Planet</h1>
            <p class="max-w-2xl mx-auto text-lg sm:text-xl text-slate-200 mb-10">We bridge gaps in education, healthcare, environmental preservation, and animal welfare to build a compassionate, sustainable future.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="donate.html" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-8 py-4 rounded-xl shadow-lg transition">Support Our Mission</a>
                <a href="causes.html" class="bg-white/10 hover:bg-white/20 backdrop-blur border border-white/30 text-white font-bold px-8 py-4 rounded-xl transition">Explore Our Work</a>
            </div>
        </div>
    </header>

    <!-- Impact Counters -->
    <section class="bg-emerald-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
            <div>
                <p class="text-3xl sm:text-4xl font-black mb-1">15,000+</p>
                <p class="text-emerald-200 text-sm">Children Educated</p>
            </div>
            <div>
                <p class="text-3xl sm:text-4xl font-black mb-1">50,000+</p>
                <p class="text-emerald-200 text-sm">Patients Treated</p>
            </div>
            <div>
                <p class="text-3xl sm:text-4xl font-black mb-1">100k+</p>
                <p class="text-emerald-200 text-sm">Trees Planted</p>
            </div>
            <div>
                <p class="text-3xl sm:text-4xl font-black mb-1">8,500+</p>
                <p class="text-emerald-200 text-sm">Animals Rescued</p>
            </div>
        </div>
    </section>

    <!-- Core Pillars Overview -->
    <section class="py-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center max-w-3xl mx-auto mb-16">
            <h2 class="text-xs uppercase tracking-widest text-emerald-600 font-bold mb-2">What We Do</h2>
            <h3 class="text-3xl font-bold text-slate-900">Four Pillars of Sustainable Impact</h3>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <!-- Education -->
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100 hover:shadow-md transition">
                <div class="w-12 h-12 rounded-xl bg-amber-50 text-amber-600 flex items-center justify-center text-xl mb-4"><i class="fa-solid fa-graduation-cap"></i></div>
                <h4 class="font-bold text-xl mb-2">Education</h4>
                <p class="text-slate-600 text-sm mb-4">Providing school supplies, tuition support, and digital labs for underprivileged children.</p>
                <a href="causes.html" class="text-emerald-600 font-semibold text-sm hover:underline">Learn more &rarr;</a>
            </div>
            <!-- Health -->
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100 hover:shadow-md transition">
                <div class="w-12 h-12 rounded-xl bg-rose-50 text-rose-600 flex items-center justify-center text-xl mb-4"><i class="fa-solid fa-heart-pulse"></i></div>
                <h4 class="font-bold text-xl mb-2">Healthcare</h4>
                <p class="text-slate-600 text-sm mb-4">Running mobile health clinics, medical check-up camps, and wellness education in rural zones.</p>
                <a href="causes.html" class="text-emerald-600 font-semibold text-sm hover:underline">Learn more &rarr;</a>
            </div>
            <!-- Environment -->
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100 hover:shadow-md transition">
                <div class="w-12 h-12 rounded-xl bg-emerald-50 text-emerald-600 flex items-center justify-center text-xl mb-4"><i class="fa-solid fa-seedling"></i></div>
                <h4 class="font-bold text-xl mb-2">Environment</h4>
                <p class="text-slate-600 text-sm mb-4">Executing massive reforestation drives, clean water initiatives, and local waste cleanup campaigns.</p>
                <a href="causes.html" class="text-emerald-600 font-semibold text-sm hover:underline">Learn more &rarr;</a>
            </div>
            <!-- Animals -->
            <div class="bg-white rounded-2xl p-6 shadow-sm border border-slate-100 hover:shadow-md transition">
                <div class="w-12 h-12 rounded-xl bg-sky-50 text-sky-600 flex items-center justify-center text-xl mb-4"><i class="fa-solid fa-paw"></i></div>
                <h4 class="font-bold text-xl mb-2">Animal Welfare</h4>
                <p class="text-slate-600 text-sm mb-4">Operating emergency rescue shelters, stray vaccination drives, and safe adoption networks.</p>
                <a href="causes.html" class="text-emerald-600 font-semibold text-sm hover:underline">Learn more &rarr;</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-6">
            <div class="flex items-center space-x-2 text-white">
                <i class="fa-solid fa-hands-holding-child text-emerald-500 text-2xl"></i>
                <span class="font-bold text-xl">Global Care Foundation</span>
            </div>
            <p class="text-sm">&copy; 2026 Global Care Foundation. Registered Non-Profit Organization.</p>
            <div class="flex space-x-4">
                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-facebook text-lg"></i></a>
                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-twitter text-lg"></i></a>
                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-instagram text-lg"></i></a>
            </div>
        </div>
    </footer>

    <script>
        const btn = document.getElementById('mobile-menu-btn');
        const menu = document.getElementById('mobile-menu');
        btn.addEventListener('click', () => { menu.classList.toggle('hidden'); });
    </script>
</body>
</html>
