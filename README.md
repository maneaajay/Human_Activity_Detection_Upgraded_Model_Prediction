# Human_Activity_Detection_Upgraded_Model_Prediction

This project aims at Suspicious Human Activity detection on CCTV camera footage using VGG-16 and LSTM Model.
The model detect human activity like - walking, running and fighting which can be used to classify in Suspicious or non-suspicious class.
Project report is also present in the project.

About The Project
Human behavior recognition in the real-world environment finds plenty of applications including intelligent video surveillance, shopping behavior analysis. Video surveillance has vast application areas especially for indoor outdoor and places. Surveillance is an integral part of security. Today security camera becomes part of life for the safety and security purposes.

The proposed system will use footage obtained from CCTV camera for monitoring the human behavior in a campus and gently warn when any suspicious event occurs. The major components in intelligent video monitoring is human activity recognition.

Dataset description
Dataset consists of KTH dataset for walking and running and Kaggle dataset for fighting.




How to setup and run?

# Note - The cell execution requires a lot of resources and might fail on low end PCs. Please Run in Google Colab if having Low end PC.
Install the requirements using the command - " pip install tensorflow opencv-python "
Run all the cells of Human_Activity_Detection_Model_Creation.ipynb for Model Creation and training.
Run all the cells of Human_Activity_Detection_Model_Prediction.ipynb for Predicting the Class of the video.
For Single action detection run predict_single_action(video_file_path, SEQUENCE_LENGTH) function with video path and sequence length as input.
For prediction of actions in the whole video run predict_on_video(video_file_path, output_file_path, SEQUENCE_LENGTH) function with input video path, output video path, sequence length as input, an output video file with predicted classes on top of the video will be saved in the output path.
Model link is given in the code.
