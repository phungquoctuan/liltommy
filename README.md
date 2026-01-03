# 🎨 LIL'TOMMY - Portfolio Website

A stunning, modern portfolio website featuring smooth scroll animations, canvas-based image sequences, and an immersive user experience.

## ✨ Features

- 🎬 **Smooth Scroll Animation** - Powered by Locomotive Scroll
- 🎨 **Canvas Animation** - 300-frame image sequence with GSAP ScrollTrigger
- 📱 **Responsive Design** - Mobile-friendly interface
- 🚀 **Modern UI/UX** - Clean, minimalist design with smooth transitions
- 📄 **Multi-page Navigation** - Home, Quotes, and Process pages
- 📝 **Markdown Support** - Dynamic content rendering for process documentation

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript** - Interactive functionality
- **Locomotive Scroll** - Smooth scrolling library
- **GSAP (GreenSock)** - Animation library
- **ScrollTrigger** - Scroll-based animations
- **Marked.js** - Markdown parser

## 📁 Project Structure

```
liltommy/
├── index.html          # Main homepage
├── quote.html          # Quotes page
├── script.js           # JavaScript functionality
├── style.css           # Stylesheet
├── img/                # Image assets (300 frames)
│   └── male0001.png - male0300.png
├── process/            # Process documentation
│   ├── index.html      # Process page
│   └── 1.md           # Markdown content
├── favicon.png         # Site icon
└── README.md           # This file
```

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone <your-repo-url>
cd liltommy
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

3. Navigate to `http://localhost:8000` in your browser

### GitHub Pages Deployment

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select the branch (usually `main` or `master`)
4. Select the folder (usually `/root`)
5. Click Save
6. Your site will be available at `https://<username>.github.io/<repository-name>`

## 🎯 Pages

- **Home** (`index.html`) - Main landing page with animated canvas
- **Quotes** (`quote.html`) - Inspirational quotes page
- **Process** (`process/index.html`) - Documentation and workflow

## 🎨 Customization

### Changing Images

Replace the images in the `img/` folder. Ensure they follow the naming convention:
- `male0001.png` through `male0300.png`
- Update the `frameCount` variable in `script.js` if using a different number of frames

### Modifying Content

- Edit `index.html` for homepage content
- Edit `quote.html` for quotes page
- Edit `process/1.md` for process documentation (Markdown format)

### Styling

Modify `style.css` to customize:
- Colors
- Fonts
- Spacing
- Animations
- Responsive breakpoints

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

See [LICENSE](LICENSE) file for details.

## 👤 Author

**LIL'TOMMY**

---

⭐ If you like this project, give it a star!
