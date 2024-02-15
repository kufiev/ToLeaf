# ToLeaf: Tomato Leaf Disease Detection with CNN Integration

ToLeaf is an Android application dedicated to the early detection of tomato leaf diseases through advanced image analysis. This open-source project combines the power of Convolutional Neural Networks (CNN) and TensorFlow Lite to classify images of tomato leaves, providing users with real-time insights into potential diseases affecting their plants.

![Screenshot 2024-02-15 163348](https://github.com/kufiev/ToLeaf/assets/90453759/76d81235-0cd6-441e-9037-28e23545d140)

### Key Features:

  1. Image Capture: Users can effortlessly capture images of tomato leaves using their device's camera within the application.
  2. Real-time CNN Classification: The application integrates a Convolutional Neural Network (CNN) model for robust and accurate image classification, ensuring precise identification of potential tomato leaf diseases in real time.
  3. Informative Output: The classified results are displayed on the user interface, allowing users to promptly access information about the detected disease.
  4. External Resources: Users can further explore details about the identified disease by clicking on the result, initiating a web search for additional resources and information.

### How to Use:

  1. Capture Image: Use the "Capture Image" button to take a photo of a tomato leaf.
  2. Real-time CNN Analysis: The application processes the captured image through a pre-trained CNN model (such as ModelVersion) using TensorFlow Lite for accurate and reliable disease classification.
  3. View Results: The identified disease is displayed on the user interface, providing immediate insights into the health of the tomato plant.
  4. Explore Information: Click on the displayed disease name to access external resources and learn more about the identified disease through a web search.

### Technical Details:

  1. The project leverages Android's camera functionalities for seamless image capture.
  2. Integration of a Convolutional Neural Network (CNN) model, such as ModelVersion, for enhanced image classification accuracy.
  3. TensorFlow Lite is utilized for efficient and real-time execution of the CNN model on mobile devices.
  4. The modular structure of the code encourages community contributions and enhancements to the application's functionality, especially in refining the CNN model for improved accuracy.

Note: This repository assumes the availability of a pre-trained CNN model (ModelVersion) for accurate tomato leaf disease classification. Contributions and adaptations to the CNN model are encouraged to further enhance the application's performance. Feel free to explore, contribute, and adapt ToLeaf with CNN integration for your specific needs.
