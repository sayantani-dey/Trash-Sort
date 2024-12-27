# Trash-Sort
A model that manages your trash efficiently, freeing you to focus on other priorities.
With this model you don't have to worry about separating it into blue (recyclable), green (biodegradable), black (non-recyclable), red (hazardous), yellow (plastic), and white (glass).

# Model build
This model is built using YOLOv8, a state-of-the-art object detection algorithm known for its speed and accuracy. YOLOv8 is trained on a diverse dataset of waste images categorized into various types, such as recyclable, biodegradable, non-recyclable, hazardous, plastic, and glass. It leverages deep learning techniques to identify and classify trash items in real time, enabling automatic sorting based on their category. This ensures precise segregation, reducing human effort and enhancing waste management efficiency.

# Model Results
The image presented below has the actual labels of the objects:
![val_batch1_labels](https://github.com/user-attachments/assets/a69aaf4c-25b4-4882-bada-b68bc62e188d)

The model predicts 84% times(top1 accuracy: 0.849; top5 accuracy:0.99), the objects correctly as shown below :
![val_batch1_pred](https://github.com/user-attachments/assets/ba3ed316-f57d-4196-babb-16daab6a5ee8)

