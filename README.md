# Predictive Modelling of Spatial Cognition in Vestibular Brain Networks

A neuroimaging analysis project testing whether vestibular-network features can predict individual differences in spatial cognition, navigation efficiency, and behavioural performance.

This repository extends cognition-mapping workflows into predictive modelling by benchmarking machine learning pipelines, evaluating model generalization, and identifying the most informative vestibular-spatial neural features.

## Project Aim

To test whether connectivity-derived features from vestibular-associated brain systems meaningfully predict spatial cognition outcomes, and to establish a scalable framework for future translational and individualized modelling.

## Dataset Used

- Domain: Vestibular and Spatial Neuroplasticity  
- Focus: Prediction of spatial cognition from brain-network features  
- Population: Healthy adult proof-of-concept samples  
- Design: Cross-sectional predictive modelling workflow  
- Modalities Referenced: fMRI, EEG-fMRI, MEG, behavioural task data

## Analytical Scope

This repository focuses on a proof-of-concept framework using:

- Predictive dataset landscape mapping
- Feature engineering from vestibular-network variables
- Baseline regression model benchmarking
- Cross-validated model comparison
- Model interpretability and error analysis
- Reproducibility and robustness testing

## Why a Predictive Pipeline Was Used

Association findings do not automatically translate into prediction. A predictive pipeline was used to test whether vestibular-network organization contains sufficient signal to estimate real behavioural differences across individuals.

This preserves the central scientific question: can vestibular neurobiology be used to forecast cognitive performance?

Future repositories may extend this framework using clinical cohorts, VR navigation paradigms, and longitudinal rehabilitation data.

## Methods

The repository used a lightweight and scalable workflow:

- Map datasets and target behavioural variables
- Engineer region-level vestibular features
- Benchmark baseline predictive models
- Compare algorithms with cross-validation
- Interpret feature importance and model errors
- Evaluate stability across repeated resamples

## Main Findings

- Vestibular-network features supported meaningful prediction of spatial outcomes
- Cross-validated models demonstrated stable generalization
- Hippocampal and vestibular cortical features were consistently informative
- Model performance remained robust across repeated resamples
- Predictive workflows are feasible for future individualized vestibular neuroscience

## Repository Workflow

### Notebook 1 - Predictive Dataset Landscape

Mapped candidate resources and behavioural targets suitable for modelling.

### Notebook 2 - Feature Engineering Baseline Models

Constructed neural feature sets and benchmarked baseline regressors.

### Notebook 3 - Model Comparison Cross Validation

Compared algorithms using repeated cross-validation metrics.

### Notebook 4 - Model Interpretability Error Analysis

Inspected feature drivers and prediction errors.

### Notebook 5 - Predictive Reproducibility Robustness

Evaluated model stability and feature consistency across resamples.

## Limitations

- Proof-of-concept modelling rather than raw cohort ingestion
- Region-level features rather than full connectome prediction
- Cross-sectional framework before longitudinal validation
- Simplified behavioural targets for scalable demonstration

## Future Directions

- Clinical dizziness and vestibular disorder prediction
- VR navigation outcome forecasting
- Longitudinal rehabilitation response modelling
- Multimodal imaging integration
- Personalized cognitive intervention pipelines

## Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Maintained By

Aditya Sundaray
