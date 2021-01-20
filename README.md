<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Add a gray background color with some padding */
body {
  font-family: Arial;
  padding: 20px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  font-size: 40px;
  text-align: center;
  background: white;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  padding-left: 20px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
   background-color: white;
   padding: 20px;
   margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
</style>
</head>
<body>

<div class="header">
  <h2>Get Started With Rockets!</h2>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>DIY water bottle alcohol rocket</h2>
      <h5>Jan 20 2021 last edited</h5>
      <img src="03eb43ce-a0b3-4c16-8d6b-a60568f49da9.png" alt="picture" style="width:500px;height:600px;">
      <p>rocketry is pretty hard to get into but with a bottle and alcohol, the sky is the limit! literally...</p>
    </div>
    <div class="card">step 2 to the world of rockets
      <h2>DIY rocket fuel without KNO3</h2>
      <h5></h5>
      <img src="d957230c-2442-42aa-b6cd-1337347019d1.png" alt="picture">
      <p>this solid rocket fuel is a combo of match heads and sugar.</p>
    </div>
  </div>
  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <img src="kerbaldigitalart.jpg" alt="picture">
      <p>i love rockets or anything that flys really</p>
    </div>
    <div class="card">
      <h3>check out my blogs</h3>
      <div class="fakeimg">HardWareBear.blogspot.com</div><br>
      <div class="fakeimg">pycommunity30.github.io</div><br>
    </div>
    <div class="card">
      <h3>my contacts</h3>
      <p>jerrbearis2cool@gmail.com</p>
    </div>
  </div>
</div>

<div class="future AD">
  <h2>Footer</h2>
</div>

</body>
</html>

