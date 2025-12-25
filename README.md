# 🕵️‍♂️ .0xR00t | Deep Metadata Forensics

> **Client-Side Image Forensics & Metadata Extraction Tool**
> *Advanced EXIF, XMP, IPTC, and GPS Analyzer with a Cyberpunk Interface.*

![Version](https://img.shields.io/badge/Version-2.0-green?style=for-the-badge)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20JS%20%7C%20Tailwind-blue?style=for-the-badge)
![Privacy](https://img.shields.io/badge/Privacy-100%25%20Client--Side-red?style=for-the-badge)

## 📜 Overview

**.0xR00t** is a lightweight, web-based digital forensics tool designed to extract hidden metadata from image files. Built with a **"Hacker/Cyberpunk" aesthetic**, it runs entirely in your browser using the powerful `exifr` library.

Unlike online tools that upload your files to a server, **.0xR00t processes everything locally**, ensuring 100% privacy for sensitive forensic investigations.

## ✨ Key Features

* **⚡ Zero-Upload Privacy:** Files are processed locally in your browser's memory. No data leaves your machine.
* **🧩 Deep Extraction:** Parses **EXIF, TIFF, XMP, IPTC, ICC, JFIF, and GPS** data blocks.
* **🗺️ Geo-Intelligence:** Automatically detects GPS coordinates and generates a direct **Google Maps** link.
* **🎨 Cyberpunk UI:** Features a dynamic **Matrix Rain** background, glowing borders, and a terminal-style interface.
* **📂 Multi-Format Support:** Works with JPG, PNG, HEIC, TIFF, and WEBP.
* **📋 JSON Export:** One-click button to copy raw metadata logs for reporting.

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Parsing Engine:** [exifr](https://github.com/MikeKovarik/exifr) (CDN)
* **Icons/Fonts:** FontAwesome & JetBrains Mono.

## 🚀 How to Run

Since this tool is built using CDNs, you don't need `npm` or a backend server.

1.  **Download the Code:**
    Save the code as `index.html`.

2.  **Open in Browser:**
    Simply double-click `index.html` to open it in Chrome, Firefox, or Edge.

    > **Note:** An active internet connection is required initially to load the Tailwind CSS and Exifr libraries via CDN.

## 📸 Usage Guide

1.  **Launch the Tool:** You will see the Matrix animation and the Drop Zone.
2.  **Upload Image:** Drag and drop an image or click to select.
3.  **Analyze:** The tool will decrypt the binary data instantly.
4.  **Review Data:** Scroll through the "Extraction Logs" to see hidden details (Device model, Date, Software used, Shutter speed, etc.).
5.  **Geo-Locate:** If GPS data is found, click the **"VIEW LOCATION ON MAPS"** button.

## ⚠️ Limitations

* **Social Media Stripping:** Images downloaded from Facebook, Instagram, or WhatsApp usually have their metadata stripped for privacy. This tool works best on **original** files (from cameras or raw backups).
* **Soft 404/Empty Data:** If an image has no metadata, the tool will display a "NO METADATA DETECTED" warning.

## 🤝 Contributing

Feel free to fork this project and add features like:
* Batch processing.
* Hex viewer integration.
* Steganography detection.

## ⚖️ License & Disclaimer

**For Educational & Forensic Use Only.**
The creator is not responsible for how this tool is used. Ensure you have permission to analyze files that do not belong to you.

---
**Developed by .0xR00t LABS // Decentralized Forensics**
