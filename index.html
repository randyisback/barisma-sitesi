<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barışalım mı? ❤️</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            text-align: center;
            background-color: #ffebee;
            padding: 20px;
            transition: all 0.3s;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            overflow: hidden;
            position: relative;
        }
        
        h1 {
            color: #d32f2f;
            font-size: 2.5em;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .buttons {
            display: flex;
            gap: 20px;
            margin-top: 20px;
            flex-wrap: wrap;
            justify-content: center;
            z-index: 10;
        }
        
        button {
            padding: 15px 30px;
            font-size: 1.2em;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        #yes {
            background-color: #4caf50;
            color: white;
            transition: all 0.5s ease-out;
        }
        
        #no {
            background-color: #f44336;
            color: white;
            position: relative;
        }
        
        #no:hover {
            transform: scale(0.95);
        }
        
        #yes:hover {
            transform: scale(1.05);
        }
        
        .hidden {
            display: none;
        }
        
        #message {
            font-size: 2em;
            color: #d32f2f;
            margin-top: 30px;
            animation: pulse 1.5s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        
        .heart {
            font-size: 3em;
            animation: float 3s ease-in-out infinite;
            margin: 20px 0;
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .confetti {
            position: fixed;
            z-index: 1000;
            pointer-events: none;
        }
        
        #blocker {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.5);
            z-index: 10000;
            display: none;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        
        #blocker-message {
            background-color: white;
            padding: 30px;
            border-radius: 20px;
            max-width: 80%;
            font-size: 1.5em;
            color: #d32f2f;
        }
    </style>
</head>
<body>
    <div id="question">
        <h1>Barışalım mı artık? 😊</h1>
        <div class="heart">❤️</div>
        <div class="buttons">
            <button id="yes">EVET 😊</button>
            <button id="no">Hayır 😠</button>
        </div>
    </div>
    
    <div id="response" class="hidden">
        <h1>Oleyyyyyyy 🎉</h1>
        <div class="heart">💕</div>
        <div id="message">Seni seviyorum essek 😘</div>
    </div>
    
    <div id="blocker">
        <div id="blocker-message">
            <h2>Kaçış yok! 😈</h2>
            <p>Sayfayı kapatamazsın! Barışmadan gitmene izin vermeyeceğim!</p>
            <p>Otomatik olarak EVET'e basılmış sayılıyorsun! ❤️</p>
        </div>
    </div>

    <script>
        const yesBtn = document.getElementById('yes');
        const noBtn = document.getElementById('no');
        const questionDiv = document.getElementById('question');
        const responseDiv = document.getElementById('response');
        const blocker = document.getElementById('blocker');
        let clickCount = 0;
        
        const noButtonTexts = [
            "Hayır 😠",
            "Emin misin? 😒",
            "Gerçekten emin misin? 😤",
            "Son kez soruyorum! 😠",
            "Cidden mi? 😡",
            "Artık basmazsan olmaz! 😫",
            "YETER! BAS ARTIK! 😭"
        ];
        
        window.addEventListener('beforeunload', function(e) {
            if (!responseDiv.classList.contains('hidden')) return;
            
            e.preventDefault();
            e.returnValue = 'Barışmadan gitmek yok!';
            showBlocker();
            forceYes();
            return 'Barışmadan gitmek yok!';
        });
        
        function showBlocker() {
            blocker.style.display = 'flex';
            setTimeout(() => {
                blocker.style.display = 'none';
            }, 3000);
        }
        
        function forceYes() {
            questionDiv.classList.add('hidden');
            responseDiv.classList.remove('hidden');
            
            for(let i = 0; i < 300; i++) {
                setTimeout(() => createConfetti(), i * 30);
            }
        }
        
        yesBtn.addEventListener('click', function() {
            acceptLove();
        });
        
        function acceptLove() {
            questionDiv.classList.add('hidden');
            responseDiv.classList.remove('hidden');
            
            for(let i = 0; i < 200; i++) {
                setTimeout(() => createConfetti(), i * 50);
            }
        }
        
        noBtn.addEventListener('click', function() {
            clickCount++;
            
            if (clickCount < noButtonTexts.length) {
                noBtn.textContent = noButtonTexts[clickCount];
            } else {
                noBtn.textContent = "ARTIK BASMAK ZORUNDASIN! 😫";
                noBtn.style.display = 'none'; 
            }
            
             
            const kodlamaDiliFSZ = parseFloat(getComputedStyle(yesBtn).fontSize);
            const kodlamaDiliPDV = parseFloat(getComputedStyle(yesBtn).paddingTop);
            const kodlamaDiliPDH = parseFloat(getComputedStyle(yesBtn).paddingLeft);
            
            yesBtn.style.fontSize = (kodlamaDiliFSZ * 1.3) + 'px';
            yesBtn.style.padding = (kodlamaDiliPDV * 1.3) + 'px ' + (kodlamaDiliPDH * 1.3) + 'px';
            
            
            if (clickCount < noButtonTexts.length) {
                const maxX = window.innerWidth - noBtn.offsetWidth - 20;
                const maxY = window.innerHeight - noBtn.offsetHeight - 20;
                const x = Math.max(10, Math.random() * maxX);
                const y = Math.max(10, Math.random() * maxY);
                
                noBtn.style.position = 'absolute';
                noBtn.style.left = x + 'px';
                noBtn.style.top = y + 'px';
            }
            
           
            if(clickCount >= noButtonTexts.length - 1) {
                yesBtn.style.fontSize = '3.5em';
                yesBtn.style.padding = '40px 80px';
                yesBtn.textContent = "BAŞKA ÇAREN YOK! 😍 BAS ARTIK!";
                
               
                yesBtn.style.animation = 'shake 0.5s infinite';
                const style = document.createElement('style');
                style.innerHTML = `
                    @keyframes shake {
                        0% { transform: translateX(0); }
                        25% { transform: translateX(-15px); }
                        50% { transform: translateX(15px); }
                        75% { transform: translateX(-15px); }
                        100% { transform: translateX(0); }
                    }
                `;
                document.head.appendChild(style);
            }
        });
        
        function createConfetti() {
            const confetti = document.createElement('div');
            confetti.className = 'confetti';
            confetti.innerHTML = ['❤️', '💕', '💖', '💗', '💓', '💞', '💝'][Math.floor(Math.random() * 7)];
            confetti.style.fontSize = (Math.random() * 25 + 15) + 'px';
            confetti.style.left = Math.random() * window.innerWidth + 'px';
            confetti.style.top = -50 + 'px';
            confetti.style.opacity = Math.random() * 0.7 + 0.3;
            
            const duration = Math.random() * 3 + 2;
            
            document.body.appendChild(confetti);
            
            const start = Date.now();
            const animate = () => {
                const elapsed = Date.now() - start;
                const progress = elapsed / (duration * 1000);
                
                if (progress < 1) {
                    confetti.style.top = (progress * (window.innerHeight + 100)) + 'px';
                    confetti.style.transform = `rotate(${progress * 360 * 2}deg)`;
                    requestAnimationFrame(animate);
                } else {
                    confetti.remove();
                }
            };
            
            requestAnimationFrame(animate);
        }
    </script>
</body>
</html>
