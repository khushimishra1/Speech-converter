# Text-to-Speech Converter

A simple and elegant web application that converts text to speech using the browser's built-in Speech Synthesis API. Users can type or paste text and hear it spoken in different voices.

## Features

- **Text-to-Speech Conversion**: Type or paste any text and click "Listen" to hear it spoken
- **Multiple Voice Options**: Choose from all available voices on your device/browser
- **Responsive Design**: Clean, modern interface that works on desktop and mobile devices
- **Color Gradient Background**: Visually appealing gradient background design
- **Easy to Use**: Simple interface with just a textarea, voice selector, and play button

## Demo

Visit the live demo: [Text-to-Speech Converter](https://your-github-username.github.io/text-to-speech-converter)

## Screenshots

[Include screenshots of your application here]

## Technologies Used

- HTML5
- CSS3 (with custom styling and gradients)
- JavaScript (ES6+)
- Speech Synthesis API
- GitHub Pages for deployment

## Getting Started

### Prerequisites

- A modern web browser that supports the Speech Synthesis API (Chrome, Firefox, Safari, Edge)
- Web server or GitHub Pages for hosting (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/text-to-speech-converter.git
```

2. Navigate to the project directory:
```bash
cd text-to-speech-converter
```

3. Open `index.html` in your browser or set up a local server:
```bash
# Using Python 3
python -m http.server 8000

# Or using Node.js http-server
npx http-server
```

4. Visit `http://localhost:8000` (or your server's address) to use the application

## How to Use

1. **Enter Text**: Type or paste your text in the textarea
2. **Select Voice**: Choose your preferred voice from the dropdown menu
3. **Listen**: Click the "Listen" button to hear your text spoken aloud

## Project Structure

```
text-to-speech-converter/
├── index.html          # Main HTML file
├── style.css           # CSS styles and layout
├── script.js           # JavaScript functionality
├── images/             # Images directory
│   ├── play.png       # Play button icon
│   └── dropdown.png   # Dropdown arrow icon
├── .github/
│   └── workflows/
│       └── static.yml # GitHub Pages deployment workflow
└── README.md          # Project documentation
```

## Deployment

This project is configured to automatically deploy to GitHub Pages using GitHub Actions. When you push to the `main` branch, the workflow will:

1. Check out the code
2. Configure GitHub Pages
3. Upload the project files
4. Deploy to GitHub Pages

To enable this:

1. Enable GitHub Pages in your repository settings
2. Set the source to "GitHub Actions"
3. Push your code to the `main` branch

## Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

*Note: Some browsers may have limited voice options compared to others*

## Known Issues

- Voice selection may be limited depending on the user's operating system and browser
- Some voices may not work properly on certain devices
- Voice quality varies by browser and operating system

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Add speech rate control
- [ ] Add pitch control
- [ ] Save text to local storage
- [ ] Export speech as audio file
- [ ] Add text highlighting as it's being spoken
- [ ] Add multiple language support
- [ ] Dark/light theme toggle
- [ ] Text file upload capability

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Font: Poppins from Google Fonts
- Icons: Custom icons for play and dropdown
- Speech Synthesis API provided by browsers
