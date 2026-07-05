# Personal website of Dr. Himani Garg

A free personal academic website built with Jekyll, designed to be hosted on **GitHub Pages** at no cost, forever.

Your site will live at: **https://YOUR-USERNAME.github.io**

---

## Part 1 — Put the site online (about 10 minutes, one time only)

1. **Create a free GitHub account** at https://github.com/signup (skip if you have one). Choose a professional username — it becomes your web address, e.g. `himanigarg` → `himanigarg.github.io`.

2. **Create the repository.** Click the **+** in the top-right → **New repository**.
   - Repository name: exactly `YOUR-USERNAME.github.io` (e.g. `himanigarg.github.io`)
   - Set it to **Public**
   - Do NOT tick "Add a README"
   - Click **Create repository**

3. **Upload the site files.** On the new repository page, click the link **"uploading an existing file"**.
   - Unzip the folder you downloaded from Claude on your computer
   - Drag ALL its contents (the folders `_layouts`, `_posts`, `assets`, `news`, and the files `_config.yml`, `index.html`, `research.md`, etc.) into the browser window
   - Important: drag the *contents* of the folder, not the folder itself
   - Click **Commit changes**

4. **Wait 1–2 minutes**, then open `https://YOUR-USERNAME.github.io` in your browser. Your website is live.

That's it. No payment, no ads, no renewal.

---

## Part 2 — Publish a new post (2 minutes, whenever you like)

Every news item is one small text file in the `_posts` folder. To add one:

1. Go to your repository on github.com → open the `_posts` folder
2. Click **Add file → Create new file**
3. Name it with the date first: `2026-09-15-my-conference-talk.md`
4. Paste this template and edit it:

```
---
layout: post
title: "Invited talk at the Turbulence Workshop"
location: "Stockholm, Sweden"
---

On 15 September I gave an invited talk on turbulent heat transfer
over additively manufactured surfaces at the Turbulence Workshop
in Stockholm. Great discussions with colleagues from KTH and Chalmers.
```

5. Click **Commit changes**. The post appears on your site's News page and homepage within a minute.

**Tip:** you can also come back to Claude with "write a post about conference X" and paste the result in.

### Adding a photo to a post

1. Open the `assets/img` folder in your repository → **Add file → Upload files** → upload your photo (e.g. `stockholm2026.jpg`)
2. In your post, add this line where you want the image:

```
![Speaking at the Turbulence Workshop](/assets/img/stockholm2026.jpg)
```

---

## Part 3 — Everyday edits

All pages are plain text files you can edit directly on github.com (open the file → click the pencil icon → edit → Commit changes):

| To change… | Edit this file |
|---|---|
| Homepage bio | `index.html` |
| Research themes | `research.md` |
| Publication list | `publications.md` |
| Teaching info | `teaching.md` |
| CV summary | `cv.md` |
| Your CV PDF | Upload a new `Himani_Garg_CV.pdf` into `assets/` |
| Colors / fonts | `assets/css/style.css` |

## Optional: a custom domain later

If one day you want an address like `himanigarg.info`, buy just the domain (~$10/year from any registrar) and point it to GitHub Pages under Settings → Pages → Custom domain. Everything else stays free. This is entirely optional — the `github.io` address is permanent and professional.
