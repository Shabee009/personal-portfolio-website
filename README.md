# Personal Portfolio Website

A beginner-friendly, responsive personal portfolio built with **HTML, CSS and vanilla JavaScript**. It includes an introduction, about section, skills, sample projects and a contact form that prepares an email in the visitor's default email application.

## Preview

Open `index.html` in your browser. No build tools or package installation are required.

## Features

- Responsive layout for desktop, tablet and mobile
- Sticky navigation with a mobile menu
- Hero/introduction section
- About and skills sections
- Three sample project cards
- Contact form with basic required-field validation
- Contact form prepares a `mailto:` message (it does not store or send messages on a server)
- Current year in the footer
- Semantic HTML and accessible labels

## Project structure

```text
personal-portfolio-website/
├── index.html
├── README.md
├── css/
│   └── style.css
├── js/
│   └── script.js
└── assets/
    └── (add your images and other assets here)
```

## Run locally

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`, or open it in a browser.
4. Edit the HTML, CSS and JavaScript files with a code editor such as Visual Studio Code.

Optional: install the **Live Server** extension in Visual Studio Code, right-click `index.html`, and choose **Open with Live Server**.

## Personalise the website

Before publishing, replace the sample details:

1. In `index.html`, change **Alex Morgan**, the introduction, location, about text and skills to your own details.
2. Replace the sample project names and descriptions with your real projects. Add links to each project or its GitHub repository when available.
3. Replace `hello@example.com` in both `index.html` and `js/script.js` with your email address.
4. Adjust the skill descriptions and progress-bar widths in `index.html`. Use honest values that represent your current experience.
5. Add your own images to `assets/` and reference them with paths such as `assets/profile.jpg`.
6. Update the page title and description in the `<head>` section.

## Screenshot guidance

Take screenshots after opening the site in a browser. Suggested images for your GitHub repository:

- `screenshots/home-desktop.png` — full desktop hero and navigation
- `screenshots/about-skills.png` — about and skills sections
- `screenshots/projects.png` — project cards
- `screenshots/mobile-view.png` — mobile layout (use browser developer tools to select a phone-sized viewport)

To capture a screenshot:
1. Open the page in Chrome or another browser.
2. Set the browser window to the desired size.
3. Use **Win + Shift + S** on Windows (or your operating system's screenshot shortcut).
4. Save the image in a new `screenshots/` folder in the project.
5. You can embed a screenshot in this README by adding, for example:

   ```md
   ![Portfolio home page](screenshots/home-desktop.png)
   ```

Do not add empty or pretend screenshots; capture the actual running website.

## Upload to GitHub (website)

### Option A — GitHub website (easiest)

1. Sign in at [GitHub](https://github.com/).
2. Click **New repository**.
3. Enter a repository name such as `personal-portfolio-website`.
4. Choose **Public** if you want everyone to see it, or **Private** if you do not.
5. Click **Create repository**.
6. In the new repository, choose **Add file → Upload files**.
7. Upload the project files and folders. Keep `index.html` at the repository root.
8. Enter a commit message such as `Add personal portfolio website`.
9. Click **Commit changes**.

### Option B — Git commands

Install Git, open a terminal in this project folder, and run:

```bash
git init
git add .
git commit -m "Add personal portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/personal-portfolio-website.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username. If Git says the remote already exists, check it with `git remote -v` rather than adding it again.

## Publish with GitHub Pages

1. Open your repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Click **Save**.
6. Wait for GitHub Pages to publish. Your site address will look like:

   `https://YOUR-USERNAME.github.io/personal-portfolio-website/`

Keep `index.html` in the repository root so GitHub Pages can find the home page.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (DM Sans and Space Grotesk)

## Notes

- This is a static front-end project. It has no database, login system or server-side contact form.
- The contact form uses the visitor's email application. For a production contact form, connect a trusted form service or build a backend.
- Google Fonts requires an internet connection; system fonts will be used if the font service is unavailable.

## License

You may use, edit and customise this starter project for personal and learning purposes.
