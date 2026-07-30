# CARLA Autonomous Car & Data Logger

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
