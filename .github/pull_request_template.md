---
name: code review PR
about: A template PR for contributing to this project
---

<!--
  make this PR easy to find:

  - assign yourself
  - use labels
  - request a review when you open a PR
-->

## Checklists

<!-- general checks -->

- [ ] All CI checks pass
- [ ] the branch is up to date with `main`/`master`
- [ ] the code works when pulled and run locally

## Markdown

<!-- markdown-specific checks -->

- [ ] the markdown source is formatted
- [ ] spelling and grammar is correct in all text
- [ ] The markdown looks correct when you preview the file
- [ ] all links and images work

### HTML

- [ ] the code is well-formatted
- [ ] the HTML code passes validation
- [ ] there are no inline styles (example: `style='color: red;'`)
- [ ] there are no `<style>` tags with CSS, all styles are hrefs
- [ ] there is no inline JavaScript (example: `onclick='doSomething()'`)
- [ ] there are no `<script>` tags with JS, all JS is in an separate file
- [ ] `id`s are used for JavaScript only, not for CSS
- [ ] semantic tags are used
- [ ] spelling and grammar is correct in all site content

### CSS

- [ ] the code is well-formatted
- [ ] passes all the linting checks
