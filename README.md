# 📄 HTML & CSS Greeting Card Assignment

## 📌 Project Overview

This project is developed and maintained by **Maha Mission Education and Career Council (NGO)** through learning projects on **ApnaGuru.in**. It is proudly supported by **Apnasite IT Services Pvt. Ltd.**, which provides: ✅ **Technical support**\
✅ **Mentorship**\
✅ **Deployment**\
✅ **Ongoing maintenance** of these projects

**🌐 Live URL:** [https://greeting.apnasite.in](https://greeting.apnasite.in)\
**📢 Join us:** [https://apnaguru.in](https://aapn.in/M7PM3JB5)\
**📌 Organization:** [https://mmeac.org](https://mmeac.org)\
**🏢 Company:** [https://apnasite.in](https://apnasite.in)\
**📞 Call/WhatsApp:** +91-8999417889

---

## 🧭 Goal

Design a **visually engaging and decorative greeting card** using **HTML, CSS, and SVG**.
Your focus should be on **aesthetic appeal, layout creativity, and responsive design**, using **SVG decorations, advanced CSS properties**, and web fonts.

🔗 **Live Deployment Format:**
`https://services.apnasite.in/greeting-card-assignments/[YourName_AssignmentNumber]/preview.html`
**Sample:** [https://services.apnasite.in/greeting-card-assignments/Adarsh_Ovhal_19/preview.html](https://services.apnasite.in/greeting-card-assignments/Adarsh_Ovhal_19/preview.html)

🔗 **GitHub Repository:**
👉 [https://github.com/Apnasite/greeting-card-assignments](https://github.com/Apnasite/greeting-card-assignments)

---

## 📁 Folder Structure

```
greeting-card-assignments/
 ┣ 📂 designs/
 ┃ ┗ 📂 design-01/ (or your assigned design)
 ┃   ┣ 📂 css/
 ┃   ┃ ┗ styles.css
 ┃   ┣ 📂 img/
 ┃   ┃ ┣ svg-flowers/
 ┃   ┃ ┗ logo.png
 ┃   ┣ 📂 fonts/
 ┃   ┣ 📜 index.html
 ┃   ┗ 📜 preview.html
 ┣ 📂 SubmittedAssignments/
 ┃ ┗ 📂 [YourName_AssignmentNumber]/
 ┣ 📜 GreetingCard Assignment.docx
 ┗ 📜 User Assignment Mapping.xlsx
```

---

## 🧱 HTML Structure Guidelines

### ✅ You Can Modify: `preview.html`

```html
<div class="greeting-card-background">
  <!-- ✅ Add or edit content/styling elements here -->
</div>
```

### ❌ Do NOT Modify:

```html
<div class="greeting-card-content">
  <!-- ❌ Keep everything inside this div unchanged -->
</div>
```

### Add/Copy new background html block `index.html`:

```html
<div class="greeting-card-background">
  <!-- ✅ Add or edit content/styling elements here -->
</div>
```

---

## 🎨 CSS Styling Guidelines

### ✅ 1. Background Styling

* Use `background-color`, `linear-gradient`, or `patterned SVG backgrounds` inside `.greeting-card-background`.

### ✅ 2. Fonts

* Use **custom web fonts** from Google Fonts or your own `fonts/` folder.
* Apply `font-size`, `font-weight`, `letter-spacing`, `text-shadow` for elegance.

### ✅ 3. SVG Decoration

* Embed or link **SVG flowers and icons**.
* Use `transform`, `scale`, `rotate`, and `positioning` for decoration.
* Ensure responsiveness using `viewBox`, `width="100%"`, etc.

### ✅ 4. Layout and Transformations

* Use `display`, `flex`, `position`, `translate`, and `z-index` to layer your design beautifully.
* Add `border-radius`, `box-shadow`, or `clip-path` for visual softness.

### ✅ 5. Content Styling

* Style **title, greeting message, event name, serial number, date, subtitle, etc.**
* Focus on margins, alignment, and hierarchy for a clean look.

### ✅ 6. Organization Details

* Style **organization logo, name, and address** in the footer or header of the card.
* Use brand-friendly colors and matching fonts.

---

## 📐 Measurement Units

* Use **px** for widths, font sizes, spacing, borders.
* You may also use **mm** and **pt** where needed.
* ❌ Avoid using `%`, `em`, or `rem`.

---

## 🧪 CSS Property Checklist

Use as many of these as possible:

* **Typography:**
  `font-family`, `font-size`, `font-style`, `letter-spacing`, `line-height`, `text-shadow`, `text-align`

* **Color & Decoration:**
  `color`, `background`, `gradient`, `opacity`, `box-shadow`

* **Layout & Sizing:**
  `width`, `height`, `margin`, `padding`, `position`, `display`, `z-index`

* **Advanced Styling:**
  `border-radius`, `clip-path`, `filter`, `transform`, `animation`, `transition`

* **SVG Integration:**
  Embed SVG with proper viewBox, use inline or background SVGs, apply CSS on SVGs

---

## 🚀 Assignment Submission Process (with Git Commands)

### 🔁 1. **Fork the Repository**

👉 [https://github.com/Apnasite/Greeting-card-assignments](https://github.com/Apnasite/Greeting-card-assignments)

---

### 💻 2. **Clone Your Forked Repo**

```bash
git clone https://github.com/YOUR_USERNAME/Greeting-card-assignments.git
cd Greeting-card-assignments
```

---

### 📁 3. **Create Your Assignment Folder**

```bash
mkdir SubmittedAssignments/YourName_Assignment01
cp -r designs/design-[AssignedNumber]/* SubmittedAssignments/YourName_Assignment01/
```

---

### 🛠️ 4. **Work on Your Greeting Card Design**

* Edit only `preview.html` and `css/styles.css`
* Add SVG files, images, fonts as needed in `img/` or `fonts/`.

---

### ✅ 5. **Commit Your Work**

```bash
git add .
git commit -m "Added Greeting Card Assignment - YourName_Assignment01"
```

---

### ⬆️ 6. **Push to Your GitHub Repo**

```bash
git push origin main
```

---

### 🔃 7. **Raise a Pull Request**

* Go to your GitHub fork
* Click “Compare & Pull Request”
* Base repo: `Apnasite/Greeting-card-assignments`
* Head repo: `YourUsername/Greeting-card-assignments`
* Title: `"Submitting Greeting Card Assignment - YourName_Assignment01"`
* Click **Create Pull Request**

---

## 🧾 Evaluation Criteria

| Evaluation Area                         | Weightage |
| --------------------------------------- | --------- |
| HTML Structure Adherence                | ✅         |
| Use of Advanced CSS Properties          | ✅✅✅       |
| Layout, Balance, and Visual Composition | ✅✅        |
| Creative SVG and Flower Usage           | ✅✅        |
| Typography and Text Styling             | ✅✅        |
| Use of Units (px, mm, pt)               | ✅         |
| Folder Naming and Git Usage             | ✅         |
| Bonus: Animations and Print Support     | ⭐ Bonus   |

---

## 🧠 Reminder

Make your greeting card stand out with elegance, creativity, and clarity. Think of real-life cards—festive, personal, and beautiful!

> ✍️ **Example Submission:**
> `https://services.apnasite.in/greeting-card-assignments/Shruti_Kale_01/preview.html`
