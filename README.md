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
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
        }
        .project-card {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .project-card:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <!-- Navigation (Sticky to Top) -->
    <nav class="fixed top-0 w-full z-50 glass border-b border-slate-200">
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
                <h2 class="text-blue-600 font-semibold tracking-wide uppercase mb-2 text-sm uppercase">Welcome to my profile</h2>
                <h1 class="text-5xl md:text-6xl font-extrabold text-slate-900 mb-6 leading-tight">
                    I'm <span class="text-blue-600">HEND</span>, Trader & Web3 Developer.
                </h1>
                <p class="text-lg text-slate-600 mb-8 max-w-lg">
                    Building the decentralized future and analyzing market dynamics. Specializing in Smart Contract development and digital asset growth strategies.
                </p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-blue-600 text-white px-8 py-3 rounded-full font-semibold hover:bg-blue-700 transition shadow-lg shadow-blue-200 text-center text-sm md:text-base">
                        Hire Me
                    </a>
                    <a href="#portfolio" class="border border-slate-300 text-slate-700 px-8 py-3 rounded-full font-semibold hover:bg-slate-100 transition text-center text-sm md:text-base">
                        View Projects
                    </a>
                </div>
            </div>
            <div class="md:w-1/2 flex justify-center">
                <div class="relative w-64 h-64 md:w-80 md:h-80">
                    <div class="absolute inset-0 bg-blue-600 rounded-3xl rotate-6 opacity-20"></div>
                    <!-- Menggunakan avatar wolf sesuai referensi gambar terakhir -->
                    <img src="https://raw.githubusercontent.com/hendroah/Personal-data/75ff41d07aeb7619a516b339d6ad6393f149d84f/Desain%20tanpa%20judul_20260223_171612_0000.png" 
                         alt="HEND Profile Avatar" 
                         class="relative z-10 w-full h-full object-cover rounded-3xl shadow-2xl hover:scale-105 transition duration-500">
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">About Me</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8 rounded-full"></div>
            <p class="text-slate-600 leading-relaxed text-lg mb-6">
                I am a dedicated professional with over 5 years of experience in blockchain technology and financial markets. I am passionate about developing innovative Web3 solutions and conducting deep technical analysis to navigate market volatility.
            </p>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4 mt-12">
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">50+</h3>
                    <p class="text-sm text-slate-500">Smart Contracts</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">1k+</h3>
                    <p class="text-sm text-slate-500">Successful Trades</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">5+</h3>
                    <p class="text-sm text-slate-500">Years Exp.</p>
                </div>
                <div class="p-4 border border-slate-100 rounded-xl">
                    <h3 class="text-2xl font-bold text-blue-600">20+</h3>
                    <p class="text-sm text-slate-500">Web3 Projects</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 bg-slate-50">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Latest Projects</h2>
            
            <div class="grid grid-cols-1 gap-12">
                <!-- Project 1: Web3 Card UI (Portrait focus) -->
                <div class="flex justify-center">
                    <div class="bg-white max-w-sm w-full rounded-3xl overflow-hidden shadow-xl border border-slate-100 project-card flex flex-col">
                        <div class="p-4 bg-slate-50 flex justify-center">
                            <div class="relative w-full aspect-[3/4] shadow-lg rounded-2xl overflow-hidden border border-slate-200">
                                <img src="https://raw.githubusercontent.com/hendroah/Personal-data/ae89fd9527bc3550e085650de881b722d13e476a/card.gif" 
                                     alt="dApp Interface" 
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                        <div class="p-6">
                            <div class="mb-2 inline-block px-2 py-0.5 bg-blue-600 text-white text-[10px] font-bold rounded uppercase tracking-wider">
                                Interactive
                            </div>
                            <h3 class="text-xl font-bold text-slate-900 mb-2">Web3 Card UI</h3>
                            <p class="text-slate-600 text-sm mb-4">
                                Seamless user interface integration with high-performance blockchain functionalities.
                            </p>
                            <div class="flex gap-2">
                                <span class="px-2 py-1 bg-blue-50 text-blue-600 rounded text-[10px] font-bold">SOLIDITY</span>
                                <span class="px-2 py-1 bg-indigo-50 text-indigo-600 rounded text-[10px] font-bold">UI/UX</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Project 2: Market Analysis (Landscape) -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-xl border border-slate-100 project-card flex flex-col md:flex-row">
                    <div class="md:w-2/3 p-4 bg-slate-50">
                        <div class="relative w-full aspect-video shadow-lg rounded-2xl overflow-hidden border border-slate-200">
                            <img src="https://raw.githubusercontent.com/hendroah/Personal-data/d2c7c0a1281f2cb26f2c34f78bdcb6113cd80910/Screenshot_2026-02-20-12-09-25-181_com.tradingview.tradingviewapp.jpg" 
                                 alt="Market Analysis" 
                                 class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="md:w-1/3 p-8 flex flex-col justify-center">
                        <div class="mb-2 inline-block self-start px-2 py-0.5 bg-indigo-600 text-white text-[10px] font-bold rounded uppercase tracking-wider">
                            Trading
                        </div>
                        <h3 class="text-2xl font-bold text-slate-900 mb-3">Market Analysis</h3>
                        <p class="text-slate-600 mb-6">
                            Advanced technical indicator setups and strategic market psychology mapping for digital assets.
                        </p>
                        <div class="flex gap-2">
                            <span class="px-2 py-1 bg-blue-50 text-blue-600 rounded text-[10px] font-bold">ANALYSIS</span>
                            <span class="px-2 py-1 bg-indigo-50 text-indigo-600 rounded text-[10px] font-bold">CHARTS</span>
                        </div>
                    </div>
                </div>

                <!-- Project 3: Contract Audit (Landscape) -->
                <div class="bg-white rounded-3xl overflow-hidden shadow-xl border border-slate-100 project-card flex flex-col md:flex-row-reverse">
                    <div class="md:w-2/3 p-4 bg-slate-50">
                        <div class="relative w-full aspect-video shadow-lg rounded-2xl overflow-hidden border border-slate-200 bg-slate-900">
                            <img src="https://raw.githubusercontent.com/hendroah/Personal-data/16dacab4cc4fc421f732806935426d656b46d258/editor-without-bg.png" 
                                 alt="Contract Audit" 
                                 class="w-full h-full object-contain p-4">
                        </div>
                    </div>
                    <div class="md:w-1/3 p-8 flex flex-col justify-center">
                        <div class="mb-2 inline-block self-start px-2 py-0.5 bg-purple-600 text-white text-[10px] font-bold rounded uppercase tracking-wider">
                            Security
                        </div>
                        <h3 class="text-2xl font-bold text-slate-900 mb-3">Contract Audit</h3>
                        <p class="text-slate-600 mb-6">
                            In-depth security auditing and optimization for EVM-compatible smart contracts.
                        </p>
                        <div class="flex gap-2">
                            <span class="px-2 py-1 bg-blue-50 text-blue-600 rounded text-[10px] font-bold">SECURITY</span>
                            <span class="px-2 py-1 bg-indigo-50 text-indigo-600 rounded text-[10px] font-bold">BLOCKCHAIN</span>
                        </div>
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
                    <p class="text-slate-400 mb-8">Interested in Web3 project collaboration or market strategy discussion? Please reach out to me.</p>
                    <div class="space-y-4">
                        <div class="flex items-center space-x-4 text-slate-300">
                            <div class="w-10 h-10 bg-blue-600/20 text-blue-400 flex items-center justify-center rounded-full">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <span>hendroabdhh@gmail.com</span>
                        </div>
                        <div class="flex items-center space-x-4 text-slate-300">
                            <div class="w-10 h-10 bg-blue-600/20 text-blue-400 flex items-center justify-center rounded-full">
                                <i class="fas fa-phone"></i>
                            </div>
                            <span>+62 8123-890-4302</span>
                        </div>
                    </div>
                    
                    <!-- Social Links -->
                    <div class="mt-8">
                        <p class="text-sm font-semibold text-slate-500 uppercase tracking-wider mb-4">Connect with me</p>
                        <div class="flex space-x-5">
                            <a href="https://x.com/Hendroabdh_" target="_blank" class="text-2xl text-slate-400 hover:text-blue-400 transition" title="X (Twitter)">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="https://t.me/hnd229" target="_blank" class="text-2xl text-slate-400 hover:text-sky-400 transition" title="Telegram">
                                <i class="fab fa-telegram"></i>
                            </a>
                            <a href="https://discord.com/users/551796569935052830" target="_blank" class="text-2xl text-slate-400 hover:text-indigo-400 transition" title="Discord">
                                <i class="fab fa-discord"></i>
                            </a>
                            <a href="https://www.instagram.com/hendro_abdh?igsh=cG45Z21tdXJkaG9m" target="_blank" class="text-2xl text-slate-400 hover:text-pink-500 transition" title="Instagram">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </div>
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
                            Send Message
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 bg-slate-950 text-slate-500 text-center border-t border-slate-800">
        <p>&copy; 2024 HEND. Built with <i class="fas fa-heart text-red-500"></i></p>
    </footer>

    <script>
        // Smooth scroll for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href').startsWith('#')) {
                    e.preventDefault();
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        target.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                }
            });
        });

        // Simple form submission handler
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const successMsg = document.createElement('div');
            successMsg.className = 'mt-4 p-4 bg-green-100 text-green-700 rounded-lg text-center';
            successMsg.innerText = 'Your message has been sent! Thank you.';
            this.appendChild(successMsg);
            this.reset();
            setTimeout(() => successMsg.remove(), 5000);
        });
    </script>
</body>
</html>

