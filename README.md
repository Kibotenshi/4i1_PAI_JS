# 4i1_PAI_JS

Added index.html


<!DOCTYPE html>
<html lang="pl" data-bs-theme="dark">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="script.js"></script>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <div class="border border-white">
      <h1 class="d-flex justify-content-center m-3">Dziennik Praktyki zawodowej</h1>

      <ul
        class="nav nav-pills nav-fill gap-2 p-1 m-4 small bg-success rounded-5 shadow-sm"
        id="pillNav2"
        role="tablist"
        style="
          --bs-nav-link-color: var(--bs-white);
          --bs-nav-pills-link-active-color: var(--bs-success);
          --bs-nav-pills-link-active-bg: var(--bs-white);
        "
      >
        <li class="nav-item" role="presentation">
          <button
            class="nav-link active rounded-5"
            id="home-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="true"
          >
            Metryczka
          </button>
        </li>
        <li class="nav-item" role="presentation">
          <button
            class="nav-link rounded-5"
            id="profile-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="false"
          >
            Dziennik zajęć
          </button>
        </li>
        <li class="nav-item" role="presentation">
          <button
            class="nav-link rounded-5"
            id="contact-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="false"
          >
            Podsumowanie
          </button>
        </li>
      </ul>
      <div class="border border-success m-4">
        <h2 class="d-flex justify-content-center m-3">Wprowadź dane ucznia i praktyki</h2>
        <form class="row g-3 d-flex justify-content-center" action="#">
          <div class="col-md-5 d-flex justify-content-center m-4">
            <label for="name" class="form-label p-2 col-sm-4">Imię:</label>
            <input type="text" class="form-control" id="name" />
          </div>
          <div class="col-md-5 d-flex justify-content-center m-4">
            <label for="surname" class="form-label p-2 col-sm-4">Nazwisko:</label>
            <input type="text" class="form-control" id="surname" />
          </div>
          <div class="col-md-5 d-flex justify-content-center m-4">
            <label for="klass" class="form-label p-2 col-sm-4">Klasa:</label>
            <input type="text" class="form-control" id="klass" />
          </div>
          <div class="col-md-5 d-flex justify-content-center m-4">
            <label for="year_sch_1" class="form-label p-2 col-sm-4">Rok szkolny:</label>
            <input type="text" class="form-control" id="year_sch_1" />
          </div>
          <div class="col-md-5 d-flex justify-content-center m-4">
            <label for="place_1" class="form-label p-2 col-sm-4">Odbyte w:</label>
            <input type="text" class="form-control" id="place_1" />
          </div>

          <fieldset class="d-flex flex-wrap border border-success">
            <legend>Czas Trwania praktyki</legend>
            <div class="col-md- d-flex justify-content-center m-4">
              <label for="year_sch_2" class="form-label p-2 col-sm-5">Dzień rozpoczęcia:</label>
              <input type="text" class="form-control" id="year_sch_2" />
            </div>
            <div class="col-md-5 d-flex justify-content-center m-4">
              <label for="place_2" class="form-label p-2 col-sm-5">Dzień zakończenia:</label>
              <input type="text" class="form-control" id="place_2" />
            </div>
          </fieldset>

          <div class="col-12">
            <button type="submit" class="btn btn-primary">Zapisz dane</button>
          </div>
        </form>





        <!DOCTYPE html>
<html lang="pl">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Dziennik praktyki zawodowej</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        background-color: #1e1e1e;
        color: white;
      }
      .container {
        background-color: #2a2a2a;
        padding: 20px;
        border-radius: 10px;
        margin-top: 50px;
      }
      .btn-custom {
        background-color: #4caf50;
        color: white;
      }
      .text-hover {
            transition: transform 0.3s ease-in-out;
            display: inline-block; /* Zapobiega przesuwaniu sąsiednich elementów */
        }

        .text-hover:hover {
            transform: scale(1.2);
            color: aliceblue;
        }
    </style>
  </head>
  <body>
    <div class="container text-center">
      <h1 class="mb-4">Dziennik praktyki zawodowej</h2>
      <ul
        class="nav nav-pills nav-fill gap-2 p-1 m-4 small bg-success rounded-5 shadow-sm"
        id="pillNav2"
        role="tablist"
        style="
          --bs-nav-link-color: var(--bs-white);
          --bs-nav-pills-link-active-color: var(--bs-success);
          --bs-nav-pills-link-active-bg: var(--bs-white);
        "
      >
        <li class="nav-item" role="presentation">
          <button
            class="text-hover nav-link rounded-5"
            id="home-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="true"
          >
            Metryczka
          </button>
        </li>
        <li class="text-hover nav-item" role="presentation">
          <button
            class="nav-link rounded-5"
            id="profile-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="false"
          >
            Dziennik zajęć
          </button>
        </li>
        <li class="nav-item" role="presentation">
          <button
            class="text-hover nav-link rounded-5"
            id="contact-tab2"
            data-bs-toggle="tab"
            type="button"
            role="tab"
            aria-selected="false"
          >
            Podsumowanie
          </button>
        </li>
      </ul>

      <div class="border border-success p-3 rounded">
        <h3 class="mb-3">Wprowadź dane ucznia i praktyki</h4>
        <form>
          <div class="row mb-3">
            <div class="col">
              <input type="text" class="form-control" placeholder="Imię" />
            </div>
            <div class="col">
              <input type="text" class="form-control" placeholder="Nazwisko" />
            </div>
          </div>
          <div class="row mb-3">
            <div class="col">
              <input type="text" class="form-control" placeholder="Klasa" />
            </div>
            <div class="col">
              <input
                type="text"
                class="form-control"
                placeholder="Rok szkolny"
              />
            </div>
          </div>
          <div class="mb-3">
            <input type="text" class="form-control" placeholder="Odbytej w" />
          </div>
          <div class="border p-3 rounded">
            <label class="form-label">Czas trwania praktyki</label>
            <div class="row">
              <div class="col">
                <input type="date" class="form-control" />
              </div>
              <div class="col">
                <input type="date" class="form-control" />
              </div>
            </div>
          </div>
          <button type="submit" class="btn btn-custom mt-3">Zatwierdź</button>
        </form>
      </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

      </div>
    </div>
  </body>
</html>
