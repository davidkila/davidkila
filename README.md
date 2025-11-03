## Hey, I’m David Kila! 🤠


## A Bit About Me 🤙🏽

I’m currently a senior at Arizona State studying graphic web design, interested in brand strategy and app development. I
also intend to begin a Master’s in Computer Science at Georgia Tech in the spring of 2027.


## Tech Toolbox 🔧

• Languages:
HTML (Intermediate), CSS (Intermediate), JavaScript (Beginner), Java (Beginner)

• Software Tools:
Illustrator (Intermediate), Canva (Intermediate), InDesigner (Beginner), Figma (Beginner)

• Libraries:
JQuery (Beginner)


## Favorite Projects 🔧

• Disneyland, in Action! Webpage Design (Prototype)

Developed front-end and back-end of a test Disneyland webpage with functionalities including a light/dark mode, photo carousel,
calendar picker and submission form.
```py
document.addEventListener("DOMContentLoaded", function () {
const productButtons = document.getElementsByClassName("product-button");
const productBlocks = document.querySelectorAll("#product-display > .product");

for (let i = 0; i < productButtons.length; i++) {
		productButtons[i].addEventListener("click", function () {
			const productId = productButtons[i].getAttribute("data-product");

for (let j = 0; j < productBlocks.length; j++) {
	productBlocks[j].classList.remove("currentItem");
	productBlocks[j].classList.add("hiddenItem");
}

const chosenProduct = document.getElementById(productId);
if (chosenProduct) {
chosenProduct.classList.remove("hiddenItem");
chosenProduct.classList.add("currentItem");
}
});
}
});
```

```
        <!-- ~~~~~~~~~~ TWITTER CARD TAGS ~~~~~~~~~~ -->
        <meta name="twitter:card" content="summary_large_image">
        <meta name="twitter:site" content="@wunderlusttravel">
        <meta name="twitter:creator" content="@wunderlusttravel">
        <meta name="twitter:title" content="Wunderlust Travel: Majorca">
        <meta name="twitter:description" content="Let Wunderlust Travel take you to beautiful Majorca this year! Majorca is a beautiful island and offers beauty and fun to its visitors">
        <meta name="twitter:image" content="https://wunderlusttravel.com/images/majorca-cove.png">

        <!-- ~~~~~~~~~~ OPEN GRAPH META TAGS ~~~~~~~~~~ -->
        <meta property="og:title" content="See Majorca with Wunderlust Travel">
        <meta property="og:type" content="website">
        <meta property="og:image" content="https://wunderlusttravel.com/images/majorca-cove.png">
        <meta property="og:url" content="https://wunderlusttravel.com/majorca">
        <meta property="og:description" content="Let Wunderlust Travel take you to beautiful Majorca this year! Majorca is a beautiful island and offers beauty and fun to its visitors">
        <!-- ~~~~~~~~~~FAVICON ~~~~~~~~~~ -->
        <link rel="shortcut icon" href="images/favicon.png">
```

• New Hope Kailua Website Redesign (Prototype)

Designed a test website for New Hope Kailua by refreshing its logo and brand style guide, aimed at streamlining the process for
prospective and current members to get connected.
```
/* --------------- MEDIA QUERY (medium) ----------------- */
@media screen and (min-width:880px) {
body {
  min-width:880px;
}

header {
  text-align:left;
  padding-left:10px;
}

#gallery {
  text-align:center;
  display:grid;
  grid-template-columns:repeat(2,1fr);
}

section:nth-child(even) :is(h2, p) {
  grid-column:1/-1;
}

figure:nth-last-child(-n+2) img {
  margin-bottom:-3.40em;
}
  
figure:nth-last-child(-n+2) figcaption {
  bottom:14.10em;
}
```




• Dutch Bros Website Redesign (Prototype)

Conducted a heuristic evaluation on Dutch Bros’ official site and designed wireframes in Figma based on my findings. They showcased a minimalistic layout and a more intuitive navigation.
