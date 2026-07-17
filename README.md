<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Good Morning</title>

<style>
body{
margin:0;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
background:linear-gradient(135deg,#87CEEB,#FFD54F);
font-family:Arial,sans-serif;
overflow:hidden;
}

.card{
background:white;
padding:30px;
border-radius:20px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,.2);
max-width:350px;
animation:pop 1s;
}

h1{
color:#ff9800;
}

p{
font-size:18px;
line-height:1.6;
}

button{
padding:12px 25px;
border:none;
border-radius:30px;
background:#ff9800;
color:white;
font-size:18px;
cursor:pointer;
}

@keyframes pop{
from{transform:scale(.5);opacity:0;}
to{transform:scale(1);opacity:1;}
}
</style>
</head>

<body>

<div class="card">
<h1>🌞 Good Morning 🌞</h1>

<p>
Respected <b>CCM Mam Aashi Ji</b>,<br><br>

Wishing you a wonderful morning filled with happiness, success, and positive energy. ☀️✨<br><br>

Have a fantastic day ahead! 🌸
</p>

<button onclick="alert('😊 Thank you for everything. Have a wonderful day!')">
🌼 Tap Here
</button>

</div>

</body>
</html>
