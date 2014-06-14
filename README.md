<!doctype html>
<html>
    <head>
        <title>Flappy Bird</title>
        <meta name="viewport" content="width=device-width, user-scalable=no">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="apple-touch-icon" href="assets/icon.png">
        <link rel="apple-touch-icon" sizes="120x120" href="assets/icon-120.png">
        <style>
            body {
                background: #abc;
                margin: 0;
                padding: 0;
            }
            #screen {
                margin: 0 auto;
                max-height:500px;
                max-width:500px;
                position: relative;
                overflow: hidden;
                
            }
            </style>
        </style>
    </head>
    <body>
        <div id="screen"></div>
        <script src="phaser.min.js"></script>
        <script src="main.js"></script>
    </body>
</html>
