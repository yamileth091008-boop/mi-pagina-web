<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Make Up</title>
<style>
body{
background:#ffd6e8;
font-family:Arial;
text-align:center;
}
img{
width:300px;
border-radius:20px;
}
a{
display:inline-block;
margin:20px;
padding:15px 25px;
background:#ff4f87;
color:white;
text-decoration:none;
border-radius:10px;
font-size:20px;
}
</style>
</head>

<body>

<h1>MAKE UP</h1>

<img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?w=600" alt="Maquillaje">

<p>
Bienvenido a mi página web sobre maquillaje.
Aquí conocerás los tipos de maquillaje y un pequeño tutorial.
</p>

<a href="pagina1.html">Tipos de maquillaje</a>

<a href="pagina2.html">Tutorial</a>

</body>
</html><!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tipos de Maquillaje</title>

<style>

body{
background:#fff0f6;
font-family:Arial;
text-align:center;
}

img{
width:300px;
border-radius:20px;
}

a{
display:inline-block;
margin:20px;
padding:15px 25px;
background:#ff4f87;
color:white;
text-decoration:none;
border-radius:10px;
}

</style>

</head>

<body>

<h1>Tipos de Maquillaje</h1>

<img src="https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?w=600">

<h2>Natural</h2>
<p>Ideal para el uso diario.</p>

<h2>Social</h2>
<p>Perfecto para fiestas.</p>

<h2>Glam</h2>
<p>Con brillo y colores intensos.</p>

<a href="index.html">Menú</a>

<a href="pagina2.html">Página 2</a>

</body>

</html><!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Tutorial</title>

<style>

body{
background:#ffe4ef;
font-family:Arial;
text-align:center;
}

img{
width:350px;
border-radius:20px;
}

a{
display:inline-block;
margin:20px;
padding:15px 25px;
background:#ff4f87;
color:white;
text-decoration:none;
border-radius:10px;
}

</style>

</head>

<body>

<h1>Tutorial de Maquillaje</h1>

<img src="https://img.youtube.com/vi/Xjv1sY630Uc/maxresdefault.jpg">

<h2>Pasos</h2>

<p>
1. Limpia tu rostro.<br>
2. Aplica primer.<br>
3. Coloca la base.<br>
4. Usa corrector.<br>
5. Aplica sombras.<br>
6. Delineador.<br>
7. Máscara para pestañas.<br>
8. Labial.
</p>

<a href="https://www.youtube.com/watch?v=Xjv1sY630Uc">
Ver Video
</a>

<br>

<a href="index.html">Menú</a>

<a href="pagina1.html">Página 1</a>

</body>

</html><h2>Agenda tu cita</h2>

Nombre:
<input type="text"><br><br>

Correo:
<input type="email"><br><br>

Fecha:
<input type="date"><br><br>

<input type="submit" value="Enviar"><h2>Calculadora</h2>

<input type="number" id="n1">

+

<input type="number" id="n2">

<button onclick="sumar()">Sumar</button>

<p id="resultado"></p>

<script>
function sumar(){
let a=Number(document.getElementById("n1").value);
let b=Number(document.getElementById("n2").value);

document.getElementById("resultado").innerHTML="Resultado: "+(a+b);
}
</script><audio id="sonido" src="clic.mp3"></audio>

<button onclick="document.getElementById('sonido').play()">
Escuchar sonido
</button>a:hover{

background:#ff1493;

transform:scale(1.1);

transition:.3s;

}
</body>
</html>
