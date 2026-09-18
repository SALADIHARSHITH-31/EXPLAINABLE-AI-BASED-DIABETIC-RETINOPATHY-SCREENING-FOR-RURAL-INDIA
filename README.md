# EXPLAINABLE-AI-BASED-DIABETIC-RETINOPATHY-SCREENING-FOR-RURAL-INDIA
CAPSTONE PROJECT 2026 -27
# ANALYSIS REPORT

THANURAKSHA

Explainable AI-Based Diabetic Retinopathy Screening for Rural India

Application Name: THANURAKSHA
Project Type: Academic Project
Domain: Artificial Intelligence / Medical Image Analysis
Primary Focus: Explainable AI for Diabetic Retinopathy (DR)
Screening
Target Context: Rural and underserved healthcare settings in India

1. About the Project

THANURAKSHA is a proposed AI-based screening application for diabetic
retinopathy using retinal fundus images.

The main aim of the project is to support early screening of diabetic
retinopathy, especially in rural and underserved areas where access to
eye specialists may be limited.

The system is planned to analyse a retinal fundus image, identify
whether signs of diabetic retinopathy are present, and provide an
explanation of the model prediction using Explainable AI techniques.

The application is intended as a screening and referral support
system. It is not designed to replace an ophthalmologist or provide a
final clinical diagnosis.

2. Problem Statement

Diabetic retinopathy is an important complication of diabetes and can
lead to vision impairment when it is not detected and managed at an
early stage.

Regular retinal screening can help identify people who may need further
examination. However, screening access can be difficult in rural and
underserved communities because of limited specialist availability,
travel requirements, and the need for trained personnel.

AI-based retinal image analysis can assist with screening. However, a
prediction without an understandable reason can be difficult for
healthcare users to review.

Therefore, this project focuses on developing a screening system that
combines:

Retinal Image Analysis + AI Detection + Explainable AI + Referral
Support

3. Why Diabetic Retinopathy?

Diabetic retinopathy is associated with long-term diabetes and may
progress without obvious symptoms during its early stages.

The need for this project is supported by published studies and reports
showing:

A large global population living with diabetes.

A substantial proportion of people with diabetes affected by
diabetic retinopathy.

A significant diabetic retinopathy burden in India.

Screening gaps in rural and underserved populations.

Evidence of diabetic retinopathy among diabetic patients in rural
Tamil Nadu.

The use of retinal photography, portable fundus cameras and
teleophthalmology for screening.

The potential role of AI in assisting retinal image grading.

4. Evidence Supporting the Need

Global

The International Diabetes Federation and International Agency for the
Prevention of Blindness have highlighted diabetic retinopathy as an
important cause of vision impairment and the need for early detection
and regular screening.

India

The National Survey of Blindness and Visual Impairment 2015--19 reported
diabetic retinopathy among people with diabetes in India and highlighted
the need for early identification and screening.

Rural India

Studies from rural India have reported screening gaps and have
investigated portable fundus cameras, primary healthcare-based screening
and teleophthalmology approaches.

Tamil Nadu

Studies from rural areas of Tamil Nadu, including Villupuram district
and rural primary healthcare settings, have reported diabetic
retinopathy among diabetic patients. This gives direct regional
relevance to the project.

5. Proposed Workflow

Patient / Screening Centre
          |
          v
Retinal Fundus Image
          |
          v
Image Quality Check
          |
          v
Image Preprocessing
          |
          v
AI-Based DR Detection / Grading
          |
          v
Explainable AI
          |
          v
Visual Explanation / Heatmap
          |
          v
Screening Report
          |
          v
Referral Guidance

6. Main Modules

6.1 Fundus Image Input

The user or healthcare worker provides a retinal fundus image for
screening.

6.2 Image Quality Check

The system can check whether the image is suitable for analysis.
Poor-quality images should be flagged instead of giving an unreliable
prediction.

6.3 Image Preprocessing

The image is prepared for the AI model through suitable preprocessing
steps such as resizing, normalization and augmentation during model
development.

6.4 Diabetic Retinopathy Detection

A deep learning image classification model will be trained to identify
diabetic retinopathy from retinal fundus images.

Depending on the selected dataset and final model design, the system can
be developed for binary detection or multi-class DR severity grading.

6.5 Explainable AI

Explainable AI methods will be used to show which regions of the retinal
image contributed to the model prediction.

Possible methods include: - Grad-CAM - Grad-CAM++ - Integrated Gradients

6.6 Screening Report

The application will present the prediction and explanation in a simple
screening-oriented format.

6.7 Referral Support

Cases requiring further examination can be directed towards an eye-care
professional.

7. AI and Machine Learning Approach

The project is expected to use deep learning for retinal image analysis.

The planned workflow is:

Collect a suitable labelled retinal fundus image dataset.

Clean and organise the dataset.

Split the data into training, validation and test sets.

Preprocess the retinal images.

Train a CNN or transfer-learning model.

Evaluate the model using appropriate metrics.

Apply Explainable AI to the trained model.

Integrate the model with the application.

Test the complete screening workflow.

Candidate model families include:

EfficientNet

ResNet

DenseNet

MobileNet

The final architecture will be selected after comparing performance,
computational requirements and suitability for the available hardware.

8. Explainable AI Component

The main research focus of this project is not only prediction but also
explanation.

A normal model may provide:

Prediction: Diabetic Retinopathy

The proposed system should also provide a visual explanation such as a
heatmap showing the retinal regions that contributed to the prediction.

Fundus Image + AI Prediction + Explainability Heatmap = More
understandable screening output

