<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarjeta de Felicitación Neón - Navidad Criminalística y Básquetbol</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            overflow: hidden;
            font-family: 'Rajdhani', sans-serif;
            position: relative;
            background: linear-gradient(180deg, 
                #0a1929 0%, 
                #1a2332 30%, 
                #2d3561 60%, 
                #4a3f6f 75%, 
                #6b4c7a 85%, 
                #8b5a8c 95%, 
                #a8689a 100%);
        }

        /* Estrellas parpadeantes */
        .stars {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
        }

        .star {
            position: absolute;
            width: 2px;
            height: 2px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 50%;
            animation: twinkle 3s infinite;
        }

        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 1; }
        }

        /* Siluetas de edificios */
        .cityscape {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 150px;
            background: #0a0a0a;
            clip-path: polygon(
                0% 100%, 0% 85%, 5% 85%, 5% 70%, 10% 70%, 10% 60%, 15% 60%, 15% 75%, 
                20% 75%, 20% 55%, 25% 55%, 25% 65%, 30% 65%, 30% 50%, 35% 50%, 
                35% 70%, 40% 70%, 40% 45%, 45% 45%, 45% 75%, 50% 75%, 50% 40%, 
                55% 40%, 55% 80%, 60% 80%, 60% 35%, 65% 35%, 65% 85%, 70% 85%, 
                70% 30%, 75% 30%, 75% 90%, 80% 90%, 80% 25%, 85% 25%, 85% 95%, 
                90% 95%, 90% 20%, 95% 20%, 95% 100%, 100% 100%
            );
            opacity: 0.9;
        }

        /* Neblina */
        .fog {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 200px;
            background: linear-gradient(0deg, 
                rgba(255, 255, 255, 0.1) 0%, 
                rgba(255, 255, 255, 0.05) 50%, 
                transparent 100%);
            animation: fogDrift 20s infinite ease-in-out;
        }

        @keyframes fogDrift {
            0%, 100% { transform: translateX(0); }
            50% { transform: translateX(30px); }
        }

        /* Título principal */
        .main-title {
            position: absolute;
            top: 10%;
            left: 50%;
            transform: translateX(-50%);
            font-family: 'Orbitron', sans-serif;
            font-size: clamp(1.5rem, 4vw, 2.5rem);
            font-weight: 700;
            text-align: center;
            color: #ffffff;
            text-shadow: 
                0 0 10px rgba(147, 197, 253, 0.8),
                0 0 20px rgba(147, 197, 253, 0.6),
                0 0 30px rgba(244, 114, 182, 0.4),
                0 0 40px rgba(244, 114, 182, 0.3);
            animation: titleGlow 3s infinite alternate;
            z-index: 10;
            padding: 0 20px;
        }

        @keyframes titleGlow {
            0% { 
                text-shadow: 
                    0 0 10px rgba(147, 197, 253, 0.8),
                    0 0 20px rgba(147, 197, 253, 0.6),
                    0 0 30px rgba(244, 114, 182, 0.4),
                    0 0 40px rgba(244, 114, 182, 0.3);
            }
            100% { 
                text-shadow: 
                    0 0 15px rgba(147, 197, 253, 0.9),
                    0 0 25px rgba(147, 197, 253, 0.7),
                    0 0 35px rgba(244, 114, 182, 0.5),
                    0 0 45px rgba(244, 114, 182, 0.4);
            }
        }

        /* Contenedor de elementos */
        .elements-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 90%;
            max-width: 1200px;
            height: 500px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            flex-wrap: wrap;
            z-index: 5;
        }

        /* Iconos SVG */
        .icon {
            filter: drop-shadow(0 0 10px currentColor);
            animation: float 4s infinite ease-in-out;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        /* Lupa con huella */
        .magnifying-glass {
            position: absolute;
            top: 20%;
            left: 15%;
            color: #93c5fd;
            animation: float 4s infinite ease-in-out, pulse 2s infinite alternate;
        }

        @keyframes pulse {
            0% { opacity: 0.8; }
            100% { opacity: 1; }
        }

        /* ADN */
        .dna {
            position: absolute;
            top: 30%;
            right: 20%;
            color: #f472b6;
            animation: float 5s infinite ease-in-out 1s, rotate 10s infinite linear;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Cámara */
        .camera {
            position: absolute;
            top: 60%;
            left: 10%;
            color: #fbbf24;
            animation: float 4.5s infinite ease-in-out 0.5s, flash 3s infinite;
        }

        @keyframes flash {
            0%, 90%, 100% { opacity: 0.7; }
            95% { opacity: 1; filter: brightness(1.5); }
        }

        /* Cinta de escena */
        .crime-tape {
            position: absolute;
            bottom: 20%;
            left: 5%;
            width: 200px;
            height: 30px;
            background: repeating-linear-gradient(
                45deg,
                #fbbf24,
                #fbbf24 10px,
                #000000 10px,
                #000000 20px
            );
            transform: rotate(-5deg);
            filter: drop-shadow(0 0 8px rgba(251, 191, 36, 0.8));
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: #000;
            font-size: 12px;
            animation: tapeFloat 6s infinite ease-in-out;
        }

        @keyframes tapeFloat {
            0%, 100% { transform: rotate(-5deg) translateY(0); }
            50% { transform: rotate(-5deg) translateY(-5px); }
        }

        /* Aro de básquetbol */
        .basketball-hoop {
            position: absolute;
            top: 25%;
            right: 15%;
            color: #fb923c;
            animation: float 4s infinite ease-in-out 2s;
        }

        /* Balón de básquetbol */
        .basketball {
            position: absolute;
            top: 45%;
            right: 25%;
            color: #fb923c;
            filter: drop-shadow(0 0 15px rgba(251, 146, 60, 0.8));
            animation: float 3.5s infinite ease-in-out 1.5s, spin 8s infinite linear;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Marcador digital */
        .scoreboard {
            position: absolute;
            bottom: 25%;
            right: 10%;
            background: linear-gradient(135deg, #1e293b, #334155);
            border: 2px solid #fb923c;
            border-radius: 10px;
            padding: 15px 25px;
            font-family: 'Orbitron', monospace;
            font-size: 2rem;
            font-weight: 900;
            color: #fb923c;
            text-shadow: 
                0 0 10px rgba(251, 146, 60, 0.8),
                0 0 20px rgba(251, 146, 60, 0.6);
            animation: scoreboardGlow 2s infinite alternate;
        }

        @keyframes scoreboardGlow {
            0% { 
                box-shadow: 0 0 10px rgba(251, 146, 60, 0.5);
                text-shadow: 
                    0 0 10px rgba(251, 146, 60, 0.8),
                    0 0 20px rgba(251, 146, 60, 0.6);
            }
            100% { 
                box-shadow: 0 0 20px rgba(251, 146, 60, 0.8);
                text-shadow: 
                    0 0 15px rgba(251, 146, 60, 1),
                    0 0 25px rgba(251, 146, 60, 0.8);
            }
        }

        /* Responsive */
        @media (max-width: 768px) {
            .main-title {
                font-size: 1.5rem;
                top: 5%;
            }
            
            .elements-container {
                height: 400px;
            }
            
            .icon {
                transform: scale(0.8);
            }
            
            .crime-tape {
                width: 150px;
                font-size: 10px;
            }
            
            .scoreboard {
                font-size: 1.5rem;
                padding: 10px 15px;
            }
        }
    </style>
</head>
<body>
    <!-- Estrellas -->
    <div class="stars" id="stars"></div>
    
    <!-- Siluetas de ciudad -->
    <div class="cityscape"></div>
    
    <!-- Neblina -->
    <div class="fog"></div>
    
    <!-- Título principal -->
    <h1 class="main-title">Feliz Navidad mi Criminalística y Basquetbolista</h1>
    
    <!-- Elementos de criminalística -->
    <div class="magnifying-glass icon">
        <svg width="80" height="80" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="35" cy="35" r="25" stroke="currentColor" stroke-width="3" fill="none"/>
            <line x1="52" y1="52" x2="75" y2="75" stroke="currentColor" stroke-width="3" stroke-linecap="round"/>
            <!-- Huella dactilar simplificada -->
            <circle cx="35" cy="35" r="8" fill="none" stroke="currentColor" stroke-width="1" opacity="0.7"/>
            <circle cx="35" cy="35" r="15" fill="none" stroke="currentColor" stroke-width="1" opacity="0.5"/>
            <circle cx="35" cy="35" r="20" fill="none" stroke="currentColor" stroke-width="1" opacity="0.3"/>
        </svg>
    </div>
    
    <div class="dna icon">
        <svg width="60" height="80" viewBox="0 0 60 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M15 10 Q30 20 45 10 Q30 30 15 50 Q30 70 45 50 Q30 60 15 70" 
                  stroke="currentColor" stroke-width="2" fill="none"/>
            <path d="M15 20 Q30 10 45 20 Q30 40 15 60 Q30 80 45 60 Q30 50 15 40" 
                  stroke="currentColor" stroke-width="2" fill="none"/>
            <circle cx="15" cy="10" r="3" fill="currentColor"/>
            <circle cx="45" cy="10" r="3" fill="currentColor"/>
            <circle cx="15" cy="70" r="3" fill="currentColor"/>
            <circle cx="45" cy="70" r="3" fill="currentColor"/>
        </svg>
    </div>
    
    <div class="camera icon">
        <svg width="70" height="60" viewBox="0 0 70 60" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="10" y="15" width="50" height="35" rx="5" stroke="currentColor" stroke-width="2" fill="none"/>
            <circle cx="35" cy="32" r="12" stroke="currentColor" stroke-width="2" fill="none"/>
            <circle cx="35" cy="32" r="8" fill="currentColor" opacity="0.3"/>
            <rect x="25" y="10" width="20" height="10" rx="2" stroke="currentColor" stroke-width="2" fill="none"/>
            <!-- Flash -->
            <rect x="50" y="5" width="8" height="6" rx="1" fill="currentColor" class="flash"/>
        </svg>
    </div>
    
    <div class="crime-tape">
        CRIMEN SCENE
    </div>
    
    <!-- Elementos de básquetbol -->
    <div class="basketball-hoop icon">
        <svg width="100" height="120" viewBox="0 0 100 120" fill="none" xmlns="http://www.w3.org/2000/svg">
            <!-- Tablero -->
            <rect x="20" y="10" width="60" height="40" rx="3" stroke="currentColor" stroke-width="2" fill="none"/>
            <rect x="30" y="20" width="40" height="20" rx="2" stroke="currentColor" stroke-width="1" fill="none"/>
            <!-- Aro -->
            <circle cx="50" cy="60" r="20" stroke="currentColor" stroke-width="3" fill="none"/>
            <!-- Red -->
            <path d="M30 60 L35 80 M40 60 L42 80 M50 60 L50 80 M58 60 L60 80 M65 60 L70 80" 
                  stroke="currentColor" stroke-width="1" opacity="0.8"/>
        </svg>
    </div>
    
    <div class="basketball icon">
        <svg width="80" height="80" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="40" cy="40" r="35" stroke="currentColor" stroke-width="3" fill="none"/>
            <path d="M40 5 Q40 40 40 75 M5 40 Q40 40 75 40" stroke="currentColor" stroke-width="2"/>
            <path d="M15 20 Q40 40 65 20 M15 60 Q40 40 65 60" stroke="currentColor" stroke-width="1.5" opacity="0.7"/>
        </svg>
    </div>
    
    <div class="scoreboard">
        25
    </div>
    
    <script>
        // Generar estrellas aleatorias
        function generateStars() {
            const starsContainer = document.getElementById('stars');
            const numberOfStars = 50;
            
            for (let i = 0; i < numberOfStars; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.animationDelay = Math.random() * 3 + 's';
                star.style.animationDuration = (Math.random() * 3 + 2) + 's';
                starsContainer.appendChild(star);
            }
        }
        
        // Inicializar
        generateStars();
        
        // Efectos interactivos sutiles
        document.addEventListener('mousemove', (e) => {
            const x = e.clientX / window.innerWidth;
            const y = e.clientY / window.innerHeight;
            
            // Movimiento sutil del título
            const title = document.querySelector('.main-title');
            if (title) {
                title.style.transform = `translateX(calc(-50% + ${(x - 0.5) * 10}px))`;
            }
        });
    </script>
</body>
</html>
