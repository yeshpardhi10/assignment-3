<html>
<head>
    <script>
        function hello() {
            
            var u = document.getElementById("fname");
            alert (" Your Password is " + u.value);
            

        }
        function myFunction(){
            var x = document.getElementById("fname");
            x.value = x.value.toUpperCase();
        }
        function hov()
        {
            var e = document.getElementById('hover');
            e.style = "background-color: rgb(255, 0, 255);height: 30px; width: 100px;"; //e.style.display = 'none';
            
        }
        function hove()
        {
            var e = document.getElementById('hover');
           e.style = "background-color: rgb(0, 4, 255);height: 30px; width: 100px;"; 
        }
</script>
</head>
<body background="Colaba1.jpg" style="color: rgb(0, 0, 0); font-size: large; font-family: 'Times New Roman', Times, serif;" >
    
    <h1 style="text-align: center;">Welcome to the souled store </h1> <br> <p style="color: rgb(0, 0, 0);">Enter your name: <input type = "text" id = "pname" onkeyup="myFunction()"></p>
    <p style="color: red;">Enter your Password: <input type = "password" id = "fname" onkeyup="myFunction()">
    <button type = "button" onclick="hello()"> Click to view your entered Password  </button></p>
    <p style="color: red;">Enter your birth date
    <input type="date" id="datee"> </p>
    <h3 style="color: rgb(129, 247, 174);">Select your merchandise
    <select name = "option">
        <option value = "aa"> T-Shirts</option>
        <option value = "bb"> Sweatshirts</option>
        <option value = "cc"> Joggers</option>
        <option value = "dd"> Slippers</option>
        <option value = "ee"> Hoodies</option></select></h3>
    <h3 style="background-color: red; text-align: center;">Click on photo to view real website</h3>
    <button type = "button"  onclick="location.href = 'https://www.thesouledstore.com/'"> <img src="download (1).png"  alt="Website" height="500px" width="750px">  </button>
    <div id = "hover" onmouseover="hov()" onmouseleave="hove()" style = "background-color: rgb(0, 4, 255);height: 50px; width: 100px;";> <p style="text-align: center; text-anchor: middle; color: rgb(9, 255, 0);"><a href="https://www.thesouledstore.com/men/t-shirts#" style="color: black;"> New collection!!</a></p></div> <br><br>
    <hr>
    <h2>FOLLOW US ON</h2>
    <button type = "button" onclick="location.href = 'https://www.instagram.com/accounts/login/?next=/thesouledstore/'"> <img src="94409a775c02d7658dd6e7ba88429b63.jpg" alt="Website" height="50px" width="50px">  </button>
    <button type = "button" onclick="location.href = 'https://www.facebook.com/souledstore/'"> <img src="fb_icon_325x325.png" alt="Website" height="50px" width="50px">  </button>
    <button type = "button" onclick="location.href = 'https://twitter.com/thesouledstore?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor'"> <img src="download.png" height="50px" width="50px">  </button>
    <button type = "button" onclick="location.href = 'https://in.pinterest.com/pin/442760207105347403/'"> <img src="Pinterestlogo.png"; alt="Website" height="50px" width="50px">  </button>
    
</body>
</html>
