# 🌈 Multi-Page Gradient Website

This project is a simple **5-page HTML website** created using HTML and CSS.
Each webpage has a different **linear-gradient background color**, while the navigation bar remains common on all pages.

## 📁 Project Structure

```text
project-folder/
│
├── index.html
├── about.html
├── gallery.html
├── achievements.html
├── contact.html
└── README.md
```

## 📄 Pages

### 1. Home

**File:** `index.html`

Background:

```css
background: linear-gradient(120deg, #ffb703, #fff200);
```

### 2. About Us

**File:** `about.html`

Background:

```css
background: linear-gradient(120deg, #ff6b6b, #ffd166);
```

### 3. Gallery

**File:** `gallery.html`

Background:

```css
background: linear-gradient(120deg, #00b4d8, #90e0ef);
```

### 4. Achievements

**File:** `achievements.html`

Background:

```css
background: linear-gradient(120deg, #7b2cbf, #e0aaff);
```

### 5. Contact Us

**File:** `contact.html`

Background:

```css
background: linear-gradient(120deg, #06d6a0, #118ab2);
```

## 🎨 Features

* 5 separate HTML webpages
* Different gradient background on every page
* Common navigation bar
* Rounded navigation bar using `border-radius`
* Hover effect on navigation links
* Responsive design using CSS media queries
* Flexbox used for navigation layout
* Simple and clean design

## 🧭 Navigation

All pages are connected through the navigation bar:

```html
<nav class="navbar">
    <a href="index.html">Home</a>
    <a href="about.html">About Us</a>
    <a href="gallery.html">Gallery</a>
    <a href="achievements.html">Achievements</a>
    <a href="contact.html">Contact Us</a>
</nav>
```

## 💻 Technologies Used

* **HTML5**
* **CSS3**
* **Flexbox**
* **CSS Linear Gradient**
* **CSS Media Queries**

## 📱 Responsive Design

The website uses a media query for screens smaller than `900px`.

On smaller screens:

* Navigation links wrap to multiple lines.
* Spacing between links is reduced.
* The navigation bar gets additional padding.
* The top margin is reduced.

## 🚀 How to Run

1. Download or clone this project.
2. Keep all five HTML files in the same folder.
3. Open `index.html` in any web browser.
4. Use the navigation bar to move between pages.

## 🎯 Purpose

The main purpose of this project is to practice:

* Creating multiple HTML pages
* Linking webpages together
* Using CSS gradients
* Creating navigation bars
* Using Flexbox
* Making webpages responsive

## 👨‍💻 Author

**Vikash Kumawat**
