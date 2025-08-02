# Twimba

A Twitter-like social media application built with vanilla JavaScript, HTML, and CSS.

## 🚀 Live Demo

[View Live Site](https://kvothe1387.github.io/Twimba/)

## 📸 Screenshot

![Twimba Screenshot](images\screenshot.png)


## 🔥 Features

- **Post Tweets**: Create and publish new tweets with a simple text input
- **Interactive Engagement**: Like and retweet posts with real-time counter updates
- **Reply System**: View and toggle replies for each tweet
- **Responsive Design**: Clean, Twitter-inspired UI that works on different screen sizes
- **Dynamic Feed**: Real-time updates without page refresh

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Custom styling with Flexbox layout
- **Vanilla JavaScript**: ES6+ features including modules and arrow functions
- **Font Awesome**: Icons for social interactions
- **Google Fonts**: Roboto font family for typography
- **UUID**: Unique identifier generation for tweets

## 📁 Project Structure

```
Twimba/
│
├── index.html          # Main HTML file
├── index.css           # Stylesheet
├── index.js            # Main JavaScript functionality
├── data.js             # Tweet data and sample content
├── images/             # Profile pictures and assets
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/kvothe1387/Twimba.git
   ```

2. Navigate to the project directory
   ```bash
   cd Twimba
   ```

3. Open `index.html` in your web browser or use a local server

### Local Development

For the best development experience, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using VS Code Live Server extension
# Right-click on index.html and select "Open with Live Server"
```

## 💡 How It Works

### Core Functionality

1. **Tweet Creation**: Users can type in the textarea and click "Tweet" to add new posts
2. **Like System**: Click the heart icon to like/unlike tweets with animated feedback
3. **Retweet System**: Share tweets with the retweet button
4. **Reply Visibility**: Click the comment icon to show/hide replies for each tweet

### Key JavaScript Features

- **Event Delegation**: Single event listener handles all user interactions
- **Data Manipulation**: Dynamic updates to tweet objects and UI rendering
- **Module System**: ES6 imports for clean code organization
- **UUID Generation**: Unique identifiers for each tweet

## 🔧 Customization

### Adding New Features

The modular structure makes it easy to extend:

- Add new tweet properties in `data.js`
- Extend the UI in `getFeedHtml()` function
- Add new event handlers in the main event listener

### Styling

Modify `index.css` to customize:
- Color scheme
- Layout dimensions
- Typography
- Animations and transitions

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**kvothe1387**
- GitHub: [kvothe1387](https://github.com/kvothe1387)
- LinkedIn: [David McCullough](https://www.linkedin.com/in/davidmcc-webdev/)
- Portfolio: [My Portfolio](https://davidmcc.netlify.app/)

## 🙏 Acknowledgments

- Font Awesome for the beautiful icons
- Google Fonts for typography
- Inspired by Twitter's user interface design

---

⭐ Star this repo if you found it helpful!