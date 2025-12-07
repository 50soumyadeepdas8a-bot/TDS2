---
marp: true
title: Product Documentation Presentation
paginate: true
theme: default
style: |
  /* Custom styling on top of the default theme */

  section {
    font-family: "Segoe UI", system-ui, sans-serif;
    color: #222;
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

  .small {
    font-size: 14px;
  }

  footer {
    font-size: 12px;
    color: #666;
  }
---

# Product Documentation  
### Technical Writer Presentation

**Email:** `50soumyadeepdas8a@gmail.com`

---

# Why Use Marp?

- Write slides in simple **Markdown**
- Easy to keep in **Git / version control**
- Export to **PDF / PPTX / HTML**
- Supports:
  - Custom styling
  - Background images
  - Math (LaTeX)

<footer>Page ${pageNumber}</footer>

---

# Background Image Slide

![bg](https://images.unsplash.com/photo-1518770660439-4636190af475)

<div class="box">
This slide uses a background image.  
You can replace the link with your own image URL or a local file path.
</div>

---

# Version Control Basics

We can keep this presentation in a Git repository:

```bash
git init
git add presentation.md
git commit -m "Add product documentation slides"
git remote add origin https://example.com/your/repo.git
git push -u origin main
