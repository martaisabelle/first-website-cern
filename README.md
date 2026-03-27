## First Website Recreation – Study Project

Recreation of the first website ever created, originally hosted at CERN (`http://info.cern.ch`).  
This is a minimal, static HTML project designed to study early web structure, information architecture, and the historical evolution of the World Wide Web.

## Project overview

This repository implements a faithful recreation of the original homepage of the first website, preserving:

- The same **link destinations** as the real `info.cern.ch` page (CERN history, W3 project, line‑mode browser, etc.).  
- A **clean, semantic HTML structure** without CSS or JavaScript.  
- A custom favicon (`icon.png`, labeled as `1st Web`) created as a minimal visual reference.

This is **not an official site** by CERN or the World Wide Web project.  
It is strictly a **recreation for educational purposes**, focused on understanding how the web looked and worked in its earliest days.

## Technology stack

- **HTML 5** – vanilla, semantic, no frameworks.  
- **Static assets** – favicon in PNG format, served directly from the `src/` directory.  

No build tool, bundler, or dependency manager is required.

## Deploy

The project is deployed on Vercel and can be accessed live at:

- **Live site:** [https://first-website-coral.vercel.app/](https://first-website-coral.vercel.app/)

This deployment is done directly from the GitHub repository, without any build step, since the project is fully static.

## How the project runs

The project is hosted as a static site, meant to be opened through a standard browser:

- Opening `index.html` directly loads the homepage locally.  
- Clicking the links opens the **original CERN pages** in the browser, since those resources are hosted externally.

The project can be deployed to any static host (GitHub Pages, Vercel, Netlify, etc.) from the root folder without additional configuration.

## Key external links (original sources)

- Main first website page: [http://info.cern.ch](http://info.cern.ch)  
- Line‑mode browser simulator: [http://line-mode.cern.ch/www/hypertext/WWW/TheProject.html](http://line-mode.cern.ch/www/hypertext/WWW/TheProject.html)  
- History of the birth of the Web: [https://home.web.cern.ch/topics/birth-web](https://home.web.cern.ch/topics/birth-web)  
- About CERN: [https://home.web.cern.ch/about](https://home.web.cern.ch/about)

## Notes – What was learned

Rebuilding this historical page from the ground up gave practical insights into:

- **Semantic HTML structure** and how early sites prioritized content and links over styling, making them simple, fast, and highly accessible.  
- **Information architecture** of the web: organizing sections, documents, and outbound links in a way that guides users through complex material without visual clutter.  
- **Cross‑origin resource usage** – keeping the real CERN pages as external links instead of trying to host them, respecting ownership and avoiding duplication.  
- **Minimalist design for accessibility** – how a text‑based, image‑light layout can be usable and performant even on very old hardware and limited networks.  
- **Ethical reuse of historical content** – clearly documenting attribution, educational purpose, and non‑commercial usage in the codebase and README.

This project reinforced habits such as:

- Keeping the codebase **small, readable, and self‑documented**, so it’s easy to revisit or share.  
- Using descriptive filenames and a clear folder structure (`src/` for static assets), making the project feel organized and maintainable.  
- Writing a detailed `README.md` that explains the context, technology choices, and learning goals, turning the project into a proper portfolio piece.

## Credits

- Original first website and content: [CERN](http://info.cern.ch)  
- Recreation, code, and custom favicon: **Marta Isabelle**  
- GitHub profile: [https://github.com/martaisabelle](https://github.com/martaisabelle)  
- Live deployment: [https://first-website-coral.vercel.app/](https://first-website-coral.vercel.app/)

## License / usage

This project is intended **exclusively for educational use**:

- The code is open for study, experimentation, and adaptation.  
- The **original content and links** belong to CERN and should be accessed through the official URLs.  
- This repository is **not affiliated with CERN** or the official World Wide Web project.

No part of this codebase is meant to be passed off as official or commercial software.  
Use it as a learning resource, playground, or portfolio piece showcasing the understanding of web history and vanilla HTML.
