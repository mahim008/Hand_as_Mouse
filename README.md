<h1>Hand as Mouse</h1>

<p>This Python script utilizes computer vision and hand tracking to control the mouse cursor using your hand. The script captures video from your webcam, tracks your hand movements, and moves the mouse cursor accordingly.</p>

<h2>Requirements</h2>

<p>Make sure to install the required libraries before running the script:</p>

<pre>
pip install opencv-python
pip install numpy
pip install pyautogui
pip install cvzone
pip install mouse
</pre>

<h2>How to Run</h2>

<ol>
    <li>Clone the repository:</li>
    <pre>
    git clone https://github.com/your-username/hand-as-mouse.git
    cd hand-as-mouse
    </pre>
</ol>
<ol>
    <li>Run the script:</li>
    <pre>
    python hand_as_mouse.py
    </pre>
    <pre>
    Use your hand gestures to control the mouse cursor
    </pre>
</ol>

<h2>Controls</h2>

<ul>
    <li><strong>Moving Cursor:</strong> Move your hand within the rectangle displayed on the camera feed.</li>
    <li><strong>Clicking:</strong> Close your thumb and index finger to simulate a mouse click.</li>
</ul>

<h2>Dependencies</h2>

<ul>
    <li><a href="https://pypi.org/project/opencv-python/">OpenCV</a></li>
    <li><a href="https://pypi.org/project/numpy/">NumPy</a></li>
    <li><a href="https://pypi.org/project/PyAutoGUI/">PyAutoGUI</a></li>
    <li><a href="https://pypi.org/project/cvzone/">cvzone</a></li>
    <li><a href="https://pypi.org/project/mouse/">Mouse</a></li>
</ul>

<h2>Notes</h2>

<ul>
    <li>Ensure that your webcam is properly connected and accessible.</li>
    <li>Adjust the <code>frameR</code> variable to change the size of the rectangle for hand tracking.</li>
</ul>

<p>Feel free to experiment with the script and customize it according to your needs. If you encounter any issues or have suggestions for improvements, please create an issue or submit a pull request.</p>

