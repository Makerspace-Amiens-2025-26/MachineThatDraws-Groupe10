<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>G10 | Machine That Draws</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="https://fonts.bunny.net/css?family=plus-jakarta-sans:400,700" rel="stylesheet" />

    <style>
        :root { --primary-color: #00d2ff; --secondary-color: #3a7bd5; }
        body { font-family: 'Plus Jakarta Sans', sans-serif; scroll-behavior: smooth; background-color: #fcfcfc; }
        
        /* Style Premium pour le Header */
        .hero {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
            color: white; padding: 120px 0 80px; clip-path: polygon(0 0, 100% 0, 100% 90%, 0% 100%);
        }

        /* Cartes de section */
        .feature-card {
            border: none; border-radius: 20px; transition: 0.3s;
            background: white; box-shadow: 0 10px 30px rgba(0,0,0,0.05);
        }
        .feature-card:hover { transform: translateY(-10px); box-shadow: 0 15px 35px rgba(0,0,0,0.1); }

        /* Badge pour les liens */
        .btn-custom {
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
            border: none; color: white; border-radius: 30px; padding: 10px 25px;
        }

        .section-title { font-weight: 700; margin-bottom: 40px; position: relative; }
        .section-title::after { content: ''; width: 50px; height: 5px; background: var(--primary-color); position: absolute; bottom: -10px; left: 0; }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">GROUPE 10</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#projet">Projet</a></li>
                    <li class="nav-item"><a class="nav-link" href="#conception">Conception</a></li>
                    <li class="nav-item"><a class="nav-link" href="#electronique">Électronique</a></li>
                    <li class="nav-item"><a class="nav-link" href="#etapes">Étapes</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero text-center">
        <div class="container" data-aos="fade-up">
            <h1 class="display-3 fw-bold">Machine That Draws</h1>
            <p class="lead opacity-75">L'alliance de la mécanique de précision et du code.</p>
            <div class="mt-4">
                <a href="#projet" class="btn btn-custom me-2">Explorer le projet</a>
                <a href="https://github.com/votre-lien" class="btn btn-outline-light rounded-pill">GitHub</a>
            </div>
        </div>
    </header>

    <section id="projet" class="container py-5">
        <div class="row align-items-center">
            <div class="col-md-6" data-aos="fade-right">
                <h2 class="section-title">Présentation du Projet</h2>
                <p>Notre machine est conçue pour transformer des fichiers numériques en dessins physiques avec une précision millimétrique.</p>
                <h4 class="mt-4">Nos Objectifs :</h4>
                <ul class="list-unstyled">
                    <li><i data-lucide="check-circle" class="text-success me-2"></i> Précision des tracés</li>
                    <li><i data-lucide="check-circle" class="text-success me-2"></i> Structure robuste en impression 3D</li>
                    <li><i data-lucide="check-circle" class="text-success me-2"></i> Interface utilisateur intuitive</li>
                </ul>
            </div>
            <div class="col-md-6" data-aos="fade-left">
                <div class="feature-card p-2 text-center">
                    <img src="ton-affiche.jpg" alt="Affiche Groupe 10" class="img-fluid rounded-4 shadow">
                    <p class="mt-2 text-muted">Affiche officielle du groupe</p>
                </div>
            </div>
        </div>
    </section>

    <section id="conception" class="bg-light py-5">
        <div class="container">
            <h2 class="section-title">Conception & Fabrication</h2>
            <div class="row g-4">
                <div class="col-md-6" data-aos="zoom-in">
                    <div class="feature-card p-4 h-100">
                        <i data-lucide="box" class="mb-3 text-primary" size="40"></i>
                        <h3>Fichiers 3D</h3>
                        <p>Visualisez nos modèles CAO réalisés sur [Nom du logiciel].</p>
                        <a href="#" class="btn btn-sm btn-outline-primary">Voir sur le dépôt</a>
                    </div>
                </div>
                <div class="col-md-6" data-aos="zoom-in" data-aos-delay="100">
                    <div class="feature-card p-4 h-100">
                        <i data-lucide="wrench" class="mb-3 text-primary" size="40"></i>
                        <h3>Fabrication</h3>
                        <p>Impression 3D, découpe laser et assemblage mécanique.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        lucide.createIcons();
        AOS.init({ duration: 800, once: true });
    </script>
</body>
</html>
