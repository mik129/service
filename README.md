<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>M&M Digital – Performance de l'IA</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    :root {
      --bg: #050816;
      --card: #0f172a;
      --accent: #38bdf8;
      --accent-soft: rgba(56,189,248,0.15);
      --text: #e5e7eb;
      --muted: #9ca3af;
      --danger: #f97373;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #1e293b 0, #020617 45%, #000 100%);
      color: var(--text);
    }
    header {
      padding: 40px 20px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0 0 10px;
      font-size: 2.4rem;
      letter-spacing: 0.04em;
    }
    header p {
      margin: 0;
      color: var(--muted);
      font-size: 0.98rem;
    }
    main {
      max-width: 960px;
      margin: 0 auto 40px;
      padding: 0 16px 40px;
    }
    .badge {
      display: inline-block;
      padding: 4px 10px;
      border-radius: 999px;
      background: var(--accent-soft);
      color: var(--accent);
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 10px;
    }
    .hero {
      text-align: center;
      margin-bottom: 30px;
    }
    .hero h2 {
      font-size: 1.6rem;
      margin: 10px 0 8px;
    }
    .hero p {
      margin: 0;
      color: var(--muted);
      font-size: 0.95rem;
    }
    .grid {
      display: grid;
      gap: 18px;
      margin-top: 24px;
    }
    @media (min-width: 800px) {
      .grid-2 {
        grid-template-columns: 1.4fr 1fr;
      }
      .grid-3 {
        grid-template-columns: repeat(3, minmax(0, 1fr));
      }
    }
    .card {
      background: linear-gradient(145deg, rgba(15,23,42,0.96), rgba(15,23,42,0.9));
      border-radius: 16px;
      padding: 18px 18px 20px;
      border: 1px solid rgba(148,163,184,0.25);
      box-shadow: 0 18px 40px rgba(15,23,42,0.9);
    }
    .card h3 {
      margin: 0 0 8px;
      font-size: 1.1rem;
    }
    .card p {
      margin: 0 0 10px;
      font-size: 0.92rem;
      color: var(--muted);
    }
    ul {
      padding-left: 18px;
      margin: 0 0 10px;
      font-size: 0.9rem;
      color: var(--muted);
    }
    li + li { margin-top: 4px; }
    .price {
      font-size: 1.2rem;
      font-weight: 600;
      color: var(--accent);
      margin-bottom: 6px;
    }
    .tag {
      display: inline-block;
      padding: 2px 8px;
      border-radius: 999px;
      border: 1px solid rgba(148,163,184,0.4);
      font-size: 0.72rem;
      color: var(--muted);
      margin-bottom: 8px;
    }
    .button {
      display: inline-block;
      margin-top: 8px;
      padding: 8px 14px;
      border-radius: 999px;
      background: var(--accent);
      color: #0b1120;
      font-weight: 600;
      font-size: 0.9rem;
      text-decoration: none;
    }
    .button.secondary {
      background: transparent;
      color: var(--accent);
      border: 1px solid rgba(56,189,248,0.5);
    }
    .section-title {
      font-size: 1.2rem;
      margin: 26px 0 10px;
    }
    .section-sub {
      margin: 0 0 14px;
      color: var(--muted);
      font-size: 0.9rem;
    }
    .contact p {
      margin: 4px 0;
      font-size: 0.9rem;
    }
    .danger {
      color: var(--danger);
      font-size: 0.8rem;
    }
  </style>
</head>
<body>

<header>
  <div class="badge">M&M Digital</div>
  <h1>Découvrez la performance de l’IA</h1>
  <p>Automatisation intelligente de vos emails, support client et organisation — sans complexité.</p>
</header>

