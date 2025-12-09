<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Your Landing Page</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Internal CSS -->
  <style>
    /* Page basics */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #022c22; /* dark green */
      color: #ffffff;
      text-align: center;
    }
    
    .wrapper {
      max-width: 420px;
      margin: 0 auto;
      padding: 24px 16px 40px;
    }

    <div class="logo-circle">
  <img src="1000148374.jpg" alt="Logo" class="logo-img">
</div>
   
  .logo-circle {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    border: 4px solid #facc15; /* yellow border */
    margin: 0 auto 16px;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;            
    background-color: #000000; /* fallback bg */
  }

  .logo-img {
    width: 100%;
    height: 100%;
    object-fit: cover;      
  }

  /* Heading and subtitle */
  h1 {
    font-size: 26px;
    margin: 8px 0 4px;
  }
  
  .tagline {
    font-size: 14px;
    color: #c4c4c4;
    margin-bottom: 20px;
  }

  /* Stats cards */
  .stats {
    display: flex;
    gap: 8px;
    margin-bottom: 20px;
  }

  .stat-card {
    flex: 1;
    background-color: #064e3b;
    border-radius: 10px;
    padding: 10px 4px;
    font-size: 11px;
  }

  .stat-main {
    font-weight: bold;
    font-size: 14px;
    color: #facc15;
  }

  /* CTA button */
  .cta-btn {
    display: block;
    width: 100%;
    margin: 8px 0 14px;
    padding: 14px 0;
    background-color: #f59e0b; /* orange */
    color: #111111;
    border: none;
    border-radius: 999px;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
  }

  .cta-btn:hover {
    background-color: #fbbf24;
  }

  .badge {
    display: inline-block;
    padding: 6px 16px;
    border-radius: 999px;
    background-color: #ef4444; /* red */
    font-size: 12px;
    font-weight: 600;
    margin-bottom: 16px;
  }

  /* Benefits box */
  .benefits {
    background-color: #064e3b;
    border-radius: 16px;
    padding: 16px 14px;
    text-align: middle;
    font-size: 13px;
  }

  .benefits ul {
    list-style: none;
    padding-left: 0;
    margin: 0;
  }

  .benefits li {
    margin-bottom: 8px;
  }

  .benefits li::before {
    content: "★ ";
    color: #facc15;
  }

  </style>
</head>

<body>
  <div class="wrapper">
    <!-- top logo area -->
    <div class="logo-circle">
      LOGO
    </div>

    <h1>South_Indian_Report</h1>
    <div class="tagline">Premium Match & Toss Predictions</div>

    <!-- stats -->
    <div class="stats">
      <div class="stat-card">
        <div class="stat-main">165,423+</div>
        <div>Subscribers</div>
      </div>
      <div class="stat-card">
        <div class="stat-main">99.99%</div>
        <div>Accuracy</div>
      </div>
      <div class="stat-card">
        <div class="stat-main">Tips</div>
        <div>Free + Match</div>
      </div>
    </div>
    
<!-- main button -->
    <button class="cta-btn">
    <a href="https://t.me/+YPGUNZl08xYyODM1" target="_blank" class="cta-link">JOIN CHANNEL NOW</a>
 </button>


    <div class="badge">99.99% Accuracy in All Matches</div>

    <!-- benefits -->
    <div class="benefits">
      <ul>
        <li>Toss + Match free tips</li>
        <li>"Daily expert guidance with risk management"</li>
        <li>Immediate updates before every session</li>
      </ul>
    </div>
  </div>
</body>
</html> 
