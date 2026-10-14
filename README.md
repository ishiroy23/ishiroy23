<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biswajeet Parida | Digital Growth & Automation</title>
    
    <!-- Primary Meta Tags -->
    <meta name="title" content="Biswajeet Parida | Digital Marketing Strategist">
    <meta name="description" content="Portfolio of Biswajeet Parida, a Digital Marketing Strategist specializing in marketing automation, SEO, and data visualization based in Ahmedabad.">
    
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-B5ERB8DNP6"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'G-B5ERB8DNP6');
    </script>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Space+Grotesk:wght@500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Icons & Animations -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.css" rel="stylesheet">
    
    <!-- Chart.js -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        display: ['Space Grotesk', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0fdfa',
                            100: '#ccfbf1',
                            500: '#14b8a6', // Teal accent
                            900: '#134e4a',
                            dark: '#0f172a', // Slate 900
                        }
                    }
                }
            }
        }
    </script>

    <style>
        body {
            background-color: #fafafa;
            color: #334155;
            overflow-x: hidden;
        }

        .bg-grid {
            background-size: 40px 40px;
            background-image: linear-gradient(to right, rgba(0, 0, 0, 0.05) 1px, transparent 1px),
                              linear-gradient(to bottom, rgba(0, 0, 0, 0.05) 1px, transparent 1px);
            mask-image: linear-gradient(to bottom, black 40%, transparent 100%);
            -webkit-mask-image: linear-gradient(to bottom, black 40%, transparent 100%);
        }

        .card-hover {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .card-hover:hover {
            transform: translateY(-4px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.01);
            border-color: #cbd5e1;
        }

        .project-card {
            transition: opacity 0.3s ease, transform 0.3s ease;
        }

        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-track { background: transparent; }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 3px; }
        ::-webkit-scrollbar-thumb:hover { background: #94a3b8; }

        .timeline-line::before {
            content: '';
            position: absolute;
            top: 0; bottom: 0; left: 24px; width: 2px;
            background: #e2e8f0;
            z-index: 0;
        }
    </style>
</head>
<body class="antialiased selection:bg-brand-500 selection:text-white">

    <nav class="fixed w-full top-0 z-50 bg-white/80 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#" class="font-display font-bold text-xl tracking-tight text-brand-dark">
                Biswajeet<span class="text-brand-500">.</span>
            </a>
            
            <div class="hidden md:flex gap-8 text-sm font-medium text-slate-600">
                <a href="#work" class="hover:text-brand-500 transition-colors">Featured Work</a>
                <a href="#experience" class="hover:text-brand-500 transition-colors">Experience</a>
                <a href="#education" class="hover:text-brand-500 transition-colors">Education</a>
                <a href="#certifications" class="hover:text-brand-500 transition-colors">Certs</a>
            </div>

            <div class="flex items-center gap-4">
                <a href="mailto:biswajeetkumarp@gmail.com" class="hidden sm:flex bg-brand-dark text-white px-5 py-2.5 rounded-lg text-sm font-medium hover:bg-slate-800 transition-colors">
                    Let's Talk
                </a>
                <button id="menu-btn" class="md:hidden text-slate-600 hover:text-brand-500 focus:outline-none" aria-label="Toggle Mobile Menu">
                    <i class="fa-solid fa-bars fa-lg"></i>
                </button>
            </div>
        </div>
        
        <div id="mobile-menu" class="hidden absolute top-20 left-0 w-full bg-white border-b border-slate-200 shadow-lg">
            <div class="flex flex-col space-y-4 p-6 text-sm font-medium text-slate-600">
                <a href="#work" class="hover:text-brand-500 block py-2">Featured Work</a>
                <a href="#experience" class="hover:text-brand-500 block py-2">Experience</a>
                <a href="#education" class="hover:text-brand-500 block py-2">Education</a>
                <a href="#certifications" class="hover:text-brand-500 block py-2">Certifications</a>
            </div>
        </div>
    </nav>

    <section id="home" class="relative pt-40 pb-20 overflow-hidden">
        <div class="absolute inset-0 bg-grid pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="max-w-4xl" data-aos="fade-up">
                <div class="inline-flex items-center gap-2 px-3 py-1.5 bg-brand-50 border border-brand-100 text-brand-900 rounded-full text-xs font-semibold uppercase tracking-wider mb-8">
                    <span class="w-2 h-2 rounded-full bg-brand-500 animate-pulse"></span>
                    Available for Digital Marketing Roles
                </div>
                
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-display font-extrabold text-brand-dark tracking-tight leading-[1.1] mb-8">
                    Architecting <br/>
                    <span class="text-brand-500">Digital Growth.</span>
                </h1>
                
                <p class="text-lg md:text-xl text-slate-500 leading-relaxed max-w-2xl mb-10">
                    I combine <span class="text-slate-800 font-semibold">marketing automation</span>, <span class="text-slate-800 font-semibold">performance SEO</span>, and <span class="text-slate-800 font-semibold">data visualization</span> to scale brands and drive measurable ROI. Based in Ahmedabad.
                </p>
                
                <div class="flex flex-wrap gap-4">
                    <a href="#work" class="bg-brand-500 text-white px-7 py-3.5 rounded-lg font-medium hover:bg-teal-400 transition-transform hover:scale-105 flex items-center gap-2 shadow-lg shadow-brand-500/20">
                        View Portfolio <i class="fa-solid fa-arrow-down text-sm"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/biswajeet-marketing" target="_blank" rel="noopener noreferrer" class="bg-white text-slate-700 border border-slate-200 px-7 py-3.5 rounded-lg font-medium hover:bg-slate-50 hover:border-slate-300 transition-colors flex items-center gap-2 shadow-sm">
                        <i class="fa-brands fa-linkedin text-[#0A66C2]"></i> LinkedIn
                    </a>
                    <a href="https://drive.google.com/file/d/1xkI-SJkHXlzLqY5tJENBqVXJEDP6NQYG/view?usp=sharing" target="_blank" rel="noopener noreferrer" class="bg-white text-slate-700 border border-slate-200 px-7 py-3.5 rounded-lg font-medium hover:bg-slate-50 hover:border-slate-300 transition-colors flex items-center gap-2 shadow-sm">
                        <i class="fa-solid fa-file-pdf text-rose-500"></i> Resume
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats & Tech Bento -->
    <section class="py-10 px-6 max-w-7xl mx-auto z-20 relative">
        <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-4 auto-rows-auto md:auto-rows-[200px]">
            
            <div class="bg-white rounded-3xl p-6 md:p-8 border border-slate-200 shadow-sm col-span-1 md:col-span-2 lg:col-span-2 flex flex-col justify-between card-hover" data-aos="fade-up" data-aos-delay="50">
                <div class="flex justify-between items-start">
                    <div class="w-12 h-12 bg-slate-50 text-slate-600 rounded-full flex items-center justify-center border border-slate-100">
                        <i class="fa-solid fa-location-dot text-xl"></i>
                    </div>
                    <span class="text-[10px] font-bold text-slate-400 uppercase tracking-widest bg-slate-50 px-3 py-1 rounded-full border border-slate-100">Base Location</span>
                </div>
                <div class="mt-4 md:mt-0">
                    <h3 class="text-2xl md:text-3xl font-bold font-display text-brand-dark mb-1">Ahmedabad, India</h3>
                    <p class="text-sm text-slate-500 font-medium">Open to Remote / Relocation</p>
                </div>
            </div>

            <div class="rounded-3xl p-6 md:p-8 border border-slate-200 shadow-sm col-span-1 md:col-span-1 lg:col-span-2 flex flex-col justify-between card-hover relative overflow-hidden group" data-aos="fade-up" data-aos-delay="100">
                <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=800&q=80" class="absolute inset-0 w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" alt="Workspace">
                <div class="absolute inset-0 bg-gradient-to-t from-brand-dark/95 via-brand-dark/60 to-transparent"></div>
                
                <div class="relative z-10 flex justify-between items-start h-full flex-col">
                    <div class="px-3 py-1 bg-white/10 backdrop-blur-md border border-white/20 rounded-full text-xs font-bold text-white mb-4">Current Role</div>
                    <div>
                        <h3 class="text-xl md:text-2xl font-bold font-display text-white mb-1">Digital Marketing Specialist</h3>
                        <p class="text-sm text-brand-100 font-medium">@ Om Space Rocket & Exploration</p>
                    </div>
                </div>
            </div>

            <div class="bg-brand-dark rounded-3xl p-6 md:p-8 border border-slate-800 shadow-lg col-span-1 flex flex-col items-center justify-center text-center card-hover relative overflow-hidden" data-aos="fade-up" data-aos-delay="150">
                <div class="absolute -right-4 -bottom-4 w-32 h-32 bg-brand-500/20 rounded-full blur-3xl"></div>
                <h2 class="text-5xl md:text-6xl font-black font-display text-white mb-2 relative z-10">660<span class="text-brand-500">K+</span></h2>
                <p class="text-xs text-slate-400 font-medium relative z-10 uppercase tracking-wide">Multi-Sprint Organic Reach</p>
            </div>

            <div class="bg-white rounded-3xl p-6 md:p-8 border border-slate-200 shadow-sm col-span-1 flex flex-col items-center justify-center text-center card-hover" data-aos="fade-up" data-aos-delay="200">
                <h2 class="text-5xl md:text-6xl font-black font-display text-brand-dark mb-2"><span class="text-brand-500">+</span>680</h2>
                <p class="text-xs text-slate-500 font-medium uppercase tracking-wide">July Organic Followers</p>
            </div>

            <div class="bg-white rounded-3xl p-6 md:p-8 border border-slate-200 shadow-sm col-span-1 md:col-span-3 lg:col-span-2 flex flex-col justify-between card-hover" data-aos="fade-up" data-aos-delay="250">
                <div class="flex justify-between items-start mb-6">
                    <h3 class="text-[10px] font-bold text-slate-400 uppercase tracking-widest bg-slate-50 px-3 py-1 rounded-full border border-slate-100">Technical Arsenal</h3>
                </div>
                <div class="flex flex-wrap gap-2.5">
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Pabbly</span>
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Google Analytics 4</span>
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Power BI</span>
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Zoho CRM</span>
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Advanced SEO</span>
                    <span class="px-4 py-2 bg-slate-50 border border-slate-200 text-brand-dark rounded-xl text-sm font-semibold hover:border-brand-500 hover:text-brand-500 transition-colors shadow-sm cursor-default">Figma</span>
                </div>
            </div>

        </div>
    </section>

    <section id="work" class="py-24">
        <div class="max-w-7xl mx-auto px-6">
            
            <div class="flex flex-col md:flex-row justify-between items-end mb-12" data-aos="fade-up">
                <div>
                    <h2 class="text-3xl md:text-4xl font-display font-bold text-brand-dark mb-4">Featured Work</h2>
                    <p class="text-slate-500 text-lg max-w-xl">A showcase of automated workflows, data dashboards, and omnichannel scaling strategies.</p>
                </div>
            </div>

            <!-- Filters -->
            <div class="flex flex-wrap gap-3 mb-12" data-aos="fade-up">
                <button class="filter-btn active px-5 py-2 rounded-full border border-brand-500 bg-brand-500 text-white font-semibold transition-all text-sm shadow-md" onclick="filterProjects('all', this)">All</button>
                <button class="filter-btn px-5 py-2 rounded-full border border-slate-200 bg-white text-slate-500 hover:border-brand-500 hover:text-brand-500 font-semibold transition-all text-sm" onclick="filterProjects('casestudy', this)">Case Studies</button>
                <button class="filter-btn px-5 py-2 rounded-full border border-slate-200 bg-white text-slate-500 hover:border-brand-500 hover:text-brand-500 font-semibold transition-all text-sm" onclick="filterProjects('automation', this)">Automation</button>
                <button class="filter-btn px-5 py-2 rounded-full border border-slate-200 bg-white text-slate-500 hover:border-brand-500 hover:text-brand-500 font-semibold transition-all text-sm" onclick="filterProjects('seo', this)">SEO</button>
                <button class="filter-btn px-5 py-2 rounded-full border border-slate-200 bg-white text-slate-500 hover:border-brand-500 hover:text-brand-500 font-semibold transition-all text-sm" onclick="filterProjects('content', this)">Content</button>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

                <!-- JULY 2026 CASE STUDY (UPDATED TO REMOVE GAPS) -->
                <div class="project-card casestudy content seo col-span-1 md:col-span-2 lg:col-span-3 bg-white rounded-3xl p-6 md:p-10 border border-slate-200 shadow-sm card-hover mb-6" data-aos="fade-up">
                    <div class="flex flex-col lg:flex-row gap-8 lg:gap-10 items-stretch">
                        <!-- Left Content -->
                        <div class="lg:w-1/3 flex flex-col justify-between">
                            <div>
                                <div class="inline-block px-3 py-1 bg-teal-50 text-teal-900 border border-teal-200 rounded-full text-xs font-semibold uppercase tracking-wider mb-4">
                                    July 2026 Sprint
                                </div>
                                <h3 class="text-2xl md:text-3xl font-display font-bold text-brand-dark mb-3">202K+ Organic Ecosystem Growth</h3>
                                <p class="text-slate-600 leading-relaxed mb-6 text-sm">
                                    Driven strictly with <strong class="text-brand-dark">0% ad spend</strong> across LinkedIn and Instagram. Focused on capturing high-intent B2B audiences (Engineering & BizDev) while scaling content distribution.
                                </p>
                            </div>

                            <div class="space-y-3">
                                <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">Instagram Organic Views</span>
                                    <span class="text-base font-bold text-brand-dark">111.8K</span>
                                </div>
                                <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">LinkedIn Impressions</span>
                                    <span class="text-base font-bold text-brand-500">90.9K</span>
                                </div>
                                <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">LinkedIn Reactions</span>
                                    <span class="text-base font-bold text-brand-dark">1,347</span>
                                </div>
                                <div class="flex items-center justify-between pb-1">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">New Organic Followers</span>
                                    <span class="text-base font-bold text-emerald-600">+680</span>
                                </div>
                            </div>
                        </div>

                        <!-- Right Visuals (Tighter Grid) -->
                        <div class="lg:w-2/3 bg-slate-50 rounded-2xl p-5 md:p-6 border border-slate-100">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-5 h-full">
                                
                                <!-- Chart: LinkedIn Demographics -->
                                <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between h-full">
                                    <div>
                                        <div class="flex items-center justify-between mb-3">
                                            <h5 class="text-xs md:text-sm font-semibold text-slate-700">LinkedIn Visitor Demographics</h5>
                                            <span class="text-[10px] bg-blue-50 text-blue-600 font-bold px-2 py-0.5 rounded">B2B Intent</span>
                                        </div>
                                        <div class="relative h-48">
                                            <canvas id="julyDemoChart"></canvas>
                                        </div>
                                    </div>
                                    <p class="text-xs text-slate-500 mt-3 leading-relaxed border-t border-slate-100 pt-2.5">
                                        <strong class="text-brand-dark">21.5% Engineering & 9.7% BizDev</strong> composed the majority of total inbound site/profile traffic.
                                    </p>
                                </div>

                                <!-- IG & LinkedIn Cards -->
                                <div class="flex flex-col gap-4 justify-between">
                                    <!-- Instagram Stat Card -->
                                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex-1 flex flex-col justify-between">
                                        <div>
                                            <div class="flex items-center justify-between mb-2">
                                                <span class="text-xs font-semibold text-slate-500 uppercase">Instagram Reach</span>
                                                <i class="fa-brands fa-instagram text-pink-500 text-lg"></i>
                                            </div>
                                            <div class="flex items-baseline gap-2">
                                                <h4 class="text-2xl font-bold font-display text-brand-dark">111,886</h4>
                                                <span class="text-xs font-bold text-emerald-600">100% Organic</span>
                                            </div>
                                        </div>
                                        <div class="mt-3">
                                            <div class="flex justify-between text-[11px] font-medium text-slate-500 mb-1">
                                                <span>Posts (71.8%)</span>
                                                <span>Reels (17.2%)</span>
                                            </div>
                                            <div class="w-full bg-slate-100 h-2 rounded-full overflow-hidden flex">
                                                <div class="bg-pink-500 h-full" style="width: 71.8%"></div>
                                                <div class="bg-purple-500 h-full" style="width: 17.2%"></div>
                                                <div class="bg-indigo-300 h-full" style="width: 11.0%"></div>
                                            </div>
                                        </div>
                                    </div>

                                    <!-- LinkedIn Stat Card -->
                                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex-1 flex flex-col justify-between">
                                        <div>
                                            <div class="flex items-center justify-between mb-2">
                                                <span class="text-xs font-semibold text-slate-500 uppercase">LinkedIn Content</span>
                                                <i class="fa-brands fa-linkedin text-blue-600 text-lg"></i>
                                            </div>
                                            <div class="flex items-baseline gap-2">
                                                <h4 class="text-2xl font-bold font-display text-brand-dark">90,913</h4>
                                                <span class="text-xs font-bold text-emerald-600"><i class="fa-solid fa-arrow-up text-[10px]"></i> 1.7% YoY</span>
                                            </div>
                                        </div>
                                        <p class="text-xs text-slate-500 mt-2">
                                            <i class="fa-solid fa-retweet text-slate-400 mr-1"></i> 9 Reposts (<span class="text-emerald-600 font-semibold">+50% increase</span>)
                                        </p>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>

                <!-- June 2026 Case Study -->
                <div class="project-card casestudy content seo col-span-1 md:col-span-2 lg:col-span-3 bg-white rounded-3xl p-6 md:p-10 border border-slate-200 shadow-sm card-hover mb-6" data-aos="fade-up">
                    <div class="flex flex-col lg:flex-row gap-8 lg:gap-10 items-stretch">
                        <div class="lg:w-1/3 flex flex-col justify-between">
                            <div>
                                <div class="inline-block px-3 py-1 bg-brand-50 text-brand-900 border border-brand-100 rounded-full text-xs font-semibold uppercase tracking-wider mb-4">
                                    June 2026 Sprint
                                </div>
                                <h3 class="text-2xl md:text-3xl font-display font-bold text-brand-dark mb-3">Omnichannel Viral Growth</h3>
                                <p class="text-slate-600 leading-relaxed mb-6 text-sm">
                                    Scaled brand presence through an organic, zero-ad-spend strategy. By leveraging algorithm discovery and technical content structuring, we achieved massive top-of-funnel reach that actively converted into intent.
                                </p>
                            </div>
                            
                            <div class="space-y-3">
                                <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">Total IG Views</span>
                                    <span class="text-base font-bold text-brand-dark">269.9K</span>
                                </div>
                                <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">External Link Taps</span>
                                    <span class="text-base font-bold text-brand-500">+320%</span>
                                </div>
                                <div class="flex items-center justify-between pb-1">
                                    <span class="text-xs md:text-sm font-medium text-slate-500">LinkedIn Organic</span>
                                    <span class="text-base font-bold text-brand-dark">87.5K</span>
                                </div>
                            </div>
                        </div>

                        <div class="lg:w-2/3 bg-slate-50 rounded-2xl p-5 md:p-6 border border-slate-100">
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-5 h-full">
                                <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between h-full">
                                    <div>
                                        <h5 class="text-xs md:text-sm font-semibold text-slate-700 mb-3">Audience Expansion</h5>
                                        <div class="relative h-44">
                                            <canvas id="newReachChart"></canvas>
                                        </div>
                                    </div>
                                    <p class="text-xs text-slate-500 mt-3 leading-relaxed border-t border-slate-100 pt-2.5">
                                        <strong class="text-brand-dark">72% of views</strong> originated from algorithmic discovery, penetrating non-follower segments.
                                    </p>
                                </div>

                                <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-center items-center text-center h-full">
                                    <div class="w-14 h-14 bg-[#0A66C2]/10 rounded-full flex items-center justify-center mb-3">
                                        <i class="fa-brands fa-linkedin-in text-xl text-[#0A66C2]"></i>
                                    </div>
                                    <h4 class="text-2xl font-display font-bold text-brand-dark mb-1">87,511</h4>
                                    <p class="text-xs font-medium text-slate-500 uppercase tracking-wide mb-3">Organic Impressions</p>
                                    <div class="w-full bg-slate-50 rounded-lg p-3 text-xs text-slate-600 text-left border border-slate-100">
                                        <i class="fa-solid fa-lightbulb text-yellow-500 mr-1"></i> B2B engagement spiked with 1,565 active reactions and zero sponsored spend.
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- May 2026 Case Study -->
                <div class="project-card casestudy content seo col-span-1 md:col-span-2 lg:col-span-3 bg-white rounded-3xl p-6 md:p-10 border border-slate-200 shadow-sm card-hover mb-6" data-aos="fade-up">
                    <div class="flex flex-col lg:flex-row gap-8 lg:gap-10 items-stretch">
                        <div class="lg:w-1/3 flex flex-col justify-center">
                            <div class="inline-block px-3 py-1 bg-slate-100 text-slate-700 border border-slate-200 rounded-full text-xs font-semibold uppercase tracking-wider mb-4 w-max">
                                May 2026 Performance
                            </div>
                            <h3 class="text-2xl md:text-3xl font-display font-bold text-brand-dark mb-3">460K+ Ecosystem Reach</h3>
                            <p class="text-slate-600 text-sm leading-relaxed">
                                Spearheaded a 30-day multi-platform content sprint for OmSpace Rocket & Exploration. By synchronizing organic social strategies across platforms with technical SEO, we achieved exponential brand visibility, accelerated community growth, and a 54% surge in website traffic.
                            </p>
                        </div>
                        
                        <div class="lg:w-2/3 grid grid-cols-2 gap-4">
                            <div class="bg-pink-50 border border-pink-100 p-5 rounded-2xl flex flex-col justify-center">
                                <i class="fa-brands fa-instagram text-pink-500 mb-2 text-xl"></i>
                                <div class="text-2xl font-bold font-display text-brand-dark mb-1">316K+</div>
                                <div class="text-xs text-slate-500 font-medium">Total Video Views</div>
                                <div class="text-xs text-pink-600 mt-2 font-semibold"><i class="fa-solid fa-arrow-trend-up"></i> 1,691 New Followers</div>
                            </div>

                            <div class="bg-blue-50 border border-blue-100 p-5 rounded-2xl flex flex-col justify-center">
                                <i class="fa-brands fa-linkedin text-blue-600 mb-2 text-xl"></i>
                                <div class="text-2xl font-bold font-display text-brand-dark mb-1">108K+</div>
                                <div class="text-xs text-slate-500 font-medium">Post Impressions</div>
                                <div class="text-xs text-blue-600 mt-2 font-semibold"><i class="fa-solid fa-arrow-trend-up"></i> +241% Growth YoY</div>
                            </div>

                            <div class="bg-slate-50 border border-slate-200 p-5 rounded-2xl flex flex-col justify-center">
                                <i class="fa-brands fa-x-twitter text-slate-800 mb-2 text-xl"></i>
                                <div class="text-2xl font-bold font-display text-brand-dark mb-1">36K+</div>
                                <div class="text-xs text-slate-500 font-medium">Organic Impressions</div>
                                <div class="text-xs text-slate-600 mt-2 font-semibold">Consistent Viral Reach</div>
                            </div>

                            <div class="bg-brand-50 border border-brand-100 p-5 rounded-2xl flex flex-col justify-center">
                                <i class="fa-solid fa-globe text-brand-500 mb-2 text-xl"></i>
                                <div class="text-2xl font-bold font-display text-brand-dark mb-1">2.3K+</div>
                                <div class="text-xs text-slate-500 font-medium">Site Sessions</div>
                                <div class="text-xs text-brand-600 mt-2 font-semibold"><i class="fa-solid fa-arrow-trend-up"></i> 858+ AI Queries</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Regular Projects -->
                <a href="https://www.linkedin.com/posts/biswajeet-marketing_datavisualization-powerbi-businessintelligence-activity-7406980680095744000-P3KG" target="_blank" rel="noopener noreferrer" class="project-card automation block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?auto=format&fit=crop&w=800&q=80" alt="Power BI" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-brand-50 text-brand-700 rounded text-[10px] font-bold uppercase tracking-wide">Power BI</span>
                        <span class="px-2 py-1 bg-slate-100 text-slate-600 rounded text-[10px] font-bold uppercase tracking-wide">Data</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">Lead Analytics Dashboard</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Transformed raw education vertical data into interactive visuals, identifying key audience segments and geographical demand trends.</p>
                </a>

                <a href="https://www.linkedin.com/posts/biswajeet-marketing_marketingautomation-pabblyconnect-zohocrm-activity-7381000848589451264-OZ5V" target="_blank" rel="noopener noreferrer" class="project-card automation block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up" data-aos-delay="100">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=800&q=80" alt="Automation" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-purple-50 text-purple-700 rounded text-[10px] font-bold uppercase tracking-wide">Pabbly</span>
                        <span class="px-2 py-1 bg-slate-100 text-slate-600 rounded text-[10px] font-bold uppercase tracking-wide">Zoho CRM</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">Marketing Automation Flow</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Streamlined lead management and sales processes using multi-step automated workflows to eliminate manual data entry.</p>
                </a>

                <a href="https://www.linkedin.com/posts/biswajeet-marketing_digitalmarketing-googlemybusiness-localseo-activity-7314855110101123073-ywIx" target="_blank" rel="noopener noreferrer" class="project-card seo block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up" data-aos-delay="200">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1569025690938-a00729c9e1f9?auto=format&fit=crop&w=800&q=80" alt="SEO" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-amber-50 text-amber-700 rounded text-[10px] font-bold uppercase tracking-wide">Local SEO</span>
                        <span class="px-2 py-1 bg-slate-100 text-slate-600 rounded text-[10px] font-bold uppercase tracking-wide">GMB</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">Google My Business SEO</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Optimized GMB profiles and implemented local search strategies to dramatically improve client visibility and foot traffic.</p>
                </a>

                <a href="https://www.linkedin.com/company/zeepty/posts/?feedView=all" target="_blank" rel="noopener noreferrer" class="project-card content block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1611162617213-7d7a39e9b1d7?auto=format&fit=crop&w=800&q=80" alt="Social Media" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-blue-50 text-blue-700 rounded text-[10px] font-bold uppercase tracking-wide">Social Media</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">Zeepty Social Growth</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Achieved 40% increase in brand mentions and generated 100+ qualified leads through targeted organic campaigns.</p>
                </a>

                <a href="https://peerfives.com/gratitude-journal/" target="_blank" rel="noopener noreferrer" class="project-card content block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up" data-aos-delay="100">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1455390582262-044cdead277a?auto=format&fit=crop&w=800&q=80" alt="Content" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-indigo-50 text-indigo-700 rounded text-[10px] font-bold uppercase tracking-wide">Blogging</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">Peerfives Content Strategy</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Developed and executed a blog strategy focused on user engagement, leading to a 25% increase in site retention.</p>
                </a>

                <a href="https://biswajeet-stack.github.io/Pehchan-/" target="_blank" rel="noopener noreferrer" class="project-card seo content block bg-white rounded-2xl p-6 border border-slate-200 card-hover group" data-aos="fade-up" data-aos-delay="200">
                    <div class="h-48 w-full bg-slate-100 rounded-xl mb-6 overflow-hidden relative border border-slate-100">
                        <img src="https://images.unsplash.com/photo-1499951360447-b19be8fe80f5?auto=format&fit=crop&w=800&q=80" alt="Branding" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                    </div>
                    <div class="flex gap-2 mb-3">
                        <span class="px-2 py-1 bg-rose-50 text-rose-700 rounded text-[10px] font-bold uppercase tracking-wide">Branding</span>
                        <span class="px-2 py-1 bg-slate-100 text-slate-600 rounded text-[10px] font-bold uppercase tracking-wide">Web</span>
                    </div>
                    <h3 class="text-lg font-bold font-display text-brand-dark mb-2">PehchanPlus Brand</h3>
                    <p class="text-slate-500 text-sm leading-relaxed">Created a personal digital marketing agency brand providing comprehensive SEO and SEM solutions for small businesses.</p>
                </a>

            </div>
        </div>
    </section>

    <section id="experience" class="py-24 bg-slate-50 border-t border-slate-200">
        <div class="max-w-4xl mx-auto px-6">
            <div class="mb-16 text-center md:text-left" data-aos="fade-up">
                <h2 class="text-3xl md:text-4xl font-display font-bold text-brand-dark mb-4">Work Experience</h2>
                <p class="text-slate-500 text-lg">My trajectory in digital strategy and execution.</p>
            </div>

            <div class="relative timeline-line space-y-12">
                <div class="relative pl-14" data-aos="fade-up">
                    <div class="absolute left-0 top-1 w-12 h-12 bg-white border border-slate-200 shadow-sm rounded-full flex items-center justify-center z-10 text-brand-500">
                        <i class="fa-solid fa-rocket"></i>
                    </div>
                    <div class="group bg-white p-6 rounded-2xl border border-slate-200 shadow-sm card-hover">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-2">
                            <h3 class="text-xl font-bold font-display text-brand-dark group-hover:text-brand-500 transition-colors">Digital Marketing Specialist</h3>
                            <span class="text-xs text-brand-500 font-semibold bg-brand-50 px-3 py-1 rounded-full mt-2 sm:mt-0">Sep 2025 - Present</span>
                        </div>
                        <p class="text-slate-700 font-medium mb-4">Om Space Rocket and Exploration</p>
                        <ul class="space-y-2 text-slate-500 text-sm leading-relaxed">
                            <li>• Designed and deployed 20+ automated workflows using Pabbly and AiSensy (80% deployment rate).</li>
                            <li>• Implemented Razorpay Webhook & Zoho CRM flow for real-time lead generation.</li>
                            <li>• Developed Power BI dashboards for segmented reporting (state-wise, age-based).</li>
                        </ul>
                    </div>
                </div>

                <div class="relative pl-14" data-aos="fade-up">
                    <div class="absolute left-0 top-1 w-12 h-12 bg-white border border-slate-200 shadow-sm rounded-full flex items-center justify-center z-10 text-purple-500">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <div class="group bg-white p-6 rounded-2xl border border-slate-200 shadow-sm card-hover">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-2">
                            <h3 class="text-xl font-bold font-display text-brand-dark group-hover:text-purple-600 transition-colors">Digital Marketing Intern</h3>
                            <span class="text-xs text-slate-500 font-semibold bg-slate-100 px-3 py-1 rounded-full mt-2 sm:mt-0">Jun 2025 - Sep 2025</span>
                        </div>
                        <p class="text-slate-700 font-medium mb-4">SOLVATIVE</p>
                        <ul class="space-y-2 text-slate-500 text-sm leading-relaxed">
                            <li>• Managed content for LinkedIn, Instagram & Bluesky; updated websites using Storyblok CMS.</li>
                            <li>• Created automated cold emailing workflows using n8n for lead generation.</li>
                        </ul>
                    </div>
                </div>

                <div class="relative pl-14" data-aos="fade-up">
                    <div class="absolute left-0 top-1 w-12 h-12 bg-white border border-slate-200 shadow-sm rounded-full flex items-center justify-center z-10 text-blue-500">
                        <i class="fa-solid fa-hashtag"></i>
                    </div>
                    <div class="group bg-white p-6 rounded-2xl border border-slate-200 shadow-sm card-hover">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-2">
                            <h3 class="text-xl font-bold font-display text-brand-dark group-hover:text-blue-600 transition-colors">Digital Marketing Intern</h3>
                            <span class="text-xs text-slate-500 font-semibold bg-slate-100 px-3 py-1 rounded-full mt-2 sm:mt-0">Mar 2025 - Jun 2025</span>
                        </div>
                        <p class="text-slate-700 font-medium mb-4">Zeepty</p>
                        <ul class="space-y-2 text-slate-500 text-sm leading-relaxed">
                            <li>• Boosted social interactions by 30% and organic traffic by 12%.</li>
                            <li>• Generated 15+ qualified leads/month; authored high-engagement blogs for Gen Z.</li>
                        </ul>
                    </div>
                </div>

                <div class="relative pl-14" data-aos="fade-up">
                    <div class="absolute left-0 top-1 w-12 h-12 bg-white border border-slate-200 shadow-sm rounded-full flex items-center justify-center z-10 text-slate-500">
                        <i class="fa-solid fa-clock-rotate-left"></i>
                    </div>
                    <div class="group bg-white p-6 rounded-2xl border border-slate-200 shadow-sm card-hover">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between mb-2">
                            <h3 class="text-xl font-bold font-display text-brand-dark">Early Roles</h3>
                            <span class="text-xs text-slate-500 font-semibold bg-slate-100 px-3 py-1 rounded-full mt-2 sm:mt-0">2023 - 2025</span>
                        </div>
                        <p class="text-slate-700 font-medium mb-4">Olcademy, Stellar8Labs & VR Academy</p>
                        <ul class="space-y-2 text-slate-500 text-sm leading-relaxed">
                            <li>• <strong class="text-gray-300">Olcademy:</strong> SEO optimization (Score 70+); developed Gen Z blog strategies.</li>
                            <li>• <strong class="text-gray-300">Stellar8Labs:</strong> Fixed 15+ technical SEO issues; grew LinkedIn followers by 15%.</li>
                            <li>• <strong class="text-gray-300">VR Academy:</strong> High School Teacher achieving 100% pass rate.</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="education" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-display font-bold text-brand-dark mb-12 text-center md:text-left" data-aos="fade-up">Education</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white p-8 rounded-2xl border border-slate-200 shadow-sm card-hover" data-aos="fade-up">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold font-display text-brand-dark">MBA in International Business</h3>
                        <span class="px-3 py-1 bg-brand-50 text-brand-700 rounded-md text-xs font-semibold shrink-0">2024 - Present</span>
                    </div>
                    <p class="text-slate-600 font-medium">Lovely Professional University</p>
                    <p class="text-slate-500 text-sm mt-2 flex items-center gap-2">
                        <i class="fa-solid fa-building-columns text-slate-400"></i> Mittal School of Business (2026 Batch)
                    </p>
                </div>
                
                <div class="bg-white p-8 rounded-2xl border border-slate-200 shadow-sm card-hover" data-aos="fade-up" data-aos-delay="100">
                    <div class="flex justify-between items-start mb-4">
                        <h3 class="text-xl font-bold font-display text-brand-dark">B.Sc. Zoology Honors</h3>
                        <span class="px-3 py-1 bg-slate-100 text-slate-600 rounded-md text-xs font-semibold shrink-0">2020 - 2023</span>
                    </div>
                    <p class="text-slate-600 font-medium">Jupiter Degree College</p>
                    <div class="text-slate-500 text-sm mt-2 flex justify-between items-center">
                        <span class="flex items-center gap-2"><i class="fa-solid fa-location-dot text-slate-400"></i> Bhubaneswar</span>
                        <span class="font-bold text-brand-600 bg-brand-50 border border-brand-100 px-2 py-1 rounded">CGPA: 8.99</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="certifications" class="py-24 bg-slate-50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-6">
            <h2 class="text-3xl md:text-4xl font-display font-bold text-brand-dark mb-12 text-center md:text-left" data-aos="fade-up">Licenses & Certifications</h2>
            
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up">
                    <div class="w-12 h-12 rounded-full bg-brand-50 flex items-center justify-center text-brand-500 shrink-0">
                        <i class="fa-solid fa-chart-line text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">Google Analytics 4 (2025)</h4>
                        <p class="text-xs text-slate-500 mt-1">Udemy</p>
                    </div>
                </div>
                
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up" data-aos-delay="50">
                    <div class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 shrink-0">
                        <i class="fa-brands fa-google text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">Digital Marketing & E-com</h4>
                        <p class="text-xs text-slate-500 mt-1">Coursera</p>
                    </div>
                </div>
                
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 shrink-0">
                        <i class="fa-brands fa-google text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">Data Analytics</h4>
                        <p class="text-xs text-slate-500 mt-1">Coursera</p>
                    </div>
                </div>
                
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up">
                    <div class="w-12 h-12 rounded-full bg-blue-50 flex items-center justify-center text-blue-600 shrink-0">
                        <i class="fa-brands fa-google text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">Google AI Essentials</h4>
                        <p class="text-xs text-slate-500 mt-1">Coursera</p>
                    </div>
                </div>
                
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up" data-aos-delay="50">
                    <div class="w-12 h-12 rounded-full bg-orange-50 flex items-center justify-center text-orange-500 shrink-0">
                        <i class="fa-solid fa-bullhorn text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">PPC Fundamentals</h4>
                        <p class="text-xs text-slate-500 mt-1">Semrush</p>
                    </div>
                </div>
                
                <div class="p-5 border border-slate-200 rounded-xl bg-white flex items-center gap-4 card-hover shadow-sm" data-aos="fade-up" data-aos-delay="100">
                    <div class="w-12 h-12 rounded-full bg-orange-50 flex items-center justify-center text-orange-500 shrink-0">
                        <i class="fa-solid fa-globe text-lg"></i>
                    </div>
                    <div>
                        <h4 class="text-sm font-bold font-display text-brand-dark leading-tight">International SEO</h4>
                        <p class="text-xs text-slate-500 mt-1">Semrush</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-16 bg-brand-dark text-slate-400 text-center border-t-4 border-brand-500 relative overflow-hidden">
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-[40%] h-[100px] bg-brand-500 filter blur-[100px] opacity-20 pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-6 flex flex-col items-center relative z-10">
            <h2 class="text-3xl font-display font-bold text-white mb-6">Let's build something exceptional.</h2>
            <p class="mb-10 text-slate-400 max-w-lg text-sm">Looking to scale your brand's digital presence? Let's talk about automation, data, and growth.</p>
            <div class="flex gap-4 mb-12">
                <a href="mailto:biswajeetkumarp@gmail.com" class="bg-brand-500 text-white px-8 py-3.5 rounded-lg font-medium hover:bg-teal-400 transition-colors shadow-lg shadow-brand-500/20 flex items-center gap-2">
                    <i class="fa-solid fa-envelope"></i> Email Me
                </a>
                <a href="https://www.linkedin.com/in/biswajeet-marketing" target="_blank" rel="noopener noreferrer" class="bg-slate-800 text-white px-8 py-3.5 rounded-lg font-medium hover:bg-slate-700 transition-colors flex items-center gap-2">
                    <i class="fa-brands fa-linkedin-in"></i> LinkedIn
                </a>
            </div>
            <div class="w-full max-w-sm h-px bg-slate-800 mb-8"></div>
            <p class="text-sm">&copy; 2026 Biswajeet Parida. Designed with intent.</p>
        </div>
    </footer>

    <!-- Scripts -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        window.addEventListener('scroll', () => {
            const scrolled = window.scrollY;
            document.documentElement.style.setProperty('--scroll', scrolled);
        });

        AOS.init({
            once: true,
            offset: 20,
            duration: 800,
            easing: 'ease-out-expo',
        });

        function filterProjects(category, btn) {
            document.querySelectorAll('.filter-btn').forEach(b => {
                b.classList.remove('active', 'bg-brand-500', 'text-white', 'border-brand-500', 'shadow-md');
                b.classList.add('text-slate-500', 'border-slate-200', 'bg-white');
            });
            btn.classList.add('active', 'bg-brand-500', 'text-white', 'border-brand-500', 'shadow-md');
            btn.classList.remove('text-slate-500', 'border-slate-200', 'bg-white');

            const items = document.querySelectorAll('.project-card');
            
            items.forEach(item => {
                item.style.opacity = '0';
                item.style.transform = 'scale(0.95)';
                
                setTimeout(() => {
                    if (category === 'all' || item.classList.contains(category)) {
                        item.style.display = 'block';
                        void item.offsetWidth; 
                        item.style.opacity = '1';
                        item.style.transform = 'scale(1)';
                    } else {
                        item.style.display = 'none';
                    }
                }, 300);
            });
        }

        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        document.addEventListener("DOMContentLoaded", function() {
            Chart.defaults.font.family = "'Inter', sans-serif";
            Chart.defaults.color = '#64748b';

            const ctxJulyDemo = document.getElementById('julyDemoChart');
            if (ctxJulyDemo) {
                new Chart(ctxJulyDemo, {
                    type: 'bar',
                    data: {
                        labels: ['Engineering', 'Biz Dev', 'Operations', 'Research', 'Sales'],
                        datasets: [{
                            label: 'Visitor Percentage %',
                            data: [21.5, 9.7, 8.4, 4.6, 4.4],
                            backgroundColor: '#0A66C2',
                            borderRadius: 4,
                            barThickness: 10
                        }]
                    },
                    options: {
                        indexAxis: 'y',
                        responsive: true,
                        maintainAspectRatio: false,
                        plugins: {
                            legend: { display: false },
                            tooltip: {
                                callbacks: {
                                    label: function(ctx) { return ctx.raw + '% of Total Traffic'; }
                                }
                            }
                        },
                        scales: {
                            x: {
                                grid: { display: false },
                                border: { display: false },
                                ticks: { callback: function(val) { return val + '%'; }, font: { size: 10 } }
                            },
                            y: {
                                grid: { display: false },
                                border: { display: false },
                                ticks: { font: { size: 10 } }
                            }
                        }
                    }
                });
            }

            const ctxReach = document.getElementById('newReachChart');
            if (ctxReach) {
                new Chart(ctxReach, {
                    type: 'bar',
                    data: {
                        labels: ['Views (269.9K)'],
                        datasets: [
                            {
                                label: 'Non-Followers (Discovery)',
                                data: [72],
                                backgroundColor: '#14b8a6',
                                borderRadius: 4,
                                barPercentage: 0.6,
                                categoryPercentage: 0.6
                            },
                            {
                                label: 'Existing Followers',
                                data: [28],
                                backgroundColor: '#e2e8f0',
                                borderRadius: 4,
                                barPercentage: 0.6,
                                categoryPercentage: 0.6
                            }
                        ]
                    },
                    options: {
                        indexAxis: 'y',
                        responsive: true,
                        maintainAspectRatio: false,
                        scales: {
                            x: { 
                                stacked: true, 
                                max: 100, 
                                grid: { display: false },
                                border: { display: false },
                                ticks: { callback: function(value) { return value + "%" } }
                            },
                            y: { stacked: true, grid: { display: false }, border: { display: false }, display: false }
                        },
                        plugins: {
                            legend: { position: 'bottom', labels: { usePointStyle: true, boxWidth: 8 } },
                            tooltip: {
                                callbacks: {
                                    label: function(context) { return context.dataset.label + ': ' + context.parsed.x + '%'; }
                                }
                            }
                        }
                    }
                });
            }
        });
    </script>
</body>
</html>
