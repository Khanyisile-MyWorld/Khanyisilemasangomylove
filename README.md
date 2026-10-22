<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>For Khanyisile | An Adventure Invitation</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Premium Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400&family=Inter:wght@200;300;400;500&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'cream': '#FAF7F2',
                        'soft-rose': '#E2B6B1',
                        'deep-rose': '#9E6B65',
                        'gold': '#C5A374',
                        'text-main': '#3D2B29'
                    },
                    fontFamily: {
                        serif: ['"Cormorant Garamond"', 'serif'],
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>
    
    <style>
        :root {
            --bg-cream: #FAF7F2;
            --soft-rose: #E2B6B1;
            --deep-rose: #9E6B65;
            --gold: #C5A374;
            --text-main: #3D2B29;
            --easing: cubic-bezier(0.23, 1, 0.32, 1);
        }

        body {
            background-color: var(--bg-cream);
            color: var(--text-main);
            font-family: 'Inter', sans-serif;
            overflow-x: hidden;
            line-height: 1.7;
        }

        h1, h2, h3, h4, .serif {
            font-family: 'Cormorant Garamond', serif;
            font-weight: 300;
        }

        /* Canvas Background */
        #petal-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 10;
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% { transform: translateY(0); }
            40% { transform: translateY(-10px); }
            60% { transform: translateY(-5px); }
        }

        .animate-fade-in { animation: fadeIn 1.8s forwards 0.3s; opacity: 0; }
        .animate-fade-in-up { animation: fadeInUp 1.8s forwards 0.6s; opacity: 0; }
        .scroll-indicator { animation: bounce 2s infinite; }

        /* Floating particles for adventure section */
        .sparkle {
            position: absolute;
            pointer-events: none;
            background: radial-gradient(circle, rgba(197,163,116,0.8) 0%, rgba(226,182,177,0) 70%);
            border-radius: 50%;
            animation: floatUp 4s infinite linear;
        }

        @keyframes floatUp {
            0% { transform: translateY(0) scale(0.8); opacity: 0.2; }
            50% { opacity: 0.8; }
            100% { transform: translateY(-80px) scale(1.2); opacity: 0; }
        }
    </style>
</head>
<body class="bg-[#FAF7F2] text-[#3D2B29] selection:bg-[#E2B6B1] selection:text-[#3D2B29]">

    <!-- Floating Petal Canvas -->
    <canvas id="petal-canvas"></canvas>

    <!-- 1. Hero & Welcome Section -->
    <section class="min-h-screen flex flex-col justify-center items-center text-center px-6 relative z-20">
        <p class="text-xs md:text-sm tracking-[0.3em] uppercase text-gold mb-4 animate-fade-in">A Dedicated Space For You</p>
        <h1 class="text-4xl sm:text-6xl md:text-7xl lg:text-8xl font-serif leading-[1.1] mb-6 animate-fade-in-up">
            Welcome to our story, <br><span class="italic text-deep-rose">Khanyisile.</span>
        </h1>
        <div class="max-w-2xl mx-auto px-4 mt-4 animate-fade-in-up" style="animation-delay: 1s;">
            <p class="text-lg md:text-xl font-serif text-text-main/90 italic">
                "I created this quiet little corner of the world just for you. A place to pause, reflect, and hold close every beautiful heartbeat of what we share."
            </p>
        </div>
        <div class="scroll-indicator absolute bottom-10 text-[0.7rem] tracking-[3px] uppercase opacity-50">
            Scroll to explore
        </div>
    </section>

    <!-- 2. Deep Feelings / Narrative Note -->
    <section class="py-20 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-white/70 backdrop-blur-md p-8 md:p-14 rounded-3xl shadow-xl shadow-stone-200/50 border border-stone-100 text-center transition-all duration-700 hover:shadow-2xl">
            <span class="text-gold uppercase tracking-[0.2em] text-xs font-semibold block mb-3">From My Heart</span>
            <h2 class="text-3xl md:text-5xl font-serif mb-6">How You Illuminate My World</h2>
            <div class="space-y-6 text-base md:text-lg text-text-main/80 font-light leading-relaxed max-w-2xl mx-auto">
                <p>

