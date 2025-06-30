
# 🧠 Markdown Tips for Programmers

Markdown (`.md`) is super simple but powerful once you know a few tricks. Here are some essential and pro tips to make your notes clean, readable, and GitHub-worthy:

---

## 🧠 **Markdown Basics**

### 1. **Headings**
Use `#` to define headings (like titles and subtitles):

```md
# H1 - Title
## H2 - Section
### H3 - Subsection
```

### 2. **Bold & Italics**
```md
**bold text**
*italic text*
***bold and italic***
```

### 3. **Lists**

#### • Unordered list:
```md
- Item 1
- Item 2
  - Sub-item
```

#### 1️⃣ Ordered list:
```md
1. First
2. Second
```

### 4. **Code**
#### • Inline:
```md
Use the `ls` command to list files.
```

#### • Code block:
Use triple backticks (```) with optional language for syntax highlighting:
\`\`\`bash
git status
git commit -m "Initial commit"
\`\`\`

---

## 📚 **Organizing Notes**

### 5. **Links**
```md
[Google](https://www.google.com)
```

### 6. **Images**
```md
![Alt text](image.jpg)
```

### 7. **Horizontal Line**
```md
---
```

### 8. **Quotes**
```md
> This is a blockquote.
```

---

## ✨ **Pro Tips**

### ✅ Checklists (great for TODOs!)
```md
- [x] Learn Markdown
- [ ] Build a to-do app
```

### ⬇️ Collapsible Sections (GitHub only)
```md
<details>
<summary>Click to expand</summary>

Your hidden content goes here.

</details>
```

### 🧩 Syntax Highlighting
GitHub and editors like VS Code will highlight code if you specify the language:

```python
def hello():
    print("Hello, world!")
```

---

## 🔧 Tools to Preview Markdown
- **VS Code**: Press `Ctrl+Shift+V` to preview
- **Obsidian**: Free and beautiful
- **Typora**: Smooth live preview
- **StackEdit / Dillinger**: Online Markdown editors
