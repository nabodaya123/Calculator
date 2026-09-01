# 🧮 JavaScript Calculator

A simple and modern calculator built using **HTML, CSS, and JavaScript**. This project provides a clean calculator interface with basic arithmetic operations and interactive buttons.

## 🚀 Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* `%` Percentage operation
* `AC` — Clear the entire calculation
* `DEL` — Delete the last entered character
* `00` and `0` input
* Decimal number support
* `=` button for calculating results
* Dark gradient calculator interface
* Modern circular button design
* Poppins font styling

## 🛠️ Technologies Used

* **HTML5** — Structure of the calculator
* **CSS3** — Styling and calculator UI
* **JavaScript** — Calculator functionality
* **Google Fonts** — Poppins font

## 📁 Project Structure

```text
Calculator/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 📄 Files Description

### `index.html`

Contains the calculator structure, display input, number buttons, operators, delete button, clear button, and equal button.

### `style.css`

Controls the calculator's appearance, including:

* Dark gradient background
* Calculator container
* Circular buttons
* Button shadows
* Display styling
* Operator colors
* Equal button styling
* Poppins font

### `script.js`

Contains the calculator's interactive functionality.

The JavaScript:

* Detects button clicks
* Adds numbers/operators to the display
* Clears the calculator using `AC`
* Deletes the last character using `DEL`
* Calculates the expression when `=` is pressed

## 💻 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/nabodaya123/calculator.git
```

### 2. Open the project

Go to the project folder:

```bash
cd calculator
```

### 3. Run the project

Open `index.html` directly in your browser.

You can also use **VS Code + Live Server** for easier development.

## 🎯 How It Works

The calculator uses JavaScript to select the input field and calculator buttons.

When a button is clicked:

* Numbers and operators are added to the current expression.
* `AC` resets the display.
* `DEL` removes the last character.
* `=` evaluates the entered expression and displays the result.

## 📸 Interface

The calculator features a dark-themed interface with a gradient background and circular buttons.

## 🔮 Future Improvements

Possible improvements for this project:

* [ ] Add keyboard support
* [ ] Add scientific calculator functions
* [ ] Add calculation history
* [ ] Improve mobile responsiveness
* [ ] Add error handling for invalid expressions
* [ ] Replace `eval()` with a safer expression parser
* [ ] Add light/dark theme switching
* [ ] Add calculation history stored in LocalStorage

## ⚠️ Note

The current JavaScript implementation uses JavaScript's `eval()` function to evaluate mathematical expressions.

For a learning project this demonstrates how expression evaluation works, but for a production application it is recommended to use a safer mathematical expression parser.

## 👨‍💻 Author

**Nabodaya Sahu**

B.Tech — Computer Science and Engineering (Data Science)

---

⭐ If you found this project useful, consider giving the repository a star!
