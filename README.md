# Blaze Page Portfolio

![Blaze Portfolio Banner](/images/banner.png)

A modern, responsive portfolio website with light/dark mode toggle, built with HTML, CSS, and JavaScript.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Overview

Blaze Page is a personal portfolio website template designed to showcase your professional skills, projects, and services. It features a clean, modern design with a light/dark mode toggle and smooth animations.

[Live Demo](https://blazepage.online/)

![Website Preview](/images/preview.png)

## ✨ Features

- **Responsive Design**: Adapts to all device sizes
- **Light/Dark Mode**: Toggle between themes with persistent settings
- **CSS Animations**: Animated lines in hero section, card hover effects
- **Image Sliders**: Interactive project showcases with auto-play
- **Contact Form**: Integrated with Web3Forms API
- **Newsletter Subscription**: Capture visitor emails
- **Modern UI Components**: Including cards, progress bars, and service displays
- **Smooth Scrolling**: Enhanced navigation experience

## 🛠️ Technology Stack

- HTML5
- CSS3 (with CSS variables for theming)
- JavaScript (Vanilla)
- Font Awesome Icons
- Web3Forms API (for form submissions)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/eddie-blaze19/BlazePage.git
cd BlazePage
```

2. No build process required! Open `index.html` in your browser to view the site.

3. For deployment, simply upload all files to your web hosting service.

## 📁 Project Structure

```
blaze-portfolio/
├── index.html              # Main HTML file
├── images/                 # Image assets
│   ├── cloudProjects/      # Cloud project screenshots
│   ├── CkApp/             # Educational app screenshots
│   ├── GGApp/             # Inventory management screenshots
│   ├── day.gif            # Day mode background
│   ├── night.gif          # Night mode background
│   └── ...                # Other image assets
├── slide-style.css        # Additional styles for image sliders
├── site.webmanifest       # Web app manifest file
└── README.md              # Project documentation
```

## 🚀 Usage

### Local Development

Simply open the `index.html` file in your browser. No server or build process required.

For a local development server, you can use:

```bash
# If you have Python installed
python -m http.server

# If you have Node.js installed
npx serve
```

### Form Functionality

The contact and newsletter forms are connected to Web3Forms. To use them:

1. Create an account at [Web3Forms](https://web3forms.com/)
2. Replace the access key in the HTML with your own:
```html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
```

## 🎨 Customization

### Changing Colors

The color scheme is controlled by CSS variables in the `:root` selector. Modify these variables to change the theme colors:

```css
:root {
    --bg-primary: #f8f9fa;
    --bg-secondary: #ffffff;
    --text-primary: #333333;
    --text-secondary: #666666;
    --accent-color: #4a6eb5;
    /* Other variables */
}

.dark-mode {
    --bg-primary: #1a1a1a;
    --bg-secondary: #2a2a2a;
    /* Dark mode variables */
}
```

### Personalization

1. Replace all instances of "Edward Dziworshie" with Edward Dziworshie
2. Update the professional description in the hero section
3. Replace portfolio images in the `images/` directory
4. Update skills and their progress percentages
5. Change contact information and social media links

### Adding Projects

To add a new project to the portfolio section:

1. Add project images to an appropriate subfolder in `images/`
2. Copy an existing portfolio item structure and update the content:

```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <!-- Slider or image code here -->
    </div>
    <div class="portfolio-content">
        <span class="portfolio-category">Your Category</span>
        <h3 class="portfolio-title">Project Title</h3>
        <p>Project description goes here.</p>
    </div>
</div>
```

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Edward Dziworshie - [edwarddziworshie@gmail.com](mailto:edwarddziworshie@gmail.com)

Project Link: [https://github.com/eddie-blaze19/blazepage](https://github.com/eddie-blaze19/blazepage)

---

Made with ❤️ by [Edward Dziworshie](https://blazepage.online)