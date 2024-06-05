<!DOCTYPE html>
<html lang="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Melodi.Noter</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
        }
        section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2em;
        }
        .image-container {
            margin: 1em;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            height: 200px;
        }
        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        footer {
            background-color: #4CAF50;
            color: white;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Melodi.Noter</h1>
    </header>
    <section>
        <div class="image-container">
            <img src="bilde1.jpg" alt="Bilde 1">
        </div>
        <div class="image-container">
            <img src="bilde2.jpg" alt="Bilde 2">
        </div>
        <div class="image-container">
            <img src="bilde3.jpg" alt="Bilde 3">
        </div>
        <div class="image-container">
            <img src="bilde4.jpg" alt="Bilde 4">
        </div>
        <div class="image-container">
            <img src="bilde5.jpg" alt="Bilde 5">
        </div>
        <div class="image-container">
            <img src="bilde6.jpg" alt="Bilde 6">
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Melodi.Noter</p>
    </footer>
</body>
</html>
