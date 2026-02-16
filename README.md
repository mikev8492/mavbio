# Portfolio site for MavBio LLC. 
### Created using Astro JS Portfolio template:

## File Structure:
```
└── 📁src
    └── 📁components
        ├── CallToAction.astro
        ├── ContactCTA.astro
        ├── Footer.astro
        ├── Grid.astro
        ├── Hero.astro
        ├── Icon.astro
        ├── IconPaths.ts
        ├── MainHead.astro
        ├── Nav.astro
        ├── Pill.astro
        ├── PortfolioPreview.astro
        ├── Skills.astro
        ├── ThemeToggle.astro
    └── 📁content
        └── 📁work
            ├── Automated-labels.md
            ├── cell-count.md
            ├── informatics-system.md
    └── 📁layouts
        ├── BaseLayout.astro
    └── 📁pages
        └── 📁work
            ├── [...slug].astro
        ├── 404.astro
        ├── about.astro
        ├── index.astro
        ├── work.astro
    └── 📁styles
        ├── global.css
    └── content.config.ts
```
## Overview:
Project pages are dynamically generated in the `pages/work` route by rendering Markdown files in `content/work`. 
To add a new project to the portfolio page, I just need to create a new Markdown file with the required parameters.  

Read more about [dynamic routes](https://docs.astro.build/en/core-concepts/routing/#dynamic-routes).
### Astro JS Portfolio template:
```sh
npm create astro@latest -- --template portfolio
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/portfolio)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/portfolio)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/portfolio/devcontainer.json)


## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
