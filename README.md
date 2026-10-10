# Ankita Karbhari — Professional Portfolio

A responsive, static portfolio website for job and internship applications.

## Included
- Responsive design for mobile, tablet and desktop
- About, education, skills, projects, learning/experience, and contact sections
- LinkedIn and GitHub links
- Includes your supplied professional portrait at `assets/ankita-photo.jpg`
- No build tools or dependencies required

## Add your professional photo
1. Choose a clear, professional headshot.
2. Name it `ankita-photo.jpg`.
3. Put it inside the `assets` folder.
4. Keep the face centered; the image will be cropped to fit the portrait frame.

## Personalise before applying
- Add your professional email address in the contact section.
- Replace each generic GitHub project link with the exact repository URL.
- Add exact certificate links and dates.
- Confirm project descriptions and technologies reflect what you personally implemented.
- If you have a resume PDF, add it to the project and link a "Download Resume" button.

## Preview locally
Open `index.html` in your browser. You can also use the VS Code Live Server extension.

## Publish free with GitHub Pages
1. Create a new **public** repository named `ankitakarbhari.github.io` on GitHub.
2. Upload the contents of this folder (the `index.html` file must be at the repository root).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the deployment and open `https://ankitakarbhari.github.io`.

GitHub Pages publishes static files from a repository. The final public URL becomes available only after you create the repository and enable Pages.

## Git commands (run from this folder after creating the repository)
```bash
git init
git add .
git commit -m "Create professional portfolio"
git branch -M main
git remote add origin https://github.com/ankitakarbhari/ankitakarbhari.github.io.git
git push -u origin main
```

If the repository already exists, don't run `git remote add origin` a second time; check `git remote -v` first.
