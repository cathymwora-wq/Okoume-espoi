<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Okoumé Espoir - Arbre de Noël Solidaire à Libreville</title>
    <style>
        :root {
            --okoume: #2c5e3b;
            --okoume-dark: #1b3b25;
            --okoume-light: #4a8c5c;
            --okoume-accent: #d4a373;
            --okoume-warm: #faedcd;
            --gray-50: #f9fafb;
            --gray-100: #f3f4f6;
            --gray-600: #4b5563;
            --gray-750: #2d3748;
            --gray-900: #111827;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: system-ui, -apple-system, sans-serif; }
        body { background-color: var(--gray-50); color: var(--gray-900); line-height: 1.6; }
        header { background: white; border-bottom: 1px solid var(--gray-100); position: sticky; top: 0; z-index: 50; }
        .nav-container { max-width: 1200px; margin: 0 auto; padding: 0 20px; height: 80px; display: flex; align-items: center; justify-content: space-between; }
        .logo-area { display: flex; align-items: center; gap: 12px; }
        .logo-icon { width: 48px; height: 48px; background: var(--okoume); color: white; border-radius: 12px; display: flex; align-items: center; justify-content: center; font-size: 20px; }
        .logo-text h1 { font-size: 18px; font-weight: 900; color: var(--okoume-dark); }
        .logo-text p { font-size: 11px; color: var(--gray-600); }
        nav { display: flex; gap: 24px; align-items: center; }
        nav a { text-decoration: none; color: var(--gray-600); font-weight: 600; font-size: 14px; }
        .btn-primary { background: var(--okoume); color: white; padding: 10px 20px; border-radius: 10px; font-weight: 700; text-decoration: none; border: none; cursor: pointer; }
        .btn-accent { background: var(--okoume-accent); color: var(--okoume-dark); padding: 12px 24px; border-radius: 10px; font-weight: 800; text-decoration: none; border: none; cursor: pointer; }
        .hero { background: linear-gradient(135deg, var(--okoume-dark), var(--okoume), var(--okoume-light)); color: white; padding: 80px 20px; }
        .hero-grid { max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: center; }
        .hero-content h2 { font-size: 42px; font-weight: 900; line-height: 1.2; margin-bottom: 20px; }
        .hero-content h2 span { color: var(--okoume-accent); }
        .hero-card { background: rgba(255,255,255,0.1); backdrop-filter: blur(12px); border: 1px solid rgba(255,255,255,0.2); padding: 32px; border-radius: 24px; }
        section { padding: 80px 20px; }
        .container { max-width: 1200px; margin: 0 auto; }
        .section-header { text-align: center; max-width: 700px; margin: 0 auto 50px auto; }
        .badge { display: inline-block; background: rgba(44,94,59,0.1); color: var(--okoume); padding: 6px 16px; border-radius: 50px; font-weight: 700; font-size: 12px; text-transform: uppercase; margin-bottom: 12px; }
        .grid-3 { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px; }
        .card { background: white; border-radius: 20px; padding: 30px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); border: 1px solid var(--gray-100); }
        .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; }
        .form-card { background: white; padding: 40px; border-radius: 24px; box-shadow: 0 15px 35px rgba(0,0,0,0.05); border: 1px solid var(--gray-100); }
        .form-group { margin-bottom: 20px; }
        .form-group label { display: block; font-size: 14px; font-weight: 700; color: var(--gray-750); margin-bottom: 8px; }
        .form-control { width: 100%; padding: 12px 16px; border: 1px solid #d1d5db; border-radius: 10px; font-size: 14px; }
        footer { background: var(--okoume-dark); color: white; padding: 60px 20px 30px 20px; }
        .footer-grid { max-width: 1200px; margin: 0 auto; display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 40px; margin-bottom: 40px; }
        .footer-bottom { max-width: 1200px; margin: 0 auto; padding-top: 20px; border-top: 1px solid rgba(255,255,255,0.1); text-align: center; font-size: 13px; color: #9ca3af; }
    </style>
</head>
<body>
    <header>
        <div class="nav-container">
            <div class="logo-area">
                <div class="logo-icon">🌿</div>
                <div class="logo-text">
                    <h1>OKOUMÉ ESPOIR</h1>
                    <p>Association Loi 1901 • RNA W543017664</p>
                </div>
            </div>
            <nav>
                <a href="#accueil">Accueil</a>
                <a href="#projet" style="color: var(--okoume); font-weight: bold;">🎁 Noël à Libreville</a>
                <a href="#association">L'Association</a>
                <a href="#benevole">Devenir Bénévole</a>
                <a href="#contact">Contact</a>
            </nav>
            <div><a href="#projet" class="btn-primary">Soutenir le Projet</a></div>
        </div>
    </header>
    <section id="accueil" class="hero">
        <div class="hero-grid">
            <div class="hero-content">
                <span class="badge" style="background: rgba(255,255,255,0.2); color: var(--okoume-warm);">Campagne Solidaire</span>
                <h2>Offrons un Arbre de Noël magique aux orphelins de <span>Libreville</span>.</h2>
                <p>L'association <strong>Okoumé Espoir</strong> lance sa grande collecte de fin d'année pour illuminer les yeux des enfants de l'orphelinat partenaire au Gabon.</p>
                <div style="display: flex; gap: 16px; flex-wrap: wrap; margin-top: 20px;">
                    <a href="#projet" class="btn-accent">🎁 Participer à l'Arbre de Noël</a>
                    <a href="#benevole" class="btn-primary" style="background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.3);">🤝 Devenir Bénévole</a>
                </div>
            </div>
            <div class="hero-card">
                <h3>🎯 Nos Objectifs pour l'Orphelinat</h3>
                <ul style="list-style: none; display: flex; flex-direction: column; gap: 16px; font-size: 14px; margin-top: 15px;">
                    <li>⭐ <strong>Distribution de cadeaux :</strong> Un jouet neuf pour chaque enfant.</li>
                    <li>⭐ <strong>Goûter de fête :</strong> Un moment festif et gourmand partagé tous ensemble.</li>
                    <li>⭐ <strong>Soutien matériel :</strong> Fournitures scolaires et produits d'hygiène essentiels.</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="association" style="background: var(--gray-100);">
        <div class="container">
            <div class="grid-2" style="align-items: center;">
                <div>
                    <span class="badge">Notre Identité</span>
                    <h3 style="font-size: 32px; font-weight: 900; color: var(--okoume-dark); margin-bottom: 20px;">L'Association Okoumé Espoir</h3>
                    <p style="color: var(--gray-600); margin-bottom: 20px; font-size: 15px;">
                        Déclarée officiellement en préfecture de Meurthe-et-Moselle et parue au Journal Officiel, l'association a pour vocation d'apporter un soutien matériel, alimentaire, éducatif, médical et humain aux personnes vulnérables, notamment les orphelins au Gabon et en France[span_0](start_span)[span_0](end_span).
                    </p>
                    <div style="background: white; padding: 20px; border-radius: 16px; border: 1px solid #e5e7eb; display: flex; flex-direction: column; gap: 12px;">
                        <div><strong>Numéro RNA :</strong> W543017664[span_1](start_span)[span_1](end_span)</div>
                        <div><strong>Siège administratif :</strong> Nancy, Meurthe-et-Moselle (54)[span_2](start_span)[span_2](end_span)</div>
                        <div><strong>Contact :</strong> Cathymwora@gmail.com</div>
                    </div>
                </div>
                <div style="background: var(--okoume-dark); color: white; padding: 40px; border-radius: 24px;">
                    <h4 style="font-size: 22px; font-weight: bold; margin-bottom: 20px; color: var(--okoume-accent);">Nos Missions Officielles</h4>
                    <ul style="list-style: none; display: flex; flex-direction: column; gap: 16px; font-size: 14px;">
                        <li>✅ <strong>Soutien global :</strong> Matériel, alimentaire, éducatif et médical pour les orphelins[span_3](start_span)[span_3](end_span).</li>
                        <li>✅ <strong>Collectes et acheminement :</strong> Distribution de produits de première nécessité[span_4](start_span)[span_4](end_span).</li>
                        <li>✅ <strong>Action de terrain :</strong> Soutien aux structures d'accueil et entraide solidaire[span_5](start_span)[span_5](end_span).</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <section id="benevole">
        <div class="container">
            <div class="grid-2">
                <div class="form-card">
                    <h3 style="font-size: 20px; font-weight: 900; color: var(--okoume-dark); margin-bottom: 15px;">🤝 Devenir Bénévole</h3>
                    <form action="https://formspree.io/f/Cathymwora@gmail.com" method="POST">
                        <div class="form-group"><label>Nom et Prénom</label><input type="text" name="nom" required class="form-control" placeholder="Marie Dupont"></div>
                        <div class="form-group"><label>Email</label><input type="email" name="email" required class="form-control" placeholder="marie@exemple.fr"></div>
                        <div class="form-group"><label>Téléphone</label><input type="tel" name="telephone" class="form-control" placeholder="06 12 34 56 78"></div>
                        <div class="form-group"><label>Comment souhaitez-vous aider ?</label>
                            <select name="aide" class="form-control">
                                <option>Collecte et tri des jouets</option>
                                <option>Aide pour l'Arbre de Noël</option>
                                <option>Communication et partenariats</option>
                            </select>
                        </div>
                        <button type="submit" class="btn-primary" style="width: 100%; justify-content: center;">Envoyer ma candidature</button>
                    </form>
                </div>
                <div id="contact" class="form-card">
                    <h3 style="font-size: 20px; font-weight: 900; color: var(--okoume-dark); margin-bottom: 15px;">✉️ Contactez-nous</h3>
                    <form action="https://formspree.io/f/Cathymwora@gmail.com" method="POST">
                        <div class="form-group"><label>Votre Nom</label><input type="text" name="nom" required class="form-control" placeholder="Jean Martin"></div>
                        <div class="form-group"><label>Votre Email</label><input type="email" name="email" required class="form-control" placeholder="jean@exemple.fr"></div>
                        <div class="form-group"><label>Message</label><textarea name="message" rows="3" required class="form-control" placeholder="Votre message..."></textarea></div>
                        <button type="submit" class="btn-accent" style="width: 100%; justify-content: center;">Envoyer le message</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="footer-grid">
            <div>
                <h5 style="color: var(--okoume-accent); font-weight: bold; margin-bottom: 10px;">OKOUMÉ ESPOIR</h5>
                <p style="font-size: 13px; color: #d1d5db;">Association loi 1901 • RNA W543017664[span_6](start_span)[span_6](end_span)</p>
                <p style="font-size: 13px; color: #d1d5db;">Nancy, Meurthe-et-Moselle (54)[span_7](start_span)[span_7](end_span)</p>
            </div>
            <div>
                <h6 style="font-weight: bold; margin-bottom: 10px;">Contact direct</h6>
                <p style="font-size: 13px; color: #9ca3af;">Cathymwora@gmail.com</p>
            </div>
        </div>
        <div class="footer-bottom">© 2026 Association Okoumé Espoir. Tous droits réservés.</div>
    </footer>
</body>
</html>
