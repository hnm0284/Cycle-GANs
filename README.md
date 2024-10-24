🖊️ Signature Image Generation using GANs and VAEs
This project focuses on comparing the performance of Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs) in generating signature images. The dataset used consists of custom signature images, which were preprocessed and augmented to enhance training due to the small dataset size.

📁 Dataset
Type: Custom dataset of signature images.
Preprocessing: Resizing, normalization, and data augmentation to address the limited size of the dataset.
Augmentation Techniques: Rotation, scaling, and random noise.
🧠 Models
Generative Adversarial Network (GAN): Trained to generate high-quality signature images.
Variational Autoencoder (VAE): Compared against the GAN to analyze its performance on the same task.
🚀 Training
Both models were trained for 150 epochs with nearly equal training time.
Results: The GAN outperformed the VAE, generating more realistic and sharper signature images.
🛠️ Key Tools & Libraries
Python
TensorFlow/Keras: Used for building and training the models.
OpenCV: For image preprocessing and augmentation.
Matplotlib: For visualizing the results.
🔑 Key Takeaways
GANs proved to be more effective in generating lifelike images compared to VAEs.
Data augmentation was essential due to the limited size of the dataset.
Model selection has a significant impact, even when training conditions (epochs, data) are the same.
📜 License
This project is licensed under the MIT License.

