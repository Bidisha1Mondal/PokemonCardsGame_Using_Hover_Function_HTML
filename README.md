# Pokemon Cards Game Using HTML:

###HTML Code:-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pokemon Cards</title>
    <link rel="stylesheet"href="style.css">
    
</head>
<body>
    <div id="main">
        <div id="card1" class="card">
            <img src= "https://images.unsplash.com/photo-1638964758061-117853a20865?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MzN8fHBva2Vtb24lMjBjYXJ0b29uc3xlbnwwfHwwfHx8MA%3D%3D"></div>
        <div id="card2"class="card">
            <img src="https://images.unsplash.com/photo-1609372332255-611485350f25?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTZ8fHBva2Vtb24lMjBjYXJ0b29uc3xlbnwwfHwwfHx8MA%3D%3D"></div>
        <div id="card3"class="card">
            <img src="https://images.unsplash.com/photo-1529143732233-da7fb74682a3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cG9rZW1vbiUyMGNhcnRvb25zfGVufDB8fDB8fHww"></div> 
        <div id="card4"class="card">
            <img src="https://images.unsplash.com/photo-1678736424903-a80e2c7f9d31?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTF8fHBva2Vtb24lMjBjYXJ0b29uc3xlbnwwfHwwfHx8MA%3D%3D">
        </div>
    </div>
</body>
</html>

###CSS Code:-

*{
    margin:0%;
    padding:0%; 
    box-sizing:border-box; 
} 
html,body{
    height: 100%;
    width:100%;

}
#main{
    height: 100%;
    width:100%; 
    background-color: rgba(238, 51, 26, 0.832); 
    border:2px solid red;
}
.card{ 
    position: absolute; 
    top:50%;
    left:50%;
    height:300px;
    width:230px;
    border:1px solid black;
    border-radius:20px;
    overflow: hidden;
}


#card1{
    z-index: 4;
    transform:translate(-50%,-50%); 
    background-color:aqua ;

}
#card2{
    z-index: 3;
    transform:translate(-50%,-50%)rotate(-8deg);
    background-color: blue;

}
#card3{
    z-index:2;
    transform:translate(-50%,-50%)rotate(-16deg);
    background-color: crimson;

}
#card4{
    z-index:1;
    transform:translate(-50%,-50%)rotate(-24deg);
    background-color: darkgreen;

}
img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
#card2:hover{
        z-index: 50;
    }
        
#card3:hover{
            z-index: 50;
    }
#card4:hover{
                z-index: 50;
 }

    






