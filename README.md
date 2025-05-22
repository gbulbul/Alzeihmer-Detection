Alzeihmer detection and classification are two different and essential tasks to take precautions for prevention and improve its treatment. DL and ML approaches are used to achieve both tasks. In this context, detection refers to discover whether a patient is demented or not. On the other hand, classification task aims to assign a patient into a correct group of alzeihmer to specify treatment while there are 4 groups defined.

333302871-c4a92c22-7aee-4195-b933-6ecdab837ad8

The above figure shows the four groups of dementia. The dementia classes can be codified like this NonDemented:0, ModerateDemented:1, MildDemented:2, VeryMildDemented:3. In the detection procedure, the number of the classes should be reduced to two like NonDemented:0 & Demented:1 where Moderate, Mild and VeryMild cases fall into the second category.

7 deep learning models were compared in terms of accuracy for the detection task. From the given table below, it looks like ResNet outperformed others with respect to accuracy for the task of interest.

336622933-4315d274-fb47-4f5b-8d7e-6d290c7234371

Note on training/testing procedure: each model was trained with 5121 MRI images, then tested with 1279 MRI images.
