<!doctype html>
<html lang="it">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfolio — Flavio</title>
  <style>
    body{font-family:system-ui,Arial;margin:2rem}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:1rem}
    .card{border:1px solid #ddd;padding:1rem;border-radius:8px;text-align:left}
    .card h2{margin:0 0 .5rem 0}
    a{color:#0366d6;text-decoration:none}
  </style>
</head>
<body>
  <h1>Ciao — Le mie "cartelle"</h1>
  <p>Benvenuto: clicca sulle cartelle per aprire le pagine dei progetti.</p>

  <div class="grid">
    <div class="card">
      <h2><a href="./projects/">📁 Progetti Web</a></h2>
      <p>Repo e demo front-end</p>
    </div>

    <div class="card">
      <h2><a href="./data/">📁 Dati & Script</a></h2>
      <p>Script, notebook e dataset</p>
    </div>

    <div class="card">
      <h2><a href="./about/">📁 Info</a></h2>
      <p>Chi sono e contatti</p>
    </div>
  </div>
</body>
</html>
