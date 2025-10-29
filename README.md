# cv-project-plant-disease-classification

Rodrigo Sierra

Project Tier 1
This project is tier 1 because it focuses on creating and training an image classification model (ResNet). The model is built from the beginning using a special dataset of plant leaves to solve a specific problem.

Problem Statement
For improving crop production and reduce financial losses is very critical detection plant diseases. Nowadays, manual inspection methods are inefficient because they require a lot of labor and are slow. In addition, these methods often lead to human errors, which delay the response time needed to solve the problem.

Solution Overview
This project aims to build an image classification model that can automatically detect and classify common plant diseases from leaf images. The proposed solution will give farmers a fast way to find plant health problems and take action to care their crops.

Technical Approach
- CV Technique: Classification.
- Model: ResNet50.
- Framework: PyTorch
- Why this approach: ResNet50 is selected because it has shown high accuracy in image recognition tasks. Its structure makes it easier to train deep learning networks to learn complex image features (disease patterns).

Dataset
- Source: PlantVillage Dataset.
- Size: 54.000+ images.
- Labels: 38 different classes.
- Link: https://www.kaggle.com/datasets/emmarex/plantdisease

Success Metrics
- Primary Metric: Accuracy.
- Target: Greater than 90% accuracy.
- Secondary Metrics: F1-score.

Week-by-week Plan
    Week                      Tasks                      Milestone
10 (Oct 30)      Get dataset, set up environment       Dataset ready
11 (Nov 06)      Train/fine-tune model                 Model working
                 Load Pre-trained model (ResNet)
                 Organize dataset
                 Fine-tune model                 
12 (Nov 13)      Test and improve                      Good accuracy
                 Evaluate performance
                 Improve performance 
                 (if required)                 
13 (Nov 20)      Create demo, make video               Demo ready
                 Make demo notebook
                 Record demo video
                 Update README.md                 
14 (Nov 27)      Final testing, documentation          Everything done
                 Clean up code
                 Make presentations slides
                 Final testing
15 (Dec 04)      Presentation                          Presentation done

Resources Needed
- Compute: Google Colab or Google Colab Pro.
- Cost: 0 - 10 USD
- API: No.

Risks & Mitigation
Risk                      Probability                      Mitigation
Overfitting               Medium                           Implement strong data augmentation.
Class Imbalance           Medium                           Use of Weighted Cross-Entropy Loss.
Interruption
Training Time             Medium                           Use Google Colab Pro

AI Usage Log


Current Status
- OK Repository created.
- OK Proposal written.
-    Dataset acquired.
-    Model training started.
-    Demo created.
-    Final presentation ready.
