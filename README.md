# BlindNavigationDoorDetector
Android app to assist visually impaired users by detecting doors and obstacles in real time. Uses custom ML Kit object detection and voice guidance to help navigate indoor spaces safely. Provides audio alerts and visual overlays for enhanced usability.
# BlindDoorExitDetector

**BlindDoorExitDetector** is an Android application designed to assist visually impaired users by detecting doors and obstacles in real-time. Leveraging a custom ML Kit object detection model combined with Text-to-Speech (TTS) audio guidance, this app enhances indoor navigation safety and independence.

---

## Features

- **Real-time Object Detection:** Detects doors and obstacles using a custom TensorFlow Lite model optimized for indoor environments.  
- **Audio Navigation Guidance:** Provides clear, context-aware spoken instructions to guide users safely toward exits while avoiding obstacles.  
- **Visual Overlay (Debug Mode):** Displays bounding boxes and labels for detected objects, useful for development and demonstration.  
- **Efficient and Responsive:** Frame skipping and cooldowns optimize performance and prevent audio overload.  
- **Easy Permission Handling:** Seamlessly requests camera permissions and handles lifecycle events.

---

## Screenshots

*(Add screenshots here to showcase the app UI and detection in action)*

---

## Getting Started

### Prerequisites

- Android device running API level 21 or above  
- Camera and microphone permissions enabled  
- Android Studio (recommended) for building from source  

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/BlindDoorExitDetector.git

