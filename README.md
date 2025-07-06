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

## 📁 Project Structure

```
smart-attendance-capture/
├── frontend/
│   ├── index.html
│   ├── login.html
│   └── styles/
├── backend/
│   ├── app.js
│   ├── routes/
│   ├── models/
├── Py-Scripts/
│   ├── app.py
│   ├── recognizer.py
│   └── attendance_logger.py
├── dataset/
│   └── [User images]
├── attendance/
│   └── [Excel sheets]
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
  ![Homepage](https://your-link/homepage.png)

* Face Detected
  ![Face Detected](https://your-link/face_detected.png)

* Unknown Face
  ![Unknown Face](https://your-link/unknown.png)

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

---

Let me know if you'd like this as a downloadable file (`README.md`), or if I should help you generate hosted image links or automate deployment with Vercel/GitHub Pages.
```
