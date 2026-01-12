<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Horse Agenda Pro</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; background: linear-gradient(135deg, #E67E22, #D35400); min-height: 100vh; color: #333; }
        .lang-switcher { position: absolute; top: 20px; right: 20px; }
        .lang-switcher button { background: white; border: none; padding: 8px 12px; margin: 2px; border-radius: 5px; cursor: pointer; font-weight: bold; }
        .lang-switcher button:hover, .lang-switcher button.active { background: #333; color: white; }
        .container { max-width: 800px; margin: 0 auto; padding: 60px 20px; }
        .hero { text-align: center; color: white; margin-bottom: 40px; }
        .hero h1 { font-size: 3em; margin-bottom: 10px; }
        .hero p { font-size: 1.3em; opacity: 0.9; }
        .card { background: white; border-radius: 15px; padding: 30px; margin-bottom: 20px; box-shadow: 0 10px 30px rgba(0,0,0,0.2); }
        .card h2 { color: #E67E22; margin-bottom: 15px; }
        .card ul { list-style: none; }
        .card li { padding: 10px 0; border-bottom: 1px solid #eee; }
        .card li:last-child { border: none; }
        .card li::before { content: "✓ "; color: #27ae60; font-weight: bold; }
        .contact-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; margin-top: 20px; }
        .contact-item { text-align: center; padding: 20px; background: #f8f9fa; border-radius: 10px; }
        .contact-item a { color: #E67E22; text-decoration: none; font-weight: bold; }
        .footer { text-align: center; color: white; margin-top: 40px; opacity: 0.8; }
        .lang-content { display: none; }
        .lang-content.active { display: block; }
    </style>
</head>
<body>
    <div class="lang-switcher">
        <button onclick="switchLang('fr')" class="active">FR</button>
        <button onclick="switchLang('en')">EN</button>
        <button onclick="switchLang('de')">DE</button>
        <button onclick="switchLang('nl')">NL</button>
    </div>

    <div class="container">
        <div class="hero">
            <h1>🐴 Horse Agenda Pro</h1>
            <p class="lang-content active" data-lang="fr">L'application de gestion pour les professionnels équins</p>
            <p class="lang-content" data-lang="en">The management app for equine professionals</p>
            <p class="lang-content" data-lang="de">Die Verwaltungs-App für Pferdeprofis</p>
            <p class="lang-content" data-lang="nl">De beheer-app voor paardenprofessionals</p>
        </div>

        <!-- FRANÇAIS -->
        <div class="lang-content active" data-lang="fr">
            <div class="card">
                <h2>Fonctionnalités</h2>
                <ul>
                    <li>Gestion complète des clients et chevaux</li>
                    <li>Calendrier de rendez-vous intelligent</li>
                    <li>Suivi de l'équipement par cheval</li>
                    <li>Gestion du stock de matériel</li>
                    <li>Optimisation des tournées GPS</li>
                    <li>Notifications push pour rappels</li>
                    <li>Système d'urgences</li>
                    <li>Historique complet des interventions</li>
                </ul>
            </div>
            <div class="card">
                <h2>Pour qui ?</h2>
                <p>Horse Agenda Pro est conçu pour tous les professionnels équins : maréchaux-ferrants, vétérinaires, dentistes équins, ostéopathes, et autres spécialistes.</p>
            </div>
            <div class="card">
                <h2>Contact & Support</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <p>📧 Email</p>
                        <a href="mailto:mathieudumortier80@gmail.com">mathieudumortier80@gmail.com</a>
                    </div>
                    <div class="contact-item">
                        <p>🌐 Site web</p>
                        <a href="https://horseagenda.app">horseagenda.app</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- ENGLISH -->
        <div class="lang-content" data-lang="en">
            <div class="card">
                <h2>Features</h2>
                <ul>
                    <li>Complete client and horse management</li>
                    <li>Smart appointment calendar</li>
                    <li>Equipment tracking per horse</li>
                    <li>Stock management</li>
                    <li>GPS route optimization</li>
                    <li>Push notifications for reminders</li>
                    <li>Emergency system</li>
                    <li>Complete intervention history</li>
                </ul>
            </div>
            <div class="card">
                <h2>Who is it for?</h2>
                <p>Horse Agenda Pro is designed for all equine professionals: farriers, veterinarians, equine dentists, osteopaths, and other specialists.</p>
            </div>
            <div class="card">
                <h2>Contact & Support</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <p>📧 Email</p>
                        <a href="mailto:mathieudumortier80@gmail.com">mathieudumortier80@gmail.com</a>
                    </div>
                    <div class="contact-item">
                        <p>🌐 Website</p>
                        <a href="https://horseagenda.app">horseagenda.app</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- DEUTSCH -->
        <div class="lang-content" data-lang="de">
            <div class="card">
                <h2>Funktionen</h2>
                <ul>
                    <li>Komplette Kunden- und Pferdeverwaltung</li>
                    <li>Intelligenter Terminkalender</li>
                    <li>Ausrüstungsverfolgung pro Pferd</li>
                    <li>Lagerverwaltung</li>
                    <li>GPS-Routenoptimierung</li>
                    <li>Push-Benachrichtigungen für Erinnerungen</li>
                    <li>Notfallsystem</li>
                    <li>Vollständiger Interventionsverlauf</li>
                </ul>
            </div>
            <div class="card">
                <h2>Für wen?</h2>
                <p>Horse Agenda Pro ist für alle Pferdeprofis konzipiert: Hufschmiede, Tierärzte, Pferdezahnärzte, Osteopathen und andere Spezialisten.</p>
            </div>
            <div class="card">
                <h2>Kontakt & Support</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <p>📧 E-Mail</p>
                        <a href="mailto:mathieudumortier80@gmail.com">mathieudumortier80@gmail.com</a>
                    </div>
                    <div class="contact-item">
                        <p>🌐 Webseite</p>
                        <a href="https://horseagenda.app">horseagenda.app</a>
                    </div>
                </div>
            </div>
        </div>

        <!-- NEDERLANDS -->
        <div class="lang-content" data-lang="nl">
            <div class="card">
                <h2>Functies</h2>
                <ul>
                    <li>Volledig klanten- en paardenbeheer</li>
                    <li>Slimme afsprakenkalender</li>
                    <li>Uitrustingtracking per paard</li>
                    <li>Voorraadbeheer</li>
                    <li>GPS-route optimalisatie</li>
                    <li>Push-notificaties voor herinneringen</li>
                    <li>Noodsysteem</li>
                    <li>Volledige interventiegeschiedenis</li>
                </ul>
            </div>
            <div class="card">
                <h2>Voor wie?</h2>
                <p>Horse Agenda Pro is ontworpen voor alle paardenprofessionals: hoefsmeden, dierenartsen, paardentandartsen, osteopaten en andere specialisten.</p>
            </div>
            <div class="card">
                <h2>Contact & Support</h2>
                <div class="contact-grid">
                    <div class="contact-item">
                        <p>📧 E-mail</p>
                        <a href="mailto:mathieudumortier80@gmail.com">mathieudumortier80@gmail.com</a>
                    </div>
                    <div class="contact-item">
                        <p>🌐 Website</p>
                        <a href="https://horseagenda.app">horseagenda.app</a>
                    </div>
                </div>
            </div>
        </div>

        <div class="footer">
            <p>© 2025 Horse Agenda. All rights reserved.</p>
        </div>
    </div>

    <script>
        function switchLang(lang) {
            document.querySelectorAll('.lang-content').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('[data-lang="' + lang + '"]').forEach(el => el.classList.add('active'));
            document.querySelectorAll('.lang-switcher button').forEach(btn => btn.classList.remove('active'));
            event.target.classList.add('active');
        }
    </script>
</body>
</html>