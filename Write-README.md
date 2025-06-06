# How to Write README.md
Quick guide to Markdown symbols and syntax 

## Markdown Symbols
### Headings
Use # symbols (1 to 6) for headers:

``` md
# H1 (Main Title)
## H2 (Subheading)
### H3
#### H4
##### H5
###### H6
```

### Text Formatting

| Format         | Markdown Syntax             | Output              |
|----------------|-----------------------------|---------------------|
| Bold           | `**bold**` or `__bold__`     | **bold**            |
| Italic         | `*italic*` or `_italic_`     | *italic*            |
| Bold + Italic  | `***bold italic***`          | ***bold italic***   |
| Strikethrough  | `~~strikethrough~~`          | ~~strikethrough~~   |
| Inline code    | `` `code` ``                 | `code`              |
| Blockquote     | `> quote`                    | > quote             |

### Code Blocks
(```) for multiline code (with optional language):

```md
```python
python def hello():
print("Hello, Markdown!") ```
```

### Lists
#### Unordered List
```md
- Item 1
- Item 2
  - Sub-item
* Item 3
+ Item 4
  ```

#### Ordered List
```md
1. First
2. Second
   1. Sub-item
```

### Links
```md
[Github/abcofdevops](https://github.com/abcofdevops/github/new/main)
```

### Images
```md
![Alt text](https://example.com/image.png)
```

### Horizontal Line
```md
---
```

### Tables
```md
| Name  | Age |
|-------|-----|
| John  | 20  |
| Alice | 30  |
```

### Task Lists
```md
- [x] Write README
- [ ] Push to GitHub
```

### Escape Characters
Use \ to escape symbols:

```md
\*not italic\*
```
