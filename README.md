## Abstract

In this study, a novel and efficient method for unsupervised and label-free road semantic segmentation is proposed, operating based on scene geometry analysis. The proposed method introduces an architecture-independent loss function that leverages geometric features such as the vanishing line for horizon identification, ground points for road detection, and point tracking for road boundary estimation. In this pixel-wise classification, pixels are categorized into road and non-road. First, the method considers the area above the horizon line as non-road and then a specific area of the road in front of the autonomous vehicle, which is typically free of other vehicles, as road. In the initial stage, the network is trained solely based on these two regions. In the next stage, an additional loss function is incorporated to enforce temporal consistency, ensuring that corresponding points in consecutive frames retain the same label over time. The evaluation results show that the proposed method performs well in identifying roads and drivable areas with accuracy close to supervised methods. Furthermore, due to its independence from labeled data, this method has greater generalization capability across diverse conditions and environments.  
<br />  

# Some of the Outputs of Unsupervised Drivable Area Detection

![2](https://github.com/user-attachments/assets/fe721571-4828-4d3e-b908-362fdabcffd3)
![4](https://github.com/user-attachments/assets/d23f9d7f-1787-4f8f-8bdb-0a81c41f550d)
![6](https://github.com/user-attachments/assets/bd1a6244-7395-4e97-a27e-9f29d4223992)
![1](https://github.com/user-attachments/assets/82ade30f-23c9-4cf3-b91e-0f6b46fd0c58)
![5](https://github.com/user-attachments/assets/b9f93650-b7e4-4942-ba0e-e26302b2b6c0)
![8](https://github.com/user-attachments/assets/8e7b472d-5607-4bd4-a5f3-cb615042f2c2)  


# Instants of Tracked Points:
![11](https://github.com/user-attachments/assets/8b6ccc16-9686-4052-ac3e-a8af34553e32)
![55](https://github.com/user-attachments/assets/d8fda540-d6ae-4860-b784-c2d19cca9a3a)
