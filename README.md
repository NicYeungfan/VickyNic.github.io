# VickyNic.github.io
love
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #005b96;
        }
        .image-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: space-between;
        }
        .image-container img {
            width: calc(33.333% - 10px); /* Make each image take up 1/3 of the container minus the gap */
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            padding: 5px;
            background-color: white;
        }
    </style>
</head>
<body>
    <h1>Image Gallery</h1>

    <div class="image-container">
        <img src="DSC01703.JPG" alt="Image 1" />
        <img src="DSC01704.JPG" alt="Image 2" />
        <img src="DSC01722.JPG" alt="Image 3" />
    </div>

</body>
</html>
