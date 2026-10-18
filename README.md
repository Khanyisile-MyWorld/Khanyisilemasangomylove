<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>For Khanyisile | A Special Journey</title>
    
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

        h1, h2, h3, .serif {
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

        .animate-fade-in { animation: fadeIn 2s forwards 0.5s; opacity: 0; }
        .animate-fade-in-up { animation: fadeInUp 2s forwards 1s; opacity: 0; }
        .scroll-indicator { animation: bounce 2s infinite; }
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
        <div class="max-w-2xl mx-auto px-4 mt-4 animate-fade-in-up" style="animation-delay: 1.4s;">
            <p class="text-lg md:text-xl font-serif text-text-main/90 italic">
                "I created this quiet little corner of the world just for you. A place to pause, reflect, and hold close every beautiful heartbeat of what we share."
            </p>
        </div>
        <div class="scroll-indicator absolute bottom-10 text-[0.7rem] tracking-[3px] uppercase opacity-50">
            Scroll to explore
        </div>
    </section>

    <!-- Deep Feelings / Narrative Note -->
    <section class="py-24 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-white/70 backdrop-blur-md p-8 md:p-14 rounded-3xl shadow-xl shadow-stone-200/50 border border-stone-100 text-center transition-all duration-700 hover:shadow-2xl">
            <span class="text-gold uppercase tracking-[0.2em] text-xs font-semibold block mb-3">From My Heart</span>
            <h2 class="text-3xl md:text-5xl font-serif mb-6">How You Illuminate My World</h2>
            <div class="space-y-6 text-base md:text-lg text-text-main/80 font-light leading-relaxed max-w-2xl mx-auto">
                <p>
                

My love,

Sometimes I wonder if you truly understand the kind of light you bring into my world. It's not just in your smile, your laugh, or the way your eyes light up when you're happy. It's in the way your presence can make an ordinary day feel a little less ordinary, how a simple conversation with you can stay with me long after it's over, and how even the thought of seeing you can give me something beautiful to look forward to.<br><br>

Before you, I never really understood how one person could make such a difference without even trying. You don't have to do anything extraordinary. You don't have to have the perfect words or make every moment magical. Sometimes, it's simply you being you that makes everything feel a little brighter.<br><br>

You illuminate the little corners of my world that I might otherwise overlook. You remind me that there is beauty in the smallest things, that happiness can live in a shared laugh, a quiet moment, a long conversation, or simply being beside someone who means something to you.<br><br>

And if I could give you one thing, it would be the ability to see yourself through my eyes, even for a moment. I wish you could see how beautiful you are to me, not just in the ways the world might notice, but in all the little ways that make you *you*. I wish you could feel how much your presence matters, how deeply I appreciate the moments we share, and how much I look forward to all the moments we haven't experienced yet.<br><br>

I don't need every day to be extraordinary. I just want more days where I get to discover another reason to smile because of you. More memories, more laughter, more little adventures, and more moments where the world slows down just enough for me to appreciate that I get to share a part of it with you.<br><br>

You are not responsible for making my world beautiful, and I never want you to feel that you have to be anything other than yourself. But you have brought a kind of light into it that I wouldn't trade for anything.<br><br>

And if life ever feels heavy, or if you ever forget just how special you are, I hope you remember this: somewhere in this world, there is someone who looks at you and sees so much more than words can explain.<br><br>

You don't just brighten my days, my love. You illuminate my world in ways you may never fully realise. And one of my favourite things about life is knowing that there are still so many beautiful moments ahead of us, waiting to be shared.<br><br>

With all my love,
Always yours. ❤️

                </p>
            </div>
        </div>
    </section>

    <!-- 2. Gallery Section -->
    <section class="py-20 px-6 max-w-7xl mx-auto z-20 relative">
        <div class="text-center mb-16">
            <span class="text-gold uppercase tracking-[0.3em] text-xs block mb-2">Moments in Time</span>
            <h2 class="text-3xl md:text-5xl font-serif">Our Gallery of Memories</h2>
        </div>
        
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Gallery Item 1 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 1.jpeg" alt="Memory 1" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+1'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Precious moments</p>
            </div>
            <!-- Gallery Item 2 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 2.jpeg" alt="Memory 2" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+2'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Radiant smile</p>
            </div>
            <!-- Gallery Item 3 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 3.jpeg" alt="Memory 3" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+3'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Unforgettable days</p>
            </div>
            <!-- Gallery Item 4 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 4.jpeg" alt="Memory 4" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+4'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Pure elegance</p>
            </div>
            <!-- Gallery Item 5 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform hover:-translate-y-2 hover:rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 5.jpeg" alt="Memory 5" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+5'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">Endless warmth</p>
            </div>
            <!-- Gallery Item 6 -->
            <div class="bg-white p-4 pb-12 shadow-md hover:shadow-2xl transition-all duration-500 rounded-lg transform sm:translate-y-6 hover:-translate-y-2 hover:-rotate-1 group">
                <div class="overflow-hidden aspect-[4/5] bg-stone-100 mb-4 rounded">
                    <img src="herpictures/Khanyi 6.jpeg" alt="Memory 6" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" onerror="this.src='https://placehold.co/600x750/E2B6B1/3D2B29?text=Khanyisile+6'">
                </div>
                <p class="font-serif text-center text-sm tracking-widest text-deep-rose italic">My favorite person</p>
            </div>
        </div>
    </section>

    <!-- 3. Curated Apple Music Playlist Section -->
    <section class="py-20 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-gradient-to-br from-stone-900 to-stone-800 text-cream rounded-3xl p-8 md:p-14 shadow-2xl relative overflow-hidden text-center">
            <!-- Decorative blur orb -->
            <div class="absolute -right-20 -top-20 w-64 h-64 bg-deep-rose/30 rounded-full blur-3xl pointer-events-none"></div>
            
            <span class="text-gold uppercase tracking-[0.25em] text-xs font-medium block mb-3">A Curated Soundtrack</span>
            <h3 class="text-3xl md:text-4xl font-serif mb-4">Songs That Remind Me of You</h3>
            <p class="text-stone-300 text-sm md:text-base mb-8 max-w-xl mx-auto font-light">
                I put together a special playlist of melodies that capture every lovely thought I have of you. Listen directly on Apple Music anytime.
            </p>

            <a href="https://music.apple.com/za/playlist/a-piece-of-me-to-you/pl.u-11zBX4muN08aDyy" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-3 px-8 py-4 rounded-full bg-[#fa243c] hover:bg-[#e01b33] text-white uppercase tracking-widest text-xs font-semibold shadow-xl transition-all duration-300 hover:-translate-y-1">
                <!-- Apple Music Icon SVG -->
                <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24">
                    <path d="M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10 10-4.477 10-10S17.523 2 12 2zm3.328 13.974c-.58.337-1.488.528-2.435.528-2.222 0-3.793-1.341-3.793-3.692 0-2.31 1.637-3.766 3.905-3.766.902 0 1.705.176 2.235.485v1.64c-.496-.282-1.205-.443-1.93-.443-1.24 0-2.072.783-2.072 2.052 0 1.258.85 2.023 2.115 2.023.702 0 1.348-.157 1.88-.445v1.618z"/>
                </svg>
                Listen on Apple Music
            </a>
        </div>
    </section>

    <!-- 4. The Big Reveal & Live Countdown Section -->
    <section class="py-24 px-6 max-w-4xl mx-auto z-20 relative text-center">
        <div class="bg-white/80 backdrop-blur-md p-10 md:p-16 rounded-3xl shadow-xl border border-stone-200">
            <span class="text-gold uppercase tracking-[0.3em] text-xs font-semibold block mb-3">Mark Your Calendar</span>
            <h2 class="text-3xl md:text-5xl font-serif mb-4">Prepare Yourself for the Big News</h2>
            <p class="text-stone-600 max-w-xl mx-auto mb-10 text-base md:text-lg font-light">
                Something truly special is awaiting us. Get ready for an unforgettable announcement shared with you on <span class="font-medium text-text-main">Friday, the 23rd of October, 2026</span>.
            </p>

            <!-- Countdown Timer Grid -->
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-4 max-w-xl mx-auto mb-12">
                <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                    <span id="days" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                    <span class="text-xs uppercase tracking-wider text-stone-500">Days</span>
                </div>
                <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                    <span id="hours" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                    <span class="text-xs uppercase tracking-wider text-stone-500">Hours</span>
                </div>
                <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                    <span id="minutes" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                    <span class="text-xs uppercase tracking-wider text-stone-500">Minutes</span>
                </div>
                <div class="bg-cream p-4 rounded-2xl border border-stone-200 shadow-inner">
                    <span id="seconds" class="text-3xl md:text-4xl font-serif text-deep-rose font-bold block">00</span>
                    <span class="text-xs uppercase tracking-wider text-stone-500">Seconds</span>
                </div>
            </div>

            <!-- Valentine Question Trigger -->
            <div class="pt-6 border-t border-stone-200">
                <h3 class="text-2xl md:text-3xl font-serif mb-6">Khanyisile, will you go on this adventure with me?</h3>
                <div class="flex flex-wrap justify-center gap-4">
                    <button onclick="triggerCelebration()" class="px-8 py-4 rounded-full bg-deep-rose text-white uppercase tracking-widest text-xs font-medium shadow-lg hover:bg-rose-700 hover:-translate-y-1 transition-all">
                        Yes, I'd love to ❤️
                    </button>
                    <button id="btn-move" class="px-8 py-4 rounded-full bg-soft-rose text-text-main uppercase tracking-widest text-xs font-medium shadow-md transition-all">
                        Yes (Obviously)
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. Interactive Game Section -->
    <section class="py-24 px-6 max-w-4xl mx-auto z-20 relative">
        <div class="bg-white/90 backdrop-blur-md p-8 md:p-12 rounded-3xl shadow-xl border border-stone-200 text-center">
            <span class="text-gold uppercase tracking-[0.3em] text-xs font-semibold block mb-3">Play Together</span>
            <h2 class="text-3xl md:text-4xl font-serif mb-3">Our Love Memory Match</h2>
            <p class="text-stone-600 text-sm md:text-base mb-8 max-w-md mx-auto font-light">
                Test your memory! Match the romantic icons to unlock a special secret note just for you.
            </p>

            <!-- Game Board -->
            <div id="memory-game" class="grid grid-cols-4 gap-3 sm:gap-4 max-w-md mx-auto mb-6">
                <!-- Cards generated via JS -->
            </div>

            <!-- Game Status & Reset -->
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
        <p>Made with infinite love for Khanyisile By Mpumelelo Hlongwane • October 2026</p>
    </footer>

    <!-- Success Celebration Overlay -->
    <div id="overlay" class="fixed inset-0 bg-cream/95 backdrop-blur-md z-50 hidden flex-col justify-center items-center text-center p-6 opacity-0 transition-opacity duration-700">
        <h3 class="text-4xl md:text-6xl font-serif mb-4 text-deep-rose">I can't wait for the 23rd.</h3>
        <p class="text-gold uppercase tracking-[0.3em] text-sm mb-8 font-medium">You made me the happiest person in the world</p>
        <button onclick="closeCelebration()" class="px-8 py-3 rounded-full bg-deep-rose text-white uppercase tracking-widest text-xs font-medium shadow-lg hover:bg-rose-700 transition-all">
            Continue Our Journey
        </button>
    </div>

    <!-- Custom Message Modal (Replaces alert) -->
    <div id="modal" class="fixed inset-0 bg-black/40 backdrop-blur-sm z-50 hidden flex justify-center items-center p-4">
        <div class="bg-white p-8 rounded-3xl shadow-2xl max-w-sm w-full text-center border border-stone-100 animate-fade-in-up">
            <h4 id="modal-title" class="text-2xl font-serif mb-2 text-deep-rose">A Note For You</h4>
            <p id="modal-message" class="text-stone-600 text-sm mb-6 leading-relaxed">You successfully matched all the memories!</p>
            <button onclick="closeModal()" class="w-full py-3 bg-deep-rose text-white rounded-xl uppercase tracking-wider text-xs font-medium shadow-md hover:bg-rose-700 transition-colors">
                Wonderful
            </button>
        </div>
    </div>

    <!-- JavaScript Application Logic -->
    <script>
        // --- 1. Petal Rain Canvas Effect ---
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

        // --- 2. Live Countdown to October 23, 2026 ---
        const targetDate = new Date('October 23, 2026 00:00:00').getTime();

        function updateCountdown() {
            const now = new Date().getTime();
            const difference = targetDate - now;

            if (difference < 0) {
                document.getElementById('days').textContent = '00';
                document.getElementById('hours').textContent = '00';
                document.getElementById('minutes').textContent = '00';
                document.getElementById('seconds').textContent = '00';
                return;
            }

            const days = Math.floor(difference / (1000 * 60 * 60 * 24));
            const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((difference % (1000 * 60)) / 1000);

            document.getElementById('days').textContent = String(days).padStart(2, '0');
            document.getElementById('hours').textContent = String(hours).padStart(2, '0');
            document.getElementById('minutes').textContent = String(minutes).padStart(2, '0');
            document.getElementById('seconds').textContent = String(seconds).padStart(2, '0');
        }
        setInterval(updateCountdown, 1000);
        updateCountdown();

        // --- 3. Celebration & "No" Button Evasion ---
        function triggerCelebration() {
            const overlay = document.getElementById('overlay');
            overlay.style.display = 'flex';
            setTimeout(() => overlay.style.opacity = '1', 50);
            for (let i = 0; i < 100; i++) petals.push(new Petal());
        }

        function closeCelebration() {
            const overlay = document.getElementById('overlay');
            overlay.style.opacity = '0';
            setTimeout(() => overlay.style.display = 'none', 700);
        }

        const moveBtn = document.getElementById('btn-move');
        moveBtn.addEventListener('mouseover', () => {
            if (window.innerWidth > 768) {
                moveBtn.style.transform = `translate(${Math.random() * 120 - 60}px, ${Math.random() * 60 - 30}px)`;
            }
        });
        moveBtn.addEventListener('click', triggerCelebration);

        // --- 4. Interactive Memory Match Game ---
        const emojis = ['🌹', '❤️', '✨', '💌'];
        let cardArray = [...emojis, ...emojis]; // 8 cards total (4 pairs)
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

            // Shuffle cards
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
