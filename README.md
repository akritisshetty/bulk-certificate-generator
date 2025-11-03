# Bulk Certificate Generator

A web-based tool to generate personalized certificates in bulk using a certificate template image and Excel/ODS data. Upload your template, upload your recipient list, map the text fields visually, and download all certificates in one click. No server required.

## Features

* Upload certificate template (PNG/JPG)
* Upload Excel/ODS file with names and fields
* Click-to-position dynamic text fields on the template
* Customize font, size, color, and alignment per field
* Live preview on canvas
* Download sample certificate
* Generate all certificates and download as ZIP
* Runs entirely in the browser

## How It Works

1. Upload your certificate template image
2. Upload Excel or ODS file with participant names and details
3. Map each data field to a position on the certificate by clicking on the canvas
4. Adjust font, size, and color
5. Preview a sample
6. Generate and download all certificates

This project uses HTML Canvas to render each certificate and JSZip to bundle all outputs.

## Tech Stack

| Component        | Technology            |
| ---------------- | --------------------- |
| Frontend         | HTML, CSS, JavaScript |
| Excel Parsing    | XLSX.js               |
| ZIP Creation     | JSZip                 |
| Canvas Rendering | HTML5 Canvas API      |
