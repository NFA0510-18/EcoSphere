# EcoSphere

A website for UN Sustainable Development Goal 13: Climate Action, built for the Web Design and Development coursework (4COSC011W). The site focuses on real, everyday actions that individuals, communities and businesses can take against climate change.


## About

EcoSphere is a static website (HTML, CSS and JavaScript, no frameworks). It uses one shared HTML template and a single global stylesheet so every page has a consistent look, navigation and footer.

## Features

- Splash screen with a JavaScript countdown and automatic redirect to the Home page
- Interactive Gallery and an Action Impact Simulator that scores the actions you pick
- JavaScript-driven User Profile builder and a graphical SVG Sitemap
- Feedback form with live validation, and a Team page
- Four individual content pages, one per team member
- Consistent navigation, a "Back to Home" button and a scroll-reveal "Go to Top" button
- Accessible markup: semantic HTML, alt text on all images, keyboard-focusable controls
- All pages pass the W3C Nu HTML Checker with zero errors

## Tech

- HTML5, CSS3, vanilla JavaScript
- Global stylesheet: style.css
- Continuous integration on every push (GitHub Actions): Prettier format check + W3C HTML/CSS validation

## Run locally

No build step is needed. Either:

- Open index.html in a web browser, or
- Serve the folder with a simple local server:

```
python3 -m http.server 8000
# then open http://localhost:8000
```

## Project structure

```
index.html            Entry point (splash screen)
home.html, gallery.html, ais.html, profile.html,
feedback.html, team.html, sitemap.html      Main pages
content_ST1..4.html   Individual content pages
pageEditor_ST1..4.html, validation_ST1..4.html
style.css             Global stylesheet
splash.css            Splash-only styles
images/               Site graphics and icons
additionals/          Content images and media
```


## Validation

Every page has been checked with the W3C Nu HTML Checker and returns no errors or warnings. Evidence is recorded on each student's validation page.

## Done by: Nicola Fernando

## Licence

Coursework project for the University of Westminster. For educational use only.
