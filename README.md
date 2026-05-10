# 🎁 Daily Reward Popover  

A clean and minimal **Daily Reward Popover UI** built using **HTML5 and CSS3**.  
This project demonstrates how to use the **HTML Popover API** to show and hide a reward message — no JavaScript required!

---

## 🌟 Features

- ⚡ **No JavaScript needed** — powered entirely by native HTML Popover attributes  
- 🎨 **Modern UI** with smooth button styles and shadow effects  
- 📱 **Responsive design** — works across all devices  
- 💰 Simulates a “daily reward claim” experience (like mobile games or apps)  

---

## 🧩 Project Structure

```
Daily-Reward-Popover/
│
├── index.html    # HTML structure
├── styles.css    # Styling
├── LICENSE
└── README.md     # Project documentation
```

---

## 🚀 How to Use

1. Clone or download the project  
   ```bash
   git clone https://github.com/sagesakshi27/Daily-Reward-Popover.git
   ```

2. Open the project folder  
   ```bash
   cd Daily-Reward-Popover
   ```

3. Launch the project  
   Simply open **index.html** in your browser.

4. Click on the **“🎁 Claim Daily Reward”** button —  
   A popover appears showing your **200-coin daily reward** message!

---

## 🧠 How It Works

- The button uses the new **Popover API** attributes:
  ```html
  popovertarget="reward"
  popovertargetaction="show"
  ```
  These trigger the element with the `popover` attribute to appear or hide — completely without JS.

- The popover message is defined in:
  ```html
  <div id="reward" popover> ... </div>
  ```

---

## 🎨 Customization

- Edit **`styles.css`** to change button colors, font style, or layout.  
- Modify the popover text in **`index.html`** to display different reward messages.  
- You can also integrate it into larger web apps or daily reward systems.

---

## 💡 Technologies Used

- **HTML5**
- **CSS3 (Flexbox & Shadow Effects)**
- **Native HTML Popover API**

---

## 🧑‍💻 Author

> **Developer:**  **Sakshi Chavan**

> **Github:** **[sagesakshi27](https://github.com/sagesakshi27)**

---
