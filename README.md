<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor 11 Panjman</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }
        /* FIX: Full Green Header */
        .hero {
            background: linear-gradient(135deg, #064e3b 0%, #065f46 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
            width: 100%;
            box-sizing: border-box;
            margin: 0;
        }
        .hero img {
            width: 120px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 15px;
        }
        .nav-menu {
            background: #043d2e;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 10px;
            gap: 15px;
        }
        .nav-menu a {
            color: white;
            text-decoration: none;
            font-size: 14px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
        }
        .section-title {
            color: #064e3b;
            border-left: 5px solid #064e3b;
            padding-left: 10px;
            margin-bottom: 20px;
        }
        .squad-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
        }
        .player-card {
            background: white;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .player-card h3 { margin: 5px 0; color: #333; }
        .player-card p { margin: 0; color: #666; font-size: 13px; }
        
        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25d366;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.2);
        }
    </style>
</head>
<body>

    <header class="hero">
        <img src="https://via.placeholder.com/120" alt="Doctor 11 Logo">
        <h1>DOCTOR 11 PANJMAN</h1>
        <p>Official Cricket Team | Panjman, Swabi</p>
    </header>

    <nav class="nav-menu">
        <a href="#achievements">Achievements</a>
        <a href="#squad">Squad</a>
        <a href="#announcements">Announcements</a>
        <a href="#management">Management</a>
    </nav>

    <div class="container">
        <h2 id="squad" class="section-title">TEAM SQUAD</h2>
        <div class="squad-grid">
            <div class="player-card"><h3>Muneer Iqbal</h3><p>Captain</p></div>
            <div class="player-card"><h3>Muhammad Amir</h3><p>All-Rounder</p></div>
            <div class="player-card"><h3>Muhammad Huzaifa</h3><p>Batsman</p></div>
            <div class="player-card"><h3>Saqib Shah</h3><p>Bowler</p></div>
            <div class="player-card"><h3>Adnan</h3><p>Batsman</p></div>
            <div class="player-card"><h3>Samir Khan</h3><p>Media Director</p></div>
        </div>
    </div>

    <a href="https://wa.me/YOURNUMBER" class="whatsapp-float">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="35" alt="WhatsApp">
    </a>

</body>
</html>
