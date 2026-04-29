<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no" />
  <title>🎂 Happy Birthday Samiksha | A Joyful Celebration 🎉</title>
  
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
    }

    body {
      overflow: hidden;
      height: 100vh;
      width: 100vw;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      animation: bgChange 12s infinite alternate ease-in-out;
      background-size: 400% 400%;
      background-position: center;
    }

    /* dynamic gradient background with soft pastel transitions */
    @keyframes bgChange {
      0% {
        background: linear-gradient(135deg, #ff9a9e, #fad0c4, #ffdde1);
        background-size: 200% 200%;
        background-position: 0% 50%;
      }
      25% {
        background: linear-gradient(135deg, #a18cd1, #fbc2eb, #ffb7b2);
        background-size: 200% 200%;
        background-position: 50% 50%;
      }
      50% {
        background: linear-gradient(135deg, #f6d365, #fda085, #ffcfb6);
        background-size: 200% 200%;
        background-position: 100% 50%;
      }
      75% {
        background: linear-gradient(135deg, #84fab0, #8fd3f4, #b5f4e7);
        background-size: 200% 200%;
        background-position: 100% 50%;
      }
      100% {
        background: linear-gradient(135deg, #fccb90, #d57eeb, #ffb3ba);
        background-size: 200% 200%;
        background-position: 0% 50%;
      }
    }

    /* floating card with sparkling glassmorphism */
    .container {
      text-align: center;
      padding: 28px 20px;
      border-radius: 48px;
      background: rgba(255, 255, 255, 0.2);
      backdrop-filter: blur(16px);
      box-shadow: 0 20px 40px rgba(0, 0, 0, 0.2), 0 0 0 1px rgba(255, 255, 255, 0.3);
      width: 90%;
      max-width: 440px;
      animation: floatCard 4.5s ease-in-out infinite;
      transition: all 0.3s;
      z-index: 10;
    }

    @keyframes floatCard {
      0%, 100% {
        transform: translateY(0px);
      }
      50% {
        transform: translateY(-12px);
      }
    }

    h1 {
      color: #fff;
      font-size: 1.9rem;
      font-weight: 700;
      margin-bottom: 18px;
      text-shadow: 2px 4px 15px rgba(0, 0, 0, 0.4);
      letter-spacing: -0.5px;
      word-break: break-word;
      background: linear-gradient(120deg, #fff, #ffe6f0);
      background-clip: text;
      -webkit-background-clip: text;
      color: transparent;
      text-shadow: none;
    }

    /* enhanced animated photo frame with rainbow shimmer */
    .photo-frame {
      width: 250px;
      height: 330px;
      margin: 0 auto 12px auto;
      padding: 6px;
      border-radius: 38px;
      background: linear-gradient(125deg, #ff4d6d, #ffb347, #06d6a0, #4c9aff, #e56bff);
      background-size: 350% 350%;
      animation: borderGlow 4.5s linear infinite;
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.3);
      transition: transform 0.2s ease;
    }

    .photo-frame:hover {
      transform: scale(1.01);
    }

    @keyframes borderGlow {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }

    .photo-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      border-radius: 34px;
      display: block;
      transition: all 0.3s;
      filter: brightness(1.02) contrast(1.03);
    }

    /* message block with soft shine */
    .message {
      margin-top: 24px;
      font-size: 1.13rem;
      font-weight: 500;
      color: #fff9f0;
      line-height: 1.65;
      text-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
      background: rgba(0, 0, 0, 0.1);
      backdrop-filter: blur(4px);
      border-radius: 48px;
      padding: 14px 12px;
      letter-spacing: 0.3px;
    }

    /* button with gentle bounce */
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      margin-top: 26px;
      padding: 12px 28px;
      border-radius: 60px;
      background: #ffffffdd;
      backdrop-filter: blur(4px);
      color: #e8436e;
      font-weight: bold;
      font-size: 1rem;
      text-decoration: none;
      transition: all 0.25s cubic-bezier(0.2, 0.9, 0.4, 1.1);
      box-shadow: 0 6px 14px rgba(0, 0, 0, 0.2);
      border: 1px solid rgba(255,255,240,0.6);
    }

    .btn:hover {
      transform: scale(1.08) translateY(-3px);
      background: #fff5f9;
      color: #c52d5c;
      box-shadow: 0 15px 25px rgba(0, 0, 0, 0.25);
      cursor: pointer;
    }

    .btn:active {
      transform: scale(0.97);
    }

    /* ---- floating party elements (balloons + extra cute decor) ---- */
    .balloon {
      position: absolute;
      font-size: 58px;
      opacity: 0.85;
      filter: drop-shadow(2px 4px 8px rgba(0,0,0,0.2));
      z-index: 5;
      pointer-events: none;
      animation: floatUpDown 8s infinite ease-in-out;
    }

    /* different starting positions and random speeds */
    .balloon:nth-child(1) {
      left: 5%;
      bottom: -100px;
      animation-duration: 9s;
      animation-delay: 0s;
      font-size: 68px;
    }

    .balloon:nth-child(2) {
      left: 85%;
      bottom: -80px;
      animation-duration: 11s;
      animation-delay: 1s;
      font-size: 62px;
    }

    .balloon:nth-child(3) {
      left: 20%;
      bottom: -130px;
      animation-duration: 10s;
      animation-delay: 2.5s;
      font-size: 55px;
    }

    .balloon:nth-child(4) {
      left: 70%;
      bottom: -60px;
      animation-duration: 12s;
      animation-delay: 0.5s;
      font-size: 70px;
    }

    .balloon:nth-child(5) {
      left: 45%;
      bottom: -110px;
      animation-duration: 8.5s;
      animation-delay: 1.8s;
      font-size: 60px;
    }

    .balloon:nth-child(6) {
      left: 92%;
      bottom: -40px;
      animation-duration: 13s;
      animation-delay: 0.2s;
      font-size: 52px;
    }

    .balloon:nth-child(7) {
      left: 8%;
      bottom: -150px;
      animation-duration: 14s;
      animation-delay: 3s;
      font-size: 48px;
    }

    /* floating stars / sparkles */
    .sparkle {
      position: absolute;
      font-size: 24px;
      pointer-events: none;
      opacity: 0.7;
      animation: twinkleDrift 12s infinite linear;
      z-index: 2;
    }

    @keyframes floatUpDown {
      0% {
        transform: translateY(0) rotate(0deg);
        bottom: -120px;
        opacity: 0.9;
      }
      50% {
        transform: translateX(8px) rotate(5deg);
        opacity: 1;
      }
      100% {
        transform: translateX(-6px) rotate(-3deg);
        bottom: 110%;
        opacity: 0.3;
      }
    }

    @keyframes twinkleDrift {
      0% {
        transform: translateY(0) scale(0.8);
        opacity: 0;
      }
      10% {
        opacity: 0.9;
      }
      90% {
        opacity: 0.8;
      }
      100% {
        transform: translateY(-100vh) rotate(20deg) scale(1.2);
        opacity: 0;
      }
    }

    /* Additional floating happy confetti effect using pseudo and extra divs */
    .confetti {
      position: absolute;
      width: 10px;
      height: 10px;
      background: radial-gradient(circle, #ffd966, #ffaa33);
      opacity: 0.6;
      border-radius: 2px;
      animation: confettiFall 7s infinite linear;
      pointer-events: none;
      z-index: 1;
    }

    @keyframes confettiFall {
      0% {
        transform: translateY(-10vh) rotate(0deg);
        opacity: 0.8;
      }
      100% {
        transform: translateY(120vh) rotate(360deg);
        opacity: 0;
      }
    }

    /* responsive adjustments */
    @media (max-width: 550px) {
      .container {
        padding: 20px 14px;
        max-width: 92%;
      }
      h1 {
        font-size: 1.6rem;
      }
      .photo-frame {
        width: 200px;
        height: 270px;
      }
      .message {
        font-size: 0.95rem;
        padding: 12px 10px;
      }
      .btn {
        padding: 10px 20px;
        font-size: 0.9rem;
      }
      .balloon {
        font-size: 42px;
      }
      .balloon:nth-child(1), .balloon:nth-child(2) {
        font-size: 48px;
      }
    }

    /* for better touch & accessibility */
    a {
      cursor: pointer;
    }

    /* subtle radial overlay for readability */
    .glass-helper {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: radial-gradient(circle at 50% 30%, rgba(255,240,200,0.08), rgba(0,0,0,0.1));
      pointer-events: none;
      z-index: 1;
    }
  </style>
</head>
<body>

<div class="glass-helper"></div>

<!-- 🎈 animated balloons & joy symbols -->
<div class="balloon">🎈</div>
<div class="balloon">🎉</div>
<div class="balloon">🎂</div>
<div class="balloon">🎁</div>
<div class="balloon">✨</div>
<div class="balloon">💖</div>
<div class="balloon">🎊</div>

<!-- mini floating sparkles for extra magic -->
<div class="sparkle" style="top: 15%; left: 12%; animation-duration: 14s;">⭐</div>
<div class="sparkle" style="top: 30%; left: 88%; animation-duration: 11s;">✨</div>
<div class="sparkle" style="top: 60%; left: 6%; animation-duration: 18s;">🌟</div>
<div class="sparkle" style="top: 80%; left: 93%; animation-duration: 13s;">💫</div>
<div class="sparkle" style="top: 45%; left: 75%; animation-duration: 16s;">⭐</div>
<div class="sparkle" style="top: 20%; left: 45%; animation-duration: 15s;">🎵</div>

<!-- dynamic random confetti particles generated via JS later for extra glam -->
<div id="confetti-wrapper"></div>

<!-- Main Birthday Card -->
<div class="container">
  <h1>🎂 Happy Birthday..! SAMIKSHA ! 🎂</h1>

  <div class="photo-frame">
    <!-- image from postimg (as provided) - ensures beautiful birthday portrait -->
    <img src="https://i.postimg.cc/Y9ZJrX98/IMG-20260429-100727.jpg" alt="SAMIKSHA - Birthday Girl" onerror="this.onerror=null; this.src='https://via.placeholder.com/250x330?text=🎂+Happy+Birthday+Samiksha';">
  </div>

  <div class="message">
    🎀 Wishing you a day filled with happiness, laughter, love and lots of joy 🎁💖
    <br><br>
    May your smile always shine bright like today ✨
    <br>
    🌸 You make the world more beautiful! 🌸
  </div>

  <a href="#" class="btn" id="celebrateBtn">🎊 Enjoy Your Special Day 🎊</a>
</div>

<script>
  (function() {
    // Create additional moving confetti pieces for dynamic celebration
    const confettiWrapper = document.getElementById('confetti-wrapper');
    if (confettiWrapper) {
      // generate 45 floating confetti pieces with different colors & positions
      const colors = ['#ffadad', '#ffd6a5', '#fdffb6', '#caffbf', '#9bf6ff', '#bdb2ff', '#ffc6ff', '#f0a6ca'];
      for (let i = 0; i < 65; i++) {
        const conf = document.createElement('div');
        conf.classList.add('confetti');
        const size = Math.floor(Math.random() * 10) + 5; // 5px - 14px
        const leftPos = Math.random() * 100; // vw percentage
        const delay = Math.random() * 12;
        const duration = Math.random() * 5 + 5; // 5-10s
        const bgColor = colors[Math.floor(Math.random() * colors.length)];
        conf.style.width = size + 'px';
        conf.style.height = size + 'px';
        conf.style.left = leftPos + '%';
        conf.style.top = '-5%';
        conf.style.animationDelay = delay + 's';
        conf.style.animationDuration = duration + 's';
        conf.style.backgroundColor = bgColor;
        conf.style.opacity = Math.random() * 0.7 + 0.3;
        conf.style.borderRadius = Math.random() > 0.7 ? '50%' : '2px';
        conf.style.position = 'absolute';
        conf.style.zIndex = '2';
        confettiWrapper.appendChild(conf);
      }
    }

    // additional floating hearts that appear on click or hover? button interactive feedback.
    const btn = document.getElementById('celebrateBtn');
    if (btn) {
      btn.addEventListener('click', (e) => {
        e.preventDefault();
        // create burst of floating hearts & stars on click
        for (let i = 0; i < 28; i++) {
          const heartOrStar = document.createElement('div');
          const emojis = ['❤️', '💖', '🎉', '✨', '⭐', '🌸', '🎂', '💫', '🥳'];
          const randomEmoji = emojis[Math.floor(Math.random() * emojis.length)];
          heartOrStar.innerText = randomEmoji;
          heartOrStar.style.position = 'fixed';
          heartOrStar.style.left = (e.clientX || window.innerWidth/2) + (Math.random() - 0.5) * 150 + 'px';
          heartOrStar.style.top = (e.clientY || window.innerHeight/2) + (Math.random() - 0.5) * 120 + 'px';
          heartOrStar.style.fontSize = Math.floor(Math.random() * 24) + 18 + 'px';
          heartOrStar.style.pointerEvents = 'none';
          heartOrStar.style.zIndex = '999';
          heartOrStar.style.opacity = '1';
          heartOrStar.style.transition = 'transform 1s cubic-bezier(0.2, 0.9, 0.6, 1.1), opacity 1.2s';
          heartOrStar.style.transform = 'scale(0.6)';
          document.body.appendChild(heartOrStar);
          
          // animate burst flying upward
          requestAnimationFrame(() => {
            heartOrStar.style.transform = `translate(${(Math.random() - 0.5) * 120}px, -${Math.random() * 250 + 100}px) scale(1.3) rotate(${Math.random() * 40 - 20}deg)`;
            heartOrStar.style.opacity = '0';
          });
          setTimeout(() => {
            if (heartOrStar && heartOrStar.remove) heartOrStar.remove();
          }, 1300);
        }
        
        // temporary ripple effect on button
        btn.style.transform = 'scale(0.98)';
        setTimeout(() => {
          if (btn) btn.style.transform = '';
        }, 150);
        
        // also add extra happy message in console but no issue
        console.log("🎈✨ HAPPY BIRTHDAY SAMIKSHA! ✨🎈");
      });
    }
    
    // Add a subtle flurry of sparkles that move randomly - for joy
    function createFloatingSparkle() {
      const spark = document.createElement('div');
      spark.innerText = ['⭐', '✨', '💖', '🎈', '🌸', '🎶'][Math.floor(Math.random() * 6)];
      spark.style.position = 'fixed';
      spark.style.fontSize = Math.random() * 20 + 14 + 'px';
      spark.style.left = Math.random() * 100 + '%';
      spark.style.bottom = '-30px';
      spark.style.opacity = '0.7';
      spark.style.pointerEvents = 'none';
      spark.style.zIndex = '3';
      spark.style.transition = 'all 5s linear';
      spark.style.filter = 'drop-shadow(0 2px 6px rgba(0,0,0,0.2))';
      document.body.appendChild(spark);
      
      setTimeout(() => {
        spark.style.transform = `translateY(-110vh) rotate(${Math.random() * 30}deg)`;
        spark.style.opacity = '0';
      }, 20);
      
      setTimeout(() => {
        if (spark && spark.remove) spark.remove();
      }, 5200);
    }
    
    // launch a floating sparkle every 1.8 seconds for continuous party mood
    setInterval(() => {
      if (document.hasFocus()) {
        createFloatingSparkle();
      }
    }, 1900);
    
    // initial burst of floating particles when page loads – festive welcome
    window.addEventListener('load', () => {
      for (let i = 0; i < 18; i++) {
        setTimeout(() => {
          const greetElem = document.createElement('div');
          greetElem.innerText = ['🎉', '🎂', '💖', '✨', '🎊', '🌸'][Math.floor(Math.random() * 6)];
          greetElem.style.position = 'fixed';
          greetElem.style.left = Math.random() * 100 + '%';
          greetElem.style.bottom = '10px';
          greetElem.style.fontSize = '28px';
          greetElem.style.pointerEvents = 'none';
          greetElem.style.zIndex = '100';
          greetElem.style.opacity = '0.9';
          greetElem.style.transition = 'all 3s ease-out';
          document.body.appendChild(greetElem);
          setTimeout(() => {
            greetElem.style.transform = `translateY(-75vh) translateX(${(Math.random() - 0.5) * 80}px) rotate(20deg)`;
            greetElem.style.opacity = '0';
          }, 10);
          setTimeout(() => greetElem.remove(), 3100);
        }, i * 130);
      }
    });
    
    // add floating gradient music notes or just joy but ensures responsiveness
    // also we prevent any overflow scrolling weirdness
    document.body.style.overflow = 'hidden';
    
    // small interactive hover effect for photo frame: extra shine
    const photoDiv = document.querySelector('.photo-frame');
    if (photoDiv) {
      photoDiv.addEventListener('mouseenter', () => {
        photoDiv.style.transition = 'all 0.2s';
      });
    }
  })();
</script>
</body>
</html>
