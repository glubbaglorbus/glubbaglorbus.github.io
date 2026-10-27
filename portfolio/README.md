# Matt Livingstone – Portfolio

Plain HTML + CSS site (no frameworks, no build step). Red/black style.

## Folder layout

```
index.html      Home / About Me
projects.html   3 projects, each with STAR + reflection
skills.html    Technical skills, soft skills, certifications
resume.html     Web resume + PDF download button
contact.html    Email, LinkedIn, GitHub, contact form
css/style.css   All the styling (colours are at the top)
images/         Photos and screenshots (replace the placeholders)
downloads/      Resume PDF and project proposal PDF
```

## Fill-in checklist (yellow dashed boxes on the site)

1. Search every .html file for `[` and replace each yellow bracketed note with your own text.
   Delete the `<mark class="fill">` and `</mark>` tags around it when you do.
2. Replace `YOUR-GITHUB-USERNAME`, `YOUR-LINKEDIN-NAME`, `YOUR-REPO-NAME`, `YOUR-CAPSTONE-REPO`
   and `YOUR_EMAIL@example.com` (index, projects, resume, contact pages).
3. Replace the placeholder images in `images/` with your own files, **same file name, same .jpg ending**.
4. Replace the two placeholder PDFs in `downloads/` (same file names).
5. Do not put a phone number, home address or references on the site (the rubric says not to).
6. When you change anything later, update the "Last updated" date in the footer of every page.

## Putting it on GitHub Pages (free)

1. Sign in at github.com. Click **+** (top right) > **New repository**.
2. Name it `portfolio` (or `YOURUSERNAME.github.io` for a shorter address). Set it to **Public**. Click **Create repository**.
3. On the empty repo page click **uploading an existing file**.
4. Unzip this folder on your computer. Open it, select EVERYTHING inside (index.html, css, images, downloads...)
   and drag it into the browser window. Keep the folders. Wait for the upload to finish.
5. Click **Commit changes**.
6. Go to **Settings** > **Pages** (left menu). Under **Build and deployment** set Source to
   **Deploy from a branch**, Branch **main**, folder **/ (root)**, then **Save**.
7. Wait 1-2 minutes and refresh. The page shows your link:
   `https://YOURUSERNAME.github.io/portfolio/`
8. Open that link in a private/incognito window to check it works for someone who is not logged in,
   click every nav link, then submit the link in Brightspace.

## Updating the site later

Open the file in your repo, click the pencil icon, edit, **Commit changes**. The site refreshes in a minute or two.
To replace an image: open the `images` folder > **Add file** > **Upload files**, using the same file name.

## Optional: contact form that sends without opening an email app

The form uses `mailto:`, which opens the visitor's email app. For a form that sends directly:
make a free account at formspree.io, create a form, and change the form's `action` in
`contact.html` to the URL they give you (looks like `https://formspree.io/f/abcdwxyz`).
Also remove `enctype="text/plain"` from that form tag.
