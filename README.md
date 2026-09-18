Bubble Shooter (Hand Gesture Controlled)
A web-based Bubble Shooter arcade game where you control the slingshot using your real hands in front of your webcam. Pinch your fingers to grab the bubble, pull back to aim, and let go to shoot!

What is this project?
This project is an AI-powered version of the classic Bubble Shooter game. Instead of using a mouse or touchscreen, it uses your webcam and Google's MediaPipe AI to detect hand movements and gestures in real time directly inside the browser.

How it Works
Hand Tracking: The webcam tracks 21 points on your hand in real time.
Pinch Gesture: When your thumb and index fingertip touch or come close, it detects a pinch.
Slingshot Mechanics:
Pinching near the bottom bubble grabs it.
Moving your hand while pinching stretches the slingshot band and shows aiming dots.
Opening your fingers releases the pinch and shoots the bubble forward.
Wall Bounces & Friction: The bubble bounces off the left and right walls and flies towards the top.
Match 3 & Pop: When the shot bubble sticks to bubbles of the same color, if 3 or more connect, they burst and pop.
Falling Bubbles: Any bubbles that lose their connection to the top ceiling drop down and give bonus points.
Change Colors: You can change your bubble color by hovering your hand over any color bubble in the bottom tray for a moment, or by clicking it.
Mouse Fallback: If you don't have a webcam or don't want to use gestures, you can simply click and drag with your mouse.
Controls
Pinch (Thumb + Index finger): Grab the bubble
Drag while pinching: Aim the slingshot
Release pinch (Open fingers): Shoot the bubble
Hover over bottom color bar: Switch bubble color
Mouse Click & Drag: Alternative control without camera
Points & Scoring
Red Bubble: 100 points
Blue Bubble: 150 points
Green Bubble: 200 points
Yellow Bubble: 250 points
Purple Bubble: 300 points
Orange Bubble: 500 points
Technologies Used
HTML5 & Canvas (2D rendering for bubbles and physics)
Vanilla JavaScript (Game logic, collision detection, and scoring)
Google MediaPipe Hands (Real-time hand tracking and gesture detection)
Tailwind CSS (Interface styling and glassmorphism HUD)
Node.js (Optional local web server)
How to Run the Project Locally
Because the game uses your webcam, browsers require it to run through a local server (http://localhost) rather than opening the file directly.

Option 1: Using Node.js (Easiest)
Open your terminal in the project folder.
Run: node server.js
Open your browser and go to: http://localhost:3000
Option 2: Using Python
Open your terminal in the project folder.
Run: python -m http.server 3000
Open your browser and go to: http://localhost:3000
Option 3: Using VS Code Live Server
Open the project in VS Code.
Right click on index.html and select "Open with Live Server".
Allow camera access in your browser when prompted.
Privacy
Everything runs completely inside your web browser. No camera video or images are recorded, stored, or sent to any server.

License
This project is licensed under the MIT License.
