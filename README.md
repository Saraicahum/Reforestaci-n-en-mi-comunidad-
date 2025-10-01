<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Verde: Proyecto de Reforestación del Parque Comunitario</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            background: linear-gradient(to bottom, #f0f9f0, #e0f2e0); /* Gradiente suave verde */
            color: #2e4d2e; /* Verde oscuro terroso */
            font-family: 'Poppins', sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #3b7d3b; /* Verde musgo */
            color: #fff;
            padding: 60px 30px;
            text-align: center;
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
            position: relative;
            overflow: hidden;
        }
        header::before {
            content: '';
            position: absolute;
            top: -50px;
            left: -50px;
            width: 200px;
            height: 200px;
            background: radial-gradient(circle, rgba(255,255,255,0.2), transparent);
            opacity: 0.5;
        }
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            margin: 0;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.2);
        }
        nav {
            background-color: #8b5a2b; /* Marrón tierra */
            padding: 15px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-weight: 600;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #d9ead3; /* Verde claro */
        }
        main {
            max-width: 900px;
            margin: 40px auto;
            padding: 0 20px;
        }
        article {
            background-color: #fff;
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 40px;
            box-shadow: 0 8px 16px rgba(0,128,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        article:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 24px rgba(0,128,0,0.15);
        }
        h2 {
            color: #8b4513; /* Marrón otoñal */
            font-family: 'Playfair Display', serif;
            font-size: 2.2em;
            border-bottom: 3px solid #3b7d3b;
            padding-bottom: 15px;
            position: relative;
        }
        h2::after {
            content: '🌿';
            position: absolute;
            right: 0;
            bottom: 10px;
            font-size: 1.5em;
            opacity: 0.7;
        }
        h3 {
            color: #3b7d3b;
            font-size: 1.8em;
            margin-top: 20px;
            font-weight: 600;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        ul li {
            background: linear-gradient(to right, #d9ead3, transparent);
            padding: 12px 20px;
            margin-bottom: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
            position: relative;
        }
        ul li::before {
            content: '🍃';
            margin-right: 10px;
            font-size: 1.2em;
        }
        img {
            width: 100%;
            height: auto;
            border-radius: 15px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: block;
        }
        footer {
            background-color: #3b7d3b;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            border-top: 5px solid #8b5a2b;
        }
        footer p {
            margin: 0;
            font-size: 1.1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>🌳 Blog Verde: Reforestación en Nuestro Parque 🌳</h1>
        <p>Una aventura creativa hacia un futuro sostenible en nuestra comunidad</p>
    </header>

  <nav>
        <a href="#intro">Introducción</a>
        <a href="#agenda">Agenda 2030</a>
        <a href="#cuidado">Cuidado y Justicia</a>
        <a href="#ods">ODS Clave</a>
        <a href="#implementacion">Implementación</a>
        <a href="#plantas">Nuestras Plantas</a>
        <a href="#vital">Vitalidad Ambiental</a>
        <a href="#importancia">Importancia</a>
        <a href="#acciones">Acciones</a>
        <a href="#conclusion">Conclusión</a>
    </nav>

   <main>
        <article id="intro">
            <h2>Introducción al Proyecto</h2>
            <p>En nuestra comunidad, nos hemos embarcado en un emocionante proyecto de reforestación para transformar nuestro parque en un oasis verde. Con la participación de vecinos, voluntarios y expertos, estamos plantando árboles nativos, creando senderos ecológicos y educando sobre la importancia de la naturaleza. Este blog explora cómo este esfuerzo se alinea con metas globales de sostenibilidad. ¡Únete a nosotros en esta aventura verde!</p>
        </article>

  <article id="agenda">
            <h2>La Agenda 2030 de la ONU</h2>
            <p>La Agenda 2030 de la ONU establece una visión global hacia la sostenibilidad económica, social y ambiental mediante 17 Objetivos de Desarrollo Sostenible (ODS), que buscan promover el bienestar humano mientras protegen el planeta. La degradación ambiental, el cambio climático y el agotamiento de recursos amenazan los avances sociales y económicos; de mantenerse los patrones actuales, para 2050 serían necesarios casi tres planetas para sostener el nivel de vida global.</p>
        </article>

   <article id="cuidado">
            <h2>Cuidado del Medio Ambiente y Justicia Social</h2>
            <p>Un medio ambiente sano garantiza agua potable, alimentos, aire limpio y protección ante desastres, elementos esenciales para la vida humana y la dignidad. Los ODS 13 y 15 promueven la acción climática y la conservación de ecosistemas mediante energías renovables, reforestación y reducción de emisiones, mitigando daños ecológicos y riesgos económicos. La justicia ambiental subraya que los impactos ambientales afectan más a las comunidades vulnerables, intensificando pobreza y desigualdad, por lo que las políticas deben integrar equidad y derechos sociales.</p>
        </article>

  <article id="ods">
            <h2>ODS Clave y Acciones</h2>
            <ul>
                <li>ODS 6 (Agua limpia y saneamiento): Garantizar acceso equitativo al agua y saneamiento mediante tratamiento de aguas, conservación de cuencas y educación en uso eficiente del recurso.</li>
                <li>ODS 11 (Ciudades sostenibles): Promover transporte limpio, infraestructura verde y viviendas dignas, reduciendo riesgos urbanos y mejorando calidad de vida.</li>
                <li>ODS 12 (Producción y consumo responsables): Fomentar consumo sostenible, reciclaje y economía circular, vinculando hábitos responsables con equidad social.</li>
                <li>ODS 13 (Acción por el clima): Implementar energías renovables, eficiencia energética, reforestación y sistemas de alerta temprana ante desastres, asegurando resiliencia global.</li>
            </ul>
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a7/Sustainable_Development_Goals.svg" alt="Infográfico de los Objetivos de Desarrollo Sostenible (ODS)">
        </article>

  <article id="implementacion">
            <h2>Implementación y Actores</h2>
            <p>Avanzar en sostenibilidad requiere acciones concretas: energías limpias, gestión integral del agua, planificación urbana, educación ambiental y políticas públicas. La cooperación multisectorial es clave:</p>
            <ul>
                <li>Gobiernos: Regulación, planificación y políticas públicas.</li>
                <li>Sector privado: Innovación, financiamiento y adopción de producción sostenible.</li>
                <li>Sociedad civil: Vigilancia, educación y presión para la justicia ambiental y social.</li>
                <li>Organizaciones internacionales: Coordinación, financiamiento y seguimiento global.</li>
            </ul>
        </article>

  <article id="plantas">
            <h2>Nuestras Plantas Estrella para la Reforestación</h2>
            <p>Para nuestro proyecto de reforestación, hemos seleccionado tres especies clave que no solo embellecen nuestro parque, sino que también se adaptan perfectamente al clima de Yucatán y promueven la sostenibilidad ambiental. Conoce más sobre estas plantas:</p>
            
   <h3>Lirio de Lluvia (Zephyranthes candida)</h3>
            <p><strong>Nombres comunes:</strong> Azucenita del río, Azucenita blanca, Lirio de hadas, Flor de céfiro, Brujitas, Duendes blancos.</p>
            <p>El lirio de lluvia es una planta bulbosa perenne de la familia Amaryllidaceae. Sus hojas verdes dan lugar a flores blancas en forma de copa que florecen tras las lluvias de verano y otoño, formando densas alfombras floridas. Nativa del Cono Sur, se adapta bien a Yucatán con riego moderado.</p>
            <ul>
                <li><strong>Reproducción:</strong> Por semillas (cápsulas con semillas aladas) o división de bulbos en primavera.</li>
                <li><strong>Clima:</strong> Prefiere climas cálidos o subtropicales, tolera hasta –12 °C, florece tras lluvias.</li>
                <li><strong>Siembra:</strong> Bulbos a 10 cm de profundidad en verano u otoño, en jardines o macetas.</li>
                <li><strong>Riego:</strong> Suelo húmedo sin encharcar, riego regular en verano.</li>
                <li><strong>Suelo:</strong> Fértil, con buen drenaje, indiferente al pH.</li>
                <li><strong>Adaptación en Yucatán:</strong> Ideal como ornamental, se adapta al calor con riego periódico.</li>
            </ul>
            <img src="https://upload.wikimedia.org/wikipedia/commons/b/b6/Zephyranthes_candida.jpg" alt="Lirio de lluvia (Zephyranthes candida) en floración">

  <h3>Hibisco o Flor de Jamaica (Hibiscus rosa-sinensis)</h3>
            <p><strong>Nombres comunes:</strong> Tulipán mexicano, Flor de Jamaica, Rosa de China, Cayena, Cardenales, Amapola, Mar pacífico.</p>
            <p>El hibisco es un arbusto perennifolio de la familia Malváceas, originario de Asia tropical. Crece hasta 3 m y produce flores grandes y coloridas (rojo, rosa, amarillo, blanco) casi todo el año. Es perfecto para jardines tropicales y muy común en Yucatán.</p>
            <ul>
                <li><strong>Reproducción:</strong> Por esquejes semileñosos en primavera o verano, o por semillas con escarificación.</li>
                <li><strong>Clima:</strong> Tropical, necesita sol abundante, no tolera heladas por debajo de 12–14 °C.</li>
                <li><strong>Riego:</strong> Generoso en verano (2–3 veces por semana), moderado en invierno.</li>
                <li><strong>Suelo:</strong> Fértil, suelto, con buen drenaje, ligeramente ácido a neutro.</li>
                <li><strong>Plantación:</strong> En primavera, en hoyos amplios con compost y mantillo.</li>
                <li><strong>Adaptación en Yucatán:</strong> Muy adecuado para el clima cálido-húmedo, común en viveros locales.</li>
            </ul>
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/5c/Hibiscus_rosa_-sinensis.jpg" alt="Hibisco (Hibiscus rosa-sinensis) en flor">

   <h3>Palmera de Molino (Trachycarpus fortunei)</h3>
            <p><strong>Nombres comunes:</strong> Palmera de molino, Palma de molino, Palmera de Fortune, Palmera de cáñamo china.</p>
            <p>La palmera china de abanico es una palma robusta de Asia, con tronco fibroso y hojas palmadas en forma de abanico. Alcanza hasta 12 m en su hábitat natural, pero en cultivo es más baja. Produce flores amarillas y frutos negro-azulados.</p>
            <ul>
                <li><strong>Reproducción:</strong> Por semillas frescas sembradas en primavera, germinación lenta.</li>
                <li><strong>Clima:</strong> Adaptable a calor intenso y heladas moderadas (hasta –15 °C).</li>
                <li><strong>Riego:</strong> Moderado, 1–2 veces por semana en verano, ocasional en invierno.</li>
                <li><strong>Suelo:</strong> Bien drenado, tolera suelos pobres, pH 6.0–7.5.</li>
                <li><strong>Adaptación en Yucatán:</strong> Apta para el calor con riego moderado, disponible en viveros especializados.</li>
            </ul>
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c2/TrachycarpusFortunei.jpg" alt="Palmera de molino (Trachycarpus fortunei)">
        </article>

  <article id="vital">
            <h2>El Cuidado del Medio Ambiente es Vital</h2>
            <p>El cuidado del medio ambiente es vital porque sustenta la vida, provee recursos naturales esenciales como agua y aire, y garantiza la salud humana al reducir la contaminación y los desastres climáticos. Preservar los ecosistemas es una responsabilidad para nuestra generación y las futuras, lo que implica adoptar prácticas de consumo responsable, gestión de residuos y eficiencia en el uso de los recursos para un futuro sostenible.</p>
        </article>

  <article id="importancia">
            <h2>¿Por Qué es Importante Cuidar el Medio Ambiente?</h2>
            <ul>
                <li>Soporte de la vida: El medio ambiente nos proporciona todo lo necesario para sobrevivir: alimento, agua, aire puro y un hogar.</li>
                <li>Recursos naturales: Es la fuente de todos los recursos que utilizamos para vivir, desde lo que comemos hasta la ropa que vestimos y los productos que fabricamos.</li>
                <li>Salud humana: Un medio ambiente saludable reduce la contaminación del aire y del agua, lo que mejora la salud física y mental de las personas.</li>
                <li>Protección de la biodiversidad: Conservar los ecosistemas protege la vida de todas las especies, manteniendo el equilibrio natural del planeta.</li>
                <li>Prevención del cambio climático: Cuidar nuestro planeta es fundamental para mitigar los efectos del cambio climático, como sequías e inundaciones.</li>
                <li>Legado para las futuras generaciones: Es nuestra responsabilidad asegurar que las generaciones futuras tengan los mismos recursos y un entorno habitable.</li>
            </ul>
        </article>

   <article id="acciones">
            <h2>Acciones para Cuidar el Medio Ambiente</h2>
            <ul>
                <li>Consumo responsable: Reducir el uso de productos de un solo uso, preferir los productos biodegradables y comprar de forma consciente.</li>
                <li>Gestión de residuos: Separar los desechos para el reciclaje, compostar los orgánicos y evitar tirar basura en la calle.</li>
                <li>Ahorro de energía: Apagar los aparatos electrónicos y desenchufar los que no se usan.</li>
                <li>Ahorro de agua: Reparar fugas, usar la lavadora con cargas completas y reutilizar agua.</li>
                <li>Protección de la naturaleza: No arrancar plantas, cuidar los árboles por su rol en la oxigenación y evitar la quema de basura.</li>
                <li>Transporte sostenible: Reducir el uso del automóvil y optar por otras alternativas de transporte.</li>
            </ul>
        </article>

  <article id="conclusion">
            <h2>Conclusión</h2>
            <p>Los ODS integran desarrollo social y protección ambiental. La sostenibilidad no es un lujo, sino condición para la equidad: acceso al agua, vivienda y seguridad alimentaria dependen de ecosistemas saludables y clima estable. Implementar los ODS requiere acciones concretas y cooperación global; solo así será posible avanzar hacia un mundo más justo y sostenible, cumpliendo la visión de la Agenda 2030 de armonizar crecimiento económico, inclusión social y conservación del medio ambiente.</p>
        </article>
    </main>

  <footer>
        <p>¡Únete al proyecto y haz la diferencia hoy! 🌱 Contacto: comunidad@reforestacionparque.com</p>
    </footer>
</body>
</html>
