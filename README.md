# 🧠 Quizzler Pro

<div align="center">

![Quizzler Pro Logo](https://img.shields.io/badge/🧠-Quizzler%20Pro-blue?style=for-the-badge&logoColor=white)

**A modern, interactive quiz application with AI-powered content generation**

[![Live Demo](https://img.shields.io/badge/🚀-Live%20Demo-green?style=for-the-badge)](https://quizzlerpro.netlify.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-orange?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![Netlify Status](https://img.shields.io/badge/Deployed%20on-Netlify-blue?style=for-the-badge&logo=netlify)](https://netlify.com)

*Create custom quizzes from CSV files, track your performance, and generate quiz content with AI assistance.*

</div>

## ✨ Features

### 🎯 **Core Quiz Features**
- 📁 **CSV File Support** - Upload custom quiz files in CSV format
- 🔀 **Question Shuffling** - Randomize question order for varied practice  
- ⚙️ **Customizable Difficulty** - Set 1-3 attempts per question
- 🎯 **Smart Scoring** - Tracks attempts and provides detailed feedback
- 🔄 **Review Mode** - Retry only the questions you missed

### 🤖 **AI-Powered Content Generation**
- ✨ **Smart Prompt Generator** - Creates custom ChatGPT prompts for any topic
- 📥 **Intelligent CSV Templates** - Downloads pre-configured templates with AI instructions
- 🎨 **Topic Customization** - Specify subject, difficulty, focus areas, and question count
- 💡 **One-Click Integration** - Direct links to ChatGPT with generated prompts

### 📊 **Performance Tracking**
- 📈 **Detailed Statistics** - Track scores, timing, and progress over time
- 💾 **Persistent Storage** - Performance history saved locally
- 🏆 **Achievement Tracking** - Best scores, averages, and improvement trends
- 📱 **Progress Analytics** - Question-by-question timing and accuracy

### 🎨 **User Experience**
- 🌙 **Dark/Light Themes** - Beautiful themes with smooth transitions
- 📱 **Mobile Responsive** - Optimized for all device sizes and touch interactions
- 🔊 **Audio Feedback** - Sound effects with haptic support
- ⌨️ **Keyboard Navigation** - Full keyboard shortcuts (1-4 for answers, Enter to continue)
- 🎭 **Smooth Animations** - Modern CSS animations and transitions

## 🚀 Quick Start

### 🌐 **Try It Now**
👉 **[Live Demo](https://your-app-name.netlify.app)** - No installation required!

### 💻 **Local Development**
```bash
# Clone the repository
git clone https://github.com/SecuredByKC/Quizzler.git

# Open the file
cd Quizzler
open index.html
# or simply double-click index.html
```

### 🚀 **Deploy Your Own**
1. **Fork this repository**
2. **Connect to Netlify** or your preferred hosting service
3. **Your quiz app is live!**

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/quizzler-pro)

## 📝 Creating Quiz Content

### 📊 **CSV Format**
Create quiz files using this simple format:

| Question                   | Option A | Option B | Option C | Option D | Correct Answer |
|----------------------------|----------|----------|----------|----------|----------------|
| What is the capital of France? | Paris    | London   | Berlin   | Madrid   | A              |
| What is 2 + 2?              | 3        | 4        | 5        | 6        | B              |
| Which planet is largest?    | Earth    | Mars     | Jupiter  | Venus    | C              |


### 🤖 **AI-Powered Quiz Generation**
1. **Use the built-in prompt generator** to create custom ChatGPT prompts
2. **Specify your topic, difficulty, and focus areas**
3. **Download the smart CSV template** with embedded AI instructions
4. **Upload to ChatGPT** and request quiz generation
5. **Download the completed CSV** and use it in Quizzler Pro

### ✅ **CSV Requirements**
- ✅ Wrap each field in quotes: `"Question text here"`
- ✅ Use A, B, C, or D for correct answers
- ✅ Include exactly 6 columns per row
- ✅ Add comments with `#` for instructions
- ✅ Skip headers when using the template generator

## 🎮 How to Use

### 📤 **Getting Started**
1. **Open the app** in your web browser
2. **Click "CSV Format Help"** to generate quiz content or download templates
3. **Upload your CSV file** using the file picker
4. **Configure your preferences** (attempts per question, question shuffling)
5. **Start your quiz!**

### ⌨️ **Keyboard Shortcuts**
- **1-4 Keys** - Select answer options A-D
- **Enter** - Continue to next question
- **Space** - Start quiz (on home screen)

### 📱 **Mobile Features**
- **Touch-optimized** interface with large buttons
- **Haptic feedback** for correct/incorrect answers
- **Responsive design** that works on any screen size

## 🛠️ Technical Details

### 📋 **Tech Stack**
- **Frontend**: Pure HTML5, CSS3, and JavaScript (ES6+)
- **Styling**: Custom CSS with modern features (Grid, Flexbox, CSS Variables)
- **Storage**: LocalStorage for performance data persistence
- **File Handling**: Native FileReader API for CSV processing
- **Audio**: Web Audio API for sound effects
- **Deployment**: Single file - works anywhere!

### 🌐 **Browser Support**
- ✅ **Chrome**
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Mobile browsers** (iOS Safari, Android, Chrome Mobile)

### ⚡ **Performance Features**
- **Zero dependencies** - Pure vanilla JavaScript
- **Lightweight** - Single HTML file under 100KB
- **Fast loading** - No external resources or API calls
- **Offline capable** - Works without internet connection
- **SEO optimized** - Proper meta tags and semantic HTML

## 📸 Screenshots

<div align="center">

## 🏠 Home Screen
Clean, modern interface with easy file upload and configuration

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/HomeScreenDarkMode.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/HomeScreenLightMode.jpg" width="45%" />
</p>

---

## 🎯 Quiz Interface
Intuitive question display with progress tracking and beautiful animations

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/SampleCorrectAnswerDarkMode.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/SampleCorrectAnswerLightMode.jpg" width="45%" />
</p>

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/SampleCorrectAnswerDarkMode2.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/SampleWrongAnswerLightMode.jpg" width="45%" />
</p>

---

## 📊 Results & Analytics
Detailed performance analysis with missed question review

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/PerformanceStatsDarkMode.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/PerformanceStatsScreenLightMode.jpg" width="45%" />
</p>

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/QuizSummaryDarkMode.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/QuizSummaryLightMode.jpg" width="45%" />
</p>

---

## 🤖 AI Content Generator
Smart prompt generator for creating custom quiz content with ChatGPT

<p float="left">
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/QuizFileGenScreenDarkMode.jpg" width="45%" />
  <img src="https://raw.githubusercontent.com/SecuredByKC/QuizzlerPro/main/QuizFileGenScreenLightMode.jpg" width="45%" />
</p>


</div>

## 🎯 Use Cases

### 🎓 **Education**
- **Students** - Create study materials for any subject
- **Teachers** - Generate quiz content for classroom use  
- **Tutors** - Build custom assessments for students

### 💼 **Professional Training**
- **Corporate Training** - Employee knowledge assessments
- **Certification Prep** - Practice tests for professional certifications
- **Skill Assessment** - Evaluate team knowledge and competencies

### 🏠 **Personal Learning**
- **Self-Study** - Track learning progress on any topic
- **Interview Prep** - Practice questions for job interviews
- **General Knowledge** - Fun quizzes for family and friends

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### 🐛 **Bug Reports**
- Use the [Issues](https://github.com/SecuredByKC/Quizzler/issues) tab
- Include browser version and steps to reproduce
- Screenshots are helpful!

### ✨ **Feature Requests**  
- Suggest new features via [Issues](https://github.com/SecuredByKC/Quizzler/issues)
- Explain the use case and expected behavior
- Check existing issues to avoid duplicates

### 💻 **Code Contributions**
1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes** and test thoroughly
4. **Commit your changes**: `git commit -m 'Add amazing feature'`
5. **Push to the branch**: `git push origin feature/amazing-feature`
6. **Open a Pull Request**

### 📝 **Documentation**
- Improve the README or add tutorials
- Create example CSV files
- Write usage guides or best practices

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Quizzler Pro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🙏 Acknowledgments

- **Design Inspiration** - Modern web design trends and glassmorphism
- **Icons & Emojis** - Unicode emoji set for visual elements  
- **Testing** - Community feedback and user testing
- **AI Integration** - OpenAI's ChatGPT for content generation capabilities

## 📞 Support

### 🆘 **Getting Help**
- 📖 **Documentation** - Check this README and code comments
- 🐛 **Issues** - Search existing [issues](https://github.com/yourusername/quizzler-pro/issues) or create a new one
- 💬 **Discussions** - Join the conversation in [Discussions](https://github.com/yourusername/quizzler-pro/discussions)

### 🔧 **Troubleshooting**
- **CSV Upload Issues** - Ensure your file follows the exact format shown above
- **Browser Compatibility** - Try in a different browser or update to the latest version
- **Performance Issues** - Clear browser cache and localStorage data
- **File Size Limits** - Keep CSV files under 1MB for optimal performance

## 🚀 What's Next?

### 🎯 **Planned Features**
- [ ] **Multi-language support** - Interface translations
- [ ] **Question types** - True/false, fill-in-the-blank, matching
- [ ] **Timer modes** - Timed quizzes with countdown
- [ ] **Themes** - Additional color schemes and customization
- [ ] **Export results** - PDF reports and sharing capabilities
- [ ] **Collaborative features** - Share quizzes with others

### 💡 **Ideas & Suggestions**
Have ideas for new features? We'd love to hear them! Open an issue with the `enhancement` label.

---

<div align="center">

**Made with ❤️ for learners everywhere**

⭐ **Star this repo** if you found it helpful! ⭐

[![GitHub stars](https://img.shields.io/github/stars/yourusername/quizzler-pro?style=social)](https://github.com/yourusername/quizzler-pro/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/quizzler-pro?style=social)](https://github.com/yourusername/quizzler-pro/network/members)

[🌐 Live Demo](https://your-app-name.netlify.app) • [📝 Documentation](https://github.com/yourusername/quizzler-pro#readme) • [🐛 Report Bug](https://github.com/yourusername/quizzler-pro/issues) • [✨ Request Feature](https://github.com/yourusername/quizzler-pro/issues)

</div>
