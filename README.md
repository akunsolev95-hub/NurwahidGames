<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nurwahid Games | Enterprise Gaming Portal</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #0f172a;
            --accent: #2563eb;
            --ps2-color: #003791;
            --android-color: #3ddc84;
            --pc-color: #f59e0b;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --bg-subtle: #f8fafc;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Inter', sans-serif; background-color: #fff; color: var(--text-main); line-height: 1.6; }

        /* Header & Nav */
        nav { display: flex; justify-content: space-between; align-items: center; padding: 20px 8%; background: #fff; border-bottom: 1px solid #e2e8f0; position: sticky; top: 0; z-index: 100; }
        .logo { font-size: 1.4rem; font-weight: 800; color: var(--primary); letter-spacing: -0.5px; }
        .logo span { color: var(--accent); }

        /* Hero Section */
        .hero { padding: 100px 8% 60px; background: var(--primary); color: white; text-align: center; }
        .hero h1 { font-size: 3rem; font-weight: 700; margin-bottom: 15px; }
        .hero p { color: #94a3b8; font-size: 1.1rem; max-width: 600px; margin: 0 auto; }

        /* Catalog Grid */
        .container { padding: 60px 8%; }
        .section-header { margin-bottom: 40px; border-left: 4px solid var(--accent); padding-left: 20px; }
        
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; }

        /* Card Design */
        .card { background: white; border-radius: 12px; border: 1px solid #e2e8f0; overflow: hidden; transition: 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .card:hover { transform: translateY(-8px); box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1); }
        
        .card-tag { padding: 15px 25px; font-weight: 700; font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; color: white; }
        .bg-ps2 { background: var(--ps2-color); }
        .bg-android { background: var(--android-color); }
        .bg-pc { background: var(--pc-color); }

        .game-item { padding: 15px 25px; border-bottom: 1px solid #f1f5f9; display: flex; justify-content: space-between; align-items: center; }
        .game-item:last-child { border-bottom: none; }
        .game-info h4 { font-size: 0.95rem; color: var(--primary); }
        .game-info p { font-size: 0.8rem; color: var(--text-muted); }

        .btn-link { font-size: 0.75rem; font-weight: 600; color: var(--accent); text-decoration: none; border: 1px solid var(--accent); padding: 4px 12px; border-radius: 4px; transition: 0.2s; }
        .btn-link:hover { background: var(--accent); color: white; }

        /* Contact Section */
        .contact-box { background: var(--bg-subtle); border-radius: 20px; padding: 60px; text-align: center; margin: 40px 8%; border: 1px solid #e2e8f0; }
        .whatsapp-main { display: inline-flex; align-items: center; background: #25d366; color: white; padding: 16px 32px; border-radius: 50px; text-decoration: none; font-weight: 700; font-size: 1.1rem; margin-top: 25px; box-shadow: 0 10px 15px -3px rgba(37, 211, 102, 0.3); }

        footer { text-align: center; padding: 40px; color: var(--text-muted); font-size: 0.9rem; border-top: 1px solid #e2e8f0; }
    </style>
</head>
<body>

    <nav>
        <div class="logo">NURWAHID<span>GAMES</span></div>
        <div style="font-size: 0.9rem; color: var(--text-muted);">Corporate Identity Portal</div>
    </nav>

    <header class="hero">
        <h1>Premium Game Database</h1>
        <p>Akses informasi terpusat untuk berbagai judul game lintas platform dengan standar profesional.</p>
    </header>

    <main class="container">
        <div class="grid">
            
            <div class="card">
                <div class="card-tag bg-ps2">Legacy: PlayStation 2</div>
                <div class="game-item">
                    <div class="game-info"><h4>GTA San Andreas</h4><p>Action-Adventure</p></div>
                    <a href="https://www.rockstargames.com/games/sanandreas" class="btn-link" target="_blank">DETAIL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Resident Evil 4</h4><p>Survival Horror</p></div>
                    <a href="https://www.capcom.com/" class="btn-link" target="_blank">DETAIL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>God of War II</h4><p>Hack and Slash</p></div>
                    <a href="https://www.playstation.com/en-id/games/god-of-war/" class="btn-link" target="_blank">DETAIL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Devil May Cry 3</h4><p>Action</p></div>
                    <a href="#" class="btn-link">DETAIL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Final Fantasy X</h4><p>RPG</p></div>
                    <a href="#" class="btn-link">DETAIL</a>
                </div>
            </div>

            <div class="card">
                <div class="card-tag bg-android">Mobile: Android OS</div>
                <div class="game-item">
                    <div class="game-info"><h4>Mobile Legends</h4><p>MOBA Strategy</p></div>
                    <a href="https://play.google.com/store/apps/details?id=com.mobile.legends" class="btn-link" target="_blank">PLAY STORE</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Genshin Impact</h4><p>Open World RPG</p></div>
                    <a href="https://play.google.com/store/apps/details?id=com.miHoYo.GenshinImpact" class="btn-link" target="_blank">PLAY STORE</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>PUBG Mobile</h4><p>Battle Royale</p></div>
                    <a href="https://play.google.com/store/apps/details?id=com.tencent.ig" class="btn-link" target="_blank">PLAY STORE</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Call of Duty Mobile</h4><p>FPS</p></div>
                    <a href="#" class="btn-link">PLAY STORE</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>League of Legends: WR</h4><p>MOBA</p></div>
                    <a href="#" class="btn-link">PLAY STORE</a>
                </div>
            </div>

            <div class="card">
                <div class="card-tag bg-pc">High-End: PC / Windows</div>
                <div class="game-item">
                    <div class="game-info"><h4>Cyberpunk 2077</h4><p>Action RPG</p></div>
                    <a href="https://store.steampowered.com/app/1091500/Cyberpunk_2077/" class="btn-link" target="_blank">STEAM</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Valorant</h4><p>Tactical Shooter</p></div>
                    <a href="https://playvalorant.com/" class="btn-link" target="_blank">OFFICIAL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Elden Ring</h4><p>Souls-like RPG</p></div>
                    <a href="https://store.steampowered.com/app/1245620/ELDEN_RING/" class="btn-link" target="_blank">STEAM</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Minecraft</h4><p>Sandbox</p></div>
                    <a href="#" class="btn-link">OFFICIAL</a>
                </div>
                <div class="game-item">
                    <div class="game-info"><h4>Red Dead Redemption 2</h4><p>Adventure</p></div>
                    <a href="#" class="btn-link">STEAM</a>
                </div>
            </div>

        </div>
    </main>

    <section class="contact-box">
        <h2>Konsultasi Teknis & Informasi Lanjutan</h2>
        <p>Butuh bantuan instalasi atau mencari database game lainnya? Hubungi tim ahli kami melalui jalur komunikasi resmi.</p>
        <a href="https://wa.me/6282340759929" class="whatsapp-main">
            Hubungi via WhatsApp (082340759929)
        </a>
    </section>

    <footer>
        <p>&copy; 2026 Nurwahid Games Corporation. Seluruh aset konten dilindungi oleh kebijakan perusahaan.</p>
    </footer>

</body>
</html>

