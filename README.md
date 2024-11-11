# Face Recognition-based Attendance System

A face recognition-based attendance system designed to automate attendance marking. This system captures facial images and matches them against a database of registered users for accurate tracking.

## Features
- **Automated Attendance**: Captures and identifies faces to mark attendance without manual intervention.
- **User Database**: Compares captured images with registered user data for verification.
- **Training Module**: Generates training data for improved recognition.
- **Real-time Detection**: Utilizes computer vision for face detection and attendance recording.

## Technologies Used
- **Python**: Core programming language.
- **OpenCV**: Real-time face detection and image processing.
- **NumPy**: Data manipulation and processing.
- **Haar Cascade Classifier**: Used for face detection.

## Getting Started

### Prerequisites
Ensure the following are installed:
- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nayanatara07/Face-Recognition-Based-Attendance-System-master.git
   ```
2. Navigate to the project directory:
   ```bash
   cd face-recognition-attendance
   ```

### Usage
1. Train the system using the provided training script:
   ```bash
   python train.py
   ```
   This generates a `trainer.yml` file in the `training image label` folder.

2. Run the face recognition program to capture and log attendance.

3. Attendance logs will be stored in the `attendance` folder with date and time.

## Project Structure
```
face-recognition-attendance/
│
├── attendance/                # Folder containing attendance logs with date and time
├── student details/           # Contains student details CSV file
│   └── student_details.csv    # CSV file with registered user data
│
├── training image label/      # Folder storing the trained data
│   └── trainer.yml            # Trained data file for facial recognition
│
├── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade model
├── train.py                   # Script for training the facial recognition model
├── .gitignore                 # Git ignore file
└── README.md                  # Project documentation
```

## Future Enhancements
- Add a user-friendly GUI for better interaction.
- Implement cloud-based storage for remote attendance access.
- Improve recognition accuracy using deep learning algorithms.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests for improvements.
---

**Happy coding and efficient attendance tracking!** 😊
```

Feel free to make further edits if needed!