The explanation is intended to help users understand the model output
and support review by healthcare professionals. It should not be treated
as independent clinical evidence.

9. Dataset

The project will use publicly available and appropriately licensed
diabetic retinopathy retinal image datasets for model development.

Possible datasets to evaluate include:

APTOS 2019 Blindness Detection

EyePACS / Kaggle Diabetic Retinopathy

IDRiD

DDR

The final dataset will be selected based on image quality, number of
samples, class distribution, labels, licence and suitability for the
project objective.

Dataset details and the final selected dataset should be documented
separately in the repository.

10. Evaluation

The model should not be evaluated only using accuracy.

Evaluation can include:

Accuracy

Precision

Recall / Sensitivity

Specificity

F1-score

ROC-AUC

Confusion matrix

For medical screening, sensitivity and specificity are especially
important because false negative and false positive results have
different consequences.

The test set should remain separate from the training process.

11. Expected Output

The proposed application is expected to provide:

Retinal fundus image input

Image quality indication

DR screening prediction

Confidence/probability information where appropriate

Explainability heatmap

Simple screening result

Referral guidance

User-friendly interface

12. Target Users

The proposed system is mainly intended as a screening support tool for:

Rural healthcare centres

Primary healthcare settings

Community screening programmes

Healthcare workers

Eye-care referral networks

The final clinical use would require appropriate validation, expert
review and regulatory/clinical considerations.

13. Advantages

Supports early DR screening.

Can assist screening in areas with limited specialist availability.

Uses retinal fundus images for analysis.

Provides an explanation along with the AI prediction.

Can support referral.

Can be designed with a simple interface for healthcare settings.

Provides a research platform for studying Explainable AI in medical
image analysis.

14. Limitations

The current project is an academic research and prototype effort.

Important limitations include:

Dataset bias can affect model performance.

Public datasets may not fully represent rural Indian patients.

Fundus image quality can affect predictions.

Class imbalance may affect training.

AI explanations do not automatically prove that the highlighted
region is a clinical lesion.

The model requires proper external validation before real clinical
deployment.

The system should not replace examination by a qualified eye-care
professional.

15. Future Work

Future development can include:

Testing with larger and more diverse Indian retinal datasets.

Collecting locally representative data with proper ethical approval.

Improving image quality assessment.

Comparing multiple deep learning architectures.

Improving Explainable AI methods.

Adding multilingual support for rural healthcare workers.

Developing an offline or low-connectivity version.

Integrating teleophthalmology and referral workflows.

External clinical validation.

Prospective evaluation in real screening settings.

16. Proposed Technology Stack

Programming

Python

AI / Machine Learning

PyTorch or TensorFlow

OpenCV

NumPy

Pandas

Scikit-learn

Explainable AI

Grad-CAM / Grad-CAM++

Captum or another suitable XAI library

Development

Visual Studio Code

Git

GitHub

Application Layer

The final frontend and backend technologies will be selected during
implementation based on project requirements.

17. Hardware Context

The current development system is Windows 11 64-bit with:

Intel Core i5-12500H processor

16 GB RAM

NVIDIA GPU available on the system

Python 3.12 and Git are installed for development.

Training requirements will depend on the selected model and dataset.

18. Project Status

Project topic identified

Problem and need analysis prepared

Literature review started

Project scope defined

Final dataset selection

Dataset preprocessing

Baseline model development

Model training

Model evaluation

Explainable AI implementation

Backend integration

Frontend integration

Complete system testing

19. Research Focus

The main research focus is:

How can Explainable AI be used with retinal fundus image analysis to
support diabetic retinopathy screening in rural and underserved
healthcare settings in India?

The project therefore focuses on both:

Detection: What does the AI predict?

Explanation: What regions of the retinal image contributed to that
prediction?

20. Medical Disclaimer

THANURAKSHA is an academic research/prototype project.

The system is intended for screening support and research purposes
and is not a replacement for a qualified ophthalmologist.

AI predictions and explanations should be reviewed by appropriate
healthcare professionals before any clinical decision is made.

21. Literature and Evidence

The literature review covers:

Global diabetic retinopathy burden and screening needs.

Diabetic retinopathy prevalence in India.

Rural and underserved population screening.

Diabetic retinopathy evidence from Tamil Nadu.

Fundus photography and teleophthalmology.

AI-based diabetic retinopathy detection.

Explainable AI for medical image analysis.

The repository should contain the selected 10 journal papers and their
bibliographic details in a separate references or literature-review
folder.

22. Team

Team Members - Saladi Harshith - Nagireddy Gari Vara Prasad -
Gillela Hemanth Reddy

Guide - Dr. M. Pallikonda Rajasekaran

Institution - Kalasalingam Academy of Research and Education

23. Suggested Repository Structure

THANURAKSHA/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
│
├── notebooks/
├── src/
│   ├── preprocessing/
│   ├── training/
│   ├── evaluation/
│   └── explainability/
│
├── models/
├── backend/
├── frontend/
├── reports/
│   ├── analysis-report/
│   └── literature-review/
└── references/

Do not upload large datasets, trained model files or private patient
information directly to GitHub unless their licence and repository
limits allow it.

24. Conclusion

THANURAKSHA proposes an Explainable AI approach for diabetic retinopathy
screening using retinal fundus images, with special attention to rural
and underserved healthcare settings in India.

The project aims to combine AI-based image analysis with visual
explanations so that the screening output is easier to understand and
review.

The final goal is to develop and evaluate an academic prototype that can
support early screening and referral while keeping qualified eye-care
professionals involved in clinical decision-making.
