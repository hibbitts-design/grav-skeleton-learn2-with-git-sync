# Learn2 with Git Sync Skeleton

[![Demo](https://img.shields.io/badge/Demo-OpenPublishingSpace-blue.svg?style=flat-square)](https://demo.hibbittsdesign.org/grav-learn2-git-sync/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/hibbitts-design/grav-theme-learn2-git-sync/blob/master/LICENSE)

[![Discord](https://img.shields.io/discord/501836936584101899.svg?logo=discord&colorB=728ADA&label=Discord%20Chat)](https://chat.getgrav.org)

**Learn2 with Git Sync** Learn2 with Git Sync, a sample documentation site using the Learn2 Git Sync theme. Includes Admin Panel and TNTSearch Plugins along with RSS/Atom Feeds. Built with the open source modern file-based [Grav CMS](http://getgrav.org).

📚 Information and Documentation
---
http://learn.hibbittsdesign.org/learn2withgitsync

💻 Grav Learn2 with Git Sync Screenshot
---

![Learn2 with Git Sync Screenshot](https://github.com/paulhibbitts/github-repo-images/blob/master/smartmockups_learn2_with_git_sync.png?raw=true)

✅ Learn2 Theme with Git Sync Features
---

* Integrated support for Git Sync (i.e. view/edit pages in GitHub)
* Support for RSS feed (great for getting documentation updates)
* Custom Theme visual styles
* Support for Taxonomy 'tag' searching with TNTSearch Plugin
* Enhanced support for the [Presentation Plugin](https://github.com/OleVik/grav-plugin-presentation)

### Base Learn2 Theme Features

* Lightweight and minimal for optimal performance
* Fully responsive with off-page mobile navigation
* SCSS based CSS source files for easy customization
* Built specifically for providing easy to read documentation
* [Font Awesome](http://fontawesome.io/) icon support
* Viewed page tracking
* Integrated support for documentation content sourced/maintained via GitHub

📄 Supported Page Templates
---

* "Docs" template
* "Chapter" template
* Error view template

### Video Walkthrough of Learn2 with Git Sync Configuration
[![Learn2 with Git Sync Configuration](https://github.com/paulhibbitts/github-repo-images/blob/master/video-learn2-git-sync-config.png?raw=true)](https://www.youtube.com/watch?v=bmQjWmwS9S8)  
_Video 1. Learn2 with Git Sync Configuration_

🔧 Configuration
---

```
top_level_version: false
home_url:
github:
    enabled: true
    position: top
    tree: https://github.com/getgrav/grav-skeleton-rtfm-site/blob/develop/
```

| Setting           | Child Setting | Description                                                                                                            |
| :-----            | :-----        | :-----                                                                                                                 |
| top_level_version |               | When set to `true`, displays level icons and numbered lists.                                                           |
| home_url          |               | Enables you to enter a different URL link from the logo (ex: http://google.com)                                        |
| github            | enabled       | Can be set to `true` or `false`. When set to `true`, it generates the **Edit this page** link to GitHub for each page. |
| github            | position      | Sets the position for the GitHub edit link. Can be set to `top` or `bottom`.                                           |
| github            | tree          | Sets the tree by which your site's content is based. Generally the repo your site's content is pulled from.            |

### Basic Setup for a New Grav Site

The simplest way to install the Learn2 Git Sync theme with sample content for Grav is to download and install the Learn2 with Git Sync Skeleton package:

1. [Download Learn2 with Git Sync Skeleton](http://getgrav.org/downloads/skeletons#extras)
2. Unzip the package into your web root folder.
3. Point your browser at the folder.
4. Job done!

**TIP:** Check out the [general Grav Installation Instructions](http://learn.getgrav.org/basics/installation) for more details on this process.

💬 Share Your Feedback
---
* Complete the [Learn2 with Git Sync Survey](https://goo.gl/forms/ywKK8XqBJ5HZ0lCv2)
