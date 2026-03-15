Task will be to use this workout dataset Links to an external site. dataset train a model to classify the activity being performed in the videos. You should be able to classify between the following activities: barbell biceps curl, bench press, deadlift, plank, pull up, push up, shoulder press and squat. Complete the following steps: 

    1. Perform keypoint detection (aka pose estimation) and train a model using the keypoints as input. Explain the preprocessing steps, report, and discuss your results. Note: To identify the keypoints, use any pre-trained model, such as:
        Movenet Links to an external site.
        MediaPipe Links to an external site. (which powers MLKit Links to an external site. for mobile implementations)
        OpenPose Links to an external site.
        YOLO Links to an external site.
    2. Perform feature engineering from the keypoint detection and report the minimal set of features that will predict the activity without affecting the performance of your model. Try using biomechanical relevant features from the keypoint detection (for example: angles, velocities, etc.). Explain the features, report, and discuss your results.
    3. Use MoViNet Links to an external site. to classify the videos. Feel free to finetune it to the classes of your dataset. Report and discuss your results.
    4. Compare the results of the models in 1, 2 and 3 and discuss them.

Resources:

    introduction-to-video-classification Links to an external site.
    video-classification-the-sequence-model 
