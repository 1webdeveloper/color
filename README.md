<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="5th.css">
</head>
<body>

  <div class="blankbox">

    <div style="color: rgb(255, 11, 51);"></div>
    <div style="color: orangered;"></div>
    <div style="color: yellow;"></div>
    <div style="color: green;"></div>
    <div style="color: blue;"></div>
    <div style="color: purple;"></div>
    
</div>
</body>
</html>


css
.blankbox{
    width: 300px;
    height: 100px;
    display: flex;
}
.blankbox div:nth-of-type(1) {flex-grow: 1;}
.blankbox div:nth-of-type(2) {flex-grow: 1;}
.blankbox div:nth-of-type(3) {flex-grow: 2;}
.blankbox div:nth-of-type(4) {flex-grow: 1;}
.blankbox div:nth-of-type(5) {flex-grow: 3;}
.blankbox div:nth-of-type(6) {flex-grow: 1;}


