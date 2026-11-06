<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7c5cff,50:00e0ff,100:ff4fd8&height=220&section=header&text=Nida%20Ali&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%26%20Python%20Developer%20%E2%80%94%20Portfolio&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Nida Ali banner"/>

<a href="#">
  <img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=24&duration=2800&pause=900&color=00E0FF&center=true&vCenter=true&width=620&lines=A+highly+animated+portfolio+website;Built+with+HTML+%2B+CSS+%2B+PHP;One+file.+Zero+frameworks.+All+motion." alt="Typing intro"/>
</a>

<br/>

<img src="https://img.shields.io/badge/PHP-7.4%2B-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<br/>
<img src="https://img.shields.io/badge/Dependencies-0-38f9a6?style=flat-square"/>
<img src="https://img.shields.io/badge/Files-1-7c5cff?style=flat-square"/>
<img src="https://img.shields.io/badge/Responsive-Yes-00e0ff?style=flat-square"/>
<img src="https://img.shields.io/badge/Reduced%20Motion-Supported-ff4fd8?style=flat-square"/>

<br/><br/>

**[🌐 Live Demo](#)** &nbsp;·&nbsp; **[✨ Features](#-features)** &nbsp;·&nbsp; **[🚀 Quick Start](#-quick-start)** &nbsp;·&nbsp; **[🎨 Customize](#-customize-it)** &nbsp;·&nbsp; **[📬 Contact](#-contact)**

</div>

---

## 👋 About

This is the personal portfolio of **Nida Ali**, an AI engineer and Python developer specializing in **AI automation, LLM integration, custom chatbots, multi-agent systems, computer vision and NLP**.

The whole site lives in **one `index.php` file**: no frameworks, no build step, no npm. Drop it on any PHP host and it runs. Every section is driven by PHP data arrays, so updating the content means editing a list, not hunting through HTML.

<div align="center">

<!-- Add your own screenshots to a /screenshots folder with these names -->
<img src="screenshots/hero.png" width="90%" alt="Hero section"/>

</div>

---

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 🎬 Motion & Animation
- Counting **preloader** with a curtain-wipe reveal
- Name that **flips in letter by letter** with a flowing gradient
- **Typing effect** cycling through roles
- **3D spinning atom rings** around a breathing glowing core
- Headings that **slide up word by word**
- Section labels that **decode** like a cipher
- **Sticky stacking** project cards that scale and dim
- Two **marquee rows** that speed up and skew with scroll velocity
- Scroll-drawn **timeline** with a travelling glow

</td>
<td width="50%" valign="top">

### 🖱️ Interaction
- **Custom cursor** that morphs into an "Explore" bubble
- **Click sparks** in the brand colours
- **3D tilt** cards and **magnetic** buttons
- Cursor-following **spotlight** and rotating **glow borders**
- **Particle network** that links to the mouse
- **Parallax** hero visual
- Sliding **active-section pill** in the navbar
- Side **dot navigation** and a **progress-ring** back-to-top button
- Navbar hides on scroll down, returns on scroll up

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ Under the Hood
- **Single file**: PHP, CSS and JS together
- **Content in PHP arrays**, rendered with loops
- All output escaped with `htmlspecialchars`
- **Smooth-scroll navigation** in JavaScript, with an offset for the fixed navbar
- Scroll work batched with `requestAnimationFrame`
- Content stays visible if JavaScript is disabled

</td>
<td width="50%" valign="top">

### 📬 Working Contact Form
- Sends email with PHP `mail()`
- **CSRF token** check
- **Honeypot** field against bots
- Server-side validation for name, email and message length
- Keeps typed values when there's an error
- Success and error messages with animation

</td>
</tr>
</table>

---

## 🧭 Sections

| # | Section | What it shows |
|:-:|---|---|
| 🏠 | **Hero** | Name, rotating roles, intro, call-to-action buttons, animated orbit visual |
| 01 | **About** | Professional summary, email, LinkedIn, location, animated stats |
| 02 | **Skills** | AI & LLMs · Automation · Computer Vision · NLP · Programming · Web & APIs |
| 03 | **Experience** | Pro Codes Solutions · Freelance · Proit, on an animated timeline |
| 04 | **Projects** | PrecisionPen · Gesture-Controlled Image Resizing · Text Preprocessing Pipeline |
| 05 | **Education** | Master of Computer Applications (FAST-NUCES) · BS Computer Science (Qarshi University) · Languages |
| 06 | **Contact** | Contact details and the PHP contact form |

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=php,html,css,js&theme=dark" alt="Tech stack icons"/>

</div>

| Layer | Used for |
|---|---|
| **PHP** | Content data, rendering loops, contact form handling, CSRF and validation |
| **HTML5** | Semantic page structure |
| **CSS3** | Keyframe animations, 3D transforms, `@property` animated gradients, glassmorphism, responsive grid |
| **Vanilla JS** | Smooth scroll, IntersectionObserver reveals, canvas particles, cursor, tilt, marquee |
| **Google Fonts** | Space Grotesk · Inter · JetBrains Mono |

---

## 🚀 Quick Start

### Option 1 · PHP's built-in server
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
php -S localhost:8000
```
Then open **http://localhost:8000** in your browser.

### Option 2 · XAMPP / WAMP / MAMP
1. Copy `index.php` into your `htdocs` (or `www`) folder.
2. Start Apache.
3. Open **http://localhost/index.php**.

### Option 3 · Shared hosting
Upload `index.php` to your `public_html` folder. That's it.

> **Requirements:** PHP 7.4 or newer. No database, no Composer, no Node.

---

## 🎨 Customize It

All content sits in arrays at the **top of `index.php`**:

```php
$profile    = [ 'name' => ..., 'title' => ..., 'email' => ..., 'linkedin' => ..., 'summary' => ... ];
$roles      = [ 'AI Engineer', 'Python Developer', ... ];   // typing effect
$stats      = [ ... ];                                      // counters in About
$skills     = [ ... ];                                      // skill cards
$experience = [ ... ];                                      // timeline
$projects   = [ ... ];                                      // project cards
$education  = [ ... ];
$languages  = [ 'English', 'Urdu', 'Arabic', 'Turkish' ];
```

**Add a project** by appending to `$projects`:
```php
[
    'num'    => '04',
    'title'  => 'My New Project',
    'sub'    => 'Short tagline',
    'stack'  => ['Python', 'FastAPI'],
    'points' => ['What it does', 'What makes it interesting'],
    'grad'   => 'g1', // g1, g2 or g3 background
],
```

**Change the colours** in the CSS `:root` block:
```css
--c1:#7c5cff;  /* violet */
--c2:#00e0ff;  /* cyan   */
--c3:#ff4fd8;  /* pink   */
--c4:#38f9a6;  /* mint   */
```

---

## 📬 Contact Form Setup

The form sends messages to the email in `$profile['email']` using PHP's `mail()` function.

| Where you run it | Does email work? |
|---|---|
| Most shared hosting (cPanel, Hostinger, etc.) | ✅ Usually works out of the box |
| Local XAMPP / `php -S` | ❌ No mail server, so you'll see the error message |
| VPS | ⚙️ Needs a mail server or SMTP setup |

If your host blocks `mail()`, swap that one call for an SMTP library such as [PHPMailer](https://github.com/PHPMailer/PHPMailer).

---

## 📁 Project Structure

```
📦 portfolio
 ┣ 📜 index.php        ← the entire website
 ┣ 📂 screenshots      ← images for this README
 ┗ 📜 README.md
```

---

## ♿ Accessibility & Performance

- Honours **`prefers-reduced-motion`**: animations are switched off for people who ask for less motion
- Custom cursor and tilt effects only run on devices with a mouse
- Pages stay readable with JavaScript disabled
- Fewer particles on small screens
- Fully **responsive**, with a mobile menu below 980px

---

## 📸 Screenshots

<div align="center">

| Skills | Projects |
|:-:|:-:|
| <img src="screenshots/skills.png" alt="Skills section"/> | <img src="screenshots/projects.png" alt="Projects section"/> |

| Mobile |
|:-:|
| <img src="screenshots/mobile.png" width="300" alt="Mobile view"/> |

</div>

---

## 📬 Contact

<div align="center">

<a href="mailto:nidaali.contact@gmail.com"><img src="https://img.shields.io/badge/Email-nidaali.contact%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/nida-ali-1b6659447"><img src="https://img.shields.io/badge/LinkedIn-Nida%20Ali-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Location-Islamabad%2C%20Pakistan-38f9a6?style=for-the-badge&logo=googlemaps&logoColor=white"/>

<br/><br/>

**Open to AI automation, LLM integration and chatbot projects.**

⭐ If you like this portfolio, consider giving the repo a star!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff4fd8,50:00e0ff,100:7c5cff&height=120&section=footer" width="100%"/>

</div>
