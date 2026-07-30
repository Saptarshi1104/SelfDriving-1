# Details of C-204-Project.py

Project on 25th October, 2022

---

## 🧠 Brief Points

* **Spawned a Tesla Model 3:** Picked a random spawn point on the map.
* **Enabled Autopilot:** Let CARLA's built-in AI handle steering and driving.
* **Mounted Hood Camera:** Attached an RGB camera to the front (`x=3.5`, `z=1.7`) with a wide 170° FOV at 1366x768 resolution.
* **Saved Camera Frames:** Streamed and saved every single frame to `output/frame_<number>.jpg`.
* **Set Spectator View:** Placed the simulator camera 30 units ahead facing back so you could watch the car drive toward you.
* **Cleanup Loop:** Added a `try...finally` block so the car and sensors get destroyed when you stop the code (`Ctrl + C`).

---

## 🚀 Quick Run

1. **Launch CARLA Simulator** (`CarlaUE4.exe` or `./CarlaUE4.sh`)
2. **Run the script:**
   ```bash
   python main.py

# Details of C-204-Project-T4.py

Project on 25th October, 2022

## 🧠 Brief Points

* **Spawned Tesla Model 3:** Placed at a random spawn point with CARLA's built-in autopilot driving it.
* **Dashcam Setup:** Configured a **640x480** RGB camera with a standard **110° FOV**.
* **Frame Recording:** Captured real-time images and saved them directly to `output/frame_<number>.jpg`.
* **Spectator Camera:** Placed the simulator spectator view 30m ahead facing backward to watch the car approach.
* **Safe Cleanup:** Used a `try...finally` block so actors and sensors get cleared when stopping the script (`Ctrl + C`).

---

# Details of C-205-Project.py

Project on 25th October, 2022

---

## 🧠 Brief Points

* **Mounted Depth Sensor:** Attached a `sensor.camera.depth` to the front hood (`1366x768` at `110° FOV`).
* **Raw Array Conversion:** Took CARLA's raw pixel byte array, converted it to a 4-channel NumPy array, and sliced it to 3 channels for OpenCV.
* **Live Display Window:** Rendered a real-time depth feed on screen using `cv2.imshow()` instead of saving files to disk.
* **Spectator Tracking & Autopilot:** Placed the spectator camera ahead of the vehicle and handed control over to CARLA's AI.

---
