<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Çarpma ve Toplama Hesaplaması</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        input {
            width: 60px;
        }
    </style>
</head>
<body>
    <h1>Çarpma ve Toplama Hesaplaması</h1>
    <label for="firstNum">İlk Sayı:</label>
    <input type="number" id="firstNum">
    <br>
    <label for="secondNum">İkinci Sayı:</label>
    <input type="number" id="secondNum">
    <br>
    <label for="desiredNum">İstenilen Sayı:</label>
    <input type="number" id="desiredNum">
    <br>
    <button onclick="calculate()">Hesapla</button>
    <br>
    <p id="result"></p>

    <script>
        function calculate() {
            var firstNum = parseInt(document.getElementById("firstNum").value);
            var secondNum = parseInt(document.getElementById("secondNum").value);
            var desiredNum = parseInt(document.getElementById("desiredNum").value);

            var result = (firstNum * 1 + secondNum * 2) * desiredNum;

            document.getElementById("result").innerText = "Sonuç: " + result;
        }
    </script>
</body>
</html>
