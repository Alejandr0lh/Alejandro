# Alejandro
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Invitación de San Valentín!</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="container">
        <h1>¡Te invito a celebrar San Valentín conmigo!</h1>
        <img src="https://images.unsplash.com/photo-1519751138087-5c2a60c5631b?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Imagen romántica" class="romantic-image">
        <p>Este 14 de febrero, quiero compartir un momento especial contigo. ¡Únete a mí para una noche llena de amor y alegría!</p>
        <div class="details">
            <p><strong>Fecha:</strong> 14 de febrero de 2025</p>
            <p><strong>Hora:</strong> 8:00 PM</p>
            <p><strong>Lugar:</strong> Mi lugar secreto (¡te lo revelaré pronto!)</p>
        </div>
        <button id="rsvpButton">¡Confirma tu asistencia!</button>
        <div id="rsvpMessage" class="message hidden"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    background-color: #fce4ec; /* Un rosa claro */
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    padding: 20px;
}

.container {
    background-color: white;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0,0,0,0.1);
    text-align: center;
    max-width: 600px;
    width: 100%;
}

h1 {
    color: #e91e63; /* Un rosa más fuerte */
    margin-bottom: 20px;
    font-family: "Dancing Script", cursive;
    font-weight: 700;
}

.romantic-image {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-bottom: 20px;
}

.details {
    margin-bottom: 20px;
}

.details p {
    margin: 5px 0;
}

button {
    background-color: #e91e63;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #c2185b;
}

.message {
    margin-top: 20px;
    padding: 10px;
    border-radius: 5px;
    font-weight: bold;
}

.message.success {
    background-color: #a5d6a7;
    color: #1b5e20;
}

.message.error {
    background-color: #ffcdd2;
    color: #b71c1c;
}

.hidden {
    display: none;
}
