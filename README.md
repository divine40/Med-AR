MedAR Pro: AR Medical Training Simulator
Bridging the Gap in Medical Education through Augmented Reality
            Description
MedAR Pro is an innovative Augmented Reality (AR) application designed as a capstone project for the African Leadership University. The solution addresses the critical shortage of high-fidelity medical training tools in Rwanda and across the continent.
By leveraging mobile AR, MedAR Pro provides medical students and professionals with an interactive, offline-capable platform to visualize complex human anatomy and practice procedural skills. Unlike traditional textbooks, MedAR Pro allows users to overlay anatomical systems, cardiovascular, skeletal, nervous, and respiratory into their physical environment, offering a 1:1 scale learning experience that enhances spatial understanding and clinical memory.
Key Features:
1. Layered Anatomy Visualization: Toggle between muscular, vascular, and skeletal layers in real-time.
2. Interactive Labeling: Spatial UI pins that identify anatomical structures with detailed medical descriptions.
3. Touch-Based Manipulation: Intuitive gestures for rotating, scaling, and inspecting 3D assets.
4. Offline Accessibility: Optimized for performance on mid-range Android devices common in African markets.
GitHub Repository: https://github.com/divine40/Med-AR

Design & Architecture
Figma Mockups
1. The user interface is designed with a "Medical-First" philosophy, focusing on clarity, minimal occlusion of the AR viewport, and ease of thumb-reach for mobile users.
2. Main Dashboard: Card-based navigation for selecting anatomical systems.
3. AR Interface: Heads-up display (HUD) featuring layered visibility controls and gesture-based transformation tools.
 User Flow: Link to Figma: https://drive.google.com/drive/folders/1jMBrY8ED78xZFfx_N7KP4EUe06aOu1rJ?usp=drive_link
System Architecture
1. Development Platform: Unity
2. AR Framework: AR Foundation / ARCore.
Environment & Project Setup
To set up this project locally, ensure you have Unity Hub and Android Studio (for SDK/JDK) installed.
Clone the Repository: Bash
git clone https://github.com/divine40/Med-AR

Unity Setup
1. Open Unity Hub and Add the project.
2. Ensure Unity 2022.3 LTS is installed.
3. Go to Window > Package Manager and ensure AR Foundation and ARCore XR Plugin are installed

Build Settings
1. Go to File > Build Settings and switch the platform to Android.
2. In Project Settings > XR Plug-in Management, check the ARCore box.

Hardware Requirements:
1. An ARCore-supported Android device (Running Android 7.0 or higher).
2. USB-C cable for sideloading the apk.

Author
Akunyiba Chimdalu (Divine) Final Year Student, African Leadership University

AR/VR Track 

