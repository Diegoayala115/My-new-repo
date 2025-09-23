# My-new-repo

 site.title:Showroom Hidráulica y Neumática
baseurl: "" 
url: "https://Diegoayala115.github.io"
collections:
  products:
    output: true
    permalink: /:collection/:title/
---
layout: default
title: Inicio
---

<h1>{{ site.title }}</h1>
<ul>
  {% for p in site.products %}
    <li>
      <a href="{{ p.url }}">
        <img src="{{ p.image }}" alt="{{ p.title }}" width="150">
        <h2>{{ p.title }}</h2>
      </a>
      <p>{{ p.specs.presion }} · {{ p.specs.caudal }}</p>
    </li>
  {% endfor %}
</ul>
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>{{ page.title }} | {{ site.title }}</title>
  <link rel="stylesheet" href="/assets/css/styles.css">
</head>
<body>
  {{ content }}
</body>
</html>

---
producto:
 Bomba hidráulica BH-200
 
 ![Bomba Hidraulica](https://github.com/user-attachments/assets/90796c6d-8f02-451c-95ba-df155ebba730)

Datos tecnicos:
  presion: "250 bar"
  caudal: "20 L/min"
  material: "Acero inoxidable"
  conexion: "G1/2"
---
La BH-200 es una bomba robusta para aplicaciones industriales de alta presión. Ideal en prensas, sistemas de elevación y maquinaria móvil.

body {
  font-family: Arial, sans-serif;
  margin: 2rem;
  line-height: 1.5;
}

h1, h2 {
  color: #005288;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 1.5rem;
}

a {
  text-decoration: none;
  color: #333;
}

img {
  border: 1px solid #ccc;
  border-radius: 4px;
}

