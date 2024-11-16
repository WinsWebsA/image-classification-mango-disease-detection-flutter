**Plant Disease Classification**

This Flutter app leverages the power of Teachable Machine to accurately classify various diseases based on image input. It provides a user-friendly interface for capturing images and receiving real-time predictions.

**Features**

* Image Capture: Easily capture images using the device's camera.
* Real-Time Prediction: Get instant disease classifications.
* Accurate Results: Benefit from the precision of Teachable Machine's machine learning model.
* Intuitive Interface: Enjoy a simple and user-friendly design.

**Getting Started**
* Clone the Repository: 
    ```bash
    https://github.com/WinsWebsA/image-classification-mango-disease-detection-flutter.git
    ```
* Set Up Flutter Environment:
Ensure you have Flutter installed and configured. Refer to the official Flutter documentation for setup instructions.

* Run the App:
    ```bash
    flutter run
    ```
**How it Works**

* **Teachable Machine Model:**

  * Train a machine learning model using Teachable Machine to recognize different disease patterns.
  * Export the model as a TensorFlow Lite model.
  
* **Flutter Integration:**

    * Integrate the TensorFlow Lite model into the Flutter app.
  * Use the tflite plugin to load and run the model.
  * Process captured images and feed them to the model for prediction.
  
* **User Interface:**

  * Design a user-friendly interface with a camera view and prediction display.
  * Provide clear instructions and feedback to the user.

