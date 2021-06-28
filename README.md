<!-- # css-grid
this is code on css grid -->
<!--

                    CSS GRID

-->

<html>
    <head>
        <title>
            css grid
        </title>
        <style>
        .container{
            display: grid;
            /*grid-template-columns:300px 300px auto;*/
            /*grid-template-columns: 300px 400px 500px;*/
            
            /*it will devide colums in three equal part*/
            /*grid-template-columns: 1fr 1fr 1fr;*/
            
            grid-template-columns: repeat(4,auto);
            
            
            grid-gap: 2rem;
        }
        .box{
            background-color: red;
            border: 2px solid black;
            /*margin: 3px;*/
            padding: 16px 9px;
        }
            
        </style>
    </head>
<body>
<!--<h1>Hello World</h1>-->
<div class="container">
    <div class="box"> box1</div>
    <div class="box"> box2</div>
    <div class="box"> box3</div>
    <div class="box"> box4</div>
    <div class="box"> box5</div>
    <div class="box"> box6</div>
    <div class="box"> box7</div>
    <div class="box"> box8</div>
    <div class="box"> box9</div>
    <div class="box"> box10</div>
    <div class="box"> box11</div>
    
</div>
</body>
</html>
