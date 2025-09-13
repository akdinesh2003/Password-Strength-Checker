## Password-Strength-Checker

**A beautiful, interactive password strength checker with advanced features and stunning animations**

[🚀 Live Demo](#) • [🎯 Features](#features) • [🛠️ Installation](#installation)

</div>

---

## ✨ Features

### 🎯 **Core Functionality**
- **Real-time Password Analysis** - Instant feedback as you type
- **Visual Strength Indicators** - Color-coded progress bars and animations
- **Security Score System** - 0-100 point scoring with detailed breakdown
- **Regex-based Validation** - Comprehensive pattern matching for security criteria

### 🎨 **Visual Excellence**
- **Stunning Animations** - Pulse, bounce, and shake effects for engaging feedback
- **Responsive Design** - Perfect on desktop, tablet, and mobile devices
- **Beautiful UI** - Modern gradient backgrounds and smooth transitions
- **Interactive Elements** - Hover effects and dynamic visual feedback

### 🚀 **Advanced Features**

#### 🎲 **Smart Password Generator**
- Customizable length (8-32 characters)
- Toggle character types (uppercase, lowercase, numbers, symbols)
- One-click secure password generation
- Animated feedback on generation

#### 📚 **Password History Tracker**
- Stores last 5 tested passwords
- Shows security scores for each attempt
- Easy comparison between different passwords
- One-click history clearing

#### 💡 **Intelligent Tips System**
- Personalized security recommendations
- Context-aware suggestions based on current password
- Rotating tip indicators with smooth animations
- Educational security best practices

---

## 🎮 How It Works

### Security Criteria Checklist
- ✅ **Length Check** - Minimum 8 characters
- ✅ **Uppercase Letters** - A-Z detection
- ✅ **Lowercase Letters** - a-z detection  
- ✅ **Numbers** - 0-9 detection
- ✅ **Special Characters** - Symbol validation

### Strength Levels
| Score | Level | Color | Description |
|-------|-------|-------|-------------|
| 0-39 | Very Weak | 🔴 Red | Needs serious improvement |
| 40-59 | Weak | 🟠 Orange | Getting better but still vulnerable |
| 60-79 | Good | 🟡 Yellow | Decent security level |
| 80-99 | Strong | 🟢 Green | Very secure password |
| 100 | Very Strong | 💚 Emerald | Fort Knox level security! |

---

## 🛠️ Installation

### Quick Start
1. **Download** the HTML file
2. **Open** in any modern web browser
3. **Start testing** your passwords immediately!

``bash
# Clone the repository
git clone  https://github.com/akdinesh2003/Password-Strength-Checker
# Navigate to the project
cd password-strength-checker

# Open in browser
open index.html

Requirements

✅ Modern web browser (Chrome, Firefox, Safari, Edge)
✅ Internet connection (for Tailwind CSS CDN)
✅ No additional dependencies required!
🎯 Usage Examples

Basic Password Testing

1. Type your password in the input field
2. Watch real-time strength analysis
3. See which criteria are met with animated checkmarks
4. Get your security score out of 100

Password Generation

1. Scroll to the Password Generator section
2. Customize length and character types
3. Click "Generate Secure Password"
4. Watch as a strong password is created and analyzed

History Tracking

1. Test multiple passwords
2. View your testing history in the Password History section
3. Compare scores between different attempts
4. Clear history when needed

🎨 Customization

Color Themes

The app uses a beautiful gradient background and can be easily customized:

.gradient-bg {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

Animation Speed

Adjust animation timing in the CSS:

.strength-bar {
    transition: all 0.3s ease;
}

Security Criteria

Modify the regex patterns for different security requirements:

// Example: Stricter special character requirement
if (/[!@#$%^&*()_+\-=\[\]{};':"\\|,.<>\/?~`]/.test(password)) {
    // Your custom logic here
}

🔧 Technical Details

Built With

HTML5
 - Semantic markup and structure
CSS3
 - Custom animations and styling
JavaScript (ES6+)
 - Interactive functionality
Tailwind CSS
 - Utility-first styling framework
Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 60+ | ✅ Fully Supported |
| Firefox | 55+ | ✅ Fully Supported |
| Safari | 12+ | ✅ Fully Supported |
| Edge | 79+ | ✅ Fully Supported |

Performance

⚡ 
Lightweight
 - Single HTML file under 15KB
🚀 
Fast Loading
 - No external dependencies except Tailwind CDN
📱 
Mobile Optimized
 - Responsive design for all devices
🔄 
Real-time Updates
 - Instant feedback without page refreshes
🤝 Contributing

We welcome contributions! Here's how you can help:

Fork
 the repository
Create
 a feature branch (
git checkout -b feature/AmazingFeature
)
Commit
 your changes (
git commit -m 'Add some AmazingFeature'
)
Push
 to the branch (
git push origin feature/AmazingFeature
)
Open
 a Pull Request
Ideas for Contributions

🌍 
Internationalization
 - Multi-language support
🎨 
Themes
 - Dark mode and custom color schemes
📊 
Analytics
 - Password strength statistics
🔒 
Advanced Security
 - Breach database checking
📱 
PWA Features
 - Offline functionality
📄 License

This project is licensed under the MIT License - see the 
LICENSE
 file for details.

MIT License

Copyright (c) 2025 Password Strength Checker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...

🙏 Acknowledgments

🎨 
Tailwind CSS
 - For the beautiful utility-first styling
🌈 
Gradient Magic
 - Inspiration for the stunning background
🔐 
Security Community
 - For password security best practices
💡 
Open Source
 - For making collaboration possible

 Features

[ ] 🌙 Dark mode toggle
[ ] 📊 Password strength analytics dashboard
[ ] 🔄 Password history export
[ ] 🌐 Multi-language support
[ ] 📱 Progressive Web App (PWA)
[ ] 🔒 Integration with Have I Been Pwned API
[ ] 🎯 Custom security policy configuration
Made with ❤️ and lots of ☕

⭐ 
Star this repo if you found it helpful!
⭐

## Author
AK DINESH https://github.com/akdinesh2003

