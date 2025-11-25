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

<!-- Title Slide -->
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
You can style any element using `<style>` in the Marp file.

Example:

```css
section {
  background: #0f1724;
  color: #eaf4ff;
}
