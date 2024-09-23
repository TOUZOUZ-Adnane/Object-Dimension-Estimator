# Contour Detection and Object Measurement Project

This project uses OpenCV to detect contours in images and videos, warp the perspective of the detected object, and measure its dimensions. It can be used for various tasks, such as detecting A4 papers, and measuring objects in an image or video.

## Features

- Detects and draws contours of objects in images and videos.
- Warps the perspective of detected objects to a flat plane.
- Measures the width and height of the objects in centimeters.
- Works with pre-recorded videos or real-time webcam input.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV: For image processing and contour detection.
  - NumPy: For numerical operations.
  
Make sure to install the required dependencies from the `requirements.txt` file.

## Setup Instructions

### Prerequisites

You need Python 3.x and `pip` installed on your machine.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/TOUZOUZ-Adnane/Object-Dimension-Estimator.git
    ```
   
2. Navigate to the project directory:
    ```bash
    cd Object-Dimension-Estimator
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### How to Run the Project

1. Place your input video file or images in the `assets` directory. Adjust the path in the script if necessary.

2. Run the project using the following command:
    ```bash
    python ObjestSize.py
    ```

3. Use a webcam or video input to detect and measure objects. Press `q` to quit the program.

## Usage Example

The project detects contours in real-time from a webcam feed or from video files and displays the measured dimensions of the detected object (e.g., an A4 paper) in centimeters.

You can adjust the parameters such as minimum contour area, contour filtering, and Canny threshold for different object sizes and detection accuracy.

## Future Improvements

- Add support for detecting multiple object types.
- Enhance the measurement accuracy by calibrating the camera.
- Implement a graphical user interface (GUI) for easier parameter adjustment.

## Contact

For any inquiries or further information, feel free to contact me via:
- [LinkedIn](https://www.linkedin.com/in/adnane-touzouz/)
- [Email](mailto:adnane.touzouz.ta@gmail.com)
