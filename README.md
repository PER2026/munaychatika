```html
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Munaychatika - Aretes de Cuero</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #0f0f0f;
    color: white;
}

header {
    background: black;
    padding: 20px;
    text-align: center;
    font-size: 28px;
    color: gold;
    letter-spacing: 2px;
}

.hero {
    text-align: center;
    padding: 50px 20px;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.hero p {
    color: #ccc;
}

.btn {
    background: gold;
    color: black;
    padding: 12px 25px;
    text-decoration: none;
    border-radius: 25px;
    display: inline-block;
    margin-top: 20px;
    font-weight: bold;
}

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 40px;
}

.card {
    background: #1a1a1a;
    border-radius: 15px;
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.card img {
    width: 100%;
}

.card h3 {
    margin: 10px 0;
}

.card p {
    color: gold;
}

.footer {
    text-align: center;
    padding: 20px;
    background: black;
    margin-top: 30px;
}

.model3d {
    width: 300px;
    height: 300px;
    margin: auto;
}
</style>
</head>

<body>

<header>
MUNAYCHATIKA
</header>

<section class="hero">
    <h1>Aretes de Cuero Elegantes</h1>
    <p>Diseños únicos hechos a mano en Perú</p>

    <div class="model3d">
        <model-viewer 
            src="https://modelviewer.dev/shared-assets/models/Astronaut.glb" 
            auto-rotate 
            camera-controls 
            background-color="#000000">
        </model-viewer>
    </div>

    <a class="btn" href="https://wa.me/51654599999">Comprar por WhatsApp</a>
</section>

<section class="products">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1617038260897-41a1f14a8ca0" alt="">
        <h3>Aretes Clásicos</h3>
        <p>S/ 25</p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1588444650733-d45ec7b0b0a2" alt="">
        <h3>Diseño Andino</h3>
        <p>S/ 30</p>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1600180758890-6c9c3d6a6d0c" alt="">
        <h3>Premium Cuero</h3>
        <p>S/ 40</p>
    </div>
</section>

<div class="footer">
© 2026 Munaychatika - Todos los derechos reservados
</div>

<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

</body>
</html>
```
