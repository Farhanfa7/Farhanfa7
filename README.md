<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic Tac Toe</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Tic-Tac-Toe Game</h1>
        </header>

        <section id="player-info">
            <h2>Enter Player Details</h2>
            <div>
                <input type="text" id="player1" placeholder="Enter Player 1 Name" required>
                <input type="text" id="player2" placeholder="Enter Player 2 Name" required>
            </div>
            <div>
                <label for="mode">Choose Mode:</label>
                <select id="mode">
                    <option value="offline">Offline</option>
                    <option value="online">Online</option>
                </select>
            </div>
            <button onclick="startGame()">Start Game</button>
        </section>

        <section id="game-board" style="display:none;">
            <h2><span id="current-player"></span>'s Turn</h2>
            <div id="timer">Time Left: <span id="time-left">10</span> seconds</div>
            <div class="board">
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
            </div>
            <button id="restart-btn" onclick="restartGame()">Restart Game</button>
        </section>

        <section id="result-section" style="display:none;">
            <h2 id="winner"></h2>
            <button onclick="startGame()">Play Again</button>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic Tac Toe</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Tic-Tac-Toe Game</h1>
        </header>

        <section id="player-info">
            <h2>Enter Player Details</h2>
            <div>
                <input type="text" id="player1" placeholder="Enter Player 1 Name" required>
                <input type="text" id="player2" placeholder="Enter Player 2 Name" required>
            </div>
            <div>
                <label for="mode">Choose Mode:</label>
                <select id="mode">
                    <option value="offline">Offline</option>
                    <option value="online">Online</option>
                </select>
            </div>
            <button onclick="startGame()">Start Game</button>
        </section>

        <section id="game-board" style="display:none;">
            <h2><span id="current-player"></span>'s Turn</h2>
            <div id="timer">Time Left: <span id="time-left">10</span> seconds</div>
            <div class="board">
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
            </div>
            <button id="restart-btn" onclick="restartGame()">Restart Game</button>
        </section>

        <section id="result-section" style="display:none;">
            <h2 id="winner"></h2>
            <button onclick="startGame()">Play Again</button>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic Tac Toe</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Tic-Tac-Toe Game</h1>
        </header>

        <section id="player-info">
            <h2>Enter Player Details</h2>
            <div>
                <input type="text" id="player1" placeholder="Enter Player 1 Name" required>
                <input type="text" id="player2" placeholder="Enter Player 2 Name" required>
            </div>
            <div>
                <label for="mode">Choose Mode:</label>
                <select id="mode">
                    <option value="offline">Offline</option>
                    <option value="online">Online</option>
                </select>
            </div>
            <button onclick="startGame()">Start Game</button>
        </section>

        <section id="game-board" style="display:none;">
            <h2><span id="current-player"></span>'s Turn</h2>
            <div id="timer">Time Left: <span id="time-left">10</span> seconds</div>
            <div class="board">
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
                <div class="cell" data-cell></div>
            </div>
            <button id="restart-btn" onclick="restartGame()">Restart Game</button>
        </section>

        <section id="result-section" style="display:none;">
            <h2 id="winner"></h2>
            <button onclick="startGame()">Play Again</button>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html>

