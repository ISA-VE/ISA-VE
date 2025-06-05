<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Información sobre ITS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0; padding: 0;
            background: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 1em;
            text-align: center;
            font-size: 1.5em;
            font-weight: bold;
        }
        nav {
            display: flex;
            background: #34495e;
            overflow-x: auto;
        }
        nav button {
            flex: 1;
            padding: 1em;
            border: none;
            background: #34495e;
            color: white;
            cursor: pointer;
            font-size: 1em;
            transition: background 0.3s;
        }
        nav button:hover, nav button.active {
            background: #1abc9c;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: auto;
            background: white;
            margin-top: 1em;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            display: none;
        }
        section.active {
            display: block;
        }
        h2 {
            color: #16a085;
        }
        /* Cuestionario */
        form {
            display: flex;
            flex-direction: column;
            max-width: 600px;
        }
        label {
            margin-top: 1em;
            font-weight: bold;
        }
        input[type="text"], textarea {
            padding: 0.5em;
            font-size: 1em;
            margin-top: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button.submit-btn {
            margin-top: 1.5em;
            padding: 0.7em;
            background-color: #16a085;
            border: none;
            color: white;
            font-size: 1em;
            border-radius: 4px;
            cursor: pointer;
            transition: background 0.3s;
        }
        button.submit-btn:hover {
            background-color: #13856a;
        }
        .reviews {
            margin-top: 2em;
            max-width: 600px;
        }
        .review-item {
            border-bottom: 1px solid #ddd;
            padding: 0.8em 0;
        }
        .review-item:last-child {
            border-bottom: none;
        }
        .review-name {
            font-weight: bold;
            color: #2c3e50;
        }
        .review-text {
            margin-top: 0.3em;
            font-style: italic;
        }
    </style>
</head>
<body>

<header>
    Transmisiones Sexuales (ITS) - Información y Apoyo
</header>

<nav>
    <button class="tab-btn active" data-target="window1">¿Qué son las ITS?</button>
    <button class="tab-btn" data-target="window2">¿Cómo prevenir las ITS?</button>
    <button class="tab-btn" data-target="window3">Tipos de ITS en Chile</button>
    <button class="tab-btn" data-target="window4">ITS comunes en hombres</button>
    <button class="tab-btn" data-target="window5">ITS comunes en mujeres</button>
    <button class="tab-btn" data-target="window6">Impacto emocional</button>
    <button class="tab-btn" data-target="window7">¿A quién acudir?</button>
    <button class="tab-btn" data-target="window8">Cuestionario y reseñas</button>
</nav>

<section id="window1" class="active">
    <h2>¿Qué son las ITS?</h2>
    <p>Las Infecciones de Transmisión Sexual (ITS) son infecciones que se transmiten principalmente a través del contacto sexual sin protección. Pueden ser causadas por bacterias, virus o parásitos. Muchas ITS no presentan síntomas inicialmente, por eso es fundamental la prevención y la detección temprana.</p>
</section>

<section id="window2">
    <h2>¿Cómo prevenir las ITS?</h2>
    <ul>
        <li>Usar preservativos en todas las relaciones sexuales.</li>
        <li>Realizarse chequeos médicos regularmente.</li>
        <li>Evitar múltiples parejas sexuales o conocer el estado de salud de la pareja.</li>
        <li>Vacunarse contra virus como el VPH y la Hepatitis B.</li>
        <li>Evitar compartir objetos personales que puedan transmitir infecciones.</li>
    </ul>
</section>

<section id="window3">
    <h2>Tipos de ITS en Chile (actualidad)</h2>
    <p>En Chile, las ITS más reportadas actualmente incluyen:</p>
    <ul>
        <li>Clamidia</li>
        <li>Gonorrea</li>
        <li>Sífilis</li>
        <li>Virus del Papiloma Humano (VPH)</li>
        <li>Herpes Genital</li>
        <li>VIH/SIDA</li>
    </ul>
</section>

<section id="window4">
    <h2>ITS más comunes en hombres</h2>
    <ul>
        <li>Clamidia</li>
        <li>Gonorrea</li>
        <li>Herpes genital</li>
        <li>Virus del Papiloma Humano (VPH)</li>
        <li>Sífilis</li>
        <li>VIH</li>
    </ul>
</section>

<section id="window5">
    <h2>ITS más comunes en mujeres</h2>
    <ul>
        <li>Clamidia</li>
        <li>Vaginosis bacteriana (no siempre considerada ITS, pero relacionada)</li>
        <li>Gonorrea</li>
        <li>Virus del Papiloma Humano (VPH)</li>
        <li>Herpes genital</li>
        <li>Sífilis</li>
        <li>VIH</li>
    </ul>
</section>

<section id="window6">
    <h2>¿Cómo te puedes ver afectado emocionalmente?</h2>
    <p>Recibir un diagnóstico de ITS puede generar ansiedad, miedo, vergüenza o culpa. Es normal sentirse afectado emocionalmente, pero es importante buscar apoyo en familiares, amigos, o profesionales. La educación y la información ayudan a reducir el estigma y enfrentar la situación con responsabilidad y autocuidado.</p>
</section>

<section id="window7">
    <h2>¿A quién debes acudir?</h2>
    <p>Si sospechas que puedes tener una ITS o tienes síntomas, acude a:</p>
    <ul>
        <li>Centros de salud públicos y privados</li>
        <li>Consultorios y clínicas especializadas en salud sexual</li>
        <li>Hospitales con servicio de atención en infectología</li>
        <li>Organizaciones y fundaciones que apoyan la salud sexual</li>
        <li>En Chile, el Fondo Nacional de Salud (FONASA) cubre gran parte de los tratamientos.</li>
    </ul>
</section>

<section id="window8">
    <h2>Cuestionario y Reseñas</h2>
    <form id="reviewForm">
        <label for="name">Nombre:</label>
        <input type="text" id="name" required placeholder="Tu nombre" />
        
        <label for="review">Tu reseña o comentario:</label>
        <textarea id="review" rows="4" required placeholder="Escribe aquí tu opinión o experiencia"></textarea>
        
        <button type="submit" class="submit-btn">Enviar reseña</button>
    </form>
    <div class="reviews" id="reviewsList">
        <h3>Reseñas de usuarios:</h3>
        <p>No hay reseñas aún.</p>
    </div>
</section>

<script>
    // Control pestañas
    const tabs = document.querySelectorAll('nav button');
    const sections = document.querySelectorAll('section');
    
    tabs.forEach(tab => {
        tab.addEventListener('click', () => {
            tabs.forEach(t => t.classList.remove('active'));
            tab.classList.add('active');
            const target = tab.getAttribute('data-target');
            sections.forEach(sec => {
                if (sec.id === target) sec.classList.add('active');
                else sec.classList.remove('active');
            });
        });
    });

    // Manejo de reseñas - guardado en localStorage para demo simple
    const form = document.getElementById('reviewForm');
    const reviewsList = document.getElementById('reviewsList');

    function renderReviews() {
        let reviews = JSON.parse(localStorage.getItem('itsReviews')) || [];
        if (reviews.length === 0) {
            reviewsList.innerHTML = '<h3>Reseñas de usuarios:</h3><p>No hay reseñas aún.</p>';
            return;
        }
        let html = '<h3>Reseñas de usuarios:</h3>';
        reviews.forEach(r => {
            html += `<div class="review-item"><div class="review-name">${r.name}</div><div class="review-text">${r.text}</div></div>`;
        });
        reviewsList.innerHTML = html;
    }

    form.addEventListener('submit', e => {
        e.preventDefault();
        const name = document.getElementById('name').value.trim();
        const reviewText = document.getElementById('review').value.trim();
        if (name && reviewText) {
            let reviews = JSON.parse(localStorage.getItem('itsReviews')) || [];
            reviews.push({ name, text: reviewText });
            localStorage.setItem('itsReviews', JSON.stringify(reviews));
            form.reset();
            renderReviews();
            alert('Gracias por tu reseña!');
        }
    });

    // Renderizar al cargar la página
    renderReviews();
</script>

</body>
</html>
