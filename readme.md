
[Markdown Guide](https://www.markdownguide.org)!

This Markdown cheat sheet provides a quick overview of all the Markdown syntax elements. It can’t cover every edge case, so if you need more information about any of these elements, refer to the reference guides for [basic syntax](https://www.markdownguide.org/basic-syntax) and [extended syntax](https://www.markdownguide.org/extended-syntax)


[host a markdown file](https://stackoverflow.com/questions/37770620/how-to-include-markdown-md-files-inside-html-files)
```
<!-- Lightweight client-side loader that feature-detects and load polyfills only when necessary -->
<script src="https://cdn.jsdelivr.net/npm/@webcomponents/webcomponentsjs@2/webcomponents-loader.min.js"></script>

<!-- Load the element definition -->
<script type="module" src="https://cdn.jsdelivr.net/gh/zerodevx/zero-md@1/src/zero-md.min.js"></script>

<!-- Simply set the `src` attribute to your MD file and win -->
<zero-md src="README.md"></zero-md>
```

Basic Syntax

# H1
## H2
### H3

Bold
**bold text**

Italic
*italicized text*

Blockquote
> blockquote

Ordered List
1. First item
2. Second item
3. Third item

Unordered List
- First item
- Second item
- Third item

Code
`code`

Horizontal Rule
---

Link
[Markdown Guide](https://www.markdownguide.org)

Image
![alt text](https://www.markdownguide.org/assets/images/tux.png)

Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

Fenced Code Block
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Footnote
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

Heading ID
My Great Heading {#custom-id}

Definition List
term
: definition

Strikethrough
~~The world is flat.~~

Task List
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
