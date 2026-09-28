# Portfolio
# Jubin Mazumder | Portfolio

A retro game-themed personal portfolio built with plain HTML and CSS. No JavaScript, no frameworks, no Tailwind.

Built for **Class 11 Builders Day** of my web development course.

## About

I'm Jubin, a frontend developer who loves building and shipping. This site introduces me like a game character: player stats, an inventory of skills, and the projects I've cleared as levels.

## Sections

- **Hero:** intro card, portrait and a "loading" bar for what I'm learning next
- **Player stats:** a short intro and quick facts
- **Inventory:** the skills I know, plus locked slots for what I'm learning
- **Levels cleared:** my projects with links
- **Quest log:** education
- **Join my party:** contact links and a contact form

## Technologies

- HTML5 (semantic tags: `header`, `nav`, `main`, `section`, `article`, `footer`)
- CSS3
  - Flexbox for the navbar, buttons and cards
  - CSS Grid for the hero, inventory, projects and contact layouts
  - Positioning: `sticky` navbar, `absolute` badge inside a `relative` portrait card, `z-index`
  - CSS variables for the colour system
  - Transitions on hover, `@keyframes` animations (float, blink, loading bar)
  - Media queries for tablet and mobile

## Projects

### CampusEats

A campus canteen queue minimizer. Students pre-order food from their rooms and track it in real time, while kitchen staff manage the order flow from a live dashboard. It cuts down the long rush-hour queues.

- **Stack:** Python, Flask, SQLite, HTML, CSS, vanilla JavaScript (Jinja2 templating)
- **Student view:** https://gradient-rush.onrender.com/
- **Staff view:** https://gradient-rush.onrender.com/staff

### Student Portal

A dark-themed web interface built with HTML and CSS that shows student profiles, skill lists and weekly academic schedules, plus a course registration form with mode selection.

- **Stack:** HTML, CSS
- **Live demo:** https://transcendent-cajeta-db5de4.netlify.app/

## Project structure

```text
portfolio/
├── index.html
├── style.css
├── README.md
└── images/
    └── profile.png
```

## Run it locally

1. Clone the repo:
   ```bash
   git clone https://github.com/jubinmazumder-afk/REPO-NAME.git
   ```
2. Open the folder and double-click `index.html` in your browser.

No install or build step is needed.

## AI usage

I used Claude (an AI assistant) to help plan and generate the first version of the code, then went through it to understand and explain how it works.

## Author

**Jubin Mazumder**

- Email: jubinmazumder@gmail.com
- GitHub: https://github.com/jubinmazumder-afk
- LinkedIn: https://www.linkedin.com/in/jubin-mazumder-299658420
