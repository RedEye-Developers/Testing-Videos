# 📦 Test-Assets

A centralized repository for storing reusable test assets used across applications such as REST APIs, mobile apps, and web clients.

This repository functions as a lightweight asset server by leveraging GitHub raw file URLs, making it easy to access test resources from anywhere.

---

## 📁 Folder Structure

```txt
/gifs        → GIF files for UI and feature testing  
/videos      → Sample video files  
/images      → Images for testing  
   /jpgs     → JPG image files  
   /pngs     → PNG image files  
   /svgs     → SVG vector files  
/jsons       → Mock JSON data and API responses  
```

---

## 🚀 Usage

Access files directly using GitHub's raw content URLs:

```txt
https://raw.githubusercontent.com/RedEye-Developers/Test-Assets/main/<folder-name>/<file-name>.<extension>
```

### 🔹 Example

```txt
https://raw.githubusercontent.com/RedEye-Developers/Test-Assets/main/videos/money-haist-reel.mp4
```

---

## 🔧 Use Cases

* Mock API responses during development
* Testing media uploads (images, videos, GIFs)
* Seeding frontend and mobile applications with sample data
* Integration testing across multiple services

---

## ⚠️ Notes

* Do not store sensitive or private data
* Keep file sizes within GitHub limits
* Use clear and consistent naming conventions
* Prefer adding files using GitHub’s **"Add file"** button (web UI)
* Avoid cloning the repository and pushing large batches of files

---

## 🧩 Best Practices

* Organize files logically by type
* Use descriptive file names (e.g., `user-profile.json`, `sample-video.jpg`)
* Keep the repository clean and easy to navigate

---

## 👨‍💻 Maintained By

**RedEye-Developers** 🚀
