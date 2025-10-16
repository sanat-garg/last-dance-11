# Markdown to HTML Converter

## Description

This is a simple, static web application that converts Markdown text to HTML and displays it in a browser. It leverages the `marked.js` library (or a simplified replacement) for Markdown parsing and `highlight.js` for syntax highlighting of code blocks.  The application is fully self-contained within a single HTML file, with embedded CSS and JavaScript for ease of deployment.

## Features

*   **Markdown Conversion:** Converts Markdown text into HTML using a basic or external parser.
*   **Syntax Highlighting:** Highlights code blocks within the Markdown content using `highlight.js`.
*   **Static Deployment:**  The application is a single HTML file, making it easy to deploy on any static web server (e.g., GitHub Pages).
*   **Responsive Design:** The layout adapts to different screen sizes, providing a good user experience on both desktop and mobile devices.
*   **Clean and Modern Design:** Features a visually appealing, modern color scheme.

## How to Use

1.  **Deployment:**  Deploy the `index.html` file to a static web server or open it directly in your browser.

2.  **Input:** The application automatically loads and converts the `file-0` attachment which contains markdown as base64.

3.  **Output:** The converted HTML will be displayed within the `#markdown-output` section of the page.  Code blocks will be automatically highlighted.

## Technologies Used

*   HTML
*   CSS (Embedded)
*   JavaScript (Vanilla, Embedded)
*   [highlight.js](https://highlightjs.org/) - For code syntax highlighting.