You bring a kind of light into my life that makes even the simplest moments feel special. From your laughter to the little things that make you uniquely you, I find more reasons to appreciate you every day.<br><br>

Thank you for your honesty, for opening up to me, and for allowing me to understand you on a deeper level. I value your willingness to have the conversations that help us grow, and I never want to take your trust or your presence in my life for granted.<br><br>


You are someone I want to keep learning, growing, and creating beautiful memories with. And if there's one thing I hope you always know, it's that I appreciate you not only for how you make me feel, but for the wonderful person you are. ❤️

                </p>
            </div>
        </div>
    </section>

    <!-- 3. Photo Gallery Section -->
    <section class="py-20 px-6 max-w-7xl mx-auto z-20 relative">
        <div class="text-center mb-16">
            <span class="text-gold uppercase tracking-[0.3em] text-xs block mb-2">Moments in Time</span>
            <h2 class="text-3xl md:text-5xl font-serif">Our Gallery of Memories</h2>
        </div>
        
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 1.jpeg" alt="Memory 1" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+1'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Precious moments</p>
            </div>
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 2.jpeg" alt="Memory 2" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+2'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Radiant smile</p>
            </div>
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 3.jpeg" alt="Memory 3" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+3'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Unforgettable days</p>
            </div>
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 4.jpeg" alt="Memory 4" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+4'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Pure elegance</p>
            </div>
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 5.jpeg" alt="Memory 5" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+5'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Endless warmth</p>
            </div>
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 6.jpeg" alt="Memory 6" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+6'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">My favorite person</p>
            </div>
        </div>
    </section>

    <!-- 4. Curated Apple Music Playlist Section -->
    <section class="py-20 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-gradient-to-br from-stone-900 to-stone-800 text-cream rounded-3xl p-8 md:p-14 shadow-2xl relative overflow-hidden text-center">
            <div class="absolute -right-20 -top-20 w-64 h-64 bg-deep-rose/30 rounded-full blur-3xl pointer-events-none"></div>
            
            <span class="text-gold uppercase tracking-[0.25em] text-xs font-medium block mb-3">A Curated Soundtrack</span>
            <h3 class="text-3xl md:text-4xl font-serif mb-4">Songs That Remind Me of You</h3>
            <p class="text-stone-300 text-sm md:text-base mb-8 max-w-xl mx-auto font-light">
                I put together a special playlist of melodies that capture every lovely thought I have of you. Listen directly on Apple Music anytime.
            </p>

            <a href="https://music.apple.com/za/playlist/a-piece-of-me-to-you/pl.u-11zBX4muN08aDyy" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-3 px-8 py-4 rounded-full bg-[#fa243c] hover:bg-[#e01b33] text-white uppercase tracking-widest text-xs font-semibold shadow-xl transition-all duration-300 hover:-translate-y-1">
                <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24">
                    <path d="M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm3.328 13.974c-.58.337-1.488.528-2.435.528-2.222 0-3.793-1.341-3.793-3.692 0-2.31 1.637-3.766 3.905-3.766.902 0 1.705.176 2.235.485v1.64c-.496-.282-1.205-.443-1.93-.443-1.24 0-2.072.783-2.072 2.052 0 1.258.85 2.023 2.115 2.023.702 0 1.348-.157 1.88-.445v1.618z"/>
                </svg>
                Listen on Apple Music
            </a>
        </div>
    </section>

    <!-- 5. THE ADVENTURE INVITATION (4 STAGES) -->
    <section id="adventure-section" class="py-24 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-white/85 backdrop-blur-md p-8 md:p-16 rounded-3xl shadow-xl border border-stone-200/80 transition-all duration-700 relative overflow-hidden">
            
            <!-- STAGE 1: THE ANTICIPATION -->
            <div id="adventure-stage-1" class="text-center py-6">
                <span class="text-gold uppercase tracking-[0.3em] text-xs font-semibold block mb-4">A Next Chapter</span>
                <h3 class="text-3xl md:text-5xl font-serif text-text-main mb-8 leading-tight">
                    There's something I've been wanting to ask you…
                </h3>
                <button onclick="goToStage(2)" class="px-9 py-4 rounded-full bg-deep-rose text-white uppercase tracking-widest text-xs font-medium shadow-lg hover:bg-rose-700 hover:-translate-y-1 transition-all">
                    Discover Your Surprise
                </button>
            </div>

            <!-- STAGE 2: THE PERSONAL MESSAGE -->
            <div id="adventure-stage-2" class="hidden text-center transition-all duration-700">
                <span class="text-gold uppercase tracking-[0.3em] text-xs font-semibold block mb-4">Just Between Us</span>
                <div class="max-w-2xl mx-auto text-left sm:text-center space-y-5 text-text-main/90 font-light text-base md:text-lg leading-relaxed mb-10">
                    <p class="font-serif italic text-2xl text-deep-rose text-center mb-6">My love,</p>
                    <p>
                        Life gets busy, days come and go, and sometimes we get caught up in everything happening around us. But amidst it all, there's something I never want us to forget: making time for each other, creating memories, and giving ourselves little moments that belong only to us.
                    </p>
                    <p>
                        So, I've been planning something.
                    </p>
                    <p>
                        Nothing you need to organise. Nothing you need to figure out. Just an opportunity for you and me to step away from the usual, enjoy each other's company, and make a memory we can look back on with a smile.
                    </p>
                    <p>
                        I've kept a few things a secret because I want you to experience this one little surprise as it unfolds.
                    </p>
                    <p class="font-medium text-text-main pt-2">
                        But before I reveal anything else, there's one thing I need to ask you…
                    </p>
                </div>
                <button onclick="goToStage(3)" class="px-8 py-4 rounded-full bg-deep-rose text-white uppercase tracking-widest text-xs font-medium shadow-lg hover:bg-rose-700 hover:-translate-y-1 transition-all">
                    There's Something I Want to Ask You
                </button>
            </div>

            <!-- STAGE 3: THE GRAND INVITATION REVEAL -->
            <div id="adventure-stage-3" class="hidden text-center transition-all duration-700">
                <div class="inline-block border-y border-gold/40 py-3 px-8 mb-6">
                    <p class="text-xs tracking-[0.4em] uppercase text-gold font-semibold mb-1">05 · 12 · 2026</p>
                    <p class="text-sm font-serif tracking-widest text-stone-600">SATURDAY, 5 DECEMBER 2026</p>
                </div>

                <h2 class="text-4xl md:text-6xl font-serif text-deep-rose mb-6">An Adventure With You</h2>

                <div class="max-w-xl mx-auto space-y-4 text-text-main/80 font-light text-base md:text-lg leading-relaxed mb-8">
                    <p>
                        My love, I'd love to steal you away for a day that's just ours.
                    </p>
                    <p>
                        A little adventure, a change of scenery, beautiful memories, and time for just you and me.
                    </p>
                    <p>
                        The details can remain a little mystery for now, but there's one thing I know for certain: I'd love to experience it with you.
                    </p>
                    <p class="font-serif italic text-xl text-gold pt-2">So, my love…</p>
                </div>

                <h3 class="text-3xl md:text-5xl font-serif text-text-main font-normal tracking-wide mb-10 leading-snug">
                    WILL YOU COME ON AN ADVENTURE WITH ME?
                </h3>

                <!-- STAGE 4: RESPONSE OPTIONS -->
                <div class="flex flex-col sm:flex-row justify-center items-center gap-4">
                    <button onclick="acceptAdventure()" class="w-full sm:w-auto px-8 py-4 rounded-full bg-deep-rose text-white uppercase tracking-widest text-xs font-medium shadow-xl hover:bg-rose-700 hover:-translate-y-1 transition-all">
                        YES, MY LOVE ❤️
                    </button>
                    <button onclick="openMoreDetailsModal()" class="w-full sm:w-auto px-8 py-4 rounded-full bg-soft-rose/80 hover:bg-soft-rose text-text-main uppercase tracking-widest text-xs font-medium shadow-md transition-all">
                        Tell Me a Little More…
                    </button>
                </div>
            </div>

            <!-- STAGE 4 CONFIRMATION & COUNTDOWN -->
            <div id="adventure-stage-confirmation" class="hidden text-center transition-all duration-700">
                <div class="text-center">
                    <span class="text-4xl mb-2 block">✨ ❤️ ✨</span>
                    <h3 class="text-3xl md:text-5xl font-serif text-deep-rose mb-4">YOU'VE MADE ME SO HAPPY. ❤️</h3>
                    <p class="text-gold uppercase tracking-[0.2em] text-xs font-semibold mb-6">It's a date, my love!</p>
                    
                    <div class="max-w-xl mx-auto space-y-4 text-text-main/80 font-light text-base md:text-lg mb-10">
                        <p>
                            Saturday, 5 December 2026 is officially our little adventure day.
                        </p>
                        <p>
                            The destination and details can stay a secret a little longer, but I cannot wait to make another beautiful memory with you.
                        </p>
                        <p class="italic font-serif text-xl text-deep-rose">
                            Until then, keep a little space in your heart for something special.
                        </p>
                        <p class="text-sm font-medium tracking-wider text-stone-500 uppercase">
                            Love always, your favourite person.
                        </p>
                    </div>

                    <!-- Live Countdown to Saturday, 5 December 2026 (09:00 SAST) -->
                    <div class="pt-8 border-t border-stone-200">
                        <span class="text-xs uppercase tracking-[0.3em] text-gold font-semibold block mb-4">Countdown to Our Adventure</span>
                        <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 max-w-xl mx-auto">
                            <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                                <span id="adv-days" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                                <span class="text-xs uppercase tracking-wider text-stone-500">Days</span>
                            </div>
                            <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                                <span id="adv-hours" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                                <span class="text-xs uppercase tracking-wider text-stone-500">Hours</span>
                            </div>
                            <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                                <span id="adv-minutes" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                                <span class="text-xs uppercase tracking-wider text-stone-500">Minutes</span>
                            </div>
                            <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                                <span id="adv-seconds" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                                <span class="text-xs uppercase tracking-wider text-stone-500">Seconds</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <!-- 6. Interactive Memory Game Section -->
    <section class="py-20 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-white/90 backdrop-blur-md p-8 md:p-12 rounded-3xl shadow-xl border border-stone-200 text-center">
            <span class="text-gold uppercase tracking-[0.3em] text-xs font-semibold block mb-3">Play Together</span>
            <h2 class="text-3xl md:text-4xl font-serif mb-3">Our Love Memory Match</h2>
            <p class="text-stone-600 text-sm md:text-base mb-8 max-w-md mx-auto font-light">
                Test your memory! Match the romantic icons to unlock a special secret note just for you.
            </p>

            <div id="memory-game" class="grid grid-cols-4 gap-3 sm:gap-4 max-w-md mx-auto mb-6">
                <!-- Cards generated via JS -->
            </div>

            <div class="flex justify-between items-center max-w-md mx-auto px-2">
                <p id="game-status" class="text-sm font-medium text-deep-rose">Matches: <span id="match-count">0</span> / 4</p>
                <button onclick="initGame()" class="px-4 py-2 bg-stone-100 hover:bg-stone-200 text-stone-700 rounded-xl text-xs uppercase tracking-wider transition-colors font-medium">
                    Reset Game
                </button>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 text-center text-xs tracking-widest text-stone-500 uppercase z-20 relative border-t border-stone-200/60">
        <p>Made with infinite love for Khanyisile, DESIGNED BY MPUMELELO HLONGWANE</p>
    </footer>

    <!-- Modal for 'Tell Me a Little More...' Response -->
    <div id="details-modal" class="fixed inset-0 bg-black/40 backdrop-blur-sm z-50 hidden flex justify-center items-center p-4">
        <div class="bg-white p-8 md:p-10 rounded-3xl shadow-2xl max-w-md w-full text-center border border-stone-100 animate-fade-in-up">
            <span class="text-3xl mb-2 block">✨ ❤️</span>
            <h4 class="text-2xl font-serif mb-4 text-deep-rose">Oh, my love, curious already? ❤️</h4>
            <div class="text-stone-600 text-sm md:text-base space-y-3 mb-6 font-light leading-relaxed">
                <p>I could tell you everything, but where would the fun be in that?</p>
                <p>All you need to know for now is that I want us to have a day to remember.</p>
                <p>The rest? You'll have to wait and see.</p>
                <p class="font-medium text-text-main pt-2">So, what do you say? Will you let me take you on this little adventure?</p>
            </div>
            <button onclick="closeDetailsModal()" class="w-full py-3.5 bg-deep-rose text-white rounded-full uppercase tracking-wider text-xs font-medium shadow-md hover:bg-rose-700 transition-colors">
                Back to the Question ❤️
            </button>
        </div>
    </div>

    <!-- Custom Message Modal for Game -->
    <div id="modal" class="fixed inset-0 bg-black/40 backdrop-blur-sm z-50 hidden flex justify-center items-center p-4">
        <div class="bg-white p-8 rounded-3xl shadow-2xl max-w-sm w-full text-center border border-stone-100 animate-fade-in-up">
            <h4 id="modal-title" class="text-2xl font-serif mb-2 text-deep-rose">A Note For You</h4>
            <p id="modal-message" class="text-stone-600 text-sm mb-6 leading-relaxed">You successfully matched all the memories!</p>
            <button onclick="closeModal()" class="w-full py-3 bg-deep-rose text-white rounded-full uppercase tracking-wider text-xs font-medium shadow-md hover:bg-rose-700 transition-colors">
                Wonderful
            </button>
        </div>
    </div>

    <!-- JavaScript Application Logic -->
    <script>
        // --- 1. Falling Petal Canvas Background Effect ---
        const canvas = document.getElementById('petal-canvas');
        const ctx = canvas.getContext('2d');
        let petals = [];

        function initCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        window.addEventListener('resize', initCanvas);
        initCanvas();

        class Petal {
            constructor() { this.init(); }
            init() {
                this.x = Math.random() * canvas.width;
                this.y = Math.random() * -canvas.height;
                this.w = Math.random() * 15 + 5;
                this.h = this.w * 0.8;
                this.opacity = Math.random() * 0.5 + 0.2;
                this.speed = Math.random() * 1 + 0.5;
                this.rotation = Math.random() * 360;
                this.spin = Math.random() * 2 - 1;
            }
            draw() {
                this.y += this.speed;
                this.rotation += this.spin;
                if (this.y > canvas.height) this.init();
                
                ctx.save();
                ctx.translate(this.x, this.y);
                ctx.rotate(this.rotation * Math.PI / 180);
                ctx.beginPath();
                ctx.ellipse(0, 0, this.w, this.h, 0, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(226, 182, 177, ${this.opacity})`;
                ctx.fill();
                ctx.restore();
            }
        }

        for (let i = 0; i < 50; i++) petals.push(new Petal());

        function animatePetals() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            petals.forEach(p => p.draw());
            requestAnimationFrame(animatePetals);
        }
        animatePetals();

        // --- 2. Adventure Invitation Stage Transitions ---
        function goToStage(stageNum) {
            document.getElementById('adventure-stage-1').classList.add('hidden');
            document.getElementById('adventure-stage-2').classList.add('hidden');
            document.getElementById('adventure-stage-3').classList.add('hidden');
            document.getElementById('adventure-stage-confirmation').classList.add('hidden');

            const nextStage = document.getElementById(`adventure-stage-${stageNum}`);
            if (nextStage) {
                nextStage.classList.remove('hidden');
                // Scroll smoothly to section center
                document.getElementById('adventure-section').scrollIntoView({ behavior: 'smooth', block: 'center' });
            }
        }

        function openMoreDetailsModal() {
            document.getElementById('details-modal').style.display = 'flex';
        }

        function closeDetailsModal() {
            document.getElementById('details-modal').style.display = 'none';
        }

        function acceptAdventure() {
            document.getElementById('adventure-stage-3').classList.add('hidden');
            const confirmStage = document.getElementById('adventure-stage-confirmation');
            confirmStage.classList.remove('hidden');

            // Burst of petals
            for (let i = 0; i < 80; i++) petals.push(new Petal());

            // Start adventure countdown
            startAdventureCountdown();

            document.getElementById('adventure-section').scrollIntoView({ behavior: 'smooth', block: 'center' });
        }

        // --- 3. Live Countdown to Saturday, 5 December 2026 (09:00 SAST / UTC+2) ---
        const adventureTargetDate = new Date('2026-12-05T09:00:00+02:00').getTime();
        let adventureTimerInterval = null;

        function updateAdventureCountdown() {
            const now = new Date().getTime();
            const difference = adventureTargetDate - now;

            if (difference <= 0) {
                document.getElementById('adv-days').textContent = '00';
                document.getElementById('adv-hours').textContent = '00';
                document.getElementById('adv-minutes').textContent = '00';
                document.getElementById('adv-seconds').textContent = '00';
                if (adventureTimerInterval) clearInterval(adventureTimerInterval);
                return;
            }

            const days = Math.floor(difference / (1000 * 60 * 60 * 24));
            const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((difference % (1000 * 60)) / 1000);

            document.getElementById('adv-days').textContent = String(days).padStart(2, '0');
            document.getElementById('adv-hours').textContent = String(hours).padStart(2, '0');
            document.getElementById('adv-minutes').textContent = String(minutes).padStart(2, '0');
            document.getElementById('adv-seconds').textContent = String(seconds).padStart(2, '0');
        }

        function startAdventureCountdown() {
            updateAdventureCountdown();
            if (!adventureTimerInterval) {
                adventureTimerInterval = setInterval(updateAdventureCountdown, 1000);
            }
        }

        // --- 4. Interactive Memory Match Game ---
        const emojis = ['🌹', '❤️', '✨', '💌'];
        let cardArray = [...emojis, ...emojis];
        let flippedCards = [];
        let matchedPairs = 0;
        let lockBoard = false;

        function initGame() {
            const gameBoard = document.getElementById('memory-game');
            gameBoard.innerHTML = '';
            matchedPairs = 0;
            document.getElementById('match-count').textContent = matchedPairs;
            flippedCards = [];
            lockBoard = false;

            cardArray.sort(() => 0.5 - Math.random());

            cardArray.forEach((symbol, index) => {
                const card = document.createElement('div');
                card.classList.add('h-20', 'bg-cream', 'border', 'border-stone-200', 'rounded-2xl', 'flex', 'items-center', 'justify-center', 'text-2xl', 'cursor-pointer', 'shadow-inner', 'transition-all', 'duration-300', 'hover:border-deep-rose');
                card.dataset.symbol = symbol;
                card.dataset.index = index;
                card.addEventListener('click', flipCard);
                gameBoard.appendChild(card);
            });
        }

        function flipCard() {
            if (lockBoard) return;
            if (this.classList.contains('matched') || this.classList.contains('flipped')) return;

            this.textContent = this.dataset.symbol;
            this.classList.add('bg-white', 'flipped', 'shadow-md');
            flippedCards.push(this);

            if (flippedCards.length === 2) {
                checkMatch();
            }
        }

        function checkMatch() {
            const [card1, card2] = flippedCards;
            const isMatch = card1.dataset.symbol === card2.dataset.symbol;

            if (isMatch) {
                card1.classList.add('matched', 'border-deep-rose');
                card2.classList.add('matched', 'border-deep-rose');
                matchedPairs++;
                document.getElementById('match-count').textContent = matchedPairs;
                flippedCards = [];

                if (matchedPairs === emojis.length) {
                    showModal("A Sweet Secret Unlocked", "You matched all our memories, Khanyisile! You make every single day of my life feel like poetry.");
                }
            } else {
                lockBoard = true;
                setTimeout(() => {
                    card1.textContent = '';
                    card2.textContent = '';
                    card1.classList.remove('bg-white', 'flipped', 'shadow-md');
                    card2.classList.remove('bg-white', 'flipped', 'shadow-md');
                    flippedCards = [];
                    lockBoard = false;
                }, 900);
            }
        }

        function showModal(title, message) {
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-message').textContent = message;
            document.getElementById('modal').style.display = 'flex';
        }

        function closeModal() {
            document.getElementById('modal').style.display = 'none';
        }

        // Initialize game on load
        initGame();
    </script>
</body>
</html>
