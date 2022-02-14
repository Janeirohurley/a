# a
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    <style>
    *{
    margin:0;
    padding:0;
    box-sizing:border-box;
    }
        @font-face {
 font-family: "Open Sans";
 src: url("/fonts/OpenSans-Regular-webfont.woff2") format("woff2"),
        url("/fonts/OpenSans-Regular-webfont.woff") format("woff");
        }
body{
position: absolute;
left: 50%;
transform: translate(-50%,-50%);
top: 50%;
}
.container{
    width: 17em;
    height: 25em;
    border: 2px solid transparent;
    box-shadow:2px 2px 5px #ebd2d2,-2px 2px 5px  #ebd2d2,2px -2px 5px  #ebd2d2,2px 2px 5px #ebd2d2,-2px 2px 5px  #ebd2d2,2px -2px 5px  #fff,2px 2px 5px #fff,-2px 2px 5px  #fff,2px -2px 5px  #fff,2px 2px 5px #aca4a4,-2px 2px 5px  #aca4a4,2px -2px 5px  #aca4a4;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 10px;
    background-color:rgb(250, 250, 250);
}
h1{
    text-indent: 15px;
    font-size:20px;
    position: absolute;
    top: 10%;
    outline: none;
}
input[type="button"]{
  transform: translate(118%);
  outline: none;
  border: 2px solid transparent;
  box-shadow:1px 1px 2px #c9c9c0,-1px 1px 2px #c9c9c0,1px -1px 2px #c9c9c0;
  background: transparent;
  cursor: pointer;
  transition:0.9s;
  color:rgba(000, 000,000, 0.5);
  text-align: center;
  font-weight:bold;
}
input[type="button"]:active{
    background-color:rgb(218, 240, 238);
      opacity: 0.5;
      color:#fff;
    transition:0.3s;
    border-radius: 5px;
    
}
input[type="text"]{
    border-radius: px;
 font-size: small;
 background: transparent;
  outline: none;
  border: 2px solid transparent;
  box-shadow:1px 1px 2px #c9c9c0,-1px 1px 2px #c9c9c0,1px -1px 2px #c9c9c0;

}
input[type="password"]{
    
 font-size: small;
 font-size: small;
 border-radius: px;
 background: transparent;
  outline: none;
  border: 2px solid transparent;
  box-shadow:1px 1px 2px #c9c9c0,-1px 1px 2px #c9c9c0,1px -1px 2px #c9c9c0;
  outline: none;
}
.mdp{
    color: black;
    text-decoration: none;
    position: relative;
    left: -29px;
}
.mdp:active{
color: #f5cf96;
text-decoration:underline  ;
}
.ctc{
    font-weight: bold;
}
footer{
position: fixed;
    top: 380px;
    left: 120px;
}
sub{
    font-family: "Open Sans";
    font-size: small;
    font-style: oblique;
    color: red;
}
    </style>
    <title>login to </title>
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    
</head>
<body>
    
    <div class="container">

        <h1>welcome to janeiro</h1>
        <form action="j.php" method="get">
        <input type="text" placeholder="Enter ur name" name="nom " id="m" onFocus="my()">
        <br>
        <br>
        <input type="password" placeholder="Enter ur password" name="pwd"> 
        <br>
        <br>
        <input type="button" value="Login">
        <br>
        <p>  <a href="mailto:janeirohurley@gmail.com" class="mdp">Mot passe oublie</a></p>
      <center><div class="ctc"><a href="registration from janeiro.html" target="_blank">Create ur account</div></a></center>
      
      <footer>&copy;2022<sub>design by janeiro</sub></footer>
      <i class="fas fa-band-aid"></i>
       </form>
       
    </div>
    
</body>
<script type="text/javascript">
function my(){
var d=getElementById("m").style.background="red";

}

</script>
</html>
