<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman | Official</title>
    <style>
        :root { --primary: #075e54; --secondary: #128c7e; --accent: #25d366; --light: #f0f2f5; }
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: var(--light); color: #1c1e21; scroll-behavior: smooth; text-align: center; }
        .hero {
    background: linear-gradient(135deg, #064e3b 0%, #065f46 100%);
    color: white;
    padding: 60px 20px;
    text-align: center;
    width: 100%;             /* Add this line */
    box-sizing: border-box;  /* Add this line */
    margin: 0;               /* Add this line */
}
        .team-logo { width: 120px; height: 120px; border-radius: 50%; border: 4px solid white; background: white; margin: 0 auto 15px; display: block; object-fit: cover; }
        nav { background: #054d44; padding: 15px; position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; flex-wrap: wrap; gap: 10px; }
        nav a { color: white; text-decoration: none; font-weight: bold; font-size: 13px; text-transform: uppercase; padding: 5px 10px; border-radius: 5px; }
        .container { max-width: 1000px; margin: 30px auto; padding: 25px; background: white; border-radius: 15px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); text-align: left; }
        h2 { color: var(--primary); border-left: 5px solid var(--accent); padding-left: 15px; margin-bottom: 20px; text-transform: uppercase; margin-top: 0; }
        
        /* Gallery */
        .gallery-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .gallery-card { border: 1px solid #ddd; border-radius: 12px; overflow: hidden; background: white; text-align: center; }
        .gallery-card img { width: 100%; height: 250px; object-fit: cover; background: #eee; }
        .gallery-caption { padding: 15px; color: var(--primary); font-weight: bold; }

        /* Squad */
        .player-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 12px; }
        .player-card { background: #f9fbf9; padding: 15px; border-radius: 10px; border: 1px solid #e0eadd; text-align: center; }
        .player-name { font-weight: bold; color: var(--primary); display: block; }
        .captain { background: var(--primary) !important; color: white !important; }
        .captain .player-name { color: white !important; }

        .footer { padding: 50px; text-align: center; color: #888; border-top: 1px solid #eee; margin-top: 50px; }
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
    <a href="#management">Management</a>
</nav>

<div class="container" id="gallery">
    <h2>🏆 Achievements & Gallery</h2>
    <div class="gallery-grid">
        <div class="gallery-card">
            <img src="trophy1.png" alt="Tournament Victory">
            <div class="gallery-caption">Tournament Winners 2025</div>
        </div>
        <div class="gallery-card">
            <img src="swabi_cup.png" alt="Swabi Cup Finalists">
            <div class="gallery-caption">Finalists - Swabi Cup</div>
        </div>
    </div>
</div>
<div class="container" id="news">
    <h2>📢 Latest Announcements</h2>
    
    <div style="background: #e9f5f2; padding: 25px; border-radius: 12px; border-left: 6px solid #25d366; margin-bottom: 20px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
        <h3 style="color: #075e54; margin-top: 0; text-align: center;">🏏 FINAL MATCH: DOCTOR 11 vs QADRA</h3>
        <p style="text-align: center; font-size: 1.2em; font-weight: bold; color: #054d44;">ڈاکٹر 11 پنجمن بہ مقابلہ قدرہ</p>
        
        <div style="background: white; padding: 15px; border-radius: 8px; border: 1px dashed #075e54; margin-top: 15px;">
            <ul style="list-style: none; padding: 0; margin: 0; color: #333; line-height: 2;">
                <li>📅 <b>Day:</b> Friday (جمعہ)</li>
                <li>⏰ <b>Time:</b> 2:30 PM (ڈھائی بجے)</li>
                <li>📍 <b>Venue:</b> Qadra Cricket Ground (قدرہ کرکٹ گراؤنڈ)</li>
            </ul>
        </div>
        
        <p style="margin-top: 20px; text-align: center; font-weight: bold; color: #075e54;">
            ہم اپنے معزز مہمانوں اور شائقینِ کرکٹ کا صمیمِ قلب سے خیر مقدم کرتے ہیں۔ آپ سب کی شرکت ہمارے لیے اعزاز کی بات ہوگی۔
        </p>
        <p style="text-align: center; font-style: italic; color: #555;">
            We warmly welcome all cricket fans and look forward to your gracious presence!
        </p>
    </div>
</div>

<div class="container" id="news">
    <h2>📢 Latest Announcements</h2>
    <div style="background: #e9f5f2; padding: 25px; border-radius: 12px; border-left: 6px solid var(--accent);">
        <h3 style="color: #075e54; margin: 0;">🏆 Doctor 11 Enters PSL 2026!</h3>
        <p>We are thrilled to participate in the <b>3rd Edition of the Panjman Super League</b> as a participant and sponsor!</p>
    </div>
</div>

<div class="container" id="squad">
    <h2>🏏 2026 Official Squad (18 Players)</h2>
    <div class="player-grid">
        <div class="player-card captain"><span class="player-name">Muneer Iqbal</span><span>Captain</span></div>
        <div class="player-card"><span class="player-name">Muhammad Amir</span><span>Premium All-Rounder</span></div>
        <div class="player-card"><span class="player-name">Huzaifa Ahmad</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Muhammad Hasnain</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Haris Iqbal</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Behram Khan</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Shakeel Ahmad</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Waqar Khan</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Saqib Shah</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Abubakar</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Shehbaz</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Azan Khan</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Baser Khan</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Sohail Ahmad</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Osama Khan</span><span>Player</span></div>
        <div class="player-card"><span class="player-name">Ihtisham Khan</span><span>Player</span></div>
    </div>
<div class="container" id="management">
<div class="container" id="management">
    <h2>🤝 Team Leadership & Contact</h2>
    
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-bottom: 30px;">
        
        <div style="background: #f9fbf9; padding: 20px; border-radius: 12px; border: 1px solid #e0eadd; text-align: center;">
            <h4 style="margin: 0; color: #075e54;">Dr. Tausif Ahmad</h4>
            <p style="margin: 5px 0; font-size: 0.9em; color: #666; font-weight: bold;">Team Owner</p>
            <p style="font-size: 0.85em; color: #555;">Founder and Lead Supporter of Doctor 11 Panjman.</p>
        </div>

        <div style="background: #e9f5f2; padding: 20px; border-radius: 12px; border: 2px solid #25d366; text-align: center;">
            <h4 style="margin: 0; color: #075e54;">Sameer Khan</h4>
            <p style="margin: 5px 0; font-size: 0.9em; color: #128c7e; font-weight: bold;">Media Director & Web Developer</p>
            <p style="font-size: 0.85em; color: #555;">Managing digital presence and SH Studio productions.</p>
        </div>
    </div>

    <div style="background: #075e54; color: white; padding: 35px; border-radius: 15px; text-align: center; box-shadow: 0 10px 25px rgba(7,94,84,0.2);">
        <h3 style="margin-top: 0; font-size: 1.5em; letter-spacing: 1px;">📩 CONNECT WITH US</h3>
        <p style="margin-bottom: 25px; opacity: 0.9;">Official contact for Doctor 11 Panjman inquiries and SH Studio media.</p>
        
        <div style="display: flex; justify-content: center; flex-wrap: wrap; gap: 15px;">
            <a href="https://wa.me/923429212247" target="_blank" style="text-decoration: none; background: #25d366; color: white; padding: 12px 25px; border-radius: 50px; font-weight: bold; font-size: 0.9em; transition: 0.3s; border: 2px solid #25d366;">
                WhatsApp
            </a>
            
            <a href="mailto:asameerkhan352@gmail.com" style="text-decoration: none; background: white; color: #075e54; padding: 12px 25px; border-radius: 50px; font-weight: bold; font-size: 0.9em; transition: 0.3s; border: 2px solid white;">
                Email Team
            </a>

            <a href="https://youtube.com/@sh-studio_official?si=smcbPjsf45GtuZPy" target="_blank" style="text-decoration: none; background: #ff0000; color: white; padding: 12px 25px; border-radius: 50px; font-weight: bold; font-size: 0.9em; transition: 0.3s; border: 2px solid #ff0000;">
                SH Studio YouTube
            </a>
        </div>
        
        <p style="margin-top: 25px; font-size: 0.8em; color: #a5d6a7; border-top: 1px solid rgba(255,255,255,0.1); padding-top: 15px;">
            📍 Panjman, Swabi, Khyber Pakhtunkhwa, Pakistan
        </p>
    </div>
</div>


<div class="footer">
    <p>&copy; 2026 Doctor 11 Panjman | Built by Sameer Khan</p>
</div>

</body>
</html>
