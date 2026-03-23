<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman | Official</title>
    <style>
        :root { --primary: #075e54; --secondary: #128c7e; --accent: #25d366; --light: #f0f2f5; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: var(--light); color: #1c1e21; scroll-behavior: smooth; text-align: center; }
        header { background: linear-gradient(135deg, var(--primary), var(--secondary)); color: white; padding: 60px 20px; text-align: center; }
        .team-logo { width: 120px; height: 120px; border-radius: 50%; border: 4px solid white; background: white; margin: 0 auto 15px; display: block; object-fit: cover; }
        nav { background: #054d44; padding: 15px; position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; }
        nav a { color: white; text-decoration: none; font-weight: bold; font-size: 13px; text-transform: uppercase; padding: 5px 10px; border-radius: 5px; transition: 0.3s; }
        nav a:hover { background: var(--accent); color: var(--primary); }
        .container { max-width: 1000px; margin: 30px auto; padding: 25px; background: white; border-radius: 15px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); text-align: left; }
        h2 { color: var(--primary); border-left: 5px solid var(--accent); padding-left: 15px; margin-bottom: 20px; text-transform: uppercase; letter-spacing: 1px; margin-top: 0; }
        .info-box { background: #e9f5f2; padding: 25px; border-radius: 12px; border-left: 6px solid var(--accent); margin-bottom: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.05); }
        .detail-box { background: white; padding: 15px; border-radius: 8px; border: 1px dashed var(--primary); margin-top: 15px; }

        /* Gallery Layout */
        .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .gallery-card { border: 1px solid #ddd; border-radius: 12px; overflow: hidden; background: white; box-shadow: 0 4px 8px rgba(0,0,0,0.1); text-align: center; }
        .gallery-card img { width: 100%; height: 250px; object-fit: cover; background: #eee; }
        .gallery-caption { padding: 15px; text-align: center; color: var(--primary); font-weight: bold; border-top: 1px solid #eee; }

        /* Squad Layout */
        .player-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 12px; }
        .player-card { background: #f9fbf9; padding: 15px; border-radius: 10px; border: 1px solid #e0eadd; text-align: center; transition: 0.3s; }
        .player-card:hover { border-color: var(--accent); transform: translateY(-3px); }
        .player-name { font-weight: bold; color: var(--primary); display: block; font-size: 1.1em; }
        .player-role { font-size: 0.8em; color: #666; text-transform: uppercase; }
        .captain { background: var(--primary) !important; color: white !important; }
        .captain .player-name { color: white !important; }

        .footer { padding: 50px; text-align: center; color: #888; border-top: 1px solid #eee; margin-top: 50px; }
        .designer { color: var(--primary); font-weight: bold; }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Doctor 11 Logo" class="team-logo">
    <h1>DOCTOR 11 PANJMAN</h1>
    <p>Official Cricket Team | Panjman, Swabi</p>
</header>

<nav>
    <a href="#gallery">Achievements</a>
    <a href="#squad">Squad</a>
    <a href="#news">Announcements</a>
    <a href="#about">Management</a>
</nav>

<div class="container" id="gallery">
    <h2>🏆 Achievements & Gallery</h2>
    <div class="gallery-grid">
        <div class="gallery-card">
            <img src="https://i.ibb.co/XkyYg1n/trophy-fix.png" alt="Match Victory">
            <div class="gallery-caption">Tournament Winners 2025</div>
        </div>
        
        <div class="gallery-card">
            <img src="https://via.placeholder.com/400x300?text=Finalist+Trophy" alt="Runner Up">
            <div class="gallery-caption">Finalists - Swabi Cup</div>
        </div>
    </div>
</div>

<div class="container" id="news">
    <h2>📢 Latest Announcements</h2>
    <div class="info-box">
        <h3 style="color: #075e54; margin-top: 0;">🏆 Doctor 11 Enters PSL 2026!</h3>
        <p>We are thrilled to announce that <b>Doctor 11 Panjman</b> will be officially participating in the <b>Panjman Super League (PSL) 2026</b>!</p>
        <p>As a proud sponsor for the <b>Third Edition</b> of the tournament, Doctor 11 Panjman is committed to supporting local talent and fostering the spirit of sportsmanship within our community. Get ready for an electrifying season of cricket!</p>
        <div class="detail-box">
            <h4 style="margin: 0 0 10px 0; color: #075e54;">Tournament Details:</h4>
            <ul style="list-style: none; padding: 0; margin: 0; color: #333;">
                <li>📍 <b>Event:</b> Panjman Super League 2026</li>
                <li>🏅 <b>Edition:</b> 3rd Edition</li>
                <li>🤝 <b>Sponsor/Participant:</b> Doctor 11 Panjman</li>
            </ul>
        </div>
        <p style="margin-top: 15px; font-style: italic; color: #555;">Stay tuned for team updates, match schedules, and behind-the-scenes coverage as we gear up for the first ball. Let the games begin!</p>
    </div>
</div>

<div class="container" id="squad">
    <h2>🏏 2026 Official Squad (18 Players)</h2>
    <div class="player-grid">
        <div class="player-card captain"><span class="player-name">Muneer Iqbal</span><span class="player-role">Captain</span></div>
        <div class="player-card"><span class="player-name">Muhammad Amir</span><span class="player-role">All-Rounder</span></div>
        <div class="player-card"><span class="player-name">Huzaifa Ahmad</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Muhammad Hasnain</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Haris Iqbal</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Behram Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Shakeel Ahmad</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Raheel Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Waqar Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Saqib Shah</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Munsif Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Abubakar</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Shehbaz</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Azan Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Baser Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Sohail Ahmad</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Osama Khan</span><span class="player-role">Player</span></div>
        <div class="player-card"><span class="player-name">Ihtisham Khan</span><span class="player-role">Player</span></div>
    </div>
</div>

<div class="container" id="about">
    <h2>🤝 Team Management</h2>
    <div style="background: #fff; padding: 20px; border-radius: 10px; border: 1px solid #ddd;">
        <p><strong>Team Owner:</strong> Dr. Tausif Ahmad</p>
        <p><strong>Home Location:</strong> Panjman, Swabi, KPK</p>
        <p>Our goal is to promote youth talent and represent Panjman with excellence in every match.</p>
    </div>
</div>

<div class="footer">
    <p>&copy; 2026 Doctor 11 Panjman Cricket Team</p>
    <p>Website Built by <span class="designer">Sameer Khan</span></p>
</div>

</body>
</html>
