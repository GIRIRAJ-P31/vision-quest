# 👁️ VISION QUEST | Your Vision's Best Friend

An interactive web application designed to help users understand and manage their eye health based on screen time and sleep patterns. Built with data-driven insights from a 500-sample study.

![Vision Quest](https://img.shields.io/badge/Eye%20Health-Dashboard-6366f1)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)

## 🌟 Features

### 📊 Data-Driven Insights
- **Risk Prediction Calculator**: Evaluate your eye strain risk based on daily screen hours and sleep patterns
- **Interactive Charts**: Visualize trends from real dataset analysis
- **Evidence-Based Recommendations**: Insights from 500-sample study data

### 🎯 Interactive Elements
- **Daily Quest System**: Gamified eye health tips with celebration animations
- **Eye Strain Simulator**: Experience what eye fatigue feels like
- **Real-Time Risk Assessment**: Instant feedback on your eye health habits

### 📈 Data Visualizations
- **Role Distribution Chart**: Student vs Professional screen time comparison
- **Pain Level Analysis**: Correlation between screen hours and discomfort
- **Trend Tracking**: Monitor patterns across different usage groups

## 🚀 Quick Start

### Option 1: Direct Use
1. Download `index.html`
2. Open in any modern web browser
3. Start tracking your eye health!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then visit http://localhost:8000
```

### Option 3: GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch
4. Your site will be live at `https://yourusername.github.io/vision-quest/`

## 📖 How to Use

### 1️⃣ Risk Predictor
- Enter your daily screen hours (e.g., 8)
- Enter your average sleep hours (e.g., 6)
- Click "Predict My Risk" to see your assessment

**Risk Levels:**
- 🟢 **LOW RISK**: ≤7 screen hours & ≥7 sleep hours
- 🟡 **MEDIUM RISK**: 7-10 screen hours OR 5-7 sleep hours
- 🔴 **HIGH RISK**: >10 screen hours OR <5 sleep hours

### 2️⃣ Daily Quest
Complete simple eye health tasks like:
- 20-20-20 rule (Look 20 feet away for 20 seconds every 20 minutes)
- Hydration reminders
- Blinking exercises
- Posture checks

### 3️⃣ Eye Strain Simulator
Click "Simulate Strain" to experience visual effects of eye fatigue. This helps you recognize early warning signs in real life.

## 📊 Data Insights

The application is based on research findings showing:
- **30% higher risk** of eye pain for 8+ hours screen time
- **Students**: 266 participants (53.2%)
- **Professionals**: 234 participants (46.8%)
- Average pain levels consistent across usage ranges (4.9-5.1/10)

## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with modern gradients and animations
- **Vanilla JavaScript** - Interactive functionality
- **Chart.js** - Data visualization
- **Canvas Confetti** - Celebration animations
- **Font Awesome** - Icons

## 🎨 Design Features

- Modern gradient backgrounds
- Responsive card-based layout
- Interactive hover effects
- Smooth transitions and animations
- Color-coded risk indicators
- Gamification elements

## 🔧 Customization

### Modify Risk Thresholds
Edit the `predictRisk()` function in the JavaScript section:
```javascript
if (hrs > 10 || sleep < 5) {
    risk = "HIGH RISK 🚨";
    // Adjust values as needed
}
```

### Add More Tips
Extend the `tips` array:
```javascript
const tips = [
    "Your new tip here!",
    // Add more...
];
```

### Update Chart Data
Modify chart data in the `window.onload` function:
```javascript
data: [266, 234], // Update with your data
```

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Opera

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] User progress tracking with localStorage
- [ ] Export health reports as PDF
- [ ] Integration with real-time device usage APIs
- [ ] Mobile app version
- [ ] Multi-language support
- [ ] Dark mode toggle
- [ ] Social sharing features

## ⚠️ Disclaimer

This application provides general wellness information based on study data. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

Created with ❤️ for better eye health awareness

## 🙏 Acknowledgments

- Dataset insights from 500-participant study
- Chart.js for beautiful visualizations
- Canvas Confetti for delightful animations
- Font Awesome for crisp icons

---

**Stay healthy, keep your vision clear!** 👁️✨
