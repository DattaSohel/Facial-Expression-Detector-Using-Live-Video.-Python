# Facial-Expression-Detector-Through-Live-Video Using-Python
<h1>Author & Creator : Sohel Datta</h1>
The Facial Expression Detector project aims to develop a real-time application that captures live video from a webcam, detects facial expressions, 
and classifies them into various emotion categories.

Utilizing Python's powerful libraries such as OpenCV and Deepface, the application will provide an interactive experience by displaying the detected emotions 

<b><h2>Objectives</b></h2>
<ul>
<li>To create a user-friendly application that can recognize and classify facial expressions in real-time.</li>
<li>To leverage deep learning techniques for accurate emotion detection.</li>
<li>To demonstrate the capabilities of computer vision in interpreting human emotions through facial cues.directly on the video feed.</li>
</ul>

<h2><b>Key Features</b></h2>
<ul>
<li>Real-Time Emotion Detection: The application will continuously capture video frames from the webcam, process each frame to detect faces, and 
classify the emotions displayed.</li>
<li>Emotion Categories: The system will identify and categorize emotions into seven primary classes: happy, sad, angry, surprised, neutral, disgusted, and fearful.</li>
<li>Visual Feedback: Detected emotions will be annotated on the video feed in real-time, providing immediate feedback to users.</li>  
<li>User-Friendly Interface: The application will be designed to be intuitive, requiring minimal user intervention.</li>
</ul>

<h2><b>Technical Implementation</b></h2>
<ol>
<li>Libraries and Dependencies:</li>

<ul>
  <li>OpenCV: For video capture and image processing tasks.</li>
  <li>Deepface: A deep learning library that provides pre-trained models for facial emotion detection.</li>
  <li>Matplotlib: For visualizing results if needed.</li>
</ul>
<br><li>Setup Instructions:</li>
<ul>
  <li>Install required libraries:</li>
  <ul>  
  <li>Code in bash:</li>
    <ul>
    <li>pip install opencv-python deepface numpy matplotlib</li>
    </ul>
  </ul>
  <li>Ensure that a webcam is connected and accessible by the system.</li>
</ul>

<br><li>Algorithm Steps:</li>
<ul>
<li><b>Capture Video:</b> Use OpenCV to access the webcam and start capturing frames.</li>
<li><B>Face Detection:</B> Implement Haar Cascade Classifier or a similar method to detect faces within each frame.</li>
<li><b>Emotion Analysis:</b></li>
  <ul>
  <li>Convert the detected face region into an appropriate format for analysis.</li>
  <li>Use the DeepFace.analyze() method to classify the emotion of the detected face.</li>
  </ul>
<li><b>Display Results:</b> Draw rectangles around detected faces and overlay text indicating the predicted emotion.</li>
</ol>
