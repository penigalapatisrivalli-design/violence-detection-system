🚨 Violence Detection System

A deep-learning based application for detecting violent and non-violent activities from video input.

📌 Project Overview

This project uses computer vision and deep learning techniques to analyze video and identify whether the observed activity is violent or non-violent. The system can process video input and provide the detection result through an easy-to-use interface.

The project is intended as an academic demonstration of how artificial intelligence can be applied to video-based safety monitoring.

✨ Features

* 🎥 Video-based violence detection
* 🧠 Deep learning based classification
* 📹 OpenCV for video processing
* 🖥️ Streamlit-based interface
* ⚡ Supports analysis of video input
* 📊 Displays the detection result
* 💾 Can be used with sample video files for testing

🛠️ Technologies Used

* Python
* OpenCV
* Deep Learning
* TensorFlow / Keras
* Streamlit
* NumPy
* Jupyter Notebook

📂 Project Structure

violence-detection-system/
│
├── models/
├── Video_Voilence_detection_with_details (1).ipynb
├── main.py
├── predict.py
├── predict2.py
├── requirements.txt
├── README.md
└── sample video files

🚀 How to Run

1. Clone the repository

git clone https://github.com/penigalapatisrivalli-design/violence-detection-system.git
cd violence-detection-system

2. Install the required libraries

pip install -r requirements.txt

3. Run the application

Depending on the application file being used:

streamlit run main.py

4. Test the system

Upload or provide a suitable video and allow the application to process it. The system will analyze the video and display the predicted activity.

📓 Notebook

The repository also contains the Jupyter Notebook:

Video_Voilence_detection_with_details (1).ipynb

It contains the development and experimentation work related to the video violence-detection system.

🔮 Future Improvements

* Improve detection accuracy with a larger and more diverse dataset
* Add real-time CCTV/webcam monitoring
* Add an automatic alert when violence is detected
* Improve the user interface
* Reduce false detections
* Deploy the system as a web application

📚 Reference

This project is based on and developed from an existing open-source violence-detection project:

https://github.com/siddhu1919/Realtime-Violence-Detection_Using-DeepLearning-OpenCV-Streamlit

The original project and its contributors are acknowledged here for the base implementation and ideas.

⚠️ Disclaimer

This project is intended for educational and research purposes. Violence detection predictions may not always be accurate and should not be treated as a replacement for human judgment or professional security systems.
