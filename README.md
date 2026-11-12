# Vaibhav Nampalliwar — Personal Portfolio

A responsive, single-page personal portfolio website for **Vaibhav Nampalliwar**, built with plain HTML, CSS and JavaScript and hosted on **GitHub Pages** at [vaibhav-nampalliwar.github.io](https://vaibhav-nampalliwar.github.io).

The site introduces Vaibhav, highlights his skills, and links to his social profiles.

## ✨ Features

- **Single-page layout** with smooth in-page navigation (Home, About, Skills, Contact)
- **Responsive design** powered by the Bootstrap 5 grid — works on mobile and desktop
- **Scroll animations** using AOS (Animate On Scroll) — fade, zoom, slide effects
- **Glassmorphism sticky navbar** that activates on scroll
- **Animated hamburger menu** that morphs into an "X" when open
- **Animated skill bars** for HTML, CSS, JavaScript, Bootstrap, Python, Linux, MySQL and AWS
- **Social links** to Facebook, GitHub, Instagram, LinkedIn, Twitter and Telegram
- **Google Analytics** integration for visit tracking
- Custom SVG **"V|N" monogram logo**

## 🛠️ Tech Stack

| Technology | Usage |
| --- | --- |
| HTML5 | Page structure and content |
| CSS3 | Styling, layout and animations |
| JavaScript (jQuery) | Sticky navbar behavior on scroll |
| [Bootstrap 5](https://getbootstrap.com/) | Responsive grid and components |
| [Bootstrap Icons](https://icons.getbootstrap.com/) | Social and UI icons |
| [AOS](https://michalsnik.github.io/aos/) | Animate-on-scroll animations |
| [Google Fonts](https://fonts.google.com/) | Montserrat typeface |
| [Google Analytics](https://analytics.google.com/) | Traffic tracking (`gtag.js`) |

## 📁 Project Structure

```
.
├── index.html                  # Single page: hero, about, skills, contact
├── README.md
├── images/
│   ├── favicon.ico             # Browser tab icon
│   ├── logo.svg                # Logo asset
│   └── pic-1.jpg               # Profile photo
├── scripts/
│   └── index.js                # Sticky navbar on scroll (jQuery)
└── styles/
    ├── style.css               # All custom styling and animations
    └── vaibhav_nampalliwar.pdf # Resume
```

## 🚀 Getting Started

This is a static website with **no build step** — just open it in a browser.

### Option 1 — Open directly

Open `index.html` in your browser.

### Option 2 — Run a local server (recommended)

```bash
# Python 3
python3 -m http.server 8000

# or with Node.js
npx serve .
```

Then visit <http://localhost:8000>.

## 🌐 Deployment

The site is served automatically by **GitHub Pages** from the `main` branch, because the repository is named `vaibhav-nampalliwar.github.io`. Any push to `main` publishes the site at:

```
https://vaibhav-nampalliwar.github.io
```

## ✏️ Customization

- **Content / text** → edit `index.html`
- **Colors, fonts, animations** → edit `styles/style.css` (background color is `rgb(32, 35, 48)`)
- **Skills & percentages** → update the `.progress-bar` `width` and `aria-valuenow` values in `index.html`
- **Social links** → update the `href` values in the Contact section of `index.html`
- **Resume** → replace `styles/vaibhav_nampalliwar.pdf` (the download button in the About section is currently commented out)
- **Analytics** → replace the Google Analytics ID `G-MNWM8ZGTHD` in `index.html`

## 🔗 Connect

- GitHub: [@vaibhav-nampalliwar](https://github.com/vaibhav-nampalliwar)
- LinkedIn: [vaibhav-nampalliwar](https://www.linkedin.com/in/vaibhav-nampalliwar)
- Instagram: [@vaibhav_nampalliwar](https://www.instagram.com/vaibhav_nampalliwar/)
- Twitter: [@Vaibhav__n](https://twitter.com/Vaibhav__n)
- Facebook: [vaibhav.nampalliwar97](https://www.facebook.com/vaibhav.nampalliwar97)
- Telegram: [@vaibhav_nampalliwar](https://t.me/vaibhav_nampalliwar)

## 📄 License

© Vaibhav Nampalliwar. All rights reserved.
