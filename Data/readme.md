Dataset Link : https://uta.app.box.com/s/e7nsmloj8xmblosvfg98q42fgqnjy6dv

For our training and test data, we use REAL LIFE DROWSINESS DATASET created by a research team from the University of Texas at Arlington specifically for detecting multi-stage drowsiness. They had uploaded data of around 30 hours of videos of 60 unique participants.
The data created by the research team was uploaded in form of zip files, each file consists of five or six folders in which there are videos of unique individuals named as 0 for alert state video and 10 for drowsy state video.
From that dataset, we chose sufficient amount of data for both the alert and drowsy state of some participants. 
For each video, we used OpenCV to extract 1 frame per second starting at the 3-minute mark until the end of the video.
Each video was approximately 10 minutes long, so we extracted around 240 frames per video.
We labeled the frames from alert videos as 0 and from the drowsy videos as 1.

