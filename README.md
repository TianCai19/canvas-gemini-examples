# Canvas Gemini Examples

This repository contains various examples and tools built with Canvas and Gemini.

## Projects

### Gemini Image Summary
A web-based tool that uses Google's Gemini AI to analyze and summarize images. Features include:
- Drag and drop or file selection for image upload
- AI-powered image analysis and description
- Real-time feedback and results display
- Modern UI with responsive design

To use the image summary tool:
1. Open `gemini-image-summary/index.html` in a web browser
2. Upload an image using drag & drop or file selection
3. Wait for the AI to analyze and provide a summary
4. View the detailed description of the image

**Online Demo:** [Gemini Image Summary](https://g.co/gemini/share/1f1e0222711c)

### Mail Generator (盲盒邮件生成器)
A web-based tool for generating blind box email pairs between pen pals. Features include:
- Simple web interface for inputting participant information
- Customizable email templates
- Automatic generation of paired messages
- Copy-to-clipboard functionality
- Modern UI with Tailwind CSS

To use the mail generator:
1. Open `mail-generater/index.html` in a web browser
2. Enter participant information (pen name and email)
3. Customize the email template if desired
4. Click "Generate" to create the paired messages

**Online Demo:** [Mail Generator](https://g.co/gemini/share/1f1e0222711c)

### Other Projects
- RL-tutorial
- body-health-detection
- finger-joint-detection

## Finger Joint Detection

This project uses TensorFlow.js and a pre-trained hand-pose detection model (MediaPipe Hands) to identify the number of extended fingers in an image uploaded by the user.

### How to Run

1.  Open the `finger-joint-detection/index.html` file in your web browser.
2.  Wait for the model to load.
3.  Click the "Upload Image" button and select an image of a hand.
4.  The AI will analyze the image, draw the hand skeleton, and display the detected number of fingers.

**Online Demo:** [Finger Joint Detection](https://g.co/gemini/share/1f1e0222711c)

## Body Health Detection

This project uses TensorFlow.js and the MoveNet pose detection model to monitor your posture in real-time and provide feedback for ergonomic sitting.

### How to Run

1. Open the `body-health-detection/index.html` file in your web browser.
2. Allow access to your camera when prompted.
3. Sit in front of your camera and the system will track your posture.
4. Receive alerts when you slouch, tilt your head, or maintain poor posture for too long.

**Online Demo:** [Body Health Detection](https://g.co/gemini/share/1f1e0222711c)

## Reinforcement Learning Tutorial

An interactive visualization of Q-Learning, demonstrating how an AI agent learns to find treasure through trial and error.

### How to Run

1. Open the `RL-tutorial/index.html` file in your web browser.
2. Click "Start Training" to watch the agent learn.
3. Toggle displays to see the Q-table (agent's memory) and decision logs.
4. View the Theory page to learn about the underlying principles of Q-Learning.

**Online Demo:** [RL Tutorial](https://g.co/gemini/share/1f1e0222711c)