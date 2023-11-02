<html lang="es">
<head>
    <meta charset="UTF-8">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .question {
            margin-bottom: 20px;
            text-align: left;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }

        .options {
            margin-top: 10px;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        input[type="radio"] {
            margin-right: 5px;
        }

        .button-container {
            text-align: center;
            margin-top: 20px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .result-container {
            margin-top: 20px;
        }

        .incorrect {
            color: red;
        }
    </style>
</head>
<body>
    <h1>Ensamble y Desensamble de PC</h1>

    <div class="container">
        <div class="question">
            <p>Pregunta 1: ¿Cuál es el propósito principal de una pulsera antiestática al ensamblar una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q1" value="a"> a. Mantener las manos limpias.</label>
                <label><input type="radio" name="q1" value="b"> b. Prevenir descargas electrostáticas que pueden dañar los componentes.</label>
                <label><input type="radio" name="q1" value="c"> c. Proteger contra virus informáticos.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 2: ¿Qué herramienta se usa comúnmente para atornillar componentes en una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q2" value="a"> a. Destornillador</label>
                <label><input type="radio" name="q2" value="b"> b. Martillo</label>
                <label><input type="radio" name="q2" value="c"> c. Llave inglesa</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 3: ¿Qué precaución debes tomar antes de tocar cualquier componente interno de una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q3" value="a"> a. Usar guantes de goma.</label>
                <label><input type="radio" name="q3" value="b"> b. Asegurarse de que la computadora esté enchufada.</label>
                <label><input type="radio" name="q3" value="c"> c. Apagar y desconectar la computadora de la fuente de alimentación y tocar una superficie metálica para descargar la electricidad estática de tu cuerpo.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 4: ¿Qué tipo de ranura de expansión se utiliza para agregar tarjetas de sonido, tarjetas de red y tarjetas gráficas a una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q4" value="a"> a. PCI Express</label>
                <label><input type="radio" name="q4" value="b"> b. SATA</label>
                <label><input type="radio" name="q4" value="c"> c. USB</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 5: ¿Qué tipo de computadora es generalmente más fácil de actualizar en cuanto a componentes como la RAM o el almacenamiento?</p>
            <div class="options">
                <label><input type="radio" name="q5" value="a"> a. PC de escritorio</label>
                <label><input type="radio" name="q5" value="b"> b. Portátil</label>
                <label><input type="radio" name="q5" value="c"> c. Ninguna de las anteriores se puede actualizar.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 6: ¿Qué describe mejor la facilidad de actualizar portátiles en comparación con PC de escritorio?</p>
            <div class="options">
                <label><input type="radio" name="q6" value="a"> a. Los portátiles son generalmente más fáciles de actualizar en cuanto a componentes como la tarjeta gráfica.</label>
                <label><input type="radio" name="q6" value="b"> b. Los portátiles son más difíciles de actualizar en comparación con las PC de escritorio.</label>
                <label><input type="radio" name="q6" value="c"> c. Los portátiles y las PC de escritorio tienen la misma facilidad de actualización.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 7: ¿Cuál es el propósito de la pasta térmica al ensamblar una CPU?</p>
            <div class="options">
                <label><input type="radio" name="q7" value="a"> a. Proporciona energía eléctrica a la CPU.</label>
                <label><input type="radio" name="q7" value="b"> b. Facilita la comunicación entre la CPU y la placa base.</label>
                <label><input type="radio" name="q7" value="c"> c. Ayuda a disipar el calor de la CPU y mantenerla a una temperatura adecuada.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 8: ¿Por qué es importante usar tornillos para asegurar componentes al ensamblar una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q8" value="a"> a. Los tornillos no son necesarios; los componentes pueden encajar sin ellos.</label>
                <label><input type="radio" name="q8" value="b"> b. Los tornillos ayudan a mantener los componentes seguros y evitan que se muevan o se dañen.</label>
                <label><input type="radio" name="q8" value="c"> c. Los tornillos complican el proceso de ensamblaje y deben evitarse.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 9: ¿Qué componente de hardware de una computadora se instala típicamente en una bahía específica dentro del estuche?</p>
            <div class="options">
                <label><input type="radio" name="q9" value="a"> a. Placa madre</label>
                <label><input type="radio" name="q9" value="b"> b. Fuente de alimentación</label>
                <label><input type="radio" name="q9" value="c"> c. Disco duro</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 10: ¿Cuál es la importancia de asegurarse de que los cables estén enrutados y organizados adecuadamente dentro del estuche al ensamblar una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q10" value="a"> a. No es necesario preocuparse por la organización de los cables.</label>
                <label><input type="radio" name="q10" value="b"> b. Ayuda a mantener un flujo de aire adecuado y evita que los cables obstruyan los componentes o se dañen por el calor.</label>
                <label><input type="radio" name="q10" value="c"> c. Aumenta el rendimiento general de la computadora.</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 11: ¿Cuál de las siguientes herramientas se utiliza comúnmente para asegurar y organizar cables dentro de una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q11" value="a"> a. Destornillador</label>
                <label><input type="radio" name="q11" value="b"> b. Alicates</label>
                <label><input type="radio" name="q11" value="c"> c. Bridas de cables o sujetacables</label>
            </div>
        </div>

        <div class="question">
            <p>Pregunta 12: ¿Por qué es importante conectar los cables correctamente a la placa madre y otros componentes al ensamblar una computadora?</p>
            <div class="options">
                <label><input type="radio" name="q12" value="a"> a. No importa cómo se conecten los cables, ya que no afecta su funcionamiento.</label>
                <label><input type="radio" name="q12" value="b"> b. Para evitar posibles cortocircuitos y asegurar que los componentes funcionen correctamente y se comuniquen entre sí.</label>
                <label><input type="radio" name="q12" value="c"> c. Para aumentar el rendimiento de la computadora.</label>
            </div>
        </div>

        <div class="button-container">
            <button onclick="calculateScore()">Calcular Puntuación</button>
        </div>

        <div class="result-container">
            <p id="score"></p>
            <p id="incorrectAnswers" class="incorrect"></p>
        </div>
    </div>

    <script>
        function calculateScore() {
            var score = 0;
            var answers = ["b", "a", "c", "b", "a", "b", "c", "b", "c", "b", "c", "b"];
            var userAnswers = [];

            for (var i = 1; i <= 12; i++) {
                var selection = document.querySelector('input[name="q' + i + '"]:checked');
                if (selection) {
                    userAnswers.push(selection.value);
                    if (selection.value === answers[i - 1]) {
                        score++;
                    }
                } else {
                    userAnswers.push("");
                }
            }

            var result = "Puntuación: " + score + " respuestas correctas de 12";
            document.getElementById("score").innerHTML = result;

            // Mostrar respuestas incorrectas
            var incorrectAnswers = [];
            for (var i = 0; i < answers.length; i++) {
                if (userAnswers[i] !== answers[i]) {
                    incorrectAnswers.push("Pregunta " + (i + 1) + ": Tu respuesta - " + userAnswers[i] + ", Respuesta correcta - " + answers[i]);
                }
            }

            var incorrectAnswersText = incorrectAnswers.length > 0 ? "Respuestas incorrectas: " + incorrectAnswers.join(", ") : "Todas las respuestas son correctas";
            document.getElementById("incorrectAnswers").innerHTML = incorrectAnswersText;
        }
    </script>
</body>
</html>
