# Rock Paper Scissors - Real-Time Detection with YOLOv11

This repository contains a real-time Rock Paper Scissors game using a webcam, powered by a YOLOv11 model trained on the [Roboflow](https://roboflow.com) platform. The game includes face detection and integrates special visual effects: a **crown** for the winner, a **red mask** for the loser, and **cheer detection** for celebrating the outcome.

## Features
- **Real-Time Webcam Detection**: Play Rock Paper Scissors using your webcam with real-time predictions.
- **YOLOv11 Model**: Trained on a dataset from Roboflow for accurate gesture recognition.
- **Face Detection**: Detects and identifies players' faces to overlay effects.
- **Winner & Loser Effects**:
  - A **crown** appears on the winner.
  - A **red mask** covers the loser's face.
  - **Cheer Detection** to celebrate the game's outcome.
- **Scoring System**:
  - Players receive points based on wins.
  - The **crown** signifies a victorious round.
  - The **red mask** is assigned to the losing player.
- **Basic Computer Vision Project**: Developed as part of a Computer Vision course.

## Installation & Setup
### Requirements
Ensure you have the following installed:
- Python 3.x
- OpenCV
- YOLOv11 (pre-trained model)
- Roboflow SDK (for model inference)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/realtime-rps-yolo.git
   cd realtime-rps-yolo
   ```
2. Download the trained YOLOv11 model from Roboflow and place it in the `models/` directory.
3. Run the game:
   ```bash
   python main.py
   ```

## How to Play
1. Start the script and enable your webcam.
2. Show **Rock**, **Paper**, or **Scissors** hand gestures.
3. The model detects the gestures in real-time and determines the winner.
4. The winner gets a **crown**, and the loser gets a **red mask** over their face.
5. **Cheat Detection** activates when an exciting outcome occurs.

## Model Training
The YOLOv11 model was trained using annotated Rock Paper Scissors images on **Roboflow**. The dataset consists of:
- Rock
- Paper
- Scissors
- Face

## Acknowledgments
- **Roboflow** for providing the dataset annotation tools.
- **Computer Vision Course** for inspiring this project.

---
Feel free to modify and improve the repository. Contributions are welcome!

