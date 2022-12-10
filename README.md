# Horiseon 

## Code Refactoring

### Deployment / Code Repository

[Live deployment](https://tweetingcynical.github.io/code-refactor-html5/)

[Repository](https://github.com/TweetingCynical/code-refactor-html5)

### Scope and Purpose

Review all HTML and CSS code and refactor to meet accessibility standards.

### Overview of Code Changes

index.html:
- Added title;
- Added alt tags to all content and benefits images;
- Removed div tags, replaced with header, nav, section, article and aside tags;
- Fixed missing id so that nav buttons follow correct links;
- Added developer comments to identify key sections of code;
- Removed redundant closing img tags.

style.css:
- Used new header, nav, article, aside tags to match html references;
- Reordered code sections to match sequence in html;
- Removed redundant code by combining article with the same styling under new single class rules;
- Repeated for aside styling;
- Added developer comments to identify key sections of code;
- **Reduced CSS styling from 200 lines of code to 136.**

## Suggested future changes

- Add (position: fixed) and (z-index: 2) properties to header bar to ensure it stay visible when user scrolls;
- Fix to header banner styling to allow for reduced browser width without losing intended optics.

## Screenshot

Working version of site should look like this:
![Site Screenshot](./assets/images/screenshot.jpg)

## License

MIT License

Copyright (c) 2022 TweetingCynical

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.