<!DOCTYPE html>
<html lang="en">
<head><title>Chess game</title>
<style>
#flex,#flex1,#flex2,#flex3,#flex4,#flex5,#flex6,#flex7{
    display: flex;
    margin-left:10%;
    margin-right:10%;
}
#1,#2,#3,#4,#5,#6,#7,#8,#9,#10,#11,#12,#13,#14,#15,#16,#17,#18,#19,#20,#21,#22,#23,#24,#25,#26,#27,#28,#29,#30,#31,#32,#33,#34,#35,#36,#37,#38,#39,#40,#41,#42,#43,#44,#45,#46,#47,#48,#49,#50,#51,#52,#53,#54,#55,#56,#57,#58,#59,#60,#61,#62,#63,#64{
    position : absolute;}
.square{ height: 40px; width:40px;}
.black{ background-color: lightblue;}
.white{ background-color: white;}
</style>
</head>

<body>
<h1 style = "text-align:center;font-size:2em;"> WHITE</h1>

<div id = "flex">
<div class = "square black" id = "1"> <img src = "whiterook.jpg" height = "30" width= "20"> </div>
<div class = "square white" id = "2"><img src = "whiteknight.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "3"><img src = "whitebishop.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "4"><img src = "whitequeen.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "5"><img src = "whiteking.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "6"><img src = "whitebishop.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "7"><img src = "whiteknight.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "8"><img src = "whiterook.jpg" height = "30" width= "20"></div>
</div>

<div id = "flex1">
<div class = "square white" id = "9"> <img src = "whitepawn.jpg" height = "30" width= "20"> </div>
<div class = "square black" id = "10"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "11"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "12"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "13"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "14"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "15"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
<div class = "square black" id="16"><img src = "whitepawn.jpg" height = "30" width= "20"></div>
</div>

<div id = "flex2">
<div class = "square black" id = "17"> </div>
<div class = "square white" id = "18"> </div>
<div class = "square black" id = "19"> </div>
<div class = "square white" id = "20"> </div>
<div class = "square black" id = "21"> </div>
<div class = "square white" id = "22"> </div>
<div class = "square black" id = "23"> </div>
<div class = "square white" id = "24"> </div>
</div>

<div id = "flex3">
<div class = "square white" id= "25"> </div>
<div class = "square black" id = "26"> </div>
<div class = "square white" id = "27"> </div>
<div class = "square black" id = "28"> </div>
<div class = "square white" id = "29"> </div>
<div class = "square black" id = "30"> </div>
<div class = "square white" id = "31"> </div>
<div class = "square black" id = "32"> </div>
</div>

<div id="flex4">
<div class = "square black" id = "33"> </div>
<div class = "square white" id = "34"> </div>
<div class = "square black" id = "35"> </div>
<div class = "square white" id = "36"> </div>
<div class = "square black" id = "37"> </div>
<div class = "square white" id = "38"> </div>
<div class = "square black" id = "39"> </div>
<div class = "square white" id = "40"> </div>
</div>

<div id="flex5">
<div class = "square white" id= "41"> </div>
<div class = "square black" id = "42"> </div>
<div class = "square white" id = "43"> </div>
<div class = "square black" id = "44"> </div>
<div class = "square white" id = "45"> </div>
<div class = "square black" id = "46"> </div>
<div class = "square white" id = "47"> </div>
<div class = "square black" id = "48"> </div>
</div>

<div id="flex6">
<div class = "square black" id = "49"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square white" id = "50"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square black" id = "51"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square white" id = "52"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square black" id = "53"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square white" id = "54"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square black" id = "55"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
<div class = "square white" id = "56"> <img src = "blackpawn.jpg" height = "30" width= "20"> </div>
</div>

<div id="flex7">
<div class = "square white" id = "57"><img src = "blackrook.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "58"><img src = "blackknight.png" height = "30" width= "20"></div>
<div class = "square white" id = "59"><img src = "blackbishop.jpg" height = "30" width= "20"></div>
<div class = "square black" id = "60"><img src = "blackqueen.png" height = "30" width= "20"></div>
<div class = "square white" id = "61"><img src = "blackking.png" height = "30" width= "20"></div>
<div class = "square black" id = "62"><img src = "blackbishop.jpg" height = "30" width= "20"></div>
<div class = "square white" id = "63"><img src = "blackknight.png" height = "30" width= "20"></div>
<div class = "square black" id = "64"><img src = "blackrook.jpg" height = "30" width= "20"></div>
</div>

<h1 style = "text-align:center;font-size:2em;"> BLACK</h1>
</body>
</html>
