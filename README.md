# Parallelised Anomaly Neural Training

## **Acknowledgemnents**

This project, though far from perfect, represents our journey as first-semester Bachelor's students in Electronics and Communication Engineering (ECE). While the results may not be groundbreaking, it has been an invaluable learning experience. We embarked on this project driven by curiosity and a desire to explore quantum computing and federated learning, even if the outcome wasn't as impressive as we hoped.

We would like to thank our seniors, **Nandan Patel and Ashwin**, for their guidance and feedback, which helped shape our understanding, even though we still have a lot to learn. We also appreciate **Dr. Reena Monica, Associate Dean of the School of Electronics Engineering at VIT Chennai**, for her time and encouragement throughout the process.

We fully acknowledge the imperfections in this project and are open to collaborating with anyone who believes we have the potential to improve. We hope to have the opportunity to work with eBRAIN Lab and CQTS at New York University Abu Dhabi to further develop our solutions properly and hopefully get our much-needed guidance and support.

A special thanks to **Dr. Nouhaila Innan** for her inspiring talk during the Qiskit Fall Fest, which ignited our interest in this competition and motivated us to take on this challenge.

While this project may not be groundbreaking, it has been a valuable stepping stone in our learning journey. We look forward to improving and continuing to explore new ideas. Thank you to everyone who supported us along the way!



## Abstract

This project implements a Quantum Federated Learning (QFL) framework for fraud detection in decentralized systems. Traditional Federated Learning (FL) preserves privacy but is vulnerable to adversarial attacks. By integrating Quantum Vector Support Machines (QVSM) and Quantum Differential Privacy (QDP), our architecture enhances security and resilience. Using Qiskit, PennyLane, TensorFlow Federated, and Flower, we combine quantum computing with FL to improve fraud detection. Performance is evaluated through metrics like accuracy, precision, recall, F1-score, and AUC-ROC.


## Introduction

Fraud detection in financial systems is critical, and while ML models can identify fraud, they often rely on centralized data, raising privacy concerns. Federated Learning (FL) mitigates these concerns but remains susceptible to adversarial attacks. Quantum Federated Learning (QFL) combines FL with quantum computing to enhance security. By integrating QVSM and QDP, QFL introduces quantum unpredictability to better resist adversarial manipulations. Frameworks such as Qiskit, PennyLane, and TensorFlow Federated are used for simulation and evaluation.

## Methodology

### Differential Privacy

- **Classical Differential Privacy**: Introduces noise to protect privacy during data processing.
- **Quantum Differential Privacy**: Extends classical differential privacy to quantum systems, ensuring privacy via quantum noise and post-measurement techniques.

### Achieving Quantum Differential Privacy

- **Quantum Noise Mechanisms**: Introduces noise to quantum systems for enhanced privacy.
- **Quantum Randomized Algorithms**: Controlled randomness provides stronger privacy guarantees.

## Implemented Solution

Our solution builds a QFL framework for fraud detection using federated learning principles and quantum noise mechanisms to protect privacy during model training.

### Advanced Encryption

We use a hybrid quantum-classical approach for privacy-preserving gradient encryption, adding quantum noise and Laplace noise to ensure differential privacy.

### Decentralized Client-Server Workflow

A client-server model facilitates decentralized model updates, using Python socket programming for file transfers, and multithreading for parallel execution.

## Conclusion and Future Work

This project demonstrates the potential of QFL with quantum differential privacy to address security challenges in fraud detection. Future work will focus on optimizing quantum noise models and scaling the QFL framework.
