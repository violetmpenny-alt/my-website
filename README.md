<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water - Inspire Change</title>
  <style>
    @import url('https://fonts.cdnfonts.com/css/proxima-nova-2');

    body {
      margin: 0;
      font-family: 'Proxima Nova', sans-serif;
      background-color: #f9f9f9;
      color: #fff;
      overflow-x: hidden;
    }

    /* Header Banner */
    header {
      width: 100%;
      background: #FFD400;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 40px;
      position: fixed;
      top: 0;
      left: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .header-logo {
      display: flex;
      align-items: center;
      font-weight: 600;
      font-size: 1.1rem;
      color: #000;
    }

    .header-logo img {
      height: 28px;
      margin-right: 10px;
    }

    .header-btn {
      background: #000;
      color: #FFD400;
      border: none;
      padding: 10px 22px;
      border-radius: 30px;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .header-btn:hover {
      transform: scale(1.08);
      background: #222;
    }

    /* Hero Section */
    .hero {
      position: relative;
      height: 100vh;
      background: url(Screenshot\ 2025-09-07\ at\ 3.38.16\ PM.png) no-repeat center center/cover; /* 🔄 replace with your background image */
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 40px;
      color: #fff;
      padding-top: 100px; /* offset for header */
    }

    .hero::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.45);
    }

    .hero-content {
      position: relative;
      max-width: 650px;
      z-index: 1;
      animation: fadeInUp 1.5s ease forwards;
    }

    h1 {
      font-size: 3rem;
      font-weight: 300; /* thin look */
      margin-bottom: 25px;
      line-height: 1.2;
      color: #fff;
      text-shadow: 0 3px 10px rgba(0,0,0,0.5);
      opacity: 0;
      animation: slideIn 1.5s ease forwards;
      animation-delay: 0.3s;
    }

    p {
      font-size: 1.2rem;
      margin-bottom: 40px;
      line-height: 1.6;
      color: #f0f0f0;
      font-weight: 300;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
      animation-delay: 0.8s;
    }

    /* Animated CTA Button */
    .give-btn {
      background: #FFD400;
      color: #000;
      font-weight: 600;
      border: none;
      padding: 16px 36px;
      border-radius: 50px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      font-size: 1.2rem;
      box-shadow: 0 6px 20px rgba(0,0,0,0.2);
      transition: all 0.3s ease;
      position: relative;
      overflow: hidden;
      opacity: 0;
      animation: fadeInUp 1.5s ease forwards;
      animation-delay: 1.2s;
    }

    .give-btn::after {
      content: "";
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: rgba(255,255,255,0.5);
      transition: left 0.4s;
    }

    .give-btn:hover::after {
      left: 100%;
    }

    .give-btn:hover {
      background: #ffcc00;
      transform: scale(1.08) rotate(-1deg);
    }

    /* Right-side image */
    .side-image {
      position: absolute;
      right: 40px;
      bottom: 60px;
      width: 320px;
      border-radius: 8px;
      overflow: hidden;
      z-index: 1;
      box-shadow: 0 6px 16px rgba(0,0,0,0.2);
      opacity: 0;
      animation: fadeIn 2s ease forwards;
      animation-delay: 1.5s;
    }

    .side-image img {
      width: 100%;
      display: block;
    }

    /* Keyframes for animations */
    @keyframes fadeInUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes slideIn {
      from { transform: translateX(-50px); opacity: 0; }
      to { transform: translateX(0); opacity: 1; }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Responsive */
    @media (max-width: 768px) {
      .side-image {
        position: static;
        margin-top: 25px;
        width: 100%;
      }

      .hero {
        align-items: center;
        text-align: center;
        padding: 20px;
      }

      .hero-content {
        max-width: 90%;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="header-logo">
      <img src="charity-water.webp" alt="Charity: Water Logo"> <!-- 🔄 replace with your logo file -->
      charity: water
    </div>
    <button class="header-btn">Give 💧</button>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Lead Change. Fund Impact. Inspire a Better World.</h1>
      <p>
        Join a global movement of young changemakers tackling one of the
        world’s most urgent issues. Big change starts with bold first steps.
      </p>
      <a href="#donate" class="give-btn">Give 💧</a>
    </div>

    <div class="side-image">
      <img src="Website_Layout_Mobile_92_768x.webp" alt="Child carrying water"> <!-- 🔄 replace with your side image -->
    </div>
  </section>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My GitHub Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #333;
    }
    p {
      font-size: 18px;
      color: #555;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Website!</h1>
  <p>This is my GitHub Pages site. All my content will display correctly now.</p>
  
  <!-- Example of adding more HTML content -->
  <ul>
    <li>HTML content works</li>
    <li>CSS works</li>
    <li>JavaScript can be added too</li>
  </ul>

  <script>
    console.log("Hello from GitHub Pages!");
  </script>
</body>
</html>
