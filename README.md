<!DOCTYPE html>
<html>
<head>

<style>

body {
margin: 0;
}

.header {
background-color: #f1f1f1;
background-image: url(banner2.webp);
background-repeat: no-repeat;
background-size: cover;
height: 510px;
}

#navbar {
overflow: hidden;
background-color: #000000;
position: fixed;
width: 100%;
font-size: 28px;
font-family: Arial, Helvetica, sans-serif;
}

#navbar a {
float: right;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
font-size: 17px;
}

#navlist a:hover {
background-color: #ddd;
color: black;
}

#navbar a.active {
background-image: linear-gradient(to right top, #00f4ff, #00c9ff, #0099ff, #0063fe, #0800c9);
color: white;
}

#Logo {
margin-top: -15px;
margin-left: -10px;
float: left;
}

#NowShowing {
text-align: center;
height: 25px;
padding-top: 18px;
font-size: 28px;
font-family: Arial, Helvetica, sans-serif;
}

img {
padding: 5px;
border-radius: 0.8em;
}

#Promotions {
text-align: center;
height: 25px;
padding-top: 18px;
font-size: 28px;
font-family: Arial, Helvetica, sans-serif;
}


.content {
padding: 15px;
font-size: 20px;
}

.footer{
text-align: center;
background-color: #000000;
height: 80px;
}

.footer ul {list-style-type: none; padding-top: 20px;}
.footer ul li {display: inline-block;}
.footer ul li a {text-decoration: none; padding: 25px; color: #f2f2f2; font-size: 17px;}

.footer a:hover {
background-color: #ddd;
color: black;
}

@media (max-width: 500px) {
.header{
  width: 100%;
}
}

</style>
</head>
<body>

<div class="header">
<header>
    
<div id="navbar">
  <nav>
    <div id="navlist">
      <a href="FeedbackPage.html">Feedback</a>
      <a href="UpcomingPage.html">Upcoming</a>
      <a href="MoviesPage.html">Movies</a>
      <a href="Cat-HorrorPage.html">Category</a>
      <a class="active" href="index.html">Home</a>
    </div>

    <div id="Logo">
      <a href="index.html"><img src="Logo1.png" alt="Logo" height="40px" width="100px"></a> 
    </div>

  </nav>
</div>

</header>
</div>

<hr>

<div id="NowShowing">
  Now Showing
</div>

<div class="content">
  <table>
    <tr>
      <td>
        <div class="movie">
          <a href="m1_description.html"><img src="m1.jpg" alt="movie1"></a>
          <a href="m1_description.html">Warming Up To You</a> 
      </td>   
      <td>
          <a href="m2_description.html"><img src="m2.jpg" alt="movie2"></a>
          <a href="m2_description.html">Doctor Strange</a> 
      </td>
      <td>
          <a href="m3_description.html"><img src="m3.jpg" alt="movie3"></a>
          <a href="m3_description.html">Dragon Knight</a> 
      </td>
      <td>
          <a href="m4_description.html"><img src="m4.jpg" alt="movie4"></a>
          <a href="m4_description.html">The Bunker Game</a> 
      </td>
      <td>
          <a href="m5_description.html"><img src="m5.jpg" alt="movie5"></a>
          <a href="m5_description.html">Morbius</a>
        </div>
      </td>
    </tr>
  </table>
</div>

<div id="Promotions">
 Promotions
</div>

<div class="content">
<table>
  <tr>
    <td>
      <div class="movie"> 
        <a href="m6_description.html"><img src="m11.jpg" alt="movie11"></a>
        <a href="m6_description.html">Graves</a> 
    </td>
    <td>
        <a href="m7_description.html"><img src="m12.jpg" alt="movie12"></a>
        <a href="m7_description.html">9 Bullets</a> 
    </td>
    <td>
        <a href="m8_description.html"><img src="m13.jpg" alt="movie13"></a>
        <a href="m8_description.html">Agent Game</a> 
    </td>
    <td>
        <a href="m9_description.html"><img src="m14.jpg" alt="movie14"></a>
        <a href="m9_description.html">Jurassic Island</a>
    </td>
    <td>
        <a href="m10_description.html"><img src="m15.jpg" alt="movie15"></a>
        <a href="m10_description.html">Yaksha: Ruthless Operations</a> 
      </div>
    </td>
  </tr>
</table>
</div>

<div class="footer">
<footer>
  <ul>
  <li><a href="AboutUsPage.html">About Us</a></li>
  <li><a href="ContactInfoPage.html">Contact Info</a></li>
  </ul>
</footer>
</div>

</body>
</html>

