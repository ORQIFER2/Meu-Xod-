# Meu-Xod-
Te amo 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Para el amor de mi vida</title>
    <style>
        body {
            background: #fddde6;
            font-family: 'Arial', sans-serif;
            color: #5C4033;
            text-align: center;
            padding: 20px;
        }
        .Love__You {
            margin: 0;
            padding: 20px;
            background: #F5E0DC;
            font-size: 20px;
            font-family: 'Love', sans-serif;
            color: #5C4033;
            overflow: auto;
            border-radius: 10px;
            display: inline-block;
        }
        img {
            width: 300px;
            margin: 20px 0;
        }
        .contador {
            font-size: 18px;
            margin-top: 10px;
            color: #5C4033;
        }
    </style>
</head>
<body>

    <div class="Love__You">
        <h2>Para el amor de mi vida:</h2>
        <p>
            Si pudiera elegir un lugar seguro, sería a tu lado.<br>
            Cuanto más tiempo estoy contigo, más te amo.<br>
            Este texto es solo un ejemplo de demostración y no refleja sentimientos reales.<br>
            — ¡I Love You!
        </p>
        <img src="https://cdn.pixabay.com/photo/2021/01/22/18/50/heart-5940729_1280.png" alt="Árbol en forma de corazón">
        
        <div class="contador">
            Mi amor por ti comenzó hace...<br>
            <span id="contador"></span>
        </div>
    </div>

    <script>
        const fechaInicio = new Date('2023-06-24T00:00:00'); // Aquí cambia la fecha si deseas
        const contador = document.getElementById('contador');

        function actualizarContador() {
            const ahora = new Date();
            const diferencia = ahora - fechaInicio;

            const dias = Math.floor(diferencia / (1000 * 60 * 60 * 24));
            const horas = Math.floor((diferencia / (1000 * 60 * 60)) % 24);
            const minutos = Math.floor((diferencia / (1000 * 60)) % 60);
            const segundos = Math.floor((diferencia / 1000) % 60);

            contador.textContent = `${dias} días ${horas} horas ${minutos} minutos ${segundos} segundos`;
        }

        setInterval(actualizarContador, 1000);
        actualizarContador();
    </script>

</body>
</html>
