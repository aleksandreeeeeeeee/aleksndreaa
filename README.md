<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
    <title>Frontend Mentor</title>
    <style>
         body {
            background-color: hsl(220, 15%, 55%);
         }
            .child-container {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            position: relative;
            word-wrap: initial;
            background-color: hsl(0, 0%, 100%);
            border: 1px solid white;
            margin: 10% auto 0 auto;
            border-radius: 13px;
            padding: 10px;
            box-sizing: border-box;
            box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        }
            img {
            display: inline-block;
            position: relative;
            max-width: 100%;
            height: auto;
            box-sizing: border-box;
            object-fit: cover;
            border-radius: 13px;
            margin: 0 auto;
           }
            .child-container h1 {
            display: inline-block;
            box-sizing: border-box;
            font-size: 20px;
            font-family: "Outfit", sans-serif;
            font-optical-sizing: auto;
            font-weight: bold;
            font-style: normal;
            padding: 20px;
        }
            p {
            display: inline-block;
            margin-top: -40px;
            box-sizing: border-box;
            font-size: 15px;
            font-family: "Outfit", sans-serif;
            font-optical-sizing: auto;
            font-style: normal;
            padding: 15px;
            opacity: 0.7;
        }
             @media (min-width:375px) {
                .child-container {
                width: 290px;
                }
             }
    </style>
</head>
<body>
    <div class="child-container">
        <img src="https://www.frontendmentor.io/solutions/frontend-mentor-JcBa9Ku6Lu" alt="QR code">
        <h1>Improve your front-end skills by building projects</h1>
        <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
</body>
</html>
