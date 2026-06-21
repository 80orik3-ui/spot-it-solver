# spot-it-solver

A web-based tool that uses a custom YOLOv8 model converted to TensorFlow.js to automatically find matching symbols between two Spot It! (Dobble) cards. 

Everything runs completely client-side in the browser—no external servers or backend required.

![image](https://github.com/user-attachments/assets/xxxx-xxxx-xxxx)
## Features

* **Real-time webcam detection:** Hold two cards up to your camera to instantly see the matching symbol highlighted.
* **Image upload:** Drop in a photo of two cards to find the match.
* **Speed match game:** A built-in mini-game where you can try to beat the AI's detection speed.
* **Pure frontend:** Built with static files, making it easy to host on GitHub Pages, Vercel, or Netlify.

## Tech Stack

* **Frontend:** HTML, CSS, JavaScript / TypeScript
* **ML Framework:** TensorFlow.js
* **Model:** YOLOv8s (exported to TF.js Graph Model format)

## Getting Started

Because the app loads local model files (`model.json` and shards) via TensorFlow.js, you need to run it through a local server to avoid CORS browser restrictions.

### Running Locally

1. Clone the repo:
   ```bash
   git clone [https://github.com/80orik3-ui/spot-it-solver.git](https://github.com/80orik3-ui/spot-it-solver.git)
   cd spot-it-solver
