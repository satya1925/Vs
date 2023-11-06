
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Website</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            font-family: serif;
        }

        video {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            width: 110%;
            height: 100%;
            z-index: -1;
        }

        .welcome-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: white;
            font-size: 100%;
            backdrop-filter: blur(1px);     
          background-color: rgba(0, 0, 0, 0.01);
             padding: 10px; 
             border-radius: 10px;
             border: solid 1px white;
             color: black;
             zoom: 150%;
        }
       .id
        {
            color: #002264;
            background-color: transparent;
            border:solid 1px black ;
            border-radius: 5px;
            font-size:90%;
        }
        h3 {
            color: #ff946a;
       font-family: 'Brush Script MT',cursive;
        }
    </style>
</head>
<body>
    <video autoplay muted loop>
        <source src="vs_1.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

  <a href="groom.html">  <div class="welcome-text">
        <h4>Wedding Invitation </h4>
        <h3>Sai ♡ lalitha</h3>
        <p>save date <br><b>19-25-1925</b></p>
        <p class="id">Enter</p>
    </div>
    </a>
</body>
</html>
