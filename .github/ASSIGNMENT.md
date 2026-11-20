# 📄 A Guide to Skyline Chili

## 🎯 Overview

Build a three-page fan guide to Skyline Chili on your own, and show what you've learned about
building a multi-page website with HTML.

Skyline Chili has served Cincinnati chili since 1949, and one of its parlors is just down
Ludlow Avenue from UC's Clifton campus. In this assignment you will turn the text in
`index.txt`, `menu.txt`, and `our-story.txt` and the photos in `images` into **A Guide to
Skyline Chili**, a small fan site with three pages:

- **Home**, which introduces Skyline and the Clifton parlor
- **Menu**, which explains the 3-way, 4-way, 5-way and coneys, with links that jump to each one
- **Our Story**, which tells how Skyline started, kept in its own folder

This is an **independent** assignment. There is no follow-along video, and the content files
are plain text with no hints about which elements to use. Deciding that is part of the assignment.
After you submit, a walkthrough video unlocks in Canvas so you can compare your choices with
mine.

There is no CSS in this assignment, so the pages will look plain when you are finished.
**That is expected.**

### 🧠 What You'll Show

- Build a shared `header`, `nav`, and `footer`, and repeat them on every page
- Link pages together with relative paths, including into and out of a folder (`../`)
- Jump to a section of a page with `id` and `#` links, and create an email link
- Choose between `section`, `article`, and `aside` based on what the content is
- Group a photo with its caption using `figure` and `figcaption`
- Choose between `ul` and `ol` for list content, based on whether the order matters
- Add contact information with `address`
- Show special characters such as © and & with character entities
- Give every page its own `title`, `meta` description, and a favicon

## 📋 Requirements

### Every page

- [ ] Has a `DOCTYPE`, `html` (with `lang="en"`), `head`, and `body`
- [ ] The `head` has `<meta charset="utf-8">`, a viewport `meta`, the page's own `title`, and
      its own `meta` description from that page's content file
- [ ] The `head` links to the favicon with `<link rel="icon">`
- [ ] Has the same `header`, `nav`, `main`, and `footer` as every other page
- [ ] The `header` shows the Skyline logo, and the logo links to the Home page
- [ ] Has exactly one `h1`, and the rest of the headings follow the page's outline

### Links

- [ ] The `nav` is a `ul`, with each link in its own `li`
- [ ] Every page's `nav` links to all three pages with **relative** paths
- [ ] On `our-story/index.html`, every link to another page and every image uses `../`
- [ ] The Menu page has links at the top that jump to the 3-way, 4-way, 5-way, and coneys
      sections, using matching `id`s
- [ ] The email address in the footer is a `mailto:` link to `help@skylinechili.com`
- [ ] Link text says where the link goes. No "click here"

### Page structure

- [ ] Each main part of a page is a `section` with its own heading
- [ ] At least one `article` is used for content that would make sense on its own
- [ ] Every page has at least one `aside` for a side note that isn't part of the main content
- [ ] Every list in the content files is a `ul` or `ol`, with each item in its own `li`. Use
      `ol` when the order matters and `ul` when it doesn't

### Images

- [ ] Every photo marked in a content file is on its page, with the correct path
- [ ] Each photo and its caption are wrapped in a `figure`, with the caption in a `figcaption`
- [ ] Every image, including the logo, has `alt` text that describes what it shows
- [ ] Every image displays on the live site

### Contact info and special characters

- [ ] The Clifton parlor's name, address, and phone number in the footer are inside an
      `address`
- [ ] The © in every footer is written as `&copy;`
- [ ] Every & in the page text is written as `&amp;`

### ✅ Before You Submit

Check the following:

- [ ] All of the text from each content file is on its page, and no labels from the
      content files (such as "Page title:") appear on any page
- [ ] Your pages use the exact names and folders in the [README](../README.md#-where-your-files-go)
- [ ] On the **live site**, you clicked every `nav` link on every page, including from Our
      Story, and each one opened the right page
- [ ] The jump links on the Menu page land on the right sections
- [ ] Every image shows up, on a computer and on your phone
- [ ] Each browser tab shows that page's own title and the favicon
- [ ] Every page passes the [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
      with no errors
- [ ] You saved all of your files
- [ ] The site is live on GitHub Pages and the URL is in your pull request

## 📂 Starter Files

| File / Folder | Purpose |
| --- | --- |
| `index.txt`, `menu.txt`, `our-story.txt` | The text for each page, plus its title and description, where each photo goes, and the header and footer text every page shares. **Don't turn these into web pages.** Copy their text into the pages you create. |
| `images/` | Skyline's logos, photos of the food and the Clifton parlor, and the favicon. |

You create these pages:

| File | Page |
| --- | --- |
| `index.html` | Home |
| `menu.html` | Menu |
| `our-story/index.html` | Our Story |

## 🧮 Grading

| Criteria | What earns full credit | Points |
| --- | --- | --- |
| **Links and paths** | The `nav` is a list on every page and every link works, including the `../` links from Our Story; the jump links land on the right Menu sections; the `mailto:` link is correct; link text says where each link goes. | 8 |
| **Page structure** | Correct document structure; the same `header`, `nav`, `main`, and `footer` on every page; one `h1` per page with headings in order; `section`, `article`, and `aside` used where they fit the content. | 8 |
| **Content elements** | Photos are in `figure`s with `figcaption`s and descriptive `alt` text; lists use `ul` or `ol` correctly; the Clifton contact info is in an `address`; © and & use character entities. | 4 |
| **Head metadata** | Each page has its own `title` and `meta` description, and the favicon shows on every page. | 4 |
| **Published and submitted** | GitHub Pages site is live and loads correctly; pull request into `main` is open with the live URL in the description; PR URL submitted in Canvas. | 1 |
| **Total** |  | **25** |

## 📚 Resources

- Your CE3: Ocarina of Time Guide repo, which uses every element this assignment needs
- [MDN — HTML elements reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)
- [MDN — Creating links](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Creating_links)
- [MDN — Document and website structure](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content/Structuring_documents)
- [MDN — `figure`](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/figure)
- [MDN — Entity (special characters)](https://developer.mozilla.org/en-US/docs/Glossary/Entity)
- [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input): paste your
  HTML in to catch unclosed tags

## 🆘 Getting Help

Ask during class or office hours, or post on the Canvas discussion board. Because this is an
independent assignment, I can point you to the right idea, but I won't tell you which element
to use.

Before you ask, check these common problems:

- **A link goes to a "404" or "file not found" page?** Check the file name and folder in the
  `href`, letter for letter. From Our Story, every link to another page needs `../`.
- **Images work on Home but not on Our Story?** Our Story is one folder down, so its `src`
  needs `../images/` instead of `images/`.
- **A jump link doesn't move the page?** The `href` after the `#` must match the `id` exactly,
  including dashes.
- **The email link opens nothing?** That's normal in some browsers and in WebStorm's built-in
  preview if no email app is set up. Check that the `href` starts with `mailto:`.
- **The favicon doesn't show?** Browsers cache favicons. Check the path in the `link`, then
  reload the page or open it in a private window.
- **The © shows up as strange characters?** Add `<meta charset="utf-8">` to the `head`, and use
  `&copy;`.
- Did you save every file? Are your opening and closing tags in the correct places, and nested
  properly? Are there quotation marks around your attribute values?

---

The AI policy and submission instructions are in the [README](../README.md).
