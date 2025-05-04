# Variational Quantum Circuits for Classification: A Hybrid Approach

## Project Overview

This project implements and evaluates a Variational Quantum Classifier (VQC) using quantum machine learning techniques for binary classification tasks. We compare the performance of our quantum approach against traditional classical machine learning methods to assess potential quantum advantages in pattern recognition and high-dimensional data processing.

## Team Members

- Bhumika Gupta (bhumika034btcse21@igdtuw.ac.in)
- Shreya Saroha (shreya039btcse21@igdtuw.ac.in)
- Nidhi Bhatt (nidhi040btcse21@igdtuw.ac.in)
- Renuka Joshi (renuka012btcse21@igdtuw.ac.in)

## Problem Statement

Classical machine learning models often struggle with complex pattern recognition and high-dimensional data. This project explores how Variational Quantum Circuits (VQCs) can leverage quantum properties like superposition and entanglement to potentially achieve better classification performance on real-world datasets.

## Research Gap Addressed

This work addresses several limitations in current quantum machine learning research:

- Limited comparative studies between classical feature engineering and quantum feature mapping
- Insufficient understanding of which quantum embeddings work best for specific data types
- Few practical demonstrations of quantum models' advantages in real-world applications

## Methodology

### Dataset

- The Titanic dataset was used for binary classification (survival prediction)
- Passenger attributes were encoded as quantum states

### Implementation Details

- **Tools & Libraries**: PennyLane and Qiskit for quantum computing implementations
- **Quantum Circuit Design**:
  - Rotation gates for creating superposition states
  - CNOT gates for generating entanglement
  - Two-layer ansatz architecture balancing complexity and performance
- **Training**: Adam optimizer with a qubit simulator
- **Benchmark**: Logistic Regression model for performance comparison

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC curves and AUC scores

## Results & Findings

### Performance Comparison

- **VQC Accuracy**: 78.89%
- **Logistic Regression Accuracy**: 75.56%

The confusion matrices and ROC curves show that the VQC implementation achieved higher classification accuracy than the classical logistic regression model. However, the AUC score for the VQC (0.678) was slightly lower than that of logistic regression (0.738).

### Key Observations

- VQC performance is highly dependent on feature selection and circuit depth
- Excessive circuit layers can lead to overfitting, highlighting the importance of optimal architecture design

## Conclusions

### Key Takeaways

- Variational Quantum Circuits show potential for classification tasks but require careful fine-tuning to consistently outperform classical methods
- Feature embedding choices significantly impact classification results

### Future Work

- Test on larger datasets to validate scalability of the quantum approach
- Explore different quantum embedding methods (Amplitude Encoding, Angle Encoding)
- Implement on actual quantum hardware for real-world feasibility analysis

## Getting Started

(Add installation instructions, dependencies, and basic usage examples here)

## References

(Add relevant papers, resources, and citations here)
