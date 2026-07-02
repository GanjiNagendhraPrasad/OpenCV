<div align="center">

  <h1>📸 OpenCV Computer Vision  Repository</h1>

  <p>
    A beginner-friendly OpenCV repository containing practical Python programs for
    image reading, resizing, color processing, edge detection, mouse events,
    ROI handling, video processing, and basic feature extraction.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Python-100%25-blue?style=for-the-badge&logo=python" />
    <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv" />
    <img src="https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-orange?style=for-the-badge" />
  </p>

</div>

<hr>

<h2>📌 About This Repository</h2>

<p>
This repository is created to practice and understand the fundamentals of 
<strong>OpenCV using Python</strong>. It contains multiple small programs that explain
how images and videos are processed using OpenCV functions.
</p>

<p>
The project is useful for beginners who want to learn:
</p>

<ul>
  <li>How to read and display images using OpenCV</li>
  <li>How to work with color and grayscale images</li>
  <li>How to resize and save images</li>
  <li>How to detect edges using Canny Edge Detection</li>
  <li>How to use mouse events in OpenCV</li>
  <li>How to work with HSV color space and masking</li>
  <li>How to process videos frame by frame</li>
  <li>How basic filters work in image processing</li>
</ul>

<hr>

<h2>🧠 Concepts Covered</h2>

<table>
  <tr>
    <th>Concept</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Image Reading</td>
    <td>Loading color and grayscale images using <code>cv2.imread()</code></td>
  </tr>
  <tr>
    <td>Image Display</td>
    <td>Displaying images using <code>cv2.imshow()</code></td>
  </tr>
  <tr>
    <td>Image Resizing</td>
    <td>Changing image width and height using <code>cv2.resize()</code></td>
  </tr>
  <tr>
    <td>Edge Detection</td>
    <td>Detecting object boundaries using Canny edge detection</td>
  </tr>
  <tr>
    <td>HSV Color Space</td>
    <td>Converting BGR images into HSV format for color-based detection</td>
  </tr>
  <tr>
    <td>Mouse Events</td>
    <td>Capturing mouse click coordinates and pixel values</td>
  </tr>
  <tr>
    <td>Trackbars</td>
    <td>Using OpenCV sliders to dynamically adjust values</td>
  </tr>
  <tr>
    <td>Video Processing</td>
    <td>Reading video frames, writing output video, and adding text on frames</td>
  </tr>
  <tr>
    <td>Filtering</td>
    <td>Applying custom kernels using <code>cv2.filter2D()</code></td>
  </tr>
</table>

<hr>

<h2>📂 Repository Structure</h2>

<table>
  <tr>
    <th>File Name</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td><code>read_show_color_opencv.py</code></td>
    <td>Reads and displays a color image using OpenCV</td>
  </tr>
  <tr>
    <td><code>read_show_gray_opencv.py</code></td>
    <td>Reads and displays a grayscale image</td>
  </tr>
  <tr>
    <td><code>resize.py</code></td>
    <td>Resizes an image to a custom width and height</td>
  </tr>
  <tr>
    <td><code>save_img.py</code></td>
    <td>Saves processed images into the local folder</td>
  </tr>
  <tr>
    <td><code>edge_detection.py</code></td>
    <td>Applies Canny Edge Detection on an image</td>
  </tr>
  <tr>
    <td><code>hsv_color_space.py</code></td>
    <td>Converts image from BGR to HSV and applies color masking</td>
  </tr>
  <tr>
    <td><code>Mouse_events-1.py</code></td>
    <td>Captures mouse click coordinates on an image</td>
  </tr>
  <tr>
    <td><code>Mouse_events-2.py</code></td>
    <td>Captures BGR pixel values from mouse click position</td>
  </tr>
  <tr>
    <td><code>ROI_imp.py</code></td>
    <td>Demonstrates Region of Interest and mouse callback concepts</td>
  </tr>
  <tr>
    <td><code>t_bar_1.py</code></td>
    <td>Uses trackbars to adjust Canny edge threshold values</td>
  </tr>
  <tr>
    <td><code>t_bar_2.py</code></td>
    <td>Uses trackbars for HSV color range selection</td>
  </tr>
  <tr>
    <td><code>video.py</code></td>
    <td>Reads video, processes frames, adds frame count, and saves output video</td>
  </tr>
  <tr>
    <td><code>feature_extraction_cnn.py</code></td>
    <td>Applies a custom filter/kernel for feature extraction</td>
  </tr>
</table>

<hr>

<h2>⚙️ Technologies Used</h2>

