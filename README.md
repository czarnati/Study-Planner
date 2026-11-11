# Study Planner website

A one-page site where people can download Study Planner for Mac.

```
website/
├── index.html                 the page
├── assets/                    icon, favicon, screenshot
└── downloads/StudyPlanner.dmg the installer (universal: Apple Silicon + Intel)
```

## Putting it online for free (GitHub Pages)

1. Make a free account at https://github.com.
2. Click **+ → New repository**, name it `study-planner`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in everything **inside** this `website` folder (`index.html`, `assets`, `downloads`, this README), then click **Commit changes**.
4. Open **Settings → Pages**. Under *Branch*, choose **main** and **/ (root)**, then click **Save**.
5. After a minute, your site is live at `https://YOUR-USERNAME.github.io/study-planner/`.

## Releasing a new version

1. Rebuild the app and make a new `StudyPlanner.dmg`.
2. Upload it to `downloads/` in the repository, replacing the old one.
3. Update the version number in the line under the download button in `index.html`.
