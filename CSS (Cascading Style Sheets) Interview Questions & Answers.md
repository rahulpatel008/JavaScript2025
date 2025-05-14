# 📘 CSS (Cascading Style Sheets) Interview Questions and Answers

This document contains basic, intermediate, and advanced-level CSS interview questions and answers with easy navigation.

---

## 📑 Table of Contents

### 🔰 Basic Level
1. [What is CSS?](#1-what-is-css)
2. [What are the different ways to apply CSS to a web page?](#2-what-are-the-different-ways-to-apply-css-to-a-web-page)

### 🚀 Intermediate Level
3. [What is the box model in CSS?](#3-what-is-the-box-model-in-css)
4. [What is flexbox?](#4-what-is-flexbox)

### 🧠 Advanced Level
5. [How can you create a CSS grid layout?](#5-how-can-you-create-a-css-grid-layout)
6. [What are CSS preprocessors, and give examples?](#6-what-are-css-preprocessors-and-give-examples)

---

## 🔰 Basic Level

### 1) What is CSS?
**Answer:**  
CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation of a document written in HTML or XML. It controls how elements should be displayed on screen, paper, or other media.

[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---

### 2) What are the different ways to apply CSS to a web page?
**Answer:**  
CSS can be applied in three ways:
- **Inline CSS**: Using the `style` attribute inside HTML tags.
- **Internal CSS**: Using a `<style>` tag inside the `<head>` of the HTML document.
- **External CSS**: Linking a separate `.css` file using a `<link>` tag.

[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---

## 🚀 Intermediate Level

### 3) What is the box model in CSS?
**Answer:**  
The **CSS box model** describes the rectangular boxes that are generated for elements in the document. It consists of:
- **Content**: The actual content of the box (text, image, etc.)
- **Padding**: Space around the content
- **Border**: A border surrounding the padding
- **Margin**: Space outside the border

[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---

### 4) What is flexbox?
**Answer:**  
**Flexbox** (Flexible Box Layout) is a CSS layout model that allows you to efficiently layout, align, and distribute space among items in a container. It is useful for dynamic and responsive designs.

Key properties:
- `display: flex;`
- `justify-content`
- `align-items`
- `flex-direction`

[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---

## 🧠 Advanced Level

### 5) How can you create a CSS grid layout?
**Answer:**  
You can create a grid layout by using `display: grid;` on a container and then defining:
- `grid-template-rows`
- `grid-template-columns`

Example:
```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: auto;
}
.item {
  grid-column: 1 / 3;
  grid-row: 1;
}

```
[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---

### 6) What are CSS preprocessors, and give examples?
**Answer:**  
CSS preprocessors are scripting languages that extend CSS and add features like variables, nesting, mixins, and functions. They must be compiled into regular CSS before being used.

- Popular CSS preprocessors:

- Sass (Syntactically Awesome Stylesheets)

- LESS

- Stylus

[🔝 Go to top](#-css-cascading-style-sheets-interview-questions-and-answers)

---
