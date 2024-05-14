<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Play Tic Tac Online</title>
    <p>BEST GAME ONLINE TIC TAC TOE</p>
    <link rel="stylesheet" href="./Css/game.css">
</head>
<body id="body">
    <!-- This container is needed to overlay our canvas over our tabl.-->
    <div class="center-container">
        <!--NOTE: Canvas width and height must be within the element.-->
        <canvas id="win-lines" width="608" height="608"></canvas>
        <table>
            <tr>
                <td id="0" onclick="placeXOrO('0')"></td>
                <td id="1" onclick="placeXOrO('1')"></td>
                <td id="2" onclick="placeXOrO('2')"></td>
            </tr>
            <tr>
                <td id="3" onclick="placeXOrO('3')"></td>
                <td id="4" onclick="placeXOrO('4')"></td>
                <td id="5" onclick="placeXOrO('5')"></td>
            </tr>
            <tr>
                <td id="6" onclick="placeXOrO('6')"></td>
                <td id="7" onclick="placeXOrO('7')"></td>
                <td id="8" onclick="placeXOrO('8')"></td>
            </tr>
        </table>
    </div>
    
</body>
</html>
