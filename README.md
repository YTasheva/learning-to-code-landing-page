# Learning to code landing page

## Table of contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [User Story](#user-story)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

-  Code refactor an existing site to make it more accessible.

### User Story

- AS A marketing agency
- I WANT a codebase that follows accessibility standards
- SO THAT our site is optimized for search engines

### Acceptance Criteria

- Semantic HTML elements can be found throughout the source code
- HTML elements follow a logical structure independent of styling and positioning
- Image and icon elements contain accessible alt attributes
- Heading attributes fall in sequential order
- Title elements contain a concise, descriptive title
- Application’s links all function correctly.
- The application’s CSS selectors and properties are consolidated and organized to follow semantic structure.
- The application’s CSS file is properly commented.
- Application deployed at live URL
- Application loads with no errors.
- Application GitHub URL submitted.
- GitHub repository that contains application code.
- Application resembles (at least 90%) screenshots provided in the challenge instructions.
- Repository has a unique name.
- Repository follows best practices for file structure and naming conventions.
- Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
- Repository contains multiple descriptive commit messages.
- Repository contains quality README file with description, screenshot, and link to deployed application.
  
### Screenshot

![01-html-css-git-challenge-demo](https://github.com/YTasheva/learning-to-code-landing-page/assets/148258557/c55f1039-d751-49e6-a8b8-dc12c08132b8)


### Links

- Solution URL: https://github.com/YTasheva/learning-to-code-landing-page
- Live Site URL: https://ytasheva.github.io/learning-to-code-landing-page
## My process

### Build with

- Semantic HTML
- CSS

### What I learned

- It is best to build HTML with semantic elements to increase readability and provide a good reading experience.
- Image elements need to have accessible alt attributes, and image elements do not need a closing tag.
- Add the id attribute to the heading that needs to be navigated.
- A unique title is required.
- The heading attributes fall in sequential order.
- Use class to reduce or merge duplicates in CSS.

To see how I add code snippets, see below:

```html
<title>Learning to code landing page</title>
<header><nav>...</nav></header>
<h1>Hori<span>seo</span>n</h1>
<h2>Online Reputation Management</h2>
<section id="search-engine-optimization">...</section>
```
```css
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```

## Author

- Github - [Yuliya Tasheva](https://github.com/YTasheva)
