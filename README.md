# Waste Classification and Recycling 

---

## ABSTRACT
 ---
 
 This project aims to develop a smart waste management system that handles waste classification, sorting, and recycling challenges using IoT, deep learning, and cloud computing. The Smart Waste Management System analyzes waste types in real-time and automates the entire process from collection to disposal. This system is a comprehensive solution with three modules that provides accurate waste detection, automated sorting, and user monitoring through a mobile app and LED display. Any user or facility just has to deploy the modules at waste points. The responses are precise about waste volume, contamination, and processing status. The user can monitor collection points, recycling facilities, and receive real-time alerts through the system. The user does not have to manually sort or track waste manually. The System analyzes waste through cameras and sensors, then sorts and notifies automatically. The user can also view analytics and receive status updates through an effective mobile app interface and 4-LED home module which feels like an intelligent assistant managing waste for you.

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

## Cloud Services & Deployment:
-AWS / Google Cloud / Azure – Train CNN models using large datasets and computational resources.

---
## End Users
---
1. Municipal Waste Management Authorities - For efficient waste segregation and management in cities and towns.
2. Recycling Companies and Facilities – To automatically categorize and sort waste, improving recycling efficiency.
3. Smart Waste Bin Manufacturers – To integrate AI-powered sorting and monitoring into intelligent bin systems.
