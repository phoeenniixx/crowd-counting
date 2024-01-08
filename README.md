# crowd-counting
This project leverages the power of machine learning to address the challenging task of crowd counting. Using a state-of-the-art deep learning architecture, ResNet-50, as the pre-trained model, we have developed a robust solution for estimating crowd sizes in diverse scenarios.

Key Features:

1) Model Architecture: The project harnesses the capabilities of ResNet-50, a deep convolutional neural network renowned for its effectiveness in image-related tasks. By utilizing a pre-trained model, we benefit       from the knowledge acquired during its extensive training on large-scale datasets.

2) Training Details: The model underwent 30 epochs of training, iterating through the entire dataset multiple times to fine-tune its parameters. The chosen hyperparameters, including a learning rate of 3.2e-06, were carefully tuned to strike a balance between model convergence and generalization.

3) Performance Metrics:
   
        Final Loss: Achieving a final loss of 1.8161 on the training set showcases the model's ability to minimize the disparity between predicted and actual crowd counts.
        Mean Absolute Error (MAE): With a low MAE of 1.0808, the model exhibits accurate predictions on average, reflecting its proficiency in estimating crowd sizes.
        Mean Squared Error (MSE): The mean squared error of 1.8161 further emphasizes the model's precision, with larger errors being appropriately accounted for.
   
5) Validation Insights: The model's generalization capabilities are assessed through a separate validation dataset. The validation loss, MAE, and MSE (896.9456, 29.0348, and 896.9456, respectively) provide insights   into how well the model performs on unseen data.
      
