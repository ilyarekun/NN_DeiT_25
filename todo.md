## Vision Transformers (ViTs)


### Project 19: Implementing Data-efficient Image Transformers (DeiT) for Image Classification


1. Title of the Project: 
    Data-efficient Image Transformers (DeiT) for Image Classification

2. Literature Overview: 
    DeiT is a Vision Transformer variant that enhances training efficiency
and performance without requiring extensive datasets. It introduces a teacher-student
distillation approach to improve accuracy. For more details, refer to the paper (["Training
Data-Efficient Image Transformers & Distillation Through Attention"](https://arxiv.org/abs/2012.12877)).


3. Source of the Code: 
    The official implementation of DeiT is available on GitHub: 
[DeiT GitHub Repository](https://github.com/facebookresearch/deit)

5.DONE Dataset Management and Acquisition: 
Utilize the  [CIFAR-100](https://www.kaggle.com/datasets/fedesoriano/cifar100) dataset, which contains 100 classes of images. 
Split the dataset into 70% training, 15% validation, and 15% testing sets
to ensure robust model evaluation.


6. Analytics of the Source Code: 
Develop a flow diagram illustrating the DeiT architecture,
highlighting the distillation token mechanism and the training process. 
This will demonstrate a clear understanding of the model's structure and data flow.

7. Results Analysis: 
Evaluate the model's performance using accuracy metrics 
and present a confusion matrix to analyze classification errors across different classes.

8. Conclusion: 
Prepare a public video presentation detailing the project's objectives,
methodology, results, and individual contributions. 
Recording via Microsoft Teams is recommended, and ensure the video is submitted by the deadline. 
All project team members should speak in the video - there is no time limitation on video. 
Be aware that the video will go public to increase your position among stakeholders in companies.






EN
Project Roles Structure
Project Roles and Responsibilities
Each project will be completed by a group of three students. 
To ensure an effective and structured workflow, each student will take on a specific role.
The roles are designed to cover theoretical understanding, practical implementation, data analysis, and presentation of results. 
Additionally, each group must develop a clear understanding of the topology of the assigned neural network, ensuring they comprehend the internal structure and
operation of the model.

1. Theory & Implementation Lead Responsibilities:

• Research and explain the theoretical background of the assigned neural network.

• Understand and describe the mathematical foundations behind the model.

• Implement the neural network using the provided source code.

• Train the model, troubleshoot issues, and ensure it runs correctly.

• Create detailed flow diagrams illustrating the architecture, including
layers, activation functions, and key computational operations.

• Work closely with the Data & Model Analysis Lead to validate the implementation.

2. Data & Model Analysis Lead
Responsibilities:
• Manage dataset acquisition, preprocessing, and division into training, validation, and test sets.

• Conduct data augmentation if necessary to improve model performance.

• Analyze the model’s training process and evaluate its performance using relevant metrics (accuracy, precision, recall, F1-score, AUC-ROC, etc.).

• Compare the results with other architectures or baseline models where applicable.

• Ensure proper visualization of the network topology and interpret the behavior of different layers 
(e.g., feature maps, weight distributions, attention maps for transformers, etc.).

• Validate findings with the Theory & Implementation Lead to ensure correctness.

3. Presentation & Documentation Lead
Responsibilities:
• Prepare a structured presentation detailing the project’s objectives,
methodology, results, and conclusions.
• Ensure that all team members participate in the video presentation.
• Record the presentation using Microsoft Teams as proof of work.
• The presentation should be clear, demonstrating the network topology,
showing visualizations (e.g., architecture flow diagrams, performance
graphs, error analysis).
• Document key insights and findings in a summary report (optional but
beneficial for better project understanding).
• Ensure the final presentation reflects the contributions of the entire
group.




Understanding Neural Network Topology
A critical requirement for all projects is to demonstrate a clear understanding
of the topology of the neural network being implemented. 

This includes:

• Creating flow diagrams showcasing each layer and its function.
• Visualizing how input data is transformed through the network.
• Identifying key components such as convolutional layers, residual blocks, transformers, or attention mechanisms.
• Explaining how the model’s structure contributes to its performance.


Final Submission Requirements
1. Working implementation of the neural network with clear documentation.
2. Analysis of results, including performance metrics and visualizations.
3. Video presentation, recorded and submitted via Microsoft Teams.
4. Network topology visualization, included in both the analysis and
presentation.

This structure ensures all students contribute meaningfully while also
confirming their deep understanding of the neural network they are working
on. Each student plays a crucial role in the project’s success, balancing
theoretical and practical aspects efficiently.