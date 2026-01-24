ThatOneGuy's Soundboard 🎵

A sleek, glass-themed web soundboard with interactive buttons, search, favorites, and a stylish dark aesthetic. Perfect for playing sound effects quickly and easily.

⚡ Features

Glass-style dark theme with blur effects.

Start page overlay with an “Enter” button.

Interactive sound buttons with press animations.

Favorites toggle to show only favorite sounds.

Overlap toggle for playing multiple sounds simultaneously.

Stop all sounds button to instantly stop everything.

Search functionality to quickly filter sounds.

Fully customizable sounds and colors.

🎬 Demo

You can preview the soundboard locally:

Clone the repository:

git clone https://github.com/YourUsername/soundboard.git


Open index.html in a modern browser (Chrome, Firefox, or Edge recommended).

Optional: Deploy on GitHub Pages for a live demo.

🛠 Installation & Usage

Edit sounds.js to add your own sounds:

export const sounds = [
  { name: 'Laugh', url: 'sounds/laugh.mp3', color: '#777' },
  { name: 'Clap', url: 'sounds/clap.mp3', color: '#555' }
];


Open index.html in a browser.

Click Enter on the start page.

Click any sound button to play sounds.

Use Favorites or Search to filter buttons.

Use Stop All Sounds to stop playback.

🎨 Customization

Theme & colors: Adjust the glass effect in CSS:

#startpage {
    background: rgba(30,30,30,0.85);
    backdrop-filter: blur(10px);
}
.sound-button-img {
    background-color: var(--btn-color);
}


Add or remove sounds: Modify sounds.js entries.

Button size & layout: Adjust .sound-wrapper and .sound-button-img in CSS.

🤝 Contributing

Fork the repository.

Create a new branch: git checkout -b feature-name.

Make your changes and commit them: git commit -m "Add feature".

Push to your branch: git push origin feature-name.

Open a Pull Request explaining your changes.

📜 License

This project is open-source. You may use, modify, and distribute it freely.

🙌 Credits

Background images: Pixabay

Sound button images: jsDelivr / GitHub

Inspired by custom soundboard layouts.
