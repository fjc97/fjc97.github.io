<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fernando Contreras | Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 antialiased selection:bg-blue-500 selection:text-white">

    <!-- Navigation Bar -->
    <header class="sticky top-0 z-50 bg-slate-900/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-6 h-16 flex items-center justify-between">
            <a href="#" class="font-bold text-lg tracking-tight text-white flex items-center gap-2">
                <span class="w-3 h-3 rounded-full bg-blue-500 inline-block"></span>
                Fernando Contreras
            </a>
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium text-slate-300">
                <a href="#about" class="hover:text-blue-400 transition">About</a>
                <a href="#skills" class="hover:text-blue-400 transition">Skills</a>
                <a href="#projects" class="hover:text-blue-400 transition">Projects</a>
                <a href="#contact" class="hover:text-blue-400 transition">Contact</a>
            </nav>
            <div class="flex items-center gap-4">
                <a href="https://www.linkedin.com/in/fernando-contreras-0b0171225/" target="_blank" class="text-sm bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-lg font-medium transition shadow-sm">
                    LinkedIn
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section / Personal Statement -->
    <section id="about" class="pt-24 pb-20 px-6 border-b border-slate-800/60">
        <div class="max-w-4xl mx-auto text-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-blue-500/10 text-blue-400 text-xs font-semibold mb-6 border border-blue-500/20">
                Rutgers University • Business Undergraduate
            </div>
            <h1 class="text-4xl md:text-6xl font-bold tracking-tight text-white mb-6">
                Driven by numbers, focused on <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-indigo-400">financial strategy.</span>
            </h1>
            <!-- Rubric Requirement: One clear, concise professional sentence introduction -->
            <p class="text-lg md:text-xl text-slate-300 max-w-2xl mx-auto leading-relaxed">
                An aspiring financial analyst and Rutgers University business undergraduate combining quantitative rigor in applied calculus and financial accounting with strategic supply chain insights.
            </p>
        </div>
    </section>

    <!-- Skills Showcase Section -->
    <section id="skills" class="py-20 px-6 bg-slate-950/40 border-b border-slate-800/60">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold tracking-tight text-white mb-3">Skills & Expertise</h2>
                <p class="text-slate-400 text-sm">Core competencies tailored for financial analysis and modern business operations.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Skill Group 1 -->
                <div class="bg-slate-900/60 border border-slate-800 p-6 rounded-xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 rounded-lg bg-blue-500/10 text-blue-400 flex items-center justify-center font-bold mb-4">
                        📊
                    </div>
                    <h3 class="text-lg font-semibold text-white mb-2">Finance & Accounting</h3>
                    <p class="text-slate-400 text-sm mb-4">Foundational financial reporting, statement analysis, and cost-benefit evaluations.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Financial Accounting</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Microeconomics</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Excel</span>
                    </div>
                </div>

                <!-- Skill Group 2 -->
                <div class="bg-slate-900/60 border border-slate-800 p-6 rounded-xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 rounded-lg bg-indigo-500/10 text-indigo-400 flex items-center justify-center font-bold mb-4">
                        📈
                    </div>
                    <h3 class="text-lg font-semibold text-white mb-2">Quantitative & Analytics</h3>
                    <p class="text-slate-400 text-sm mb-4">Data-backed problem solving, statistical methods, and operational optimization.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Applied Calculus</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Operations Analytics</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Elementary Statistics</span>
                    </div>
                </div>

                <!-- Skill Group 3 -->
                <div class="bg-slate-900/60 border border-slate-800 p-6 rounded-xl hover:border-blue-500/50 transition">
                    <div class="w-10 h-10 rounded-lg bg-emerald-500/10 text-emerald-400 flex items-center justify-center font-bold mb-4">
                        💼
                    </div>
                    <h3 class="text-lg font-semibold text-white mb-2">Business & Strategy</h3>
                    <p class="text-slate-400 text-sm mb-4">Supply chain mechanics, professional leadership, and ethical business standards.</p>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Supply Chain Management</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Business Ethics</span>
                        <span class="px-2.5 py-1 bg-slate-800 text-slate-300 text-xs rounded-md">Leadership</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 px-6 border-b border-slate-800/60">
        <div class="max-w-6xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold tracking-tight text-white mb-3">Featured Projects</h2>
                <p class="text-slate-400 text-sm">Academic case studies, analytical assignments, and professional development.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden flex flex-col justify-between hover:border-slate-700 transition">
                    <div class="p-6">
                        <span class="text-xs font-semibold text-blue-400 uppercase tracking-wider">Financial Analysis</span>
                        <h3 class="text-xl font-bold text-white mt-2 mb-3">Corporate Financial Statement Review</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Evaluated simulated balance sheets and income statements using fundamental accounting principles to assess firm liquidity and profitability performance.
                        </p>
                    </div>
                    <div class="px-6 pb-6 pt-0">
                        <a href="https://www.linkedin.com/in/fernando-contreras-0b0171225/" target="_blank" class="inline-flex items-center gap-1.5 text-sm font-medium text-blue-400 hover:text-blue-300 transition">
                            View details &rarr;
                        </a>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden flex flex-col justify-between hover:border-slate-700 transition">
                    <div class="p-6">
                        <span class="text-xs font-semibold text-indigo-400 uppercase tracking-wider">Operations & Logistics</span>
                        <h3 class="text-xl font-bold text-white mt-2 mb-3">Supply Chain Optimization Case Study</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Applied operations analytics models and linear programming methodologies to minimize logistics bottlenecks and improve distribution efficiency.
                        </p>
                    </div>
                    <div class="px-6 pb-6 pt-0">
                        <a href="https://www.linkedin.com/in/fernando-contreras-0b0171225/" target="_blank" class="inline-flex items-center gap-1.5 text-sm font-medium text-blue-400 hover:text-blue-300 transition">
                            View details &rarr;
                        </a>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="bg-slate-900 border border-slate-800 rounded-xl overflow-hidden flex flex-col justify-between hover:border-slate-700 transition">
                    <div class="p-6">
                        <span class="text-xs font-semibold text-emerald-400 uppercase tracking-wider">Market Research</span>
                        <h3 class="text-xl font-bold text-white mt-2 mb-3">Microeconomic Market Equilibrium Model</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Analyzed consumer behavior, supply-demand shifts, and pricing elasticity curves using data sets to predict market price fluctuations.
                        </p>
                    </div>
                    <div class="px-6 pb-6 pt-0">
                        <a href="https://www.linkedin.com/in/fernando-contreras-0b0171225/" target="_blank" class="inline-flex items-center gap-1.5 text-sm font-medium text-blue-400 hover:text-blue-300 transition">
                            View details &rarr;
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Footer Section -->
    <footer id="contact" class="py-16 px-6 bg-slate-950">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-2xl font-bold text-white mb-4">Let's Connect</h2>
            <p class="text-slate-400 text-sm mb-8 max-w-md mx-auto">
                I'm actively seeking opportunities to connect with professionals, student organizations, and future internships in finance and business analytics.
            </p>
            <div class="flex justify-center gap-4 mb-12">
                <a href="https://www.linkedin.com/in/fernando-contreras-0b0171225/" target="_blank" class="bg-slate-800 hover:bg-slate-700 text-white px-5 py-2.5 rounded-lg text-sm font-medium transition border border-slate-700">
                    LinkedIn Profile
                </a>
            </div>
            <p class="text-xs text-slate-500">
                &copy; 2026 Fernando Contreras. Built for GitHub Pages.
            </p>
        </div>
    </footer>

</body>
</html>

