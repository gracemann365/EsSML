# EsSML (Emotion Sentient System using Machine Learning)

---

## Introduction:

EsSML is a Python-based project that utilizes Machine Learning (ML) and OpenCV to detect human emotions from Live Feed. The detected emotions are then displayed on a Flask web application, providing users with an immersive experience. Additionally, the web application allows users to select genres and singers, input custom emotions, and automatically routes to curated YouTube playlists based on the detected emotions. The project is continuously evolving, with upcoming updates focusing on enhancing the user interface (UI) and user experience (UX).

---

## Features:

1. **Emotion Detection**: EsSML employs ML algorithms and OpenCV to accurately detect human emotions from images or videos in real-time.
   
2. **Genre and Singer Selection**: Users can select their preferred music genres and favorite singers to personalize their experience.
   
3. **Custom Inputs**: EsSML allows users to input custom emotions, enabling them to explore a wide range of emotional responses beyond the detected ones.
   
4. **Auto-Routing to YouTube Playlists**: Based on the detected emotions or custom inputs, the web application automatically routes users to curated YouTube playlists corresponding to the selected genres and singers.

5. **User-Friendly Interface**: The Flask web application provides an intuitive and user-friendly interface, making it easy for users to navigate and interact with the features.

6. **Responsive Design**: EsSML is designed to be responsive, ensuring a seamless experience across different devices and screen sizes.

---
## Local Setup:

To set up EsSML locally on your machine, follow these steps:

1. **Clone the Repository**: Start by cloning the EsSML repository to your local machine using the following command:
   ```bash
   git clone https://github.com/gracemann365/EsSML.git
   ```

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using `pip`. It's recommended to use a virtual environment to manage dependencies. If you don't have `virtualenv` installed, you can install it using `pip install virtualenv`. Then, create and activate a virtual environment:
   ```bash
   cd EsSML
   python -m venv venv
   source venv/bin/activate  # On Windows, use venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Download Model Weights**: Download the pre-trained model weights for emotion detection and place them in the project directory. You can obtain the model weights from [here](https://example.com/model_weights.h5).

4. **Run the Flask App**: Once the dependencies are installed and the model weights are downloaded, you can run the Flask web application. Use the following command to start the server:
   ```bash
   python app.py
   ```

5. **Access the Web Application**: Open your web browser and navigate to `http://localhost:5000` to access the EsSML web application locally.

6. **Explore Features**: You can now explore the various features of EsSML, including emotion detection, genre and singer selection, custom inputs, and auto-routing to YouTube curated playlists.

7. **Provide Feedback**: Feel free to provide feedback, suggestions, or report any issues by creating a new GitHub issue in the EsSML repository.

By following these steps, you'll have EsSML up and running on your local machine, ready to detect emotions and provide an immersive music experience based on the detected emotions. Enjoy exploring the world of emotion sensing using machine learning with EsSML!


---

# Upcoming UI/UX Update:

The upcoming update of EsSML focuses on enhancing the user interface (UI) and user experience (UX) with the following improvements:

1. **Improved Visual Design**: Revamped visual elements, including color schemes, typography, and layout, to create a more visually appealing interface.
   
2. **Enhanced Navigation**: Streamlined navigation features for easier access to different sections of the web application and smoother transitions between pages.
   
3. **Interactive Elements**: Addition of interactive elements such as animations, hover effects, and tooltips to make the user experience more engaging and interactive.
   
4. **Accessibility Features**: Implementation of accessibility features to ensure that the web application is inclusive and accessible to users with disabilities.

5. **Performance Optimization**: Optimization of page loading times and overall performance to provide a faster and more responsive experience.

EsSML is a dynamic project that aims to provide users with a seamless and immersive experience while exploring the intersection of machine learning, computer vision, and music. Stay tuned for future updates and enhancements to further elevate the user experience. Contributions and feedback are highly appreciated.


--- 
