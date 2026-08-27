# Image & PDF Tool

> A simple, browser-based toolkit for resizing images and working with PDF files — built with plain HTML, CSS, and JavaScript.

## 🚀 Live Demo

**Try it now:** https://image-resizer-by-vikrant.netlify.app/

---

## ✨ Features

This project combines multiple useful image and PDF utilities in one lightweight web app.

### 🖼️ Image Resizer
- Upload JPG, PNG, or WEBP images
- Resize by target width and height
- Maintain aspect ratio when needed
- Optimize an image toward a target file size
- Preview the original and processed image
- Download the final image

### 📄 Image to PDF
- Select multiple images
- Convert images into a PDF
- Arrange the images before generating the PDF
- Download the generated PDF

### 🧩 Merge PDF
- Add multiple PDF files
- Combine them into a single PDF
- Download the merged document

### 🖼️ PDF to Image
- Upload a PDF
- Render PDF pages as images
- Preview the converted pages
- Download the generated images

### 📦 Compress PDF
- Upload a PDF
- Process the document to reduce its size where possible
- Download the compressed result

### 🌙 Dark / Light Mode
Switch between dark and light themes for a more comfortable experience.

---

## 🛠️ Tech Stack

- **HTML5** — application structure
- **CSS3** — responsive UI, glass-style design, themes
- **JavaScript** — client-side image and PDF processing
- **pdf-lib** — PDF creation and manipulation
- **PDF.js** — PDF rendering
- **JSZip** — packaging downloaded image files

All processing is designed to happen in the browser, so files do not need to be uploaded to a backend for the core tools.

---

## 📁 Project Structure

```text
image-pdf-tool/
├── index.html   # Complete web application
└── README.md    # Project documentation
```

The current project is intentionally lightweight and can be run as a static website.

---

## ▶️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/vikantdbg/image-pdf-tool.git
```

### 2. Open the project folder

```bash
cd image-pdf-tool
```

### 3. Run the app

Because this is a static web app, you can open `index.html` directly in a modern browser.

For a local development server, you can also use any static server. For example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 🌐 Deployment

This project can be deployed easily to static hosting platforms such as Netlify, GitHub Pages, or Vercel.

The current live version is hosted on Netlify:

**https://image-resizer-by-vikrant.netlify.app/**

---

## 🔒 Privacy

The application is designed around client-side processing for its main image and PDF operations. Files selected in the browser are processed locally by the web application rather than being sent to a custom backend.

Third-party CDN resources used by the page, such as PDF libraries, are loaded from their respective public CDNs.

---

## 📱 Responsive Design

The interface is designed to work across desktop and mobile screen sizes, with responsive layouts and touch-friendly controls.

---

## 🎯 Use Cases

This tool is useful for quick everyday tasks such as:

- Reducing image dimensions before uploading
- Preparing images for forms and websites
- Converting image collections into PDFs
- Combining multiple PDFs
- Turning PDF pages into images
- Creating smaller document files for sharing

---

## 👨‍💻 Author

**Vikrant**

Built as a practical browser-based image and PDF utility.

---

## ⭐ Support the Project

If you find this project useful, consider giving the repository a ⭐ on GitHub.
