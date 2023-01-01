<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fjalla+One&display=swap">
</head>
<style>
    body{
        
        background: url('https://www.businessinsider.in/photo/68737328/apple-music-spotify-jiosaavn-gaana-subscription-price-in-india.jpg?imgsize=737340');
        background-size: cover;
        background-repeat: no-repeat;
        background-color: black;
        font-family: 'Fjalla One', sans-serif;
    }

    .logo img{
        opacity: 0.7;
        height: 120px;
        width: 350px;
        padding: 25px;
        margin-top: 50px;
        
    }
    .logo{
        display: flex;
        justify-content: center;
    }

    .container{
        width: 530px;
        height: 550px;
        
        display: flex;
        flex-direction: column;
        border-radius: 25px;
        align-items: center;
        margin: auto;
        background-color: rgba(0, 0, 0, 0.5);
    }

    input{
        padding: 35px;
        margin: 25px;
        width: 350px;
        height: 10px;
        background-color: rgba( 255,255,255, 0.5);
        border-radius: 50px;
        border: none;
        color: black;
        font-size: 18px;

    }
form ::placeholder{
    color: rgb(47, 46, 46);
}

    .name{
        margin-top: 40px;
    }
    h2{
        text-align: center;
        color: rgb(29, 29, 29);
    }

    button{
        width: 410px;
        height: 50px;
        padding: 0px;
        margin: 25px;
        border-radius: 25px;
        font-size: 22px;
        background-color: rgb(36, 214, 36);
        border: none;

    }

    .btn:hover{
        background-color: rgb(4, 141, 4);
        cursor: pointer;
    }

</style>
<body>
    <div class="logo">
        <i><img src="https://storage.googleapis.com/pr-newsroom-wp/1/2018/11/Spotify_Logo_RGB_White.png"  alt=""></i>
    </div>
    <h2>To continue, log in to spotify.</h2>
    <div class="container">
        <form action="nobackend.php">
            <div class="name">
                <input type="text" placeholder="User Name or Email address">
            </div>
            <div>
                <input type="password" placeholder="Password">
            </div>
            
        </form>
        <button class="btn">log in</button>
    </div>
</body>
</html>