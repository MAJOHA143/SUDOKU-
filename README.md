<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width initial-scale=1.0 user-scalable=no">
        <title>Sudoku</title>

        <link rel="stylesheet" href="Soduko.css">
        <script src="Soduko.js"></script>
    </head>
       
    <body>
        <div>
            
        </div>
        <div id="start-screen" class="container-start">
            <h1>SUDOKU</h1>
            <button class="blue" onclick="startGame()">Start</button>
        </div>

        <div id="container">
        <!-- 9x9 board -->
        <div id="board" class="initial-hidden">
        </div>
        
        <br>
    
        <div id="digits" class="initial-hidden"></div>
        <h1 id="game-title" class="hidden">SUDOKU GAME</h1>

    </div>
    </body>


</html>

