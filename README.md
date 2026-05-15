<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Essenza Perfumes</title>

  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
  <link rel="stylesheet" href="../css/style.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">

      <a class="navbar-brand fw-bold" href="#">Essenza</a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="menu">

        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" href="#">Início</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#produtos">Perfumes</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="./contato.html">Contato</a>
          </li>
        </ul>

        <form class="d-flex" role="search">
          <input class="form-control me-2" type="search" placeholder="Buscar">
          <button class="btn btn-outline-light" type="submit">Pesquisar</button>
        </form>

      </div>
    </div>
  </nav>
  <div class="carro">
    <div id="carouselExampleDark" class="carousel carousel-dark slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
          aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
          <img src="../html/img/242209286205341033.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Lattafa Musaman White Intense</h5>
            <p>Elegância e intensidade em cada fragrância.</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img src="../html/img/486881409741500310.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>J'Dore Dior</h5>
            <p>Elegância e intensidade luxuoso em cada fragrância.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../html/img/Smell Good with these Luxury Perfume Collection That Smells Expensive ✨.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Valentino</h5>
            <p>Elegância e intensidade luxuoso em cada fragrância.</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
  <section class="bg-dark text-light text-center d-flex align-items-center"
    style="height: 100vh; background: linear-gradient(135deg, #1a1a1a, #2b1b3a);">

    <div class="container">

      <h1 class="display-3 fw-bold">
        Essenza Perfumes
      </h1>

      <p class="lead text-secondary mt-3">
        Descubra fragrâncias únicas que combinam com o seu estilo.
      </p>

      <a href="#produtos" class="btn btn-outline-light btn-lg mt-4">
        Ver Perfumes
      </a>


    </div>
  </section>
  <section id="produtos" class="py-5 bg-light">
    <div class="container text-center">

      <h2 class="mb-5 fw-bold">Perfumes Femininos</h2>

      <div class="row g-4">

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (2).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Valentino Donna Born In Roma Intense</h5>
              <p class="card-text">Moderno, sofisticado e intenso.</p>
              <p class="fw-bold text-dark">R$ 899,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (7).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Lancôme La Vie Est Belle</h5>
              <p class="card-text">Elegante, feminino e clássico.</p>
              <p class="fw-bold text-dark">R$ 590,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (8).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Carolina Herrera Good Girl</h5>
              <p class="card-text">Marcante, sensual e luxuoso.</p>
              <p class="fw-bold text-dark">R$ 950,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

      </div>

    </div>
  </section>
  <section id="masculinos" class="py-5 bg-white">
    <div class="container text-center">

      <h2 class="mb-5 fw-bold">Perfumes Masculinos</h2>

      <div class="row g-4">

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (9).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Dior Sauvage</h5>
              <p class="card-text">Fresco, amadeirado e moderno.</p>
              <p class="fw-bold text-dark">R$ 799,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (10).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Bleu de Chanel</h5>
              <p class="card-text">Elegante, sofisticado e versátil.</p>
              <p class="fw-bold text-dark">R$ 650,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="card shadow-sm">
            <img src="./img/Design sem nome (11).jpg" alt="">
            <div class="card-body">
              <h5 class="card-title">Acqua di Giò Profumo</h5>
              <p class="card-text">Intenso, fresco e aquático.</p>
              <p class="fw-bold text-dark">R$ 1.560,90</p>
              <a href="#" class="btn btn-dark">Comprar</a>
            </div>
          </div>
        </div>

      </div>
      <!-- FOOTER -->
    </div>
  </section>
  <footer class="bg-dark text-light text-center py-3">
    <p class="mb-0">&copy; 2026 Essenza Perfumes - Todos os direitos reservados</p>
  </footer>

</body>

</html>
