# crab
So it’s a very crab website…
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crab Detector</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>How Crab Are You?</h1>
        <p>Upload an image to see how "orange" it is!</p>
        <input type="file" id="imageInput" accept="image/*" />
        <canvas id="canvas" style="display:none;"></canvas>
        <div id="result">
            <p id="score">Upload an image to get started!</p>
            <p id="crabLevel"></p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
