# # 🎨 ASP Class Poster Generator

A specialized, browser-based tool designed for the **Aamar School Project (ASP)** to generate standardized social media posters for Math & Science classes.

![Project Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-Web-blue)
![Language](https://img.shields.io/badge/Language-Bangla-brightgreen)

## 📖 Description

This tool automates the creation of high-quality event posters. Instead of manually editing Photoshop files for every class, instructors can simply enter the class details, upload photos, and download a perfectly formatted image ready for Facebook and Instagram.

It enforces brand consistency (fonts, colors, layout) while being accessible from any device (mobile or desktop).

## ✨ Key Features

* **⚡ Real-Time Preview:** Instantly visualizes changes as you type names, dates, and locations.
* **📱 Mobile-First Design:** The preview window automatically scales to fit small mobile screens while preserving the full HD resolution for export.
* **🖼️ Smart Image Handling:**
    * Automatic circular cropping for instructor/student photos.
    * Restricted file inputs to ensure only images are selected.
* **⬇️ HD Export:** Uses `html2canvas` to generate a crisp **1080x1350px (4:5 ratio)** PNG file, optimized for social media feeds.
* **🎨 Brand Consistency:**
    * **Font:** Hind Siliguri (Google Fonts) for beautiful Bangla typography.
    * **Theme:** Dark scientific theme (`#020617`) with gold and blue accents.
    * **Logo:** Auto-embeds the ASP logo.

## 🚀 How to Use

1.  **Open the Tool:** Simply open `index.html` in any modern web browser. No installation or server required.
2.  **Enter Class Info:**
    * Update the Date, Time, and Location fields.
    * Fill in the names and details for the Primary, Junior, and Secondary groups.
3.  **Upload Photos:** Click the camera icon buttons to select images for each instructor.
4.  **Download:** Click the **"Download HD Poster"** button to save the final image to your device.

## 🛠️ Technology Stack

* **HTML5 & CSS3:** For structure and styling.
* **JavaScript (Vanilla):** For logic and interactivity.
* **[html2canvas](https://html2canvas.hertzen.com/):** For rendering the DOM element into a downloadable image.
* **FontAwesome:** For UI icons.

## 📂 Project Structure

```text
/
├── index.html       # The main application file
├── README.md        # Project documentation
└── asplogo.png      # (Optional) Local logo file if needed
