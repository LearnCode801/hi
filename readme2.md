Markdown is a lightweight markup language used for formatting text. It’s commonly used for documentation, README files, and content creation on platforms like GitHub, GitLab, and many others. Below is a comprehensive guide to Markdown syntax.

---

## **Basic Markdown Syntax**

### **1. Headers**
Headers are created using the `#` symbol. The number of `#` indicates the level of the header.

```markdown
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

### **2. Emphasis**
You can apply italic or bold formatting to text.

- **Italic:**
  - Wrap the text with either asterisks `*` or underscores `_`.

```markdown
*This is italic*
_This is also italic_
```

- **Bold:**
  - Wrap the text with double asterisks `**` or double underscores `__`.

```markdown
**This is bold**
__This is also bold__
```

- **Bold and Italic:**
  - Combine three asterisks or underscores.

```markdown
***This is bold and italic***
___This is also bold and italic___
```

### **3. Blockquotes**
Use the `>` symbol to create blockquotes. You can nest them by adding more `>` symbols.

```markdown
> This is a blockquote.
>> This is a nested blockquote.
```

### **4. Lists**
- **Unordered Lists:**
  - Use `*`, `-`, or `+` followed by a space to create unordered lists.

```markdown
* Item 1
* Item 2
  * Sub-item 2.1
  * Sub-item 2.2
```

- **Ordered Lists:**
  - Use numbers followed by a period (`.`).

```markdown
1. Item 1
2. Item 2
   1. Sub-item 2.1
   2. Sub-item 2.2
```

### **5. Links**
You can create hyperlinks with the following syntax:

```markdown
[Link Text](https://example.com)
```

- For reference-style links:

```markdown
[Link Text][1]

[1]: https://example.com "Optional Title"
```

### **6. Images**
Images use similar syntax to links but with an exclamation mark (`!`).

```markdown
![Alt Text](https://example.com/image.jpg)
```

- Reference-style images:

```markdown
![Alt Text][1]

[1]: https://example.com/image.jpg "Optional Title"
```

### **7. Code**
- **Inline Code:**
  - Use backticks (\`code\`) to format inline code.

```markdown
Here is some `inline code`.
```

- **Block Code:**
  - Use triple backticks (\``` ```) or indentation of 4 spaces for code blocks.

\```
```
function helloWorld() {
  console.log("Hello, World!");
}
```
```

- **Language-Specific Syntax Highlighting:**
  - After the opening triple backticks, specify the language for syntax highlighting (e.g., `javascript`).

```markdown
```javascript
function helloWorld() {
  console.log("Hello, World!");
}
```
```

### **8. Horizontal Rules**
Create a horizontal rule using three or more dashes (`---`), asterisks (`***`), or underscores (`___`).

```markdown
---
***
___
```

---

## **Extended Markdown Syntax**

Many platforms support additional Markdown features that go beyond the basic syntax.

### **1. Tables**
Tables can be created using pipes (`|`) and dashes (`-`) to separate columns and rows.

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

You can align table content using colons (`:`):
- Left-aligned: `:---`
- Center-aligned: `:---:`
- Right-aligned: `---:`

```markdown
| Left Align | Center Align | Right Align |
|:-----------|:------------:|------------:|
| Row 1      | Row 1        | Row 1       |
| Row 2      | Row 2        | Row 2       |
```

### **2. Task Lists**
You can create a task list using square brackets (`[ ]` for unchecked and `[x]` for checked items).

```markdown
- [x] Task 1
- [ ] Task 2
- [x] Task 3
```

### **3. Strikethrough**
Strikethrough is created by wrapping text with double tildes `~~`.

```markdown
~~This is strikethrough~~
```

### **4. Footnotes**
You can add footnotes using square brackets and the caret (`^`).

```markdown
This is a footnote example[^1].

[^1]: Here is the footnote content.
```

### **5. Definitions**
You can create a definition list with terms and descriptions.

```markdown
Term
: Definition of the term

Another Term
: Another definition
```

### **6. Emoji**
You can insert emojis using colons around the emoji name:

```markdown
I love Markdown! :heart:
```

For a full list of emojis supported on GitHub, you can check [GitHub Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

### **7. HTML in Markdown**
You can also use raw HTML in Markdown for more advanced formatting options.

```markdown
<p>This is a paragraph using HTML.</p>
```

### **8. Automatic Links**
Markdown supports automatic link formatting. URLs and email addresses will be automatically converted into clickable links.

```markdown
https://example.com
user@example.com
```

---

## **GitHub-Flavored Markdown (GFM)**
GitHub provides additional Markdown features, called GitHub-Flavored Markdown, which includes:

1. **Task Lists** (as mentioned above).
2. **Tables** (with automatic formatting).
3. **Syntax Highlighting** for code blocks.
4. **URL Auto-Linking** for easy navigation.
5. **SHA References**, Issue Numbers, and @mentions (specific to GitHub).

Examples:
- Reference commits: `16c999e`
- Reference issues: `#42`
- Mention a user: `@username`

---

## **Markdown Cheat Sheet**

### Text Formatting
```markdown
# Header 1
## Header 2
### Header 3

**Bold** or __Bold__
*Italic* or _Italic_
~~Strikethrough~~

> Blockquote

1. Ordered list item 1
2. Ordered list item 2

- Unordered list item
* Unordered list item

`Inline code`

```
Code block
```

[Link Text](https://example.com)

![Alt Text](https://example.com/image.jpg)
```

### Extended Elements
```markdown
- [x] Task 1
- [ ] Task 2

| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Row 2    |

This is a footnote example[^1].

[^1]: Footnote content.
```

---

Markdown is incredibly versatile and widely used in both technical and non-technical writing. It allows for clear, structured documents with minimal effort. Many platforms have adopted Markdown with additional features, so always check platform-specific extensions when needed.

Let me know if you need more details on any specific part of Markdown!