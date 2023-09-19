# QR_CODE-Project
<!DOCTYPE html>

<html lang="en">
    <head>
        <meta charset="utf-8"/>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="styles.css"/>
        <title>QR Scan</title>
        <link rel="icon" href="favicon-32x32.png" type="favicon-32x32">
        body {
    background-color: #dce8f3;
    font-size: 15px;
    font-family: 'Outfit', sans-serif;
    font-weight: 400, 700;
    height: 100vh;
    align-items: center;
    justify-content: center;
    display: flex;
}

.container{

    background-color: #FFFFFF;
    width: 250px;
    height: 380px;
    border-radius: 10px;
    text-align: center;
    align-items: center;
}

.image-container{

    margin-top: 10px
}


.resized-image{
    width: 230px;
    height: 230px;
    align-items: center;
    border-radius: 10px; 
}
.body{
    margin-top: 10px;
    text-align: center;
    align-items: center;
    min-width: 10px;
    max-width: 206px;
    margin-left: 20px;
}

p{
    align-items: center;
    margin: 20 auto;
    text-align: center;
}

strong{
    font-size: 16px;
}

.close{
    margin-top: 10px;
    text-align: center;
    align-items: center;
    min-width: 10px;
    max-width: 206px;
    margin-left: 20px;
    font-size: 12px;
}

span{
    color: grey;
}

@media (max-width: 375px) {
    body {
      font-size: 14px;
      
    }
  }

  @media (min-width: 1441px) {
    body {
      font-size: 18px;
    }
    </head>
    <body>
        <div class="container">
            <div class="image-container">
                <a href="image-qr-code.png"><img src="image-qr-code.png" alt="qr code" class="resized-image"></a>
            </div>
            <div class="body">
                <p><strong>Improve your front-end skills by building projects</p></strong></p>
            </div>
            <div class="close">
                <p><span>Scan the QR code to visit frontend Mentor and take your coding skills to the next level</span></p>
            </div>
        </div>
        
    </body>
</html>
