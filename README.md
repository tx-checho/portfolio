# My Portfolio

A personal portfolio site built with HTML, CSS, and JavaScript. Hosted on GitHub Pages.

## Pages
- **Home** (`index.html`) — Intro, bio, photo
- **PBR Work** (`pbr.html`) — Ms. Frade / CTE projects
- **AP CS Work** (`cs.html`) — Ms. Teal / AP Computer Science projects
- **Contact** (`contact.html`) — School email

---

## How to Put This on GitHub Pages

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have one.

### Step 2 — Create a new repository
- Click the **+** button → **New repository**
- Name it: `portfolio` (or anything you want)
- Make it **Public**
- Click **Create repository**

### Step 3 — Upload your files
- Click **Add file** → **Upload files**
- Drag and drop ALL files from this folder (index.html, pbr.html, cs.html, contact.html, style.css, main.js)
- Click **Commit changes**

### Step 4 — Enable GitHub Pages
- Go to your repo's **Settings** tab
- Scroll to **Pages** in the left sidebar
- Under **Source**, select **Deploy from a branch**
- Set branch to `main` and folder to `/ (root)`
- Click **Save**

### Step 5 — Your site is live!
After ~1 minute, your site will be at:
`https://YOUR-USERNAME.github.io/portfolio/`

---

## Customizing Your Portfolio

### Change your name
Open `index.html` and find `Your Name` — replace it everywhere (also update `YN` in the nav logo).

### Add your photo
1. Create an `images/` folder
2. Drop your photo in there (e.g. `me.jpg`)
3. In `index.html`, replace the `<div class="photo-placeholder">` block with:
   ```html
   <img src="images/me.jpg" alt="Your Name" />
   ```

### Add project screenshots
Same idea — put screenshots in `images/` and replace the `<div class="media-placeholder">` blocks with:
```html
<img src="images/pbr-project1.png" alt="Project screenshot" />
```

### Add more projects
Copy one of the `<article class="project-block">` blocks and paste it below, changing the number and content.

### Update your email
Open `contact.html` and replace `yourname@students.uplifteducation.org` with your real school email (in both the `href` and the visible text).
