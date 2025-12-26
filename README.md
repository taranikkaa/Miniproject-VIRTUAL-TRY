## AI VIRTUAL TRY ON STYLIST
Virtual AI Try-On Stylist is a web-based application that allows users to upload their photo and virtually try dresses and accessories. The system uses MediaPipe for pose detection and OpenCV for image processing to place clothing items realistically on the user’s body. The application is built using Streamlit and runs locally, providing an easy and interactive try-on experience without using a camera.
## About
The Virtual AI Try-On Stylist is a web-based application designed to provide users with an interactive fashion experience by allowing them to virtually try dresses and accessories using a single uploaded image. The application eliminates the need for physical trials and helps users visualize how different clothing items will look on them in real time.

The system is developed using Python, with Streamlit serving as the web interface, MediaPipe for human pose detection, and OpenCV for image processing and overlay operations. The entire application runs locally in VS Code and does not require a camera or external hardware.

In this application, the user first uploads a personal photo in JPG or PNG format. Once the image is uploaded, the system processes it and detects important body landmarks such as the head, neck, shoulders, torso, and hands using MediaPipe’s pose estimation model. These landmarks help in identifying the correct positions where dresses and accessories should be placed.

The application provides a limited but well-structured product catalog consisting of two dresses and two accessories. When the user selects a product, the system loads the corresponding PNG image with a transparent background and resizes it according to predefined scale factors. The selected product is then blended onto the user’s image using OpenCV’s image overlay and alpha blending techniques to create a realistic try-on effect.

The try-on process takes approximately 20–40 seconds, depending on the system performance and image size. After the overlay is completed, the final output image is displayed on the same page. The user can preview the result and download the generated try-on image with a single click.

The application follows a single-page design, ensuring ease of use and smooth navigation. All major functions such as image upload, product selection, processing, preview, and download are available on one screen. This makes the system user-friendly and suitable for demonstration and academic evaluation.

Overall, the Virtual AI Try-On Stylist demonstrates the practical application of computer vision and AI techniques in the fashion domain. It reduces manual effort, improves user engagement, and serves as a strong foundation for future enhancements such as real-time camera input, 3D clothing models, and online deployment.

## Features

Features of the Virtual AI Try-On Stylist Project:

1. Allows users to upload their photo in JPG or PNG format without using a camera.
2. Provides a virtual try-on experience for 2 dresses and 2 accessories.
3. Uses AI-based pose detection to identify body landmarks accurately.
4. Automatically places dresses and accessories on the correct body parts.
5. Applies realistic image overlay using OpenCV and alpha blending techniques.
6. Displays all features on a single-page Streamlit interface.
7. Generates try-on results within 20–40 seconds.
8. Enables users to preview the final output instantly.
9. Provides one-click download option for the generated try-on image.
10. Runs completely on a local system using VS Code.
11. Supports easy customization by adding or modifying products.
12. Does not require internet connection after installation.



## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks.
* Development Environment: Python 3.6 or later is necessary for coding the sign language detection system.
* Deep Learning Frameworks: TensorFlow for model training, MediaPipe for hand gesture recognition.
* Image Processing Libraries: OpenCV is essential for efficient image processing and real-time hand gesture recognition.
* Version Control: Implementation of Git for collaborative development and effective code management.
* IDE: Use of VSCode as the Integrated Development Environment for coding, debugging, and version control integration.
* Additional Dependencies: Includes scikit-learn, TensorFlow (versions 2.4.1), TensorFlow GPU, OpenCV, and Mediapipe for deep learning tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![Screenshot 2023-11-25 133637](https://github.com/<<yourusername>>/Hand-Gesture-Recognition-System/assets/75235455/a60c11f3-0a11-47fb-ac89-755d5f45c995)


## Output

<img width="1914" height="967" alt="Screenshot 2025-12-06 213234" src="https://github.com/user-attachments/assets/f85a121a-c71f-418b-97d7-62174c65d6c2" />





## Results and Impact
The Virtual AI Try-On Stylist successfully detects body landmarks from uploaded images and accurately overlays dresses and accessories on the user’s photo. The system generates realistic try-on previews within 20–40 seconds and allows users to visualize outfits without physically trying them. The single-page interface makes the application easy to use and interactive. The project demonstrates the practical use of AI and computer vision techniques such as pose detection and image blending. It reduces time and effort in outfit selection and provides a convenient digital alternative to traditional trial methods.

## Articles published / References



OpenCV Documentation – OpenCV.org. Open Source Computer Vision Library. Available at: https://opencv.org/

Streamlit Documentation. Streamlit: Turn Python scripts into shareable web apps. Available at: https://docs.streamlit.io/

Zhang, Z., et al. (2021). Real-time Human Pose Estimation Techniques in Computer Vision. Journal of Visual Communication and Image Representation, 80, 103-120.

Kaur, R., & Singh, J. (2020). Virtual Try-On Systems Using AI and Computer Vision: A Review. International Journal of Advanced Computer Science and Applications, 11(5), 45–52.



