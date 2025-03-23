
<!doctype html>
<html lang="pt-BR">
<!---CRTL + SHFT + K(APAGA LINHA)-->
<!---SHIFT + ALT + SETA(DUPLICA)-->
<!---CTRL + SHIFT + K(APAGA LINHA)-->
<!--ALT + CLICK(SELECIONA PALAVRAS)-->

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="calculator">
        <div class="display" id="display"></div>
        <div class="buttons">
            <button class="button red" onclick="clearDisplay()">C</button>
            <button class="button light-gray" onclick="appendOperator('%')">%</button>
            <button class="button light-gray" onclick="appendOperator('.')">.</button>
            <button class="button orange" onclick="appendOperator('/')">/</button>
            <button class="button dark-gray" onclick="appendNumber('7')">7</button>
            <button class="button dark-gray" onclick="appendNumber('8')">8</button>
            <button class="button dark-gray" onclick="appendNumber('9')">9</button>
            <button class="button orange" onclick="appendOperator('*')">*</button>
            <button class="button dark-gray" onclick="appendNumber('4')">4</button>
            <button class="button dark-gray" onclick="appendNumber('5')">5</button>
            <button class="button dark-gray" onclick="appendNumber('6')">6</button>
            <button class="button orange" onclick="appendOperator('-')">-</button>
            <button class="button dark-gray" onclick="appendNumber('1')">1</button>
            <button class="button dark-gray" onclick="appendNumber('2')">2</button>
            <button class="button dark-gray" onclick="appendNumber('3')">3</button>
            <button class="button orange" onclick="appendOperator('+')">+</button>
            <button class="button dark-gray wide" onclick="appendNumber('0')">0</button>
            <button class="button orange wide" onclick="calculate()">=</button>
        </div>
    </div>

    <script src="scripts.js" </body>
