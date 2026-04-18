<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Bonne fête Duaa !</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            background: linear-gradient(145deg, #f9e7b3 0%, #f5b7b1 50%, #f9e7b3 100%);
            font-family: 'Poppins', 'Segoe UI', 'Comic Neue', 'Chalkboard SE', cursive, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        /* carte principale */
        .birthday-card {
            max-width: 650px;
            width: 100%;
            background: rgba(255, 248, 225, 0.95);
            border-radius: 70px 70px 60px 60px;
            box-shadow: 0 30px 40px rgba(0, 0, 0, 0.2), inset 0 1px 4px rgba(255, 255, 200, 0.8);
            text-align: center;
            padding: 35px 20px 45px;
            transition: transform 0.2s ease;
            backdrop-filter: blur(2px);
            border: 2px solid #ffdd99;
        }

        .birthday-card:hover {
            transform: scale(1.01);
        }

        /* zone titre + prénom */
        .name-title {
            font-size: 3.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #e84393, #ff6b6b, #feca57);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
            text-shadow: 3px 3px 12px rgba(0,0,0,0.1);
            margin-bottom: 15px;
            letter-spacing: 2px;
        }

        /* message joyeux anniversaire */
        .birthday-message {
            font-size: 2.2rem;
            font-weight: bold;
            color: #c44569;
            background: #fff0e0;
            display: inline-block;
            padding: 12px 25px;
            border-radius: 60px;
            margin: 20px 0;
            box-shadow: 0 8px 0 #ffb347;
            transform: rotate(-0.5deg);
            transition: all 0.2s;
        }

        /* zone décorative (ballons / gâteaux) */
        .deco {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin: 20px 0 15px;
            flex-wrap: wrap;
        }

        .deco span {
            font-size: 3rem;
            filter: drop-shadow(2px 6px 12px rgba(0,0,0,0.2));
            animation: flottement 3s infinite ease-in-out;
            display: inline-block;
        }

        /* animation légère pour les emojis */
        @keyframes flottement {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-8px); }
            100% { transform: translateY(0px); }
        }

        /* phrase "I love you" stylée */
        .love-bottom {
            margin-top: 45px;
            font-size: 1.8rem;
            font-weight: 600;
            color: #ff4d6d;
            background: #fffbe6;
            display: inline-block;
            padding: 12px 30px;
            border-radius: 50px;
            box-shadow: 0 5px 15px rgba(255, 80, 120, 0.3);
            border: 1px solid #ffb7c5;
            backdrop-filter: blur(4px);
            transition: 0.2s;
        }

        .love-bottom:hover {
            background: #ffebf0;
            transform: scale(1.02);
            letter-spacing: 1px;
        }

        /* petit texte d’âge */
        .age-badge {
            background: #ffb142;
            color: #2d1b00;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 40px;
            padding: 5px 15px;
            display: inline-block;
            margin-bottom: 20px;
            box-shadow: inset 0 -1px 0 #ffdd99, 0 3px 8px rgba(0,0,0,0.1);
        }

        /* responsive : réduire un peu sur mobile */
        @media (max-width: 550px) {
            .birthday-card {
                padding: 25px 15px 35px;
            }
            .name-title {
                font-size: 2.4rem;
            }
            .birthday-message {
                font-size: 1.5rem;
                padding: 8px 18px;
            }
            .love-bottom {
                font-size: 1.4rem;
                padding: 8px 22px;
            }
            .deco span {
                font-size: 2.2rem;
            }
        }

        /* petite touche de cœurs volants */
        .floating-hearts {
            position: fixed;
            bottom: 10px;
            left: 0;
            width: 100%;
            pointer-events: none;
            font-size: 1.1rem;
            text-align: center;
            color: #ff80ab;
            opacity: 0.6;
            font-weight: bold;
        }
        footer {
            font-size: 0.7rem;
            margin-top: 30px;
            color: #aa6f5e;
        }
    </style>
</head>
<body>

<div class="birthday-card">
    <!-- Titre avec le prénom "Duaa" -->
    <div class="name-title">🎈 Doaae 🎈</div>

    <!-- Badge âge / 17 ans -->
    <div class="age-badge">✨ 17 ans ✨</div>

    <!-- Message personnalisé -->
    <div class="birthday-message">
        🎂 Joyeux 17ème Anniversaire ! 🎂
    </div>

    <!-- décoration joyeuse -->
    <div class="deco">
        <span>🎉</span>
        <span>🎂</span>
        <span>🎈</span>
        <span>🎁</span>
        <span>🌸</span>
        <span>✨</span>
    </div>

    <!-- Texte I love you en bas -->
    <div class="love-bottom">
        💖 I love you 💖
    </div>

    <!-- petite note mignonne -->
    <footer>
        🌟 que cette journée soit magique 🌟
    </footer>
</div>

<!-- petits cœurs qui flottent en bas (juste pour le fun) -->
<div class="floating-hearts">
    ❤️ 💕 💗 💓 💖
</div>

</body>
</html>