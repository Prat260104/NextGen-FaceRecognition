# NextGen Face Recognition



NextGen Face Recognition is a **real-time face recognition system** built with Python using **PyTorch, Facenet-PyTorch, and OpenCV**. It can recognize multiple people in real-time, even under minor occlusions like glasses, with high accuracy using a few images per person.

---

## Features

- Real-time webcam-based face recognition
- Handles multiple faces at once
- Works with **5–10 images per person**, including variations (with/without glasses)
- Easy to add new people on the fly
- Works cross-platform: **Windows and Mac**
- Optimized for **accuracy and speed** with frame skipping and embedding averaging
- Supports both **CPU and GPU** (if available)

---



## Folder Structure

NextGen-FaceRecognition/
├── dataset/ # Folder containing images of each person
│ ├── Person1/
│ │ ├── 1.jpg
│ │ ├── 2.jpg
│ │ └── ...
│ └── Person2/
├── main.py # Main script for running real-time face recognition
├── requirements.txt # All required dependencies
├── README.md # This file
└── .gitignore # Ignored files (dataset, venv, etc.)


### 1. Clone the repository

```bash
git clone https://github.com/Prat260104/NextGen-FaceRecognition.git
cd NextGen-FaceRecognition
```

2. Create a virtual environment (recommended)
# Mac/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

# Windows
```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

4. Prepare the dataset

Create a folder named dataset in the project root.

Structure:

dataset/
   Person1/
      img1.jpg
      img2.jpg
   Person2/
      img1.jpg


5. Run the face recognition
```bash
# Make sure your virtual environment is activated
python main.py
```

