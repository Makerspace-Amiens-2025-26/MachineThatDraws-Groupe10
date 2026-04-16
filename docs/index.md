<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Machine That Draws | Groupe 10</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <link href="https://fonts.bunny.net/css?family=plus-jakarta-sans:400,600,800" rel="stylesheet" />

    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light fixed-top shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold text-primary" href="#">GROUPE 10</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#projet">Le Projet</a></li>
                    <li class="nav-item"><a class="nav-link" href="#conception">Conception 3D</a></li>
                    <li class="nav-item"><a class="nav-link" href="#electronique">Électronique</a></li>
                    <li class="nav-item"><a class="nav-link" href="#etapes">Étapes</a></li>
                    <li class="nav-item"><a class="nav-link" href="#equipe">L'Équipe</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero-gradient text-center">
        <div class="container" data-aos="zoom-in">
            <h1 class="display-2 fw-bolder mb-3">Machine That Draws</h1>
            <p class="lead mb-5">Le futur du dessin automatisé par le Groupe 10.</p>
            
            <div class="d-flex flex-column flex-md-row justify-content-center gap-3">
                <a href="https://cad.onshape.com/documents/8b8c43a593a6e22dfd5bf280/w/f337884a351008c809d7df22/e/a178174cd77496a5cd270f55?renderMode=0&uiState=69d8e3a393e9b9c5b111a1c9" class="btn btn-primary fs-5 px-4 py-2 rounded-pill">Notre projet sur Onshape</a>
                <a href="https://github.com/Makerspace-Amiens-2025-26/MachineThatDraws-Groupe10" class="btn btn-outline-light fs-5 px-4 py-2 rounded-pill">Notre repo GitHub</a>
            </div>
        </div>
    </header>

    <section id="projet" class="container py-5 mt-5">
        <div class="row align-items-center g-5">
            <div class="col-lg-6" data-aos="fade-right">
                <h2 class="section-title text-start">Le <span>Projet</span></h2>
                <p>Bienvenue sur le site du Groupe 10. Notre projet consiste à concevoir une machine capable de reproduire des dessins complexes avec une précision robotique.</p>
                <div class="row mt-4">
                    <div class="col-6">
                        <div class="p-3 border-start border-4 border-primary">
                            <h5 class="fw-bold">Objectifs</h5>
                            <p class="small text-muted">Précision, fluidité et design modulaire.</p>
                        </div>
                    </div>
                    <div class="col-6">
                        <div class="p-3 border-start border-4 border-accent">
                            <h5 class="fw-bold">Techno</h5>
                            <p class="small text-muted">Impression 3D & Contrôle Arduino.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 text-center" data-aos="fade-left">
                <div class="p-4 bg-white shadow rounded-4">
                    <img src="images/affiche-groupe10.jpg" class="img-fluid rounded-3" alt="Affiche du groupe">
                    <p class="mt-3 fw-bold">Affiche Officielle</p>
                </div>
            </div>
        </div>
    </section>

    <section id="conception" class="bg-light py-5">
        <div class="container text-center">
            <h2 class="section-title">Modélisation <span>3D Interactive</span></h2>
            <p class="mb-5">Explorez notre assemblage mécanique directement dans votre navigateur.</p>
            
            <div class="modern-card p-2 shadow-lg mb-5" data-aos="zoom-in">
                <iframe src="https://modelembedder.net/embed?did=8b8c43a593a6e22dfd5bf280&wvm=v&wvmid=01f7cd1fe38b59d1cf645123&eid=a178174cd77496a5cd270f55&elementType=ASSEMBLY" 
                        width="100%" height="500" frameborder="0" allowfullscreen class="rounded-3"></iframe>
            </div>

            <div class="row g-4 text-start">
                <div class="col-md-6" data-aos="fade-up">
                    <div class="modern-card p-4">
                        <i data-lucide="box" class="text-primary mb-3" size="40"></i>
                        <h4>Conception sur Onshape</h4>
                        <p>L'intégralité des pièces a été modélisée pour permettre une maintenance facile et une rigidité maximale lors du tracé.</p>
                    </div>
                </div>
                <div class="col-md-6" data-aos="fade-up" data-aos-delay="100">
                    <div class="modern-card p-4">
                        <i data-lucide="wrench" class="text-primary mb-3" size="40"></i>
                        <h4>Fabrication Mécanique</h4>
                        <p>Utilisation de l'impression 3D pour les supports et de profilés aluminium pour le châssis.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="electronique" class="container py-5 text-center">
        <div class="pcb-section bg-dark text-white p-5" data-aos="flip-up">
            <h2 class="fw-bold mb-4">Électronique & <span class="text-info">PCB</span></h2>
            <p class="mb-4">Notre système repose sur un PCB personnalisé conçu sous KiCad.</p>
            <div class="d-flex justify-content-center gap-3">
                <a href="#" class="btn btn-info rounded-pill px-4 fw-bold">Fichiers KiCad</a>
                <a href="#" class="btn btn-outline-light rounded-pill px-4">Schématique</a>
            </div>
            <div class="mt-5 text-info">
                <i data-lucide="cpu" size="80"></i>
            </div>
        </div>
    </section>

    <section id="etapes" class="container py-5">
        <h2 class="section-title">Les Étapes du <span>Projet</span></h2>
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="timeline-item" data-aos="fade-left">
                    <h5>Analyse du besoin</h5>
                    <p class="text-muted">Rédaction du CDC et choix des composants (moteurs Nema 17, courroies GT2).</p>
                </div>
                <div class="timeline-item" data-aos="fade-left" data-aos-delay="100">
                    <h5>Modélisation CAO</h5>
                    <p class="text-muted">Conception sur Onshape et vérification des interférences.</p>
                </div>
                <div class="timeline-item" data-aos="fade-left" data-aos-delay="200">
                    <h5>Développement & Tests</h5>
                    <p class="text-muted">Programmation du firmware et premiers tests de déplacement.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="equipe" class="bg-light py-5 text-center">
        <div class="container">
            <h2 class="section-title">L'<span>Équipe</span></h2>
            <div class="row g-4 justify-content-center">
                <div class="col-md-3" data-aos="zoom-in">
                    <div class="modern-card p-4">
                        <div class="bg-primary rounded-circle mx-auto mb-3 d-flex align-items-center justify-content-center text-white" style="width: 70px; height: 70px;">
                            <i data-lucide="user"></i>
                        </div>
                        <h5>Membre 1</h5>
                        <p class="small text-primary fw-bold">Chef de Projet</p>
                    </div>
                </div>
                <div class="col-md-3" data-aos="zoom-in" data-aos-delay="100">
                    <div class="modern-card p-4">
                        <div class="bg-primary rounded-circle mx-auto mb-3 d-flex align-items-center justify-content-center text-white" style="width: 70px; height: 70px;">
                            <i data-lucide="user"></i>
                        </div>
                        <h5>Membre 2</h5>
                        <p class="small text-primary fw-bold">Expert Électronique</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-5">
        <div class="container text-center">
            <p class="mb-1 fw-bold">Makerspace Amiens 2025-26 - Groupe 10</p>
            <p class="small opacity-50">Site réalisé avec passion et précision.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        lucide.createIcons();
        AOS.init({ duration: 1000, once: true });
    </script>
</body>
</html>
