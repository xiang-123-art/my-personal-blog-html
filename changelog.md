# Changelog

All notable changes to the project will be documented in this file.

---

## 2025-06-15
### Features / Changes
- ✅ **Added Configuration Management**: Created `js/config.js` to centrally manage site-wide configurations such as navigation links, footer text, and page title, improving consistency and maintainability.
- ✅ **Implemented Dynamic Navigation**: Replaced static navigation bars in all pages (`index.html`, `about.html`, `articles.html`) with dynamic navigation generated from `SITE_CONFIG.navLinks` in `config.js`, allowing centralized and consistent updates.
- ✅ **Implemented Dynamic Footer**: Replaced hardcoded footer text in all pages with dynamic content loaded from `SITE_CONFIG.footerText` in `config.js`, ensuring unified footer management.
- ✅ **Dynamic Article List**: Enhanced `articles.html` to dynamically generate a list of articles from the `articles` array in `js/data.js`, including article titles (as clickable links to details), summaries, and proper styling.
- ✅ **Structured Project Files**: Organized JavaScript files into `js/` folder (`config.js`, `data.js`), CSS into `css/` folder, and maintained clean HTML structures across all pages.

---

## 2025-06-10
### Features
- ✅ **Created Data File**: Added `js/data.js` containing an array of article objects (`articles`), each with `id`, `title`, `summary`, and other fields, laying the foundation for dynamic content rendering.
- ✅ **Initialized Basic Pages**: Created core HTML pages including `index.html` (homepage), `about.html` (about page), and `articles.html` (article list), with initial content and structure.

---

## 2025-06-01
### Project Setup
- ✅ **Initialized Project**: Set up the initial project structure with essential files such as `index.html`, and planned for future features like dynamic content, configuration management, and multi-page support.