<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile | HEND</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .glass {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <span class="text-xl font-bold bg-gradient-to-r from-blue-600 to-indigo-600 bg-clip-text text-transparent">
                    HEND.
                </span>
                <div class="hidden md:flex space-x-8 font-medium">
                    <a href="#home" class="hover:text-blue-600 transition">Home</a>
                    <a href="#about" class="hover:text-blue-600 transition">About</a>
                    <a href="#skills" class="hover:text-blue-600 transition">Skills</a>
                    <a href="#portfolio" class="hover:text-blue-600 transition">Portfolio</a>
                    <a href="#contact" class="hover:text-blue-600 transition">Contact</a>
                </div>
                <button class="md:hidden text-2xl" id="menu-btn">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-32 pb-20 px-4">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h2 class="text-blue-600 font-semibold tracking-wide uppercase mb-2 text-sm">Welcome to my profile</h2>
                <h1 class="text-5xl md:text-6xl font-extrabold text-slate-900 mb-6 leading-tight">
                    I am <span class="text-blue-600">HEND</span>, Artist & Trader.
                </h1>
                <p class="text-lg text-slate-600 mb-8 max-w-lg">
                    Blending creative vision with market analysis. I focus on aesthetic expression and strategic growth. Let's work together to bring your ideas to life.
                </p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-blue-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-blue-700 transition shadow-lg shadow-blue-200">
                        Contact Me
                    </a>
                    <a href="#portfolio" class="border border-slate-300 text-slate-700 px-8 py-3 rounded-full font-semibold hover:bg-slate-100 transition">
                        View Work
                    </a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative w-64 h-64 md:w-80 md:h-80">
                    <div class="absolute inset-0 bg-blue-600 rounded-3xl rotate-6 opacity-20"></div>
                    <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?fit=crop&w=800&q=80" 
                         alt="HEND Profile Photo" 
                         class="relative z-10 w-full h-full object-cover rounded-3xl shadow-2xl grayscale hover:grayscale-0 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">About Me</h2>
            <p class="text-slate-600 leading-relaxed text-lg mb-6">
                I am a dedicated professional with over 5 years of experience in creative arts and financial markets. I am passionate about exploring the intersection of visual aesthetics and technical analysis.
            </p>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-12">
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">100+</h3>
                    <p class="text-sm text-slate-500">Artworks Created</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">500+</h3>
                    <p class="text-sm text-slate-500">Successful Trades</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">5+</h3>
                    <p class="text-sm text-slate-500">Years Experience</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">15</h3>
                    <p class="text-sm text-slate-500">Exhibitions</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-slate-50">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">My Skills</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Skill 1 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="w-12 h-12 bg-blue-100 text-blue-600 flex items-center justify-center rounded-lg mb-6 text-xl">
                        <i class="fas fa-palette"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Digital Art</h3>
                    <p class="text-slate-600">Specializing in digital illustration, concept art, and high-fidelity visual storytelling.</p>
                </div>
                <!-- Skill 2 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="w-12 h-12 bg-indigo-100 text-indigo-600 flex items-center justify-center rounded-lg mb-6 text-xl">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Technical Analysis</h3>
                    <p class="text-slate-600">Expertise in price action, market psychology, and risk management strategies.</p>
                </div>
                <!-- Skill 3 -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="w-12 h-12 bg-purple-100 text-purple-600 flex items-center justify-center rounded-lg mb-6 text-xl">
                        <i class="fas fa-coins"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Crypto Assets</h3>
                    <p class="text-slate-600">In-depth knowledge of blockchain technology and decentralized finance ecosystems.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Recent Works</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1579783902614-a3fb3927b6a5?fit=crop&w=800&q=80" alt="Art Portfolio" class="w-full h-64 object-cover transform group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6 text-white opacity-0 group-hover:opacity-100 transition">
                        <h4 class="text-lg font-bold">Neo-Abstract Series</h4>
                        <p class="text-sm">Digital Art</p>
                    </div>
                </div>
                <!-- Project 2 -->
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1611974714851-eb6053e62359?fit=crop&w=800&q=80" alt="Trading Portfolio" class="w-full h-64 object-cover transform group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6 text-white opacity-0 group-hover:opacity-100 transition">
                        <h4 class="text-lg font-bold">Market Analysis Dashboard</h4>
                        <p class="text-sm">Trading Strategy</p>
                    </div>
                </div>
                <!-- Project 3 -->
                <div class="group relative overflow-hidden rounded-2xl">
                    <img src="https://images.unsplash.com/photo-1620641788421-7a1c342ea42e?fit=crop&w=800&q=80" alt="Creative Portfolio" class="w-full h-64 object-cover transform group-hover:scale-110 transition duration-500">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 to-transparent flex flex-col justify-end p-6 text-white opacity-0 group-hover:opacity-100 transition">
                        <h4 class="text-lg font-bold">Cyberpunk Environment</h4>
                        <p class="text-sm">Concept Design</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-slate-900 text-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="grid md:grid-cols-2 gap-12">
                <div>
                    <h2 class="text-3xl font-bold mb-6">Contact HEND</h2>
                    <p class="text-slate-400 mb-8">Have a creative inquiry or want to discuss market trends? Please send a message below.</p>
                    <div class="space-y-4">
                        <div class="flex items-center space-x-4">
                            <div class="w-10 h-10 bg-blue-600/20 text-blue-400 flex items-center justify-center rounded-full">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <span>hendroabdhh@gmail.com</span>
                        </div>
                        <div class="flex items-center space-x-4">
                            <div class="w-10 h-10 bg-blue-600/20 text-blue-400 flex items-center justify-center rounded-full">
                                <i class="fas fa-phone"></i>
                            </div>
                            <span>+62 8123-890-4302</span>
                        </div>
                    </div>
                    <div class="flex space-x-4 mt-8">
                        <!-- Twitter link updated -->
                        <a href="https://x.com/Hendroabdh_" target="_blank" class="text-2xl hover:text-blue-400 transition" title="Visit Twitter Profile">
                            <i class="fab fa-twitter"></i>
                        </a>
                        <a href="#" class="text-2xl hover:text-blue-400 transition" title="Visit Instagram Profile">
                            <i class="fab fa-instagram"></i>
                        </a>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-2xl text-slate-900 shadow-xl">
                    <form id="contactForm" class="space-y-4">
                        <div>
                            <label class="block text-sm font-semibold mb-1">Full Name</label>
                            <input type="text" class="w-full px-4 py-2 border border-slate-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required>
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-1">Email Address</label>
                            <input type="email" class="w-full px-4 py-2 border border-slate-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required>
                        </div>
                        <div>
                            <label class="block text-sm font-semibold mb-1">Message</label>
                            <textarea rows="4" class="w-full px-4 py-2 border border-slate-200 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" required></textarea>
                        </div>
                        <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded-lg font-bold hover:bg-blue-700 transition">
                            Send Inquiry
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-slate-950 text-slate-500 text-center border-t border-slate-800">
        <p>&copy; 2024 HEND. Created with <i class="fas fa-heart text-red-500"></i></p>
    </footer>

    <script>
        // Smooth scroll for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                // Only prevent default if it's an internal hash link
                if (this.getAttribute('href').startsWith('#')) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Simple Form Submission Handler
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const successMsg = document.createElement('div');
            successMsg.className = 'mt-4 p-4 bg-green-100 text-green-700 rounded-lg text-center';
            successMsg.innerText = 'Your message has been sent! Thank you.';
            this.appendChild(successMsg);
            this.reset();
            setTimeout(() => successMsg.remove(), 5000);
        });

        // Mobile Menu Logic
        const btn = document.getElementById('menu-btn');
        btn.addEventListener('click', () => {
            console.log("Mobile menu activated");
        });
    </script>
</body>
</html>

