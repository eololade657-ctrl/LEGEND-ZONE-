<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Blue VIP Predictions</title>
<style>
  * { margin:0; padding:0; box-sizing:border-box; font-family: 'Poppins', sans-serif; }

  body {
    background: #e0f2fe; /* Light sky blue background */
    color: #1e293b;
    padding: 12px;
  }

  /* Header */
  .header {
    text-align: center;
    font-size: 26px;
    font-weight: 800;
    margin-bottom: 18px;
    color: #0ea5e9; /* Bright VIP blue */
    text-shadow: 0 0 6px #0ea5e9;
  }

  /* Container */
  .container { display: flex; flex-direction: column; gap: 10px; }

  /* Card */
  .card {
    background: #bae6fd; /* Light blue card */
    border-left: 6px solid #0ea5e9; /* VIP blue accent */
    border-radius: 10px;
    padding: 12px 10px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.2);
    transition: transform 0.2s;
  }

  .card:hover { transform: scale(1.02); }

  /* Item layout */
  .item {
    display: flex;
    justify-content: space-between;
    margin: 4px 0;
    font-size: 15px;
  }

  .item-label { color: #0c4a6e; font-weight: 600; }

  /* Result colors */
  .result-win { color: #16a34a; font-weight: bold; }
  .result-lose { color: #dc2626; font-weight: bold; }
  .result-pending { color: #fbbf24; font-weight: bold; }
</style>
</head>
<body>

<div class="header">BLUE VIP PREDICTIONS</div>

<div class="container">

  <!-- Day 1 -->
  <div class="card">
    <div class="item"><span class="item-label">Date:</span> 10 Feb 2026</div>
    <div class="item"><span class="item-label">Match:</span> Barcelona vs Real Madrid</div>
    <div class="item"><span class="item-label">Tip:</span> Over 3.5 Goals</div>
    <div class="item"><span class="item-label">Results:</span> <span class="result-pending">PENDING</span></div>
  </div>

  <!-- Day 2 -->
  <div class="card">
    <div class="item"><span class="item-label">Date:</span> 09 Feb 2026</div>
    <div class="item"><span class="item-label">Match:</span> Liverpool vs Manchester City</div>
    <div class="item"><span class="item-label">Tip:</span> B.T.T.S</div>
    <div class="item"><span class="item-label">Results:</span> <span class="result-win">WIN</span></div>
  </div>

  <!-- Day 3 -->
  <div class="card">
    <div class="item"><span class="item-label">Date:</span> 08 Feb 2026</div>
    <div class="item"><span class="item-label">Match:</span> Juventus vs Inter Milan</div>
    <div class="item"><span class="item-label">Tip:</span> Over 2.5 Goals</div>
    <div class="item"><span class="item-label">Results:</span> <span class="result-lose">LOSS</span></div>
  </div>

  <!-- Day 4 -->
  <div class="card">
    <div class="item"><span class="item-label">Date:</span> 07 Feb 2026</div>
    <div class="item"><span class="item-label">Match:</span> PSG vs Lyon</div>
    <div class="item"><span class="item-label">Tip:</span> B.T.T.S</div>
    <div class="item"><span class="item-label">Results:</span> <span class="result-win">WIN</span></div>
  </div>

</div>
</body>
</html>
