# feature Engineering
![feature engineering](https://miro.medium.com/v2/resize:fit:1400/1*sopItiVC6VJnR-qmyKMFyw.jpeg)


Feature Engineering
├── 1. Handling Missing Values
│   ├── Mean / Median / Mode Imputation
│   ├── Constant Value Imputation
│   ├── Forward / Backward Fill
│   ├── KNN Imputer
│   └── Iterative / MICE Imputer
│
├── 2. Handling Categorical Features
│   ├── Label Encoding
│   ├── One-Hot Encoding
│   ├── Ordinal Encoding
│   ├── Frequency / Count Encoding
│   ├── Target / Mean Encoding
│   └── Binary / Hash Encoding
│
├── 3. Handling Numerical Features
│   ├── Scaling / Normalization
│   │   ├── Min-Max Scaling
│   │   ├── Standardization (Z-score)
│   │   └── Robust Scaling
│   ├── Transformation / Skewness Correction
│   │   ├── Log Transformation
│   │   ├── Square Root / Cube Root
│   │   └── Box-Cox / Yeo-Johnson
│   ├── Outlier Handling
│   └── Binning / Discretization
│       ├── Equal-Width Binning
│       ├── Equal-Frequency Binning
│       ├── Custom / Domain-Specific Binning
│       └── Clustering-Based Binning
│
├── 4. Feature Generation
│   ├── Polynomial Features
│   ├── Interaction Terms
│   ├── Date-Time Features (Year, Month, Weekday, Hour)
│   ├── Lag / Rolling Features (Time Series)
│   ├── Text Features (TF-IDF, Count, Word2Vec)
│   └── Aggregation / Grouping Features
│
├── 5. Feature Selection
│   ├── Filter Methods
│   │   ├── Correlation
│   │   ├── Chi-Square
│   │   └── ANOVA
│   ├── Wrapper Methods
│   │   └── Recursive Feature Elimination (RFE)
│   └── Embedded Methods
│       ├── Lasso / Ridge
│       └── Tree-Based Feature Importance
│
├── 6. Dimensionality Reduction
│   ├── PCA (Principal Component Analysis)
│   ├── LDA (Linear Discriminant Analysis)
│   └── t-SNE / UMAP (Visualization)
│
├── 7. Handling Imbalanced Data
│   ├── Oversampling (SMOTE, ADASYN)
│   ├── Undersampling
│   └── Class Weight Adjustment
│
├── 8. Automation in Feature Engineering
│   ├── Featuretools
│   ├── tsfresh (Time Series)
│   └── Pipelines (Sklearn ColumnTransformer / Pipeline)
│
└── 9. Best Practices
    ├── Avoid Data Leakage
    ├── Keep Features Interpretable
    ├── Test Feature Impact on Validation Set
    └── Document Transformations
