﻿# FitnessRepsCounter
**FitnessRepsCounter**

### Project Description
This project is a simple application that uses computer vision to help you count pull-ups or push-ups repetitions. Just select a video of someone performing the exercises, click "Track Exercise," and the app will process the video to count and display the number of repetitions. It's a great tool for tracking your workout progress and staying motivated!

### README

# FitnessRepsCounter

## Project Overview
FitnessRepsCounter is a computer vision application designed to help you count the number of pull-ups or push-ups you perform in a video. It's an easy-to-use tool that leverages human pose detection to track your exercise progress. Simply select a video file, and the application will process it to count the repetitions for you.

## Features
- **Select Video**: Choose a video file of someone performing pull-ups or push-ups.
- **Track Exercise**: Click the "Track Exercise" button to start processing the video and count the repetitions.
- **Real-Time Display**: Watch the video with landmarks and the repetition count displayed.

## Impact
This project makes tracking your fitness progress easier and more fun. By automatically counting your pull-ups or push-ups, it helps you stay motivated and focused on your goals. No more manually counting reps or losing track during your workout!

## How to Use
1. **Install Dependencies**:
   Make sure you have Python and the required libraries installed. You can install the necessary libraries using pip:
   ```bash
   pip install opencv-python mediapipe Pillow
   ```

2. **Run the Application**:
   Execute the main script to launch the application:
   ```bash
   python src/main.py
   ```

3. **Select a Video**:
   - Click the "Select Video" button to choose a video file (supported formats: .mp4, .avi, .mov).
   - The application will display information about the selected video.

4. **Track Exercise**:
   - Click the "Track Exercise" button to start processing the video.
   - The application will process each frame to count and display the number of pull-up repetitions.

## File Structure
```
FitnessRepsCounter/
│
├── data/
│   └── pullups.MOV              # Example video file for testing
│
├── results/
│   ├── output_video.gif         # Output video with landmarks and rep count (GIF format)
│   └── output_video.avi         # Output video with landmarks and rep count (AVI format)
│
├── src/
│   └── main.py                  # Main application script
│
└── README.md                    # Project README file
```

## Future Improvements
- Add support for more exercises.
- Enhance the accuracy of repetition counting.
- Implement a graphical user interface (GUI) for a better user experience.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

FitnessRepsCounter helps you stay on track with your fitness goals by providing an easy and accurate way to count your exercise repetitions. Whether you're working on pull-ups or push-ups, this tool will keep you motivated and informed about your progress. Happy exercising!
