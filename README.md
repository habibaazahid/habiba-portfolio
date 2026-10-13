# Habiba Zahid | Portfolio

Personal portfolio website of **Habiba Zahid**: AI Engineer, AI agents & automation developer, and frontend developer. Computer Science student at IU International University of Applied Sciences, Germany.

**Live site:** https://habibaazahid.github.io/REPO-NAME/ <!-- replace REPO-NAME with this repository's name -->

---

## About this project

A fast, single-page portfolio built with plain HTML, CSS and JavaScript. There is no framework, no build step and no dependencies, so it loads quickly and can be hosted anywhere.

It presents my projects, experience, skills, certifications and contact details in one clean, responsive page.

## Features

- **Responsive design** for phones, tablets and desktops
- **Light and dark mode** with the visitor's choice remembered
- **Animated hero** with an interactive network background drawn on a canvas
- **Smooth scroll experience**: eased anchor navigation, progress bar, staggered reveal animations and back-to-top button
- **Filterable project gallery** (AI Agents, Full-Stack, Frontend, Database)
- **Resume timeline, technical skills and certifications** with a "show all" toggle
- **Downloadable CV** (PDF)
- **Contact form** that opens the visitor's email app, plus direct links to LinkedIn, GitHub and email
- **Accessible by default**: keyboard-friendly navigation, visible focus states, semantic HTML, and reduced-motion support for visitors who prefer less animation

## Sections

| Section | What it shows |
| --- | --- |
| Home | Introduction and headline |
| Portfolio | Tools I build with, project gallery and featured case studies |
| Resume | Education, volunteering, experience, technical skills and certifications |
| About | Short bio and key numbers |
| Contact | Contact form and links |

## Tech stack

- HTML5
- CSS3 (custom properties, grid, flexbox, no preprocessor)
- Vanilla JavaScript (no libraries)
- [Inter](https://rsms.me/inter/) typeface, bundled locally

## Project structure

```
.
├── index.html                  # Page markup
├── css/
│   └── style.css               # All styles, including dark mode and responsive rules
├── js/
│   └── main.js                 # Navigation, theme, filters, animations, hero canvas, form
├── assets/
│   ├── Habiba_Zahid_CV_2026.pdf
│   └── fonts/                  # Inter (Light, Regular, Medium, SemiBold, Bold)
└── README.md
```

## Run locally

No installation is needed.

```bash
git clone https://github.com/habibaazahid/REPO-NAME.git
cd REPO-NAME
```

Then open `index.html` in your browser. To serve it over a local server instead:

```bash
# Python
python3 -m http.server 8000

# or Node
npx serve .
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. After a minute or two the site is live at `https://<username>.github.io/<repo-name>/`.

It also works on Netlify, Vercel, Cloudflare Pages or any static host. Upload the folder as it is.

## Customising

If you fork this project to build your own portfolio:

- **Content:** edit the text, links and projects directly in `index.html`.
- **Colours:** change the CSS variables at the top of `css/style.css` (`--accent` is the main blue; dark mode values are under `:root[data-theme="dark"]`).
- **CV:** replace `assets/Habiba_Zahid_CV_2026.pdf` and update the filename in the Download CV button.
- **Contact form:** it uses a `mailto:` link, so no backend is required. To receive messages directly in an inbox, connect the form to a service such as Formspree or Web3Forms.
- **Project covers:** the project tiles are generated colour covers. To use screenshots, add an `<img>` inside the relevant `.cover` element.

## Contact

- **Email:** habibaazahid@gmail.com
- **LinkedIn:** [linkedin.com/in/habibazahid03](https://www.linkedin.com/in/habibazahid03)
- **GitHub:** [github.com/habibaazahid](https://github.com/habibaazahid)

## Credits

- Layout and visual style inspired by Colorlib's **Rezume** template. All code in this repository was written from scratch.
- Typeface: [Inter](https://rsms.me/inter/) by Rasmus Andersson, used under the SIL Open Font License 1.1.

## License

The source code is released under the [MIT License](https://opensource.org/licenses/MIT). My CV, written content, project descriptions and personal details are © Habiba Zahid and are not licensed for reuse.