<p>
  <img src="https://img.shields.io/badge/Python-Programming-blue?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-green?style=flat-square&logo=opencv" />
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-purple?style=flat-square&logo=numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-yellow?style=flat-square" />
</p>

<hr>

<h2>🚀 How to Run This Project</h2>

<h3>1️⃣ Clone the Repository</h3>

<pre>
git clone https://github.com/GanjiNagendhraPrasad/OpenCV.git
cd OpenCV
</pre>

<h3>2️⃣ Install Required Libraries</h3>

<pre>
pip install opencv-python numpy matplotlib pandas
</pre>

<h3>3️⃣ Run Any Python File</h3>

<pre>
python edge_detection.py
</pre>

<p>
Example:
</p>

<pre>
python resize.py
python hsv_color_space.py
python video.py
</pre>

<hr>

<h2>🖼️ Main OpenCV Operations Used</h2>

<table>
  <tr>
    <th>OpenCV Function</th>
    <th>Use</th>
  </tr>
  <tr>
    <td><code>cv2.imread()</code></td>
    <td>Reads an image from a file</td>
  </tr>
  <tr>
    <td><code>cv2.imshow()</code></td>
    <td>Displays an image in a window</td>
  </tr>
  <tr>
    <td><code>cv2.resize()</code></td>
    <td>Resizes the image</td>
  </tr>
  <tr>
    <td><code>cv2.Canny()</code></td>
    <td>Detects edges in an image</td>
  </tr>
  <tr>
    <td><code>cv2.cvtColor()</code></td>
    <td>Converts image from one color space to another</td>
  </tr>
  <tr>
    <td><code>cv2.inRange()</code></td>
    <td>Creates a mask based on color range</td>
  </tr>
  <tr>
    <td><code>cv2.bitwise_and()</code></td>
    <td>Applies mask on original image</td>
  </tr>
  <tr>
    <td><code>cv2.setMouseCallback()</code></td>
    <td>Handles mouse click events</td>
  </tr>
  <tr>
    <td><code>cv2.createTrackbar()</code></td>
    <td>Creates sliders for real-time value adjustment</td>
  </tr>
  <tr>
    <td><code>cv2.VideoCapture()</code></td>
    <td>Reads video file or camera input</td>
  </tr>
  <tr>
    <td><code>cv2.VideoWriter()</code></td>
    <td>Saves processed video output</td>
  </tr>
</table>

<hr>

<h2>📊 Workflow</h2>

<pre>
Input Image / Video
        ↓
Read using OpenCV
        ↓
Apply Processing
        ↓
Display Output
        ↓
Save Result if Required
</pre>

<hr>

<h2>✅ Key Learnings</h2>

<ul>
  <li>Understanding how images are stored as NumPy arrays</li>
  <li>Difference between color image and grayscale image</li>
  <li>Importance of BGR and HSV color spaces</li>
  <li>How edge detection helps identify object boundaries</li>
  <li>How mouse events are used to get coordinates and pixel values</li>
  <li>How video is processed frame by frame</li>
  <li>How filters and kernels are used for feature extraction</li>
</ul>

<hr>

<h2>🎯 Use Cases</h2>

<ul>
  <li>Computer Vision learning</li>
  <li>Image preprocessing practice</li>
  <li>Object detection preparation</li>
  <li>Video analytics basics</li>
  <li>AI/ML image processing foundation</li>
</ul>

<hr>

<h2>📌 Future Improvements</h2>

<ul>
  <li>Add object detection using YOLO or Haar Cascade</li>
  <li>Add face detection and eye detection examples</li>
  <li>Create a proper folder structure for images and outputs</li>
  <li>Add sample input and output screenshots</li>
  <li>Add requirements.txt file</li>
  <li>Add real-time webcam processing examples</li>
</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<strong>Ganji Nagendhra Prasad</strong><br>
AI & ML Graduate | Data Science Intern | Aspiring Data Analyst / Data Scientist
</p>

<p>
  <a href="https://github.com/GanjiNagendhraPrasad">
    <img src="https://img.shields.io/badge/GitHub-GanjiNagendhraPrasad-black?style=for-the-badge&logo=github" />
  </a>
  <a href="https://www.linkedin.com/in/ganji-nagendhra-prasad-1a47a7347">
    <img src="https://img.shields.io/badge/LinkedIn-Nagendhra%20Prasad-blue?style=for-the-badge&logo=linkedin" />
  </a>
</p>

<hr>

<div align="center">

  <h3>⭐ If you found this repository useful, give it a star!</h3>

  <p>
    This repository is part of my learning journey in Computer Vision and OpenCV.
  </p>

</div>
