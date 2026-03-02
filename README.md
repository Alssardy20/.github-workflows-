<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Satellite Guide</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<style>
body {
  margin: 0;
  font-family: Poppins, Arial, sans-serif;
  background: linear-gradient(180deg, #0b1220, #09162e);
  color: white;
}

header {
  background: #0f1f3d;
  padding: 18px;
  text-align: center;
  font-size: 22px;
  font-weight: 600;
  box-shadow: 0 4px 12px rgba(0,0,0,.5);
}

.container {
  padding: 16px;
}

.card {
  background: linear-gradient(145deg, #122a52, #0c1f3a);
  border-radius: 16px;
  padding: 16px;
  margin-bottom: 14px;
  box-shadow: 0 6px 18px rgba(0,0,0,.45);
  transition: transform .15s ease;
}

.card:hover {
  transform: scale(1.02);
}

.card h3 {
  margin: 0 0 10px;
  font-weight: 600;
}

button {
  width: 100%;
  padding: 12px;
  border: none;
  border-radius: 10px;
  background: linear-gradient(135deg, #1f6fff, #3fa9ff);
  color: white;
  font-size: 16px;
  font-weight: 600;
}

input {
  width: 100%;
  padding: 12px;
  border-radius: 10px;
  border: none;
  margin-bottom: 10px;
  background: #091d3a;
  color: white;
}

footer {
  text-align: center;
  padding: 14px;
  font-size: 13px;
  color: #9fb4ff;
}
</style>
</head>

<body>

<header>📡 Satellite Guide</header>

<div class="container">

<div class="card">
<h3>🛰️ Satellites</h3>
<p>Nilesat — Arabsat — Hotbird</p>
</div>

<div class="card">
<h3>📺 Popular Frequencies</h3>
<p>MBC 1 — 11470 V — SR 27500</p>
<p>Al Jazeera — 10971 H — SR 27500</p>
<p>beIN Sports — 11013 H — SR 27500</p>
</div>

<div class="card">
<h3>🔍 Search Channel</h3>
<input placeholder="Search channel name...">
<button>Search</button>
</div>

<div class="card">
<h3>🔄 Device Updates</h3>
<p>Starsat — Tiger — Samsat</p>
<button>Download Firmware</button>
</div>

<div class="card">
<h3>📨 Request Frequency</h3>
<input placeholder="Channel Name">
<input placeholder="Satellite (optional)">
<button>Send Request</button>
</div>

</div>

<footer>
Satellite Guide — Developed by Hussain
</footer>

</body>
</html>