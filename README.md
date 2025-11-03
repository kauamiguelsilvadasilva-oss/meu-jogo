# meu-jogo
<!DOCTYPE html> 
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale:1.0">
    <title>tela inicial</title>
    <style>
        .p {
            color:aquamarine     
        }     
        #a{
            z-index: 2;
            position: absolute;
            height: 50px;
            width: 200px;
            top: 300px;
            left: 800px;
            background-color: rgb(255, 0, 0);
        }    
        #b{
            z-index: 2;
            position: absolute;
            height: 50px;
            width: 200px;
            top: 350px;
            left: 800px;
            background-color: rgb(255, 0, 0);
        }     
        body {
            background-image: url(https://tse2.mm.bing.net/th/id/OIP.guBQb45caxjG8CqyMBhAGQHaEK?rs=1&pid=ImgDetMain&o=7&rm=3);
        }  
                                                            
    </style>                                         
    </head>
<body>
    <button id="a" onclick="iniciar()">iniciar</button>
    <button id="b" onclick="codigo()">código</button>

<script>
function iniciar(){
 window.location.href = "";
}
function codigo(){
 window.location.href = "http://127.0.0.1:3000/e:/gh.html?serverWindowId=a128e2f1-f5e6-40fd-82f9-c5040551a69b";
}
</script>


</body>
</html>
