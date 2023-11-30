# recognize_emotions

Small Python project which aims to recognize your emotions via a camera

---

## Prerequisites

- Python (>= 3.6)
- OpenCV (For Face Detection)
- TensorFlow (To utilize the deeplearning model)
- NumPy (For numerical computations)

## Installation

1. Clone this repo:

    ```
    git clone https://github.com/Backooo/recognize_emotions.git
    cd recognize_emotions
    ```
2. Create and activate a venv:
    ```
    python -m venv venv
    venv\Scripts\activate # On Mac use: source venv/bin/activate
    ```
3. Install project dependencies:
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the Script:
    ```
    python recognize_emotions.py
    ```
   
The camera should open and the script will begin to display your recognized emotions.
To quit the window press 'q'.