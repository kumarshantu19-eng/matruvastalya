<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matruvastalya - Empowering Lives & Protecting Nature</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-50 text-gray-800 font-sans scroll-smooth">

    <!-- Announcement Bar -->
    <div class="bg-emerald-700 text-white text-xs sm:text-sm py-2 px-4 text-center">
        🎉 Join our upcoming Community Health & Tree Plantation Drive this Saturday! <a href="#contact" class="underline font-semibold ml-2">Contact Us</a>
    </div>

    <!-- Header / Navbar -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center h-16">
            <div class="text-2xl font-bold text-emerald-600 flex items-center space-x-2">
                <i class="fa-solid fa-hands-holding-child"></i>
                <span>Matruvastalya</span>
            </div>
            <nav class="hidden md:flex space-x-6 font-medium">
                <a href="#home" class="hover:text-emerald-600">Home</a>
                <a href="#about" class="hover:text-emerald-600">About Us</a>
                <a href="#causes" class="hover:text-emerald-600">Our Causes</a>
                <a href="#get-involved" class="hover:text-emerald-600">Get Involved</a>
                <a href="#contact" class="hover:text-emerald-600">Contact</a>
            </nav>
            <a href="#donate" class="bg-emerald-600 text-white px-5 py-2 rounded-full font-medium hover:bg-emerald-700 transition">Donate Now</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-emerald-900 text-white py-20 text-center px-4">
        <div class="max-w-3xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">Empowering Communities, Healing the Planet</h1>
            <p class="text-lg md:text-xl text-emerald-100 mb-8">We work tirelessly across Education, Healthcare, Environment, and Animal Welfare to bring positive change.</p>
            <div class="flex justify-center space-x-4">
                <a href="#causes" class="bg-white text-emerald-900 px-6 py-3 rounded-full font-bold hover:bg-emerald-50 transition">Explore Causes</a>
                <a href="#donate" class="border-2 border-white px-6 py-3 rounded-full font-bold hover:bg-white hover:text-emerald-900 transition">Support Us</a>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-3xl font-bold text-gray-900 mb-4">About Matruvastalya</h2>
                <p class="text-gray-600 mb-4">Matruvastalya is dedicated to uplifting underprivileged communities and protecting our natural ecosystem. Founded with a vision of compassion and service, we strive to bridge gaps in education and healthcare while championing environmental and animal welfare.</p>
                <p class="text-gray-600">Our mission is to create a sustainable, inclusive society where every child gets education, every sick person gets care, and nature thrives.</p>
            </div>
            <div class="bg-emerald-100 p-8 rounded-2xl shadow-inner border border-emerald-200">
                <h3 class="text-2xl font-bold text-emerald-900 mb-4">Our Vision & Values</h3>
                <ul class="space-y-3 text-emerald-800 font-medium">
                    <li><i class="fa-solid fa-check text-emerald-600 mr-2"></i> Transparent & Impact-Driven Operations</li>
                    <li><i class="fa-solid fa-check text-emerald-600 mr-2"></i> Grassroots Community Engagement</li>
                    <li><i class="fa-solid fa-check text-emerald-600 mr-2"></i> Sustainable Environmental Protection</li>
                    <li><i class="fa-solid fa-check text-emerald-600 mr-2"></i> Compassion for All Living Beings</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Causes Section -->
    <section id="causes" class="py-16 bg-gray-100 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-900">Our Core Pillars</h2>
                <p class="text-gray-600 mt-2">How we are making an impact every single day.</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Education -->
                <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
                    <div class="text-emerald-600 text-3xl mb-4"><i class="fa-solid fa-book-open"></i></div>
                    <h3 class="text-xl font-bold mb-2">Education</h3>
                    <p class="text-gray-600 text-sm">Providing quality learning resources, scholarships, and schooling support for underprivileged children.</p>
                </div>
                <!-- Healthcare -->
                <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
                    <div class="text-emerald-600 text-3xl mb-4"><i class="fa-solid fa-hospital"></i></div>
                    <h3 class="text-xl font-bold mb-2">Healthcare</h3>
                    <p class="text-gray-600 text-sm">Organizing health check-up camps, mobile clinics, and distributing essential medicines in rural areas.</p>
                </div>
                <!-- Environment -->
                <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
                    <div class="text-emerald-600 text-3xl mb-4"><i class="fa-solid fa-seedling"></i></div>
                    <h3 class="text-xl font-bold mb-2">Environment</h3>
                    <p class="text-gray-600 text-sm">Conducting massive tree plantation drives, water conservation projects, and cleanliness campaigns.</p>
                </div>
                <!-- Animal Welfare -->
                <div class="bg-white p-6 rounded-xl shadow hover:shadow-lg transition">
                    <div class="text-emerald-600 text-3xl mb-4"><i class="fa-solid fa-paw"></i></div>
                    <h3 class="text-xl font-bold mb-2">Animal Welfare</h3>
                    <p class="text-gray-600 text-sm">Running rescue shelters, emergency medical aid, and vaccination/adoption programs for stray animals.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Get Involved Section -->
    <section id="get-involved" class="py-16 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h2 class="text-3xl font-bold text-gray-900 mb-4">Get Involved</h2>
        <p class="text-gray-600 max-w-2xl mx-auto mb-8">You don't need to change the world alone. Join our community of volunteers and changemakers today.</p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white p-6 rounded-xl shadow border border-gray-100">
                <h3 class="text-xl font-bold text-emerald-700 mb-2">Become a Volunteer</h3>
                <p class="text-gray-600 text-sm mb-4">Give your time and skills to our field operations, teaching programs, or drives.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow border border-gray-100">
                <h3 class="text-xl font-bold text-emerald-700 mb-2">Partner with Us</h3>
                <p class="text-gray-600 text-sm mb-4">Collaborate as corporate partners, educational institutions, or community groups.</p>
            </div>
            <div class="bg-white p-6 rounded-xl shadow border border-gray-100">
                <h3 class="text-xl font-bold text-emerald-700 mb-2">Spread the Word</h3>
                <p class="text-gray-600 text-sm mb-4">Share our mission on social media and inspire others to support our cause.</p>
            </div>
        </div>
    </section>

    <!-- Donate Section -->
    <section id="donate" class="py-16 bg-emerald-800 text-white text-center px-4">
        <div class="max-w-2xl mx-auto">
            <h2 class="text-3xl font-bold mb-4">Support Our Cause</h2>
            <p class="text-emerald-100 mb-6">Your small contribution can light up a child's future, heal a stray animal, or plant a sapling.</p>
            <div class="bg-white text-gray-900 p-6 rounded-xl inline-block shadow-lg">
                <p class="font-bold text-lg mb-2">Bank / UPI Donation Details</p>
                <p class="text-sm text-gray-600">UPI ID: <span class="font-semibold text-emerald-700">matruvastalya@upi</span></p>
                <p class="text-sm text-gray-600 mt-1">Account Name: Matruvastalya Trust</p>
            </div>
        </div>
    </section>

    <!-- Footer / Contact Section -->
    <footer id="contact" class="bg-gray-900 text-white py-12 px-4">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
            <div>
                <h3 class="text-xl font-bold text-emerald-400 mb-3">Matruvastalya</h3>
                <p class="text-gray-400 text-sm">Working together for a better, compassionate, and greener tomorrow.</p>
            </div>
            <div>
                <h4 class="font-bold mb-3">Quick Links</h4>
                <ul class="space-y-2 text-gray-400 text-sm">
                    <li><a href="#about" class="hover:text-white">About Us</a></li>
                    <li><a href="#causes" class="hover:text-white">Our Causes</a></li>
                    <li><a href="#get-involved" class="hover:text-white">Get Involved</a></li>
                    <li><a href="#donate" class="hover:text-white">Donate</a></li>
                </ul>
            </div>
            <div>
                <h4 class="font-bold mb-3">Contact Us</h4>
                <p class="text-gray-400 text-sm"><i class="fa-solid fa-envelope mr-2"></i> info@matruvastalya.org</p>
                <p class="text-gray-400 text-sm mt-1"><i class="fa-solid fa-phone mr-2"></i> +91 98765 43210</p>
            </div>
        </div>
        <div class="border-t border-gray-800 pt-6 text-center text-gray-500 text-sm">
            &copy; 2026 Matruvastalya NGO. All Rights Reserved.
        </div>
    </footer>

</body>
</html>
