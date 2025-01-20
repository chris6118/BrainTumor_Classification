## DEEP LEARNING BASE-APPROACH FOR BRAIN TUMOR CLASSIFICATION AND PREVENTION

### ABSTRACT
This project delves into the classification of brain tumor Glioblastoma (GBM), a highly aggressive and malignant form of brain cancer, using an advanced deep learning approach. By analyzing medical imagery, such as MRI scans, this research aims to aid in the early detection and accurate classification of GBM, a critical step in improving treatment outcomes and patient care. Leveraging cutting-edge neural network architectures, this work bridges the fields of computer science, artificial intelligence, and medicine, specifically neurology and oncology. It also highlights the potential of AI to transform medical diagnostics by enhancing precision, reducing human error, and enabling faster decision-making in critical healthcare scenarios. 


![Image](https://github.com/user-attachments/assets/312dfb94-3eae-4d47-ae8e-f3fd5270d96c)
### GBM Image

It has been demonstrated that convolutional neural networks (CNNs) are significantly more efficient and accurate compared to traditional diagnostic methods in the field of medicine. Conventional approaches, such as biopsies where cell tissues are extracted from a living body to determine the underlying cause or nature of a disease are both time-consuming and costly. By contrast, CNNs offer a faster, non-invasive, and more precise alternative, revolutionizing the way medical diagnostics are performed.

### INTRODUCTION
The integration of deep learning, specifically convolutional neural networks (CNNs), into the field of medicine offers transformative benefits for both medical professionals and patients. These advancements include:

- Enhancing the quality of life for patients.

- Reducing the costs associated with diagnosis.

- Boosting the efficiency of medical workers by streamlining diagnostic processes.

- Supporting telemedicine, enabling remote consultations and diagnostics.

- Facilitating early tumor detection for improved treatment outcomes.

- Significantly improving diagnostic accuracy.

The motivation behind this project stems from the urgent need to address critical healthcare challenges through advanced technological solutions. This initiative is inspired by statistics from the Cancer Research Center, which reports an alarming annual mortality rate of 5,200 patients in the United Kingdom due to Glioblastoma (GBM). By focusing on early detection and accurate classification, this project aims to improve these outcomes and provide hope to those affected by this aggressive disease.

### RESEARCH METHODOLOGY
This project’s methodology emphasizes a quantitative research approach over a qualitative one, as the effectiveness of a deep learning model is heavily dependent on the volume and quality of the dataset. Large and diverse datasets are crucial for ensuring the model’s robustness and accuracy.

### Research Methodology Stages:
- Data Collection & Preprocessing
Gathering a comprehensive dataset, cleaning it, and preparing it for model input by handling missing values, normalizing data, and augmenting where necessary.

- Data Splitting
Dividing the dataset into training, validation, and testing subsets to ensure unbiased evaluation and to prevent overfitting.

- Model Architecture
Designing and configuring a convolutional neural network (CNN) tailored for the classification task, selecting appropriate layers and parameters.

- Training, Testing, and Evaluation
Training the model on the dataset, fine-tuning hyperparameters, and evaluating its performance using metrics such as accuracy, precision, recall, and F1-score.

- Deployment
Implementing the trained model into a real-world application, making it accessible for use in medical diagnostics and tumor classification.

### DESIGN AND DEVELOPMENT
This project model consists of two parts which are

### Feature Extraction
- Convolutional Layer
- Max-Pooling Layer

### Classification
- Fully Connected Layer
- Classification Layer

![Image](https://github.com/user-attachments/assets/2941a308-38f9-475f-942b-07356217f319)
### Combined Layers

### TESTING
Input the image(Input Data) into the model.

- Obtain predictions from the model
- Compare the predictions with real results (unbias)
- Calculate the evaluation metric(K Fold cross validations)
- Visualize the model

![Image](https://github.com/user-attachments/assets/7499a6f2-8b56-45f2-a77a-dee27f0c3a69)
#### Model Training with Epoch of 8.
                                             
![Image](https://github.com/user-attachments/assets/bc95ec6b-e579-43d2-938b-f36e0d008f0e)
#### Model Training Performance: Low Accuracy and High Loss 


![Image](https://github.com/user-attachments/assets/8396b6ef-d38e-41bd-a3df-2e5c59871ac5)
#### Model Training Performance: High Accuracy and Low Loss

### RESULTS/EVALUATION

Results:
- Accuracy: 90%
- Loss: 30%
Model Performance (K-Fold Cross-Validation):

Average Accuracy: 64%
The model's performance indicates potential for improvement. Fine-tuning the hyperparameters could enhance accuracy and reduce loss, leading to better overall results.

### DISCUSSION/CONCLUSION
This MSc project successfully executed the task of classifying brain tumors using a CNN-based approach, demonstrating the potential for automating brain tumor diagnosis and classification. This innovation offers significant benefits for improving efficiency in the healthcare sector. Additionally, the project underscored the ethical dimensions of brain tumor management, advocating for equitable access to healthcare services and compassionate care for all patients, regardless of their socioeconomic status.

The experimental results validate that CNNs are highly effective for photo imagery classification. However, the model's performance could be further enhanced by addressing key limitations, such as the availability of larger and more diverse datasets.

Moving forward, efforts will focus on improving the model's performance through the acquisition of diverse datasets, which will contribute to increased accuracy. By doing so, this research aims to have a meaningful impact on improving healthcare outcomes and enhancing patients' quality of life.

### REFERENCES

1. Banan, R., & Hartmann, C. (2017). The new WHO 2016 classification of brain tumors—what neurosurgeons need to know. Acta Neurochir, 159(3), 403–418. https://doi.org/10.1007/s00701-016-3062-34

2. Barboriak, D. (2015). Data from RIDER_NEURO_MRI. Cancer Imaging Archive. https://doi.org/10.7937/K9/TCIA.2015.VOSN3HN1

3. Bruno, M. A., Walker, E. A., & Abujudeh, H. H. (2015). Understanding and confronting our mistakes: The epidemiology of error in radiology and strategies for error reduction. Radiographics, 35(6), 1668–1676. https://doi.org/10.1148/rg.2015150023

4. Wais, M. S. (2023). Does ethnicity affect brain tumor survival? Healthcare in Europe. Accessed June 23, 2023. https://healthcare-in-europe.com/en/news/ethnicity-brain-tumour-survival.html




