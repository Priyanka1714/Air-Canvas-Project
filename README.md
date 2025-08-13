Summary:
The project uses OpenCV for real-time image capture and processing, along with libraries like NumPy for handling arrays and sometimes MediaPipe for robust hand or finger tracking. The webcam detects your hand or a specific colored object (like a colored cap or marker) and tracks its tip position. As you move it, the program draws lines on a virtual canvas, mimicking your movement.

Key steps:

Capture video from the webcam.

Detect and track hand or object position using color detection (HSV color space) or hand landmark models.

Store previous points to draw continuous lines.

Overlay the drawing on the video feed, creating a live painting effect.

Optional: Add gesture controls for clearing the canvas or changing colors.

Applications: Virtual drawing boards, touchless control systems, interactive art tools, and educational tech.
# Air-Canvas-Project
