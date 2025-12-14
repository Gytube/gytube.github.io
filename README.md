# Gytube.github.io

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DELATTRE François</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #2c3e50;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #34495e;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      width: 90%;
      max-width: 1000px;
      margin: 20px auto;
    }
    .section-title {
      text-align: center;
      margin-bottom: 20px;
      font-size: 1.8em;
      color: #2c3e50;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.03);
    }
    .card h3 {
      margin-top: 0;
      color: #2980b9;
    }
    footer {
      background: #34495e;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Portfolio de François</h1>
    <p>Bienvenue sur mon espace personnel où je partage mes projets et logiciels</p>
  </header>

  <nav>
    <a href="#projets">Projets</a>
    <a href="#logiciels">Logiciels</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="projets">
      <h2 class="section-title">Mes Projets</h2>
      <div class="projects">
        <div class="card">
          <h3>Serveur de stockage de fichiers à distance (FTP/SFTP) + HTTP pour l'interface</h3>
          <p>Ce projet personnel a pour but de me faciliter le partage de fichiers entre mes différents appareils à domicile sur réseau local ou à l'extérieur via VPN (facultatif mais plus sûr).</p>
        </div>
        <div class="card">
          <h3>Bot de trading Binance</h3>
          <p>En utilisant l'API Binance, le code importe des données et indicateurs d'une devise choisie et envoie des requêtes (achat, vente, emprunts, etc...)
            en fonction de ces données.
          </p>
        </div>
        <!-- Ajoute d'autres projets ici -->
      </div>
    </section>

    <section id="logiciels">
      <h2 class="section-title">Mes Logiciels</h2>
      <div class="projects">
        <div class="card">
          <h3>Autoclicker</h3>
          <p>Petit logiciel permettant d'activer le clic automatique de la souris avec une fréquence réglable.</p>
        </div>
        <div class="card">
          <h3>Photovoltaïc</h3>
          <p>Application ayant pour but de gérer des installations de panneaux solaires</p>
        </div>
        <!-- Ajoute d'autres logiciels ici -->
      </div>
    </section>

    <section id="contact" style="color: white">
      <h2 class="section-title">Contact</h2>
      <p style="text-align:center;">Tu peux me contacter à : <strong>fdelattre12@gmail.com</strong></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 DELATTRE François</p>
  </footer>
</body>
</html>
