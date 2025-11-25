---
marp: true
theme: default
paginate: true
size: 16:9
---

<!-- Custom CSS theme -->
<style>
section {
  background: #0f1724;
  color: #eaf4ff;
  font-family: "Inter", "Segoe UI", Roboto, sans-serif;
}

h1 {
  color: #ffd166;
  font-size: 48px;
  letter-spacing: -1px;
}

h2 {
  color: #7dd3fc;
}

.card {
  padding: 18px;
  border-radius: 12px;
  background: rgba(255,255,255,0.05);
  box-shadow: 0 0 18px rgba(0,0,0,0.3);
}

pre, code {
  background: rgba(255,255,255,0.05);
  padding: 6px 10px;
  border-radius: 6px;
  color: #f8fafc;
}
</style>

# Product Documentation  
### AwesomeApp v1.0  
**Author:** 22f3003000@ds.study.iitm.ac.in

---

# Agenda
- Documentation goals  
- Theme customization  
- Math examples  
- Background image usage  
- Raw GitHub URL format  
- Export workflow  

---

# Maintainable Documentation
<div class="card">
- Stored in GitHub (version control)  
- Markdown-based  
- Export to **PDF**, **PPTX**, **HTML**  
- Easy collaboration  
</div>

---

# Custom Theme (CSS)

Example:

```css
section {
  background: #0f1724;
  color: #eaf4ff;
}
```

This deck uses a full custom CSS theme (at top of file).

---

# Math (Algorithmic Complexity)

Inline math:  
\( O(n \cdot d) \)

Block math:

$$
T(n, d) = O(n \cdot d)
$$

Approximate search:

$$
T_{\text{HNSW}} \approx O(\log n)
$$

---

---
background-image: url("https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80")
background-size: cover
background-position: center
class: lead
---

# System Architecture  
### (This is the required background image slide)

---

# Metadata Example  
```yaml
---
marp: true
theme: default
paginate: true
---
```

---

# Raw GitHub URL Format

```
https://raw.githubusercontent.com/[USER]/[REPO]/main/slides.md
```

Example:

```
https://raw.githubusercontent.com/your-username/awesome-docs/main/slides.md
```

---

# Exporting (No Terminal Needed)
<div class="card">
1. Open **Marp for VS Code** or https://marp.app  
2. Load `slides.md`  
3. Click **Export** → PDF / PPTX / HTML  
4. Done!
</div>

---

# Thank You!
Email: **22f3003000@ds.study.iitm.ac.in**

Page numbers appear automatically from `paginate: true`.
