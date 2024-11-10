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

        /* Neon Purple Flickering "MY WPUB RADIO SHOW PICS" Title */
        .neonTitle {
            font-family: 'Arial', sans-serif;
            font-size: 70px;
            color: #9b59b6;
            text-align: center;
            text-shadow: 0 0 5px #9b59b6, 0 0 10px #9b59b6, 0 0 20px #9b59b6, 0 0 40px #9b59b6;
            animation: flicker 1.5s infinite;
        }

        @keyframes flicker {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        /* Subtitle Styles (Slightly Different Purple) */
        .subtitle {
            font-family: 'Arial', sans-serif;
            font-size: 30px;
            color: #8e44ad; /* Slightly different shade of purple */
            text-align: center;
            text-shadow: 0 0 5px #8e44ad, 0 0 10px #8e44ad, 0 0 20px #8e44ad;
            margin-top: 30px;
        }

        /* Song List with Sequential Fade In */
        .song-list {
            text-align: center;
            font-size: 20px;
            line-height: 1.8;
            margin-top: 30px;
        }

        /* Individual Song Animation */
        .song {
            opacity: 0;
            animation: fadeIn 1s forwards;
        }

        /* Sequential Song Fade In */
        .song:nth-child(1) { animation-delay: 0s; }
        .song:nth-child(2) { animation-delay: 1s; }
        .song:nth-child(3) { animation-delay: 2s; }
        .song:nth-child(4) { animation-delay: 3s; }
        .song:nth-child(5) { animation-delay: 4s; }
        .song:nth-child(6) { animation-delay: 5s; }
        .song:nth-child(7) { animation-delay: 6s; }

        /* Animation for Song Fade In */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* Conveyor Belt for Images (Left Side Up, Right Side Down) */
        .imageContainer {
            position: fixed;
            top: 0;
            width: 100px;
            height: 100%;
            z-index: -1;

        }

        .imageContainerLeft {
            left: 0;
            animation: moveUp 6s linear infinite;
        }

        .imageContainerRight {
            right: 300px;
            animation: moveDown 6s linear infinite;
        }

        .image {
            width: 300px;  /* Adjusted the image size to 80px */
            height: 300px; /* Adjusted the image size to 80px */
            margin: 20px;
            border: 5px solid #9b59b6; /* Neon purple border */
            box-shadow: 0 0 10px #9b59b6, 0 0 20px #9b59b6, 0 0 30px #9b59b6; /* Neon glow effect */
        }

        @keyframes moveUp {
            0% { transform: translateY(100%); }
            100% { transform: translateY(-100%); }
        }

        @keyframes moveDown {
            0% { transform: translateY(-100%); }
            100% { transform: translateY(100%); }
        }
    </style>
</head>
<body>

    <!-- Neon Flickering Title -->
    <div class="neonTitle">MY WPUB RADIO SHOW PICS</div>

    <!-- Conveyor Belt Left Side Images (Moving Up) -->
    <div class="imageContainer imageContainerLeft">
        <!-- Replace with your actual image paths -->
        <img src="ab67616d0000b27336831b6c01f1eb90fd87d53f.jpg" alt="Image1" class="image">
        <img src="f6c842fb35267bfb1531093b9548a57f.1000x1000x1.jpg" class="image">
        <img src="618+cD9dpjL._UF1000,1000_QL80_.jpg" class="image">
        <img src="prince01.jpg" class="image">
        <img src="61dkuz2-ubL._UF1000,1000_QL80_.jpg" class="image">
        <!-- Add more images as needed -->
    </div>

    <!-- Conveyor Belt Right Side Images (Moving Down) -->
    <div class="imageContainer imageContainerRight">
        <!-- Replace with your actual image paths -->
        <img src="BackEggCover.jpg" alt="Image4" class="image">
        <img src="61dkuz2-ubL._UF1000,1000_QL80_.jpg" alt="Image5" class="image">
        <img src="54125775357_7358794049_o.jpg" alt="Image6" class="image">
        <img src="54127074810_eaa5ee13d3_o.png" alt="Image6" class="image">
        <!-- Add more images as needed -->
    </div>

    <!-- Show 5: On Stage -->
    <div class="subtitle">SHOW 5: On Stage</div>
    <div class="song-list">
        <div class="song">SUNDAY FINALE - STEPHEN SONDHEIM</div>
        <div class="song">MOVING TOO FAST - JASON ROBERT BROWN</div>
        <div class="song">THE BITCH OF LIVING - STEVEN SATER</div>
    </div>

    <!-- Show 4: My Top Pics -->
    <div class="subtitle">SHOW 4: My Top Pics</div>
    <div class="song-list">
        <div class="song">POP LIFE - PRINCE</div>
        <div class="song">FORGET HER - JEFF BUCKLEY</div>
        <div class="song">GET ON THE RIGHT THING - WINGS</div>
        <div class="song">PEANUT MAN - TIM BUCKLEY</div>
    </div>

    <!-- Show 3: Established/Underrated -->
    <div class="subtitle">SHOW 3: Established/Underrated</div>
    <div class="song-list">
        <div class="song">AND SHE WAS - TALKING HEADS</div>
        <div class="song">PINBALL - BRIAN PROTHEROE</div>
        <div class="song">LOVE HURTS - Z BERG</div>
        <div class="song">PARADISE - REX ORANGE COUNTY</div>
    </div>

    <!-- Show 2: The 27 Club -->
    <div class="subtitle">SHOW 2: The 27 Club</div>
    <div class="song-list">
        <div class="song">PEACE FROG - THE DOORS</div>
        <div class="song">BACK TO BLACK - AMY WINEHOUSE</div>
        <div class="song">WHO KNOWS - JIMI HENDRIX</div>
        <div class="song">MARIGOLD - NIRVANA</div>
        <div class="song">SYMPATHY FOR THE DEVIL - THE ROLLING STONES</div>
        <div class="song">AS GOOD AS YOU'VE BEEN TO THIS WORLD - JANIS JOPLIN</div>
    </div>

    <!-- Show 1: Gems -->
    <div class="subtitle">SHOW 1: Gems</div>
    <div class="song-list">
        <div class="song">POP MUZIC - M. ROBIN SCOTT</div>
        <div class="song">TOO SWEET - HOZIER</div>
        <div class="song">ZANZIBAR - BILLY JOEL</div>
        <div class="song">SILVERLINES - DAMIAN LABRINTH</div>
        <div class="song">WAH-WAH - GEORGE HARRISON</div>
        <div class="song">WHAT A GIRL WANTS - SABRINA CARPENTER</div>
        <div class="song">CHRISTINA AGUILERA</div>
    </div>

</body>
</html>

