# Jor
<html><head><base href="javascript:void(0)" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Jordan Collection - ZapatoStyle</title>



<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">



<style>

:root {

--jordan-red: #CE1141;

--jordan-black: #000000;

}



body {

background: linear-gradient(135deg, #f5f5f5 0%, white 100%); font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}



.navbar {

background-color: var(--jordan-black) !important;

}



.product-card {

transition: transform 0.3s; background: white; border-radius: 10px;

box-shadow: 0 4px 8px rgba(0,0,0,0.1); margin-bottom: 20px;

}



.product-card:hover { transform: translateY(-5px);

}



.product-price {

color: var(--jordan-red); font-size: 1.25rem;

font-weight: bold;

}



.jordan-btn {

background-color: var(--jordan-red); color: white;

 

border: none;

}



.jordan-btn:hover { background-color: #a50d32; color: white;

}



#cart-counter { position: relative; top: -10px;

right: -5px;

background-color: var(--jordan-red); color: white;

border-radius: 50%; padding: 2px 6px; font-size: 12px;

}



.footer {

background-color: var(--jordan-black); color: white;

padding: 20px 0; margin-top: 40px;

}



.sale-badge { position: absolute; top: 10px;

right: 10px;

background-color: var(--jordan-red); color: white;

padding: 5px 10px; border-radius: 5px;

}

</style>

</head>

<body>



<nav class="navbar navbar-expand-lg navbar-dark">

<div class="container">

<a class="navbar-brand" href="https://zapatostyle.com">

<img src="https://images.unsplash.com/photo-1600269452121-4f2416e55c28" alt="Jordan Logo" width="40" height="40" class="d-inline-block align-text-top me-2">

Jordan Collection

</a>

 

<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>



<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a  href="https://jd-354.github.io/Z/">Inicio</a>

</li>

<li class="nav-item">

<a class="<a href="https://jd-354.github.io/Z/" >" href="https://zapatostyle.com/jordan/nuevos"><i class="fas fa-fire"></i> Nuevos Lanzamientos</a>

</li>

<li class="nav-item">

<a  class="nav-link"  href="<a href="https://jd-354.github.io/Z/" >"><i  class="fas  fa-star"></i>

Clásicos</a>

</li>

</ul>



<div class="cart-container">

<button class="btn btn-outline-light">

<i class="fas fa-shopping-cart"></i>

<span id="cart-counter">0</span>

</button>

</div>

</div>

</div>

</nav>



<div class="container mt-4">

<h1 class="text-center mb-4">Colección Jordan</h1>



<div class="row">

<!-- Jordan 1 -->

<div class="col-md-4">

<div class="product-card p-3">

<div class="position-relative">

<img src="https://images.unsplash.com/photo-1586525198428-225f6f12cff5" alt="Air Jordan 1 Retro High OG, classic red and white colorway" class="img-fluid mb-3" width="100%" height="300">

<span class="sale-badge">Clásico</span>

</div>

<h5>Air Jordan 1 Retro High OG</h5>

<p class="product-price">$189.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

 

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn jordan-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Jordan 3 -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1515555230216-82228b88ea98" alt="Air Jordan 3 Retro, elephant print details" class="img-fluid mb-3" width="100%" height="300">

<h5>Air Jordan 3 Retro</h5>

<p class="product-price">$195.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn jordan-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Jordan 4 -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1607893378714-007fd47c8719" alt="Air Jordan 4 Retro, premium suede finish" class="img-fluid mb-3" width="100%" height="300">

<h5>Air Jordan 4 Retro</h5>

<p class="product-price">$199.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn jordan-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

 

</div>



<!-- Jordan 11 -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1552346958-0c38ae745ae1" alt="Air Jordan 11 Retro, patent leather design" class="img-fluid mb-3" width="100%" height="300">

<h5>Air Jordan 11 Retro</h5>

<p class="product-price">$209.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn jordan-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Jordan 23 -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1579338559194-a162d19bf842" alt="Air Jordan 23, premium performance model" class="img-fluid mb-3" width="100%" height="300">

<h5>Air Jordan 23</h5>

<p class="product-price">$225.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn jordan-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>

</div>

</div>



<footer class="footer">

<div class="container">

<div class="row">

<div class="col-md-4">

 

<h5>Contacto</h5>

<p><i class="fas fa-phone"></i> +1 234 567 890</p>

<p><i class="fas fa-envelope"></i> jordan@zapatostyle.com</p>

</div>

<div class="col-md-4">

<h5>Síguenos</h5>

<a href="https://facebook.com/jordan" class="text-white me-3"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com/jordan" class="text-white me-3"><i class="fab fa-instagram"></i></a>

<a href="https://twitter.com/jordan" class="text-white"><i class="fab fa-twitter"></i></a>

</div>

<div class="col-md-4">

<h5>Newsletter</h5>

<p>Recibe las últimas novedades de Jordan</p>

<form class="d-flex">

<input type="email" class="form-control me-2" placeholder="Tu email">

<button class="btn jordan-btn">Suscribir</button>

</form>

</div>

</div>

</div>

</footer>



<script>

let cartCount = 0;



document.querySelectorAll('.jordan-btn').forEach(button => { button.addEventListener('click', () => {

if(button.textContent.includes('Añadir al carrito')) { cartCount++;

document.getElementById('cart-counter').textContent = cartCount;



 

















}

});

});

 

// Animación del contador

const counter = document.getElementById('cart-counter'); counter.style.transform = 'scale(1.5)';

setTimeout(() => { counter.style.transform = 'scale(1)';

}, 200);

 

</script>



</body>

</html>

