```html
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohit Fitness</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
    }

    header {
      background: #1e1e1e;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      color: #00ff88;
      font-size: 35px;
    }

    nav {
      margin-top: 15px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 10px;
      font-weight: bold;
    }

    nav a:hover {
      color: #00ff88;
    }

    .hero {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #111, #173d2d);
    }

    .hero h2 {
      font-size: 45px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 20px;
      margin-bottom: 25px;
    }

    .btn {
      display: inline-block;
      background: #00ff88;
      color: #111;
      padding: 12px 25px;
      border-radius: 25px;
      text-decoration: none;
      font-weight: bold;
    }

    .section {
      padding: 50px 20px;
      text-align: center;
    }

    .section h2 {
      color: #00ff88;
      margin-bottom: 30px;
    }

    .cards {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .card {
      background: #222;
      padding: 25px;
      width: 250px;
      border-radius: 15px;
      box-shadow: 0 0 10px #000;
    }

    .card h3 {
      color: #00ff88;
      margin-bottom: 10px;
    }

    footer {
      background: #1e1e1e;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>

<body>

  <header>
    <h1>ROHIT FITNESS</h1>

    <nav>
      <a href="#home">Home</a>
      <a href="#workout">Workout</a>
      <a href="#tips">Tips</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>Stay Fit, Stay Strong 💪</h2>
    <p>Welcome to Rohit Fitness</p>
    <a href="#workout" class="btn">Start Workout</a>
  </section>

  <section class="section" id="workout">
    <h2>Workout Plans</h2>

    <div class="cards">

      <div class="card">
        <h3>🏃 Cardio</h3>
        <p>Walking, jogging और अन्य सामान्य cardio activities.</p>
      </div>

      <div class="card">
        <h3>🧘 Flexibility</h3>
        <p>Stretching और mobility exercises से flexibility पर काम करें।</p>
      </div>

      <div class="card">
        <h3>💪 Strength</h3>
        <p>सही technique और सुरक्षित तरीके से strength training सीखें।</p>
      </div>

    </div>
  </section>

  <section class="section" id="tips">
    <h2>Fitness Tips</h2>

    <div class="cards">
      <div class="card">
        <h3>💧 पानी</h3>
        <p>दिनभर पर्याप्त पानी पीने की आदत रखें।</p>
      </div>

      <div class="card">
        <h3>😴 नींद</h3>
        <p>अच्छी नींद और आराम को अपनी routine का हिस्सा बनाएं।</p>
      </div>

      <div class="card">
        <h3>🥗 भोजन</h3>
        <p>संतुलित और पौष्टिक भोजन को प्राथमिकता दें।</p>
      </div>
    </div>
  </section>

  <section class="section" id="contact">
    <h2>Contact</h2>
    <p>Rohit Fitness में आपका स्वागत है!</p>
  </section>

  <footer>
    <p>© 2026 Rohit Fitness | Created by Rohit Nayak</p>
  </footer>

</body>
</html>
```
