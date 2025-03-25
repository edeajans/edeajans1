<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Türk Bayrağı</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #e5e5e5;
        }

        .flag {
            position: relative;
            width: 400px;
            height: 250px;
            background-color: red;
            border: 2px solid #d40000;
        }

        .circle {
            position: absolute;
            top: 50%;
            left: 10%;
            transform: translateY(-50%);
            width: 80px;
            height: 80px;
            background-color: white;
            border-radius: 50%;
        }

        .star {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 0;
            height: 0;
            border-left: 40px solid transparent;
            border-right: 40px solid transparent;
            border-bottom: 70px solid white;
            clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
        }
    </style>
</head>
<body>
    <div class="flag">
        <div class="circle"></div>
        <div class="star"></div>
    </div>
</body>
</html>
