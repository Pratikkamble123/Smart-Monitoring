Thanks! Here's the **updated `README.md` format** with your **Prerequisites and Installation instructions** correctly included and organized:

---

````markdown
# 📸 Smart Attendance Capture

A face recognition-based smart attendance monitoring system developed using **OpenCV**, **Python**, and **Machine Learning**, featuring a web interface for teachers and students. The system recognizes registered faces from a webcam stream and logs attendance automatically.

---

## 🌐 Project Overview

The Smart Attendance Capture system automates attendance by recognizing faces in real time.

### ✅ Key Features

- 👨‍🏫 Teacher & Student Registration
- 🎦 Live Face Recognition via Webcam
- 🧠 Automatic Name Detection using ML
- 📋 Attendance Export to Excel
- 📊 Subject-wise Attendance Stats
- 🚫 Unknown Face Detection
- 🌐 Web Interface

---

## 🧰 Tech Stack

| Layer       | Technology                        |
|-------------|-----------------------------------|
| Frontend    | HTML, CSS, JavaScript             |
| Backend     | Node.js, Express.js               |
| Face Recog. | Python, OpenCV, face_recognition  |
| Database    | MongoDB                           |
| Reporting   | Pandas, OpenPyXL                  |

---

## ⚙️ Prerequisites

Make sure you have the following installed on your system:

- Node.js & npm
- Python (>= 3.6)
- MongoDB

### 🔧 Update npm to the latest version

```bash
npm install npm@latest -g
````

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/staticshreyas/Attendance-Portal.git
cd Attendance-Portal
```

### 2. Install Node.js Packages (from root)

```bash
npm install
```

### 3. Install Python Packages (from Py-Scripts)

```bash
cd ./Py-Scripts
pip install -r requirements.txt
```

---

## 🚀 Running the Project

### 1. Start the Express Server (from root)

```bash
npm start
```

### 2. Start the Flask Server (Python - Face Recognition)

```bash
cd ./Py-Scripts
python app.py
```

### 3. Start MongoDB Server

```bash
mongod --dbpath YOUR_PATH
```

---


## 📦 Output

* Excel files are generated with subject-wise attendance
* `"Not a part of class"` label for unregistered students
* Percentage calculation displayed per student

---

## 🖥️ Screenshots

> Replace image links with your actual hosted screenshots

* Homepage
<img width="1842" height="854" alt="Image" src="https://github.com/user-attachments/assets/b076bee1-9254-46c2-a184-fb27f09a33ef" />

* Face Detected
  ![Face Detected](https://your-link/face_detected.png)

* Unknown Face
  <img width="967" height="716" alt="Image" src="https://github.com/user-attachments/assets/d80839a4-dcef-46ec-a627-2607d531819f" />

* Excel Output
  ![Excel](https://your-link/excel_output.png)

---

## ✍️ Author

**Pratik Kamble**
📧 [dpratikkamble@gmail.com](mailto:dpratikkamble@gmail.com)
🌐 [LinkedIn](https://linkedin.com/in/pratikkamble-dev) | [GitHub](https://github.com/pratikkamble-dev)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

```