<main>

  <section class="hero">
    <h2>L’IA qui révolutionne votre gestion d’emails</h2>
    <p>
      Trop d’emails, trop de répétition, pas assez de temps ?<br>
      M&M Digital automatise vos échanges grâce à une IA intelligente, rapide et personnalisable.
    </p>
  </section>

  <section class="grid grid-2">
    <div class="card">
      <h3>Pourquoi choisir M&M Digital ?</h3>
      <p>
        Notre solution vous permet de réduire drastiquement le temps passé sur vos emails tout en
        améliorant la qualité de vos réponses.
      </p>
      <ul>
        <li>Réduction jusqu’à <strong>80&nbsp;%</strong> du temps passé sur les emails</li>
        <li>Réponses instantanées, cohérentes et adaptées au contexte</li>
        <li>Gestion multilingue automatique</li>
        <li>Analyse intelligente du contenu</li>
        <li>Automatisation des rendez-vous et tâches répétitives</li>
        <li>Support client amélioré, sans surcharge d’équipe</li>
      </ul>
      <p>
        Vous vous concentrez sur votre activité.<br>
        <strong>L’IA s’occupe du reste.</strong>
      </p>
    </div>

    <div class="card">
      <h3>Pour qui ?</h3>
      <ul>
        <li>Indépendants et petites entreprises</li>
        <li>Agences et services clients</li>
        <li>Entreprises internationales</li>
        <li>Équipes commerciales et support débordés</li>
      </ul>
      <p>
        Trois abonnements pensés pour accompagner votre croissance, du premier niveau d’automatisation
        jusqu’à une gestion quasi totale par l’IA.
      </p>
    </div>
  </section>

  <h2 class="section-title">Nos abonnements</h2>
  <p class="section-sub">Choisissez le niveau d’automatisation adapté à votre activité.</p>

  <section class="grid grid-3">

    <div class="card">
      <div class="tag">Starter AI</div>
      <h3>🚀 Starter AI</h3>
      <p class="price">25,99 € / mois</p>
      <p>L’essentiel pour commencer à automatiser vos emails.</p>
      <ul>
        <li>Réponses automatiques</li>
        <li>Détection d’intention (information, plainte, candidature…)</li>
        <li>Personnalisation du ton (professionnel, amical, neutre…)</li>
        <li>Gestion des emails répétitifs</li>
      </ul>
      <a class="button" href="https://buy.stripe.com/test_eVq6oJglN0Mm6c8eNkcV200">Souscrire à Starter AI</a>
    </div>

    <div class="card">
      <div class="tag">Smart AI</div>
      <h3>💡 Smart AI</h3>
      <p class="price">41,99 € / mois</p>
      <p>Votre assistant devient un véritable collaborateur intelligent.</p>
      <ul>
        <li>Toutes les fonctions Starter AI</li>
        <li>Traduction automatique (toutes langues)</li>
        <li>Analyse avancée du contenu</li>
        <li>Réponses longues, pertinentes et structurées</li>
        <li>Intégration de liens, documents et ressources</li>
      </ul>
      <a class="button" href="https://buy.stripe.com/test_fZufZj7PhfHg9okcFccV202">Souscrire à Smart AI</a>
    </div>

    <div class="card">
      <div class="tag">Pro AI</div>
      <h3>👑 Pro AI</h3>
      <p class="price">55,99 € / mois</p>
      <p>L’automatisation totale, sans limites.</p>
      <ul>
        <li>Toutes les fonctions Smart AI</li>
        <li>Personnalisation illimitée</li>
        <li>Gestion automatique des rendez-vous</li>
        <li>Intégration calendrier (créneaux, alternatives, confirmations)</li>
        <li>Résumé IA des échanges</li>
        <li>Gestion multi-boîtes mail</li>
        <li>Routage intelligent vers un humain si nécessaire</li>
      </ul>
      <p class="danger">Lien Stripe Pro à ajouter.</p>
      <a class="button secondary" href="#">Prochainement disponible</a>
    </div>

  </section>

  <h2 class="section-title">Contact</h2>
  <section class="card contact">
    <p>Pour une démonstration ou un accompagnement personnalisé :</p>
    <p><strong>Email :</strong> aaxeldiomande@gmail.com</p>
    <p><strong>Téléphone :</strong> +33 7 51 27 02 43</p>
    <p><strong>Téléphone :</strong> +33 6 98 66 16 59</p>
  </section>

</main>

</body>
</html>
