# Kad-nlar-g-n-hediyesi
Gizeme özel sürpriz 
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Kadınlar Günü</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #ffe6f0, #fff0f5);
      font-family: 'Segoe UI', sans-serif;
    }
    .card {
      text-align: center;
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 0 25px rgba(0,0,0,0.2);
      opacity: 0;
      transform: scale(0.9);
      transition: all 2s ease;
    }
    h1 {
      color: #e60073;
      font-size: 28px;
      margin-bottom: 15px;
    }
    p {
      font-size: 18px;
      color: #333;
    }
    img {
      width: 250px;
      border-radius: 15px;
      margin: 15px 0;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    .heart {
      color: red;
      font-size: 30px;
      animation: pulse 1s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.3); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="card" id="surprise">
    <h1>Kadınlar Günün Kutlu Olsun ❤️</h1>
    <img src="flower.jpg" alt="Çiçek Buketi">
    <p>Sen benim en güzel çiçeğimsin.</p>
    <div class="heart">❤</div>
  </div>

  <script>
    window.onload = () => {
      const card = document.getElementById('surprise');
      setTimeout(() => {
        card.style.opacity = 1;
        card.style.transform = "scale(1)";
      }, 500);
    };
  </script>
</body>
</html>
