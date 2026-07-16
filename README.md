## Hi there 👋

<!--
**shuja-graphics/Shuja-graphics** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shuja Graphics | Creative Graphic Designer Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            dark: '#0B0F19',
                            card: '#161B26',
                            accent: '#6366F1', // Indigo accent
                            accentHover: '#4F46E5',
                            textMuted: '#9CA3AF'
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-brand-dark text-white font-sans antialiased selection:bg-brand-accent selection:text-white">

    <!-- Header / Navigation -->
    <header class="fixed top-0 left-0 w-full z-50 bg-brand-dark/80 backdrop-blur-md border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="text-2xl font-extrabold tracking-wider bg-gradient-to-r from-brand-accent to-purple-400 bg-clip-text text-transparent">
                SHUJA<span class="text-white">.GRAPHICS</span>
            </a>
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#work" class="hover:text-brand-accent transition-colors">Work</a>
                <a href="#services" class="hover:text-brand-accent transition-colors">Services</a>
                <a href="#about" class="hover:text-brand-accent transition-colors">About</a>
                <a href="#contact" class="px-5 py-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full transition-all duration-300 transform hover:-translate-y-0.5">Let's Talk</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(circle_at_top_right,rgba(99,102,241,0.15),transparent_45%)]"></div>
        <div class="max-w-4xl mx-auto px-6 text-center z-10">
            <span class="inline-block px-4 py-1.5 mb-6 text-xs font-semibold tracking-widest text-brand-accent uppercase bg-brand-accent/10 rounded-full border border-brand-accent/20">
                Available for Freelance & Contract
            </span>
            <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight leading-tight mb-6">
                Turning Bold Concepts Into <br>
                <span class="bg-gradient-to-r from-brand-accent to-purple-400 bg-clip-text text-transparent">Visual Masterpieces</span>
            </h1>
            <p class="text-lg md:text-xl text-brand-textMuted max-w-2xl mx-auto mb-10 font-light">
                High-impact poster designs, modern brand identities, and custom digital assets tailored to make your message impossible to ignore.
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="#work" class="w-full sm:w-auto px-8 py-4 bg-brand-accent hover:bg-brand-accentHover text-white font-semibold rounded-lg shadow-lg shadow-brand-accent/20 transition-all duration-300">
                    View Portfolio
                </a>
                <a href="#contact" class="w-full sm:w-auto px-8 py-4 bg-transparent hover:bg-white/5 text-white font-semibold rounded-lg border border-gray-700 transition-all duration-300">
                    Get a Quote
                </a>
            </div>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="work" class="py-24 border-t border-gray-900 bg-brand-dark/50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-16">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold mb-4">Featured Work</h2>
                    <p class="text-brand-textMuted">A selection of recent digital edits, branding projects, and layouts.</p>
                </div>
            </div>

            <!-- Portfolio Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project Card 1 -->
                <div class="group relative bg-brand-card rounded-2xl overflow-hidden border border-gray-800 hover:border-brand-accent/50 transition-all duration-300">
                    <div class="aspect-[4/5] bg-gray-800 overflow-hidden relative">
                        <!-- Placeholder Image (Replace with your actual design file path) -->
                        <img src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?auto=format&fit=crop&w=800&q=80" alt="Creative Poster Design" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-dark via-transparent to-transparent opacity-80"></div>
                    </div>
                    <div class="p-6 absolute bottom-0 left-0 w-full">
                        <span class="text-xs font-semibold text-brand-accent uppercase tracking-wider">Poster Design</span>
                        <h3 class="text-xl font-bold mt-1 text-white">Conceptual Event Flyer</h3>
                    </div>
                </div>

                <!-- Project Card 2 -->
                <div class="group relative bg-brand-card rounded-2xl overflow-hidden border border-gray-800 hover:border-brand-accent/50 transition-all duration-300">
                    <div class="aspect-[4/5] bg-gray-800 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1626785774573-4b799315345d?auto=format&fit=crop&w=800&q=80" alt="Brand Identity" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-dark via-transparent to-transparent opacity-80"></div>
                    </div>
                    <div class="p-6 absolute bottom-0 left-0 w-full">
                        <span class="text-xs font-semibold text-brand-accent uppercase tracking-wider">Branding</span>
                        <h3 class="text-xl font-bold mt-1 text-white">Modern Identity Design</h3>
                    </div>
                </div>

                <!-- Project Card 3 -->
                <div class="group relative bg-brand-card rounded-2xl overflow-hidden border border-gray-800 hover:border-brand-accent/50 transition-all duration-300">
                    <div class="aspect-[4/5] bg-gray-800 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?auto=format&fit=crop&w=800&q=80" alt="Social Media Assets" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-dark via-transparent to-transparent opacity-80"></div>
                    </div>
                    <div class="p-6 absolute bottom-0 left-0 w-full">
                        <span class="text-xs font-semibold text-brand-accent uppercase tracking-wider">Digital Media</span>
                        <h3 class="text-xl font-bold mt-1 text-white">Social Feed Kit</h3>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 border-t border-gray-950">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Core Creative Services</h2>
                <p class="text-brand-textMuted">Tailored graphic solutions built to elevate your brand presence across physical and digital mediums.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="p-8 bg-brand-card rounded-2xl border border-gray-800 hover:border-gray-700 transition-all duration-300 group">
                    <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-brand-accent/10 text-brand-accent mb-6 group-hover:bg-brand-accent group-hover:text-white transition-all duration-300">
                        <i class="fa-solid fa-palette text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Custom Layouts & Poster Design</h3>
                    <p class="text-brand-textMuted text-sm leading-relaxed">
                        Eye-catching, structured posters and flyers designed to communicate clearly and dominate visual feeds.
                    </p>
                </div>

                <!-- Service 2 -->
                <div class="p-8 bg-brand-card rounded-2xl border border-gray-800 hover:border-gray-700 transition-all duration-300 group">
                    <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-brand-accent/10 text-brand-accent mb-6 group-hover:bg-brand-accent group-hover:text-white transition-all duration-300">
                        <i class="fa-solid fa-bezier-curve text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Brand Identity & Assets</h3>
                    <p class="text-brand-textMuted text-sm leading-relaxed">
                        From striking typography setups to cohesive digital assets that set your project or business apart.
                    </p>
                </div>

                <!-- Service 3 -->
                <div class="p-8 bg-brand-card rounded-2xl border border-gray-800 hover:border-gray-700 transition-all duration-300 group">
                    <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-brand-accent/10 text-brand-accent mb-6 group-hover:bg-brand-accent group-hover:text-white transition-all duration-300">
                        <i class="fa-solid fa-wand-magic-sparkles text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Photo Editing & Manipulation</h3>
                    <p class="text-brand-textMuted text-sm leading-relaxed">
                        Seamless digital composition, advanced blending, and aesthetic corrections to craft a unified visual style.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-24 border-t border-gray-900 bg-brand-dark/30">
        <div class="max-w-5xl mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
                <div class="md:col-span-5 relative">
                    <div class="aspect-square bg-gradient-to-tr from-brand-accent to-purple-600 rounded-2xl overflow-hidden p-1">
                        <div class="w-full h-full bg-brand-card rounded-2xl flex items-center justify-center">
                            <!-- Replace with a professional avatar / camera vector / portrait -->
                            <i class="fa-solid fa-signature text-7xl text-brand-accent/30"></i>
                        </div>
                    </div>
                </div>
                <div class="md:col-span-7">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6">About Shuja Graphics</h2>
                    <p class="text-brand-textMuted leading-relaxed mb-6">
                        Hi, I’m a passionate graphic designer dedicated to transforming concepts into polished visual art. Specializing in balance, structured layout patterns, and color harmony, I focus on building impactful assets that stay with the audience long after they’ve looked away.
                    </p>
                    <p class="text-brand-textMuted leading-relaxed mb-6">
                        Whether you need highly detailed event flyers, striking digital content for social media, or a fresh identity for your project, I mix technical precision with creative styling to get the job done right.
                    </p>
                    <div class="flex items-center gap-6">
                        <div>
                            <span class="block text-2xl font-bold text-white">99%</span>
                            <span class="text-xs text-brand-textMuted">Project Satisfaction</span>
                        </div>
                        <div class="h-8 w-px bg-gray-800"></div>
                        <div>
                            <span class="block text-2xl font-bold text-white">Fast</span>
                            <span class="text-xs text-brand-textMuted">Turnaround Times</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 border-t border-gray-950">
        <div class="max-w-4xl mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Start a Project</h2>
                <p class="text-brand-textMuted">Ready to bring your ideas to life? Fill out the details below, and let’s create something incredible together.</p>
            </div>

            <div class="bg-brand-card p-8 md:p-10 rounded-2xl border border-gray-800">
                <form action="#" method="POST" class="space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-xs font-semibold text-brand-textMuted uppercase tracking-wider mb-2" for="name">Your Name</label>
                            <input type="text" id="name" required class="w-full bg-brand-dark border border-gray-800 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-brand-accent transition-colors">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-brand-textMuted uppercase tracking-wider mb-2" for="email">Email Address</label>
                            <input type="email" id="email" required class="w-full bg-brand-dark border border-gray-800 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-brand-accent transition-colors">
                        </div>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-brand-textMuted uppercase tracking-wider mb-2" for="project-type">What type of project?</label>
                        <select id="project-type" class="w-full bg-brand-dark border border-gray-800 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-brand-accent transition-colors">
                            <option>Poster & Flyer Design</option>
                            <option>Social Media Assets</option>
                            <option>Brand Identity / Logo</option>
                            <option>Other Creative Assets</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-semibold text-brand-textMuted uppercase tracking-wider mb-2" for="message">Project Details</label>
                        <textarea id="message" rows="4" required placeholder="Describe your design needs..." class="w-full bg-brand-dark border border-gray-800 rounded-lg px-4 py-3 text-white focus:outline-none focus:border-brand-accent transition-colors"></textarea>
                    </div>
                    <button type="submit" class="w-full py-4 bg-brand-accent hover:bg-brand-accentHover text-white font-bold rounded-lg transition-colors">
                        Send Message
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 border-t border-gray-900 bg-brand-dark/80 text-center">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
            <span class="text-sm text-brand-textMuted">&copy; 2026 Shuja Graphics. All rights reserved.</span>
            <div class="flex space-x-6 text-brand-textMuted">
                <a href="#" class="hover:text-brand-accent"><i class="fa-brands fa-behance text-lg"></i></a>
                <a href="#" class="hover:text-brand-accent"><i class="fa-brands fa-dribbble text-lg"></i></a>
                <a href="#" class="hover:text-brand-accent"><i class="fa-brands fa-instagram text-lg"></i></a>
                <a href="#" class="hover:text-brand-accent"><i class="fa-brands fa-pinterest text-lg"></i></a>
            </div>
        </div>
    </footer>

</body>
</html>

-->

## 📱 Contact Information

**WhatsApp:** 03700081212
