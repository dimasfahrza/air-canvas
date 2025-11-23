# ✍️ Air Canvas: Hand Tracking Drawing Application

An innovative computer vision project that allows users to **draw in the air** using hand gestures, translating the movements onto a digital canvas in real-time.

This application uses the **MediaPipe Hand Landmarker** model and leverages the power of Python, OpenCV, and PyQt5 for a real-time, interactive experience.

## ✨ Features

* **Real-Time Drawing:** Draw on the screen by moving your index finger in the webcam feed.
* **Hand Tracking:** Uses the powerful MediaPipe library for accurate and robust hand landmark detection.
* **Custom GUI:** A user-friendly interface built with PyQt5 for displaying the video feed and the canvas.
* **Model Integration:** Direct integration of the TensorFlow Lite **`hand_landmarker.task`** model.

## 🛠️ Prerequisites

Before running the application, ensure you have the following installed:

* **Python 3.x**
* **Webcam**

## 📦 Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourProjectName.git](https://github.com/YourUsername/YourProjectName.git)
    cd YourProjectName
    ```

2.  **Create and activate a virtual environment (Recommended):**
    ```bash
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

1.  **Ensure the `hand_landmarker.task` file is in the root directory.**
2.  **Run the application:**
    ```bash
    python air_canvas.ipynb
    # OR, if converted to a standard Python script (e.g., air_canvas.py)
    # python air_canvas.py
    ```
3.  **Start Drawing:** Once the webcam feed appears, raise your hand. The application tracks the tip of your index finger to draw on the canvas.

***Note:** The file `air_canvas.ipynb` can be executed directly as a Python script via `jupyter notebook air_canvas.ipynb` or by converting it to a standard `.py` file if you prefer.*

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
