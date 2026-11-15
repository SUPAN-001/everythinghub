# EverythingHub

A responsive, dark-themed, searchable directory of useful web resources. It is a static website: no backend, database, account, tracking, build step, or paid hosting is required.

## Run locally
1. Download and unzip the project.
2. Open `index.html` in a modern browser.

For local development, you can also run a static server from this folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Customize
- Edit the `resources` array near the bottom of `index.html` to add, remove, or update directory entries.
- Each entry has `name`, `category`, `icon`, `desc`, `url`, and `type`.
- Categories and search filters are generated automatically from that data.

## Publish for free
You can publish this static site with GitHub Pages:
1. Create a public GitHub repository.
2. Upload `index.html`, `README.md`, and `LICENSE`.
3. In repository Settings → Pages, select deployment from the `main` branch and root folder.
4. Save; GitHub will provide the public website URL.

Other static hosts can also serve these files.

## Open-source notes
This project is released under the MIT License. The directory links to third-party websites; it does not host or own their content. External services have their own terms, pricing, privacy policies, and licences. Check those before using or redistributing their content.
