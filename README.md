# Rossana-Mendoza
<!DOCTYPE html>
<html>
    <head>
        <title>Calculadora Basal</title>
        <link rel="stylesheet" href="./style.css">
        <script src="script.js" defer></script>
    </head>
    <body>
        <div id="contenedor">
            <div id="calculadora">
                <div class="contenido">
                    <h1>Hidratación Basal</h1>
                    <p class="item">Completa todos los datos</p>
                    <input class="item" id="peso" type="number" placeholder="Ingrese el peso del paciente en kg" />
                    <p class="item" id="error">* Debe completar todos los datos</p>
                    <button class="item" id="calcular">Calcular</button>
                    <p class="item resultado" id="flu">71cc/h</p>
                    <p class="item resultado" id="man">m+m/2 : 105cc/h</p>
                </div>
            </div>
            <div id="detalle">
                <div class="contenido">
                    <h1>¿Como se calcula?</h1>
                    <ul>
                        <li>De 0kg a 10kg, se calcula 100cc por cada kilo.</li>
                        <li>Se suman 50cc por cada kilo de peso por arriba de 10kg, hasta 20kg</li>
                        <li>De 20kg para arriba, se suman 20cc por cada kilo adicional</li>
                    </ul>
                </div>
            </div>
        </div>
    </body>
</html>
