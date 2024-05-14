# Brain Tumor Detection Web Application

This is a web application built using Flask for detecting brain tumors from MRI images. The application allows users to upload MRI images and get predictions about whether a brain tumor is present in the image or not.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/17Manojsr/Brain_Tumor_Detection.git

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the root directory of the project.

2. Start the Flask application by running the following command:

   ```bash
   python app.py
   ```
3. Once the application is running, open your web browser and go to http://127.0.0.1:5000/.

4. You will see the home page of the application where you can upload an MRI image.

5. Select an MRI image file and click the "Upload" button.

6. Wait for the prediction result to be displayed. The result will indicate whether a brain tumor is detected in the uploaded image or not.

## Model

The brain tumor detection model used in this application is stored in the file BrainTumor10Epochs.h5. It is a pre-trained model built using TensorFlow/Keras.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Checkout [Website Deployment Link](https://17manojsr.github.io/Brain_Tumor_Detection/)
