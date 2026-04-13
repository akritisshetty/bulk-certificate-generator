# Certificate Tools

A browser-based toolkit for creating and signing certificates. The suite includes two tools available on a single page: a Bulk Certificate Generator and a Certificate Signature Studio. No server or installation required; everything runs entirely in the browser.

## Tools

### Bulk Certificate Generator

Generate personalized certificates in bulk using a certificate template image and an Excel or ODS data file. Upload your template, upload your recipient list, map text fields visually on the canvas, and download all certificates as a ZIP in one click.

### Certificate Signature Studio

Add one or more signature images to an individual certificate. Upload a certificate template, add signature images, drag and resize them into position, and download the final signed certificate as a PNG.

## Features

**Bulk Certificate Generator**

- Upload a certificate template (PNG or JPG)
- Upload an Excel or ODS file with recipient names and fields
- Click-to-position dynamic text fields on the template canvas
- Customize font, size, color, and alignment per field
- Live preview with the first row of data
- Download a sample certificate before generating all
- Generate all certificates and download as a ZIP
- Handles Excel date fields and custom number formats automatically

**Certificate Signature Studio**

- Upload a certificate template (PNG, JPG, or WEBP)
- Add one or more signature images (PNG, JPG, or WEBP)
- Drag signature overlays to reposition on the canvas
- Resize signatures by dragging the corner handle
- Set precise position and size via numeric inputs
- Click-to-place mode for accurate positioning
- Download the signed certificate as a full-resolution PNG

## How It Works

### Bulk Certificate Generator

1. Switch to the Bulk Certificate Generator tab
2. Upload your certificate template image
3. Upload an Excel or ODS file with participant names and details in columns
4. Map each data column to a position on the certificate by clicking on the canvas
5. Adjust font, size, and color per field
6. Preview a sample certificate, then generate and download all certificates as a ZIP

### Certificate Signature Studio

1. Switch to the Certificate Signature Studio tab
2. Upload a certificate template image
3. Add one or more signature images using the sidebar
4. Drag each signature into position on the canvas, or use Click to Place mode
5. Resize signatures as needed using the corner drag handle or numeric inputs
6. Download the final signed certificate as a PNG

## Tech Stack

| Component        | Technology            |
| ---------------- | --------------------- |
| Frontend         | HTML, CSS, JavaScript |
| Excel Parsing    | XLSX.js               |
| ZIP Creation     | JSZip                 |
| Canvas Rendering | HTML5 Canvas API      |
