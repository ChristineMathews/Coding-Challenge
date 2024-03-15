Coding Challenge- Detection of Athletes

My approach to the problem: 

Method 1: Background Subtraction: This technique involves separating foreground objects (players) from the background by analyzing the difference between consecutive frames in a video sequence.
With 
Color-based Segmentation: Color-based segmentation methods isolate objects based on their color properties in the image. For player detection, color ranges corresponding to player uniforms or skin tones can segment players from the background.


Method 2: YOLOv8 achieves high accuracy in player detection by leveraging deep learning techniques and large-scale training datasets. It learns robust representations of players, enabling accurate detection across various poses and lighting conditions.


The methodology selected:


YOLOv8 was selected as the primary approach for athlete detection in football matches.
The model is trained on large-scale datasets with diverse scenes, allowing it to learn robust representations of players directly from data.
YOLOv8 utilizes deep learning techniques, specifically convolutional neural networks (CNNs), to achieve high accuracy and efficiency in player detection tasks.
Real-time processing capabilities of YOLOv8 enable timely detection of players during live football matches

In contrast, traditional approaches, such as background subtraction and color-based segmentation, rely on manual rules and thresholds, which may result in less accurate and adaptable solutions, especially in complex environments. Overall, YOLOv8 offers superior performance and scalability for player detection in football matches compared to traditional methods.

input>


https://github.com/ChristineMathews/Coding-Challenge/assets/34720216/4fdf80b1-41df-46d3-92d8-0ef0ced64988



Output>

https://github.com/ChristineMathews/Coding-Challenge/assets/34720216/577d646c-6c10-4004-8808-e9090bae2d5f


## Folder Structure

```
Athlete Detection/
    └── data/                # data set with labels
    └── output/              # Save output after processing 
    └── test/                # test images
    └── videos/              # for detection 
    └── training_result/     # to store training data
    └── yolo_data/           # data after seperate and for training the model
    └──  + The rest of the python files are uploaded 


