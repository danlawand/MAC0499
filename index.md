#  Introducing MLOps Practices in the SPIRA Continuos Training Pipeline

Page for the discipline MAC0499 - Capstone Project - at IME-USP.

### **Members:** Daniel Angelo Esteves Lawand (10297693)

### **Supervisors:**
  - Prof. Dr. Alfredo Goldman
  - M.Sc. Renato Cordeiro Ferreira

### **Summary:**

During the COVID-19 pandemic, an interdisciplinary group from the University of São Paulo created SPIRA: an intelligent system capable of pre-diagnosing respiratory insufficiency via speech analysis based on Machine Learning (ML). Currently, the project is being prepared to train a new generation of models with data collected from partner hospitals. The goal of this research is to implement a continuous training pipeline for SPIRA. This will allow automatic, on-demand retraining of models as new labeled data gets acquired over time. Unfortunately, the original experimental pipeline lacked good MLOps practices, which come from both software engineering and machine learning practices. This made the pipeline difficult to maintain. To improve its reliability, this research applied changes into three layers of the system: architecture, components, and code. For the architectural layer, it introduced the hexagonal architectural pattern, isolating business logic (core) from external dependencies (adapters) through well-defined interfaces (ports). In the component layer, it applied design patterns and ML engineering practices to improve the flexibility of the system. Finally, in the code layer, it used clean code techniques to make development decisions more explicit and ease the onboarding of new developers. Overall, these changes brought important quality attributes for the system: maintainability, extensibility, and readability. Moreover, it allowed the automated deployment and execution of the pipeline. When combined, these improvements will provide a consistent framework for data scientists to further evolve the SPIRA model.

## Proposal (in Portuguese)

[Download](./docs/proposal.pdf) | [Online](https://github.com/danlawand/MAC0499/blob/main/docs/proposal.pdf)

<!--
## WIP - Presentation

[Online](https://docs.google.com/presentation/d/1YwmEnBYANt809Q-RLivfO-HputAdU7U2H2g3XSCWky0/edit?usp=sharing)

 ## Poster

[Download](./poster.pdf)

## Published Article

[Download](./cbsoft.pdf)

## Subjective Part

[Download](./subjective_part.pdf)
-->
## WIP - Monograph

[Download](./docs/monograph.pdf) | [Online](https://github.com/danlawand/MAC0499/blob/main/docs/monograph.pdf)

## Repository

<!--| Description |
| --- |-->
[Training Pipeline](https://github.com/spirabr/SPIRA-training)


## Contact Information

Any questions? Send an e-mail to daniel.lawand at usp.br


<sub>Page inspired by the [Bachelor's Monograph](https://daitamae.github.io/MAC0499/) of Vitor Daisuke Tamae</sub>
