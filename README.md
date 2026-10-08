# SplitFrame

### ₊⊹ About

As the name suggests and the description makes clear, **SplitFrame** is an animation project designed to split the image into four equal parts as soon as the cursor hovers over it. As soon as the cursor moves away, the image returns to its original state.


https://github.com/user-attachments/assets/885b68b6-7cca-47d5-8ac6-6547f27f2d00

---

### ⚙️ Tech Stack

- **HTML5**
- **CSS3**

---

### 🖿 Project structure

```
SplitFrame/
├── Assets/
├── index.html
├── style.css
└── README.md

```

---

### .ᐟ.ᐟ How It Works

- To work correctly, it needs four pieces of an image—all four parts must be exactly the same

- Using the `grid`, we’ll combine these four parts to form the complete image, joining them without leaving any space between them 

- Using `background-position`, we’ll define the position of each part of the image

- `transform: translate()` is what will push the parts in their corresponding directions, and it’s also what will return them to their original state

- `transition: transform 0.3s ease` causes the four parts to smoothly move apart when the cursor hovers over them and return to their original positions when the cursor is moved away
