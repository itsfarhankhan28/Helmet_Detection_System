
# HELMET DETECTION SYSTEM USING ESP32 CAMERA & RASPBERRY PI

Road safety is a critical concern in the modern world, particularly for motorcyclists who are more vulnerable to accidents and injuries. The proposed project addresses this issue by introducing a Helmet Detection System that utilizes the ESP32 Camera and Raspberry Pi to enhance safety measures for motorcyclists. By harnessing the ESP32 Camera’s highresolution imaging capabilities and the Raspberry Pi’s processing power, this system aims to detect helmetless riders in real time, promoting compliance with safety regulations and reducing accident risks. The system employs advanced deep learning algorithms, such as YOLO and SSD, to analyze video feeds from the ESP32 Camera and accurately identify riders not wearing helmets. This approach is ideal for deployment at traffic intersections,
highways, and other locations where motorcyclists are at risk. The integration of Raspberry Pi allows for flexible data processing and connectivity, enabling seamless communication with centralized monitoring systems. Through this innovative technology, the project seeks to improve road safety by providing authorities with a reliable tool for enforcing helmet regulations, ultimately contributing to a safer environment for all road users. The long-term
impact of this project includes reduced accidents and enhanced public awareness about the importance of wearing helmets, thereby fostering a culture of safety on the roads.



## Models

SSD MobileNet V1 FPN 640x640
The SSD (Single Shot MultiBox Detector) MobileNet V1 FPN 640x640 model integrates the MobileNet architecture with the Feature Pyramid Network (FPN) to efficiently detect objects within images. This
model employs a single shot detection approach, enabling it to predict object locations and classes in a single pass through the network. In the context of a helmet detection
system, SSD MobileNet V1 FPN 640x640 offers a balance between speed and accuracy, making it suitable for real-time applications. By leveraging its multi-scale feature representation, this model can effectively detect helmets of varying sizes and orientations, even in complex environments.


CenterNet ResNet50 V2 FPN 512x512
CenterNet ResNet50 V2 FPN 512x512 combines the CenterNet architecture with the ResNet50 backbone network and Feature Pyramid Network (FPN) for precise object detection. This model excels in accurately localizing objects by predicting their center points and sizes. In the context of helmet detection, CenterNet ResNet50 V2 FPN 512x512 offers robust performance in identifying motorcyclists wearing helmets, even amidst occlusions or challenging lighting conditions. Its feature-rich representation allows for efficient detection of helmets, contributing to enhanced road safety measures.
