<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre mí y Mis Stats de GitHub</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            padding: 50px;
        }
        .stats-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }
        .stats-container img {
            width: 400px; 
            height: auto;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .description {
            margin-bottom: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>

    <h1>Sobre mí</h1>
    
    <div class="description">
        <p>Hola, soy Tomás, estudiante de Licenciatura en Sistemas en la UNLP. Me gusta el desarrollo de software y aprender constantemente nuevas herramientas para poder mejorar mis habilidades.</p>
        <p>Actualemnte estoy en 2do año de la carrera</p>
    </div>
    
    <h1>Mis Stats de GitHub</h1>
    
    <div class="stats-container">
        <!-- Tarjeta con estadísticas del perfil -->
        <img src="https://github-readme-stats.vercel.app/api?username=TomasCurcio04&show_icons=true&theme=radical&count_private=true" alt="Estadísticas de GitHub" />
        
        <!-- Tarjeta con los lenguajes más usados -->
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TomasCurcio04&layout=compact&theme=radical" alt="Lenguajes más usados en GitHub" />
    </div>

</body>
</html>
