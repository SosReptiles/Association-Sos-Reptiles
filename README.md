[formations.html](https://github.com/user-attachments/files/23503136/formations.html)
[contact.html](https://github.com/user-attachments/files/23503127/contact.html)
<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contact — SOS Reptiles</title>
  <link rel="icon" href="images/logo_refuge.svg" />![logo_petits_potes](https://github.com/user-attachments/assets/48935edd-2f5e-43e0-8266-e964dedca2f2)![logo_refuge](https://github.com/user-attachments/assets/9974f45d-cd69-4175-a369-47fb3e6815ba)![sample_turtle2](https://github.com/user-attachments/assets/b51d736f-f42e-47cf-8d87-b1bab1db04c0)
![sample_turtle1](https://github.com/user-attachments/assets/75d36b3c-e4c1-427e-9b7a-183684a3a9a4)[main.js](https://github.com/user-attachments/files/23503141/main.js)[petits-potes.html](https://github.com/user-attachments/files/23503146/petits-potes.html)[refuge.html](https://github.com/user-attachments/files/23503147/refuge.html)

// Menu mobile
const toggle = document.querySelector('.menu-toggle');
const menu = document.getElementById('menu');
if (toggle && menu) {
  toggle.addEventListener('click', () => {
    const isOpen = menu.classList.toggle('open');
    toggle.setAttribute('aria-expanded', isOpen);
  });
}
// Année footer
const yearSpan = document.getElementById('year');
if (yearSpan) yearSpan.textContent = new Date().getFullYear();

// Formulaire (contact)
const form = document.querySelector('.contact-form');
if (form) {
  form.addEventListener('submit', (e) => {
    e.preventDefault();
    const note = document.getElementById('form-note');
    if (note) {
      note.textContent = '✅ Merci ! Votre message a été pris en compte (démo).';
      setTimeout(()=> note.textContent = '', 4000);
    }
    form.reset();
  });
}


![sample_snake2](https://github.com/user-attachments/assets/b6fcee02-f3e9-42b7-897c-3471c9639c83)[index.html](https://github.com/user-attachments/files/23503139/index.html)<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Accueil — SOS Reptiles</title>
  <link rel="icon" href="images/logo_refuge.svg" />
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  
    <header>
      <div class="container nav">
        <a class="brand" href="index.html">
          <img src="images/logo_refuge.svg" alt="Logo SOS Reptiles" />
          <span>SOS Reptiles</span>
        </a>
        <button class="btn menu-toggle" aria-expanded="false" aria-controls="menu">Menu</button>
        <nav id="menu" class="menu" aria-label="Navigation principale">
          <a href="refuge.html" class="">Le Refuge</a>
          <a href="formations.html" class="">Pôle formation</a>
          <a href="petits-potes.html" class="">Les Petits Potes</a>
          <a href="contact.html" class="">Contact</a>
        </nav>
      </div>
    </header>
    
  
    <section class="hero home">
      <div class="container hero-inner">
        <h1>SOS Reptiles</h1>
        <p>Refuge, formations et activités pédagogiques pour une terrariophilie responsable.</p>
        <div class="cta">
          <a class="btn primary" href="refuge.html">Voir les animaux à l’adoption</a>
          <a class="btn" href="formations.html">Découvrir nos formations</a>
        </div>
      </div>
    </section>
    <section class="section container grid-3 intro-cards">
      <a class="card link" href="refuge.html"><h3>Le Refuge</h3><p>Adoptions responsables • RDV obligatoires le dimanche matin.</p></a>
      <a class="card link" href="formations.html"><h3>Pôle formation</h3><p>CDC, pompiers et modules à thème.</p></a>
      <a class="card link" href="petits-potes.html"><h3>Les Petits Potes</h3><p>Animations mercredi & samedi, séjours et fiche d’inscription.</p></a>
    </section>
    
  
    <footer>
      <div class="container footer-wrap">
        <span>© <span id="year"></span> SOS Reptiles</span>
        <nav class="foot">
          <a href="#">Mentions légales</a>
          <a href="#">Confidentialité</a>
        </nav>
      </div>
    </footer>
    
  <script src="js/main.js"></script>
</body>
</html>

![sample_snake1](https://github.com/user-attachments/assets/b61d92e5-80d2-47e6-bb96-c51b11c370b7)
![sample_other1](https://github.com/user-attachments/assets/a117813f-4b98-4d8a-b480-88838ae9f7ec)
![sample_lizard2](https://github.com/user-attachments/assets/3d97da58-022a-40b7-86b2-67b380a1ab24)
![sample_lizard1](https://github.com/user-attachments/assets/f0f70fe1-587d-4bb7-b46b-c1c79525ccc9)


  <link rel="stylesheet" href="css/style.css" />[style.css](https://github.com/user-attachments/files/23503129/style.css)
:root{
  --bg:#f7f4ee;--card:#ffffff;--muted:#5b6470;--text:#1f2937;
  --accent:#2e7d32;--accent-2:#2ea3a5;--beige:#f3efe7;--green-soft:#dfeee2[fiche_adoption.pdf](https://github.com/user-[Uploading formati<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pôle formation — SOS Reptiles</title>
  <link rel="icon" href="images/logo_refuge.svg" />
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  
    <header>
      <div class="container nav">
        <a class="brand" href="index.html">
          <img src="images/logo_refuge.svg" alt="Logo SOS Reptiles" />
          <span>SOS Reptiles</span>
        </a>
        <button class="btn menu-toggle" aria-expanded="false" aria-controls="menu">Menu</button>
        <nav id="menu" class="menu" aria-label="Navigation principale">
          <a href="refuge.html" class="">Le Refuge</a>
          <a href="formations.html" class="active">Pôle formation</a>
          <a href="petits-potes.html" class="">Les Petits Potes</a>
          <a href="contact.html" class="">Contact</a>
        </nav>
      </div>
    </header>
    
  
    <section class="hero page formations-hero">
      <div class="container"><h1>Pôle formation</h1><p>Formations pour particuliers, professionnels et secours.</p></div>
    </section>
    <section class="section container grid-3">
      <div class="card">
        <h2>CDC — Certificat de capacité</h2>
        <p>Parcours théorique et pratique pour constituer/renforcer votre dossier : espèces, biosécurité, bien‑être.</p>
        <div class="cta"><a class="btn" href="#">Programme & tarifs (PDF)</a></div>
      </div>
      <div class="card">
        <h2>Pompiers / secours</h2>
        <p>Reconnaissance d’espèces, capture sécurisée et procédures d’intervention pour équipes d’urgence.</p>
        <div class="cta"><a class="btn" href="contact.html">Demander un devis</a></div>
      </div>
      <div class="card">
        <h2>Formations à thème</h2>
        <p>Terrariophilie, nutrition, pathologies courantes, enrichissement, documentation réglementaire.</p>
        <div class="cta"><a class="btn" href="#">Calendrier des sessions</a></div>
      </div>
    </section>
    
  
    <footer>
      <div class="container footer-wrap">
        <span>© <span id="year"></span> SOS Reptiles</span>
        <nav class="foot">
          <a href="#">Mentions légales</a>
          <a href="#">Confidentialité</a>
        </nav>
      </div>
    </footer>
    
  <script src="js/main.js"></script>
</body>
</html>ons.html…]()
attachments/files/23503132/fiche_adoption.pdf)[fiche_inscription_petits_potes.pdf](https://github.com/user-attachments/files/23503133/fiche_inscription_petits_potes.pdf)

}
*{box-sizing:border-box}
html,body{margin:0;padding:0;background:var(--bg);color:var(--text);
  font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,"Helvetica Neue",Arial}
a{color:var(--accent);text-decoration:none}
a:hover{opacity:.9}

.container{max-width:1100px;margin:0 auto;padding:0 20px}
header{position:sticky;top:0;background:rgba(255,255,255,.9);backdrop-filter:blur(8px);
  border-bottom:1px solid #eae6dc;z-index:10}
.nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
.brand{display:flex;align-items:center;gap:12px;font-weight:700;color:var(--text)}
.brand img{height:44px;width:auto;border-radius:8px}
.menu{display:flex;gap:18px}
.menu a{color:var(--text);opacity:.9;padding:8px 6px;border-radius:8px}
.menu a.active,.menu a:hover{background:linear-gradient(135deg,rgba(46,125,50,.12),rgba(46,163,165,.12))}
.menu-toggle{display:none}

@media (max-width:780px){
  .menu{display:none}.menu.open{display:flex;flex-direction:column;gap:10px;padding:10px 0}
  .menu-toggle{display:block}
}

.hero{color:#14321a;text-align:center}
.hero.home{padding:80px 0 56px;background:radial-gradient(80% 120% at 20% 0%,rgba(46,125,50,.15),transparent),radial-gradient(100% 100% at 100% 100%,rgba(46,163,165,.18),transparent),var(--beige)}
.hero.page{padding:70px 0 40px;background:linear-gradient(135deg,rgba(46,125,50,.15),rgba(46,163,165,.15))}
.hero .cta{margin-top:16px;display:flex;gap:12px;flex-wrap:wrap;justify-content:center}

.section{padding:48px 0}
.muted{color:var(--muted)}

.grid-2{display:grid;grid-template-columns:repeat(2,1fr);gap:18px}
.grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
@media (max-width:900px){.grid-2{grid-template-columns:1fr}.grid-3{grid-template-columns:1fr 1fr}}
@media (max-width:560px){.grid-3{grid-template-columns:1fr}}

.card{background:var(--card);border:1px solid #efe9de;border-radius:18px;padding:20px;
  box-shadow:0 6px 18px rgba(149,157,165,0.15);transition:all .25s ease}
.card:hover{transform:translateY(-3px);box-shadow:0 10px 26px rgba(149,157,165,0.22)}

.card.link{display:block}

.btn{display:inline-flex;align-items:center;gap:8px;padding:12px 16px;border-radius:12px;
  border:1px solid #d6e7d8;background:#f9fbf9;color:var(--text);cursor:pointer}
.btn.primary{background:linear-gradient(135deg,var(--accent),var(--accent-2));border:none;color:white;font-weight:600;
  position:relative;overflow:hidden;transition:transform .2s ease,box-shadow .3s ease}
.btn.primary::after{content:"";position:absolute;top:0;left:-100%;width:200%;height:100%;
  background:linear-gradient(120deg,transparent,rgba(255,255,255,.35),transparent);transition:all .8s ease}
.btn.primary:hover::after{left:100%}
.btn.primary:hover{transform:translateY(-2px);box-shadow:0 0 18px rgba(46,163,165,.25),0 0 28px rgba(46,125,50,.25)}

.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
.thumb{background:var(--green-soft);border:1px solid #d7e7da;border-radius:14px;padding:10px;text-align:center}
.thumb img{width:100%;height:auto;border-radius:10px;display:block}
.thumb figcaption{font-size:.95rem;color:#374151;margin-top:6px}

.check{padding-left:18px}
.check li{margin:8px 0}

.petits-potes-logo{text-align:center;margin-bottom:12px}
.petits-potes-logo img{max-width:220px;border-radius:12px;display:block;margin:0 auto;height:auto}

footer{padding:28px 0;color:#6b7280;border-top:1px solid #eae6dc;background:#f8f6f1}
.footer-wrap{display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}
.foot{display:flex;gap:12px}

.contact-form .row{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.contact-form input,.contact-form textarea{width:100%;padding:12px 14px;border-radius:12px;border:1px solid #e3ded2;background:#fff;color:#1f2937}
.contact-form .note{display:inline-block;margin-left:10px;color:#6b7280}
@media (max-width:700px){.contact-form .row{grid-template-columns:1fr}}


</head>
<body>
  
    <header>
      <div class="container nav">
        <a class="brand" href="index.html">
          <img src="images/logo_refuge.svg" alt="Logo SOS Reptiles" />
          <span>SOS Reptiles</span>
        </a>
        <button class="btn menu-toggle" aria-expanded="false" aria-controls="menu">Menu</button>
        <nav id="menu" class="menu" aria-label="Navigation principale">
          <a href="refuge.html" class="">Le Refuge</a>
          <a href="formations.html" class="">Pôle formation</a>
          <a href="petits-potes.html" class="">Les Petits Potes</a>
          <a href="contact.html" class="active">Contact</a>
        </nav>
      </div>
    </header>
    
  
    <section class="hero page contact-hero">
      <div class="container"><h1>Contact</h1><p>Adoptions, formations, activités : écrivez‑nous.</p></div>
    </section>
    <section class="section container">
      <div class="card">
        <h2 id="rdv">Coordonnées</h2>
        <ul class="contacts">
          <li><strong>Prise en charge :</strong> <a href="mailto:sosreptiles@outlook.fr">sosreptiles@outlook.fr</a></li>
          <li><strong>Administratif :</strong> <a href="mailto:gestionsosreptiles@outlook.fr">gestionsosreptiles@outlook.fr</a></li>
          <li><strong>Téléphone :</strong> <a href="tel:+33641007330">06.41.00.73.30</a></li>
        </ul>
        <form class="contact-form">
          <div class="row">
            <input type="text" placeholder="Nom" required />
            <input type="email" placeholder="Email" required />
          </div>
          <input type="text" placeholder="Objet (Adoption / Formation / Petits Potes)" />
          <textarea placeholder="Votre message..." rows="6"></textarea>
          <button class="btn primary" type="submit">Envoyer</button>
          <span class="note" id="form-note" aria-live="polite"></span>
        </form>
      </div>
    </section>
    
  
    <footer>
      <div class="container footer-wrap">
        <span>© <span id="year"></span> SOS Reptiles</span>
        <nav class="foot">
          <a href="#">Mentions légales</a>
          <a href="#">Confidentialité</a>
        </nav>
      </div>
    </footer>
    
  <script src="js/main.js"></script>
</body>
</html>
