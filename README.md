<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman | Official Cricket Team</title>
    <style>
        :root {
            --main-green: #004d40;
            --accent-gold: #ffd700;
            --dark-blue: #0d47a1;
            --white: #ffffff;
            --bg-gray: #f0f2f5;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-gray);
            margin: 0;
            padding: 10px;
            color: #222;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            background: var(--white);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }

        /* Hero Header */
        header {
            background: linear-gradient(rgba(0, 77, 64, 0.9), rgba(0, 77, 64, 0.9)), url('team_bg.jpg'); /* Optional background image */
            background-size: cover;
            color: var(--white);
            text-align: center;
            padding: 50px 20px;
        }

        header img { width: 110px; border-radius: 50%; border: 4px solid var(--accent-gold); margin-bottom: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.3); }
        header h1 { margin: 0; font-size: 2.2rem; text-transform: uppercase; letter-spacing: 2px; }
        header p { margin: 5px 0 0; font-weight: 300; font-size: 1.1rem; opacity: 0.9; }

        /* Match Announcement Banner */
        .match-alert {
            background: var(--dark-blue);
            color: white;
            padding: 25px;
            text-align: center;
            border-bottom: 5px solid var(--accent-gold);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: inset 0 0 0 rgba(255, 215, 0, 0); }
            50% { box-shadow: inset 0 0 20px rgba(255, 215, 0, 0.3); }
            100% { box-shadow: inset 0 0 0 rgba(255, 215, 0, 0); }
        }

        .match-alert h2 { color: var(--accent-gold); border: none; margin: 0; font-size: 1.8rem; }
        .match-vs { font-size: 1.4rem; font-weight: bold; display: block; margin: 10px 0; }
        .match-meta { font-style: italic; opacity: 0.8; }

        /* Stats Row */
        .stats-bar {
            display: flex;
            justify-content: space-around;
            background: #f8f9fa;
            padding: 20px;
            border-bottom: 1px solid #ddd;
        }
        .stat-item { text-align: center; }
        .stat-number { display: block; font-size: 1.5rem; font-weight: bold; color: var(--main-green); }
        .stat-label { font-size: 0.8rem; text-transform: uppercase; color: #777; }

        /* Sections */
        section { padding: 30px 20px; }
        h2 {
            color: var(--main-green);
            border-left: 6px solid var(--main-green);
            padding-left: 15px;
            margin-bottom: 25px;
            font-size: 1.5rem;
        }

        /* Achievement Layout */
        .achievement-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .achievement-card {
            border: 1px solid #eee;
            border-radius: 12px;
            overflow: hidden;
            text-align: center;
            transition: 0.3s;
        }
        .achievement-card:hover { transform: scale(1.02); }
        .achievement-card img { width: 100%; height: 200px; object-fit: cover; }
        .achievement-info { padding: 15px; }

        /* Squad Grid */
        .squad-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
            gap: 15px;
        }
        .player-card {
            background: #fff;
            border: 1px solid #eee;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            transition: 0.3s;
        }
        .player-card:hover { border-color: var(--main-green); box-shadow: 0 5px 15px rgba(0,0,0,0.05); }
        .player-card h3 { margin: 0; font-size: 1.1rem; color: var(--main-green); }
        .player-card p { margin: 5px 0 0; font-size: 0.85rem; color: #666; font-weight: bold; }

        /* Highlight Cards */
        .captain-card { background: var(--main-green); color: white; border: none; }
        .captain-card h3, .captain-card p { color: white; }
        .management-card { border-top: 4px solid var(--accent-gold); }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 30px;
            font-size: 0.9rem;
        }
        .social-links a { color: var(--accent-gold); margin: 0 10px; text-decoration: none; font-weight: bold; }

        @media (max-width: 600px) {
            .squad-grid { grid-template-columns: repeat(2, 1fr); }
            header h1 { font-size: 1.6rem; }
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

        <div class="match-alert">
        <h2>🔥 THE GRAND FINAL 🔥</h2>
        <span class="match-vs">DOCTOR 11 PANJMAN vs QADRA</span>
        <div class="match-meta">
            <strong>📅 Date:</strong> 27 March 2026 (Friday) <br>
            <strong>⏰ Time:</strong> 2:30 PM <br>
            <strong>📍 Venue:</strong> Qadra Cricket Ground
        </div>
    </div>
    

    <div class="stats-bar">
        <div class="stat-item">
            <span class="stat-number">1</span>
            <span class="stat-label">Major Title</span>
        </div>
        <div class="stat-item">
            <span class="stat-number">4</span>
            <span class="stat-label">Finals Played</span>
        </div>
        <div class="stat-item">
            <span class="stat-number">18</span>
            <span class="stat-label">Elite Players</span>
        </div>
    </div>

    <section>
        <h2>🏆 CHAMPIONSHIPS & GLORY</h2>
        <div class="achievement-grid">
            <div class="achievement-card" style="border: 2px solid var(--accent-gold);">
                <img src="trophy1.png" alt="Boko Tournament">
                <div class="achievement-info">
                    <h3 style="color: #b8860b;">BOKO TOURNAMENT CHAMPIONS</h3>
                    <p>Dominant performance throughout the series.</p>
                </div>
            </div>
            <div class="achievement-card">
                <img src="swabi_cup.png" alt="Runners Up">
                <div class="achievement-info">
                    <h3>ELITE RUNNERS UP</h3>
                    <p>Swabi Cup • Anbar Cup • Panjman Tournament</p>
                </div>
            </div>
        </div>
    </section>

    <section>
        <h2>🏏 OFFICIAL SQUAD 2026</h2>
        <div class="squad-grid">
            <div class="player-card captain-card"><h3>Muneer Iqbal</h3><p>Captain / Batsman</p></div>
            <div class="player-card"><h3>Muhammad Amir</h3><p>Premium All-Rounder</p></div>
            <div class="player-card"><h3>Huzaifa Ahmad</h3><p>Player</p></div>
            <div class="player-card"><h3>Muhammad Hasnain</h3><p>Player</p></div>
            <div class="player-card"><h3>Haris Iqbal</h3><p>Player</p></div>
            <div class="player-card"><h3>Behram Khan</h3><p>Player</p></div>
            <div class="player-card"><h3>Shakeel Ahmad</h3><p>Player</p></div>
            <div class="player-card"><h3>Waqar Khan</h3><p>Player</p></div>
            <div class="player-card"><h3>Saqib Shah</h3><p>Player</p></div>
            <div class="player-card"><h3>Abubakar</h3><p>Player</p></div>
            <div class="player-card"><h3>Shehbaz</h3><p>Player</p></div>
            <div class="player-card"><h3>Azan Khan</h3><p>Player</p></div>
            <div class="player-card"><h3>Baser Khan</h3><p>Player</p></div>
            <div class="player-card"><h3>Sohail Ahmad</h3><p>Player</p></div>
            <div class="player-card"><h3>Osama Khan</h3><p>Player</p></div>
            <div class="player-card"><h3>Ihtisham Khan</h3><p>Player</p></div>
        </div>
    </section>

    <section>
        <h2>👔 TEAM MANAGEMENT</h2>
        <div class="squad-grid">
            <div class="player-card management-card" style="background: #fffdf0;">
                <h3 style="color: #d4af37;">Dr. Tauseef Ahmed</h3>
                <p>Owner & Chairman</p>
            </div>
            <div class="player-card management-card">
                <h3>Sameer Khan</h3>
                <p>Media Director</p>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2026 Doctor 11 Panjman Cricket Club</p>    <section id="contact">
        <h2>📞 CONTACT US</h2>
        <div class="contact-container">
            <div class="contact-info">
                <div class="contact-card">
                    <p><strong>Official Inquiries:</strong></p>
                    <p>Contact Media Director Sameer Khan or Team Owner Dr. Tauseef Ahmed for match invites or sponsorships.</p>
                </div>
                <div class="contact-method">
                    <span>📍 Venue:</span> Panjman, Swabi, KPK
                </div>
                <div class="contact-method">
                    <span>✉️ Email:</span> asameerkhan352@gmail.com
                </div>
                <div class="contact-method">
                    <span>💬 WhatsApp:</span> 03429212247
                </div>
            </div>

            <form class="contact-form">
                <input type="text" placeholder="Your name " required>
                <input type="email" placeholder="Yout Email" required>
                <textarea placeholder="Your Message (e.g., Match Invite or Feedback)" rows="4" required></textarea>
                <button type="submit">SEND MESSAGE</button>
            </form>
        </div>
    </section>
    
        <div class="social-links">
            <a href="#">Facebook</a> | <a href="#">WhatsApp</a> | <a href="#">SH Studio</a>
        </div>
    </footer>

</div>

</body>
</html>
