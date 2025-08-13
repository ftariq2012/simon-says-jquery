# Simon Says Game

A simple interactive "Simon Says" memory game built with HTML, CSS, JavaScript, and jQuery.
Players repeat a growing sequence of colours and sounds, testing their memory and speed.

## How to Play
Start the game by pressing any key.

Watch the sequence of colours that light up and listen to the sounds.

Repeat the sequence by clicking the colored buttons in the correct order.

Each round adds one new colour to the sequence.

If you press the wrong colour, the game ends, and you can restart by pressing any key again.

## Features
Four colored buttons (Red, Blue, Green, Yellow)

Distinct sound effects for each button

The sequence grows in difficulty each round

Visual button animations for better interactivity

"Game Over" effect with sound and background flash

## **Project Structure**
```
.
├── index.html        # Game layout
├── styles.css        # Game styling
├── game.js           # Game logic and event handling
├── sounds/           # Game audio files
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   ├── yellow.mp3
│   └── wrong.mp3
```

Technologies Used
HTML5 – Structure and game UI

CSS3 – Styling and animations

JavaScript (ES6) – Game logic

jQuery – DOM manipulation and event handling

## Getting Started
### 1. Clone the repository:
```
git clone https://github.com/ftariq1220/simon-says-jquery.git
cd simon-says-jquery
```

2. Open the game:
Simply open index.html in your web browser.

## Gameplay Preview
Green, Red, Yellow, and Blue buttons.

Each button plays a unique sound from the sounds/ folder.

The background flashes red when a wrong move is made.

## Sound Credits
All sounds are stored locally in the sounds/ directory:

red.mp3, blue.mp3, green.mp3, yellow.mp3 – Button sounds

wrong.mp3 – Game over sound
