# Lapin-Atallier
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lapin Atelier</title>

    <style>
        /* RESET */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        /* HEADER */
        header {
            background: #2c3e50;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: relative;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* LOGO */
        .logo {
            position: absolute;
            top: 15px;
            right: 30px;
            width: 130px;
        }

        /* HERO */
        .hero {
            background: url('Lapin.jpeg') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 120px 20px;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            max-width: 800px;
            margin: 20px auto;
            font-size: 1.2rem;
            background: rgba(255, 255, 255, 0.75);
            color: #000;
            padding: 15px;
            border-radius: 10px;
        }

        /* SECCIONES */
        section {
            max-width: 1100px;
            margin: 50px auto;
            padding: 0 20px;
        }

        section h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #2c3e50;
        }

        /* GALERÍA */
        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 15px;
        }

        .galeria img {
            width: 100%;
            border-radius: 10px;
        }

        /* TALLERES */
        .talleres-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .taller {
            background: #ffffff;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .taller img {
            width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }

        /* EQUIPO */
        .equipo {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .miembro {
            background: #fff;
            padding: 15px;
            width: 230px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .miembro img {
            width: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        /* CONTACTO */
        .contact-links a {
            display: flex;
            align-items: center;
            gap: 10px;
            margin: 10px 0;
            text-decoration: none;
            color: #333;
            font-size: 1.1rem;
        }

        .contact-links img {
            width: 30px;
        }

        /* FOOTER */
        footer {
            background: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

<header>
    <h1>Lapin Atelier</h1>
    <img src="Logo Lapin.png" class="logo" alt="Logo Lapin">
    <nav>
        <a href="#proyectos">Proyectos</a>
        <a href="#galeria">Galería</a>
        <a href="#equipo">Equipo</a>
        <a href="#agenda">Agenda</a>
        <a href="#talleres">Talleres</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<div class="hero">
    <h1>Introducción</h1>
    <p>
        DEDICA es una empresa creada para brindar a jóvenes y personas de todas las edades
        un espacio donde puedan expresarse artísticamente a través de la creación de figuras
        de arcilla y pinturas. Ofrecemos gratuitamente materiales y herramientas para que
        cada participante pueda desarrollar sus obras y dar valor a su talento.
    </p>
</div>

<section id="proyectos">
    <h2>Proyectos</h2>
    <h3>Talleres de Pintura</h3>
    <h3>Talleres de Cerámica</h3>
    <h3>Talleres de Grabado</h3>
</section>

<section id="agenda">
    <h2>Agenda</h2>

    <div class="area">
        <h3>🎨 Área de Pintura</h3>
        <ul>
            <li><strong>09:00 – 10:30</strong> | Pintura básica</li>
            <li><strong>10:45 – 12:15</strong> | Pintura acrílica</li>
            <li><strong>12:30 – 14:00</strong> | Pintura experimental</li>
        </ul>
    </div>

    <div class="area">
        <h3>🖨️ Área de Grabado</h3>
        <ul>
            <li><strong>09:00 – 10:30</strong> | Introducción al grabado</li>
            <li><strong>10:45 – 12:15</strong> | Grabado en linóleo</li>
            <li><strong>12:30 – 14:00</strong> | Técnicas mixtas</li>
        </ul>
    </div>

    <div class="area">
        <h3>🏺 Área de Cerámica</h3>
        <ul>
            <li><strong>09:00 – 10:30</strong> | Modelado básico</li>
            <li><strong>10:45 – 12:15</strong> | Torno cerámico</li>
            <li><strong>12:30 – 14:00</strong> | Esmaltado</li>
        </ul>
    </div>
</section>

<section id="galeria">
    <h2>Galería</h2>
    <div class="galeria">
        <img src="art1.jpeg" alt="Arte 1">
        <img src="art2.jpeg" alt="Arte 2">
        <img src="art3.jpeg" alt="Arte 3">
        <img src="art4.jpeg" alt="Arte 4">
        <img src="art5.jpeg" alt="Arte 5">
        <img src="art11.jpeg" alt="Arte 6">
        <img src="art0.jpeg" alt="Arte 7">
        <img src="art7.jpeg" alt="Arte 8">
    </div>
</section>

<section id="talleres">
    <h2>Talleres</h2>
    <div class="talleres-grid">
        <div class="taller">
            <h3>Grabado</h3>
            <p>Aprende técnicas de impresión artística.</p>
            <img src="Imagen grabado.avif" alt="Grabado">
        </div>

        <div class="taller">
            <h3>Cerámica</h3>
            <p>Creación de piezas con arcilla.</p>
            <img src="imagen20.jpeg" alt="Cerámica">
        </div>

        <div class="taller">
            <h3>Pintura</h3>
            <p>Técnicas con acrílicos y acuarelas.</p>
            <img src="art10.jpeg" alt="Pintura">
        </div>

        <div class="taller">
            <h3>Escultura</h3>
            <p>Trabajo tridimensional artístico.</p>
            <img src="art7.jpeg" alt="Escultura">
        </div>

        <div class="taller">
            <h3>Pintura</h3>
            <p>Exploración creativa.</p>
            <img src="art9.jpeg" alt="Pintura">
        </div>
    </div>
</section>

<section id="equipo">
    <h2>Nuestro Equipo</h2>
    <div class="equipo">
        <div class="miembro">
            <img src="art1.jpeg" alt="Manuel Haro">
            <h3>Manuel Haro</h3>
            <p>Director</p>
        </div>

        <div class="miembro">
            <img src="https://picsum.photos/100?random=7" alt="Osvaldo">
            <h3>Osvaldo</h3>
            <p>Artista</p>
        </div>

        <div class="miembro">
            <img src="https://picsum.photos/100?random=8" alt="Elvia">
            <h3>Elvia</h3>
            <p>Artista</p>
        </div>

        <div class="miembro">
            <img src="https://picsum.photos/100?random=9" alt="Mauricio">
            <h3>Mauricio</h3>
            <p>Artista</p>
        </div>
    </div>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <div class="contact-links">
        <a href="mailto:topobikerzac@hotmail.com">
            <img src="art17.png" alt="Correo"> Correo
        </a>
        <a href="tel:4921252430">
            <img src="art16.png" alt="Teléfono"> Teléfono
        </a>
        <a href="https://www.tiktok.com/@dedica.fundation" target="_blank">
            <img src="art14.png" alt="TikTok"> TikTok
        </a>
        <a href="https://www.instagram.com/lapinatelier22/" target="_blank">
            <img src="art13.png" alt="Instagram"> Instagram
        </a>
        <a href="https://www.facebook.com/colectivolapinatelier1/" target="_blank">
            <img src="art15.png" alt="Facebook"> Facebook
        </a>
    </div>
</section>

<footer>
    &copy; Fundación Dedica
</footer>

</body>
</html>

