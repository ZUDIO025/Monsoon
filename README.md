<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ZUDIO Monsoon Offer</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #fdfcfb, #e2d1c3);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    h1 {
      color: #e91e63;
      font-size: 28px;
      text-align: center;
      margin-bottom: 0;
      animation: pop-in 1s ease-out forwards;
    }

    h2 {
      color: #555;
      font-size: 18px;
      margin-top: 5px;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in-out forwards;
    }

    img {
      max-width: 90%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      margin-bottom: 20px;
      animation: float 3s ease-in-out infinite;
    }

    button {
      padding: 12px 25px;
      font-size: 18px;
      background-color: #ff4081;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transition: transform 0.2s ease-in-out;
    }

    button:hover {
      transform: scale(1.1);
    }

    #coupon {
      margin-top: 20px;
      font-size: 24px;
      color: #4CAF50;
      font-weight: bold;
      animation: bounceIn 1s forwards;
      display: none;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    @keyframes bounceIn {
      0% {
        transform: scale(0.3);
        opacity: 0;
      }
      50% {
        transform: scale(1.05);
        opacity: 1;
      }
      70% {
        transform: scale(0.9);
      }
      100% {
        transform: scale(1);
      }
    }

    @keyframes pop-in {
      from {
        transform: scale(0.8);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <h1>You are selected for the Monsoon Offer</h1>
  <h2>By ZUDIO</h2>
  
  <img src="WhatsApp Image 2025-06-24 at 2.35.43 PM.jpeg" alt="Promo Image">

  <button onclick="generateCoupon()">🎁 Generate Coupon</button>

  <div id="coupon">🎉 Your Code: <span style="color:#000">KAZHAPPU025</span></div>

  <script>
    function generateCoupon() {
      const coupon = document.getElementById('coupon');
      coupon.style.display = 'block';
      coupon.style.animation = 'bounceIn 1s';
    }
  </script>

</body>
</html>
