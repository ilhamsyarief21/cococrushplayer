<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Music Player Ilham Syarief</title>
    <style>
        .volume-controls {
            display: flex;
            justify-content: center;
        }
        
        .volume-button {
            width: 30px;
            height: 30px;
            background-color: #f7bd1d;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #ffffff;
            font-size: 16px;
            margin-bottom: 20px;
            
            cursor: pointer;


        }
        
        .volume-button:hover {
            background-color: #904716;
        }
        
        #volume-down {
            margin-right: 10px;
        }
    </style>
    
 </head>
 
    <body>
        <div class="background">
            <img src="assets/2.jpg" id="bg-img">
        </div>
        <div class="container">
            <div class="player-img">
                <img src="assets/music1.jpg" class="active" id="cover">
            </div>
        
            <h2 id="music-title">Jatuh Cinta Lagi</h2>
            <h3 id="music-artist">Ilham Syarief</h3>
        
            <div class="player-progress" id="player-progress">
                <div class="progress" id="progress"></div>
                <div class="music-duration">
                    <span id="current-time">0:00</span>
                    <span id="duration">0:00</span>
                </div>
            </div>
        
            <div class="volume-controls">
                <div id="volume-down" class="volume-button">
                    -
                </div>
                <div id="volume-up" class="volume-button">
                    +
                </div>
            </div>
        
            <div class="player-controls">
                <i class="fa-solid fa-backward" title="Previous" id="prev"></i>
                <i class="fa-solid fa-play play-button" title="Play" id="play"></i>
                <i class="fa-solid fa-forward" title="Next" id="next"></i>
            </div>

            
        </div>
        <i class=""></i>
        <!-- fa-solid fa-play play-button -->
        
        <script src="index.js"></script>
    </body>
    </html>        
