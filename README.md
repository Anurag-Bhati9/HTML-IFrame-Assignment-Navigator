# HTML IFrame Assignment Navigator 🧭

A simple **HTML and CSS-based Assignment Navigator** that uses a sidebar navigation menu and an **HTML `<iframe>`** to display multiple web development assignments within a single webpage.

## 📌 About the Project

The **HTML IFrame Assignment Navigator** is designed to demonstrate how multiple webpages can be organized and displayed through a single navigation interface.

The project contains a sidebar with assignment buttons. When an assignment is selected, its corresponding webpage is loaded inside the main **iframe area** without leaving the current page.

This project provides practical experience with **HTML iframes, anchor links, target attributes, and CSS Flexbox**.

## ✨ Features

* 🧭 Sidebar navigation for multiple assignments
* 🖼️ Displays webpages inside an iframe
* 🔗 Uses HTML anchor links for navigation
* 🎯 Loads selected pages without leaving the main interface
* 📐 CSS Flexbox-based layout
* 🔘 Styled navigation buttons
* 🎨 Simple and clean user interface
* 💻 Built using only HTML and CSS

## 🛠️ Technologies Used

| Technology | Purpose                                        |
| ---------- | ---------------------------------------------- |
| **HTML5**  | Page structure, navigation, links, and iframe  |
| **CSS3**   | Styling, layout, colors, and Flexbox           |
| **iframe** | Displaying other webpages inside the main page |

## 📂 Project Structure

```text id="y0m7c8"
HTML-IFrame-Assignment-Navigator/
│
├── index.html
└── README.md
```

> **Note:** The assignment pages displayed inside the iframe should also be available at the paths specified by the links in `index.html`.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the project folder.
3. Make sure the assignment HTML files are available at the correct locations.
4. Open **`index.html`** in any modern web browser.
5. Select an assignment from the sidebar.
6. The selected assignment will load inside the iframe.

## 📚 Concepts Learned

This project helps demonstrate the following web development concepts:

* HTML document structure
* HTML `<iframe>` element
* Anchor (`<a>`) tags
* `target` attribute
* Linking multiple HTML pages
* CSS Flexbox
* Sidebar navigation
* Button styling
* Layout and alignment
* Basic webpage organization

## 🔍 How the Navigation Works

The navigation links can target the iframe by assigning a name to the iframe.

For example:

```html id="8p3q5m"
<iframe name="assignmentFrame"></iframe>
```

A navigation link can then load a webpage inside that iframe:

```html id="k5qz2a"
<a href="assignment.html" target="assignmentFrame">
    Assignment 1
</a>
```

Instead of opening a new page, the linked webpage is displayed inside the iframe.

## 🎯 Purpose

The project was created as a learning exercise to understand how **iframes and navigation links** can be combined to build a simple multi-page assignment interface.

It is particularly useful for practicing basic HTML page integration and CSS layout techniques.

## 🔮 Future Improvements

Possible improvements include:

* Add more assignments
* Add active-state styling to the selected assignment
* Make the sidebar responsive for mobile devices
* Add icons to assignment buttons
* Add smooth transitions and animations
* Add assignment titles and descriptions
* Create a search or filter feature
* Add a modern dashboard-style interface

## 👨‍💻 Author

**Anurag Bhati**

GitHub: **[Anurag-Bhati9](https://github.com/Anurag-Bhati9)**

## 📄 License

This project is created for **educational and learning purposes**.

---

⭐ *A beginner-friendly project created to practice HTML iframes, navigation, and CSS Flexbox.*
