# 💻 A Guide to Skyline Chili

Starter files for an independent multi-page HTML assignment. You will build a three-page fan
guide to **Skyline Chili**, the Cincinnati chili parlor, from the text and photos in this repo.
Along the way, you will show what you know about linking pages, organizing a site into folders,
and choosing the right HTML element for each piece of content.

There is no follow-along video for this assignment. You build it on your own, and a walkthrough
video unlocks in Canvas after you submit. There is no CSS either, so the pages will look plain
in the browser. **That is expected.**

> [!NOTE]
> `.editorconfig`, `.gitattributes`, `.gitignore`, `.noai`, and the `.github` and `.idea`
> folders are setup files that keep assignments consistent. Leave them alone. `index.txt`,
> `menu.txt`, `our-story.txt`, and the `images` folder are your starter files.

## 📋 Assignment Requirements

> [!IMPORTANT]
> **Start here: [read ASSIGNMENT.md →](.github/ASSIGNMENT.md)**

It has the overview, the requirements, the grading criteria, and a final checklist. Read it before you start, and check it again before you submit.

## ✅ At a Glance

Every assignment follows the same steps. Each guide has screenshots for every step.

| Step | What you do                                                                | Guide                                         |
|------|----------------------------------------------------------------------------|-----------------------------------------------|
| 0    | **First assignment only:** install and set up WebStorm                     | [WebStorm Setup](.github/WEBSTORM_SETUP.md)   |
| 1    | Create your repo from this template, clone it, and make a `develop` branch | [Getting Started](.github/GETTING_STARTED.md) |
| 2    | Build your three pages from the `.txt` content files                       | [Where Your Files Go](#-where-your-files-go)  |
| 3    | Commit and push often, then turn on GitHub Pages                           | [Publishing](.github/PUBLISHING.md)           |
| 4    | Open a pull request into `main` and submit its URL in Canvas               | [Submitting](.github/SUBMITTING.md)           |

## 📂 Where Your Files Go

This time you create every page yourself. The text for each page is in its own `.txt` file
(`index.txt`, `menu.txt`, and `our-story.txt`), and the photos and logos are in `images`.
Create the pages with **exactly** these names and folders, because the links between pages
depend on them:

```
index.html
menu.html
our-story/
    index.html
images/
index.txt
menu.txt
our-story.txt
```

`index.html` has to be in the root folder, or GitHub Pages will show a 404. The Our Story page
is in its own `our-story` folder, so its links and images need `../`.

## 🤖 AI Policy

Work on this assignment must be your own. Do not use AI coding assistants — including
GitHub Copilot, Cursor, ChatGPT, Claude, or JetBrains AI Assistant — to generate,
complete, or rewrite your code.

You should be able to explain any line of your submission. You may be asked to do so.

This repo includes a `.noai` file, which disables JetBrains AI Assistant for the project
in IDEs like WebStorm. Leave it in place. It is a reminder of the policy above, not a
substitute for it — following the policy is still your responsibility.

> [!NOTE]
> The `.noai` file does **not** turn off WebStorm's local Full Line code completion. Turn that
> off yourself as part of the [one-time setup](.github/WEBSTORM_SETUP.md) (step 5).

> [!CAUTION]
> Late or missing submissions are graded on what is in the pull request at the deadline, so push your final commits
> before you submit.
