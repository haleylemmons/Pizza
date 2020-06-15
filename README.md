# Pizza
Simple HTML/CSS Web Page Demo
![pizza](https://user-images.githubusercontent.com/43729979/84615721-fd7e8780-ae86-11ea-9a1a-d1d0f2c5460b.jpg)
 <div class="textContainer">
    <h1>Pizza!</h1>
    <p>My Favorite Toppings: </p>
    <ul>
      <li>Pepperoni</li>
      <li>Mozzarella Cheese</li>
      <li>Mushrooms</li>
    </ul>
  </div>

  

/* 
	STYLE.CSS:
	One stylesheet to rule them all.
	
	selector { property:value }
	
*/

@import url(https://fonts.googleapis.com/css?family=Fredericka+the+Great|Lato);

body {
  background-color: #5f5345;
}
 
.pageContainer {
  width: 940px;
  margin: 20px auto 0 auto;
  padding: 20px;
  background-color: #fff;
}
 
.imageContainer {
  float: left;
  width: 620px;
}
 
.textContainer {
  float: left;
  width: 300px;
  margin-left: 20px;
  margin-top: 20px;
}

img {
  width: 100%;
}
 
h1 {
  font-family: 'Fredericka the Great', cursive;
  font-size: 64px;
  color: #8b1b00;
}
 
p, li {
  font-family: 'Lato', sans-serif;
  font-size: 22px;
  color: #51473b;
}




/* ---- Advanced ---- */
/* This tag is a bit advanced for this lesson,  
   but is needed to wrap the pageContainer 
   around any sized content that is floated within it. */

.pageContainer:after { 
  content: " ";
  display: table;
  clear: both;
}
 
