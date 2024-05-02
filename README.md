# DataminingA3

THIS IS THE EXPLAINATION OF HOW I HAVE CREATED AN ANOMOLY DETECTION MODEL FOR ASSIGNMENT # 3


Step 1: Obtain the PSM dataset from eBay for time series anomaly detection.

Step 2: Preprocess the dataset by cleaning any noise or irrelevant information and organizing it into a suitable format for training.

Step 3: Implement data augmentation techniques using geometric distribution masks. This involves generating masks with geometric shapes and applying them to the dataset to create variations of the original data.

Step 4: Develop a Transformer-based Autoencoder architecture. This involves creating an autoencoder model based on the Transformer architecture, which is capable of capturing temporal dependencies in multivariate time series data.

Step 5: Integrate contrastive learning into the framework. Implement a contrastive loss function that encourages the model to learn representations that are invariant to variations in the data, thereby improving its ability to distinguish between normal and abnormal patterns.

Step 6: Incorporate Generative Adversarial Networks (GANs) into the framework. Train a GAN model alongside the autoencoder to generate synthetic data samples that resemble the original data distribution, further augmenting the training dataset and improving the model's generalization ability.

Step 7: Train the anomaly detection framework using the augmented dataset. Utilize the combined loss functions (contrastive loss and reconstruction loss) to optimize the parameters of the autoencoder and GAN.

Step 8: Evaluate the performance of the trained model on test data. Measure metrics such as precision, recall, and F1-score to assess the model's ability to detect anomalies accurately.

Step 9: Fine-tune the model parameters and hyperparameters if necessary to improve performance further.
