# Adil Farash - Developer Portfolio

A responsive, high-performance, and visually stunning developer portfolio website built using standard modern web technologies (HTML5, Vanilla CSS, and modern client-side JavaScript).

## Features
- **Modern Responsive Design**: Optimized for desktops, tablets, and mobile devices.
- **System-First Light/Dark Mode**: Built-in system theme detection, with a manual theme toggle and persistence using `localStorage`. No flash of unstyled content (FOUC).
- **Interactive Experience Timeline**: Showcases career journey in a clean, vertical chronological layout.
- **Categorized Skill Grid**: Highlights expertise across languages, web technologies, ERP frameworks, databases, and integrations.
- **Featured Projects**: Highlights development work with clean interactive cards.
- **Interactive Contact Form**: Custom client-side form validation and success message simulation.

## File Structure
- `index.html`: Contains the structural semantic markup and inline theme switcher.
- `style.css`: Contains CSS variables, modern styling layout, responsive rules, transitions, and forced-colors high contrast support.
- `script.js`: Handles interactive details such as navbar shrink, theme switching, typing effect, and contact validation.

## Customization
1. **Social Links**: Search for the social links in `index.html` (under the `#hero` and `footer` section) and replace the `href` attributes with your actual LinkedIn and GitHub profile links.
2. **Contact Form**: Update the form attributes in `index.html` to integrate with a service like Formspree or Netlify Forms if you host it.
3. **Projects**: Add or replace projects in the `#projects` section inside `index.html`.

## How to Run Locally
To run this website locally without CORS issues and with correct asset loading, start a local server.

### Option 1: Python (Built-in)
Run the following command in this directory:
```bash
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

### Option 2: Node.js (npx)
Run:
```bash
npx serve
```
or
```bash
npx live-server
```
