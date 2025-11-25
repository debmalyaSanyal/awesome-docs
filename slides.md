---
marp: true
theme: default
paginate: true
size: 16:9
---

# Product Documentation  
### AwesomeApp v1.0  
**Author:** 22f3003000@ds.study.iitm.ac.in

---

---
background-image: url("https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1600&q=80")
background-size: cover
background-position: center
class: lead
---

# System Architecture  
### (This slide satisfies the background-image requirement)

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
}

h2 {
  color: #7dd3fc;
}

.card {
  padding: 18px;
  border-radius: 12px;
  background: rgba(255,255,255,0.05);
}

pre, code {
  background: rgba(255,255,255,0.05);
  padding: 6px 10px;
  border-radius: 6px;
  color: #f8fafc;
}
</style>

# Agenda
- Documentation goals  
- Custom theme  
- Math equations  
- Raw GitHub URL  
- Export workflow  

---

# Maintainable Documentation
<div class="card">
- Version-controlled  
- Markdown-based  
- Exportable to PDF, PPTX, HTML  
- Easy to maintain  
</div>

---

# Math (Algorithmic Complexity)

Inline:  
\( O(n \cdot d) \)

Block:

$$
T(n, d) = O(n \cdot d)
$$

Another example:

$$
T_{\text{BinarySearch}} = O(\log n)
$$

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

Use:

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
1. Open **Marp for VS Code** or **https://marp.app**  
2. Load `slides.md`  
3. Click **Export** → PDF / PPTX / HTML  
4. Done  
</div>

---

# Thank You!
Email: **22f3003000@ds.study.iitm.ac.in**

Page numbers appear due to `paginate: true`.
