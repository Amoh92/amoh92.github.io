<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIC CHEQUE | Professional Storytelling</title>
    <!-- Classic Font Pairing: Playfair Display for headings, Lora for body, and Montserrat for accents -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lora:ital,wght@0,400;0,700;1,400&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #1a1a1a;
            --accent-color: #c5a059;
            --text-color: #333333;
            --bg-color: #fdfdfb;
            --font-heading: 'Playfair Display', serif;
            --font-body: 'Lora', serif;
            --font-accent: 'Montserrat', sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: var(--font-body);
            line-height: 1.8;
            -webkit-font-smoothing: antialiased;
        }

        header {
            padding: 4rem 1rem 2rem;
            text-align: center;
            border-bottom: 1px solid #eee;
        }

        .logo-container img {
            max-width: 400px;
            height: auto;
            margin-bottom: 2rem;
        }

        h1.site-title {
            font-family: var(--font-heading);
            font-size: 3.5rem;
            font-weight: 700;
            color: var(--primary-color);
            letter-spacing: -1px;
            margin-bottom: 0.5rem;
        }

        .site-tagline {
            font-family: var(--font-accent);
            text-transform: uppercase;
            font-size: 0.8rem;
            letter-spacing: 4px;
            color: var(--accent-color);
            font-weight: 600;
        }

        nav {
            margin-top: 2rem;
            border-top: 1px double #ccc;
            border-bottom: 1px double #ccc;
            padding: 1rem 0;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2.5rem;
        }

        nav a {
            text-decoration: none;
            color: var(--primary-color);
            font-family: var(--font-accent);
            font-size: 0.75rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: var(--accent-color);
        }

        main {
            max-width: 800px;
            margin: 4rem auto;
            padding: 0 1.5rem;
        }

        .post {
            margin-bottom: 8rem;
        }

        .post-meta {
            font-family: var(--font-accent);
            font-size: 0.7rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #888;
            margin-bottom: 1rem;
        }

        .post-title {
            font-family: var(--font-heading);
            font-size: 2.5rem;
            line-height: 1.2;
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }

        .post-content {
            font-size: 1.15rem;
            text-align: justify;
        }

        .post-content p {
            margin-bottom: 1.5rem;
        }

        .post-content p::first-letter {
            float: left;
            font-size: 4rem;
            line-height: 1;
            font-weight: bold;
            margin-right: 10px;
            font-family: var(--font-heading);
            color: var(--primary-color);
        }

        /* Media styling */
        .post-media {
            margin: 2.5rem 0;
            text-align: center;
        }

        .post-media img, .post-media video {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
        }

        .media-caption {
            font-family: var(--font-accent);
            font-size: 0.75rem;
            color: #888;
            margin-top: 0.8rem;
            font-style: italic;
        }

        .read-more {
            display: inline-block;
            margin-top: 1rem;
            font-family: var(--font-accent);
            font-size: 0.8rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--accent-color);
            text-decoration: none;
            font-weight: 600;
            border-bottom: 1px solid transparent;
            transition: border-color 0.3s;
        }

        .read-more:hover {
            border-bottom-color: var(--accent-color);
        }

        .subscription-section {
            background-color: #f9f9f7;
            padding: 4rem 2rem;
            text-align: center;
            border-top: 1px solid #eee;
            margin-top: 6rem;
        }

        .subscription-section h2 {
            font-family: var(--font-heading);
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .subscription-section p {
            font-family: var(--font-body);
            font-style: italic;
            color: #666;
            margin-bottom: 2rem;
        }

        .subscribe-form {
            display: flex;
            justify-content: center;
            gap: 10px;
            max-width: 450px;
            margin: 0 auto;
        }

        .subscribe-form input {
            flex: 1;
            padding: 0.8rem 1rem;
            border: 1px solid #ddd;
            font-family: var(--font-body);
            outline: none;
        }

        .subscribe-form button {
            padding: 0.8rem 2rem;
            background-color: var(--primary-color);
            color: white;
            border: none;
            font-family: var(--font-accent);
            text-transform: uppercase;
            font-size: 0.75rem;
            letter-spacing: 2px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .subscribe-form button:hover {
            background-color: var(--accent-color);
        }

        footer {
            padding: 4rem 1rem;
            text-align: center;
            background-color: var(--primary-color);
            color: #fff;
        }

        .footer-tagline {
            font-family: var(--font-heading);
            font-size: 1.8rem;
            font-style: italic;
            letter-spacing: 1px;
            margin-bottom: 1rem;
            color: var(--accent-color);
        }

        .copyright {
            font-family: var(--font-accent);
            font-size: 0.65rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: #666;
        }

        @media (max-width: 600px) {
            h1.site-title { font-size: 2.5rem; }
            nav ul { flex-direction: column; gap: 1rem; }
            .subscribe-form { flex-direction: column; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo-container">
            <img src="./mic_cheque_logo.png" alt="MIC CHEQUE Logo">
        </div>
        <h1 class="site-title">MIC CHEQUE</h1>
        <p class="site-tagline">The Art of the Untold Story</p>
        
        <nav>
            <ul>
                <li><a href="#">Chronicles</a></li>
                <li><a href="#">The Vault</a></li>
                <li><a href="#">About the Mic</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Story 1: Nairobi's Tech Hustle -->
        <article class="post">
            <div class="post-meta">April 16, 2026 — Innovation</div>
            <h2 class="post-title">Nairobi’s Tech Hustle: From Small Rooms to Global Impact</h2>
            <div class="post-content">
                <p>In the modern heartbeat of Kenya, Nairobi has grown into one of Africa’s most influential innovation centers. What once looked like a city focused mainly on trade and administration is now home to fast-growing startups, digital creators, and software engineers shaping solutions for global markets.</p>
                <p>This transformation did not happen overnight. It started in small internet cafés, university dorm rooms, and cramped rented apartments where young people experimented with code, design, and online business ideas. Many had no formal funding, no advanced equipment, and limited mentorship. What they had was curiosity and persistence.</p>
                
                <!-- First Story Image 1 (Middle) -->
                <div class="post-media">
                    <img src="./tech_story_1.jpg" alt="Nairobi Tech Innovation">
                    <p class="media-caption">The early days of Nairobi's tech revolution.</p>
                </div>

                <p>Today, those early experiments have evolved into real companies. Fintech platforms are now handling payments across East Africa. Logistics startups are improving delivery systems for small businesses. Health-tech tools are helping patients in remote areas access medical advice without traveling long distances.</p>
                <p>A major driver of this growth is mobile technology. With widespread smartphone adoption and mobile money systems, developers have been able to build services that reach millions instantly. This has made Kenya one of the most advanced mobile-first economies in the world.</p>

                <!-- First Story Image 2 (Middle) -->
                <div class="post-media">
                    <img src="./tech_story_2.jpg" alt="Mobile Technology in Kenya">
                    <p class="media-caption">Mobile connectivity driving local solutions.</p>
                </div>

                <p>However, the journey is still far from easy. Many startups struggle with funding gaps, especially at early stages. Others face infrastructure challenges such as inconsistent internet in certain areas or high operational costs. Competition is also intense, with hundreds of new ideas launched every year.</p>
                
                <!-- First Story Image 3 (Middle) -->
                <div class="post-media">
                    <img src="./tech_story_3.jpg" alt="Startups in Nairobi">
                    <p class="media-caption">Challenges and resilience in the startup ecosystem.</p>
                </div>

                <p>Despite these challenges, the energy remains strong. Incubators and innovation hubs continue to support young talent. Universities are producing more tech graduates than ever before. International investors are increasingly paying attention to Nairobi as a serious tech destination.</p>
                <p>What stands out most is the mindset shift. Young innovators are no longer waiting for jobs—they are building them. They are creating platforms that solve local problems while also competing globally. Nairobi is no longer just participating in the digital economy; it is actively shaping it.</p>
                
                <!-- First Story Image 4 (End) -->
                <div class="post-media">
                    <img src="./tech_story_4.jpg" alt="Future of Nairobi Tech">
                    <p class="media-caption">Nairobi: Shaping the global digital economy.</p>
                </div>
            </div>
            <a href="#" class="read-more">Continue Reading</a>
        </article>

        <!-- Story 2: Nairobi Matatu Culture -->
        <article class="post">
            <div class="post-meta">April 16, 2026 — Culture</div>
            <h2 class="post-title">Nairobi Matatu Culture: The Moving Art That Never Sleeps</h2>
            <div class="post-content">
                <p>In the fast-moving urban life of Kenya, few things define daily experience more vividly than the matatu system. These minibuses are not just a transport network—they are a living cultural phenomenon that blends art, music, economy, and street identity into one moving ecosystem.</p>
                <p>Every matatu begins its identity long before it hits the road. Artists spend hours designing graffiti-style exteriors, often inspired by pop culture, local heroes, music icons, or social themes. Inside, the transformation continues with LED lights, high-powered sound systems, custom seats, and unique branding that makes each vehicle distinct.</p>
                
                <!-- Second Story Image 1 (Interval) -->
                <div class="post-media">
                    <img src="./matatu_story_1.jpg" alt="Matatu Graffiti Art">
                    <p class="media-caption">Vibrant graffiti art on a Nairobi matatu.</p>
                </div>

                <p>For passengers, stepping into a matatu is an experience of its own. Music fills the air, sometimes so loud it becomes part of the ride itself. Conductors call out destinations in fast, rhythmic chants that feel like performance poetry. Young people often see matatus as more than transport—they are social spaces where conversations, trends, and culture are exchanged.</p>
                
                <!-- Second Story Image 2 (Interval) -->
                <div class="post-media">
                    <img src="./matatu_story_2.jpg" alt="Matatu Interior Experience">
                    <p class="media-caption">The unique social atmosphere inside a matatu.</p>
                </div>

                <p>Behind this creativity is a crucial transport system that keeps Nairobi moving. Every day, millions of people rely on matatus to travel to work, school, markets, and hospitals. Without them, the city’s mobility would collapse under pressure.</p>
                
                <!-- Second Story Image 3 (Interval) -->
                <div class="post-media">
                    <img src="./matatu_story_3.jpg" alt="Nairobi Public Transport">
                    <p class="media-caption">Keeping the city of Nairobi in motion.</p>
                </div>

                <p>But the system operates in a complex environment. Traffic congestion in Nairobi is among the most challenging in the region, often causing long delays during peak hours. Route competition between operators can be intense, with each sacco trying to dominate popular routes. Regulations also evolve frequently, affecting pricing, design, and operation standards.</p>
                
                <!-- Second Story Image 4 (Interval) -->
                <div class="post-media">
                    <img src="./matatu_story_4.jpg" alt="Matatu Route Competition">
                    <p class="media-caption">The hustle of Nairobi's public transport routes.</p>
                </div>

                <p>Despite these issues, matatu culture continues to evolve rather than disappear. New designs appear regularly, each trying to push boundaries in creativity and style. The culture has even influenced fashion, music, and digital content creation, becoming a symbol of urban expression.</p>
                <p>For outsiders, it may look chaotic. For locals, it is structured chaos with rhythm and identity. It represents survival, creativity, and movement all at once. Matatus are not just part of Nairobi—they are Nairobi in motion.</p>
                
                <!-- Second Story Video (End) -->
                <div class="post-media">
                    <video controls>
                        <source src="./matatu_culture_video.mp4" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                    <p class="media-caption">Experience the rhythm: Nairobi Matatu Culture in motion.</p>
                </div>
            </div>
            <a href="#" class="read-more">Continue Reading</a>
        </article>
    </main>

    <section class="subscription-section">
        <h2>Join the Inner Circle</h2>
        <p>Receive our weekly chronicles directly in your inbox.</p>
        <form class="subscribe-form" onsubmit="event.preventDefault(); alert('Thank you for subscribing to MIC CHEQUE!');">
            <input type="email" placeholder="Your email address" required>
            <button type="submit">Subscribe</button>
        </form>
    </section>

    <footer>
        <p class="footer-tagline">NIKO KADI JE WEWE?</p>
        <p class="copyright">&copy; 2026 MIC CHEQUE. ALL RIGHTS RESERVED.</p>
    </footer>

</body>
</html>
