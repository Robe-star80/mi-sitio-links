# mi-sitio-links
Acceso integrado banner 
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Accesos Directos</title>
<style>
    body { 
        font-family: Arial; 
        background: #f0f0f0; 
        text-align: center; 
        padding: 40px;
    }
    .icon-container {
        display: flex;
        justify-content: center;
        gap: 40px;
        flex-wrap: wrap;
    }
    .icon-box {
        width: 110px;
        text-align: center;
    }
    .icon-box img {
        width: 80px;
        height: 80px;
        border-radius: 20px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        transition: 0.3s;
    }
    .icon-box img:hover {
        transform: scale(1.1);
    }
    .label {
        margin-top: 8px;
        font-size: 14px;
    }
</style>
</head>
<body>

<h1>Mis Accesos</h1>

<div class="icon-container">

    <div class="icon-box">
        <a href="https://www.google.com">
            <img src="https://cdn-icons-png.flaticon.com/512/300/300221.png">
        </a>
        <div class="label">Google</div>
    </div>

    <div class="icon-box">
        <a href="https://www.whatsapp.com">
            <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png">
        </a>
        <div class="label">WhatsApp</div>
    </div>

    <div class="icon-box">
        <a href="https://classroom.google.com">
            <img src="https://cdn-icons-png.flaticon.com/512/2965/2965335.png">
        </a>
        <div class="label">Classroom</div>
    </div>

    <div class="icon-box">
        <a href="https://drive.google.com">
            <img src="https://cdn-icons-png.flaticon.com/512/5968/5968523.png">
        </a>
        <div class="label">Drive</div>
    </div>

</div>

</body>
</html>
