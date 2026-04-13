# PDF & Image Workspace

A lightweight, serverless web application that lets you effortlessly manage your PDF files and images. Merge, reorder, compress, and split documents entirely within your browser. 

Since there is no backend server, your files never leave your device, ensuring 100% privacy and security.

## Features

* **Drag & Drop Uploads:** Easily add `.pdf`, `.jpg`, `.jpeg`, and `.png` files.
* **Visual Workspace:** See thumbnail previews of every single page.
* **Drag & Drop Reordering:** Rearrange pages across different documents intuitively.
* **Include/Exclude Pages:** Click to remove unwanted pages. Hold `SHIFT` to select and exclude a whole range of pages at once.
* **Rotate Pages:** Fix the orientation of upside-down pages with a single click.
* **Extract Pages:** Download any specific page as a standalone PDF.
* **Export Final PDF:** Combine all your selected and arranged pages into one clean, optimized PDF file.

## Technologies Used

This project is built using standard web technologies and powerful open-source libraries:

* **HTML5, CSS3, Vanilla JavaScript**
* **[pdf-lib](https://pdf-lib.js.org/):** For creating, modifying, and merging PDF documents.
* **[PDF.js](https://mozilla.github.io/pdf.js/):** (by Mozilla) For rendering PDF pages into visual canvas previews.
* **[SortableJS](https://sortablejs.github.io/Sortable/):** For the smooth drag-and-drop grid interface.

## How to Run / Deployment

Because this is a static, client-side only application, there is no build process or server setup required.

### Local Usage
1. Clone this repository or download the `index.html` file.
2. Double-click `index.html` to open it in any modern web browser.
3. Start editing your PDFs!

## Usage Tips
* **Quick Range Selection:** Click the **✕** on your first page, hold the **SHIFT** key, and click the **✕** on your last page to exclude the entire range instantly. Hover over any excluded page to restore it.
* **Image Handling:** You can drop photos directly into the workspace. The app will automatically convert them to the correct PDF dimensions and compress them to save space.

## ⚠️ Disclaimer

**AI-Generated Project:** Please note that the code, styling, and documentation for this project were primarily generated and refined with the assistance of AI.

This project is open-source.
