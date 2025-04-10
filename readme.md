## Driver Drowsiness Detection  

### Description  
This project implements a real-time driver drowsiness detection system using OpenCV, Dlib, and facial landmark detection

### Features  
- Real-time eye tracking   
- Drowsiness detection  
- Alerts when prolonged drowsiness is detected

### Installation  

1. **Clone the repository:**  
   ```bash
   git clone <your-repo-url>
   cd driver_drowsiness
   ```

2. **Install dependencies:**  
   ```bash
   pip install opencv-python imutils dlib scipy
   ```

3. **Download the required facial landmark model:**  
   - Download `shape_predictor_68_face_landmarks.dat` from [dlib's model repository](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2)  
   - Extract and place it in the project directory  

### Usage  

Run the script:  
```bash
python driver_drosiness.py
```

Ensure your webcam is connected, and the system will start monitoring for drowsiness.  

### Requirements  
- Python 3.x  
- OpenCV  
- Dlib  
- imutils  
- SciPy  

### NOTE
 - You have to clone the yolov5 dir from github in the DD directory
