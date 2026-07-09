# Frontend Mentor - Social Proof Section Solution

A responsive solution to the **Social Proof Section** challenge from Frontend Mentor. This project recreates a modern testimonial section featuring customer ratings, verified buyer reviews, and a fully responsive layout using only HTML and CSS.

---

## 📑 Table of Contents

* [Overview](#-overview)

  * [The Challenge](#-the-challenge)
  * [Features](#-features)
  * [Screenshot](#-screenshot)
  * [Live Demo](#-live-demo)
* [Project Structure](#-project-structure)
* [Built With](#-built-with)
* [Responsive Design](#-responsive-design)
* [Key Concepts Practiced](#-key-concepts-practiced)
* [What I Learned](#-what-i-learned)
* [Future Improvements](#-future-improvements)
* [Getting Started](#-getting-started)
* [Author](#-author)
* [Acknowledgments](#-acknowledgments)

---

# 📖 Overview

This project is a solution to the **Frontend Mentor – Social Proof Section** challenge. The goal was to recreate the provided design as accurately as possible while ensuring the layout adapts smoothly across different screen sizes.

The page displays:

* A hero section introducing customer satisfaction.
* Three customer rating summaries.
* Three testimonial cards from verified buyers.
* Responsive layouts for desktop, tablet, and mobile devices.

---

## 🎯 The Challenge

Users should be able to:

* View the optimal layout for their device.
* Experience a responsive interface on desktop and mobile screens.
* Read customer testimonials presented in a clean and visually appealing layout.

---

## ✨ Features

* Semantic HTML5 structure
* Fully responsive design
* CSS Flexbox layouts
* Desktop staggered card positioning
* Desktop staggered rating boxes
* Mobile-friendly stacked layout
* Google Fonts integration (League Spartan)
* Custom background illustrations
* Circular customer avatars
* Clean and modern UI

---

## 📷 Screenshot

![Frontend-Mentor-Social-Proof-Section-Solution.png](https://github.com/UnbrokenLogic/ASTUSummerBootcamp-Project-1/blob/main/screenshot/Frontend%20Mentor%20-%20Social%20Proof%20Section%20Solution.png)

```text
Frontend Mentor - Social Proof Section Solution.png
```

---

## 🌐 Live Demo

👉 [Live Demo Link](https://unbrokenlogic.github.io/ASTUSummerBootcamp-Project-1/)

---

# 📁 Project Structure

```text
.
├── index.html
├── style.css
├── images/
│   ├── favicon-32x32.png
│   ├── bg-pattern-top-desktop.svg
│   ├── bg-pattern-bottom-desktop.svg
│   ├── bg-pattern-top-mobile.svg
│   ├── bg-pattern-bottom-mobile.svg
│   ├── icon-star.svg
│   ├── image-colton.jpg
│   ├── image-irene.jpg
│   └── image-anne.jpg
├── screenshot/
│   └── Frontend Mentor - Social Proof Section Solution.png
└── README.md
```

---

# 🛠 Built With

* HTML5
* CSS3
* Flexbox
* Semantic HTML
* Responsive Web Design
* Google Fonts (League Spartan)

---

# 📱 Responsive Design

The layout changes depending on the screen size.

### Desktop

* Two-column top section
* Ratings shifted horizontally for a staggered appearance
* Testimonial cards displayed in one row
* Cards staggered vertically for added visual depth

### Mobile

* All sections stack vertically
* Rating boxes become centered
* Cards display in a single column
* Desktop stagger effects are removed for better readability

---

# 💡 Key Concepts Practiced

During this project, the following front-end concepts were reinforced:

* Semantic page structure
* Flexbox alignment
* Responsive layouts
* Media queries
* Typography hierarchy
* Background image positioning
* CSS spacing techniques
* Border radius and card design
* Reusable CSS classes
* Desktop-to-mobile adaptation

---

# 📚 What I Learned

One of the most interesting parts of this project was creating staggered layouts using simple CSS margins.

Instead of relying on complex positioning, individual elements are offset with different margin values to create a layered appearance.

Example:

```css
.row-1 {
  margin-left: 0;
}

.row-2 {
  margin-left: 3rem;
}

.row-3 {
  margin-left: 6rem;
}
```

The testimonial cards use the same idea vertically:

```css
.card-1 {
  margin-top: 0;
}

.card-2 {
  margin-top: 1rem;
}

.card-3 {
  margin-top: 2rem;
}
```

On smaller screens, these offsets are removed using media queries to maintain a clean, readable layout.

---

# 🚀 Future Improvements

Possible enhancements include:

* Adding subtle hover animations
* Improving accessibility with additional ARIA labels
* Introducing CSS custom properties for easier theme management
* Creating a dark mode version
* Refactoring styles into a more scalable architecture

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/unbrokenlogic/ASTUSummerBootcamp-Project-1.git
```

Navigate into the project folder:

Open `index.html` in your preferred web browser.

No installation or build tools are required.

---

# 👤 Author

**Name:** Suleyman Dawud

* Frontend Mentor: https://www.frontendmentor.io/profile/UnbrokenLogic
* GitHub: https://github.com/UnbrokenLogic

---

# 🙏 Acknowledgments

Thanks to **Frontend Mentor** for providing realistic front-end challenges that help developers improve their HTML and CSS skills through practical projects.

This project was built as part of my front-end learning journey to strengthen my understanding of responsive layouts, Flexbox, and modern CSS design techniques.
