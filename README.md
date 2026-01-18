<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ND XXX - HD Videos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        video {
            width: 100%;
            height: auto;
        }
        @media (max-width: 768px) {
            .video-grid {
                grid-template-columns: 1fr;
            }
            header {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>ND XXX</h1>
        <p>HD Videos Available on All Devices</p>
    </header>
    <div class="container">
        <div class="video-grid">
            <!-- Replace with actual video sources -->
            <video controls>
                <source src="path/to/your/hd-video1.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <video controls>
                <source src="path/to/your/hd-video2.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
            <!-- Add more videos as needed -->
        </div>
    </div>
</body>
</html>

