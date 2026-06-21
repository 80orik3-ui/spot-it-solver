# Spot It! Solver 🎯🤖

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Topics](https://img.shields.io/badge/Tech-TensorFlow.js%20%2B%20YOLOv8s-orange)](https://github.com/80orik3-ui/spot-it-solver)

An interactive, browser-based, real-time AI solver for **Spot It! (Dobble)** card games. This application leverages a custom-trained **YOLOv8s** model converted to **TensorFlow.js** to detect, identify, and match symbols on cards completely client-side—no server-side computing required!

---

## ✨ Features

* **Real-Time Webcam Detection:** Point your camera at two Spot It! cards, and watch the AI instantly find and highlight the matching symbol.
* **Photo Upload Mode:** Upload a picture of two cards from your device to quickly identify the duplicate symbol.
* **Edge-Based AI Inference:** Powered by TensorFlow.js, meaning all computer vision calculations happen directly inside your web browser using WebGL/WebGPU acceleration.
* **Speed Match Game Mode:** Put your skills to the test! Challenge yourself in a fast-paced game mode to see if you can find the match quicker than the AI solver.
* **Zero Server Overhead:** Built entirely as a static frontend application, making it easily deployable to GitHub Pages, Vercel, Netlify, or any static hosting service.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript / TypeScript
* **Machine Learning Framework:** [TensorFlow.js](https://www.tensorflow.org/js)
* **Object Detection Model:** [Ultralytics YOLOv8s](https://github.com/ultralytics/ultralytics) (Exported to TF.js Graph Model format)

---

## 🚀 Getting Started

Since the app runs entirely in the browser, setting it up locally is straightforward.

### Prerequisites

You will need a local HTTP server to run the application properly. Browsers restrict loading local model weights (`model.json` and weight shards) over the `file://` protocol due to CORS security rules.

### Installation & Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/80orik3-ui/spot-it-solver.git](https://github.com/80orik3-ui/spot-it-solver.git)
   cd spot-it-solver
