 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Love ❤️</title>
<style>
body {
  margin: 0;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-family: Arial, sans-serif;
  background: linear-gradient(135deg, #ff758c, #ff7eb3);
  color: white;
}
.card {
  background: rgba(255,255,255,0.2);
  padding: 30px 20px;
  border-radius: 25px;
  width: 85%;
  max-width: 350px;
  box-shadow: 0 8px 25px #b8326066;
}
h1 { font-size: 32px; }
button {
  border: none;
  padding: 13px 28px;
  margin: 10px;
  border-radius: 25px;
  font-size: 18px;
  cursor: pointer;
}
#yes { background: #ff1744; color: white; }
#no { background: white; color: #ff1744; }
#message { font-size: 20px; margin-top: 20px; }
</style>
</head>
<body>
<div class="card">
  <h1>I LOVE YOU ❤️</h1>
  <p>Will you be mine? 💖🥹</p>
  <button id="yes" onclick="yesLove()">YES 💖</button>
  <button id="no" onclick="noLove()">NO 💔</button>
  <div id="message"></div>
</div>
<script>
function yesLove() {
  document.getElementById("message").innerHTML =
  "Yayyy! ❤️🥰 You made my day! 💕😘";
  document.querySelector(".card").style.background =
  "rgba(255,80,130,0.5)";
}
function noLove() {
  document.getElementById("message").innerHTML =
  "Oh no! 💔🥺 Maybe someday... ❤️‍🩹";
}
</script>
</body>
</html>
