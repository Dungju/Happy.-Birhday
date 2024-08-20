# Happy.-Birhday
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selamat Ulang Tahun Salsa Almuja Dillah</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #f0f8ff;
            color: #333;
            text-align: center;
            overflow: hidden;
        }
        .container {
            position: relative;
            width: 100%;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: #ffebcd;
            overflow: hidden;
        }
        .message {
            background: #fff;
            padding: 2em;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            max-width: 800px;
            margin: auto;
            opacity: 0;
            transform: translateY(-20px);
            transition: opacity 1s ease-in-out, transform 1s ease-in-out;
        }
        .message.show {
            opacity: 1;
            transform: translateY(0);
        }
        .emoji {
            font-size: 2em;
        }
        .confetti {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            overflow: hidden;
            z-index: 0;
        }
        .confetti div {
            position: absolute;
            width: 10px;
            height: 10px;
            background: #ff6347;
            border-radius: 50%;
            animation: fall 5s infinite;
        }
        @keyframes fall {
            0% { transform: translateY(-100px); }
            100% { transform: translateY(calc(100vh + 100px)); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="confetti">
            <!-- Simulasi konfeti -->
            <div style="left: 10%; animation-duration: 4s;"></div>
            <div style="left: 20%; animation-duration: 5s;"></div>
            <div style="left: 30%; animation-duration: 6s;"></div>
            <div style="left: 40%; animation-duration: 4.5s;"></div>
            <div style="left: 50%; animation-duration: 5s;"></div>
            <div style="left: 60%; animation-duration: 6s;"></div>
            <div style="left: 70%; animation-duration: 4s;"></div>
            <div style="left: 80%; animation-duration: 5s;"></div>
            <div style="left: 90%; animation-duration: 6s;"></div>
        </div>
        <div class="message" id="message">
            <h1>🎉 Selamat Ulang Tahun Salsa Almuja Dillah! 🎂</h1>
            <p>Hari ini adalah hari istimewa yang merayakan bukan hanya bertambahnya usia, tetapi juga setiap momen berharga yang telah kamu lalui. Aku ingin mengungkapkan betapa istimewanya kamu dalam hidupku dan banyak orang di sekelilingmu. Setiap tahun, kamu semakin bijaksana, lebih kuat, dan penuh dengan semangat. Semoga tahun baru dalam hidupmu membawa peluang baru, pencapaian yang lebih besar, dan kebahagiaan yang tak terhingga.</p>
            <p></p>
            <p>Hari ini adalah kesempatan untuk merayakan semua pencapaianmu dan menyambut semua hal baik yang akan datang. Nikmati setiap detik dari hari istimewa ini dan tahu bahwa kamu dikelilingi oleh orang-orang yang menyayangimu dan menghargai segala yang kamu lakukan.</p>
            
            <p class="emoji">🎈🎁🥳</p>
        </div>
    </div>

    <script>
        window.onload = () => {
            const message = document.getElementById('message');
            setTimeout(() => {
                message.classList.add('show');
            }, 500); // Tampilkan pesan setelah 0.5 deti
