Here's the complete `README.md` file **format** for your **Smart Attendance Capture** project, ready to copy-paste or save as a markdown file:

---

```markdown
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
├── face\_recognition/
│   ├── recognizer.py
│   ├── train.py
│   └── attendance\_logger.py
├── dataset/
│   └── \[User images]
├── attendance/
│   └── \[Excel sheets]

````

---

## 🖥 Screenshots

> Replace image links with your own URLs

### 🔸 Home Page  
![Home Page](https://your-image-link/homepage.png)

### 🔸 Face Detection  
![Face Detected](https://your-image-link/face_detected.png)

### 🔸 Unknown Face  
![Unknown](https://your-image-link/unknown.png)

### 🔸 Excel Output  
![Excel](https://your-image-link/excel.png)

---

## 🚀 How to Run

### 🔹 Clone the Project

```bash
git clone https://github.com/yourusername/smart-attendance-capture.git
cd smart-attendance-capture
````

### 🔹 Setup Backend

```bash
cd backend
npm install
node app.js
```

### 🔹 Setup Python Scripts

```bash
cd face_recognition
pip install -r requirements.txt
python recognizer.py
```

### 🔹 Open Frontend

* Open `frontend/index.html` in a browser.
* Or deploy it on [Vercel](https://vercel.com/) or [GitHub Pages](https://pages.github.com/).

---

## ⚙️ Requirements

### Python

```bash
pip install opencv-python face_recognition pandas openpyxl
```

### Node.js

```bash
npm install express mongoose multer passport nodemailer
```

---

## 📦 Output

* Excel sheets saved with subject-wise attendance
* Format:

  * `"Not a part of class"` – unregistered faces
  * Percentage calculation per subject

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

Let me know if you'd like me to:

- Generate a downloadable `.md` file
- Add your actual image links
- Include GitHub deployment links or Vercel setup instructions

I'm happy to assist!
```
