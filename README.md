# Frontend Mentor - QR Code Component

This is my solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). The goal was to recreate a clean and centered card that contains a QR code and a short description, using only HTML and CSS.

---

## 📸 Screenshot

![QR Code Component Screenshot](./preview.jpg)

---

## 🔗 Links

- [Live Site URL](#) <!-- Add your live site link here -->
- [Solution on Frontend Mentor](#) <!-- Add your solution page link here -->

---

## 🔧 My Process

1. Set up the HTML structure with semantic tags.
2. Styled the layout using CSS Flexbox.
3. Focused on a clean, responsive card design.
4. Used utility-based styling for readability and spacing.

---

## 🛠️ Built With

- Semantic **HTML5**
- **CSS3** with custom properties
- **Flexbox** for layout
- Mobile-first design approach

---

## 💡 What I Learned

This challenge helped reinforce a few key CSS layout principles:

### 🔹 Centering with Flexbox

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: hsl(212, 45%, 89%);
}
```

###🔹Responsive image scaling

```css
.qr-code {
  width: 100%;
  max-width: 280px;
  height: auto;
  border-radius: 10px;
}
```
###🔹Card component styling

```css
.qr-card-container {
  background-color: white;
  border-radius: 20px;
  max-width: 320px;
  padding: 16px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.08);
  text-align: center;
}
```

🔁 Continued Development

In future projects, I want to:

Explore more advanced layout techniques using CSS Grid.

Learn about accessibility and semantic improvements.

Improve mobile responsiveness for more complex layouts.

👤 Author
Frontend Mentor: @yourusername

GitHub: @yourusername

🙌 Acknowledgments
Thanks to Frontend Mentor for creating amazing challenges and to the frontend developer community for always sharing inspiration and resources.
