<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FUCK LOVE</title>
    <style>
        body{
            margin: 0;
            padding: 0;
            height: 100dvh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #000d1e;
            .corazon{
                height: 150px;
                width: 150px;
                background: red;
                position: relative;
                transform: rotate(45deg);
                box-shadow: -20px 20px 150px #f20044;
                animation: palpitar 0.5s linear infinite alternate;
                &::before{
                    content: "";
                    position: absolute;
                    height: 150px;
                    width: 150px;
                    background: red;
                    right: 50%;
                    border-radius: 50%;
                    border-radius: 50%;
                    box-shadow: 20px 20px 150px #f20044;
                }
                &::after{
                    content: "";
                    position: absolute;
                    height: 150px;
                    width: 150px;
                    background: red;
                    top: -50%;
                    border-radius: 50%;
                    border-radius: 50%;
                    box-shadow: 20px 20px 150px #f20044;
                }
            }
            .contenido{
                position: fixed;
                margin-bottom: 50px;
                text-align: center;
                h1, h2{
                    color: white;
                }
            }
        }
        @keyframes palpitar {
            0%{transform: rotate(45deg) scale(1.10);}
            80%{transform: rotate(45deg) scale(1.0);}
            100%{transform: rotate(45deg) scale(0.8);}
        }
    </style>
</head>
<body>
    <div class="corazon"></div>
    <div class="contenido">
        <h1 class="title">SEXO</h1>
        <h1 class="title">ALCOHOL </h1>
        <h1 class="title">DROGA</h1>
    </div>
</body>
</html>
