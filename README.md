<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nikhil Sharma | Data Analyst Portfolio</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-slate-50 text-slate-800 font-sans">

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur shadow-sm">
        <div class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-xl font-bold text-indigo-600">Nikhil Sharma</a>
            <nav class="space-x-6 hidden md:flex">
                <a href="#about" class="hover:text-indigo-600 transition">About</a>
                <a href="#skills" class="hover:text-indigo-600 transition">Skills</a>
                <a href="#experience" class="hover:text-indigo-600 transition">Experience</a>
                <a href="#projects" class="hover:text-indigo-600 transition">Projects</a>
                <a href="#contact" class="hover:text-indigo-600 transition">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="about" class="max-w-5xl mx-auto px-6 py-20 flex flex-col md:flex-row items-center gap-12">
        <div class="flex-1 space-y-6">
            <span class="bg-indigo-50 text-indigo-700 px-3 py-1 rounded-full text-sm font-semibold tracking-wide">Data Analyst</span>
            <h1 class="text-4xl md:text-5xl font-extrabold tracking-tight text-slate-900">
                Hi, I'm Nikhil. I turn raw data into <span class="text-indigo-600">actionable insights</span>.
            </h1>
            <p class="text-lg text-slate-600 leading-relaxed">
                Specializing in data pipelines, statistical modeling, and interactive dashboards. I bridge the gap between complex datasets and strategic decision-making.
            </p>
            <div class="flex gap-4">
                <a href="#projects" class="bg-indigo-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-indigo-700 transition shadow-md shadow-indigo-200">View My Work</a>
                <a href="https://github.com/NikhilSharmat" target="_blank" class="border border-slate-300 px-6 py-3 rounded-lg font-medium hover:bg-slate-100 transition flex items-center gap-2">
                    <i class="fab fa-github"></i> GitHub Profile
                </a>
            </div>
        </div>
        <div class="w-64 h-64 md:w-80 md:h-80 bg-gradient-to-tr from-indigo-500 to-purple-500 rounded-full flex items-center justify-center text-white text-6xl shadow-xl shadow-indigo-100">
            <i class="fas fa-chart-pie animate-pulse"></i>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="bg-white border-y border-slate-100 py-16">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-3xl font-bold text-slate-900 mb-8 text-center">Technical Toolbox</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
                <!-- Skill Category 1 -->
                <div class="p-6 bg-slate-50 rounded-xl border border-slate-100 space-y-3">
                    <i class="fab fa-python text-3xl text-indigo-600"></i>
                    <h3 class="font-bold text-slate-900">Languages</h3>
                    <p class="text-sm text-slate-500">Python (Pandas, NumPy), SQL (PostgreSQL, MySQL), R</p>
                </div>
                <!-- Skill Category 2 -->
                <div class="p-6 bg-slate-50 rounded-xl border border-slate-100 space-y-3">
                    <i class="fas fa-chart-bar text-3xl text-indigo-600"></i>
                    <h3 class="font-bold text-slate-900">Visualization</h3>
                    <p class="text-sm text-slate-500">Power BI, Tableau, Matplotlib, Seaborn</p>
                </div>
                <!-- Skill Category 3 -->
                <div class="p-6 bg-slate-50 rounded-xl border border-slate-100 space-y-3">
                    <i class="fas fa-database text-3xl text-indigo-600"></i>
                    <h3 class="font-bold text-slate-900">Data Engineering</h3>
                    <p class="text-sm text-slate-500">ETL Pipelines, Data Wrangling, Excel (Advanced)</p>
                </div>
                <!-- Skill Category 4 -->
                <div class="p-6 bg-slate-50 rounded-xl border border-slate-100 space-y-3">
                    <i class="fas fa-brain text-3xl text-indigo-600"></i>
                    <h3 class="font-bold text-slate-900">Analytics</h3>
                    <p class="text-sm text-slate-500">A/B Testing, Statistical Analysis, Predictive Modeling</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience Timeline -->
    <section id="experience" class="max-w-5xl mx-auto px-6 py-20">
        <h2 class="text-3xl font-bold text-slate-900 mb-12 text-center">Work Experience</h2>
        <div class="relative border-l border-slate-200 ml-4 md:ml-32 space-y-12">
            
            <!-- Job 1 -->
            <div class="relative pl-8">
                <!-- Timeline dot -->
                <div class="absolute -left-2.5 top-1.5 w-5 h-5 rounded-full bg-indigo-600 border-4 border-white"></div>
                <div class="flex flex-col md:flex-row md:items-baseline justify-between mb-2">
                    <div>
                        <h3 class="text-xl font-bold text-slate-900">Senior Data Analyst</h3>
                        <p class="text-indigo-600 font-medium">TechSolutions Corp</p>
                    </div>
                    <span class="text-sm bg-slate-100 px-3 py-1 rounded text-slate-600 mt-1 md:mt-0 font-medium">2024 - Present</span>
                </div>
                <ul class="list-disc list-inside text-slate-600 space-y-2 mt-3">
                    <li>Led a cross-functional team to optimize inventory management, cutting overhead costs by 14%.</li>
                    <li>Designed and deployed automated executive dashboards in Power BI, reducing manual reporting hours by 40%.</li>
                    <li>Built SQL queries and statistical models to identify customer churn markers, boosting retention rates.</li>
                </ul>
            </div>

            <!-- Job 2 -->
            <div class="relative pl-8">
                <!-- Timeline dot -->
                <div class="absolute -left-2.5 top-1.5 w-5 h-5 rounded-full bg-slate-300 border-4 border-white"></div>
                <div class="flex flex-col md:flex-row md:items-baseline justify-between mb-2">
                    <div>
                        <h3 class="text-xl font-bold text-slate-900">Data Analyst</h3>
                        <p class="text-indigo-600 font-medium">Insight Global Finance</p>
                    </div>
                    <span class="text-sm bg-slate-100 px-3 py-1 rounded text-slate-600 mt-1 md:mt-0 font-medium">2022 - 2024</span>
                </div>
                <ul class="list-disc list-inside text-slate-600 space-y-2 mt-3">
                    <li>Cleaned and parsed complex transaction data sets of over 2M records using Python (Pandas).</li>
                    <li>Conducted rigorous A/B testing on pricing models, resulting in a 5% increase in conversion velocities.</li>
                    <li>Collaborated on building daily data pipelines to pull directly from Salesforce and internal PostgreSQL tables.</li>
                </ul>
            </div>

        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-slate-100 border-t border-slate-200/60 py-20">
        <div class="max-w-5xl mx-auto px-6">
            <h2 class="text-3xl font-bold text-slate-900 mb-4 text-center">Featured Projects</h2>
            <p class="text-slate-600 text-center max-w-xl mx-auto mb-12">
                A selection of data systems, predictive dashboards, and statistical deep-dives built to solve real business challenges.
            </p>
            
            <div class="grid md:grid-cols-2 gap-8">
                <!-- Project 1 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-200/60 overflow-hidden flex flex-col">
                    <div class="p-6 flex-1 space-y-4">
                        <div class="flex justify-between items-start">
                            <h3 class="text-xl font-bold text-slate-900">E-Commerce Customer Segmentation</h3>
                            <a href="#" class="text-slate-400 hover:text-slate-600"><i class="fab fa-github text-xl"></i></a>
                        </div>
                        <p class="text-sm text-slate-600">
                            Applied RFM (Recency, Frequency, Monetary) modeling and K-Means clustering to categorize 50k customer records into actionable marketing personas.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">Python</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">Scikit-Learn</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">Tableau</span>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-white rounded-xl shadow-sm border border-slate-200/60 overflow-hidden flex flex-col">
                    <div class="p-6 flex-1 space-y-4">
                        <div class="flex justify-between items-start">
                            <h3 class="text-xl font-bold text-slate-900">Supply Chain Performance Pipeline</h3>
                            <a href="#" class="text-slate-400 hover:text-slate-600"><i class="fab fa-github text-xl"></i></a>
                        </div>
                        <p class="text-sm text-slate-600">
                            Engineered an interactive SQL/Power BI pipeline updating fulfillment latency tracking daily, streamlining delay patterns across regional distribution channels.
                        </p>
                        <div class="flex flex-wrap gap-2 pt-2">
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">PostgreSQL</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">Power BI</span>
                            <span class="bg-slate-100 text-slate-600 text-xs px-2.5 py-1 rounded font-medium">ETL</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="max-w-5xl mx-auto px-6 py-20 text-center space-y-8">
        <h2 class="text-3xl font-bold text-slate-900">Let's Connect</h2>
        <p class="text-slate-600 max-w-md mx-auto">
            I'm currently looking for new opportunities or technical collaborations. Drop me a line if you want to chat about data infrastructure!
        </p>
        <div class="flex justify-center gap-6 text-2xl">
            <a href="mailto:your.email@example.com" class="text-slate-500 hover:text-indigo-600 transition"><i class="fas fa-envelope"></i></a>
            <a href="https://github.com/NikhilSharmat" target="_blank" class="text-slate-500 hover:text-indigo-600 transition"><i class="fab fa-github"></i></a>
            <a href="#" class="text-slate-500 hover:text-indigo-600 transition"><i class="fab fa-linkedin"></i></a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 text-sm py-8 text-center border-t border-slate-800">
        <p>&copy; 2026 Nikhil Sharma. All rights reserved.</p>
    </footer>

</body>
</html>
