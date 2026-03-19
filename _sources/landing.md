# Apuntes de Sensores Inteligentes.

```{raw} html
<style>
    .header-container {
        text-align: center;
        margin-bottom: 40px;
    }
    .logos-wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 20px;
        margin-bottom: 20px;
    }
    .unam-logo {
        max-height: 100px;
        width: auto;
    }
    .institution-text h2 {
        margin: 5px 0;
        font-size: 1.8em;
        color: #003057;
    }
    .institution-text h3 {
        margin: 0;
        font-size: 1.4em;
        color: #747474;
        font-weight: normal;
    }
    .main-title {
        text-align: center;
        font-size: 2.5em;
        color: #2c3e50;
        margin-bottom: 10px;
    }
    .main-title span {
        color: #e74c3c;
    }
    .subtitle {
        text-align: center;
        font-size: 1.2em;
        color: #555;
        margin-bottom: 40px;
        line-height: 1.5;
    }
    .info-grid {
        display: grid;
        grid-template-columns: 1fr;
        gap: 20px;
    }
    .landing-card {
        background: #fff;
        border: 1px solid #eee;
        border-radius: 8px;
        padding: 25px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        transition: transform 0.3s ease;
    }
    .landing-card:hover {
        transform: translateY(-5px);
    }
    .landing-card h2 {
        font-size: 1.5em;
        margin-top: 0;
        color: #333;
        border-bottom: 2px solid #e74c3c;
        padding-bottom: 10px;
        margin-bottom: 15px;
        display: flex;
        align-items: center;
    }
    .landing-card h2 .icon {
        font-size: 0.8em;
        margin-right: 10px;
    }
    .fade-in {
        animation: fadeIn 1s ease-in;
    }
    .delay-1 { animation-delay: 0.2s; }
    .delay-2 { animation-delay: 0.4s; }
    .delay-3 { animation-delay: 0.6s; }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>

<!-- Header con Logos y Texto -->
<div class="header-container fade-in">
    <div class="logos-wrapper">
        <img src="_static/logo.png" alt="Logo UNAM" class="unam-logo">
    </div>
    <div class="institution-text">
        <h2>Instituto de Ingeniería, UNAM</h2>
        <h3>Universidad Nacional Autónoma de México</h3>
    </div>
</div>

<div class="info-grid">

    <div class="landing-card fade-in delay-3">
        <h2><span class="icon">🔴</span> Bienvenido</h2>
        <p>Los sensores inteligentes han revolucionado la forma en que se adquiere, procesa y analiza la información en sistemas dinámicos. A diferencia de los sensores convencionales, estos incorporan algoritmos que permiten la estimación de parámetros y estados, dotando al sistema de mayor precisión y autonomía en la toma de decisiones. En este contexto, los métodos de identificación y estimación juegan un papel fundamental en el desarrollo de sensores.</p>
        <p>A lo largo de los capítulos presentados, se aborda distintas estrategias basadas en mínimos cuadrados para la identificación de sistemas y su aplicación en sensores inteligentes. En el primer capítulo, se presentan los fundamentos de los mínimos cuadrados en sus variantes ordinaria, recursiva y con factor de olvido, resaltando su importancia en la estimación de parámetros en tiempo real. Posteriormente, en el segundo capítulo, se analiza el caso de una galga extensiométrica modelada como un sistema dinámico, donde se aplica la estimación por mínimos cuadrados para determinar la masa aplicada sobre ella.</p>
        <p>En el tercer capítulo, se introduce un enfoque basado en la estimación de la entrada de un sistema mediante mínimos cuadrados recursivos, lo que amplía las capacidades de los sensores inteligentes más allá de la simple medición de variables de salida. Finalmente, en el cuarto capítulo, se presenta un caso práctico que ejemplifica la aplicación de técnicas en la identificación de un sistema masa-resorte-amortiguador. En este caso, se emplea un sensor de posición junto con el método N4SID, basado en subespacios, para estimar parámetros físicos como la constante del resorte y el coeficiente de fricción del aire. Además, se analiza la estimación de la velocidad mediante diferentes enfoques: la derivación numérica, un observador de estados y el filtro de Savitzky-Golay. Se comparan sus ventajas y limitaciones, destacando cómo el observador permite una estimación más estable en tiempo real, mientras que el filtro es útil para suavizar señales en aplicaciones fuera de línea.</p>
        <p>A lo largo de estos capítulos, se demuestra cómo la combinación de sensores y algoritmos de estimación permite mejorar la precisión, confiabilidad y funcionalidad de los sistemas de medición, abriendo nuevas posibilidades en el desarrollo de sensores inteligentes para diversas aplicaciones en ingeniería.</p>
    </div>

    <div class="landing-card fade-in delay-3">
        <h2><span class="icon">🔴</span> Alcance del material</h2>
        <p>Este libro virtual aborda técnicas de identificación y estimación aplicadas al diseño y análisis de sensores inteligentes, cubriendo métodos de mínimos cuadrados, modelado dinámico de sensores, estimación de entradas/estados y un caso práctico integrador. El alcance educativo dependerá del contexto de uso que diseñe la persona docente.</p>
    </div>

    <div class="landing-card fade-in delay-3">
        <h2><span class="icon">🔴</span> Sobre el uso de este recurso</h2>
        <p>Este libro virtual es un <strong>material de referencia y consulta</strong>, no una secuencia instruccional autocontenida. Su función es análoga a la de un libro de texto que acompaña un curso: proporciona los fundamentos teóricos, las derivaciones matemáticas y los ejemplos de código que el estudiantado necesitará consultar al enfrentar los retos planteados en las prácticas.</p>
        <p>El recurso complementario <em>"Prácticas de Sensores Inteligentes"</em> contiene los ejercicios, retos y actividades prácticas diseñados como punto de partida. La <strong>secuencia didáctica recomendada</strong> es:</p>
        <ol>
            <li>La persona docente presenta el problema o caso práctico (desde las <em>Prácticas</em>).</li>
            <li>El estudiantado investiga y explora posibles soluciones.</li>
            <li>Este libro virtual se consulta como fuente de apoyo para resolver dicho reto.</li>
        </ol>
        <p>Es decir, la secuencia de uso está concebida como <strong>práctica &rarr; consulta del libro</strong>, no a la inversa.</p>
        <p>Consulta las prácticas en: <a href="https://sitios.iingen.unam.mx/PracticasSensoresInteligentes/" target="_blank">sitios.iingen.unam.mx/PracticasSensoresInteligentes</a></p>
    </div>

    <div class="landing-card fade-in delay-3">
        <h2><span class="icon">🔴</span> Autores y Créditos</h2>
        <p>Desarrollado por el equipo del Laboratorio de Sensores Inteligentes del Instituto de Ingeniería:</p>
        <ul>
            <li><strong>Daan Yael Maldonado Uriostigue</strong> - <a href="mailto:DMaldonadoU@iingen.unam.mx" style="color: #cc0000;">DMaldonadoU@iingen.unam.mx</a></li>
            <li><strong>Roberto Giovanni Ramírez Chavarría</strong> - <a href="mailto:RRamirezC@iingen.unam.mx" style="color: #cc0000;">RRamirezC@iingen.unam.mx</a></li>
        </ul>
        <p style="font-size: 0.9em; margin-top: 15px; border-top: 1px solid #eee; padding-top: 10px;">
            <em>Este trabajo fue realizado gracias al apoyo de UNAM-DGAPA-PAPIME a través del proyecto PE101524.</em>
            <br>
            <strong>Fecha de Postulación:</strong> Diciembre de 2025
        </p>
    </div>

    <div class="landing-card fade-in delay-3">
        <h2><span class="icon">🔴</span> Licencia y Cita del Material</h2>
        <p><strong>Licencia de uso:</strong> D. R.©, 2025, UNAM - CC BY-NC-SA</p>
        <p><strong>Cita del recurso:</strong> Maldonado-Uriostigue, D. Y., & Ramírez-Chavarría, R. G. (2025). <em>Apuntes de Sensores Inteligentes</em>. <a href="https://sitios.iingen.unam.mx/ApuntesSensoresInteligentes/landing.html" target="_blank">https://sitios.iingen.unam.mx/ApuntesSensoresInteligentes/landing.html</a></p>
        <p>Esta obra está bajo una licencia <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" target="_blank">Creative Commons Atribución/Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional</a>.</p>
    </div>

</div>
```

```{tableofcontents}
```
