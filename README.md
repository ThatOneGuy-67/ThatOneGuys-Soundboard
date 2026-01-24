ThatOneGuy's Soundboard

A customizable web soundboard featuring a sleek dark glass theme, interactive buttons, favorites, search, and a start page overlay. Perfect for quickly playing sound effects with style.

Features

Glass-style dark theme matching your aesthetic.

Start page overlay with “Enter” button.

Interactive sound buttons with press animations.

Favorites toggle to show favorite sounds.

Overlap toggle to allow multiple sounds at once.

Stop all sounds button.

Search bar to quickly filter sounds.

Easy to add your own sounds.

Demo

You can preview the soundboard locally by opening index.html in a modern web browser.

Installation

Clone the repository

git clone https://github.com/YourUsername/soundboard.git


Open index.html in a browser (Chrome, Firefox, or Edge recommended).

Optional: Customize sounds by editing sounds.js:

export const sounds = [
  { name: 'Laugh', url: 'sounds/laugh.mp3', color: '#ff5555' },
  { name: 'Clap', url: 'sounds/clap.mp3', color: '#55ff55' }
];

Usage

Click Enter on the start page to show the soundboard.

Click any sound button to play the sound.

Use Stop All Sounds to immediately stop everything.

Use the Favorites toggle to filter favorite sounds.

Use the Search bar to find sounds by name.

Customization

Theme: Change the glass color by editing #startpage or .sound-button-img in the CSS.

Button colors: Set individual button colors in sounds.js via the color property.

Add sounds: Place audio files in a folder and add entries in sounds.js.

Contributing

Fork the repository.

Create a new branch for your feature.

Submit a pull request with a description of your changes.

License

This project is open-source. You can modify and distribute it freely.

Credits

Background image: Pixabay

Sound button images: jsDelivr / GitHub
