# assignment07-2026300032
# Assignment 07: Flexbox Mastery & Layout Refactoring

**Student Name:** Bashyal Khyam Prasad  
**Institution:** Seoul Theological University (STU)  
**Lab Task:** Refined Personal Profile (Name Card) using Flexbox and Responsive Design.

---

## 🚀 Key Learning Objectives
- **Flexbox Mastery:** Used `display: flex` for alignment and space distribution.
- **Refactoring:** Cleaned up redundant HTML tags and improved CSS efficiency.
- **Responsive Design:** Replaced fixed widths with `max-width` to prevent overflow.

---

## 🛠️ Code Preview

### 1. HTML Structure (Refactored)
I simplified the document structure by removing duplicate `<head>` tags and wrapping the cards in a `.content-wrapper` for horizontal alignment.

```html
<div class="content-wrapper">
    <div class="card">
        <div class="header">STU</div>
        <div class="info">
            <h1>Bashyal Khyam Prasad</h1>
            <p class="title">Student at Seoul Theological University</p>
            <img src="profile.jpg" alt="Profile" class="profile-img">
        </div>
        <div class="footer">
            <a href="[https://github.com](https://github.com)">GitHub</a>
            <a href="#">My Shortcuts</a>
        </div>
    </div>
</div>
