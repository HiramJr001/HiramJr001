# Hiram Galindo José Júnior

Software developer focused on internal tooling, process automation, and AI-assisted document processing. Based in Ituverava, SP, Brazil.

[Portfolio](https://hiramjr001.github.io) [LinkedIn](https://linkedin.com/in/hiram-galindo-jr-b0bb33330) · [Email](mailto:hiramgalindojr11@gmail.com) · +55 16 99247-3333

---

## About

I hold a Bachelor's degree in Systems Analysis and Development from Unifran (Universidade de Franca), 2025. I currently work as an Office Assistant at Inovare Contabilidade, where my role has evolved to include building software that automates and streamlines office operations — from a company website built from scratch to internal tools that cut recurring task processing time by roughly two days.

My focus areas are practical automation, front-end development, and integrating AI APIs into real workflows, particularly around document extraction and data structuring.

---

## Experience

**Office Technologist assistant — Inovare Contabilidade**
*October 2024 – Present*

- Designed and built the company's first website from the ground up, doubling overall site and Instagram engagement
- Identified logistical bottlenecks in daily office workflows and developed an internal productivity application, cutting processing time by approximately 2 days on recurring HR and bidding-department tasks; rolled out for use by the broader team
- Built a document-extraction tool integrating an AI API to automatically read and organize data from timesheets, invoices, and admission forms into structured Excel spreadsheets, used to process a batch of 140 employee admission documents far faster than manual entry
- Redesigned the company's Instagram from the ground up, including a new logo and standardized visual identity, doubling profile views and client inquiries
- Provided hardware/software troubleshooting, printer maintenance, and general IT support for the office

**Tech stack:** Python, JavaScript, React, Node.js, MySQL, Tailwind CSS, Vite

---

## Projects

**BackOffice OS — Internal Operations Suite 2025 – Present**
- github.com/HiramJr001/backoffice-os — solo build, in daily production use
Document Guardian engine: locates expiry dates across a network share of 80,000+ client documents using a four-level cascading filter
(folder pruning, filename ranking, native PDF text, OCR fallback), so expensive OCR runs on a small fraction of files instead of all of them.
Made the scan resumable: each company is committed to a SQLite checkpoint across CPU-1 worker processes, so a dropped network share,
reboot or manual stop resumes instead of restarting a multi-hour job.
Built confidence-scored extraction that routes low-evidence documents to manual review instead of guessing a date, with a parser written
for real OCR noise — broken spacing, missing accents, "valid for N months" plus issue date.
Shipped it as a single Windows installer (electron-builder, PyInstaller, embedded Tesseract): the end user installs one .exe with no runtime
setup. Document categories are declarative profiles, so adding a type needs no engine change.
Stack: Python, PyMuPDF, Tesseract OCR, SQLite, Flask, openpyxl, JavaScript, Electron, PyInstaller
---

## Education

**Bachelor of Science in Systems Analysis and Development** — Unifran, Universidade de Franca (2025)

Relevant coursework: Data Structures, Database Systems, Object-Oriented Programming, Software Engineering, Web Programming, Mobile Application Development, Cloud Computing, Big Data, Parallel and Distributed Computing, Client/Server Systems, Systems Analysis and Design, Computer Networks, Software Quality

---

## Skills

**Languages:** Python, JavaScript, Java
**Frontend:** React, Tailwind CSS, HTML/CSS, Vite
**Backend & Data:** Node.js, MySQL
**Tools:** Git, REST APIs, AI API Integration, PDF.js

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Languages

- Portuguese: Native
- English: B2 (Upper Intermediate)

---

## GitHub Stats

![Hiram's GitHub stats](https://github-readme-stats.vercel.app/api?username=HiramJr001&show_icons=true&theme=default&hide_title=false)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=HiramJr001&layout=compact&theme=default)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=HiramJr001&theme=default)
