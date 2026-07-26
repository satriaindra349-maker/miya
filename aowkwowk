<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untuk Miya ❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #ffd1dc, #ffe6eb, #e8dff5);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            color: #4a4a4a;
            overflow-x: hidden;
            position: relative;
        }

        /* Heart Floating Animation */
        .heart {
            position: absolute;
            color: rgba(255, 110, 145, 0.4);
            animation: float 6s infinite ease-in;
            z-index: 0;
            user-select: none;
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) scale(0.5);
                opacity: 1;
            }
            100% {
                transform: translateY(-10vh) scale(1.2);
                opacity: 0;
            }
        }

        .container {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 24px;
            box-shadow: 0 15px 35px rgba(255, 182, 193, 0.4);
            max-width: 500px;
            width: 100%;
            text-align: center;
            position: relative;
            z-index: 1;
            border: 1px solid rgba(255, 255, 255, 0.6);
        }

        h1 {
            color: #d63384;
            font-size: 2rem;
            margin-bottom: 10px;
        }

        p.subtitle {
            font-size: 1rem;
            color: #6c757d;
            margin-bottom: 25px;
            line-height: 1.5;
        }

        .card {
            background: #ffffff;
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
            text-align: left;
            border-left: 5px solid #ff758f;
        }

        .card h3 {
            color: #ff4d6d;
            margin-bottom: 8px;
            font-size: 1.1rem;
        }

        .card p {
            line-height: 1.6;
            color: #555;
            font-size: 0.95rem;
        }

        .interactive-zone {
            margin-top: 25px;
            padding-top: 15px;
            border-top: 1px ease #f0f0f0;
        }

        .btn {
            background: linear-gradient(135deg, #ff758f, #ff4d6d);
            color: white;
            border: none;
            padding: 14px 28px;
            border-radius: 50px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 8px 20px rgba(255, 77, 109, 0.3);
            transition: all 0.3s ease;
            width: 100%;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 25px rgba(255, 77, 109, 0.4);
        }

        .btn:active {
            transform: translateY(1px);
        }

        #dynamic-message {
            margin-top: 20px;
            padding: 15px;
            border-radius: 12px;
            background: #fff0f3;
            color: #c9184a;
            font-weight: 500;
            display: none;
            animation: fadeIn 0.5s ease;
            line-height: 1.5;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        footer {
            margin-top: 25px;
            font-size: 0.85rem;
            color: #888;
        }

        footer span {
            color: #ff4d6d;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Hai, Miya ❤️</h1>
        <p class="subtitle">Kalau harimu terasa berat hari ini, luangkan waktu sebentar buat baca ini ya...</p>

        <div class="card">
            <h3>Kamu Tidak Sendiri 🤝</h3>
            <p>Miya, apa pun yang lagi bikin kamu sedih atau capek, ingat ya... kamu nggak pernah sendirian. Ada aku yang selalu siap mendengarkan, menemani, dan berjalan di samping kamu di setiap langkahnya.</p>
        </div>

        <div class="card">
            <h3>Nggak Apa-Apa Buat Istirahat 🌿</h3>
            <p>Dunia tidak menuntut kamu untuk selalu kuat setiap hari. Kalau hari ini lelah, tidak apa-apa untuk pelan-pelan. Aku di sini menjaga kamu.</p>
        </div>

        <div class="interactive-zone">
            <button class="btn" onclick="giveHug()">Klik Ini Kalau Butuh Pelukan / Ditemani 🤗</button>
            <div id="dynamic-message"></div>
        </div>

        <footer>
            Dibuat penuh kasih sayang <span>❤️</span> khusus untuk Miya
        </footer>
    </div>

    <script>
        // Membuat animasi hati melayang secara dinamis
        function createHeart() {
            const heart = document.createElement('div');
            heart.classList.add('heart');
            heart.innerHTML = '❤️';
            heart.style.left = Math.random() * 100 + 'vh';
            heart.style.left = Math.random() * 100 + 'vw';
            heart.style.animationDuration = Math.random() * 3 + 4 + 's';
            heart.style.fontSize = Math.random() * 15 + 15 + 'px';
            document.body.appendChild(heart);

            setTimeout(() => {
                heart.remove();
            }, 6000);
        }

        setInterval(createHeart, 500);

        // Pesan acak yang muncul saat tombol diklik
        const messages = [
            "🤗 Virtual Hug dikirim! Ingat ya Miya, badai ini pasti berlalu dan aku ada di sini buat kamu.",
            "🌟 Kamu itu hebat banget udah bertahan sampai hari ini. Aku bangga sama kamu, Miya!",
            "☕ Tarik napas dalam-dalam, hembuskan pelan-pelan. Kamu aman, dan ada aku yang siap bantu kamu kapan aja.",
            "💌 Jangan dipendam sendiri ya. Chat aku kapan pun kamu siap cerita. Aku selalu ada buat kamu.",
            "🌸 Pelan-pelan aja jalannya, nggak usah buru-buru. Aku bakal nemenin kamu di setiap langkah."
        ];

        let lastIndex = -1;

        function giveHug() {
            const msgBox = document.getElementById('dynamic-message');
            let randomIndex;
            
            do {
                randomIndex = Math.floor(Math.random() * messages.length);
            } while (randomIndex === lastIndex && messages.length > 1);

            lastIndex = randomIndex;

            msgBox.style.display = 'none';
            setTimeout(() => {
                msgBox.innerText = messages[randomIndex];
                msgBox.style.display = 'block';
            }, 100);
        }
    </script>
</body>
</html>
