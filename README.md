# Multi-Language HTML Editor

## Overview

This repository contains a web-based application designed to help your company easily create multi-language versions of your static HTML page. The tool allows translators without technical expertise to modify the HTML content of a page, translating text into multiple languages using a simple, intuitive interface.

## Features

- **DOM Manipulation for Multi-Language Support:** The application scans the HTML of the page and identifies each text node. Users can then translate each piece of text into the desired language directly within the application.
- **User-Friendly Interface:** Translators see the text nodes in a series of input fields, where they can input the corresponding translation for each text element.
- **Local Storage for Persistence:** All changes are automatically saved to the local storage of the browser. This ensures that users do not lose their progress even if the page is reloaded or the browser is closed.
- **HTML Output for Use:** After translations are completed, the application generates a new HTML file with the translated content. This file is provided as `[lang].html`, which can be saved, used on your site, or sent to a server.

## How It Works

1. **Text Extraction:** The tool scans the DOM of your existing page and extracts all text nodes.
2. **Translation Input:** Each text node is presented as an input field, allowing the user to input the translation for the text in the desired language.
3. **Live Updates:** As translations are entered, the corresponding parts of the page are updated in real-time.
4. **Local Storage Save:** Changes are automatically saved to the browser's local storage, so users can resume their work without losing progress.
5. **HTML Generation:** Once all translations are complete, the application generates a new HTML file with the translated content. This file can be saved as `[lang].html` and used directly on your site or sent to a server for further processing.

## Screenshot

Below is a screenshot of the application in action:

![Screenshot of the Multi-Language HTML Editor](/screenshot.png)

## Getting Started

To get started with this application:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/umutdeveloper/html-localization-tool
   ```
3. **Add the static assets:**
   Add you static page assets into assets or other static files folder.
4. **Open the Application:** 
   Open the `index.html` file in your browser to start the application.
5. **Paste Your HTML Code:** 
   Paste the HTML code of your page to begin the translation process.
6. **Translate:** 
   Input translations for each text node in the provided input fields.
7. **Save Your Work:** 
   The application saves your progress automatically. You can also copy the translated HTML code when you're done.

## Demo

You can try the live demo of the application at the following address:

[https://umutdeveloper.github.io/html-localization-tool/](https://umutdeveloper.github.io/html-localization-tool/)

## Example

Suppose your static page includes the following text:

```html
<p>This website uses cookies to enhance your experience.</p>
```

After translating to Spanish, the application will generate:

```html
<p>Este sitio web utiliza cookies para mejorar su experiencia.</p>
```

You can copy the output then save this as `es.html` for the Spanish version of your page.

## Contributing

We welcome contributions! Please fork this repository and submit a pull request with your changes.

## Contact

If you have any questions or feedback, feel free to open an issue or contact us at [umutcakirbm@gmail.com](mailto:umutcakirbm@gmail.com).
