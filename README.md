<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY WPUB RADIO SHOW PICS</title>
    <style>
        /* Body Styles */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            overflow-x: hidden;
            background-color: #111;
            color: #fff;
        }

        /* Neon Title */
        .neonTitle {
            font-size: 50px;
            color: #9b59b6;
            text-align: center;
            text-shadow: 0 0 5px #9b59b6, 0 0 10px #9b59b6, 0 0 20px #9b59b6, 0 0 40px #9b59b6;
            animation: flicker 1.5s infinite;
            margin-top: 20px;
        }

        @keyframes flicker {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        /* Subtitle */
        .subtitle {
            font-size: 30px;
            color: #8e44ad;
            text-align: center;
            text-shadow: 0 0 5px #8e44ad, 0 0 10px #8e44ad, 0 0 20px #8e44ad;
            margin-top: 20px;
        }

        /* Song List */
        .song-list {
            text-align: center;
            font-size: 18px;
            line-height: 1.8;
            margin-top: 10px;
        }

        /* Conveyor Belt for Images */
        .imageContainer {
            position: fixed;
            top: 0;
            width: 25vw; /* Width set in viewport units */
            height: 100vh;
            overflow: hidden;
            z-index: -1;
        }

        .imageContainerLeft {
            left: 0;
            animation: moveUp 10s linear infinite;
        }

        .imageContainerRight {
            right: 0;
            animation: moveDown 10s linear infinite;
        }

        .image {
            width: 100%;
            height: auto;
            margin: 10px;
            border: 5px solid #9b59b6;
            box-shadow: 0 0 10px #9b59b6, 0 0 20px #9b59b6, 0 0 30px #9b59b6;
        }

        /* Conveyor Belt Animations */
        @keyframes moveUp {
            0% { transform: translateY(100%); }
            100% { transform: translateY(-100%); }
        }

        @keyframes moveDown {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(100%); }
        }

        /* Mobile Styles */
        @media (max-width: 600px) {
            .neonTitle {
                font-size: 40px;
            }

            .imageContainer {
                width: 40vw; /* Wider images on mobile */
            }

            .imageContainerLeft,
            .imageContainerRight {
                position: absolute;
                top: 100px;
            }

            .imageContainerRight {
                left: 40%; /* Position adjusted for mobile */
                right: auto;
                animation: moveUp 10s linear infinite;
            }
        }
    </style>
</head>
<body>

    <!-- Neon Flickering Title -->
    <div class="neonTitle">MY WPUB RADIO SHOW PICS</div>

    <!-- Conveyor Belt Left Side Images (Moving Up) -->
    <div class="imageContainer imageContainerLeft">
        <img src="ab67616d0000b27336831b6c01f1eb90fd87d53f.jpg" alt="Image1" class="image">
        <img src="f6c842fb35267bfb1531093b9548a57f.1000x1000x1.jpg" class="image">
        <img src="618+cD9dpjL._UF1000,1000_QL80_.jpg" class="image">
    </div>

    <!-- Conveyor Belt Right Side Images (Moving Down) -->
    <div class="imageContainer imageContainerRight">
        <img src="BackEggCover.jpg" alt="Image4" class="image">
        <img src="61dkuz2-ubL._UF1000,1000_QL80_.jpg" alt="Image5" class="image">
        <img src="54125775357_7358794049_o.jpg" alt="Image6" class="image">
    </div>

    <!-- Subtitle and Song List -->
    <div class="subtitle">SHOW 5: On Stage</div>
    <div class="song-list">
        <div class="song">SUNDAY FINALE - STEPHEN SONDHEIM</div>
        <div class="song">MOVING TOO FAST - JASON ROBERT BROWN</div>
    </div>

</body>
</html>

