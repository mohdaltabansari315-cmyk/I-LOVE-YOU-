

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
  padding: 30px 20px;
  border-radius: 25px;
  width: 85%;
  max-width: 350px;
  background: #ffffff30;
}
button {
  padding: 13px 25px;
  margin: 8px;
  border: none;
  border-radius: 25px;
  font-size: 18px;
}
#yes { background: #ff1744; color: white; }
#no { background: white; color: #ff1744; }
</style>
</head>
<body>
<div class="card">
<h1>I LOVE YOU ❤️</h1>
<p>Will you be mine? 🥹💖</p>
<button id="yes" onclick="document.getElementById('msg').innerHTML='Yay! ❤️ You made me so happy! 🥰💖'">YES 💖</button>
<button id="no" onclick="document.getElementById('msg').innerHTML='Oh no! 💔 Maybe someday ❤️‍🩹'">NO 💔</button>
<h3 id="msg"></h3>
</div>
</body>
</html>
