###################

Screen-recorder-ffmpeg-cpp is a C++-based application that records a desktop screen (X11) using the FFMPEG library, capable of capturing high-quality screen video and encoding it into MPEG-4 and MP4 formats.

The application is designed to be modular, efficient, and optimized for performance on Linux systems. By leveraging FFMPEG's powerful encoding tools and libraries such as libavcodec, libavformat, and x11grab, this application offers seamless screen recording with configurable parameters for different use cases.

Features:

Desktop Capture: Efficiently captures video from an X11 display.
Advanced Encoding: Encodes video using MPEG-4 and MP4 codecs for storage efficiency and playback compatibility.
Multi-threading Support: Utilizes multi-threading to ensure smooth screen recording without affecting system performance.
Command-line Control: Control recording duration, output format, and more through command-line parameters.
Frame Rate and Resolution Control: Provides options to control the frame rate and resolution of the recorded video.
Real-time Buffering: Implements real-time video buffering to minimize dropped frames.
LICENSE: MIT License

Usage:

Before running the application, ensure that libavcodec, libavformat, x11grab, and other dependencies are installed. Check the official FFMPEG installation guide for detailed installation steps.
Start recording via the terminal, and stop the recording using Ctrl+C

###################
