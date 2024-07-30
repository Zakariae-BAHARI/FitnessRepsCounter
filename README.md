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
   
   ```bash
   pip install opencv-python==4.5.1 mediapipe==0.8.0 Pillow==8.2.0
   ```

2. **Run the Application**:
   
   ```bash
   python src/main.py
   ```

3. **Select a Video**:
   - Click the "Select Video" button to choose a video file (supported formats: .mp4, .avi, .mov).
   - The application will display information about the selected video.

4. **Track Exercise**:
   - Click the "Track Exercise" button to start processing the video.
   - The application will process each frame to count and display the number of pull-up repetitions.

## Example Output
Here's an example of me performing the exercise, with the application counting my pull-up repetitions: 
![Alt Text](results/output_video.gif)


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
└── README.md                    
```

## Future Improvements
my future goal is to add the logic to count the reps for more exercises.
Contributions are welcome! If you have any ideas or improvements, please create an issue or submit a pull request.
-> For questions or feedback, feel free to reach out to zakariae.bahari@gmail.com

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



