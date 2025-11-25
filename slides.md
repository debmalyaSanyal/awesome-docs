---
marp: true
theme: default
paginate: true
size: 16:9
---

<!--
style: |
  /* === Custom theme styling ===
     These CSS rules will be applied to the Marp slides. */
  section {
    font-family: "Inter", "Segoe UI", Roboto, sans-serif;
    background-color: #0f1724;
    color: #e6eef8;
  }

  h1, h2 {
    font-weight: 700;
    letter-spacing: -0.5px;
  }

  h1 { font-size: 48px; color: #ffd166; }
  h2 { font-size: 28px; color: #7dd3fc; margin-top: 8px; }

  p { font-size: 18px; line-height: 1.45; color: #dbeafe; }

  /* Card style for content blocks */
  .card {
    border-radius: 14px;
    padding: 18px;
    background: rgba(255,255,255,0.03);
    box-shadow: 0 6px 18px rgba(2,6,23,0.6);
  }

  /* Accent code style */
  pre, code {
    background: rgba(255,255,255,0.04);
    border-radius: 8px;
    padding: 6px 8px;
    font-size: 0.9em;
    color: #f8fafc;
  }

  /* Footer space for contact / small text */
  footer {
    font-size: 0.8em;
    opacity: 0.85;
  }
-->
<!-- Title slide -->
# Product Documentation: AwesomeApp v1.0
### Maintainable Marp slides + GitHub raw URL
*Technical writer: contact via `22f3003000@ds.study.iitm.ac.in`*

---

<!-- Overview slide -->
## Goals
- Produce documentation slides that are **maintainable in version control**  
- **Easily convertible** to PDF/HTML/PowerPoint using Marp tools  
- Include: custom theme, page numbers, background image, math, custom styling

---

<!-- How to view (no terminal) -->
## How to preview & export (no terminal)
<div class="card">
1. Use **Marp for VS Code** (install via Extensions and open `slides.md`) — GUI only.  
2. Or paste this markdown into **Marp Web** (https://marp.app/) — paste & preview.  
3. Export from within the extension/web UI → choose **PDF / PPTX / HTML**.
</div>

---

<!-- Theme details / small code block -->
## Custom theme (what this file contains)
This file embeds CSS (see top) to:
- Set background, fonts, colors  
- Style headings, code, and cards  
- Keep page number (via `paginate: true` in frontmatter)

You can tweak the CSS at the top of the file to change brand colors.

---

<!-- Math slide: algorithmic complexity -->
## Algorithmic complexity (math)
For the core indexing step we use a k-NN search over embeddings.  
Typical complexity (naive) for a brute-force search:

$$
T(n, d) = O(n \cdot d)
$$

where:
- \(n\) = number of vectors (database size)  
- \(d\) = embedding dimensionality

If we use an approximate nearest neighbor index (e.g., HNSW), expected query complexity becomes:

$$
T_{HNSW} \approx O(\log n)
$$

Display inline math: \(O(n \cdot d)\) and display block math above.

---

<!-- Slide with background image (image must exist in repo or remote) -->
---
background-image: url('images/architecture.jpg')
background-size: cover
background-position: center
class: lead

# System architecture
> High level architecture diagram and call-flow (image used as slide background)

---

<!-- Example code/config slide -->
## Example: minimal metadata header
```yaml
---
marp: true
theme: default
paginate: true
---
