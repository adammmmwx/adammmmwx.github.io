<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AdamWeather Archive</title>
    <style>
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            background-color: #111;
        }
        /* This container shifts the iframe up to clip off the Wayback Machine banner */
        .archive-container {
            position: absolute;
            top: -55px; /* Adjust this value if the archive toolbar height changes */
            left: 0;
            width: 100%;
            height: calc(100% + 55px);
            border: none;
        }
    </style>
</head>
<body>

    <iframe src="https://web.archive.org/web/20260513210641/https://adamweather.info.gf/" class="archive-container"></iframe>

</body>
</html>
