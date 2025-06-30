<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=2b3036&height=85&section=header"/>

# 🌐 Linkzy — Your Minimal Link Hub

<!--image-->

Linkzy is a **clean, minimal and customizable link-in-bio site** built with HTML, CSS and JavaScript — no frameworks, no dependencies.

Inspired by developer portfolios, it's fast, responsive and ready to be personalized with your own style.

---

## 🚀 Features

- 🪄 Typing effect for custom bio
- 🎨 Built-in theme with Dev-inspired colors
- 🔗 Responsive link buttons
- ⚙️ Open Graph / Twitter meta tags for rich embeds (Discord, Twitter, etc.)
- 🖼️ GitHub avatar auto-loading

---

## 🛠️ Technologies

| Language | Usage |
|----------|-------|
| HTML     | Structure and meta tags |
| CSS      | Styling (mobile-first, custom palette) |
| JS       | Language detection, typewriter effect, GitHub integration |

---

## ✏️ Customization Guide

You can make your own version in just a few steps:

### 1. Fork or clone the project

```bash
git clone https://github.com/your-username/Linkzy.git
```
### 2. Customize your GitHub username

Edit this line in `assets/js/main.js`:

```js
const githubUsername = "your-github-username";
```
This will fetch your GitHub avatar automatically!

### 3. Change your name, @username and links
In `index.html`, edit:

```html
<h1 class="name">Your Name</h1>
<p class="username">@your.handle</p>

<nav class="links">
  <a href="https://your-link.com" class="link">YOUR LINK</a>
</nav>
```
You can add or remove buttons as needed.

### 4. Update the Open Graph meta tags

Make your link look great when shared on Discord, Twitter, etc.

```html
<meta property="og:title" content="Your Name" />
<meta property="og:description" content="@your.handle | Back-end developer" />
<meta property="og:image" content="your-preview-image-url.png" />
```
Tip: Use a 1200x630px PNG or JPG for perfect previews.

### 5. Edit your description with typing effect

In `main.js`, update your translated bio text:

```js
    const text = "Your description";
```

### 🌐 Deployment

You can publish your version for free using GitHub Pages:
- Go to your repository settings
- Enable Pages under Code → Pages
- Set source to main and folder to /root
- Access your link: `https://your-username.github.io/Linkzy`

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=2b3036&height=85&section=footer"/>
