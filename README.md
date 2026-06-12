<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>¿Una vez más?</title>
<style>
body{
    font-family: Arial, sans-serif;
    background:#f8f1f1;
    text-align:center;
    padding-top:80px;
}
button{
    padding:12px 25px;
    margin:10px;
    font-size:18px;
    cursor:pointer;
}
#carta{
    display:none;
    max-width:600px;
    margin:auto;
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 0 10px rgba(0,0,0,.2);
}
</style>
</head>
<body>

<div id="inicio">
    <h1>¿Quieres intentarlo una vez más? ❤️</h1>

    <button onclick="mostrarCarta()">SÍ</button>

    <button onclick="alert('❌ Error: opción no disponible. Por favor elija SÍ.')">
        NO
    </button>
</div>

<div id="carta">
    <h2>💌 Para ti</h2>
    <p>
        Te adoro mi amor, mi Marceline.
        Gracias por cada momento compartido.
        Mi corazón siempre guarda un lugar especial para ti.
        ❤️
    </p>
</div>

<script>
function mostrarCarta(){
    document.getElementById("inicio").style.display="none";
    document.getElementById("carta").style.display="block";
}
</script>

</body>
</html>
