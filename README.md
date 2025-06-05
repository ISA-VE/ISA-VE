<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Información sobre ITS</title>
    <meta name="description" content="Información sobre Infecciones de Transmisión Sexual (ITS), prevención, tipos en Chile, impacto emocional, y apoyo. Espacio para dejar tus reseñas y experiencias." />
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
        <li>Realizarse chequeos médicos re
