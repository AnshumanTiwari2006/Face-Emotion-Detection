# Face-Emotion-Detection
😃 Real-Time Facial Emotion Detection using OpenCV and TensorFlow
This Python program uses a webcam to detect human facial emotions in real-time using a pre-trained deep learning model and Haar Cascade face detection. I have Jupyter Notebook for this.

🧠 Features
Real-time webcam feed using OpenCV
Facial detection with Haar Cascade
Emotion recognition using a CNN model trained on FER2013 dataset
Displays the predicted emotion label on the video feed
Optional support for eye detection
Visual text overlay: "Face Mapping"

🛠️ Requirements
Install dependencies with:

bash
Copy code
pip install tensorflow opencv-python numpy

📁 File Structure
plaintext
Copy code
.
├── emotion_model.h5               # Pre-trained model
├── haarcascades/
│   └── haarcascade_frontalface_default.xml
│   └── haarcascade_eye.xml        # (optional)
├── main.py                        # Main Python script
└── README.md                      # You're here!
📥 Haarcascade Files
haarcascade_frontalface_default.xml

haarcascade_eye.xml (optional)
Place these inside a folder called haarcascades/.

▶️ How to Run
bash
Copy code
python main.ipynb
To quit the webcam feed, press q.

🚀 What Can Be Improved
✅ Already Done:

Normalization and channel reshaping
Added “Face Mapping” label
Used a grayscale model input size (64, 64, 1)
Eye detection commented for flexibility

🔧 Recommended Enhancements:
Add a GUI using Streamlit or Tkinter
Show confidence score of emotion
Add logging of frames and predictions
Create a CSV log of emotions over time
Eye tracking with cursor movement or drowsiness detection

💡 Tip
Your model works best when:
Face is properly lit
Frontal view is captured

Emotion is clearly expressed

Try exaggerating the facial emotion for better results (e.g., raise eyebrows for surprise).
