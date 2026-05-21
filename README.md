![Uploading art0.jpeg…]()
# Lapin-Atallier<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lapin Atelier | Arte y Creación</title>
    <style>
        /* RESET Y ESTILOS GENERALES */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: #f8f9fa;
            color: #333;
            line-height: 1.7;
        }

        /* HEADER */
        header {
            background: linear-gradient(135deg, #2c3e50, #34495e);
            color: white;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .header-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        h1 {
            font-size: 2.2rem;
            font-weight: 700;
        }

        .logo {
            width: 140px;
            height: auto;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 18px;
            font-weight: 600;
            transition: all 0.3s;
        }

        nav a:hover {
            color: #f1c40f;
            text-decoration: underline;
        }

        /* HERO */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)), 
                        url('Lapin.jpeg') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px;
            position: relative;
        }

        .hero h1 {
            font-size: 3.8rem;
            margin-bottom: 20px;
            text-shadow: 0 3px 10px rgba(0,0,0,0.6);
        }

        .hero p {
            max-width: 850px;
            margin: 0 auto 30px;
            font-size: 1.35rem;
            background: rgba(255, 255, 255, 0.85);
            color: #222;
            padding: 25px 40px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        /* SECCIONES */
        section {
            max-width: 1200px;
            margin: 80px auto;
            padding: 0 20px;
        }

        section h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 50px;
            color: #2c3e50;
            position: relative;
        }

        section h2::after {
            content: '';
            width: 80px;
            height: 4px;
            background: #e67e22;
            position: absolute;
            bottom: -12px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 2px;
        }

        /* GALERÍA */
        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 20px;
        }

        .galeria img {
            width: 100%;
            height: 280px;
            object-fit: cover;
            border-radius: 12px;
            transition: transform 0.4s ease;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .galeria img:hover {
            transform: scale(1.05);
        }

        /* TALLERES */
        .talleres-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .taller {
            background: white;
            border-radius: 16px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
            transition: transform 0.3s;
        }

        .taller:hover {
            transform: translateY(-10px);
        }

        .taller img {
            width: 100%;
            height: 220px;
            object-fit: cover;
        }

        .taller-content {
            padding: 20px;
        }

        .taller h3 {
            color: #2c3e50;
            margin-bottom: 10px;
        }

        /* EQUIPO */
        .equipo {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        .miembro {
            background: white;
            width: 240px;
            text-align: center;
            border-radius: 16px;
            padding: 20px 15px;
            box-shadow: 0 6px 18px rgba(0,0,0,0.08);
            transition: all 0.3s;
        }

        .miembro:hover {
            transform: translateY(-8px);
        }

        .miembro img {
            width: 130px;
            height: 130px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #f1c40f;
            margin-bottom: 15px;
        }

        /* CONTACTO */
        .contact-links {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 18px;
            max-width: 500px;
            margin: 0 auto;
        }

        .contact-links a {
            display: flex;
            align-items: center;
            gap: 15px;
            text-decoration: none;
            color: #333;
            font-size: 1.25rem;
            background: white;
            padding: 15px 30px;
            border-radius: 12px;
            width: 100%;
            max-width: 420px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.07);
            transition: all 0.3s;
        }

        .contact-links a:hover {
            background: #f1c40f;
            color: #222;
            transform: translateX(10px);
        }

        .contact-links img {
            width: 38px;
        }

        /* FOOTER */
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 80px;
        }

        /* RESPONSIVE */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.8rem; }
            .hero { padding: 120px 15px; }
            nav a { margin: 0 10px; font-size: 0.95rem; }
        }
    </style>
</head>
<body>

<header>
    <div class="header-content">
        <h1>Lapin Atelier</h1>
        <img src="Logo Lapin.png" class="logo" alt="Logo Lapin Atelier">
        <nav>
            <a href="#proyectos">Proyectos</a>
            <a href="#galeria">Galería</a>
            <a href="#agenda">Agenda</a>
            <a href="#talleres">Talleres</a>
            <a href="#equipo">Equipo</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </div>
</header>

<div class="hero">
    <h1>Lapin Atelier</h1>
    <p>
        DEDICA es un espacio creativo donde jóvenes y personas de todas las edades 
        pueden expresarse libremente a través del arte. Ofrecemos talleres gratuitos 
        de pintura, cerámica, grabado y escultura, con todos los materiales incluidos.
    </p>
</div>

<section id="proyectos">
    <h2>Nuestros Proyectos</h2>
    <h3 style="text-align:center; margin: 30px 0 40px; color:#e67e22;">Talleres de Pintura • Cerámica • Grabado • Escultura</h3>
</section>

