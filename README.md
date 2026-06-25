<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chess Registration</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
min-height:100vh;
display:flex;
justify-content:center;
align-items:center;
background:linear-gradient(135deg,#0d0221,#240046,#3c096c);
overflow:hidden;
}

.container{
width:90%;
max-width:450px;
padding:25px;
border-radius:20px;
background:rgba(255,255,255,0.08);
backdrop-filter:blur(15px);
box-shadow:0 0 25px #ff00ff;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{box-shadow:0 0 20px #ff00ff;}
to{box-shadow:0 0 40px #00ffff;}
}

h1{
text-align:center;
color:white;
margin-bottom:20px;
text-shadow:0 0 15px #ff00ff;
}

input{
width:100%;
padding:12px;
margin:10px 0;
border:none;
border-radius:10px;
outline:none;
background:rgba(255,255,255,0.15);
color:white;
}

input::placeholder{
color:#ddd;
}

button{
width:100%;
padding:14px;
border:none;
border-radius:30px;
font-size:18px;
font-weight:bold;
color:white;
cursor:pointer;
background:linear-gradient(90deg,#ff00ff,#ff7b00);
transition:.3s;
}

button:hover{
transform:scale(1.05);
}

.chess{
font-size:40px;
text-align:center;
animation:float 3s infinite;
}

@keyframes float{
50%{transform:translateY(-10px);}
}
</style>
</head>

<body>

<div class="container">
<div class="chess">♔ ♕ ♖</div>

<h1>CHESS REGISTRATION</h1>

<form>
<input type="text" placeholder="Full Name" required>
<input type="number" placeholder="Age" required>
<input type="date" required>
<input type="tel" placeholder="Mobile Number" required>
<input type="text" placeholder="City" required>
<input type="text" placeholder="Aadhaar Number" required>

<button type="submit">REGISTER NOW</button>
</form>

</div>

</body>
</html>