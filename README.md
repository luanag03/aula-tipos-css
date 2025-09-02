# aula-tipos-css

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aula CSS - 1</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>

.card {

    width:500px;
    height: fit-content;
     background-color: aliceblue;
     border-radius: 25px;
      border: solid 1px rgb(36, 36, 141);
       margin: 20px; padding: 40px;

}
.container_img {

    width: 100px;
     height: 100px;
      border-radius: 50%;
       margin-bottom:  40px;


}

 

   




</style>
<body>

    <div class = "card">

        <div class="container_img" >
            <img style="width: 100%;  height: 100%; margin-top: 20px;" src="https://cdn-icons-png.flaticon.com/512/706/706830.png" alt="">
        </div>

        <div>
            <h1 style="font-family: Arial, Helvetica, sans-serif; font-size: 30px;">
                Meu nome é: <span style="color: rgb(36, 36, 141);">Adriana</span>
            </h1>

            <p style="font-family: Arial, Helvetica, sans-serif; font-size: 15px;">
                <span style="color: rgb(36, 36, 141); font-style: italic;">Mensagem: "A vida não é um morango! E tá tudo bem!"</span>
            </p>
        </div>
    </div>

    <div style="width:500px; height: fit-content; background-color: aliceblue; border-radius: 25px; border: solid 1px rgb(36, 36, 141); margin: 20px; padding: 40px;">

        <div style="width: 100px; height: 100px; border-radius: 50%; margin-bottom:  40px;">
            <img style="width: 100%;  height: 100%; margin-top: 20px;" src="https://cdn-icons-png.flaticon.com/256/3681/3681928.png" alt="">
        </div>

        <div>
            <h1 style="font-family: Arial, Helvetica, sans-serif; font-size: 30px;">
                Meu nome é:<span style="color: rgb(36, 36, 141);">Hugo</span>
            </h1>
            <p style="font-family: Arial, Helvetica, sans-serif; font-size: 15px;">
                <span style="color: rgb(36, 36, 141); font-style: italic;">Mensagem: "Um dia é da caça, o outro é do caçador".</span>
            </p>

        </div>
    </div>

</body>

</html>
