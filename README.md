# 🕹️ E-sports Landing Page

A modern and responsive landing page for an E-sports or sports co-op brand, built using HTML, CSS, and JavaScript.

---

## 📸 Preview

![Preview Screenshot](./preview.png) <!-- Replace this with your screenshot path -->

---

## 📁 Project Structure

e-sports-landing/
│
├── index.html # Main HTML file
├── style.css # CSS styling
├── img/
│ └── shoes.png # Sample product image
└── README.md # Project documentation


---

## ✅ Features

- Responsive navigation bar
- Hamburger menu for mobile view
- Styled hero section with CTA
- Hover effects on links and buttons
- Mobile-first layout with media queries
- Modern UI using rem/vh/vw units

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox & Media Queries)
- JavaScript (Vanilla)

---

## 📲 How to Use

1. **Clone the repository** or download the ZIP.
    ```bash
    git clone https://github.com/yourusername/e-sports-landing.git
    ```

2. **Open the project folder** and run `index.html` in your browser:
    - On VS Code: Right-click → "Open with Live Server"
    - Or just double-click the `index.html` file

---

## 🖱️ Hamburger Menu Behavior

- On smaller screens (`max-width: 768px`), the nav bar becomes hidden.
- The ☰ icon (hamburger) toggles the nav links via JavaScript:
    ```js
    const hamburger = document.getElementById('hamburger');
    const navLinks = document.getElementById('nav-links');

    hamburger.addEventListener('click', () => {
        navLinks.classList.toggle('active');
    });
    ```

---

## 💡 Future Improvements

- Add animations (e.g., fade-in, slide)
- Connect product list from a CMS or backend
- Integrate contact form or newsletter
- Add accessibility improvements

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✨ Author

**Junaid Shah**  
[GitHub Profile](https://github.com/webdevshah)  
Email: junaid.devworksx@gmail.com


