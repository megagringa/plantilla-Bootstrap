# Plantilla-Bootstrap

## Documentación

### [Plantilla](https://megagringa.github.io/plantilla-Bootstrap/index.html)

---


Modelo de plantilla para la realizacion de una landing-page básica para todo aquel que esté en sus comienzos en el manejo del framework Bootstrap.

- Tecnologías:
    - Framework: 
        - Bootstrap 5


La página está divida en tres secciones en su código:

Sección 1: Navbar desplegable
```
<header>
    
      <div class="container">
        <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
          <div class="container">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav mx-auto">
                <li class="nav-item active">
                  <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Acerca de</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Servicios</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Contacto</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
        
      </div>
  </header>

```

Sección 2: contenido e imagenes

```
<main>
    <div class="container mt-lg-4">
      <div class="row py-2">
        <div class="col-12 col-md-8">
          <div class="row">
            <div class="col-12 border-bottom">
              <img src="img/p1.jpg" class="img-fluid" alt="">
              <h3 class="pt-2 text-primary">Lorem ipsum</h3>
              <p class="pt-3 text-justify">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus dolores temporibus doloremque distinctio
                labore quos sed quo, corrupti ullam facere maxime aliquid nam fuga ad nisi facilis dolorum reiciendis
                voluptates!
              </p>
            </div>
            <div class="col-12 pt-3 border-bottom">
              <img src="img/p2.jpg" class="img-fluid" alt="Pareja agarrados de la mano.">
              <h3 class="pt-2 text-primary">Lorem ipsum</h3>
              <p class="pt-3 text-justify">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus dolores temporibus doloremque distinctio
                labore quos sed quo, corrupti ullam facere maxime aliquid nam fuga ad nisi facilis dolorum reiciendis
                voluptates!
              </p>
            </div>
          </div>
        </div>
        <aside class="col-12 d-md-block col-md-4 text-center bg-dark py-4">
          <h4 class="text-white p-2">Lorem ipsum</h4>
          <img src="img/p3.png" class="img-fluid rounded" alt="Tutorial en línea de fotografía">
          <p class="text-white">Lorem ipsum</p>
          <div class="bg-light p-2 mt-1"> <a href="" class="text-success p-0 m-0 h4">
              <p class="p-0 m-0">Lorem ipsum</p>
            </a></div>

        </aside>
      </div>
    </div>
  </main>

```


Sección 3: footer

```
<footer>
    <div class="container">
      <div class="row bg-dark">
        <div class="col-12 p-4 text-center">
          <p class="h5 text-light m-0 p-0">Código de Juan y Vane.</p>
        </div>
      </div>
    </div>
  </footer>

```



---

Si necesitas más info consulta la pagina de [Bootstrap](https://getbootstrap.com/)

---
