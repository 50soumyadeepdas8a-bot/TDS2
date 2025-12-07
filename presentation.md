---
marp: true
title: Product Documentation Presentation
paginate: true
theme: default
math: mathjax
style: |
  /* Custom styling like a simple custom theme */
  section {
    font-family: "Segoe UI", system-ui, sans-serif;
    color: #222;
  }

  h1, h2 {
    color: #0A6EBD;
  }

  .title-slide {
    text-align: center;
  }

  .note-box {
    background: #FFF8C6;
    padding: 10px;
    border-radius: 8px;
    border: 1px solid #F2D24C;
  }

  footer {
    font-size: 12px;
    color: #666;
  }
---

<!-- _class: title-slide -->

# Product Documentation  
## Marp Presentation

**Contact:** `50soumyadeepdas8a@gmail.com`

This slide uses a **Marp directive**: `<!-- _class: title-slide -->`.

<footer>Page ${pageNumber}</footer>

---

# Why Use Marp?

- Markdown source files  
- Easy to track in **Git / version control**  
- Export to **PDF / PPTX / HTML**  
- Supports:
  - Custom styling
  - Background images
  - **LaTeX mathematical equations**

<footer>Page ${pageNumber}</footer>

---

<!-- _backgroundImage: url('https://images.unsplash.com/photo-1518770660439-4636190af475') -->
<!-- _backgroundSize: cover -->

# Background Image Slide

<div class="note-box">
This slide uses a Marp background image directive:<br>
<code>_backgroundImage</code> and <code>_backgroundSize</code>.
</div>

<footer>Page ${pageNumber}</footer>

---

# Version Control Workflow

```bash
git init
git add presentation.md
git commit -m "Add Mar
