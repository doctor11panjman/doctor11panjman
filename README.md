<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman | Official Site</title>
    <style>
        :root {
            --main-green: #064e3b;
            --light-green: #065f46;
            --accent-gold: #fbbf24;
            --white: #ffffff;
            --bg-gray: #f1f5f9;
        }
        body { margin: 0; font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; background-color: var(--bg-gray); color: #1e293b; line-height: 1.6; }
        
        /* FIX: FULL WIDTH GREEN HEADER */
        .hero-section {
            background: linear-gradient(135deg, var(--main-green) 0%, var(--light-green) 100%);
            color: var(--white);
            padding: 50px 20px;
            text-align: center;
            width: 100%;
            box-sizing: border-box;
            border-bottom: 5px solid var(--accent-gold);
        }
        .hero-section img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid var(--white);
            margin-bottom: 15px;
            background-color: white;
            object-fit: cover;
        }

        .nav-bar {
            background: #043d2e;
            position: sticky;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: center;
            padding: 12px;
            gap: 20px;
            flex-wrap: wrap;
        }
        .nav-bar a { color: white; text-decoration: none; font-weight: 600; font-size: 13px; text-transform: uppercase; }

        .announcement-banner {
            background: var(--accent-gold);
            color: #000;
            padding: 15px;
            text-align: center;
            font-weight: bold;
            margin: 20px auto;
            max-width: 900px;
            border-radius: 8px;
            border: 2px dashed var(--main-green);
        }

        .container { max-width: 1100px; margin: 0 auto; padding: 20px; }
        .section-header { border-left: 6px solid var(--main-green); padding-left: 15px; margin: 40px 0 20px; color: var(--main-green); font-size: 22px; text-transform: uppercase; }

        .grid-layout { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .card { background: white; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 6px rgba(0,0,0,0.05); text-align: center; padding: 20px; }
        
        .player-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 12px; }
        .player-card { background: white; padding: 15px; border-radius: 8px; text-align: center; border-bottom: 3px solid var(--main-green); }

        .footer-info { background: #e2e8f0; padding: 30px 20px; text-align: center; margin-top: 50px; border-top: 1px solid #cbd5e1; }
        .footer-info a { color: var(--main-green); text-decoration: none; font-weight: bold; margin: 0 10px; }

        .whatsapp-btn { position: fixed; bottom: 20px; right: 20px; background: #25d366; width: 60px; height: 60px; border-radius: 50%; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 10px rgba(0,0,0,0.3); z-index: 999; }
    </style>
</head>
<body>

    <header class="hero-section">
        <img src="logo.png" alt="Doctor 11 Logo">
        <h1>DOCTOR 11 PANJMAN</h1>
        <p>Official Cricket Team | Panjman, Swabi</p>
    </header>

    <nav class="nav-bar">
        <a href="#news">Latest News</a>
        <a href="#squad">Squad</a>
        <a href="#management">Management</a>
        <a href="https://www.youtube.com/@SH-Studio_Official" target="_blank">YouTube</a>
    </nav>

    <div class="container">
        
        <h2 id="news" class="section-header">📢 Latest Announcement</h2>
        <div class="announcement-banner">
            🏏 FINAL MATCH: Doctor 11 Panjman vs Qadra <br>
            📅 Friday | 🕒 2:30 PM <br>
            📍 Venue: Qadra Cricket Ground
        </div>

        <h2 id="management" class="section-header">👔 Team Management</h2>
        <div class="grid-layout">
            <div class="card"><h3>Dr. Tauseef Ahmed</h3><p>Team Owner & Chairman</p></div>
            <div class="card"><h3>Muneer Iqbal</h3><p>Team Captain</p></div>
            <div class="card"><h3>Samir Khan</h3><p>Media Director</p></div>
        </div>

        <h2 id="squad" class="section-header">🏏 Official Squad</h2>
        <div class="player-grid">
            <div class="player-card"><h3>Muhammad Amir</h3><p>All-Round
            
