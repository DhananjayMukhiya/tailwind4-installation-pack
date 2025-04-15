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
git clone https://github.com/your-username/tailwind4-startup-pack.git
cd tailwind4-startup-pack
```

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


