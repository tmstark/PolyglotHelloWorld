<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PolyglotHelloWorld</title>
    <style>
        body {
            text-align: center;
        }
        h1 {
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
        }
        #englishButton {
            background-color: #66ccff;
        }
        #spanishButton {
            background-color: #ffcc66;
        }
        #frenchButton {
            background-color: #66ff66;
        }
    </style>
</head>
<body>

    <h1 id="outputText">Hello World</h1>

    <button id="englishButton" onclick="changeText('Hello World', '#66ccff')">English</button>
    <button id="spanishButton" onclick="changeText('Hola Mundo', '#ffcc66')">Spanish</button>
    <button id="frenchButton" onclick="changeText('Bonjour le Monde', '#66ff66')">French</button>

    <script>
        function changeText(text, bgColor) {
            document.getElementById('outputText').innerText = text;
            document.getElementById('outputText').style.backgroundColor = bgColor;
        }
    </script>

</body>
</html>

