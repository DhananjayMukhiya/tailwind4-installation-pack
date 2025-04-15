# 🚀 Tailwind 4 Startup Pack (with PostCSS)

A modern frontend starter kit powered by **Tailwind CSS v4** and **PostCSS**. This pack is perfect for developers who want a clean, customizable base to build beautiful UIs faster.

---

## 📦 Features

- ✅ Tailwind CSS v4 integration
- ⚙️ PostCSS setup with Autoprefixer
- ⚡ Live watch with `npm run start`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/DhananjayMukhiya/tailwind4-installation-pack.git
cd tailwind4-startup-pack
```

---

## 📹 Video Tutorial

📺 Watch the full setup tutorial here:  
👉 [How to Setup Tailwind CSS v4 with PostCSS](https://youtu.be/k_WuDjfkGws?si=5HPhBOtoOPYex_PZ)

> Don’t forget to like 👍 and subscribe 🔔 to [Dhananjay Coders](https://www.youtube.com/@DhananjayCoders)!


---

## 🛠️ Installation Guide (Step-by-Step)

### 1. Before Tailwind Installation Install Node

### 2. Install Required Packages (run below commend in vs code)

```bash
npm install -D tailwindcss@latest @tailwindcss/postcss@latest 
postcss@latest autoprefixer@latest vite
```

### 3. Create Config Files

```bash
npx tailwindcss-cli@latest init -p
```

### 4. Create Your CSS File (style.css and add below code)

```bash
@import "tailwindcss"; 
```

### 5. Configure tailwind.config.js (Replace the existing code with the code below.)

```bash
/** @type {import('tailwindcss').Config} */ 
module.exports = { 
content: ["*"], 
theme: { 
extend: {}, 
}, 
plugins: [], 
}
```

### 6. Configure postcss.config.js (Replace the existing code with the code below.)

```bash
// postcss.config.js 
module.exports = { 
plugins: { 
'@tailwindcss/postcss': {},  
autoprefixer: {}, 
}, 
}
```

### 7. Add script in package.json

```bash
"scripts": { 
"start": "vite"
},
```

### 8. Create HTML File and add below code

```bash
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tailwind CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="bg-orange-500 p-2 font-bold text-white uppercase">Jai Hind</div>
    <div class="bg-white p-2 font-bold text-blue-700 uppercase">Jai Bharat</div>
    <div class="bg-green-500 p-2 font-bold text-white uppercase">Jai Bihar</div>
</body>
</html>
```

### 9. Install tailwind css intelisense extansions (for suggestion)

### 3. Then run

```bash
npm run start
```

---

## 🧑‍💻 Author


<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/780ac54c-631d-413c-96af-18dfe650362b" alt="Dhananjay's photo" width="100" style="border-radius: 12px;"/>
    </td>
    <td>
      <b>Dhananjay Mukhiya</b><br>
      🎓 CSE Student @ NGP Patna<br>
      💻 Tech Stack: MERN, HTML, CSS, JavaScript<br>
      🔗 GitHub: <a href="https://github.com/DhananjayMukhiya">@dhananjaymukhiya</a>
    </td>
  </tr>
</table>


---

## ⭐️ Don't forget to Star the Repository!

> Thanks for visiting! Keep learning and building 🚀


