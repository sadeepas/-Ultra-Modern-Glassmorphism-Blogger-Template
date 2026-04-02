# -Ultra-Modern-Glassmorphism-Blogger-Template
A premium, highly animated, and fully responsive Blogger/Blogspot template built with a cutting-edge Glassmorphism UI and a Bento Grid layout. Designed for developers, UI/UX designers, and tech enthusiasts who want a sleek, futuristic personal blog and portfolio.


Here is a complete, professional `README.md` file tailored specifically for the Blogger XML template you provided. 

---


## ✨ Features

### 🎨 Design & UI
*   **Glassmorphism Aesthetics:** Translucent backgrounds, background-blur filters, and premium glass-like borders.
*   **Dark/Light Mode:** Seamless toggle with local storage memory (respects system preferences).
*   **Bento Grid Layout:** Modern, masonry-style grid for the homepage article feed.
*   **Fully Responsive:** Flawless experience across Desktop, Tablet, and Mobile.
*   **Skeleton Loading:** Beautiful shimmer effects while images load.

### ⚡ Functionality & UX
*   **Vanilla ES6 JavaScript:** Zero dependencies (No jQuery!), ensuring lightning-fast load times.
*   **Smart Sticky Header:** Hides when scrolling down, reveals when scrolling up.
*   **Interactive Mobile Drawer:** App-like slide-out navigation menu for mobile devices.
*   **Reading Progress Bar:** Dynamic top bar that tracks article reading progress.
*   **Smooth Scroll Animations:** Elements fade and slide in using the Intersection Observer API.
*   **Dynamic Typing Effect:** Built-in hero section typing animation.

### 📝 Article Experience
*   **Parallax Hero Images:** Immersive depth effect on single-post featured images.
*   **Floating Share Menu:** Sticky social sharing buttons (Facebook, X, LinkedIn, WhatsApp).
*   **Engagement Buttons:** Built-in UI for "Claps" and "Bookmarks".
*   **Rich Typography:** Clean readability using Google Fonts (`Inter`, `Poppins`, `Merriweather`).
*   **SEO Optimized:** Built-in JSON-LD Schema.org markup for Google rich snippets.

---

## 🛠️ Installation Guide

1. **Download the Template:** Download the `BLOGGER.xml` file from this repository.
2. **Go to Blogger Dashboard:** Log in to your Blogger account and select your blog.
3. **Navigate to Theme:** Click on **Theme** in the left sidebar.
4. **Backup Current Theme:** Click the down arrow next to the "Customize" button and select **Backup** (Highly Recommended).
5. **Install New Theme:** 
   * Click the down arrow again and select **Restore**.
   * Upload the `BLOGGER.xml` file.
   * *Alternatively:* Select **Edit HTML**, delete all existing code, paste the contents of `BLOGGER.xml`, and click **Save**.
6. **Mobile Settings:** Click the gear icon under the mobile preview and select **"No. Show desktop theme on mobile devices"** (This template is inherently responsive).

---

## 🎨 Customization

This template is designed to be easily customizable.

### 1. Changing the Primary Theme Color
You can easily change the main brand color (default is Blue `#3b82f6`) without touching the code:
1. Go to **Theme** > **Customize**.
2. Look for the **Brand Primary Color** variable.
3. Pick your desired color and save.

### 2. Updating Hero Section Data
To change the Author Name, Avatar, and Typing Text, go to **Theme > Edit HTML** and find the `<section class='hero-section' id='about'>` tag.
* **Image:** Replace the `src` link in the `<img class='hero-profile-img'>` tag.
* **Name:** Change the text inside `<h1 class='hero-name'>`.
* **Typing Text:** Scroll to the bottom of the code to the JavaScript section. Find `const phrases = ["UX/UI Designer", "Frontend Developer", ...]` and replace the array with your own skills.

### 3. Updating Social Media Links
Search the HTML for `social-icons-wrap` (located in the footer) and `author-socials` (located inside single posts). Replace the `href` attributes with your personal GitHub, LinkedIn, Twitter, or YouTube URLs.

### 4. Updating the Newsletter/Contact Details
* Look for the `HTML1` widget to update the Newsletter form action URL (e.g., Mailchimp form action).
* Search for `sadeepapemasiri2@gmail.com` to replace the footer email with your own.

---

## 📂 File Structure

The entire template is bundled into a single Blogger-compliant XML file:
*   `BLOGGER.xml`: Contains CSS Variables, Base Reset, Keyframes, Custom UI Styling, Blogger Data Tags, and Vanilla JavaScript.

---

## 💻 Tech Stack

*   **HTML:** Blogger XML & Data Tags
*   **CSS:** CSS3, Custom Properties (Variables), Flexbox, CSS Grid, Backdrop Filters
*   **JS:** Vanilla JavaScript (ES6), Intersection Observer API, LocalStorage

---

## 👨‍💻 Author

**Sadeepa Lakshan**
*   GitHub: [@sadeepas](https://github.com/sadeepas)
*   LinkedIn: [Sadeepa Lakshan](https://www.linkedin.com/in/sadeepa-lakshan/)
*   YouTube: [@slsadeepatec](https://www.youtube.com/@slsadeepatec)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. Feel free to use, modify, and distribute this template, but please retain the author credits.
