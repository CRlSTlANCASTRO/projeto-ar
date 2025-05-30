# 🔢 AR Markers Project - Simple Math with Augmented Reality

This is a web-based Augmented Reality (AR) application built using **A-Frame** and **AR.js**. It detects custom markers through your webcam or smartphone and performs a basic math operation: **addition**.

## 📸 Demo

Try it on your phone:  
👉 [https://CRlSTlANCASTRO.github.io/projeto-ar/](https://CRlSTlANCASTRO.github.io/projeto-ar/)

---

## 🎯 Project Goal

The initial idea was to build a basic AR app that recognizes custom markers and displays numbers on top of them. The project evolved into a simple interactive **addition system**, where the app waits for:

1. A number marker (e.g., `1`)
2. Another number marker (e.g., `2`)
3. A `+` marker to trigger the sum

When all three are shown **in order**, the app displays the result (e.g., `1 + 2 = 3`) above the `+` marker, then resets for the next round.

---

## 🛠️ Tools & Technologies

- **A-Frame** `1.2.0` – for building the 3D scene
- **AR.js** `2.1.8` – for marker detection in AR
- **JavaScript** – logic for marker sequence and addition
- **Canva** – used to design marker visuals (numbers and symbols)
- **AR.js Marker Generator** – to generate `.patt` marker pattern files  
  [https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
- **GitHub Pages** – for hosting and testing on mobile

---

## 📂 Project Structure

projeto-ar/
├── index.html # Main AR scene and logic
├── markers/ # Folder with pattern files (.patt)
│ ├── pattern-marker-1.patt
│ ├── pattern-marker-2.patt
│ └── pattern-marker-plus.patt
└── assets/ # Reserved for future images, audio, etc.


---

## 💡 Features

- Real-time marker detection using webcam or phone camera
- Displays result only after correct sequence: number → number → plus
- Visual feedback using onscreen debug text
- Auto-reset after 3 seconds to allow a new operation
- Works smoothly on mobile via browser

---

## 🚀 Possible Future Updates

- Add more numbers (up to 10)
- Support for other operations (`-`, `×`, `÷`)
- Add audio feedback or animations
- Improve UI for better user experience

---

## 📱 Mobile Support

Tested on Android and iOS through **GitHub Pages**.  
Just open the link in a browser that supports camera access (Chrome, Safari).

---

## 🧑‍💻 Author

Made by Christian Castro  
[GitHub Profile](https://github.com/CRlSTlANCASTRO)

---

## 📝 License

MIT License (feel free to use, remix, and share)
