🧠 Fetal Head Segmentation Using U-Net

Overview:
In this project, I used deep learning (U-Net model) to automatically find and outline a baby’s head in ultrasound images. It shows how AI can help doctors analyze medical images more accurately and quickly. The work was done using PyTorch.

Key Highlights:

Tech Used: NumPy, PyTorch, OpenCV, PIL, Pandas

Model: U-Net (a type of deep learning model with 23 layers) designed for precise image segmentation

Image Size: Each image is 572×572 pixels

Accuracy: Reached 95.6% Dice score and 97.4% pixel accuracy

Hardware: Trained on an NVIDIA RTX 3080 Ti GPU

Data Used:

Training: 799 images

Validation: 200 images

Testing: 335 images

Data Augmentation: Added random flips and rotations to make the model more robust

Output: The model predicts a binary mask showing the baby’s head area

Training Control: Used early stopping and checkpoints to prevent overfitting and save the best version

Loss Function: Combined Binary Cross Entropy and Dice Loss for better segmentation results

Steps to Use the Project:

Install all required Python libraries.

Prepare and clean ultrasound images.

Train the model using the dataset.

Test the model’s performance on new images.

Use the trained model to segment fetal heads in unseen ultrasound scans.

What Makes It Useful:
This model helps in automating fetal head detection, which can support doctors in prenatal care by saving time and improving accuracy in ultrasound analysis
