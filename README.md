<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>For You ❤️</title>

  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #0b0010;
      color: white;
      font-family: Georgia, serif;
      text-align: center;
    }

    .text {
      font-size: 28px;
      line-height: 2;
    }

    .line {
      opacity: 0;
      transform: translateY(25px);
      animation: textShow 2s ease forwards;
    }

    .line:nth-child(1) {
      animation-delay: 0.5s;
    }

    .line:nth-child(2) {
      animation-delay: 2.5s;
    }

    .line:nth-child(3) {
      animation-delay: 4.5s;
    }

    @keyframes textShow {
      0% {
        opacity: 0;
        transform: translateY(25px);
      }

      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>

<body>

  <div class="text">
    <div class="line">Chaho ge tum jese ❤️</div>
    <div class="line">Ho jaunga waise 🫶</div>
    <div class="line">Chahe to wada hi le lo ✨</div>
  </div>

</body>
</html>
