<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesan Cinta</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-image: url('https://i.imgur.com/X1dMKSj.jpg'); /* URL gambar beruang */
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            margin: 0;
            padding: 0;
            color: white;
            text-shadow: 1px 1px 3px #000;
        }
        h1 {
            font-size: 36px;
            margin-top: 50px;
        }
        p {
            font-size: 22px;
            margin: 20px 0;
        }
        .heart {
            font-size: 50px;
            margin-top: 20px;
        }
        button {
            background-color: #ff6b81;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            border-radius: 10px;
            box-shadow: 2px 2px 5px #000;
        }
        button:hover {
            background-color: #ff859b;
        }
    </style>
</head>
<body>
    <h1>Halo, Sayangku! 🐻❤️</h1>
    <p id="message">Klik tombol di bawah ini untuk melihat pesan spesial dari aku.</p>
    <div class="heart">💖💗💓💞💕</div>
    <button onclick="showLoveMessage()">Klik di Sini</button>

    <script>
        function showLoveMessage() {
            const message = document.getElementById('message');
            message.innerHTML = "Aku sayang kamu 💕 Aku cinta kamu 💖 Sayang kuu 💞 I love you! 💓💗";
        }
    </script>
</body>
</html>"Menambahkan file pesan cinta"
