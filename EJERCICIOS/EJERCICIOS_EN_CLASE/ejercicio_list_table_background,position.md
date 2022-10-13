# Clona la siguiente página

![image](https://user-images.githubusercontent.com/91554777/165874800-e4757824-1207-4357-9426-c956fe3abc55.png)

https://th.bing.com/th/id/R.7049f96a7ab04d4ffe56f6b7a180dd31?rik=KXuBl64z1lEW%2fw&riu=http%3a%2f%2fwww.solofondos.com%2fwp-content%2fuploads%2f2015%2f11%2fFondos-para-paginas-web-profesionales-3D.jpg&ehk=lWv3MXhrf5twGIElvqeFkf1879q3Y4fb8nZFCm8U5hQ%3d&risl=&pid=ImgRaw&r=0


    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    
    <body>
      <header>
            <p>LOGO</p>
            <nav>
              <ul>
                <li>MENU1</li>
                <li>MENU2</li>
                <li>MENU3</li>
              </ul>
            </nav>
              <h1>LANDING PAGE</h1>
              <p><img src="https://th.bing.com/th/id/R.d9fc4731a5ac9affe2511d0bdc3d3210?rik=%2fLtHkxv%2f%2fBsFuQ&pid=ImgRaw&r=0" alt="ADIP" style="width:70px;height:70px;margin-left:15px;">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia officiis repellat ab esse iste explicabo reprehenderit illo officia ullam nam autem, modi facere nobis, tempore labore ipsam laboriosam quod delectus itaque numquam? Vero fuga consectetur cum quaerat libero ad molestias. Dolores amet praesentium nisi nemo at non quidem et ab in! Sit repudiandae dolore expedita eos quod nemo libero voluptatem recusandae fugiat, molestias ipsum ad minima ratione inventore nostrum aliquid, ipsam reprehenderit voluptas magnam omnis error fugit deleniti! Blanditiis repellat explicabo, nemo tenetur ad ducimus saepe voluptate fuga rerum magnam ipsam ut odio amet voluptatibus architecto illum! Voluptatibus maxime fuga ad cupiditate porro incidunt dolores? Cum culpa illum qui labore sint quia molestiae id sunt veniam natus corrupti consequuntur quaerat laudantium,   </p>
      </header>
    </body>
    </html>

 # HTML

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Backgroung</title>
            <link rel="stylesheet" href="css/style.css">
        </head>
        <body>
            <header>
                <nav>
                    <p>Logo</p>
                    <ul>
                        <li>Menu 1</li>
                        <li>Menu 2</li>
                        <li>Menu 3</li>
                    </ul>
                </nav>
                <div class="caja">
                    <div class="cajita">
                        <h1>Landing Page</h1>
                        <p> 
                            <img src="img/mouse.png" alt="ADIP" style="width:70px;height:70px;margin-left:15px"> 
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis velit facilis numquam. Eum, quia pariatur! Nemo culpa possimus voluptas consectetur dolorem expedita inventore facilis sequi. Minima itaque iusto sed similique. Lorem ipsum dolor sit amet consectetur adipisicing elit. A iste nobis architecto quibusdam nisi tempora. Voluptates impedit, nisi explicabo architecto aperiam quod illo. Pariatur beatae a tempora inventore tenetur accusantium. Esse quaerat nulla animi culpa rem illum dicta laboriosam unde, autem at cupiditate quam reprehenderit praesentium consequatur adipisci repellendus quos.
                        </p>
                    </div>
                </div>
            </header>
        </body>
        </html>
        
# CSS        

        *{
            margin: 0;
            padding: 0;
        }
        body{
            background: url(../img/fondo.jpg);
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover ;
            width: 100%;
            height: 100vh;
        }

        nav{
            display: flex;
            justify-content: space-between;
        }
        ul{
            display: flex;    
        }
        li{
            list-style: none;
            background: linear-gradient(rgba(197, 15, 15, 0.4), rgba(110, 21, 194, 0.4)) ;
            padding: 15px;
            margin-right: 15px;
            border-radius: 30px;
            color: #FFF;
        }
        li:hover{
            background-color: #FFF;
            color: black;

        }
        .caja{
            width: 100%;
            height: 80vh;
            display: flex;
            align-items: flex-end;
            padding: 20px;
        }
        .cajita{
            background: linear-gradient(rgba(190, 65, 65, 0.514), rgba(110, 21, 194, 0.384)) ;
            width: 50%;
            border-bottom-left-radius: 30px;
            border-bottom-right-radius: 30px;
            border-top-left-radius: 30px;
            border-top-right-radius: 30px;
            padding: 20px;
            color: #FFF;
            text-shadow: 1px 1px 1px #FFF;
        }
