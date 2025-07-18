<!DOCTYPE html>
<html lang="es" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Acerca del Laboratorio de Vectores</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0a0e1a;
            background-image: radial-gradient(circle at top right, rgba(12, 74, 110, 0.2), transparent 50%),
                              radial-gradient(circle at bottom left, rgba(13, 96, 96, 0.15), transparent 60%);
        }
        .content-section h2 {
            border-bottom: 2px solid #374151; /* gray-700 */
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
            font-size: 1.5rem;
            font-weight: bold;
            color: #16a34a; /* green-600 */
        }
        .content-section h3 {
            font-size: 1.25rem;
            font-weight: bold;
            color: #0ea5e9; /* sky-500 */
            margin-top: 1.5rem;
            margin-bottom: 0.5rem;
        }
        .content-section p, .content-section li {
            color: #d1d5db; /* gray-300 */
            line-height: 1.75;
        }
        .content-section ul {
            list-style-position: inside;
            padding-left: 0.5rem;
        }
        .content-section code {
            background-color: #374151; /* gray-700 */
            color: #e5e7eb; /* gray-200 */
            padding: 0.2rem 0.4rem;
            border-radius: 0.25rem;
            font-family: monospace;
        }
        .content-section a {
            color: #2563eb; /* blue-600 */
            text-decoration: underline;
        }
        .content-section strong {
            color: #f59e0b; /* amber-500 */
        }
    </style>
</head>
<body class="text-gray-200 min-h-screen">

    <div class="max-w-4xl mx-auto p-6 md:p-12">
        
        <div class="flex justify-between items-center mb-8">
            <h1 class="text-4xl font-bold text-white">Laboratorio de Adición de Vectores</h1>
            <a href="./index.html" class="text-sm bg-cyan-600 hover:bg-cyan-700 text-white py-2 px-4 rounded-lg transition-colors whitespace-nowrap">&larr; Volver al Menú</a>
        </div>

        <div class="bg-gray-800/50 backdrop-blur-sm p-8 rounded-xl shadow-2xl">
            <p class="text-lg mb-8">
                ¡Bienvenido al Laboratorio de Adición de Vectores! Una colección de simulaciones interactivas diseñadas para explorar los principios de la suma de vectores de una manera visual e intuitiva. Este proyecto ha sido creado por <strong>AulaQuest</strong> para ayudar a estudiantes y entusiastas de la física a comprender mejor cómo funcionan los vectores.
            </p>

            <div class="content-section mb-8">
                <h2>🚀 Laboratorios Disponibles</h2>
                <p>Este proyecto está organizado en varios módulos, cada uno centrado en un aspecto diferente de la adición de vectores.</p>

                <h3>1. Laboratorio 1D</h3>
                <ul>
                    <li><strong>Archivo:</strong> <code>lab-1d.html</code></li>
                    <li><strong>Descripción:</strong> Una introducción sencilla a la suma de vectores en una sola dimensión. Arrastra los vectores sobre una línea y observa cómo se suman sus magnitudes de forma colineal.</li>
                </ul>

                <h3>2. Laboratorio 2D Cartesiano</h3>
                <ul>
                    <li><strong>Archivo:</strong> <code>lab-2d-cartesian.html</code></li>
                    <li><strong>Descripción:</strong> Explora la suma de vectores en un plano cartesiano. Manipula los vectores arrastrando sus cabezas y visualiza sus componentes <code>(x, y)</code>, así como el vector resultante.</li>
                </ul>

                <h3>3. Laboratorio 2D Polar</h3>
                <ul>
                    <li><strong>Archivo:</strong> <code>lab-2d-polar.html</code></li>
                    <li><strong>Descripción:</strong> Define y suma vectores utilizando coordenadas polares. Ajusta el módulo (magnitud) y el ángulo de cada vector para ver cómo afectan al resultado final.</li>
                </ul>

                <h3>4. Ecuaciones</h3>
                <ul>
                    <li><strong>Archivo:</strong> <code>lab-equations.html</code></li>
                    <li><strong>Descripción:</strong> Un explorador que conecta la representación gráfica de los vectores con su forma matemática. Ideal para entender la relación entre el álgebra y la geometría de los vectores.</li>
                </ul>
            </div>

            <div class="content-section mb-8">
                <h2>🛠️ Cómo Utilizar</h2>
                <ol class="list-decimal list-inside space-y-2">
                    <li><strong>Navegación:</strong> Abre el archivo <code>index.html</code> para ver el menú principal.</li>
                    <li><strong>Selecciona un Laboratorio:</strong> Haz clic en cualquiera de las tarjetas para iniciar la simulación correspondiente.</li>
                    <li><strong>Interactúa:</strong> Dentro de cada laboratorio, puedes arrastrar los vectores, cambiar sus propiedades y utilizar los controles en el panel para explorar diferentes escenarios.</li>
                    <li><strong>Volver al Menú:</strong> Cada laboratorio tiene un botón para regresar fácilmente al menú principal.</li>
                </ol>
                <p class="mt-4">El proyecto está diseñado para funcionar en cualquier navegador web moderno. No se requiere instalación.</p>
            </div>

            <div class="content-section mb-8">
                <h2>💻 Tecnologías Utilizadas</h2>
                <ul class="list-disc">
                    <li><strong>HTML5:</strong> Para la estructura de las páginas.</li>
                    <li><strong>CSS3 y Tailwind CSS:</strong> Para el diseño y los estilos modernos y responsivos.</li>
                    <li><strong>JavaScript (ES6+):</strong> Para toda la lógica de las simulaciones, interacciones y cálculos en el <code>&lt;canvas&gt;</code>.</li>
                </ul>
            </div>

            <div class="content-section text-center border-t border-gray-700 pt-6 mt-8">
                <h2 class="border-none text-fuchsia-500">✨ Créditos</h2>
                <p>Este proyecto ha sido diseñado y desarrollado con pasión por:</p>
                <p class="font-bold text-lg mt-2">
                    <a href="https://aulaquest.com" target="_blank" rel="noopener noreferrer" class="text-cyan-400 hover:text-cyan-300">
                        AulaQuest
                    </a>
                </p>
                <p class="mt-4">¡Esperamos que disfrutes explorando el mundo de los vectores!</p>
            </div>

        </div>
    </div>

</body>
</html>

