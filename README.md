<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman | Official Website</title>
    <style>
        :root {
            --main-green: #004d40;
            --accent-gold: #ffd700;
            --light-bg: #f4f7f6;
            --white: #ffffff;
            --danger: #d32f2f;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: var(--light-bg);
            margin: 0;
            padding: 15px;
            color: #333;
        }

        .container {
            max-width: 1000px;
            margin: auto;
            background: var(--white);
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
        }

        /* Header */
        header {
            background-color: var(--main-green);
            color: var(--white);
            text-align: center;
            padding: 40px 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        header img { width: 90px; border-radius: 50%; border: 3px solid var(--white); margin-bottom: 10px; }
        header h1 { margin: 5px 0; font-size: 1.8rem; }

        /* Announcement Banner */
        .announcement-banner {
            background: linear-gradient(45deg, #1a237e, #0d47a1);
            color: white;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 4px solid var(--accent-gold);
        }

        .announcement-banner h2 { 
            color: var(--accent-gold); 
            border: none; 
            margin: 0; 
            padding: 0;
            font-size: 1.5rem;
        }

        .match-details {
            font-size: 1.2rem;
            font-weight: bold;
            margin: 10px 0;
            display: block;
        }

        /* Section Headings */
        h2 {
            color: var(--main-green);
            border-left: 5px solid var(--main-green);
            padding-left: 15px;
            margin: 40px 0 20px 0;
            font-size: 1.3rem;
            text-transform: uppercase;
        }

        /* Grids */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(170px, 1fr));
            gap: 15px;
        }

        .card {
            background: #fff;
            border: 1px solid #eee;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.03);
        }

        /* Achievement Styles */
        .achievement-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .achievement-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 6px;
            margin-bottom: 10px;
        }

        .champion-tag {
            background: #fff8e1;
            border: 2px solid var(--accent-gold);
        }

        /* Special Roles */
        .captain-card { background-color: var(--main-green); color: white; }
        .captain-card h3, .captain-card p { color: white; }
        .owner-card { border: 2px solid var(--accent-gold); }

        @media (max-width: 600px) {
            .grid { grid-template-columns: repeat(2, 1fr); }
        }
    </style>
</head>
<body>

<div class="container">
    
    <header>
        <img src="logo.png" alt="Doctor 11 Logo">
        <h1>DOCTOR 11 PANJMAN</h1>
        <p>Official Cricket Team | Panjman, Swabi</p>
    </header>

    <section class="announcement-banner">
        <h2>📢 FINAL MATCH ANNOUNCEMENT</h2>
        <span class="match-details">DOCTOR 11 PANJMAN vs QADRA</span>
        <p>Prepare for the ultimate showdown! Support your team as we fight for the championship title.</p>
    </section>

    <section>
        <h2>🏆 ACHIEVEMENTS & GALLERY</h2>
        <div class="achievement-grid">
            <div class="card achievement-card champion-tag">
                <img src="trophy1.png" alt="Boko Tournament">
                <h3>CHAMPIONS 🏆</h3>
                <p>Boko Tournament Winners</p>
            </div>
            <div class="card achievement-card">
                <img src="swabi_cup.png" alt="Runners Up">
                <h3>RUNNERS UP</h3>
                <p>Swabi Cup, Anbar Cup & Panjman Tournament</p>
            </div>
        </div>
    </section>

    <section>
        <h2>🏏 2026 OFFICIAL SQUAD</h2>
        <div class="grid">
            <div class="card captain-card"><h3>Muneer Iqbal</h3><p>Captain</p></div>
            <div class="card"><h3>Muhammad Amir</h3><p>Premium All-Rounder</p></div>
            <div class="card"><h3>Huzaifa Ahmad</h3><p>Player</p></div>
            <div class="card"><h3>Muhammad Hasnain</h3><p>Player</p></div>
            <div class="card"><h3>Haris Iqbal</h3><p>Player</p></div>
            <div class="card"><h3>Behram Khan</h3><p>Player</p></div>
            <div class="card"><h3>Shakeel Ahmad</h3><p>Player</p></div>
            <div class="card"><h3>Waqar Khan</h3><p>Player</p></div>
            <div class="card"><h3>Saqib Shah</h3><p>Player</p></div>
            <div class="card"><h3>Abubakar</h3><p>Player</p></div>
            <div class="card"><h3>Shehbaz</h3><p>Player</p></div>
            <div class="card"><h3>Azan Khan</h3><p>Player</p></div>
            <div class="card"><h3>Baser Khan</h3><p>Player</p></div>
            <div class="card"><h3>Sohail Ahmad</h3><p>Player</p></div>
            <div class="card"><h3>Osama Khan</h3><p>Player</p></div>
            <div class="card"><h3>Ihtisham Khan</h3><p>Player</p></div>
        </div>
    </section>

    <section>
        <h2>👔 MANAGEMENT</h2>
        <div class="grid">
            <div class="card owner-card">
                <h3>Dr. Tauseef Ahmed</h3>
                <p>Team Owner & Chairman</p>
            </div>
            <div class="card">
                <h3>Samir Khan</h3>
                <p>Media Director</p>
            </div>
        </div>
    </section>

</div>

</body>
</html>
