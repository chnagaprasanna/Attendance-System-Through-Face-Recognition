# Attendance System Through Face Recognition

## 📌 Overview

This project is a **Face Recognition-based Attendance System** built using **Python, OpenCV, and Tkinter**. It captures faces, stores them, and recognizes registered individuals to mark attendance automatically.

## ✨ Features

- **Face Registration**: Capture and store face data for individuals.
- **Real-time Face Recognition**: Identify registered users and mark attendance.
- **Attendance Logging**: Store attendance data in a CSV file.
- **GUI Interface**: User-friendly interface using Tkinter.
- **Database Integration**: Uses Pandas to manage and process attendance data.

---

## 🚀 Installation & Setup

### 1️⃣ Prerequisites

Ensure you have the following installed:

- Python (3.7+ recommended)
- Git
- Virtual Environment (optional but recommended)

### 2️⃣ Clone the Repository

```sh
 git clone https://github.com/chnagaprasanna/Attendance-System-Through-Face-Recognition.git
 cd Attendance-System-Through-Face-Recognition
```

### 3️⃣ Create & Activate Virtual Environment (Optional but Recommended)

#### On Windows:

```sh
python -m venv venv
venv\Scripts\activate
```

#### On macOS/Linux:

```sh
python3 -m venv venv
source venv/bin/activate
```

### 4️⃣ Install Required Dependencies

```sh
pip install -r requirements.txt
```

---

## 🏃‍♂️ Running the Application

```sh
python main.py
```

This will launch the Tkinter-based GUI where you can:

- Register new users.
- Recognize faces and mark attendance.
- View and export attendance records.

---

## 📂 Project Structure

```
📁 Attendance-System-Through-Face-Recognition
│── main.py                  # Main script to run the app
│── requirements.txt         # Dependencies list
│── StudentDetails/          # Folder to store registered face images
│── TrainingImage/           # Pre-trained models for face detection
│── attendance.csv           # Attendance records
│── README.md                # Project documentation
```

---

## 🔧 Troubleshooting

### 1️⃣ IndexError: index 0 is out of bounds for axis 0 with size 0

- This means no matching record was found in the attendance dataset.
- Ensure that the face is properly registered before recognition.

### 2️⃣ Large File Warning on GitHub

- If you're facing GitHub warnings about large files, use **Git LFS**:

```sh
git lfs install
git lfs track "venv/Lib/site-packages/cv2/cv2.pyd"
git add .gitattributes
git commit -m "Track large files using Git LFS"
git push origin main
```

---

## 📞 Contact

- **GitHub**: [@prasanna-chintamaneni](https://github.com/chnagaprasanna)
- **LinkedIn**: [Chintamaneni Nagaprasanna](https://www.linkedin.com/in/chintamaneninagaprasanna/)

