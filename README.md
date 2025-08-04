<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZAUQ - Elegance in Every Detail</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <style>
        html {
            scroll-behavior: smooth;
        }

        body {
            background-color: #000;
            color: #FFD700;
            font-family: 'Segoe UI', sans-serif;
        }
    </style>
</head>

<body class="bg-black text-yellow-300">

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-black to-gray-900 py-20 text-center text-white" data-aos="fade-down">
        <h1 class="text-5xl md:text-7xl font-bold mb-4 tracking-widest animate-pulse">ZAUQ</h1>
        <p class="text-xl md:text-2xl text-gray-300 italic">Elegance in Every Detail</p>
    </section>

    <!-- Products Section -->
    <section class="py-16 px-4 max-w-6xl mx-auto">
        <h2 class="text-3xl font-semibold text-center text-white mb-12" data-aos="fade-up">Featured Products</h2>
        <div class="grid gap-10 md:grid-cols-2">
            <!-- Black Clover Chain -->
            <div class="bg-gray-900 shadow-xl rounded-2xl overflow-hidden transform transition duration-500 hover:scale-105" data-aos="zoom-in">
                <img src="black.jpg" alt="Black Clover Chain" class="w-full h-64 object-cover">
                <div class="p-6 text-white">
                    <h3 class="text-2xl font-bold mb-2">Black Clover Chain</h3>
                    <p class="text-gray-300 mb-4">Stylish gold-finish chain featuring elegant black clover charms. Perfect for bold looks.</p>
                    <div class="flex justify-between items-center">
                        <span class="text-xl font-bold text-yellow-400">PKR 399</span>
                        <a href="https://wa.me/923414503595" target="_blank" class="bg-green-500 text-white px-4 py-2 rounded-full hover:bg-green-600 transition-all">Order on WhatsApp</a>
                    </div>
                </div>
            </div>

            <!-- Bestie Heart & Bunny Locket -->
            <div class="bg-gray-900 shadow-xl rounded-2xl overflow-hidden transform transition duration-500 hover:scale-105" data-aos="zoom-in" data-aos-delay="100">
                <img src="bestie.jpg" alt="Bestie Locket" class="w-full h-64 object-cover">
                <div class="p-6 text-white">
                    <h3 class="text-2xl font-bold mb-2">Bestie Heart & Bunny Locket</h3>
                    <p class="text-gray-300 mb-4">Celebrate strong friendships with this adorable heart and bunny pendant combo.</p>
                    <div class="flex justify-between items-center">
                        <span class="text-xl font-bold text-yellow-400">PKR 599</span>
                        <a href="https://wa.me/923414503595" target="_blank" class="bg-green-500 text-white px-4 py-2 rounded-full hover:bg-green-600 transition-all">Order on WhatsApp</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="bg-gray-800 py-16" data-aos="fade-up">
        <div class="max-w-4xl mx-auto text-center text-white">
            <h2 class="text-3xl font-semibold mb-8">What Our Customers Say</h2>
            <div class="grid gap-8 md:grid-cols-2">
                <div class="bg-gray-900 p-6 rounded-xl shadow-md transform hover:scale-105 transition">
                    <p class="text-gray-300 italic">"Absolutely loved the chain! Looks even better in person."</p>
                    <p class="mt-4 font-semibold">– Sara A.</p>
                </div>
                <div class="bg-gray-900 p-6 rounded-xl shadow-md transform hover:scale-105 transition">
                    <p class="text-gray-300 italic">"Bought the bestie locket for my friend – she was obsessed!"</p>
                    <p class="mt-4 font-semibold">– Mehak R.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black text-white py-6 text-center">
        <p>&copy; 2025 ZAUQ. All rights reserved.</p>
    </footer>

    <!-- AOS Animation Init -->
    <script>
        AOS.init({
            duration: 1200,
            once: true
        });
    </script>

</body>

</html>
