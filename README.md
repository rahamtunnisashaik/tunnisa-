<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic-Tac-Toe</title>
    <link rel="stylesheet" href="styles.css">
 
<style>
        .container {
            display: flex;
            justify-content: center;
            align-items:  center;
            height: 50vh; /* Adjust as needed */
        }
    </style>

</head>
<body style="background-color: #f0f0f0;">
<h1 style="color: #3498db; font-size: 6.5em; text-align: center; margin-top: 20px;">Tic-Tac-Toe</h1>
    <div class="container">
       <div id="board" class="board">
    <div class="cell" onclick="cellClicked(0)" style="background-color: #3498db;"></div>
    <div class="cell" onclick="cellClicked(1)" style="background-color: #2ecc71;"></div>
    <div class="cell" onclick="cellClicked(2)" style="background-color: #9b59b6;"></div>
    <div class="cell" onclick="cellClicked(3)" style="background-color: #f1c40f;"></div>
    <div class="cell" onclick="cellClicked(4)" style="background-color: #e74c3c;"></div>
    <div class="cell" onclick="cellClicked(5)" style="background-color: #3498db;"></div>
    <div class="cell" onclick="cellClicked(6)" style="background-color: #2ecc71;"></div>
    <div class="cell" onclick="cellClicked(7)" style="background-color: #9b59b6;"></div>
    <div class="cell" onclick="cellClicked(8)" style="background-color: #f1c40f;"></div>
     </div>
     <h2 style="text-align:right" > <button id="resetBtn" onclick="reset()">Reset</button></h2>
        <p id="message"></p>
    </div>
    <script src="window.js"></script>
</body>
</html>
