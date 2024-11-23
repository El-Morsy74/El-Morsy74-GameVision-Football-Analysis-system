# GameVision-Football-Analysis-system
This project is a Computer Vision application designed to analyze football matches using object detection, tracking, and perspective transformation. It combines state-of-the-art AI models and custom algorithms to identify, classify, and annotate objects on the FootBall pitch, providing a detailed analysis of gameplay.


##### Key Features
1- Object Detection and Classification:
1.1- Detects key entities: players, referees, goalkeepers, and the ball.
1.2- Classifies players into Team 0 (Blue) and Team 1 (Red) using a pre-trained team classifier.

2- Multi-Object Tracking:
2.1- Tracks player movements with ByteTrack, maintaining consistent identifiers for players.

3- Keypoint Detection and Pitch Alignment:
3.1- Detects key points on the football pitch for alignment with a standard FootBall pitch configuration.
3.2- Uses View Transformation to map video coordinates onto a normalized FootBall pitch layout.

4- Annotation and Visualization:
4.1- Annotates the video feed with colored shapes:
4.2- Ellipses for players, referees, and goalkeepers.
4.3- Triangles for the ball.
4.4- Displays player IDs and team affiliations for easier understanding.
4.4- Visualizes transformed positions on a 2D FootBall pitch representation.

5- Interactive Gameplay Analysis:
5.1- Tracks ball positions, player movements, and referee locations in real-time.
5.2- Integrates Voronoi diagrams for spatial analysis (if needed).
