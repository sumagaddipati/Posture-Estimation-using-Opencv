# Posture-Estimation-using-Opencv

# 🏋️‍♂️ Dumbbell Workout Counter Using OpenCV & MediaPipe  

Track your workout reps using **Pose Estimation**! This project utilizes **OpenCV** and **MediaPipe** to detect arm movement and count dumbbell curls automatically.  

## 🚀 Features  

✅ **Real-time pose tracking** using MediaPipe  
✅ **Counts repetitions dynamically** based on arm movement  
✅ **Live progress bar** showing movement percentage  
✅ **FPS Display** for performance monitoring  
✅ Works with **webcam** or **pre-recorded videos**  

## 🛠 Tech Stack  

Python 🐍 | OpenCV 🎥 | MediaPipe 🏋️ | NumPy 🔢  

## 📸 Demo  


## 🎮 Usage  

1️⃣ **Run the script**  
```bash
python main.py

2️⃣ Perform dumbbell curls 💪

Move your arm down to start a rep
Move your arm up to complete it

3️⃣ The counter updates automatically! 🎯

4️⃣ Press 'q' to exit

**🔍 Code Overview**
The script processes video input, detects arm movement, and updates the repetition count dynamically.

**Key Functions**
Pose Detection 🏃‍♂️: Identifies body landmarks using MediaPipe
Angle Calculation 📐: Tracks elbow flexion to determine movement
Dynamic Rep Counter 🔢: Increments count when full range of motion is detected
Visual Feedback 🎨: Displays live count and progress bar
🤝 Contribute
Fork the project and improve it! 🚀 PRs are welcome!
