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
<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contato - Essenza Perfumes</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link rel="stylesheet" href="../css/contato.css">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">

      <a class="navbar-brand fw-bold" href="./index.html">
        Essenza
      </a>

      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#menu">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="menu">

        <ul class="navbar-nav me-auto mb-2 mb-lg-0">

          <li class="nav-item">
            <a class="nav-link" href="./index.html">
              Início
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="./index.html#produtos">
              Perfumes
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link active" href="./contato.html">
              Contato
            </a>
          </li>

        </ul>

        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Buscar">
          <button class="btn btn-outline-light" type="submit">
            Pesquisar
          </button>
        </form>

      </div>
    </div>
  </nav>
  <section class="contato-hero d-flex align-items-center text-center">
    <div class="container">

      <h1 class="display-3 fw-bold">
        Entre em Contato
      </h1>

      <p class="lead mt-3">
        Tire dúvidas, envie sugestões ou fale com nossa equipe.
      </p>

    </div>
  </section>
  <section class="py-5 bg-light">

    <div class="container">

      <div class="row g-5">
        <div class="col-lg-7">

          <div class="card border-0 shadow-lg p-4">

            <h2 class="fw-bold mb-4">
              Fale Conosco
            </h2>

            <form>

              <div class="mb-3">
                <label class="form-label">
                  Nome
                </label>

                <input type="text" class="form-control" placeholder="Digite seu nome">
              </div>

              <div class="mb-3">
                <label class="form-label">
                  Email
                </label>

                <input type="email" class="form-control" placeholder="Digite seu email">
              </div>

              <div class="mb-3">
                <label class="form-label">
                  Assunto
                </label>

                <input type="text" class="form-control" placeholder="Digite o assunto">
              </div>

              <div class="mb-4">
                <label class="form-label">
                  Mensagem
                </label>

                <textarea class="form-control" rows="6"
                  placeholder="Digite sua mensagem"></textarea>
              </div>

              <button class="btn btn-dark btn-lg w-100">
                Enviar Mensagem
              </button>

            </form>

          </div>

        </div>
        <div class="col-lg-5">

          <div class="card border-0 shadow-lg p-4 h-100">

            <h2 class="fw-bold mb-4">
              Informações
            </h2>

            <div class="mb-4">

              <h5>
                <i class="bi bi-geo-alt-fill"></i>
                Endereço
              </h5>

              <p class="text-secondary">
                Goías - GO, Brasil
              </p>

            </div>

            <div class="mb-4">

              <h5>
                <i class="bi bi-envelope-fill"></i>
                Email
              </h5>

              <p class="text-secondary">
                contato@essenza.com
              </p>

            </div>

            <div class="mb-4">

              <h5>
                <i class="bi bi-telephone-fill"></i>
                Telefone
              </h5>

              <p class="text-secondary">
                (61) 4002-8922
              </p>

            </div>

            <div>

              <h5 class="mb-3">
                Redes Sociais
              </h5>

              <div class="d-flex gap-3">

                <a href="https://www.instagram.com/gerson_.xt/" class="social-icon">
                  <i class="bi bi-instagram"></i>
                </a>

                <a href="https://www.facebook.com/?locale=pt_BR" class="social-icon">
                  <i class="bi bi-facebook"></i>
                </a>

                <a href="https://web.whatsapp.com/" class="social-icon">
                  <i class="bi bi-whatsapp"></i>
                </a>

                <a href="https://x.com/?lang=pt" class="social-icon">
                  <i class="bi bi-twitter-x"></i>
                </a>

              </div>

            </div>

          </div>

        </div>

      </div>

    </div>

  </section>

  <!-- FOOTER -->
  <footer class="bg-dark text-light text-center py-4">

    <div class="container">

      <p class="mb-1">
        &copy;2026 Essenza Perfumes - Todos os direitos reservados
      </p>

      <small class="text-secondary">
        Elegância em cada fragrância.
      </small>

    </div>

  </footer>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>

</body>

</html>




