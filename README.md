# HTML-CSS Template

> I am creating this HTML-CSS template for future reference.
> Also, this is containing steps of basic linter setup.
> - The `Screenshot`, `Built With`, `Acknowledgments` and some of the other sections are just the format for this template.
> - You can simply modify the following sections:
    1. Heading
    2. Description
    3. Screenshot
    4. Name of the Project everywhere
    5. Built with
> - Remove:
    7. Linter Setup
    8. Auto-fix linter errors
    9. Acknowledgments (if not required)

# Screenshot

### Mobile

![Mobile The Next Web](mobile-art.png)

### Desktop

![desktop The Next Web](articles.png)

## Built With

- HTML
- CSS
- Bootstrap

## Live Demo

[Live Demo Link](https://vagyasri.github.io/HTML-CSS-template/)

## Author

👤 **Bhagyashree Patra**

- GitHub: [@Vagyasri](https://github.com/Vagyasri)
- Twitter: [@Vagyasri](https://twitter.com/Vagyasri)
- LinkedIn: [Bhagyashree Patra](https://www.linkedin.com/in/bhagyashree-patra-029bb059/)

## Getting Started

### Prerequisites:

- Web browser
- Code Editor
- Live Server Extension

### Linter Setup:

#### Set-up GitHub Actions

- Create a `.github/workflows` folder and add a copy of [`.github/workflows/linters.yml`](.github/workflows/linters.yml) to that folder.

#### Set-up linters in your local env

- The npm package manager is going to create a `node_modules` directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a `.gitignore` file and add `node_modules` to it as below:

    ```
    node_modules/
    ```

#### Webhint

- Run `npm install --save-dev hint@6.x`
- Copy [`.hintrc`](.hintrc) to the root directory of your project.

#### Stylelint

- Run `npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x`
- Copy [`.stylelintrc.json`](.stylelintrc.json) to the root directory of your project.

#### For Sass
If you prefer to work with SCSS files, you need to perform a few modifications to the linter configuration files:
  - In the file `linters.yml` [line 48](https://github.com/Vagyasri/HTML-CSS-template/blob/main/.github/workflows/linters.yml#L48) replace `"**/*.{css,scss}"` with `"**/*.scss"`
  - Use `npx stylelint "**/*.scss"` to lint you SCSS files and not the generated CSS

### Cloning the repo to your local system (If you already have git, installed in your system):

- [Copy this link](https://github.com/Vagyasri/HTML-CSS-template.git)
- Open your terminal or command line
- Run "git clone [Paste this link](https://github.com/Vagyasri/HTML-CSS-template.git)"
- Open the folder with your code editor
- Now You can edit the code and check the changes in the browser using Live Server

### Check linter errors:

- Install npm: `npm install`
- For Webhint/HTML: Run `npx hint .`
- For Stylelint/CSS: Run `npx stylelint "**/*.{css,scss}"`

### Auto-fix linter errors:

- For Stylelint(terminal): Run `npx stylelint --fix style.css`
- For Stylelint(vscode): Press `CMD+Shift+P` and select `Stylelint: Fix all auto-fixable Problems`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Start by:

- Forking the project
- Cloning the project to your local machine
- cd into the project directory
- Run `git checkout -b your-branch-name`
- Make your contributions
- Push your branch up to your forked repository: Run `git push -u origin your-branch-name`
- Open a Pull Request with a detailed description to the development branch of the original project for a review

Feel free to check the [issues page](https://github.com/Vagyasri/HTML-CSS-template), contribute to the Project by creating an issue.


## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments
- Project originally taken from The Odin Project
- Project inspired by Microverse Program
- Thanks for this Website Design "PATASHULE"
- Matthew Njuguna & Sam Achola (Design from Behance)
