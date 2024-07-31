AI Weed Detector:

![Screenshot 2024-07-31 111728](https://github.com/user-attachments/assets/67e195da-9b5a-4e3a-9fee-52ee0e3d6fc6)

Crop weed recognition using Mask R-CNN in Python involves utilizing a deep learning model for image segmentation to differentiate between crops and weeds. The Mask R-CNN model extends Faster R-CNN by adding a mask branch to predict segmentation masks for each object detected in the image. By training the model on annotated images of crops and weeds, it can accurately identify and segment these objects, helping in precise agricultural management.

Note:
I processed them offline to do this in real time you should have to chosse a neural Network or give it a lot of processing power than my current computer is able to provide.

EXAMPLES OF SYNTHETIC TRAINING IMAGES:

Here are some examples of automatically generated training images.

![Screenshot 2024-07-31 110929](https://github.com/user-attachments/assets/edb2135f-bd7f-4b67-bd05-da6d371140d1)



EXAMPLES OF MASK R-CNN INFERENCE:

Here you can see some examples of inference running on real images of weeds.

![Screenshot 2024-07-31 111132](https://github.com/user-attachments/assets/51f0ab11-ea31-4fe7-b748-0818cfae2628)

You can also detect different object by creating a custom classes in your Python code.

![Screenshot 2024-07-31 104353](https://github.com/user-attachments/assets/09f1a0cd-eda2-4354-aa4a-53981e92416e)