<section id="agenda">
    <h2>Agenda Semanal</h2>
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 30px;">
        <div class="area" style="background:white; padding:25px; border-radius:12px; box-shadow:0 5px 15px rgba(0,0,0,0.08);">
            <h3>🎨 Área de Pintura</h3>
            <ul style="margin-top:15px; line-height:2.1;">
                <li><strong>09:00 – 10:30</strong> | Pintura básica</li>
                <li><strong>10:45 – 12:15</strong> | Pintura acrílica</li>
                <li><strong>12:30 – 14:00</strong> | Pintura experimental</li>
            </ul>
        </div>
        <div class="area" style="background:white; padding:25px; border-radius:12px; box-shadow:0 5px 15px rgba(0,0,0,0.08);">
            <h3>🖌️ Área de Grabado</h3>
            <ul style="margin-top:15px; line-height:2.1;">
                <li><strong>09:00 – 10:30</strong> | Introducción al grabado</li>
                <li><strong>10:45 – 12:15</strong> | Grabado en linóleo</li>
                <li><strong>12:30 – 14:00</strong> | Técnicas mixtas</li>
            </ul>
        </div>
        <div class="area" style="background:white; padding:25px; border-radius:12px; box-shadow:0 5px 15px rgba(0,0,0,0.08);">
            <h3>🏺 Área de Cerámica</h3>
            <ul style="margin-top:15px; line-height:2.1;">
                <li><strong>09:00 – 10:30</strong> | Modelado básico</li>
                <li><strong>10:45 – 12:15</strong> | Torno cerámico</li>
                <li><strong>12:30 – 14:00</strong> | Esmaltado y terminados</li>
            </ul>
        </div>
    </div>
</section>

<section id="galeria">
    <h2>Galería de Obras</h2>
    <div class="galeria">
        <img src="art1.jpeg" alt="Obra de arte 1">
        <img src="art2.jpeg" alt="Obra de arte 2">
        <img src="art3.jpeg" alt="Obra de arte 3">
        <img src="art4.jpeg" alt="Obra de arte 4">
        <img src="art5.jpeg" alt="Obra de arte 5">
        <img src="art11.jpeg" alt="Obra de arte 6">
        <img src="art0.jpeg" alt="Obra de arte 7">
        <img src="art7.jpeg" alt="Obra de arte 8">
    </div>
</section>

<section id="talleres">
    <h2>Nuestros Talleres</h2>
    <div class="talleres-grid">
        <div class="taller">
            <img src="Imagen grabado.avif" alt="Taller de Grabado">
            <div class="taller-content">
                <h3>Grabado</h3>
                <p>Aprende técnicas tradicionales y contemporáneas de impresión artística.</p>
            </div>
        </div>
        <div class="taller">
            <img src="imagen20.jpeg" alt="Taller de Cerámica">
            <div class="taller-content">
                <h3>Cerámica</h3>
                <p>Modelado, torno y esmaltado de piezas únicas en arcilla.</p>
            </div>
        </div>
        <div class="taller">
            <img src="art10.jpeg" alt="Taller de Pintura">
            <div class="taller-content">
                <h3>Pintura</h3>
                <p>Técnicas con acrílico, óleo y acuarela para todos los niveles.</p>
            </div>
        </div>
        <div class="taller">
            <img src="art7.jpeg" alt="Taller de Escultura">
            <div class="taller-content">
                <h3>Escultura</h3>
                <p>Creación de obras tridimensionales con diferentes materiales.</p>
            </div>
        </div>
    </div>
</section>

<section id="equipo">
    <h2>Nuestro Equipo</h2>
    <div class="equipo">
        <div class="miembro">
            <img src="art1.jpeg" alt="Manuel Haro">
            <h3>Manuel Haro</h3>
            <p>Director y Fundador</p>
        </div>
        <div class="miembro">
            <img src="https://picsum.photos/300?random=7" alt="Osvaldo">
            <h3>Osvaldo Ramírez</h3>
            <p>Artista y Tallerista</p>
        </div>
        <div class="miembro">
            <img src="https://picsum.photos/300?random=8" alt="Elvia">
            <h3>Elvia González</h3>
            <p>Artista Visual</p>
        </div>
        <div class="miembro">
            <img src="https://picsum.photos/300?random=9" alt="Mauricio">
            <h3>Mauricio López</h3>
            <p>Especialista en Cerámica</p>
        </div>
    </div>
</section>

<section id="contacto">
    <h2>Contáctanos</h2>
    <div class="contact-links">
        <a href="mailto:topobikerzac@hotmail.com">
            <img src="art17.png" alt="Correo"> topobikerzac@hotmail.com
        </a>
        <a href="tel:4921252430">
            <img src="art16.png" alt="Teléfono"> (492) 125 2430
        </a>
        <a href="https://www.tiktok.com/@dedica.fundation" target="_blank">
            <img src="art14.png" alt="TikTok"> @dedica.fundation
        </a>
        <a href="https://www.instagram.com/lapinatelier22/" target="_blank">
            <img src="art13.png" alt="Instagram"> @lapinatelier22
        </a>
        <a href="https://www.facebook.com/colectivolapinatelier1/" target="_blank">
            <img src="art15.png" alt="Facebook"> Colectivo Lapin Atelier
        </a>
    </div>
</section>

<footer>
    <p>&copy; 2026 Fundación DEDICA • Lapin Atelier</p>
    <p>Espacio creativo abierto para toda la comunidad</p>
</footer>

</body>
</html>
