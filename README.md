# Waste Classification and Recycling 

---

## ABSTRACT
 ---
 
This project aims to develop a smart waste management system that handles waste classification, sorting, and recycling challenges using IoT, Convolutional Neural Networks (CNN), and cloud computing. The Smart Waste Management System uses CNN-based image processing to analyze waste types in real time and automate the entire process from collection to disposal. The system consists of three modules that provide accurate waste detection, automated sorting, and user monitoring through a mobile app and LED display. Users only need to deploy the modules at waste collection points. The system provides precise data on waste volume, contamination, and processing status, enabling real-time monitoring and alerts without manual intervention.

 ---
 
## Demo

[Watch Demo Video](./demo.mp4)

---
## Software & Hardware Used

### Programming Language
- Python – Used for programming sensors, camera module, and implementing AI models.

### Microcontroller
- ESP32 – Controls sensors and the servo motor for waste sorting.

### Actuators & Sensors
- Servo Motor – Physically sorts waste into different categories by rotating to specific angles.
- I2C LCD Display – Displays the type of waste currently detected.
- Moisture Sensor – Measures moisture to differentiate between wet and dry waste.

### Deep Learning & AI
- TensorFlow / Keras – Used for building and training Convolutional Neural Network (CNN) models.
- PyTorch – Alternative deep learning framework for CNN development.

### Model Architecture
- Convolutional Neural Network (CNN) – Uses convolution, pooling, and fully connected layers to extract features and classify waste types.

### Data Preparation & Labeling
- Image Datasets – Labeled images of waste categories such as Plastic, Paper, Metal, Glass, and Organic waste.
- Data Augmentation – Techniques like rotation, flipping, and cropping to increase dataset variety and reduce overfitting.


### Hardware & IoT Integration:
* Edge devices (Raspberry Pi / NVIDIA Jetson Nano) 
* Deploy lightweight CNN models for real-time waste classification.
* Microcontrollers (NodeMCU / ESP32) – Integrate sensors to monitor bin conditions.



---
## End Users
---
1. Municipal Waste Management Authorities - For efficient waste segregation and management in cities and towns.
2. Recycling Companies and Facilities – To automatically categorize and sort waste, improving recycling efficiency.
3. Smart Waste Bin Manufacturers – To integrate AI-powered sorting and monitoring into intelligent bin systems.
