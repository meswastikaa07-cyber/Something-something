# Something-something
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kuchupuchu Love Detector</title>
  <style>
    body {
      background: #0f0f0f;
      color: #00ffcc;
      font-family: monospace;
      text-align: center;
      padding-top: 50px;
    }
    button {
      background: #00ffcc;
      color: black;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      cursor: pointer;
      border-radius: 8px;
      margin-top: 20px;
    }
    #result {
      margin-top: 30px;
      font-size: 20px;
      color: #ff4d6d;
      display: none;
    }
  </style>
</head>

<body>

<h1>💖 Kuchupuchu Love Detector 💖</h1>
<p>Enter your name to check compatibility 👀</p>

<input id="name" placeholder="Your name here" style="padding:10px;">
<br>
<button onclick="checkLove()">Run Algorithm</button>

<div id="result"></div>

<script>
function checkLove() {
  let name = document.getElementById("name").value.toLowerCase();
  let result = document.getElementById("result");

  if (name === "nitin") {
    result.innerHTML =
      "❤️ MATCH FOUND ❤️<br><br>" +
      "Status: Kuchupuchu Baby Confirmed 🐥<br>" +
      "Compatibility: 1000000%<br>" +
      "Verdict: You are stuck with me forever 😌";
  } else {
    result.innerHTML =
      "❌ ERROR ❌<br><br>" +
      "Only Nitin is authorized to access this heart 💘";
  }

  result.style.display = "block";
}
</script>

</body>
</html>
