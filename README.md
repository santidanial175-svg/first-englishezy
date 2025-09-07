# first-englishezy
English is easy
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EnglishEzy - Learn English the Easy Way!</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3B82F6',
                        secondary: '#10B981',
                        accent: '#F59E0B'
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
        .animate-float { animation: float 3s ease-in-out infinite; }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        .animate-slide-up {
            animation: slideUp 0.8s ease-out forwards;
            opacity: 0;
            transform: translateY(30px);
        }
        @keyframes slideUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        .animate-fade-in {
            animation: fadeIn 1s ease-out forwards;
            opacity: 0;
        }
        @keyframes fadeIn {
            to { opacity: 1; }
        }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1); }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <div class="relative w-12 h-12 mr-3">
                            <div class="absolute inset-0 bg-gradient-to-br from-blue-500 to-purple-600 rounded-xl transform rotate-3 shadow-lg"></div>
                            <div class="relative bg-gradient-to-br from-blue-400 to-purple-500 rounded-xl w-full h-full flex items-center justify-center shadow-lg">
                                <svg class="w-7 h-7 text-white" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M12 2L13.09 8.26L20 9L13.09 9.74L12 16L10.91 9.74L4 9L10.91 8.26L12 2Z"/>
                                    <path d="M19 15L19.5 17L21.5 17.5L19.5 18L19 20L18.5 18L16.5 17.5L18.5 17L19 15Z"/>
                                    <path d="M5 6L5.5 7.5L7 8L5.5 8.5L5 10L4.5 8.5L3 8L4.5 7.5L5 6Z"/>
                                </svg>
                            </div>
                        </div>
                        <div class="flex flex-col">
                            <span class="text-2xl font-bold bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent">EnglishEzy</span>
                            <span class="text-xs text-gray-500 -mt-1">Learn • Grow • Succeed</span>
                        </div>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#home" class="nav-link text-primary font-medium px-3 py-2 rounded-md">Home</a>
                        <a href="#materials" class="nav-link text-gray-600 hover:text-primary px-3 py-2 rounded-md">Learning Materials</a>
                        <a href="#resources" class="nav-link text-gray-600 hover:text-primary px-3 py-2 rounded-md">Resources</a>
                        <a href="#worksheets" class="nav-link text-gray-600 hover:text-primary px-3 py-2 rounded-md">Worksheets</a>
                        <a href="#mpi" class="nav-link text-gray-600 hover:text-primary px-3 py-2 rounded-md">MPI</a>
                        <a href="#assessment" class="nav-link text-gray-600 hover:text-primary px-3 py-2 rounded-md">Assessment</a>
                    </div>
                </div>
                <div class="flex items-center space-x-4">
                    <button class="bg-primary text-white px-4 py-2 rounded-lg hover:bg-blue-600 transition">Login</button>
                    <button class="md:hidden" onclick="toggleMobileMenu()">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#home" class="block px-3 py-2 text-primary font-medium">Home</a>
                <a href="#materials" class="block px-3 py-2 text-gray-600">Learning Materials</a>
                <a href="#resources" class="block px-3 py-2 text-gray-600">Resources</a>
                <a href="#worksheets" class="block px-3 py-2 text-gray-600">Worksheets</a>
                <a href="#mpi" class="block px-3 py-2 text-gray-600">MPI</a>
                <a href="#assessment" class="block px-3 py-2 text-gray-600">Assessment</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative overflow-hidden bg-gradient-to-br from-blue-600 via-purple-600 to-indigo-700 text-white py-20 min-h-screen flex items-center">
        <!-- Animated Background Elements -->
        <div class="absolute inset-0 overflow-hidden">
            <div class="absolute -top-40 -right-40 w-80 h-80 bg-white opacity-10 rounded-full animate-pulse"></div>
            <div class="absolute top-20 -left-20 w-60 h-60 bg-yellow-300 opacity-20 rounded-full animate-bounce" style="animation-delay: 1s;"></div>
            <div class="absolute bottom-20 right-20 w-40 h-40 bg-pink-300 opacity-15 rounded-full animate-ping" style="animation-delay: 2s;"></div>
        </div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div class="text-center md:text-left">
                    <div class="mb-6">
                        <span class="inline-block bg-white bg-opacity-20 text-white px-4 py-2 rounded-full text-sm font-medium mb-4 animate-fade-in">
                            🎓 For Middle School Students (Grade 7-9)
                        </span>
                    </div>
                    <h1 class="text-6xl md:text-7xl font-bold mb-6 bg-gradient-to-r from-white to-blue-100 bg-clip-text text-transparent animate-slide-up">
                        EnglishEzy
                    </h1>
                    <p class="text-3xl mb-6 text-blue-100 font-light animate-slide-up" style="animation-delay: 0.2s;">
                        "Learn English the Easy Way!"
                    </p>
                    <p class="text-xl mb-8 text-blue-100 leading-relaxed animate-slide-up" style="animation-delay: 0.4s;">
                        Interactive English learning platform designed for Indonesian middle school students (Grade 7-9) following Kurikulum Merdeka. 
                        Make learning fun, engaging, and effective!
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4 animate-slide-up" style="animation-delay: 0.6s;">
                        <button onclick="scrollToSection('materials')" class="group bg-white text-blue-600 px-8 py-4 rounded-xl font-semibold hover:bg-blue-50 transition-all duration-300 transform hover:scale-105 shadow-lg">
                            <span class="flex items-center justify-center">
                                🚀 Start Learning
                                <svg class="w-5 h-5 ml-2 group-hover:translate-x-1 transition-transform" fill="currentColor" viewBox="0 0 20 20">
                                    <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                                </svg>
                            </span>
                        </button>
                        <button onclick="scrollToSection('assessment')" class="group border-2 border-white text-white px-8 py-4 rounded-xl font-semibold hover:bg-white hover:text-blue-600 transition-all duration-300 transform hover:scale-105">
                            <span class="flex items-center justify-center">
                                📊 Take Assessment
                            </span>
                        </button>
                    </div>
                    
                    <!-- Stats -->
                    <div class="grid grid-cols-3 gap-6 mt-12 animate-slide-up" style="animation-delay: 0.8s;">
                        <div class="text-center">
                            <div class="text-3xl font-bold text-white">1000+</div>
                            <div class="text-blue-200 text-sm">Active Students</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-white">50+</div>
                            <div class="text-blue-200 text-sm">Lessons</div>
                        </div>
                        <div class="text-center">
                            <div class="text-3xl font-bold text-white">95%</div>
                            <div class="text-blue-200 text-sm">Success Rate</div>
                        </div>
                    </div>
                </div>
                
                <!-- Animated Students Illustration -->
                <div class="relative">
                    <div class="animate-float">
                        <svg class="w-full h-96 mx-auto" viewBox="0 0 500 400" fill="none">
                            <!-- Background Circle -->
                            <circle cx="250" cy="200" r="180" fill="url(#bgGradient)" opacity="0.3"/>
                            
                            <!-- Classroom/Learning Environment -->
                            <rect x="150" y="180" width="200" height="120" rx="15" fill="#FFFFFF" class="animate-pulse"/>
                            <rect x="160" y="190" width="180" height="8" rx="4" fill="#3B82F6"/>
                            <rect x="160" y="205" width="140" height="6" rx="3" fill="#94A3B8"/>
                            <rect x="160" y="218" width="160" height="6" rx="3" fill="#94A3B8"/>
                            <rect x="160" y="231" width="120" height="6" rx="3" fill="#94A3B8"/>
                            
                            <!-- Student 1 (Girl) -->
                            <g class="animate-bounce" style="animation-delay: 0.5s;">
                                <circle cx="200" cy="140" r="30" fill="#FEF3C7"/>
                                <path d="M185 125 Q200 115 215 125" stroke="#8B4513" stroke-width="3" fill="none"/>
                                <circle cx="195" cy="135" r="2" fill="#374151"/>
                                <circle cx="205" cy="135" r="2" fill="#374151"/>
                                <path d="M195 145 Q200 150 205 145" stroke="#374151" stroke-width="2" fill="none"/>
                                <!-- Body -->
                                <rect x="185" y="170" width="30" height="40" rx="15" fill="#EC4899"/>
                                <!-- Arms -->
                                <circle cx="175" cy="185" r="8" fill="#FEF3C7"/>
                                <circle cx="225" cy="185" r="8" fill="#FEF3C7"/>
                                <!-- Book -->
                                <rect x="215" y="175" width="15" height="20" rx="2" fill="#3B82F6"/>
                            </g>
                            
                            <!-- Student 2 (Boy) -->
                            <g class="animate-bounce" style="animation-delay: 1s;">
                                <circle cx="300" cy="140" r="30" fill="#DBEAFE"/>
                                <path d="M285 125 Q300 115 315 125" stroke="#4B5563" stroke-width="3" fill="none"/>
                                <circle cx="295" cy="135" r="2" fill="#374151"/>
                                <circle cx="305" cy="135" r="2" fill="#374151"/>
                                <path d="M295 145 Q300 150 305 145" stroke="#374151" stroke-width="2" fill="none"/>
                                <!-- Body -->
                                <rect x="285" y="170" width="30" height="40" rx="15" fill="#10B981"/>
                                <!-- Arms -->
                                <circle cx="275" cy="185" r="8" fill="#DBEAFE"/>
                                <circle cx="325" cy="185" r="8" fill="#DBEAFE"/>
                                <!-- Laptop -->
                                <rect x="270" y="175" width="20" height="15" rx="2" fill="#374151"/>
                                <rect x="272" y="177" width="16" height="10" rx="1" fill="#60A5FA"/>
                            </g>
                            
                            <!-- Floating Elements -->
                            <g class="animate-ping" style="animation-delay: 2s;">
                                <text x="120" y="100" font-size="24">📚</text>
                                <text x="380" y="120" font-size="24">✏️</text>
                                <text x="100" y="300" font-size="24">🎯</text>
                                <text x="400" y="280" font-size="24">⭐</text>
                            </g>
                            
                            <!-- Speech Bubbles -->
                            <g class="animate-pulse">
                                <ellipse cx="150" cy="80" rx="40" ry="25" fill="#FFFFFF" opacity="0.9"/>
                                <text x="150" y="85" text-anchor="middle" font-size="12" fill="#3B82F6" font-weight="bold">Hello!</text>
                                
                                <ellipse cx="350" cy="80" rx="50" ry="25" fill="#FFFFFF" opacity="0.9"/>
                                <text x="350" y="85" text-anchor="middle" font-size="12" fill="#10B981" font-weight="bold">Let's learn!</text>
                            </g>
                            
                            <!-- Learning Progress Indicator -->
                            <rect x="200" y="320" width="100" height="8" rx="4" fill="#E5E7EB"/>
                            <rect x="200" y="320" width="75" height="8" rx="4" fill="#10B981" class="animate-pulse"/>
                            <text x="250" y="345" text-anchor="middle" font-size="12" fill="#FFFFFF" font-weight="bold">Learning Progress: 75%</text>
                            
                            <!-- Gradient Definitions -->
                            <defs>
                                <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" style="stop-color:#60A5FA;stop-opacity:1" />
                                    <stop offset="100%" style="stop-color:#A78BFA;stop-opacity:1" />
                                </linearGradient>
                            </defs>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Scroll Indicator -->
        <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 animate-bounce">
            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"></path>
            </svg>
        </div>
    </section>

    <!-- Quick Stats -->
    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="card-hover p-6">
                    <div class="text-4xl font-bold text-primary mb-2">50+</div>
                    <div class="text-gray-600">Complete Materials</div>
                </div>
                <div class="card-hover p-6">
                    <div class="text-4xl font-bold text-secondary mb-2">100+</div>
                    <div class="text-gray-600">Videos & Audio</div>
                </div>
                <div class="card-hover p-6">
                    <div class="text-4xl font-bold text-accent mb-2">200+</div>
                    <div class="text-gray-600">Practice Exercises</div>
                </div>
                <div class="card-hover p-6">
                    <div class="text-4xl font-bold text-purple-600 mb-2">24/7</div>
                    <div class="text-gray-600">Learning Access</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Learning Materials Section -->
    <section id="materials" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Learning Materials</h2>
                <p class="text-xl text-gray-600">Aligned with Kurikulum Merdeka for Middle School Grade 7-9 (Phase D)</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Text Structure -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                    <div class="w-16 h-16 bg-primary rounded-lg flex items-center justify-center mb-6">
                        <span class="text-2xl">📝</span>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Text Structure</h3>
                    <ul class="text-gray-600 space-y-2 mb-6">
                        <li>• Descriptive Text</li>
                        <li>• Narrative Text</li>
                        <li>• Recount Text</li>
                        <li>• Report Text</li>
                        <li>• Procedure Text</li>
                        <li>• Functional Text</li>
                    </ul>
                    <button onclick="openMateriModal('text-structure')" class="w-full bg-primary text-white py-3 rounded-lg hover:bg-blue-600 transition">Learn Now</button>
                </div>

                <!-- Grammar -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                    <div class="w-16 h-16 bg-secondary rounded-lg flex items-center justify-center mb-6">
                        <span class="text-2xl">⚙️</span>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Grammar</h3>
                    <ul class="text-gray-600 space-y-2 mb-6">
                        <li>• Tenses (Present, Past, Future)</li>
                        <li>• Modal Verbs</li>
                        <li>• Passive Voice</li>
                        <li>• Conjunctions</li>
                        <li>• Conditional Sentences</li>
                        <li>• Question Forms</li>
                    </ul>
                    <button onclick="openMateriModal('grammar')" class="w-full bg-secondary text-white py-3 rounded-lg hover:bg-green-600 transition">Learn Now</button>
                </div>

                <!-- Real Life Themes -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover">
                    <div class="w-16 h-16 bg-accent rounded-lg flex items-center justify-center mb-6">
                        <span class="text-2xl">🌍</span>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">Life Themes</h3>
                    <ul class="text-gray-600 space-y-2 mb-6">
                        <li>• Family & Friends</li>
                        <li>• School Life</li>
                        <li>• Hobbies & Interests</li>
                        <li>• Environment</li>
                        <li>• Technology</li>
                        <li>• Culture & Tradition</li>
                    </ul>
                    <button onclick="openMateriModal('life-themes')" class="w-full bg-accent text-white py-3 rounded-lg hover:bg-yellow-600 transition">Learn Now</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Learning Resources Section -->
    <section id="resources" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Multimedia Learning Resources</h2>
                <p class="text-xl text-gray-600">Learn with engaging and interactive media</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Video -->
                <div class="bg-gradient-to-br from-red-50 to-red-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-red-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🎥</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Video Learning</h3>
                    </div>
                    <ul class="text-gray-700 space-y-2 mb-6">
                        <li>• Teacher Explanations</li>
                        <li>• Storytelling</li>
                        <li>• Interactive Dialogues</li>
                        <li>• Pronunciation Guide</li>
                    </ul>
                    <button onclick="openMediaModal('video')" class="w-full bg-red-500 text-white py-3 rounded-lg hover:bg-red-600 transition">Watch Videos</button>
                </div>

                <!-- Audio -->
                <div class="bg-gradient-to-br from-purple-50 to-purple-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-purple-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🎧</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Audio Practice</h3>
                    </div>
                    <ul class="text-gray-700 space-y-2 mb-6">
                        <li>• Listening Practice</li>
                        <li>• Pronunciation</li>
                        <li>• English Songs</li>
                        <li>• Native Speaker</li>
                    </ul>
                    <button onclick="openMediaModal('audio')" class="w-full bg-purple-500 text-white py-3 rounded-lg hover:bg-purple-600 transition">Listen to Audio</button>
                </div>

                <!-- Interactive Dialog -->
                <div class="bg-gradient-to-br from-green-50 to-green-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-green-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">💬</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Interactive Dialogue</h3>
                    </div>
                    <ul class="text-gray-700 space-y-2 mb-6">
                        <li>• Conversation Simulation</li>
                        <li>• Role Playing</li>
                        <li>• Speaking Practice</li>
                        <li>• Real Situations</li>
                    </ul>
                    <button onclick="openMediaModal('dialog')" class="w-full bg-green-500 text-white py-3 rounded-lg hover:bg-green-600 transition">Start Dialogue</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Digital Worksheets Section -->
    <section id="worksheets" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Digital Worksheets</h2>
                <p class="text-xl text-gray-600">Interactive student worksheets for comprehensive practice</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Listening -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="text-center mb-4">
                        <div class="w-16 h-16 bg-blue-500 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">👂</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800">Listening</h3>
                    </div>
                    <p class="text-gray-600 text-center mb-6">Latihan mendengarkan dengan berbagai topik menarik</p>
                    <button onclick="openLKPDModal('listening')" class="w-full bg-blue-500 text-white py-2 rounded-lg hover:bg-blue-600 transition">Mulai Latihan</button>
                </div>

                <!-- Speaking -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="text-center mb-4">
                        <div class="w-16 h-16 bg-green-500 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">🗣️</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800">Speaking</h3>
                    </div>
                    <p class="text-gray-600 text-center mb-6">Praktik berbicara dengan panduan yang mudah</p>
                    <button onclick="openLKPDModal('speaking')" class="w-full bg-green-500 text-white py-2 rounded-lg hover:bg-green-600 transition">Mulai Latihan</button>
                </div>

                <!-- Reading -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="text-center mb-4">
                        <div class="w-16 h-16 bg-purple-500 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">📖</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800">Reading</h3>
                    </div>
                    <p class="text-gray-600 text-center mb-6">Bacaan menarik dengan pemahaman yang mendalam</p>
                    <button onclick="openLKPDModal('reading')" class="w-full bg-purple-500 text-white py-2 rounded-lg hover:bg-purple-600 transition">Mulai Latihan</button>
                </div>

                <!-- Writing -->
                <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                    <div class="text-center mb-4">
                        <div class="w-16 h-16 bg-orange-500 rounded-lg flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">✍️</span>
                        </div>
                        <h3 class="text-xl font-bold text-gray-800">Writing</h3>
                    </div>
                    <p class="text-gray-600 text-center mb-6">Latihan menulis dengan berbagai jenis teks</p>
                    <button onclick="openLKPDModal('writing')" class="w-full bg-orange-500 text-white py-2 rounded-lg hover:bg-orange-600 transition">Mulai Latihan</button>
                </div>
            </div>
        </div>
    </section>

    <!-- MPI Section -->
    <section id="mpi" class="py-20 bg-gradient-to-br from-indigo-50 to-purple-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">MPI (Media Pembelajaran Interaktif)</h2>
                <p class="text-xl text-gray-600">Interactive Learning Media for Engaging Education</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Home Sweet Home -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover border-2 border-pink-200">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-gradient-to-br from-pink-400 to-rose-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🏠</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Home Sweet Home</h3>
                        <p class="text-pink-600 font-medium">Interactive Learning Module</p>
                    </div>
                    <p class="text-gray-700 mb-6">Explore English learning through home and family themes with interactive multimedia content and engaging activities.</p>
                    <div class="space-y-3 mb-6">
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-pink-400 rounded-full mr-2"></span>
                            Family & Home Vocabulary
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-pink-400 rounded-full mr-2"></span>
                            Interactive Activities
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-pink-400 rounded-full mr-2"></span>
                            Multimedia Learning
                        </div>
                    </div>
                    <a href="https://procedure-text-smp.my.canva.site/misssanti-home-sweet-home" target="_blank" class="block w-full bg-gradient-to-r from-pink-500 to-rose-500 text-white py-3 rounded-lg hover:from-pink-600 hover:to-rose-600 transition text-center font-semibold">
                        🏡 Explore Home Sweet Home
                    </a>
                </div>

                <!-- CUMI Project -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover border-2 border-orange-200">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-gradient-to-br from-orange-400 to-red-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🍳</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">CUMI</h3>
                        <p class="text-orange-600 font-medium">(Culinary and Me)</p>
                    </div>
                    <p class="text-gray-700 mb-6">Interactive culinary project where students learn English through cooking procedures and food culture exploration.</p>
                    <div class="space-y-3 mb-6">
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-orange-400 rounded-full mr-2"></span>
                            Procedure Text Learning
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-orange-400 rounded-full mr-2"></span>
                            Cultural Food Exploration
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-orange-400 rounded-full mr-2"></span>
                            Interactive Recipe Creation
                        </div>
                    </div>
                    <a href="https://procedure-text-smp.my.canva.site/cumi-santi-rahmadani-s-pd" target="_blank" class="block w-full bg-gradient-to-r from-orange-500 to-red-500 text-white py-3 rounded-lg hover:from-orange-600 hover:to-red-600 transition text-center font-semibold">
                        🚀 Access CUMI Project
                    </a>
                </div>

                <!-- Secret Recipe -->
                <div class="bg-white rounded-xl shadow-lg p-8 card-hover border-2 border-purple-200">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-gradient-to-br from-purple-400 to-indigo-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🔮</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Secret Recipe</h3>
                        <p class="text-purple-600 font-medium">Mystery Cooking Adventure</p>
                    </div>
                    <p class="text-gray-700 mb-6">Discover hidden recipes and learn English through mysterious culinary adventures with step-by-step procedures.</p>
                    <div class="space-y-3 mb-6">
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-purple-400 rounded-full mr-2"></span>
                            Mystery Recipe Discovery
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-purple-400 rounded-full mr-2"></span>
                            Step-by-Step Procedures
                        </div>
                        <div class="flex items-center text-sm text-gray-600">
                            <span class="w-2 h-2 bg-purple-400 rounded-full mr-2"></span>
                            Interactive Cooking Guide
                        </div>
                    </div>
                    <a href="https://procedure-text-smp.my.canva.site/a-secret-recipe" target="_blank" class="block w-full bg-gradient-to-r from-purple-500 to-indigo-500 text-white py-3 rounded-lg hover:from-purple-600 hover:to-indigo-600 transition text-center font-semibold">
                        🔍 Discover Secret Recipe
                    </a>
                </div>
            </div>

            <!-- MPI Features -->
            <div class="mt-16 bg-white rounded-xl shadow-lg p-8">
                <h3 class="text-2xl font-bold text-gray-800 mb-6 text-center">MPI Features</h3>
                <div class="grid md:grid-cols-4 gap-6">
                    <div class="text-center">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <span class="text-2xl">🎮</span>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Interactive Content</h4>
                        <p class="text-sm text-gray-600">Engaging multimedia learning experiences</p>
                    </div>
                    <div class="text-center">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <span class="text-2xl">🎨</span>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Visual Learning</h4>
                        <p class="text-sm text-gray-600">Rich graphics and animations for better understanding</p>
                    </div>
                    <div class="text-center">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <span class="text-2xl">📱</span>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Mobile Friendly</h4>
                        <p class="text-sm text-gray-600">Access learning materials anywhere, anytime</p>
                    </div>
                    <div class="text-center">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-3">
                            <span class="text-2xl">⚡</span>
                        </div>
                        <h4 class="font-semibold text-gray-800 mb-2">Instant Feedback</h4>
                        <p class="text-sm text-gray-600">Real-time responses and progress tracking</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Assessment Section -->
    <section id="assessment" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold text-gray-800 mb-4">Assessment System</h2>
                <p class="text-xl text-gray-600">Comprehensive learning evaluation</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Diagnostic -->
                <div class="bg-gradient-to-br from-blue-50 to-blue-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-blue-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🔍</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Diagnostic Test</h3>
                    </div>
                    <p class="text-gray-700 mb-6">Assess students' initial abilities to determine the appropriate learning level</p>
                    <button onclick="startAssessment('diagnostic')" class="w-full bg-blue-500 text-white py-3 rounded-lg hover:bg-blue-600 transition">Start Test</button>
                </div>

                <!-- Formative -->
                <div class="bg-gradient-to-br from-green-50 to-green-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-green-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">📊</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Formative Test</h3>
                    </div>
                    <p class="text-gray-700 mb-6">Interactive quizzes in each sub-material to monitor learning progress</p>
                    <button onclick="startAssessment('formative')" class="w-full bg-green-500 text-white py-3 rounded-lg hover:bg-green-600 transition">Start Quiz</button>
                </div>

                <!-- Summative -->
                <div class="bg-gradient-to-br from-purple-50 to-purple-100 rounded-xl p-8 card-hover">
                    <div class="text-center mb-6">
                        <div class="w-20 h-20 bg-purple-500 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-3xl">🏆</span>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-800">Summative Test</h3>
                    </div>
                    <p class="text-gray-700 mb-6">Final unit/theme evaluation with automatic scoring system and feedback</p>
                    <button onclick="startAssessment('summative')" class="w-full bg-purple-500 text-white py-3 rounded-lg hover:bg-purple-600 transition">Start Evaluation</button>
                </div>
            </div>
        </div>
    </section>





    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <div class="w-10 h-10 bg-primary rounded-lg flex items-center justify-center mr-3">
                            <span class="text-white font-bold text-xl">E</span>
                        </div>
                        <span class="text-2xl font-bold">EnglishEzy</span>
                    </div>
                    <p class="text-gray-400">Platform pembelajaran Bahasa Inggris terbaik untuk siswa SMP kelas 7-9 sesuai Kurikulum Merdeka.</p>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Fitur Utama</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>Materi Interaktif</li>
                        <li>Video & Audio</li>
                        <li>LKPD Digital</li>
                        <li>Sistem Asesmen</li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Dukungan</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>Forum Diskusi</li>
                        <li>Bantuan Guru</li>
                        <li>Tutorial</li>
                        <li>FAQ</li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">Kontak</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li>📧 info@englishezy.id</li>
                        <li>📱 +62 812-3456-7890</li>
                        <li>🌐 www.englishezy.id</li>
                        <li>📍 Jakarta, Indonesia</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>&copy; 2024 EnglishEzy. All rights reserved. Made with ❤️ for Indonesian students.</p>
            </div>
        </div>
    </footer>

    <!-- Modals -->
    <!-- Materi Modal -->
    <div id="materiModal" class="fixed inset-0 bg-black bg-opacity-50 hidden z-50 flex items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-4xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-8">
                <div class="flex justify-between items-center mb-6">
                    <h3 id="materiTitle" class="text-3xl font-bold text-gray-800"></h3>
                    <button onclick="closeModal('materiModal')" class="text-gray-500 hover:text-gray-700 text-2xl">&times;</button>
                </div>
                <div id="materiContent" class="space-y-6">
                    <!-- Content will be loaded here -->
                </div>
            </div>
        </div>
    </div>

    <!-- Assessment Modal -->
    <div id="assessmentModal" class="fixed inset-0 bg-black bg-opacity-50 hidden z-50 flex items-center justify-center p-4">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto">
            <div class="p-8">
                <div class="flex justify-between items-center mb-6">
                    <h3 id="assessmentTitle" class="text-3xl font-bold text-gray-800"></h3>
                    <button onclick="closeModal('assessmentModal')" class="text-gray-500 hover:text-gray-700 text-2xl">&times;</button>
                </div>
                <div id="assessmentContent">
                    <!-- Assessment content will be loaded here -->
                </div>
            </div>
        </div>
    </div>

    <script>
        // Navigation functionality
        function toggleMobileMenu() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        }

        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }

        // Modal functionality
        function openMateriModal(type) {
            const modal = document.getElementById('materiModal');
            const title = document.getElementById('materiTitle');
            const content = document.getElementById('materiContent');
            
            const materiData = {
                'struktur-teks': {
                    title: 'Struktur Teks',
                    content: `
                        <div class="grid md:grid-cols-2 gap-6">
                            <div class="bg-blue-50 p-6 rounded-lg">
                                <h4 class="text-xl font-bold text-blue-800 mb-4">📝 Descriptive Text</h4>
                                <p class="text-gray-700 mb-4">Teks yang menggambarkan orang, tempat, atau benda secara detail.</p>
                                <div class="bg-white p-4 rounded border-l-4 border-blue-500">
                                    <strong>Contoh:</strong><br>
                                    "My school is a beautiful place. It has a large garden with colorful flowers..."
                                </div>
                                <button class="mt-4 bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600 transition">Pelajari Lebih Lanjut</button>
                            </div>
                            <div class="bg-green-50 p-6 rounded-lg">
                                <h4 class="text-xl font-bold text-green-800 mb-4">📚 Narrative Text</h4>
                                <p class="text-gray-700 mb-4">Teks yang menceritakan sebuah cerita dengan alur yang jelas.</p>
                                <div class="bg-white p-4 rounded border-l-4 border-green-500">
                                    <strong>Struktur:</strong><br>
                                    Orientation → Complication → Resolution
                                </div>
                                <button class="mt-4 bg-green-500 text-white px-4 py-2 rounded hover:bg-green-600 transition">Pelajari Lebih Lanjut</button>
                            </div>
                        </div>
                        <div class="mt-8 bg-gray-50 p-6 rounded-lg">
                            <h4 class="text-xl font-bold text-gray-800 mb-4">🎯 Latihan Interaktif</h4>
                            <p class="text-gray-700 mb-4">Kerjakan latihan berikut untuk memahami struktur teks:</p>
                            <div class="space-y-4">
                                <div class="bg-white p-4 rounded border">
                                    <p class="font-medium">1. Identifikasi jenis teks berikut:</p>
                                    <p class="text-gray-600 mt-2">"Once upon a time, there was a beautiful princess..."</p>
                                    <div class="mt-3 space-x-2">
                                        <button class="bg-blue-100 text-blue-800 px-3 py-1 rounded hover:bg-blue-200 transition">Descriptive</button>
                                        <button class="bg-green-100 text-green-800 px-3 py-1 rounded hover:bg-green-200 transition">Narrative</button>
                                        <button class="bg-purple-100 text-purple-800 px-3 py-1 rounded hover:bg-purple-200 transition">Recount</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    `
                },
                'grammar': {
                    title: 'Grammar Essentials',
                    content: `
                        <div class="space-y-6">
                            <div class="bg-gradient-to-r from-blue-50 to-blue-100 p-6 rounded-lg">
                                <h4 class="text-2xl font-bold text-blue-800 mb-4">⏰ Tenses</h4>
                                <div class="grid md:grid-cols-3 gap-4">
                                    <div class="bg-white p-4 rounded shadow">
                                        <h5 class="font-bold text-gray-800">Present Tense</h5>
                                        <p class="text-sm text-gray-600">I study English every day.</p>
                                    </div>
                                    <div class="bg-white p-4 rounded shadow">
                                        <h5 class="font-bold text-gray-800">Past Tense</h5>
                                        <p class="text-sm text-gray-600">I studied English yesterday.</p>
                                    </div>
                                    <div class="bg-white p-4 rounded shadow">
                                        <h5 class="font-bold text-gray-800">Future Tense</h5>
                                        <p class="text-sm text-gray-600">I will study English tomorrow.</p>
                                    </div>
                                </div>
                            </div>
                            <div class="bg-gradient-to-r from-green-50 to-green-100 p-6 rounded-lg">
                                <h4 class="text-2xl font-bold text-green-800 mb-4">🔧 Modal Verbs</h4>
                                <div class="bg-white p-4 rounded">
                                    <div class="grid md:grid-cols-2 gap-4">
                                        <div>
                                            <strong>Can/Could:</strong> Kemampuan<br>
                                            <em>I can speak English.</em>
                                        </div>
                                        <div>
                                            <strong>Must/Should:</strong> Keharusan<br>
                                            <em>You must study hard.</em>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="bg-yellow-50 p-6 rounded-lg">
                                <h4 class="text-xl font-bold text-yellow-800 mb-4">🎮 Grammar Game</h4>
                                <p class="text-gray-700 mb-4">Pilih bentuk kata kerja yang tepat:</p>
                                <div class="bg-white p-4 rounded border">
                                    <p class="font-medium">She _____ to school every morning.</p>
                                    <div class="mt-3 space-x-2">
                                        <button onclick="checkAnswer(this, false)" class="bg-red-100 text-red-800 px-3 py-1 rounded hover:bg-red-200 transition">go</button>
                                        <button onclick="checkAnswer(this, true)" class="bg-green-100 text-green-800 px-3 py-1 rounded hover:bg-green-200 transition">goes</button>
                                        <button onclick="checkAnswer(this, false)" class="bg-blue-100 text-blue-800 px-3 py-1 rounded hover:bg-blue-200 transition">going</button>
                                    </div>
                                    <div id="answer-feedback" class="mt-2 hidden"></div>
                                </div>
                            </div>
                        </div>
                    `
                },
                'tema-kehidupan': {
                    title: 'Tema Kehidupan Nyata',
                    content: `
                        <div class="grid md:grid-cols-2 gap-6">
                            <div class="bg-pink-50 p-6 rounded-lg">
                                <h4 class="text-xl font-bold text-pink-800 mb-4">👨‍👩‍👧‍👦 Family & Friends</h4>
                                <p class="text-gray-700 mb-4">Belajar vocabulary dan expressions tentang keluarga dan teman.</p>
                                <div class="space-y-2 text-sm">
                                    <div class="bg-white p-3 rounded">
                                        <strong>Vocabulary:</strong> mother, father, sister, brother, best friend
                                    </div>
                                    <div class="bg-white p-3 rounded">
                                        <strong>Expressions:</strong> "My family is very close" / "I have a best friend"
                                    </div>
                                </div>
                            </div>
                            <div class="bg-blue-50 p-6 rounded-lg">
                                <h4 class="text-xl font-bold text-blue-800 mb-4">🏫 School Life</h4>
                                <p class="text-gray-700 mb-4">Vocabulary dan situasi sehari-hari di sekolah.</p>
                                <div class="space-y-2 text-sm">
                                    <div class="bg-white p-3 rounded">
                                        <strong>Vocabulary:</strong> classroom, teacher, homework, exam, break time
                                    </div>
                                    <div class="bg-white p-3 rounded">
                                        <strong>Expressions:</strong> "I have math class" / "Let's go to the library"
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="mt-6 bg-green-50 p-6 rounded-lg">
                            <h4 class="text-xl font-bold text-green-800 mb-4">🎯 Interactive Activity</h4>
                            <p class="text-gray-700 mb-4">Ceritakan tentang keluargamu dalam bahasa Inggris:</p>
                            <textarea class="w-full p-4 border border-gray-300 rounded-lg" rows="4" placeholder="My family consists of... We like to..."></textarea>
                            <button class="mt-3 bg-green-500 text-white px-6 py-2 rounded hover:bg-green-600 transition">Submit & Get Feedback</button>
                        </div>
                    `
                }
            };
            
            title.textContent = materiData[type].title;
            content.innerHTML = materiData[type].content;
            modal.classList.remove('hidden');
        }

        function openMediaModal(type) {
            alert(`Membuka ${type} learning module. Fitur ini akan menampilkan konten multimedia interaktif!`);
        }

        function openLKPDModal(skill) {
            alert(`Membuka LKPD ${skill}. Siswa dapat mengerjakan latihan interaktif dan mengunduh dalam format PDF!`);
        }

        function startAssessment(type) {
            const modal = document.getElementById('assessmentModal');
            const title = document.getElementById('assessmentTitle');
            const content = document.getElementById('assessmentContent');
            
            const assessmentData = {
                'diagnostic': {
                    title: 'Tes Diagnostik',
                    content: `
                        <div class="text-center mb-6">
                            <div class="w-20 h-20 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-3xl">🔍</span>
                            </div>
                            <p class="text-gray-600">Tes ini akan membantu menentukan level kemampuan bahasa Inggris Anda</p>
                        </div>
                        <div class="bg-blue-50 p-6 rounded-lg mb-6">
                            <h4 class="font-bold text-blue-800 mb-3">Informasi Tes:</h4>
                            <ul class="space-y-2 text-blue-700">
                                <li>• 20 soal pilihan ganda</li>
                                <li>• Waktu: 30 menit</li>
                                <li>• Mencakup: Grammar, Vocabulary, Reading</li>
                                <li>• Hasil langsung tersedia</li>
                            </ul>
                        </div>
                        <div class="space-y-4">
                            <div class="bg-white border-2 border-gray-200 p-4 rounded-lg">
                                <p class="font-medium mb-3">1. Choose the correct answer:</p>
                                <p class="mb-3">I _____ English for three years.</p>
                                <div class="space-y-2">
                                    <label class="flex items-center">
                                        <input type="radio" name="q1" value="a" class="mr-2">
                                        <span>a) study</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="radio" name="q1" value="b" class="mr-2">
                                        <span>b) have studied</span>
                                    </label>
                                    <label class="flex items-center">
                                        <input type="radio" name="q1" value="c" class="mr-2">
                                        <span>c) studied</span>
                                    </label>
                                </div>
                            </div>
                            <div class="flex justify-between">
                                <button class="bg-gray-300 text-gray-700 px-6 py-2 rounded hover:bg-gray-400 transition">Previous</button>
                                <span class="flex items-center text-gray-600">Question 1 of 20</span>
                                <button class="bg-blue-500 text-white px-6 py-2 rounded hover:bg-blue-600 transition">Next</button>
                            </div>
                        </div>
                    `
                },
                'formative': {
                    title: 'Kuis Formatif',
                    content: `
                        <div class="text-center mb-6">
                            <div class="w-20 h-20 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-3xl">📊</span>
                            </div>
                            <p class="text-gray-600">Kuis singkat untuk mengecek pemahaman materi</p>
                        </div>
                        <div class="bg-green-50 p-4 rounded-lg mb-6">
                            <div class="flex justify-between items-center">
                                <span class="font-medium">Progress:</span>
                                <span class="text-green-600">3/5 completed</span>
                            </div>
                            <div class="w-full bg-gray-200 rounded-full h-2 mt-2">
                                <div class="bg-green-500 h-2 rounded-full" style="width: 60%"></div>
                            </div>
                        </div>
                        <div class="bg-white border-2 border-green-200 p-6 rounded-lg">
                            <h4 class="font-bold text-green-800 mb-4">Question 4: Grammar</h4>
                            <p class="mb-4">Which sentence is correct?</p>
                            <div class="space-y-3">
                                <label class="flex items-center p-3 border rounded hover:bg-gray-50 cursor-pointer">
                                    <input type="radio" name="q4" value="a" class="mr-3">
                                    <span>She don't like pizza.</span>
                                </label>
                                <label class="flex items-center p-3 border rounded hover:bg-gray-50 cursor-pointer">
                                    <input type="radio" name="q4" value="b" class="mr-3">
                                    <span>She doesn't like pizza.</span>
                                </label>
                                <label class="flex items-center p-3 border rounded hover:bg-gray-50 cursor-pointer">
                                    <input type="radio" name="q4" value="c" class="mr-3">
                                    <span>She not like pizza.</span>
                                </label>
                            </div>
                            <button class="w-full mt-4 bg-green-500 text-white py-3 rounded-lg hover:bg-green-600 transition">Submit Answer</button>
                        </div>
                    `
                },
                'summative': {
                    title: 'Evaluasi Sumatif',
                    content: `
                        <div class="text-center mb-6">
                            <div class="w-20 h-20 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                                <span class="text-3xl">🏆</span>
                            </div>
                            <p class="text-gray-600">Evaluasi komprehensif untuk mengukur pencapaian pembelajaran</p>
                        </div>
                        <div class="grid md:grid-cols-2 gap-6 mb-6">
                            <div class="bg-purple-50 p-4 rounded-lg">
                                <h4 class="font-bold text-purple-800 mb-2">📝 Writing Section</h4>
                                <p class="text-sm text-purple-700">Write a descriptive text about your favorite place (100 words)</p>
                            </div>
                            <div class="bg-purple-50 p-4 rounded-lg">
                                <h4 class="font-bold text-purple-800 mb-2">👂 Listening Section</h4>
                                <p class="text-sm text-purple-700">Listen to audio clips and answer comprehension questions</p>
                            </div>
                        </div>
                        <div class="bg-white border-2 border-purple-200 p-6 rounded-lg">
                            <h4 class="font-bold text-purple-800 mb-4">Reading Comprehension</h4>
                            <div class="bg-gray-50 p-4 rounded mb-4">
                                <p class="text-sm leading-relaxed">
                                    "Borobudur Temple is one of the most famous tourist destinations in Indonesia. 
                                    Located in Central Java, this ancient Buddhist temple was built in the 8th century. 
                                    The temple consists of nine stacked platforms, six square and three circular, 
                                    topped by a central dome..."
                                </p>
                            </div>
                            <div class="space-y-3">
                                <div>
                                    <p class="font-medium mb-2">1. Where is Borobudur Temple located?</p>
                                    <input type="text" class="w-full p-3 border rounded-lg" placeholder="Your answer...">
                                </div>
                                <div>
                                    <p class="font-medium mb-2">2. When was the temple built?</p>
                                    <input type="text" class="w-full p-3 border rounded-lg" placeholder="Your answer...">
                                </div>
                            </div>
                        </div>
                        <div class="mt-6 flex justify-center">
                            <button class="bg-purple-500 text-white px-8 py-3 rounded-lg hover:bg-purple-600 transition">Submit Final Exam</button>
                        </div>
                    `
                }
            };
            
            title.textContent = assessmentData[type].title;
            content.innerHTML = assessmentData[type].content;
            modal.classList.remove('hidden');
        }

        function openMPIProject(projectType) {
            const projectData = {
                'storytelling': {
                    title: 'Digital Storytelling Project',
                    description: 'Create engaging digital stories with multimedia elements while mastering narrative text structure.',
                    features: ['Video creation tools', 'Story templates', 'Peer review system', 'Portfolio showcase']
                },
                'eco-campaign': {
                    title: 'Environmental Campaign Project', 
                    description: 'Design compelling environmental awareness campaigns using persuasive writing and visual design.',
                    features: ['Campaign templates', 'Design tools', 'Impact tracking', 'Community sharing']
                }
            };
            
            const project = projectData[projectType];
            alert(`🚀 ${project.title}\n\n${project.description}\n\nFeatures:\n${project.features.map(f => `• ${f}`).join('\n')}\n\nProject akan segera tersedia!`);
        }



        function closeModal(modalId) {
            document.getElementById(modalId).classList.add('hidden');
        }

        function checkAnswer(button, isCorrect) {
            const feedback = document.getElementById('answer-feedback');
            feedback.classList.remove('hidden');
            
            if (isCorrect) {
                feedback.innerHTML = '<div class="text-green-600 font-medium">✅ Benar! "Goes" adalah bentuk yang tepat untuk subjek "she".</div>';
                button.classList.add('bg-green-200', 'border-green-500');
            } else {
                feedback.innerHTML = '<div class="text-red-600 font-medium">❌ Salah. Coba lagi! Ingat: untuk subjek "she/he/it" gunakan verb + s/es.</div>';
                button.classList.add('bg-red-200', 'border-red-500');
            }
        }

        // Smooth scrolling for navigation links
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                scrollToSection(targetId);
                
                // Update active nav link
                document.querySelectorAll('.nav-link').forEach(l => l.classList.remove('text-primary', 'font-medium'));
                this.classList.add('text-primary', 'font-medium');
            });
        });

        // Close modals when clicking outside
        window.addEventListener('click', function(e) {
            if (e.target.classList.contains('fixed')) {
                e.target.classList.add('hidden');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9726041921af9c44',t:'MTc1NTczNjE2Ni4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
