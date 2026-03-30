# Introduction
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Proyecto Increíble</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header */
        header {
            background: white;
            padding: 40px 20px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            margin-bottom: 40px;
        }

        header h1 {
            font-size: 3em;
            color: #667eea;
            margin-bottom: 10px;
            animation: fadeInDown 0.8s ease;
        }

        header p {
            font-size: 1.2em;
            color: #666;
            animation: fadeInUp 0.8s ease;
        }

        /* Badges */
        .badges {
            display: flex;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
            flex-wrap: wrap;
        }

        .badge {
            display: inline-block;
            padding: 8px 15px;
            background: #667eea;
            color: white;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: bold;
        }

        .badge.success { background: #10b981; }
        .badge.warning { background: #f59e0b; }
        .badge.danger { background: #ef4444; }

        /* Secciones */
        section {
            background: white;
            padding: 40px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            animation: fadeIn 0.8s ease;
        }

        section h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
        }

        section h3 {
            color: #764ba2;
            font-size: 1.5em;
            margin-top: 20px;
            margin-bottom: 10px;
        }

        /* Características */
        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .feature-card {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .feature-card:hover {
            transform: translateY(-10px);
        }

        .feature-card h3 {
            color: white;
            margin-bottom: 10px;
        }

        .emoji {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        /* Botones */
        .buttons {
            display: flex;
            gap: 10px;
            margin: 20px 0;
            flex-wrap: wrap;
        }

        .btn {
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-primary {
            background: #667eea;
            color: white;
        }

        .btn-primary:hover {
            background: #764ba2;
            transform: scale(1.05);
        }

        .btn-secondary {
            background: #10b981;
            color: white;
        }

        .btn-secondary:hover {
            background: #059669;
            transform: scale(1.05);
        }

        /* Código */
        code {
            background: #f3f4f6;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            color: #e11d48;
        }

        pre {
            background: #1f2937;
            color: #10b981;
            padding: 20px;
            border-radius: 10px;
            overflow-x: auto;
            margin: 20px 0;
            font-family: 'Courier New', monospace;
        }

        /* Footer */
        footer {
            background: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            color: #666;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        /* Animaciones */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            section {
                padding: 20px;
            }
            .features {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header>
            <h1>🚀 Mi Proyecto Increíble</h1>
            <p>Una solución moderna y elegante para tus necesidades</p>
            <div class="badges">
                <span class="badge success">✓ Activo</span>
                <span class="badge">v1.0.0</span>
                <span class="badge">MIT License</span>
            </div>
        </header>

        <!-- Descripción -->
        <section>
            <h2>📋 Descripción</h2>
            <p>
                Este es un proyecto de ejemplo que demuestra cómo crear una página web 
                decorativa y moderna. Incluye diseño responsivo, animaciones suaves y 
                una estructura limpia.
            </p>
        </section>

        <!-- Características -->
        <section>
            <h2>✨ Características Principales</h2>
            <div class="features">
                <div class="feature-card">
                    <div class="emoji">🎨</div>
                    <h3>Diseño Moderno</h3>
                    <p>Interfaz visual atractiva y profesional</p>
                </div>
                <div class="feature-card">
                    <div class="emoji">📱</div>
                    <h3>Responsivo</h3>
                    <p>Se adapta a cualquier dispositivo</p>
                </div>
                <div class="feature-card">
                    <div class="emoji">⚡</div>
                    <h3>Rápido</h3>
                    <p>Optimizado para máximo rendimiento</p>
                </div>
            </div>
        </section>

        <!-- Instalación -->
        <section>
            <h2>🔧 Instalación</h2>
            <h3>Paso 1: Clonar el repositorio</h3>
            <pre>git clone https://github.com/tuusuario/tuproyecto.git</pre>
            
            <h3>Paso 2: Instalar dependencias</h3>
            <pre>npm install</pre>
            
            <h3>Paso 3: Ejecutar el proyecto</h3>
            <pre>npm start</pre>
        </section>

        <!-- Uso -->
        <section>
            <h2>📚 Uso</h2>
            <p>Aquí va la documentación de cómo usar tu proyecto:</p>
            <pre>// Ejemplo de código
const miProyecto = new ProyectoIncreible();
miProyecto.inicializar();
miProyecto.ejecutar();</pre>
        </section>

        <!-- Botones de Acción -->
        <section>
            <h2>🎯 Acciones</h2>
            <div class="buttons">
                <a href="https://github.com" class="btn btn-primary">Ver en GitHub</a>
                <a href="#" class="btn btn-secondary">Descargar</a>
            </div>
        </section>

        <!-- Contribuciones -->
        <section>
            <h2>🤝 Contribuciones</h2>
            <p>¿Quieres contribuir? ¡Genial! Por favor:</p>
            <ol style="margin-left: 20px;">
                <li>Haz un Fork del repositorio</li>
                <li>Crea una rama para tu feature (<code>git checkout -b feature/AmazingFeature</code>)</li>
                <li>Commit tus cambios (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
                <li>Push a la rama (<code>git push origin feature/AmazingFeature</code>)</li>
                <li>Abre un Pull Request</li>
            </ol>
        </section>

        <!-- Footer -->
        <footer>
            <p>&copy; 2026 Mi Proyecto. Todos los derechos reservados. | Hecho con ❤️</p>
        </footer>
    </div>
</body>
</html>
