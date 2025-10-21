# CJDC
Association 
<!doctype html>

<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Association CJDC Mali</title>
  <style>
    :root{--accent:#2d88ff}
    body{font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; margin:0; background:#f7f9fc; color:#222}
    header{background:white; padding:12px 16px; box-shadow:0 1px 4px rgba(0,0,0,0.06); display:flex; align-items:center; gap:12px}
    .logo{width:48px;height:48px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#1b6edd);display:flex;align-items:center;justify-content:center;color:white;font-weight:700}
    .container{max-width:980px;margin:24px auto;padding:0 16px}
    .grid{display:grid;grid-template-columns:1fr 360px;gap:18px}
    .card{background:white;padding:14px;border-radius:10px;box-shadow:0 6px 18px rgba(14,30,37,0.04)}
    .aside .contact{display:flex;flex-direction:column;gap:10px}
    .btn{display:inline-block;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:600}
    .mailto{background:var(--accent);color:white}
    footer{max-width:980px;margin:24px auto;padding:8px 16px;color:#666}
    @media (max-width:880px){.grid{grid-template-columns:1fr} .aside{order:2}}
  </style>
</head>
<body>
  <header>
    <div class="logo">CJDC</div>
    <div>
      <strong>Association CJDC Mali</strong><br>
      <small>Les publications Facebook de l’association s’affichent automatiquement ci-dessous</small>
    </div>
  </header>  <main class="container">
    <div class="grid">
      <section class="card main">
        <h2>Fil d'actualité</h2>
        <p>Ci-dessous s'affiche la timeline officielle de la page Facebook de l’Association CJDC Mali.</p><div id="fb-root"></div>

    <!-- Facebook Page Plugin -->
    <div class="fb-page" 
         data-href="https://www.facebook.com/CJDC.Mali" 
         data-tabs="timeline" 
         data-width="" 
         data-height="600" 
         data-small-header="false" 
         data-adapt-container-width="true" 
         data-hide-cover="false" 
         data-show-facepile="true">
      <blockquote cite="https://www.facebook.com/CJDC.Mali" class="fb-xfbml-parse-ignore">
        <a href="https://www.facebook.com/CJDC.Mali">Visiter la page Facebook CJDC Mali</a>
      </blockquote>
    </div>

    <noscript>
      <div style="margin-top:12px;padding:12px;background:#fff3cd;border-radius:8px;color:#856404">
        Le plugin Facebook ne peut pas se charger. <br>
        Vous pouvez <a href="https://www.facebook.com/CJDC.Mali" target="_blank">visiter la page Facebook ici</a> ou nous contacter par e-mail.
      </div>
    </noscript>
  </section>

  <aside class="aside">
    <div class="card contact">
      <h3>Contact</h3>
      <p>Pour toute question ou collaboration, contactez-nous :</p>

      <p><a id="mailtoLink" class="btn mailto" href="mailto:associationcjdc@gmail.com?subject=Contact depuis le site CJDC Mali">Envoyer un e-mail</a></p>

      <p>
        <strong>Téléphone :</strong><br>
        +223 00 00 00 00
      </p>

      <p>
        <strong>Adresse :</strong><br>
        Bamako, Mali
      </p>
    </div>

    <div class="card">
      <h4>À propos de CJDC Mali</h4>
      <p>Le CJDC est une association malienne œuvrant pour la protection de l’environnement et le développement communautaire. Retrouvez nos actualités, actions et campagnes directement depuis cette page.</p>
    </div>
  </aside>
</div>

  </main>  <footer>
    <small>© CJDC Mali — Site connecté à la page Facebook officielle. Pour toute question : associationcjdc@gmail.com</small>
  </footer>  <script>
    (function(d, s, id) {
      var js, fjs = d.getElementsByTagName(s)[0];
      if (d.getElementById(id)) return;
      js = d.createElement(s); js.id = id;
      js.src = "https://connect.facebook.net/fr_FR/sdk.js#xfbml=1&version=v17.0";
      fjs.parentNode.insertBefore(js, fjs);
    }(document, 'script', 'facebook-jssdk'));
  </script></body>
</html>
