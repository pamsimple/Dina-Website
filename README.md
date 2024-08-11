# Dina-Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dina Aliguyon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1 class="name">Dina Aliguyon</h1>
        <nav class="nav">
            <a href="#about">About</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </div>
    <script src="script.js"></script>
</body>
</html>
body {
    margin: 0;
    padding: 0;
    font-family: 'Montserrat', sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
}

.container {
    text-align: center;
}

.name {
    font-size: 5rem;
    font-weight: bold;
    text-transform: uppercase;
    background: linear-gradient(90deg, #00C9FF, #92FE9D);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: glow 1s ease-in-out infinite alternate;
}

@keyframes glow {
    from {
        text-shadow: 0 0 10px #00C9FF, 0 0 20px #00C9FF, 0 0 30px #00C9FF, 0 0 40px #00C9FF, 0 0 50px #00C9FF, 0 0 60px #00C9FF, 0 0 70px #00C9FF;
    }
    to {
        text-shadow: 0 0 20px #92FE9D, 0 0 30px #92FE9D, 0 0 40px #92FE9D, 0 0 50px #92FE9D, 0 0 60px #92FE9D, 0 0 70px #92FE9D, 0 0 80px #92FE9D;
    }
}

.nav {
    margin-top: 20px;
}

.nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 10px 20px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 5px;
    transition: background 0.3s ease, transform 0.3s ease;
}

.nav a:hover {
    background: rgba(255, 255, 255, 0.3);
    transform: scale(1.1);
}
body {
    margin: 0;
    padding: 0;
    font-family: 'Montserrat', sans-serif;
    background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    overflow: hidden;
}

.container {
    text-align: center;
}

.name {
    font-size: 5rem;
    font-weight: bold;
    text-transform: uppercase;
    background: linear-gradient(90deg, #00C9FF, #92FE9D);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: glow 1s ease-in-out infinite alternate;
}

@keyframes glow {
    from {
        text-shadow: 0 0 10px #00C9FF, 0 0 20px #00C9FF, 0 0 30px #00C9FF, 0 0 40px #00C9FF, 0 0 50px #00C9FF, 0 0 60px #00C9FF, 0 0 70px #00C9FF;
    }
    to {
        text-shadow: 0 0 20px #92FE9D, 0 0 30px #92FE9D, 0 0 40px #92FE9D, 0 0 50px #92FE9D, 0 0 60px #92FE9D, 0 0 70px #92FE9D, 0 0 80px #92FE9D;
    }
}

.nav {
    margin-top: 20px;
}

.nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 10px 20px;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 5px;
    transition: background 0.3s ease, transform 0.3s ease;
}

.nav a:hover {
    background: rgba(255, 255, 255, 0.3);
    transform: scale(1.1);
}
