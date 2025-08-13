# Air-Canvas-Project


Summary:
The project uses OpenCV for real-time image capture and processing, along with libraries like NumPy for handling arrays and sometimes MediaPipe for robust hand or finger tracking. The webcam detects your hand or a specific colored object (like a colored cap or marker) and tracks its tip position. As you move it, the program draws lines on a virtual canvas, mimicking your movement.

Key steps:

Capture video from the webcam.

Detect and track hand or object position using color detection (HSV color space) or hand landmark models.

Store previous points to draw continuous lines.

Overlay the drawing on the video feed, creating a live painting effect.

Optional: Add gesture controls for clearing the canvas or changing colors.

Applications: Virtual drawing boards, touchless control systems, interactive art tools, and educational tech.

<img width="660" height="639" alt="Screenshot 2025-08-13 165225" src="https://github.com/user-attachments/assets/5c745a35-0342-41e3-bfa2-c81d0a3d0127" />



<img width="636" height="675" alt="Screenshot 2025-08-13 165237" src="https://github.com/user-attachments/assets/cdc7fbd6-570c-4200-8819-b28060493494" />
