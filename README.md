# The Scripture of the Human Dao — GitHub Pages reader

Public-reader edition generated from the author's current authoritative Library revision 7, Chapters 1–110 (2026-10-23 snapshot). The older internal title and subtitle remain unchanged in canonical source metadata; **the public title is The Scripture of the Human Dao**. This package does NOT contain the private story bible, future plot, unaccepted chapters, or private collaborative review files.

## Publish

1. Create a GitHub repository (for example `The-Scripture-of-the-Human-Dao`).
2. Upload **all** of `index.html`, `style.css`, `app.js`, `data/chapters.json`, and `.nojekyll` to the repository's **root**. GitHub lets you upload multiple files through **Add file → Upload files**. You can also unzip this package, then upload the files and folder. Do not upload the outer ZIP as the only repository file.
3. In the repository choose **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. After successful deployment GitHub gives the public site address; it will generally resemble `https://USERNAME.github.io/The-Scripture-of-the-Human-Dao/` if the repository uses that name. This is an example, not a deployed link.
5. To refresh the site, replace `data/chapters.json` with a newly exported, validated current version, commit changes, and check the live page.

## Daily automation boundary

GitHub Pages republishes when files are committed to the publishing branch. **This repository does not by itself fetch the canonical ChatGPT Library state or upload daily chapters.** ChatGPT's existing 18:00 writing automation remains independent, and no GitHub write permission or push integration has been configured. Once an authenticated GitHub connector or CI runner is connected and approved, the existing writing task can mirror a release **only after** the canonical source commit succeeds. Never publish provisional plans or partial batches.

## Editorial exchange

A public reader can be retrieved by Claude (through normal HTML or the chapter JSON URL) without Google Drive permissions. Reading does not supply write access. A reciprocal reader for Claude's novel similarly allows ChatGPT to examine published chapters. A truly unattended two-model exchange and joint draft publishing needs verified GitHub write access/appropriate API orchestration; published pages alone are not two-way communication.
