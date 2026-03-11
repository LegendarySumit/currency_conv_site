<div align="center">

# 💱 Currency Converter

**Real-Time Currency Conversion with Live Exchange Rates**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![API](https://img.shields.io/badge/API-ExchangeRate-blue)

*Convert between multiple currencies • Live exchange rates • Clean interface*

[Live Demo](https://legendarysumit.github.io/currency_conv_site/) • [View Code](https://github.com/LegendarySumit/currency_conv_site)

</div>

---

## 📖 About

A **simple and interactive Currency Converter** web application that allows users to convert between multiple currencies in **real-time** using **live exchange rates** from an external API.

---

## 🚀 Features

🔄 **Real-Time Conversion** — Fetches live exchange rates using API  
🖌️ **Clean UI** — Minimal and user-friendly interface  
📱 **Responsive Design** — Works on desktop, tablet, and mobile  
⚡ **Fast & Lightweight** — No unnecessary dependencies  
💰 **Multiple Currencies** — Support for major world currencies  
🔢 **Accurate Calculations** — Precise conversion rates  

---

## 🌐 Live Demo

**Try it now:** [Currency Converter](https://legendarysumit.github.io/currency_conv_site/)

---

## 🛠️ Tech Stack

- **HTML5** — Structure and markup
- **CSS3** — Styling and responsive design
- **JavaScript** — API integration and conversion logic
- **ExchangeRate API** — Live currency exchange rates
- **Git & GitHub** — Version control
- **VS Code** — Development environment

---

## 📦 Installation & Usage

### Quick Start

**1. Clone the repository**
```bash
git clone https://github.com/LegendarySumit/currency_conv_site.git
cd currency_conv_site
```

**2. Open in browser**
```bash
# Simply open index.html
open index.html

# Or use a local server
python -m http.server 8000
# Navigate to http://localhost:8000
```

### How to Use

1. **Select currencies** from the dropdown menus
2. **Enter amount** to convert
3. **View result** instantly with live exchange rates
4. **Swap currencies** using the swap button (if available)

---

## 🎨 Features in Detail

### Real-Time Exchange Rates
- Fetches latest rates from ExchangeRate API
- Automatic updates for accurate conversions
- Supports major world currencies

### User-Friendly Interface
- Clean, minimal design
- Easy currency selection
- Clear conversion display
- Mobile-responsive layout

### Lightweight Performance
- Fast loading times
- No heavy frameworks
- Efficient API calls
- Optimized for speed

---

## 🔧 API Integration

The application uses the **ExchangeRate API** for fetching live currency conversion rates.

**Example API Call:**
```javascript
const API_URL = 'https://api.exchangerate-api.com/v4/latest/USD';

fetch(API_URL)
  .then(response => response.json())
  .then(data => {
    // Process exchange rates
    console.log(data.rates);
  });
```

---

## 💻 Code Structure
```
currency_conv_site/
├── index.html          # Main HTML structure
├── style.css           # Styling and responsive design
├── script.js           # JavaScript logic and API calls
└── README.md           # Documentation
```

---

## 📱 Responsive Design

- **Desktop** — Full-width layout with detailed information
- **Tablet** — Optimized for medium screens
- **Mobile** — Compact, touch-friendly interface

---

## 🔮 Future Enhancements

- [ ] Historical exchange rate charts
- [ ] Multiple currency conversions at once
- [ ] Favorite currency pairs
- [ ] Offline mode with cached rates
- [ ] Currency trend indicators
- [ ] Calculator mode for complex conversions
- [ ] Dark/Light theme toggle

---

## 🐛 Known Limitations

- Requires internet connection for live rates
- API rate limits may apply (free tier)
- Limited to currencies supported by the API

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

**How to contribute:**
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available for educational purposes.

---

## 👨‍💻 Author

**LegendarySumit**

- GitHub: [@LegendarySumit](https://github.com/LegendarySumit)
- Project: [Currency Converter](https://github.com/LegendarySumit/currency_conv_site)
- Live Demo: [currency_conv_site](https://legendarysumit.github.io/currency_conv_site/)

---

## 🙏 Acknowledgments

- **ExchangeRate API** — For providing free exchange rate data
- **Font Awesome** — For icons (if used)
- **Open Source Community** — For inspiration and resources

---

<div align="center">

**💱 Convert currencies instantly with live rates**

*Simple • Fast • Accurate*

---

**⭐ Star this repo if you find it helpful!**

</div>
