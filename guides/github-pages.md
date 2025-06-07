# Publishing Your Portfolio with GitHub Pages

Once you’ve created your e-portfolio repository, you can publish it as a website using GitHub Pages. This is a free hosting service built into GitHub that allows you to share your work more accessibly, whether for an application, a course assessment, or public outreach.

---

## What you need

To publish your portfolio, you’ll need:

- A GitHub repository containing your files (e.g. the one created from the `soss-portfolio-template`)
- A `README.md`, `index.md`, or `.html` file in the root folder
- A public repository (GitHub Pages only works with public repos unless you’re on a paid plan)

---

## How to publish your site

### 1. Open your repository’s settings

- Go to your e-portfolio repository on GitHub
- Click the **Settings** tab (top right of the page)

> Note: You may need to scroll right to find the Settings tab.

---

### 2. Enable GitHub Pages

- In the left-hand menu, scroll down to **“Pages”**
- Under **“Source”**, choose:
  - **Branch**: `main`
  - **Folder**: `/ (root)` (or `/docs` if you’ve placed your site content there)
- Click **Save**

GitHub will build your site automatically.

---

### 3. View your site

After a short wait (usually under a minute), GitHub will display a link to your live website, something like:

https://yourusername.github.io/your-repo-name/

Click the link to view your published portfolio.

---

## Troubleshooting

If your site doesn’t appear:

- Double-check that your repository is set to **public**
- Confirm you’ve selected the correct branch (`main`) under the Pages settings
- Make sure there’s a valid Markdown or HTML file in the root folder
- Refresh the page or wait a few minutes as sometimes the first build takes a little longer

---

## Tips for students

- You can use your `README.md` as the homepage, or add a more detailed `index.md`
- Changes to your content are reflected on the site each time you push updates
- Use simple formatting, headings, and links to make your site easy to navigate

---

## Further reading

- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [GitHub Pages & Quarto](https://quarto.org/docs/publishing/github-pages.html) (for R/Quarto users)
