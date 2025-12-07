---
marp: true
title: Product Documentation Presentation
paginate: true
theme: gaia
style: |
  section {
    font-family: "Segoe UI", system-ui, sans-serif;
  }

  h1, h2 {
    color: #0A6EBD;
  }

  .box {
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

<!-- _class: lead -->

# Product Documentation  
### Technical Writer Presentation

**Email:** `50soumyadeepdas8a@gmail.com`

This slide uses a **Marp directive**: `<!-- _class: lead -->`.

---

# Why Use Marp?

- Plain **Markdown** source  
- Easy to keep in **Git / version control**  
- Export to **PDF / PPTX / HTML**  
- Supports:
  - Custom styling
  - Background images
  - **LaTeX mathematical equations**

<footer>Page ${pageNumber}</footer>

---

<!-- _backgroundColor: #dde8ff -->

# Background Image Slide

![bg](https://images.unsplash.com/photo-1518770660439-4636190af475)

<div class="box">
This slide has a background image and custom CSS styling.
</div>

---

# Version Control Basics

```bash
git init
git add presentation.md
git commit -m "Initial documentation presentation"
git push
