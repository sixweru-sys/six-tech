<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>SIX TECH | Build Beyond Limits</title>

    <meta name="description"
          content="SIX TECH — Gaming, AI, cybersecurity and agricultural technology. Building technology beyond limits.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background: #050505;
            color: white;
            line-height: 1.6;
        }

        /* NAVBAR */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 18px 7%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: rgba(5,5,5,0.85);
            backdrop-filter: blur(10px);
            z-index: 1000;
            border-bottom: 1px solid #1a1a1a;
        }

        .logo {
            font-size: 25px;
            font-weight: 900;
            letter-spacing: 3px;
        }

        .logo span {
            color: #00ff88;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            font-size: 14px;
            transition: 0.3s;
        }

        nav a:hover {
            color: #00ff88;
        }

        /* HERO */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 100px 20px 40px;
            background:
                radial-gradient(circle at center, #0b2b20 0%, #050505 45%);
        }

        .hero h1 {
            font-size: clamp(55px, 13vw, 130px);
            font-weight: 900;
            letter-spacing: -5px;
            line-height: 0.9;
        }

        .hero h1 span {
            color: #00ff88;
            text-shadow: 0 0 30px rgba(0,255,136,0.35);
        }

        .hero p {
            margin: 30px auto;
            max-width: 650px;
            color: #aaa;
            font-size: 18px;
        }

        .btn {
            display: inline-block;
            padding: 14px 28px;
            background: #00ff88;
            color: #000;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            transition: 0.3s;
        }

        .btn:hover {
            transform: translateY(-4px);
            box-shadow: 0 0 30px rgba(0,255,136,0.35);
        }

        /* SECTIONS */
        section {
            padding: 100px 8%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 60px;
        }

        .section-title h2 {
            font-size: 42px;
        }

        .section-title span {
            color: #00ff88;
        }

        .section-title p {
            color: #888;
            margin-top: 10px;
        }

        /* CARDS */
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 22px;
        }

        .card {
            background: #0c0c0c;
            border: 1px solid #1d1d1d;
            padding: 30px;
            border-radius: 12px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            border-color: #00ff88;
            box-shadow: 0 0 25px rgba(0,255,136,0.08);
        }

        .card .icon {
            font-size: 38px;
            margin-bottom: 15px;
        }

        .card h3 {
            margin-bottom: 10px;
            font-size: 22px;
        }

        .card p {
            color: #999;
            font-size: 15px;
        }

        /* ABOUT */
        .about {
            max-width: 900px;
            margin: auto;
            text-align: center;
        }

        .about p {
            color: #aaa;
            font-size: 18px;
        }

        /* VISION */
        .vision {
            text-align: center;
            background: #080808;
        }

        .vision h2 {
            font-size: clamp(35px, 6vw, 65px);
        }

        .vision h2 span {
            color: #00ff88;
        }

        /* FOOTER */
        footer {
            padding: 35px 20px;
            text-align: center;
            border-top: 1px solid #1a1a1a;
            color: #777;
        }

        footer strong {
            color: white;
        }

        /* MOBILE */
        @media (max-width: 600px) {
            nav {
                padding: 16px 5%;
            }

            nav a {
                margin-left: 10px;
                font-size: 12px;
            }

            .hero h1 {
                letter-spacing: -3px;
            }

            section {
                padding: 75px 6%;
            }
        }
    </style>
</head>

<body>

    <!-- NAVIGATION -->
    <nav>
        <div class="logo">SIX<span>TECH</span></div>

        <div>
            <a href="#home">Home</a>
            <a href="#tech">Tech</a>
            <a href="#about">About</a>
        </div>
    </nav>


    <!-- HERO -->
    <section class="hero" id="home">
        <div>
            <h1>BUILD<br><span>BEYOND</span></h1>

            <p>
                SIX TECH is a technology-driven vision focused on gaming,
                artificial intelligence, cybersecurity and agricultural
                innovation.
            </p>

            <a href="#tech" class="btn">EXPLORE SIX TECH</a>
        </div>
    </section>


    <!-- TECHNOLOGY -->
    <section id="tech">

        <div class="section-title">
            <h2>OUR <span>TECH</span></h2>
            <p>Where creativity meets engineering.</p>
        </div>

        <div class="cards">

            <div class="card">
                <div class="icon">🎮</div>
                <h3>Gaming</h3>
                <p>
                    Building immersive gaming experiences,
                    interactive worlds and next-generation gameplay.
                </p>
            </div>

            <div class="card">
                <div class="icon">🤖</div>
                <h3>AI & ML</h3>
                <p>
                    Exploring artificial intelligence and machine
                    learning to create smarter technology.
                </p>
            </div>

            <div class="card">
                <div class="icon">🛡️</div>
                <h3>Cybersecurity</h3>
                <p>
                    Developing secure systems and exploring the
                    technology behind digital protection.
                </p>
            </div>

            <div class="card">
                <div class="icon">🌱</div>
                <h3>AgriTech</h3>
                <p>
                    Using technology and AI to help solve agricultural
                    challenges and support future farming.
                </p>
            </div>

        </div>
    </section>


    <!-- ABOUT -->
    <section id="about">

        <div class="about">

            <div class="section-title">
                <h2>ABOUT <span>SIX TECH</span></h2>
            </div>

            <p>
                SIX TECH is built around one simple idea:
                technology should not only solve today's problems —
                it should create possibilities for tomorrow.
            </p>

            <br>

            <p>
                From gaming and artificial intelligence to cybersecurity
                and agricultural innovation, SIX TECH explores the
                intersection between technology, creativity and real-world
                impact.
            </p>

        </div>

    </section>


    <!-- VISION -->
    <section class="vision">

        <h2>
            THE FUTURE IS<br>
            <span>BUILT.</span>
        </h2>

        <p style="color:#888; margin-top:20px;">
            SIX TECH — Build Beyond Limits.
        </p>

    </section>


    <!-- FOOTER -->
    <footer>
        © 2026 <strong>SIX TECH</strong>. All rights reserved.
    </footer>

</body>
</html>
