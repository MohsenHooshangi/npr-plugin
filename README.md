# NPR Tabs – WordPress Posts Widget Plugin

A custom WordPress plugin that adds a sidebar widget with **three tabs**:
- 🆕 Newest Posts (جدیدترین مطالب)
- 🔥 Most Viewed Posts (پربازدیدترین مطالب)
- 🎲 Random Posts (مطالب تصادفی)

The widget is fully responsive and updates post lists dynamically when a tab is clicked.

---

## 🔧 Project Overview

- 👨‍💻 **Role:** Full plugin development (PHP + CSS + JS)
- 📅 **Status:** Completed
- 🌐 **Test Environment:** [Localhost Development – mh-develop.local](http://mh-develop.local)

---

## 🧰 Technologies Used

- **PHP** – WordPress widget registration, custom WP_Query calls.
- **CSS** – Styling for tab navigation and post lists.
- **JavaScript (jQuery)** – Tab switching logic without page reload.

---

## 🧠 Features

- Sidebar widget with three tabs: **Newest**, **Most Viewed**, **Random**.
- Posts display with title and excerpt or thumbnail.
- Fully responsive and works with any WordPress theme.
- Optimized queries for fast performance.

---

---

## 📄 File Details

### **`core.php`**
Main plugin loader:
- Registers the NPR widget.
- Enqueues CSS & JS for the frontend.
- Loads the widget HTML view.

### **`assets/front/css/style.css`**
Styles for:
- Tab navigation (active/inactive states)
- Post list layout inside each tab
- Responsive adjustments for mobile

### **`assets/front/js/main.js`**
Handles:
- Switching between tabs without page reload.
- Hiding inactive tab content and showing the selected tab.

### **`_inc/top-new-post.php`**
- Queries and renders the newest posts based on publish date.

### **`_inc/top-comment-post.php`**
- Queries and renders the most viewed or most commented posts.

### **`_inc/rand-post.php`**
- Queries and renders random posts.

### **`view/front/npr-tab.php`**
- Contains the main HTML structure of the widget with:
  - Tab navigation
  - Post list container for each tab


---

## 🗂️ Installation

1. Download the `npr-plugin` folder.
2. Place it inside your WordPress `wp-content/plugins/` directory.
3. Go to **WordPress Dashboard > Plugins** and activate **NPR Tabs**.
4. From **Appearance > Widgets**, add the NPR Tabs widget to your desired sidebar.

---

## 📌 Notes

- All queries use `WP_Query` for maximum WordPress compatibility.
- No page reload is required when switching tabs – handled entirely via JavaScript.
- Tested with WordPress 6.x and PHP 8.x.

---

## 📬 Contact

If you’d like to learn more or collaborate:

- 📧 Email: **mr.hooshangi.official@gmail.com**  
- 🌐 Website: [www.mohsenhooshangi.ir](https://www.mohsenhooshangi.ir)  
- 🖥️ GitHub: [github.com/MohsenHooshangi](https://github.com/MohsenHooshangi)
- 🖥️ Linkedin: [linkedin.com/in/mohsen-houshangi](https://linkedin.com/in/mohsen-houshangi)


