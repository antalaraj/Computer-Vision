# 🏀 AI Sports Broadcast Tracking (YOLOv8 + ByteTrack)

An advanced, deep learning-powered computer vision pipeline designed to track players and sports balls in dynamic broadcast footage. This project renders real-time bounding boxes and fading broadcast-style trajectory trails, simulating professional sports analytics overlays.

## 🚀 The Engineering Problem & Solution

Tracking a basketball on a wooden court is a notorious challenge in classical computer vision. 
* **The Classical Failure:** Algorithms like CamShift track color (Hue) and background subtractors (MOG2) look for motion. In basketball broadcasts, the camera pans constantly (confusing motion detectors), and the orange ball perfectly camouflages with the orange/brown wooden floor (confusing color trackers).
* **The Deep Learning Solution:** This project utilizes **YOLOv8** to understand the semantic, structural shape of a `person` and a `sports ball`, completely ignoring the floor color and camera panning. It is paired with the **ByteTrack** algorithm to maintain persistent IDs even when players occlude (block) each other.

## ✨ Key Features
* **State-of-the-Art Object Detection:** Utilizes Ultralytics YOLOv8m (Medium) for high-accuracy, real-time detection of players (Class 0) and sports balls (Class 32).
* **ByteTrack ID Persistence:** Re-identifies players correctly even after they run behind another player or the referee.
* **Broadcast Trajectory Trails:** Calculates the center-bottom of players and true-center of the ball to draw dynamic, fading historical motion trails.
* **Cloud-Optimized Architecture:** Optimized for Jupyter Notebooks and Google Colab to bypass browser memory limits by automatically mounting and saving rendered videos directly to Google Drive.

## ⚙️ Installation & Setup

### Requirements
* Python 3.8+
* Jupyter Notebook (`jupyter`)
* OpenCV (`opencv-python`)
* NumPy (`numpy`)
* Ultralytics YOLOv8 (`ultralytics`)


4. Update the `INPUT_VIDEO_PATH` in the notebook to point to your local video file and run the cells.

### Google Colab Execution (Recommended for GPU Acceleration)

1. Upload the `sports_tracker.ipynb` file to your Google Drive and open it with Google Colab.
2. Install the YOLOv8 dependencies by running the first cell:
```bash
!pip install ultralytics

```


3. Upload your target video (e.g., `sports_video.mp4`) to the Colab file explorer on the left sidebar.
4. Run the remaining cells. The notebook will process the video, prompt you to connect your Google Drive, and instantly back up the finished `.mp4` file to your Drive to prevent browser download crashes.

## 📊 Visual Output

The output video mimics a professional broadcast overlay:

* **Green Boxes & Trails:** Locks onto all human players on the court with a fading motion trail attached to their feet.
* **Orange Boxes & Trails:** Isolates and tracks the sports ball through the air and across the court.
* **Dashboard:** Displays real-time tracking status and frame counts.

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

