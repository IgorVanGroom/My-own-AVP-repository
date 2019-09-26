<!doctype html>
<html>
    <head>
        <title>AVPRG Aufgabe 2</title>
    </head>
    <body>
        <script src="../../navigation.js" onload="init(2)"></script>
        <div id="mainContainer">
            <!-- Dies ist der Code für die Aufgabe -->
            <h1>Please enter a midi note between 0 and 127 and get the corresponding frequency.</h1>

            <input type="text" id="myMidiInput">

            <button type="button" id="myButton">Convert!</button>

            <div id="outputText"></div>

            <script src="convertScript.js"></script>
            <!--------------------------------------->
        </div>
    </body>
</html>