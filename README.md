# OPTIMIZATION-MODEL

COMPANY: CODTECH IT SOLUTIONS

NAME: MANGESH VAJIRE

INTERN ID : CT08UBW

DOMAIN : DATA SCIENCE

DURATION: 4 WEEEKS

MENTOR: NILA SANTOSH

DESCRIPTION :

The project consists of four main components: First, a furniture production optimization system that uses linear programming to maximize profit while considering labor and wood constraints, calculating optimal production quantities for chairs and tables. Second, an advanced image classification system using CNN architecture with the CIFAR-10 dataset, featuring data augmentation, batch normalization, and comprehensive performance visualization. Third, a robust data preprocessing pipeline that handles both numerical and categorical data with flexible scaling options and proper encoding techniques. Fourth, an insurance pricing forecast system that implements linear regression to predict insurance premiums based on age data, demonstrating practical application of machine learning in the insurance industry.

This data science project showcases a diverse range of analytical and optimization techniques:

The furniture production optimization module uses PuLP for linear programming, efficiently determining the optimal number of chairs and tables to produce while respecting labor (100 hours) and wood (800 sq ft) constraints. The model maximizes profit with chairs earning $60 and tables earning $100 per unit.

The image classification system implements a sophisticated CNN using PyTorch to classify CIFAR-10 images. It features data augmentation techniques like random flips and rotations, batch normalization for better training stability, and dropout layers for regularization. The model's performance is tracked through detailed visualizations of training/validation metrics and confusion matrices.

The data preprocessing pipeline provides a flexible framework for handling mixed data types. It incorporates StandardScaler and MinMaxScaler for numerical features and OneHotEncoder for categorical variables, with proper handling of missing values through imputation strategies.

The insurance pricing forecast demonstrates practical regression analysis, using synthetic age data to predict insurance premiums. The linear regression model visualizes the relationship between age and premium costs, providing insights for pricing strategies.

All components are well-documented with clear code structure, proper error handling, and visualization capabilities, making it a comprehensive showcase of modern data science practices.

RESOURCES :

Based on the codebase, I'll analyze the resource requirements and constraints across different components of the project. The furniture production optimization uses labor hours and wood as key resources, the image classifier requires computational resources for CNN model training, and the data preprocessing pipeline handles various data resources including numerical and categorical features. I'll examine the specific resource allocations, constraints, and utilization patterns in each component.

The project utilizes various resources across different components:

1. Furniture Production Optimization (optimization_solution.py):
- Labor resources: 100 hours total capacity
- Wood material: 800 sq ft total capacity
- Resource constraints are clearly defined and monitored
- Optimal resource allocation shows efficient utilization
2. Image Classification System (improved_image_classifier.py):
- Computational resources: GPU/CPU utilization through PyTorch
- Memory management for batch processing (128 batch size)
- Model parameters storage (best_model.pth)
- Data resources: CIFAR-10 dataset stored in /data directory
3. Data Preprocessing Pipeline (data_preprocessing_pipeline.py):
- Handles both numerical and categorical data resources
- Efficient memory usage through pipeline transformations
- Scalable preprocessing for optimization-related data
- Resource type handling (labor, machine) with missing value management
4. Insurance Pricing System:
- Data resources: Age and premium information
- Memory efficient synthetic data generation
- Visualization resources for plotting results
All components demonstrate careful resource management and efficient utilization patterns, with clear constraints and optimization strategies in place.
Based on the project files, the main libraries used are: 1) PuLP for linear programming optimization, 2) PyTorch and torchvision for deep learning and image classification, 3) scikit-learn for machine learning components including preprocessing and metrics, 4) pandas and numpy for data manipulation, 5) matplotlib and seaborn for data visualization. These libraries form a comprehensive stack for implementing optimization, machine learning, and data processing functionalities in the project.

OUTPUT 
