# License-plate-detection

## Introduction
License plate recognition systems have become integral components of modern applications, spanning traffic control, surveillance, and automated toll collection. This project represents a fusion of cutting-edge technologies, encompassing hardware and software elements, to address the evolving demands in this domain. The project adopts a holistic approach, blending advanced image processing techniques with state-of-the-art neural networks. Through this integration, the system endeavors to deliver a high-performing and accurate license plate recognition solution. By overcoming challenges such as varying lighting conditions and diverse plate designs, the project aims to address the multifaceted requirements of license plate recognition applications. In essence, this project epitomizes the relentless pursuit of innovation in the fields of computer vision and machine learning. It underscores the transformative potential of merging diverse technologies to tackle complex real-world challenges, thereby paving the way for enhanced efficiency, security, and automation in critical applications.

## Detailed Design
### Data source and validation
The data utilized for training and validation of the license plate recognition system consisted of a diverse set of images containing Indian license plates captured under varying environmental conditions and scenarios. The dataset encompassed a wide range of license plate designs, fonts, sizes, and orientations to ensure the robustness and generalization capability of the developed system.

Data collection involved sourcing images from both publicly available datasets and custom capture sessions to cover a comprehensive spectrum of real-world scenarios. Images were captured using different cameras and devices to simulate varying lighting conditions, angles, distances, and perspectives commonly encountered in practical applications.

To ensure the reliability and accuracy of the system, rigorous validation procedures were conducted using annotated ground truth data. Each image in the dataset was meticulously annotated to delineate the exact location and content of license plates, including individual characters. The annotations served as reference points for evaluating the system's performance across different metrics. To comprehensively evaluate the system's performance, multiple key metrics are employed:

- Character Segmentation Accuracy: Gauging the system's accuracy in segmenting individual characters from license plates.
- Character Recognition Accuracy: Assessing the CNN model's accuracy in recognizing and interpreting segmented characters.
- Overall System Accuracy: Calculating the overall accuracy of the entire license plate recognition system in retrieving and presenting the correct license plate number.

### Architecture
![System Architecture](https://github.com/krishna1052/License-plate-detection/assets/95615695/68407f08-0747-4dd5-b92e-ae5c251bc904)
System Architecture

![Flattening the node data to represent it in a single dimension](https://github.com/krishna1052/License-plate-detection/assets/95615695/c49d5545-e3bb-4412-80ac-2239aeabf0a6)
Flattening the node data to represent it in a single dimension

