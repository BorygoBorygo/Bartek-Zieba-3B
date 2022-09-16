# Bartek-Zieba-3B
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
  <link rel="stylesheet" href="style.css">
    

</head>
<body>
   
<section class="banner">
    <div class="item">
        <img src="screen.jpg" alt="">

        <div class="wrapper">
            <p class="number">01/</p>
         <div class="number">
             <div class="box">
                 <p class="text>">
                 Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis commodi itaque deserunt ad non. Et dolorem, maxime hic ipsam animi voluptatum rerum quia quisquam eligendi illum consequuntur, nihil sunt eius.
                 </p>
                 <a href="" class="link">Learn more</a>
             </div>
         </div>

        </div>
    </div>


    <div class="item">
        <img src="screen.jpg" alt="">

        <div class="wrapper">
            <p class="number">02/</p>
         <div class="number">
             <div class="box">
                 <p class="text>">
                 Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis commodi itaque deserunt ad non. Et dolorem, maxime hic ipsam animi voluptatum rerum quia quisquam eligendi illum consequuntur, nihil sunt eius.
                 </p>
                 <a href="" class="link">Learn more</a>
             </div>
         </div>

        </div>
    </div>


    <div class="item">
        <img src="screen.jpg" alt="">

        <div class="wrapper">
            <p class="number">03/</p>
         <div class="number">
             <div class="box">
                 <p class="text>">
                 Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis commodi itaque deserunt ad non. Et dolorem, maxime hic ipsam animi voluptatum rerum quia quisquam eligendi illum consequuntur, nihil sunt eius.
                 </p>
                 <a href="" class="link">Learn more</a>
             </div>
         </div>

        </div>
    </div>
</section>


</body>
</html>


*{
    margin: 0;
    padding: 0;
}

img{
    width: 100%;
    height: 300px;
    object-fit: cover;
}
.banner{
    position: relative;
    display: flex;
    justify-content: space-evenly;
    padding: 30px 0;
    background-color: black;
    color: white;
}

.item{
    position: relative;
    width: 400px;
    z-index: 1;
}
.wrapper{
    display: flex;
}
.number{
    margin-right: 20px;
    font-size: 2rem;

}

.link{
    text-transform: uppercase;
    color: white;
    ;
}
.banner::before{
    content: '';
    position: absolute;
    top: 0;
   left: 0;
   width: 100%;
   height: 50%;
   background-color: gainsboro;


}
