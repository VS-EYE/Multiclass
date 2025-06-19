# Multiclass

In this section, we provide detailed information about the datasets used to assess the reliability and efficacy of our proposed model in differentiating various medical conditions across diverse modalities. The datasets utilized in this study include MRI [42], Chest X-ray [55], and
endoscopic [56] images. Each modality presents unique characteristics, such as infection regions and tumor sizes, which are crucial for evaluating the model performance across different medical scenarios.

Table 1
provides an overview of dataset distribution across different classes for training, testing, validation, and total dataset size. For each class, the number of samples is divided into training, testing, and validation subsets. For example, the COVID class has 1440 samples for training,
400 for testing, and 160 for validation, totaling 2000 samples. Other classes, such as Colorectal cancer and Pylorus, have fewer samples, with totals of 139 and 150, respectively. The distribution varies significantly
among classes, with some like Glioma and Meningioma having larger datasets, indicating a focus on balancing the dataset size across various medical conditions to ensure comprehensive model training and evaluation.

Table 1
Overview of Dataset Distribution.
Class             Train Test Validation Total
Colorectal cancer 100   28   11         139
COVID             1440  400  160        2000
Esophagitis       77    21   9          107
glioma            1189  300  132        1620
Lung Opacity      1440  400  160        2000
meningioma        1206  306  133        1645
pituitary         1311  300  146        1757
Pylorus           108   30   12         150
Viral Pneumonia   968   269  108        1345

