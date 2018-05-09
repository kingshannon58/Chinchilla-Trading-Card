#Chinchilla-Trading-Card
This is the laughing project that I did in school. It was mainly for learning about borders and images.
The HTML code is below.

<html>

<head>
  <meta charset="utf-8">
  <title>Chinchillas are Awesome!</title>
  <link href="styles.css" rel="stylesheet">
</head>

<body>
  <div class="card">
    <div class="decorative">
      <div class="top">
        <div class="species">
          <class="animal-info">
            <h1>Chinchillas</h1>
            <!-- photo credit: pinterest -->
        </div>
        <div class="border">
          <img src="https://i.pinimg.com/236x/21/fc/04/21fc0409f61c91278a2e90ff5ded044b--choose-the-right-chinchillas.jpg" alt="chinchilla" border="3">
        </div>
      </div>
      <div class="bottom">
        <div id="card">
          <p class="#interesting-fact">They love taking dust baths instead of water baths.</p>
          <ul id="#facts">
            <li><span>Scientific Name</span>: Chinchilla Lanigera</li>
            <li><span>Average Size</span>: 25cm - 35cm</li>
            <li><span>Average Lifespan</span>: 10-18 years</li>
            <li><span>Favorite Food</span>: Fruit, Nuts, and Seeds</li>
          </ul>
          <p id="summary">Chinchilllas are medium sized rodents that are native to the Andes Mountains in South America. The reason that they are so rare is because they were hunted by the Chinchas, which wierdly enough, is how they were named. Chinchillas have a feature
            called "floating ribs." So, you can't exactly lift them like a hamster, under the belly. Their ribs are not fully attached to their spine and if enough pressure is applied upwards, the ribs could hurt some vital organs and kill the chinchilla.
            Basically, having a chinchilla isn't for the faint of heart. </p>
        </div>
      </div>
</body>

</html>


This is the CSS code below

/* add your CSS here */

/* The items in front of the brackets access the html elements in the panel to the left */
html {
  font-size: 12px;
}

ul {
  list-style-type: none;
}

span {
  font-weight: bold;
}

.card {
  
  background: #0e0e0e;
  border-radius: 5px; 
  box-shadow: 3px 3px 6px 1px rgba(0, 0, 0, 0.0);
  border: light black 3px;
  padding: 5px;
  width: 328px;
}

.decorative {
/*  I just learned about color gradients. That's how I got the background to go from red to yellow. Here's one place to find color gradients:
  https://www.w3schools.com/css/css3_gradients.asp*/
  background: white;
  border-radius: 4px;
  border: 1px black;
  box-shadow: 3px 3px 6px 1px rgba(0, 0, 0, 0.36);
  padding: 5px;
}

.top {}

.species {
  border: solid black 2px;
  border-radius: 4px;
  background-color: rgba(77, 51, 25, 0.3);
  /*   box-shadow: 3px 3px 6px 1px rgba(0, 0, 0, 0.36); */
  color: white;
  display: inline-block;
  padding: 11px;
  box-sizing: border-box;
  margin-left: 83px;
}

.top img {
  height: 300px;
  width: 300px;
  border-radius: 4px;
  box-shadow: 3px 3px 2px 0px rgba(0, 0, 0, 0.17);
  border: solid black 2px;
  margin: 5px;
}

.bottom {
  border: solid black 2px;
  border-radius: 5px;
  box-shadow: 3px 3px 2px 0px rgba(0, 0, 0, 0.17);
  padding: 2px;
  margin: 7px;
  color: white;
  background-color: rgba(77, 51, 25, 0.69);
}

.interesting_fact {
  font-style: italic;
}

.description {}

.info {}

h3.species {
  color: white;
  font-size: 20px;
  margin: 11px 0 0 78px;
  padding-top: 2px;
  text-align: center;
  /* width: 151px; */
  height: 26px;
  font-family: "papyrus";
}

.species h3 {
  font-size: 25px;
  font-family: "Papyrus";
  /* text-align: center; */
  display: inline-block;
  margin: 0 auto;
}
