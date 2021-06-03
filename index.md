<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>By Definition</title>

    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
    <meta name="apple-mobile-web-app-capable" content="yes">

    <style>
        .app {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            text-align: center;
            font-family: sans-serif;
            color: rgb(0, 0, 0);
        }

        .bg {
            background: #7e0707;
            background-image: url("Assetination/garageBG2.png");
            background-position: center;
            background-size: cover;
            filter: blur(0px);
            transform: scale(1.5);
            width: 100%;
            height: 100%;
            z-index: 0;
            position: fixed;
            left: 0;
            top: 0;

        }

        img {
            padding: 10px;
            max-width: 85%;
            max-height: 85%;

        }

        h3 {
            font-size: 30px;
            margin: 50px;
        }

        p {
            background: white;
            color: black;
            padding: 25px;

        }

        button {
            background: black;
            color: white;
            padding: 15px;
            border: none;
            transition: 100ms;
            outline: none;

        }


        button:hover {
            background: white;
            color: black;
        }

        .logo,
        .title,
        .text,
        .button {
            height: 25%;
        }

        .footer {
            z-index: 2;
            width: 100%;
            text-align: center;
            position: fixed;
            bottom: 0;
            font-family: sans-serif;
            opacity: 0.5;
            padding: 5px;
            left: 0;
            font-size: 10px;
        }

        a {
            text-decoration: none;
            color: white;
        }
    </style>
</head>

<body>




    <div class="app">
        <div class="logo">

        </div>
        <div class="title">
            <h3 id="peter"></h3>
        </div>
        <div class="button">

            <img id="def" src="Assetination/definition00.png">
            <br> </br>
            <button onClick="explain();">Beispiel anzeigen</button>

        </div>
        <div class="button">
            <br> </br>
            <br> </br>

            <button onClick="random();">Zufällig</button>
        </div>
    </div>

    <script type="text/javascript">

        var i = 1
        var definition01 = "Assetination/definition01.png"
        var definition02 = "Assetination/definition02.png"
        var definition03 = "Assetination/definition03.png"
        var definition04 = "Assetination/definition04.png"
        var definition05 = "Assetination/definition05.png"
        var definition06 = "Assetination/definition06.png"
        var definition07 = "Assetination/definition07.png"
        var definition08 = "Assetination/definition08.png"
        var definition09 = "Assetination/definition09.png"
        var definition10 = "Assetination/definition10.png"

        var pic01 = "Assetination/pic01.png"
        var pic02 = "Assetination/pic02.png"
        var pic03 = "Assetination/pic03.png"
        var pic04 = "Assetination/pic04.png"
        var pic05 = "Assetination/pic05.png"
        var pic06 = "Assetination/pic06.png"
        var pic07 = "Assetination/pic07.png"
        var pic08 = "Assetination/pic08.png"
        var pic09 = "Assetination/pic09.png"
        var pic10 = "Assetination/pic10.png"

            document.body.style.backgroundImage = "Assetination/definition00.png"

            var pics = [
            definition01,
            definition02,
            definition03,
            definition04,
            definition05,
            definition06,
            definition07,
            definition08,
            definition09,
            definition10
            ];
            function random() {
                var i = Math.floor(Math.random() * Math.floor(10));
                document.getElementById("def").src = pics[i];
                console.log(document.getElementById("def").src)

            
                document.body.style.webkitBackgroundSize = "cover"
                console.log(i)
            }
        

            function explain() {
                if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition01.png") {
                    document.body.style.backgroundImage = "url(" + pic01 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition02.png") {
                    document.body.style.backgroundImage = "url(" + pic02 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition03.png") {
                    document.body.style.backgroundImage = "url(" + pic03 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition04.png") {
                    document.body.style.backgroundImage = "url(" + pic04 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition05.png") {
                    document.body.style.backgroundImage = "url(" + pic05 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition06.png") {
                    document.body.style.backgroundImage = "url(" + pic06 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition07.png") {
                    document.body.style.backgroundImage = "url(" + pic07 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition08.png") {
                    document.body.style.backgroundImage = "url(" + pic08 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition09.png") {
                    document.body.style.backgroundImage = "url(" + pic09 + ")"
                }
                else if (document.getElementById("def").src == "https://kaboomfisch.github.io/Not-Wrong-Definitions/Assetination/definition10.png") {
                    document.body.style.backgroundImage = "url(" + pic10 + ")"
                }
                console.log(document.getElementById("def").src)
            }

    </script>
    <script defer=""></script>
    </div>
    </div>
    <div class="footer">
        <a></a>
    </div>
</body>

</html>