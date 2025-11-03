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
function guessingGame(){

document.getElementById("guessing-game-form").addEventListener("submit", function(e) {
	e.preventDefault();

let computerGuessDisplay = document.getElementById("computer-guess");
let userGuessDisplay = document.getElementById("user-guess");
let userGuessInput = document.getElementById("user-guess-input");
let guessingGameMessage = document.getElementById("gameOutput");

let computerGuess = getRandomNumber (1,10);
let userGuess = parseInt(userGuessInput.value.trim());

computerGuessDisplay.innerHTML = computerGuess;
userGuessDisplay.innerHTML = userGuess;

if(computerGuess === userGuess){
  guessingGameMessage.innerHTML = "Congratulations!<br>You won!";
}else{
guessingGameMessage.innerHTML = "Try Again.";
}
});
}
```



• New Hope Kailua Website Redesign (Prototype)

Designed a test website for New Hope Kailua by refreshing its logo and brand style guide, aimed at streamlining the process for
prospective and current members to get connected.




• Dutch Bros Website Redesign (Prototype)

Conducted a heuristic evaluation on Dutch Bros’ official site and designed wireframes in Figma based on my findings. They showcased a minimalistic layout and a more intuitive navigation.
