# ☕ Dark Brew - Premium Coffee Experience

[![Website Status](https://img.shields.io/website?url=https%3A%2F%2Fyagartem4ik.github.io%2FDark_Brew%2F)](https://yagartem4ik.github.io/Dark_Brew/)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/yagartem4ik/Dark_Brew)](https://github.com/yagartem4ik/Dark_Brew/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![Dark Brew Hero Section](https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1200&q=80)

## 🚀 Live Demo

Experience Dark Brew right now:  
👉 [https://yagartem4ik.github.io/Dark_Brew/](https://yagartem4ik.github.io/Dark_Brew/)

## ✨ Features

- **Dark Aesthetic Design**
  - Elegant color palette with coffee-inspired tones
  - Sophisticated typography combination
  - Smooth glass morphism effects

- **Interactive Elements**
  - Animated coffee cards
  - Scroll-triggered animations
  - Responsive navigation

- **Premium Coffee Showcase**
  - Detailed coffee profiles
  - Tasting notes visualization
  - Origin information

## 🛠 Technologies Used

| Technology | Usage |
|------------|-------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Semantic structure |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Styling and animations |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Interactive functionality |
| ![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat&logo=fontawesome&logoColor=white) | Icons |
| ![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat&logo=google&logoColor=white) | Typography |

## 📂 Project Structure

```bash
Dark_Brew/
├── index.html          # Main entry point
├── assets/             # Static assets
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   └── images/         # Local images
├── README.md           # Documentation
└── LICENSE             # License file
```

## 🎨 Design Highlights

### Color Palette
```css
:root {
  --primary: #6F4E37;   /* Coffee Brown */
  --secondary: #C4A484; /* Latte */
  --dark: #1A120B;      /* Dark Chocolate */
  --light: #F5F5DC;     /* Beige */
  --accent: #A26769;    /* Marsala */
}
```

### Typography
- **Headings**: Cormorant Garamond (700 weight)
- **Body Text**: Montserrat (300/500 weights)

## 💻 Installation

1. Clone the repository:
```bash
git clone https://github.com/yagartem4ik/Dark_Brew.git
```

2. Navigate to project directory:
```bash
cd Dark_Brew
```

3. Open in your preferred browser:
```bash
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

## 🌐 Responsive Design

| Breakpoint | Target Devices |
|------------|----------------|
| 1920px+    | Large desktops |
| 1200px     | Standard desktops |
| 992px      | Tablets (landscape) |
| 768px      | Tablets (portrait) |
| 576px      | Large phones |
| 320px      | Small phones |

## 🧑‍💻 Development

### Key JavaScript Functions

**Smooth Scrolling**:
```javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function(e) {
    e.preventDefault();
    document.querySelector(this.getAttribute('href')).scrollIntoView({
      behavior: 'smooth'
    });
  });
});
```

**Scroll Animations**:
```javascript
window.addEventListener('scroll', () => {
  const cards = document.querySelectorAll('.coffee-card');
  cards.forEach((card, index) => {
    const position = card.getBoundingClientRect().top;
    if (position < window.innerHeight * 0.75) {
      setTimeout(() => {
        card.classList.add('animate');
      }, index * 150);
    }
  });
});
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


---

**Dark Brew** © 2023 | Crafted with ♥ and caffeine
