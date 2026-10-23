# AirPods — Portfolio Site

A front-end portfolio project about the AirPods lineup: a dark-first, Apple-inspired product page with liquid-glass navigation, scroll-driven motion and a built-in language and theme switcher. No frameworks, no build step, just HTML, CSS and vanilla JavaScript.

![HTML5](https://img.shields.io/badge/HTML5-161618?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-161618?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-161618?style=flat&logo=javascript&logoColor=white)
![Dependencies](https://img.shields.io/badge/dependencies-none-0071e3?style=flat)

![Hero](docs/screenshots/hero.png)

## Highlights

- **Liquid-glass navigation bar** with a pointer-following highlight that hides on scroll down and returns on scroll up
- **Bento product cards** for AirPods Max, AirPods Pro 3 and AirPods, each with expandable specs
- **Scroll motion with easing**: products rotate and drift as you scroll, blocks reveal softly, and the key sentence lights up word by word
- **Compare table** for the three models
- **Dark theme on every visit**, with a light theme one click away
- **Three languages (EN / RU / DE)**, always starting in English
- **Responsive** down to small phones, and `prefers-reduced-motion` is respected
- Accessible basics: visible keyboard focus, labelled controls, readable contrast

## Screenshots

**Product cards**

![Cards](docs/screenshots/cards.png)

**Footer**

![Footer](docs/screenshots/footer.png)

## Project structure

```
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── apple.png
│   ├── Big.png
│   ├── Case.png
│   ├── Min.png
│   ├── Power.png
│   └── raser.png
└── docs/
    └── screenshots/
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize

- **Texts and languages** live in the `T` object at the top of `js/main.js`. Add a new language block there and a button with `data-lang` in the navigation.
- **Colors** are CSS variables at the top of `css/style.css`, one set for dark and one for light.

## Notes

AirPods and the Apple logo are trademarks of Apple Inc. This is a non-commercial portfolio project and is not affiliated with or endorsed by Apple.

---

Site made by [Nate](https://github.com/NatePoint)
