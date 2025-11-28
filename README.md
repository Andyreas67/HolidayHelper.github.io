# HolidayHelper.github.io
Website to aid with selecting holiday destinations
test


<!DOCTYPE HTML>
<html>
<head>
<meta charset="utf-8">
<title>HolidayHelper</title>
<link rel ="stylesheet" href="Homepage.css">
</head>
<body>
<div id="big-bar">
  <h1 class="logo">
    <a href="index.html"><b>Holiday Helper</b></a>
  </h1>
  <ul class="navbar">
    <li><a href="China.html"><b>China</b></a></li>
    <li><a href="Sweden.html"><b>Sweden</b></a></li>
    <li><a href="Australia.html"><b>Australia</b></a></li>
    <li><a href="Portugal.html"><b>Portugal</b></a></li>
  </ul>
</div>
<section class="email">
  <h2 class="email-title">Discover new deals and travel inspiration every week</h2>
  <div class="email-text">
  <div class="email-images">
  <img src="beach.png" alt="beach">
  <div class="email-banner">Exclusive deals</div>
  <div class="socials">
    <a href="https://facebook.com"></a>
    <img src="facebook.png" alt="Facebook">
  </a>
  <a href="https://instagram.com">
    <img src="insta.png" alt="Instagram">
  </a>
  <a href="https://twitter.com">
    <img src="twitter.png" alt="Twitter">
  </a>
    </div>
    </div>

    <div class="email-form">
      <form>
        <label>Full name</label>
        <input type="text" name="name" required>

    <label>Email</label>
    <input type="text" name="email" required>
    <div class="check-box">
        <input type="checkbox" id="consent" required>
      <label for="consent">By submitting this form, I consent to receiving emails</label>
    </div>
    
    <button type="submit" class="subscribe-btn">Subscribe</button>
  </form>
</div>
</div>
</section>
<body>
</html>



body {
  margin:0px;
  background-color: #FBFBF8;
}
#big-bar{
position: sticky;
  top: 0;
  background-color: #2A3439;
  padding: 6px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  z-index: 9999;
}
#big-bar .logo a {
  color: white;
  text-decoration: none;
  font-family:Arial, Helvetica, sans-serif;
}
.navbar {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  gap: 20px;
  float:left;
}
.navbar a {
  color: white;
  text-decoration: none;
  padding: 10px 15px;
  font-size:30px;
}
.navbar a:hover {
  background-color: hsl(0, 0%, 10%);
}
.country-grid{
  position:static;
  display:grid;
  grid-gap:10px;
  grid-template-columns: 200px 200px;
  grid-template-rows: 600px 600px;
  margin-left:170px;
  margin-top:170px;
}
.email {
  width: 100%;
  max-width: 1000px;
  margin: 40px auto;
  padding: 40px 20px;
  font-family: Arial, Helvetica, sans-serif;
  box-sizing: border-box;
}
.email-title {
  text-align: center;
  margin-bottom: 30px;
  font-size: 25px;
}
.email-text {
  display: flex;
  gap: 40px;
  justify-content: center;
  align-items: flex-start;
  flex-wrap: wrap;
  max-width: 900px;
  width: 100%;
  margin: 0;
}

.email-images {
  flex: 1.2;
  max-width: 500px;
  position: relative;
}

.email-images img {
  width: 100%;
  border-radius: 12px;
  display: block;
}

.email-form {
  flex: 1;
  max-width: 400px;
  background: white;
  border: 1px solid grey;
  border-radius: 10px;
  padding: 20px;
  box-sizing: border-box;
}
.email-form input[type="text"]{
  margin-top: 18px;
  width: 100%;
  padding: 10px;
  border-width: 1px;
  border-style: solid;
  border-color: grey;
  border-radius: 10px;
  font-size: 15px;
}
.check-box{
  display: flex;
  align-items: flex-start;
  margin-top: 20px;
  font-size: 15px;
  gap: 10px;
}
.subscribe-btn{
  cursor: pointer;
  width: 100%;
  font-size: 15px;
  color: white;
  margin-top: 25px;
  padding: 14px;
  background: #ff2626;
  border: none;
  border-radius: 8px;
}
.subscribe-btn:hover{
  background: #660000;
}
.socials{
  display: flex;
  gap: 10px;
  margin-top: 15px;
}
.socials img{
  height: 30px;
  width: 30px;
  cursor: pointer;
  transition: 0.2s
}
.socials img:hover{
  transform: scale(1.15);
}
