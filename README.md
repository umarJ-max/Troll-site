# 🎭 Troll Hacker Site

> A fun interactive website that trolls users with a moving "Yes" button and personalized messages. Perfect for pranking friends!

![Version](https://img.shields.io/badge/version-2.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Mobile](https://img.shields.io/badge/mobile-friendly-brightgreen.svg)

## ✨ Features

### 🎮 Core Functionality
- **Welcome Screen**: Personalized greeting with name input
- **Dynamic Questions**: Customizable questions using user's name
- **Troll Mechanics**: "Yes" button that escapes when users try to click it
- **Smart Movement**: Button avoids question area and "No" button
- **Instant Feedback**: "No" button reveals the troll message

### 🎨 User Experience
- **Modern Design**: Beautiful gradient backgrounds with glass-morphism effects
- **Smooth Animations**: Hover effects, transitions, and micro-interactions
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile
- **Touch Support**: Optimized for mobile touch interactions
- **Accessibility**: Proper contrast ratios and keyboard navigation

### 🛠️ Admin Features
- **Question Customization**: Change the troll question dynamically
- **Persistent Storage**: Questions saved in browser localStorage
- **Mobile-Friendly Admin**: Works on all devices
- **Real-time Updates**: Changes reflect immediately

## 🚀 Quick Start

### Option 1: Direct Use
1. Download or clone this repository
2. Open `index.html` in any modern web browser
3. Start trolling! 😄

### Option 2: Deploy to Vercel
1. Fork this repository to your GitHub account
2. Go to [Vercel](https://vercel.com) and import your repository
3. Deploy with one click - no configuration needed!

## 🔧 Admin Panel Access

### Mobile & Desktop Compatible Method:
1. On the welcome screen, enter `hackAdm8` in the name field
2. Click "Start the Fun" button
3. Admin panel will open automatically
4. Customize your question and save

### Alternative Method (Desktop Only):
- Press `Ctrl + Alt + Q` and enter password `hackAdmin123`

### Admin Panel Features:
- ✏️ Edit the troll question
- 💾 Auto-save to browser storage
- 🔄 Real-time preview
- 📱 Mobile-friendly interface

**Pro Tip**: Use `{name}` in your question where you want the user's name to appear!

## 🎯 How It Works

1. **User enters name** → Personalized experience begins
2. **Question appears** → Customizable troll question with user's name
3. **User tries "Yes"** → Button moves away (the troll begins!)
4. **User clicks "No"** → Reveals the punchline
5. **Play Again** → Restart for more fun

## 🛡️ Security Features

- Input validation and sanitization
- XSS protection
- Safe localStorage usage
- No external dependencies

## 📱 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Colors & Themes
Edit CSS variables in the `:root` section:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    /* ... more variables */
}
```

### Questions
- Use admin panel for easy editing
- Or modify `CONFIG.defaultQuestion` in JavaScript
- Remember to use `{name}` placeholder

### Admin Password
Change `CONFIG.secretKey` in the JavaScript section

## 📁 Project Structure

```
trool-site/
├── index.html          # Main application file
├── Icon.png           # Favicon
├── README.md          # This file
└── vercel.json        # Vercel deployment config
```

## 🔧 Technologies Used

- **HTML5**: Semantic markup and modern features
- **CSS3**: 
  - CSS Grid & Flexbox for layout
  - CSS Variables for theming
  - Backdrop-filter for glass effects
  - CSS Animations & Transitions
- **JavaScript (ES6+)**:
  - Modern DOM manipulation
  - Event handling
  - LocalStorage API
  - Responsive design patterns

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Developer

**Umar J** - Full Stack Developer

- 🌟 Passionate about creating fun, interactive web experiences
- 💡 Specializes in modern web technologies and user experience
- 🎯 Focus on clean code and responsive design

## 🎉 Fun Facts

- 🎭 Perfect for April Fools' pranks
- 📱 Works great as a mobile web app
- 🚀 Zero dependencies - pure vanilla JavaScript
- 🎨 Modern design trends with glass-morphism
- ⚡ Lightning fast loading

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](../../issues) section
2. Create a new issue with detailed description
3. Include browser version and device information

---

**Made with ❤️ for fun and entertainment!**

*Remember: Use responsibly and only prank friends who appreciate good humor! 😄*