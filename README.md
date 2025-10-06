Interactive Particle Human Figure

This project is a Web-based interactive animation that visualizes a human figure made of thousands of dynamically animated particles.
The particles react to user interactions and can simulate multiple poses, effects, and motion patterns — all rendered in real time using the HTML5 Canvas API.

Features

Gender Toggle: Switch between male and female particle figures.

Pose Selector: Choose from multiple poses such as standing, walking, running, dancing, exploding, vortex, and wave.

Visual Effects: Enable or disable options like colors, trails, glow, particle connections, and 3D depth.

Real-Time Interactivity: Particles respond to mouse movement and create dynamic motion effects.

Video Recording: Record and download your animation as a .webm video directly from the browser.

Responsive Canvas: Automatically adapts to different screen sizes and resolutions.

Preview

Below is a preview of the interactive animation interface:

How It Works

The application generates thousands of small particle objects, each representing a pixel in the silhouette of a human figure.

Each particle has its own position, velocity, color, and behavioral properties (like trails, glow, and z-depth).

The animation loop updates particle motion frame by frame based on the current pose and user interactions.

You can modify the figure in real time using control buttons for gender, pose, and visual effects.

The recording feature captures the canvas stream and lets you save it as a video.

Controls
Control	Description
Men / Women	Switch between male and female figure shapes.
Pose Dropdown	Choose figure motion (Standing, Walking, Running, Dancing, Explode, Vortex, Wave).
Colors	Enable colorful particle palettes.
Trails	Activate trailing motion blur for particles.
Glow	Adds a soft light effect around each particle.
Connect	Draws connection lines between nearby particles.
3D Effect	Simulates depth for a 3D-like illusion.
Record Video	Starts video recording of the animation.
Stop Recording	Ends recording and downloads the file.
Tech Stack

HTML5 Canvas – For real-time particle rendering.

JavaScript (Vanilla) – Core logic, interactivity, and animation.

CSS3 – Responsive UI and dark theme controls.

MediaRecorder API – Records the canvas animation as video.

Web Animations – Frame-based physics and motion effects.
