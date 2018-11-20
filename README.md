<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Hello!</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <!-- import the webpage's stylesheet -->
    <link rel="stylesheet" href="/style.css">
    
    <!-- import the webpage's javascript file -->
    <script src="/script.js" defer></script>
    <style>
      section#home{
  margin-top: 50px;
}
section{
  border: 10px solid black;
  width: 100%;
  height: 600px;
  text-align: center;
}
nav{
  position: fixed;
  background-color: black;
  color: black;
  width: 100%;
  top: 0;
}
nav a{
  color: white;
}
nav ul > li{
  display: inline-block;
}
section > div{
  display: inline-block;
  height: 100%;
  border: 10px solid black;
  background-color: black;
  color: black;
  font-size: 100px;
}
section#about > div{
  width: 30%;
}
section#portfolio > div{
  width: 48%;
}
    </style>
  </head>  
  <body>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <section id="home">
      <h1>"A & R COLLECTION"</h1>
      <p>GET A CLASSIC DRESS FOR A COOL PRICE!</p>
    </section>
    <section id="about">
      <p>Hennes & Mauritz AB is a Swedish multinational clothing-retail company known for its fast-fashion clothing for men, women, teenagers and children. A%R and its associated companies operate in 62 countries with over 4,500 stores and as of 2015 employed around 132,000 people.!</p>
      <table>
        <tr>
        <th>Price / Item </th>
        <td>Foot </td>
        <td>Dresses </td>
        <td>Watches </td>
      </tr>
        <tr>
        <th>Minimum price</th>
        <td>10 000</td>
        <td>22 000</td>
        <td>12 000 </td>
      </tr>
        <tr>
        <th>Complex product</th>
        <td>20 000</td>
        <td>30 000</td>
        <td>50 000 </td>
      </tr>
      </table>
    </section>
    <section id="portfolio">
      <img src="http://imgs.su/tmp/2013-07-06/1373090772-600.jpg">
      <img src="http://img.gdeslon.ru/commodities/big/b69c/fcfa3edd542f80253c6973a7d04e.big.jpg">
      <img src="https://images.vcene.com/images/items/12404/type2/7995752.jpg">
    </section>
    <section id="contact">
      <a href="https://www.facebook.com/">CONTACT US ON FB!</a>
    </section>
  </body>
</html>
