Alzeihmer detection is an essential tasks to take precautions for prevention and improve its treatment. DL and ML approaches are used to achieve this task. In this context, detection refers to discover whether a patient is demented or not.

![333302871-c4a92c22-7aee-4195-b933-6ecdab837ad8](https://github.com/user-attachments/assets/3a8ca15c-9349-4f89-889f-5c6bff0b1291)

The above figure shows the four groups of dementia. The dementia classes can be codified like this NonDemented:0, ModerateDemented:1, MildDemented:2, VeryMildDemented:3. In the detection procedure, the number of the classes should be reduced to two like NonDemented:0 & Demented:1 where Moderate, Mild and VeryMild cases fall into the second category.

7 deep learning models were compared in terms of accuracy for the detection task. From the given table below, it looks like ResNet outperformed others with respect to accuracy for the task of interest.

![336622933-4315d274-fb47-4f5b-8d7e-6d290c7234371](https://github.com/user-attachments/assets/b474dd25-a9b1-4c03-ba98-80b582ba6b29)

Note on training/testing procedure: each model was trained with 5121 MRI images, then tested with 1279 MRI images.
