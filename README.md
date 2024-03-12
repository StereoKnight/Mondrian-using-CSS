# Mondrian-using-CSS
Below is the code for Mondrain style Painting using HTML and CSS.

HTML:  

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mondrian Project</title>
  <style>
   body{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
    padding: 0;
   }
   .painting{
    display: grid;
    height: 748px;
    width: 748px;
    background-color: black;
    grid-template-columns: 320px 198px 153px 50px;
    grid-template-rows: 414px 130px 155px 20px;
    gap: 9px;
   }
   .item{
    background-color: #F0F1EC;
   }
   .red{
    background-color: red;
   }
   .white1{
    grid-column: span 3;
   }
   .white2{
    grid-row: span 2;
   }
   .white3{
    grid-area: 2 / 2 / 4 / 4;
   }
   .blue{
    background-color: #004592;
    border-bottom: 10px solid black;
   }
   .yellow{
    background-color: yellow;
   }
   .black{
    background-color: black;
   }

  </style>
</head>

<body>
  <!-- Write your HTML here -->
  <div class="painting">
    <div class="item red"></div>
    <div class="item white1"></div>
    <div class="item white2"></div>
    <div class="item white3"></div>
    <div class="item blue"></div>
    <div class="item white4"></div>
    <div class="item"></div>
    <div class="item yellow"></div>
    <div class="item black"></div>
  </div>
</body>

</html>
