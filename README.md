# 🎓 Udemy Clone

A responsive front-end clone of the Udemy e-learning platform, built with vanilla HTML and CSS.

---

## 📸 Preview

### 🏠 Homepage
![Homepage](screenshots/Homepage.png)

### 📚 Recommended Section
![Recommended Section](screenshots/Recommended-section.png)

### 🔥 Popular Courses
![Popular Courses](screenshots/popular-courses.png)

### 🖥️ Full Page Preview
![Full Preview](screenshots/preview.png)

---

## 🚀 Features

- **Navbar** with a search bar, navigation links, and icon actions (cart, notifications, profile)
- **Category bar** with pill-style links for quick topic browsing
- **Sale banner** image section
- **Recommended Courses** section with course cards (image, title, instructor, rating, price)
- **Topics** section with hover-effect topic pills
- **Most Popular** section with an extended course card grid
- **Footer** with links and branding

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantics |
| CSS3 | Styling, layout (Flexbox), hover effects |
| Google Fonts | [Gabarito](https://fonts.google.com/specimen/Gabarito) font family |
| Font Awesome 7 | Icons (search, cart, bell, user) |

---

## 📁 Project Structure

```
udemy-clone/
├── index.html       # Main HTML file
├── style.css        # Stylesheet
└── image/           # Course images and sale banner
    ├── sale image.png
    ├── c1.jpg
    ├── c2.jpg
    └── ...
```

---

## 🏁 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/anithasankar33-droid/udemy-clone.git
   ```

2. **Navigate into the project folder**
   ```bash
   cd udemy-clone
   ```

3. **Add your images**  
   Place your course images (`c1.jpg` through `c12.jpg`) and `sale image.png` inside an `image/` folder in the project root. Then update the `src` paths in `index.html` from absolute local paths to relative ones:
   ```html
   <!-- Before -->
   <img src="c:\Users\DELL\Desktop\FSWD\CSS\udemy-clone\image\c1.jpg">

   <!-- After -->
   <img src="image/c1.jpg">
   ```

4. **Open in browser**  
   Open `index.html` directly in your browser, or use the Live Server extension in VS Code.

---

## 📌 Known Issues / TODO

- [ ] Fix absolute image paths — convert to relative paths for portability
- [ ] Fix CSS typo: `background-color: 2x solid #d1d7dc` on `.topics__container a` should be `border: 2px solid #d1d7dc`
- [ ] Add responsiveness for mobile/tablet screens (media queries)
- [ ] Make the search bar functional
- [ ] Add hover tooltips on navbar icons
- [ ] Close the `</div>` for `.footer` in `index.html`

---

## 🎨 Design Reference

This project is inspired by [Udemy](https://www.udemy.com/). Built for learning and practice purposes only. All course names, instructor names, and branding belong to their respective owners.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author
Anitha

**Your Name**  
[GitHub](https://github.com/anithas) · [LinkedIn](https://www.linkedin.com/in/anitha-s-442072318)
