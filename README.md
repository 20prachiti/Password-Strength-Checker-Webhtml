## 🔐 Password Strength Checker

A **real-time password evaluation tool** built using **HTML, CSS, and JavaScript** that analyzes password security based on **length, complexity, and uniqueness**.

### 🚀 Features

* **Live Strength Meter** – Visual bar with color-coded strength levels from *Very Weak* to *Very Strong*.
* **Dynamic Criteria Check** – Verifies:

  * 8+ characters
  * Uppercase letter (A–Z)
  * Lowercase letter (a–z)
  * Number (0–9)
  * Special character (@, #, \$, %, etc.)
  * Not a common password
* **Common Password Detection** – Blocks widely used weak passwords from a preloaded list.
* **Real-Time Suggestions** – Gives tips to improve password security instantly.
* **Pattern Detection** – Warns against repeated characters and sequential patterns (e.g., `123`, `abc`).
* **Password Visibility Toggle** – Show/Hide password option for convenience.
* **Responsive UI** – Works smoothly on desktop and mobile devices.

### 🛠️ Tech Stack

* **HTML5** – Structure and semantics
* **CSS3** – Styling with gradient backgrounds and animations
* **JavaScript (Vanilla)** – Logic for real-time evaluation and scoring

### 📸 Screenshot

![Password Strength Checker UI](screenshot.png)

### 📂 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/password-strength-checker.git
   ```
2. Open the `index.html` file in your browser.
3. Start typing a password and watch the real-time evaluation.

### 💡 Future Enhancements

* Expand common password list with external datasets like `rockyou.txt` (filtered).
* Integrate HaveIBeenPwned API for breach detection.
* Add entropy-based scoring for advanced evaluation.

---


