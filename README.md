<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>House Day 2025: The Ultimate Christmas Takeover!</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Mountains+of+Christmas:wght@700&family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
            /* Warm cream background with subtle snowflake pattern */
            background-color: #fffaf0;
            background-image: url("data:image/svg+xml,%3Csvg width='40' height='40' viewBox='0 0 40 40' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23e2d8c5' fill-opacity='0.4' fill-rule='evenodd'%3E%3Cpath d='M20 20c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM0 0c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm10 10c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm10-10c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM0 20c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM30 10c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM20 30c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm10 10c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM10 30c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zm20-20c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2zM30 30c1.1 0 2 .9 2 2s-.9 2-2 2-2-.9-2-2 .9-2 2-2z'/%3E%3C/g%3E%3C/svg%3E");
        }
        h1, h2.festive-font {
            font-family: 'Mountains of Christmas', cursive;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 900px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .header-green { color: #15803d; }
        .header-orange { color: #c2410c; }
        .header-purple { color: #7e22ce; }
        .header-blue { color: #1d4ed8; }
        .header-red { color: #b91c1c; }

        /* Festive Header Background - Updated with a real festive image */
        .festive-header-bg {
            background: linear-gradient(rgba(255,255,255,0.1), rgba(255,255,255,0.1)), url('https://images.template.net/270259/Blank-Christmas-Banner-edit-online-7.jpg');
            background-size: 100% 100%, 50% 100%;
	    background-repeat: no-repeat, repeat-x;
            background-position: center, left top;
            border-bottom: 8px solid transparent;
            border-image: repeating-linear-gradient(45deg, #b91c1c, #b91c1c 10px, #ffffff 10px, #ffffff 20px) 1;
        }

        .house-card {
            /* Text centered explicitly */
            @apply flex flex-col items-center justify-center p-6 rounded-lg text-white shadow-lg text-2xl font-bold relative overflow-hidden transform transition hover:scale-105 text-center;
        }
        /* Add a little snow effect on top of house cards */
        .house-card::before {
            content: ❄️';
            position: absolute;
            top: -5px;
            right: 5px;
            opacity: 0.5;
            font-size: 1.5rem;
        }

        /* Activity Card Styling */
        .activity-card {
            @apply bg-white rounded-xl shadow-md flex flex-col overflow-hidden border border-gray-100 cursor-pointer h-full;
            transition: all 0.3s ease;
        }
        .activity-card:hover {
            @apply shadow-2xl -translate-y-2 border-red-300;
            /* Candy cane border on hover */
            border-image: repeating-linear-gradient(45deg, #b91c1c, #b91c1c 10px, #15803d 10px, #15803d 20px) 1;
        }
        .activity-card-image-container {
            @apply relative h-48 w-full overflow-hidden bg-gray-200;
        }
        .activity-card img {
            @apply w-full h-full object-cover transition-transform duration-500;
        }
        .activity-card:hover img {
            @apply scale-110;
        }
        .activity-icon-overlay {
            @apply absolute top-2 right-2 bg-white/90 rounded-full p-2 text-2xl shadow-sm backdrop-blur-sm;
        }
        .activity-card-content {
            @apply p-6 flex-grow flex flex-col relative;
        }

       <! -- /* Festive divider - TOP - current commented out*/
	.activity-card-content::before {
  	 content: '';
  	 position: absolute;
  	 top: 0;
   	 left: 25%;
   	 width: 50%;
   	 height: 4px;
   	 background: repeating-linear-gradient(to right, #b91c1c, #b91c1c 5px, #15803d 5px, #15803d 10px);
  	 border-radius: 0 0 4px 4px; /* Rounded corners point down */
	}
	 -->

	/* Festive divider - BOTTOM */
	.activity-card-content::after {
	  content: '';
	  position: absolute;
	  bottom: 0;
	  left: 25%;
	  width: 50%;
	  height: 4px;
	  background: repeating-linear-gradient(to right, #b91c1c, #b91c1c 5px, #15803d 5px, #15803d 10px);
	  border-radius: 4px 4px 0 0; /* Rounded corners point up */
	}

        .activity-card h3 {
            @apply text-xl font-extrabold mb-2 text-gray-800 mt-4;
        }
        .activity-card p {
            @apply text-gray-600 text-sm leading-relaxed font-medium;
        }
        
        .activity-card:hover p {
            @apply text-gray-900;
        }

        /* Timeline Styling */
        .timeline-item {
            @apply relative flex items-start pb-8;
        }
        .timeline-item:last-child {
            @apply pb-0;
        }
        .timeline-item-connector {
            @apply absolute left-5 top-5 h-full w-0.5 bg-red-300;
        }
        .timeline-item:last-child .timeline-item-connector {
            @apply h-0;
        }
        .timeline-item-dot {
            @apply relative z-10 h-10 w-10 rounded-full flex items-center justify-center bg-red-600 text-white font-bold shadow-md border-2 border-white ring-2 ring-red-200;
        }
        .timeline-item-content {
            @apply ml-6 bg-white p-4 rounded-lg shadow-sm border-l-4 border-red-500 w-full;
        }
        .timeline-item-content .time {
            @apply text-sm font-semibold text-red-600;
        }
        .timeline-item-content .title {
            @apply text-lg font-bold text-gray-800;
        }

        /* CTA Button Style */
        .cta-button {
            @apply inline-block bg-gradient-to-r from-red-600 to-red-800 text-white font-black text-xl py-4 px-10 rounded-full shadow-lg hover:shadow-xl transition-all transform hover:scale-105 border-4 border-white hover:border-green-300 animate-bounce;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }
    </style>
</head>
<body class="bg-gray-100">

    <header class="festive-header-bg shadow-md relative overflow-hidden">
    <div class="container mx-auto px-4 py-8 text-center relative z-10 bg-white/80 rounded-2xl max-w-2xl mt-6 backdrop-blur-sm border-double border-8 border-yellow-500">
        
        <h1 class="text-4xl md:text-6xl font-bold header-red mb-2 festive-font drop-shadow-lg">🎄 House Day 2025 🎄</h1>
        <h2 class="text-2xl md:text-4xl font-black text-green-700 festive-font tracking-wider">The Ultimate Christmas Takeover!</h2>
        
        <div class="mt-6 w-full mx-auto text-base bg-white/80 p-4 rounded-xl shadow-md border-2 border-red-200 backdrop-blur-md">
            <p class="text-gray-800 font-semibold leading-relaxed">
                Forget the timetable. This isn't just a non-uniform day - it's an epic, <span class="text-red-600 font-black">festive competition</span> where your House can shine! We’re setting aside lessons for a day packed with thrilling challenges. You control your destiny: lock in the two activities that get you fired up and ignite your competitive spirit. <br><span class="text-red-600 font-black">Win BIG for your House and help bring home the Cup!</span>
            </p>
        </div>

</div> <div class="mt-10 relative z-10 text-center pb-12">
        <a href="https://forms.gle/BbWYuXKaQ9fud9F26" target="_blank" class="cta-button text-green-700 hover:text-green-800">
            🎅 SECURE YOUR SPOT NOW! 🎅
        </a>
                <p class="text-sm mt-3 font-bold text-white">Places are limited - first come, first served!</p>
            </div>
    </header>

    <main class="container mx-auto p-4 md:p-8 relative z-10 -mt-8">

        <section class="grid grid-cols-2 md:grid-cols-4 gap-4 mb-12">
    <div class="house-card flex justify-center items-center bg-gradient-to-br from-orange-400 to-orange-600 border-b-4 border-orange-800">
        <span class="drop-shadow-md">Atholl-Sussex</span>
    </div>
    <div class="house-card flex justify-center items-center bg-gradient-to-br from-purple-400 to-purple-600 border-b-4 border-purple-800">
        <span class="drop-shadow-md">Cumberland</span>
    </div>
    <div class="house-card flex justify-center items-center bg-gradient-to-br from-green-400 to-green-600 border-b-4 border-green-800">
        <span class="drop-shadow-md">Moira</span>
    </div>
    <div class="house-card flex justify-center items-center bg-gradient-to-br from-blue-400 to-blue-600 border-b-4 border-blue-800">
        <span class="drop-shadow-md">Scarborough</span>
    </div>
	</section>

        <section class="grid grid-cols-1 lg:grid-cols-3 gap-8 mb-12">
            
            <div class="lg:col-span-1 bg-white rounded-2xl shadow-xl p-6 border-t-4 border-red-500 relative overflow-hidden">
                <span class="absolute top-0 right-0 text-5xl opacity-75 p-2">📜</span>
                <h2 class="text-3xl font-bold text-gray-800 mb-6 festive-font header-red">The Schedule 🎅</h2>
                <ol class="relative">
                    <li class="timeline-item">
                        <div class="timeline-item-connector"></div>
                        <div class="timeline-item-dot">1</div>
                        <div class="timeline-item-content">
                            <span class="time">08:35 - 09:40</span>
                            <h3 class="title">Morning Briefing</h3>
                            <p class="text-gray-600 text-sm">Whole School Opening Assembly in the Great Hall. Intro to the day and House Hype!</p>
                        </div>
                    </li>
                    <li class="timeline-item">
                        <div class="timeline-item-connector"></div>
                        <div class="timeline-item-dot">2</div>
                        <div class="timeline-item-content">
                            <span class="time">10:00 - 11:00</span>
                            <h3 class="title">Session 1</h3>
                            <p class="text-gray-600 text-sm">Head to your first chosen activity!</p>
                        </div>
                    </li>
                    <li class="timeline-item">
                        <div class="timeline-item-connector"></div>
                        <div class="timeline-item-dot">3</div>
                        <div class="timeline-item-content">
                            <span class="time">11:05 - 12:05</span>
                            <h3 class="title">Session 2</h3>
                            <p class="text-gray-600 text-sm">Head to your second chosen activity!</p>
                        </div>
                    </li>
                    <li class="timeline-item">
                        <div class="timeline-item-connector"></div>
                        <div class="timeline-item-dot">4</div>
                        <div class="timeline-item-content">
                            <span class="time">12:10 - 12:40</span>
                            <h3 class="title">The Grand Finale 🎉</h3>
                            <p class="text-gray-600 text-sm">Just Dance and Carols: Celebration for all in the Great Hall. Final Points!</p>
                        </div>
                    </li>
                    <li class="timeline-item">
                        <div class="timeline-item-dot">5</div>
                        <div class="timeline-item-content">
                            <span class="time">12:40 - 14:00</span>
                            <h3 class="title">Lunch & Dismissal</h3>
                            <p class="text-gray-600 text-sm">Enjoy lunch, registration in forms, and then home!</p>
                        </div>
                    </li>
                </ol>
            </div>

            <div class="lg:col-span-2 bg-white rounded-2xl shadow-xl p-6 border-t-4 border-green-500 relative overflow-hidden">
                 <span class="absolute top-0 right-0 text-5xl opacity-75 p-2">🏆</span>
                <h2 class="text-3xl font-bold text-gray-800 mb-6 festive-font header-green">How to Score Big 🎁</h2>
                <p class="text-gray-700 mb-8 text-lg font-semibold">The House Cup is on the line! Do you have what it takes to bring it home? Here’s the breakdown:</p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="bg-blue-50 rounded-xl p-6 text-center border-4 border-blue-200 shadow-md hover:shadow-xl transition-all transform hover:-translate-y-1 relative group">
                        <div class="absolute -top-4 -left-4 text-4xl group-hover:scale-125 transition">🥇</div>
                        <span class="text-7xl drop-shadow-sm" role="img" aria-label="trophy">🏆</span>
                        <h3 class="text-xl font-black text-gray-800 mt-4 uppercase">Champion Status</h3>
                        <p class="text-6xl font-extrabold header-blue my-2 drop-shadow-sm">50</p>
                        <p class="text-blue-900 font-bold">Dominate your session and claim glory for your House.</p>
                    </div>
                    <div class="bg-green-50 rounded-xl p-6 text-center border-4 border-green-200 shadow-md hover:shadow-xl transition-all transform hover:-translate-y-1 relative group">
                         <div class="absolute -top-4 -left-4 text-4xl group-hover:scale-125 transition">😎</div>
                        <span class="text-7xl drop-shadow-sm" role="img" aria-label="checkmark">✅</span>
                        <h3 class="text-xl font-black text-gray-800 mt-4 uppercase">Show Up, Show Out</h3>
                        <p class="text-6xl font-extrabold header-green my-2 drop-shadow-sm">5</p>
                        <p class="text-green-900 font-bold">Just being there and completing an activity earns respect (and points).</p>
                    </div>
                    <div class="bg-orange-50 rounded-xl p-6 text-center border-4 border-orange-200 shadow-md hover:shadow-xl transition-all transform hover:-translate-y-1 relative group">
                        <div class="absolute -top-4 -left-4 text-4xl group-hover:scale-125 transition">🤩</div>
                        <span class="text-7xl drop-shadow-sm" role="img" aria-label="ticket">🎟️</span>
                        <h3 class="text-xl font-black text-gray-800 mt-4 uppercase">Legendary Vibe</h3>
                        <p class="text-6xl font-extrabold header-orange my-2 drop-shadow-sm">20</p>
                        <p class="text-orange-900 font-bold">Blow the staff away with epic teamwork to earn a "Golden Ticket"!</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden border-t-8 border-blue-400 relative">
            <h2 class="text-3xl font-bold text-gray-800 mb-4 text-center festive-font header-red">The Activity Lineup 📊</h2>
            <p class="text-gray-700 mb-8 text-center max-w-3xl mx-auto text-lg font-semibold">We’ve stacked the deck with something for everyone. Whether you want to sweat, create, solve, or just chill, your perfect day is waiting. Check the mix!</p>
            <div class="chart-container">
                <canvas id="activityMixChart"></canvas>
            </div>
                    </div>

                </div>
            </div>
        </section>
       

        <section class="mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden border-t-8 border-orange-400 relative">
                <span class="absolute top-0 left-0 text-6xl opacity-5 p-4 transform -rotate-12">🦌</span>
                <div class="flex items-center justify-center bg-orange-100 py-6">
                    <span class="text-5xl mr-4 animate-pulse">🦌</span>
                    <h2 class="text-4xl md:text-5xl font-black text-center header-orange festive-font drop-shadow-sm">Juniors (Y7 & 8): Pick Your Challenges!</h2>
                    <span class="text-5xl ml-4 animate-pulse">🦌</span>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 p-6 md:p-8">
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/c2410c/ffffff?text=Obstacle+Course&font=roboto" alt="Obstacle Course">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🏃💨</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>A: The Grinch’s Obstacle Course</h3>
                            <p>A high-octane relay race in the Sports Hall. Navigate through "chimneys" (tunnels), jump through "icy ponds" (hoops), and master the "sleigh pull" (weighted gym mats). Speed, agility, and chaos! Can your team outwit the Grinch?</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/15803d/ffffff?text=Eco-Wreath+Making&font=roboto" alt="Wreath">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">�♻️</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>B: Eco-Wreath Making</h3>
                            <p>Get crafty and sustainable! Use foraged materials like twigs, leaves, and holly, combined with recycled fabric scraps, to create your own beautiful and eco-friendly Christmas wreath. A perfect way to bring natural festive cheer home!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/a855f7/ffffff?text=Panto+Time&font=roboto" alt="Drama Stage">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🎭🎬</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>C: Panto Pandemonium</h3>
                            <p>Lights, camera, ACTION! In the Drama Studio, your group has 45 minutes to recreate a hilarious 2-minute version of a classic fairytale with a Christmas twist. Props and costumes provided! The best performance wins ultimate bragging rights!</p>
                        </div>
                    </div>
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/3b82f6/ffffff?text=Elf+Escape+Room&font=roboto" alt="Escape Room Locks">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🔐🧠</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>D: Elf Escape Room</h3>
                            <p>Emergency! Santa has lost the keys to the sleigh! Your team must solve a series of logic puzzles, maths codes, and riddles to unlock the box and save Christmas before time runs out! Teamwork is key to escaping!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/ef4444/ffffff?text=Carol-oke&font=roboto" alt="Karaoke Microphone">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🎤🎸</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>E: Christmas "Carol-oke"</h3>
                            <p>Bring the noise! A festive karaoke competition in the Music Room. Major points will be awarded for enthusiasm, volume, and terrible choreography! Your requested songs are included, so warm up those vocal cords!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/c2410c/ffffff?text=Capture+the+Pudding&font=roboto" alt="Capture the Flag">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🚩🏃‍♀️</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>F: Capture the Pudding</h3>
                            <p>A festive version of Capture the Flag on the Astro (or Gym if wet). Your team must sneak into enemy territory to steal the "Christmas Pudding" (a weighted medicine ball) and return it to your base without getting caught! Tactical movement and swift actions will lead to victory!</p>
                        </div>
                    </div>

                    <div class="activity-card lg:col-start-2 group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/eab308/ffffff?text=Pom+Poms+%26+Looms&font=roboto" alt="Loom Bands">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🧶😊</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>G: The Pom Pom & Loom Band Lab</h3>
                            <p>A relaxing creative session. Choose between making festive yarn pom-poms (think adorable Robins, Snowmen, or Puddings) or creating intricate red, green, and gold festive bracelets and charms with loom bands. Perfect for a calming, crafty break!</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <section class="mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden border-t-8 border-purple-400 relative">
                <span class="absolute top-0 right-0 text-6xl opacity-5 p-4 transform rotate-12">⛄</span>
                <div class="flex items-center justify-center bg-purple-100 py-6 relative overflow-hidden">
                    <span class="text-5xl mr-4 animate-bounce">⛄</span>
                    <h2 class="text-4xl md:text-5xl font-black text-center header-purple festive-font drop-shadow-sm">Intermediates (Y9 & 10): Step Up! Claim Your Zone!</h2>
                    <span class="text-5xl ml-4 animate-bounce">⛄</span>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 p-6 md:p-8">
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/7e22ce/ffffff?text=Snowball+Dodgeball&font=roboto" alt="Dodgeball">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🏐❄️</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>A: Snowball Dodgeball</h3>
                            <p>It’s a high-intensity dodgeball tournament in the Gymnasium! Standard rules apply, but with special "Medic" rules (one "Rudolph" can save players). Watch out for "Blizzard Mode" where foam snowballs are dumped onto the court for 30 seconds of pure chaos! Dodge, duck, dip, dive, and dodge!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/a855f7/ffffff?text=Festive+Print+Shop&font=roboto" alt="Block Printing">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🖌️🎁</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>B: The Festive Print Shop</h3>
                            <p>Head to the Art/DT rooms to learn exciting block printing techniques! You will get to design and create your very own custom Wrapping Paper and unique Christmas Cards to take home. Impress everyone with your bespoke designs!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/f97316/ffffff?text=Gingerbread+Engineering&font=roboto" alt="Gingerbread House">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🍬🏗️</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>C: Gingerbread Engineering & Lego Winter Village</h3>
                            <p>Two choices! 1) Use biscuits, wafers, and icing "cement" to build the tallest, most structurally sound tower that can withstand a fan "snowstorm". 2) A parallel Lego competition for those with allergies to build a fantastic festive village. May the best builder win!</p>
                        </div>
                    </div>
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/1d4ed8/ffffff?text=Big+Fat+Quiz&font=roboto" alt="Quiz">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🧠❓</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>D: The Big Fat Quiz of the Year</h3>
                            <p>Prove your knowledge in this massive multimedia quiz! It covers music, news, and memes from 2025, and as requested, includes a special "Christmas Movie Trivia" round! Gather your team and prepare for a true test of wits!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/b91c1c/ffffff?text=Taskmaster+Elf&font=roboto" alt="Taskmaster Envelope">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">📜⏱️</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>E: Taskmaster: Elf Edition</h3>
                            <p>Expect the unexpected! Fast-paced, wacky challenges await, including "Competitive Present Wrapping" (judged on speed and aesthetics) and the "Longest Paper Chain challenge using only one hand"! The Taskmaster awaits!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/22c55e/ffffff?text=Workshop+Crafts&font=roboto" alt="Crafts">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🎨✨</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>F: The Workshop: Gnomes & Baubles</h3>
                            <p>A dual craft workshop! Choose between creating "Gonk" style gnomes using socks, rice, and felt beards OR decorating styrofoam baubles and wooden hanging ornaments to adorn your tree. Get creative!</p>
                        </div>
                    </div>

                     <div class="activity-card lg:col-start-2 group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/6b7280/ffffff?text=The+Ad-Prentice&font=roboto" alt="Video Editing">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🎬💡</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>G: The "Ad-Prentice" Pitch</h3>
                            <p>Your team must script, storyboard, and then film a John Lewis-style tear-jerker Christmas advert in the IT rooms. You'll then present your final "Pitch" to the dragons (staff) at the end!</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <section class="mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden border-t-8 border-green-500 relative">
                <span class="absolute top-0 left-0 text-6xl opacity-5 p-4 transform -rotate-6">❄️</span>
                <div class="flex items-center justify-center bg-green-100 py-6 relative overflow-hidden">
                    <span class="text-5xl mr-4 animate-spin-slow">❄️</span>
                    <h2 class="text-4xl md:text-5xl font-black text-center header-green festive-font drop-shadow-sm">Seniors (Y11-13): The Final Showdown! Choose Wisely!</h2>
                    <span class="text-5xl ml-4 animate-spin-slow">❄️</span>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 p-6 md:p-8">
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/15803d/ffffff?text=Zumba+%26+Just+Dance&font=roboto" alt="Dancing">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🧘‍♀️🔥</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>A: Festive Zumba & Just Dance "Battle Royale"</h3>
                            <p>The perfect exam stress relief! Start with 30 minutes of high-energy Christmas Zumba followed by a 30-minute high-energy tournament using the "Just Dance" game. It's time to move!</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/b91c1c/ffffff?text=Murder+Mystery&font=roboto" alt="Detective Magnifying Glass">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🕵️‍♂️🔍</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>B: Murder Mystery: "Who Killed Santa?"</h3>
                            <p>A Cluedo-style live-action game in the Library. Evidence is hidden around the room. You must interview "suspects" to solve the crime before time runs out! Can you crack the case?</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/c2410c/ffffff?text=Nordic+Knits&font=roboto" alt="Knitting">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🧣🧶</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>C: Nordic Knits & Crackers</h3>
                            <p>A "Hygge" style session. Learn simple arm-knitting to make scarves or finger knitting. Alternatively, make premium Christmas crackers (including the terrible jokes!).</p>
                        </div>
                    </div>
                    
                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/a855f7/ffffff?text=Upcycling+for+Charity&font=roboto" alt="Crafts">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">💖🎨</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>D: Upcycling for Charity</h3>
                            <p>Head to the Art Room to create festive decorations or cards that will be donated to a local care home. A great way to give back and spread joy this Christmas.</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/eab308/ffffff?text=Cookie+%26+Ceramic+Art&font=roboto" alt="Cookies">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🍪👩‍🍳</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>E: Cookie & Ceramic Art</h3>
                            <p>In Food Tech, decorate pre-baked cookies with intricate designs using piping skills. For a non-food alternative, decorate ceramic mugs or plates with porcelain pens that are baked to set.</p>
                        </div>
                    </div>

                    <div class="activity-card group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/3b82f6/ffffff?text=The+Chill+Zone&font=roboto" alt="Board Games">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">☕🎲</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>F: The "Chill" Zone / The Board Game Café</h3>
                            <p>A "phones-away" relaxation zone in the Sixth Form Centre. Enjoy a hot chocolate station and Lo-Fi Christmas beats while playing highly requested games like Uno, Bingo, and Scrabble.</p>
                        </div>
                    </div>
                    
                    <div class="activity-card lg:col-start-2 group">
                        <div class="activity-card-image-container">
                            <img src="https://placehold.co/600x400/6b7280/ffffff?text=The+Ad-Prentice&font=roboto" alt="Video Editing">
                            <span class="activity-icon-overlay group-hover:rotate-12 transition">🎬💡</span>
                        </div>
                        <div class="activity-card-content">
                            <h3>G: The "Ad-Prentice" Pitch</h3>
                            <p>Your team must script, storyboard, and then film a John Lewis-style tear-jerker Christmas advert in the IT rooms. You'll then present your final "Pitch" to the dragons (staff) at the end!</p>
                        </div>
                    </div>

                </div>
            </div>
        </section>



    <footer class="bg-gray-900 text-white py-12 text-center mt-8 border-t-8 border-red-600 relative overflow-hidden px-4">
        <div class="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCI+CjxnIGZpbGw9IiNmZmZmZmYiIGZpbGwtb3BhY2l0eT0iMC4xIj4KPGNpcmNsZSBjeD0iMyIgY3k9IjMiIHI9IjEiLz4KPGNpcmNsZSBjeD0iMTMiIGN5PSIxMyIgcj0iMSIvPgo8L2c+Cjwvc3ZnPg==')] opacity-50"></div>
        <div class="relative z-10 max-w-2xl mx-auto">
            <h3 class="text-4xl festive-font mb-6 text-red-300 font-bold">Don't Get Left Out in the Cold!</h3>
            <p class="text-xl mb-8 font-semibold text-gray-300">The best activities fill up fast. Lock in your choices now and prepare for glory.</p>
            
             <a href="https://forms.gle/BbWYuXKaQ9fud9F26" target="_blank" class="cta-button">
                CLICK HERE TO SIGN UP!
            </a>

            <p class="font-black text-3xl mt-12 text-green-400 tracking-wider uppercase">🎄 Let the best house win! 🎄</p>
        </div>
    </footer>

    <script>
        window.onload = function() {
            const ctx = document.getElementById('activityMixChart').getContext('2d');
            // Using festive colors for the chart
            const sportColor = '#1d4ed8'; // Deep Blue
            const craftColor = '#c2410c'; // Deep Orange/Red
            const logicColor = '#7e22ce'; // Deep Purple
            const chillColor = '#15803d'; // Deep Green

            const activityMixChart = new Chart(ctx, {
                type: 'bar',
                data: {
                    labels: ['Juniors (Y7-8)', 'Intermediates (Y9-10)', 'Seniors (Y11-13)'],
                    datasets: [
                        {
                            label: 'Sport & Active 🏃',
                            data: [2, 1, 1],
                            backgroundColor: sportColor,
                            borderColor: '#ffffff',
                            borderWidth: 2,
                        },
                        {
                            label: 'Creative & Craft 🎨',
                            data: [4, 4, 4],
                            backgroundColor: craftColor,
                            borderColor: '#ffffff',
                            borderWidth: 2,
                        },
                        {
                            label: 'Logic & Strategy 🧠',
                            data: [1, 2, 1],
                            backgroundColor: logicColor,
                            borderColor: '#ffffff',
                            borderWidth: 2,
                        },
                        {
                            label: 'Chill & Social ☕',
                            data: [0, 0, 1],
                            backgroundColor: chillColor,
                            borderColor: '#ffffff',
                            borderWidth: 2,
                        }
                    ]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    scales: {
                        x: {
                            stacked: true,
                            grid: { display: false },
                            ticks: { font: { weight: 'bold', size: 14 } }
                        },
                        y: {
                            stacked: true,
                            beginAtZero: true,
                            ticks: { precision: 0, font: { weight: 'bold' } }
                        }
                    },
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                padding: 20,
                                font: { size: 16, weight: 'bold' }
                            }
                        },
                        tooltip: {
                            backgroundColor: 'rgba(185, 28, 28, 0.95)', // Red tooltip background
                            titleFont: { size: 18, family: 'Mountains of Christmas' },
                            bodyFont: { size: 16, weight: 'bold' },
                            padding: 12,
                            cornerRadius: 8
                        }
                    }
                }
            });
        };
    </script>

