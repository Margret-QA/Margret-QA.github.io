# QA & Test Management Portfolio — GitHub Pages

A responsive, multi-page HTML/CSS/JavaScript portfolio based on the supplied Test Manager CV.

## Preview locally

Open `index.html` in your browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Publish on GitHub Pages (free)

1. Create a GitHub account at https://github.com/signup.
2. Create a **public** repository named `YOURUSERNAME.github.io` (replace `YOURUSERNAME` with your exact GitHub username). If you prefer a different repository name, your site will use `https://YOURUSERNAME.github.io/REPOSITORY/` instead.
3. Upload the contents of this ZIP to the **root** of your repository. Upload the `assets` and `projects` folders as folders. Do **not** upload the outer `qa-portfolio` folder itself.
4. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
5. After deployment, visit `https://YOURUSERNAME.github.io/` (or the repository-specific URL). Allow a few minutes for publishing.
6. Update any text in HTML files directly through GitHub's file editor and commit changes to republish.

## Site structure

- `index.html`: Home, professional introduction, achievements
- `experience.html`: Career timeline
- `skills.html`: Technical expertise
- `projects.html`: Portfolio projects overview
- `projects/*.html`: Individual project plans
- `education.html`: Education and training
- `contact.html`: Professional contact
- `assets/style.css`: Responsive light visual theme
- `assets/script.js`: Mobile menu and dynamic footer year

## Personalization

- Update the display name and contact details in the generated HTML pages as needed.
- The project pages are marked **Planned**. Replace with actual evidence only after completing each project.
- No personal phone number, resume PDF, internal documents, or client-confidential materials are included.
- To add a CV download, place a sanitized public PDF in `assets/` and link to it from the website.
- A GitHub username is not required in the source code; GitHub Pages will use the account/repository name.

## Security and privacy

Review public contact details before publishing. Never commit secrets, private client data, internal systems screenshots, or proprietary code. The professional email address is sourced from the supplied CV; replace it if you prefer a dedicated public email.
