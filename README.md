<div align="center">

# 📘 Grav Learn2 with Git Sync

### Ready-to-Run Skeleton Package

<p><em>An open, collaborative documentation site – easy to read and easy to edit, with content in portable Markdown files you control.</em></p>

[![Grav Discord Chat](https://img.shields.io/discord/501836936584101899.svg?logo=discord&colorB=728ADA&label=Grav%20Discord%20Chat)](https://chat.getgrav.org) [![Latest Release](https://img.shields.io/github/v/release/hibbitts-design/grav-skeleton-learn2-with-git-sync?style=flat-square&label=Release)](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/releases/latest) [![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/blob/master/LICENSE) [![PHP](https://img.shields.io/badge/PHP-%3E%3D8.0.2-8892BF?style=flat-square&logo=php&logoColor=white)](https://learn.getgrav.org/17/basics/requirements)

<p>Try the <a href="https://demo.hibbittsdesign.org/grav-learn2-git-sync/">demo</a></p>

<p>A free, open-source package built on <a href="https://getgrav.org">Grav CMS</a> and the <a href="https://github.com/hibbitts-design/grav-theme-learn2-git-sync">Learn2 with Git Sync</a> theme, with Markdown file-based content, a built-in Admin panel, and no database required.</p>

<a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot-dark.webp"><img alt="Chapter page for Basics with numbered sidebar navigation, search, and an Edit this Page link" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot.webp" width="49%"></picture></a> <a href="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot-2.webp"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot-2-dark.webp"><img alt="Documentation page with chapter navigation in the sidebar, an Edit this Page link, and previous and next arrows" src="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/refs/heads/master/screenshots/screenshot-2.webp" width="49%"></picture></a>

<p>Learn2 with Git Sync – Chapter page (left) and documentation page (right)</p>

</div>

A complete, pre-configured package for an open documentation site – a place to publish guides, manuals, or course notes that others can read and help improve. Content is stored as simple Markdown files you can keep locally, with a built-in Admin panel for browser-based editing and no database required. Runs on nearly any web hosting service.

## What Sets It Apart

- **Open authoring built in** – Git Sync keeps the site in step with GitHub or a similar Git service, with "Edit this Page" links to each page's Markdown source
- **Made for reading documentation** – chapters with numbered sidebar navigation, previous and next page arrows, and reading history
- **Search included** – instant search, plus tag-aware full-text search with the included TNTSearch plugin
- **Stay up to date** – Atom/RSS feeds so readers can follow documentation changes
- **Visual styles** – 2026 Refresh or Classic, with Dark Mode off, on, or following the visitor's system setting
- **Portable by design** – your content is plain Markdown files on your server, ready to move to any tool or host if your needs change

## When is Grav Learn2 with Git Sync a Good Candidate?

Grav Learn2 with Git Sync is a good fit when you:

- Want an open documentation site with your own hosting and domain
- Value Git-based, open authoring so others can suggest and make improvements
- Prefer a clean, readable layout focused on navigation and search

Other options might be better when you:

- Want zero-server publishing directly from GitHub – consider [Docsify-This](https://docsify-this.net)
- Need a full knowledge base with user accounts, comments, or approval workflows
- Prefer fully visual drag-and-drop page builders over Markdown-based editing

## Quick Start

Learn2 with Git Sync is best suited for authors and educators comfortable with web hosting and folder-based content. An online Admin panel is included for browser-based editing – no code editor required.

### Pre-flight Checklist
1. Confirm your web server meets [Grav's requirements](https://learn.getgrav.org/17/basics/requirements) (PHP 8.0.2 or higher)
2. Have your web server login credentials ready (username and password)

### Installation Steps
1. **Download** the [Learn2 with Git Sync Skeleton](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/releases/latest/download/grav-skeleton-learn2-with-git-sync.zip) package (a Grav 1.7 version is also available on the [release page](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/releases/latest))
2. **Unzip** the package onto your desktop
3. **Copy** the entire Grav Learn2 with Git Sync folder to your web server
4. **Open your browser** and go to your site's URL
5. **Create your site administrator account** when prompted
6. **You're done!** – press the preview icon in the Admin Panel to view your site

> [!TIP]
> When copying the Grav Learn2 with Git Sync folder to your web server, copy the **entire folder** – it contains hidden files (such as `.htaccess`) that are not selected by default. Omitting these hidden files can cause problems when running Grav.

## Site Setup

- **Site name** – in the Admin Panel under **Configuration → Site**; it appears at the top of the sidebar
- **Chapters and pages** – each chapter (Basics, Intermediate, Advanced) is a top-level folder using the Chapter page type, with its pages inside using the Docs page type. Folder numbers set the order in the sidebar; add pages with **Pages → Add**
- **Previous and next arrows** – pages in the `docs` category are linked in order; the theme's Default Taxonomy Category option adds it to new pages automatically
- **Search** – instant search works out of the box; for full-text search, build the TNTSearch index from the Admin Panel after adding content
- **Look and options** – under **Themes → My Theme**: visual style and Dark Mode, Git link position, document versioning, and home URL (see the [Learn2 with Git Sync theme README](https://github.com/hibbitts-design/grav-theme-learn2-git-sync#theme-options) for all options)
- **Git Sync and "Edit this Page"** – set up the Git Sync plugin in the Admin Panel; the "Edit this Page" link then points to each page's source automatically

## Requirements

- PHP >= 8.0.2
- Grav CMS 1.7 or 2.0 (included in the package)

## Support

### Contact and Support
- Share your feedback in the [Learn2 with Git Sync Survey](https://docs.google.com/forms/d/e/1FAIpQLSdOAQL_4m56zIvmTQMszTtS6U3pVQ0nZlaxnZfPspEy-i6eOg/viewform)
- Follow [@hibbittsdesign@mastodon.social](https://mastodon.social/@hibbittsdesign) on Mastodon for updates
- 👩🏻‍💻🧑🏻‍💻 Join the [Grav Discord](https://chat.getgrav.org) and often find me there
- Add a ⭐️ [star on GitHub](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync) to the Learn2 with Git Sync project repository
- For bugs or feature requests, [open an issue](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/issues) on GitHub

### Professional Services

By leveraging his extensive UX design expertise and systems-oriented approach, Paul helps teams and individuals utilize open content in education and publication settings. Professional services include user experience and workflow consulting, premium support subscriptions, workshops, and custom development. Interested? Send a note to [paul@hibbittsdesign.org](mailto:paul@hibbittsdesign.org).

## License

MIT – Hibbitts Design
