<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For Aashi ❤️</title>

<style>

body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
font-family:'Arial',sans-serif;
background:linear-gradient(135deg,#ff758c,#ff7eb3,#ffd1dc);
overflow:hidden;
}

/* Glowing card */
.card{
position:relative;
z-index:5;
background:rgba(255,255,255,0.95);
padding:35px;
border-radius:30px;
max-width:380px;
text-align:center;
box-shadow:0 0 40px rgba(255,0,100,.4);
animation:zoom 1.5s ease;
}

h1{
color:#e91e63;
font-size:28px;
}

p{
font-size:18px;
line-height:1.7;
color:#555;
}

button{
background:#e91e63;
color:white;
border:none;
padding:14px 30px;
border-radius:50px;
font-size:18px;
cursor:pointer;
box-shadow:0 5px 15px rgba(233,30,99,.5);
}


/* Hearts */

.heart{
position:absolute;
font-size:25px;
animation:heartMove 8s linear infinite;
}

@keyframes heartMove{
0%{
transform:translateY(100vh) scale(.5);
opacity:0;
}
20%{
opacity:1;
}
100%{
transform:translateY(-120vh) scale(1.5);
opacity:0;
}
}


/* Roses */

.rose{
position:absolute;
font-size:35px;
animation:roseFall 10s linear infinite;
}

@keyframes roseFall{
0%{
transform:translateY(-100px) rotate(0deg);
}
100%{
transform:translateY(110vh) rotate(360deg);
}
}


/* Balloons */

.balloon{
position:absolute;
font-size:45px;
animation:balloonUp 12s linear infinite;
}

@keyframes balloonUp{
0%{
transform:translateY(110vh);
}
100%{
transform:translateY(-120vh);
}
}


/* Sparkle */

.sparkle{
position:absolute;
font-size:20px;
animation:blink 2s infinite;
}

@keyframes blink{
50%{
opacity:.2;
}
}


@keyframes zoom{
from{
opacity:0;
transform:scale(.5);
}
to{
opacity:1;
transform:scale(1);
}
}

</style>

</head>


<body>


<div class="card">

<h1>🌹 Good Morning, Aashi Ji ❤️</h1>

<p>

Every sunrise becomes more beautiful when we remember the special people who bring happiness into our lives. ☀️❤️

<br><br>

May your day be filled with endless smiles, happiness, success and beautiful moments. 🌸

<br><br>

You deserve all the positivity and love this beautiful morning brings. 💖

<br><br>

✨ Have a wonderful day ahead ✨

</p>


<button onclick="message()">
💌 Open Surprise
</button>


</div>



<script>


function message(){
alert("🌹 A small surprise to make your morning brighter ❤️ Have a beautiful day, Aashi Ji!");
}


// Hearts

for(let i=0;i<35;i++){

let h=document.createElement("div");
h.className="heart";
h.innerHTML="❤️";

h.style.left=Math.random()*100+"vw";
h.style.animationDuration=(5+Math.random()*6)+"s";

document.body.appendChild(h);

}


// Roses

for(let i=0;i<20;i++){

let r=document.createElement("div");
r.className="rose";
r.innerHTML="🌹";

r.style.left=Math.random()*100+"vw";
r.style.animationDuration=(6+Math.random()*8)+"s";

document.body.appendChild(r);

}


// Balloons

for(let i=0;i<12;i++){

let b=document.createElement("div");
b.className="balloon";
b.innerHTML="🎈";

b.style.left=Math.random()*100+"vw";
b.style.animationDuration=(8+Math.random()*8)+"s";

document.body.appendChild(b);

}


// Sparkles

for(let i=0;i<20;i++){

let s=document.createElement("div");
s.className="sparkle";
s.innerHTML="✨";

s.style.left=Math.random()*100+"vw";
s.style.top=Math.random()*100+"vh";

document.body.appendChild(s);

}


</script>


</body>
</html>
