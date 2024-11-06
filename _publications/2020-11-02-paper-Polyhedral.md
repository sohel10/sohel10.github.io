---
title: "Testing Machine Learning Code using Polyhedral Region"
collection: publications
category: conferences
permalink: /publication/2020-11-02

date: 2020-11-02
venue: '28th ACM Joint European Software Engineering Conference and Symposium
on the Foundations of Software Engineering (ESEC/FSE ’20)'
paperurl: 'https://dl.acm.org/doi/pdf/10.1145/3368089.3417043'

---

The paper "Testing Machine Learning Code using Polyhedral Region" introduces a novel approach for testing machine learning (ML) code by leveraging the concept of a polyhedral region, a theoretical bounding that ensures consistency in output for inputs within a defined region. This approach detects bugs by identifying instances where the ML system produces inconsistent results for inputs within the same polyhedral region, which would indicate an implementation error.

The authors apply this testing method specifically to the lasso algorithm, a popular ML technique for sparse regression and feature selection, and validate its effectiveness through mutation testing. Mutation testing involves introducing small changes (mutants) in the code to check if the testing method can detect these introduced bugs. The study shows that the polyhedral-based testing method successfully detects 98% of the mutants in the lasso code, making it an effective tool for identifying inconsistencies in ML code.

The results suggest that this polyhedral approach can be widely applicable to various ML algorithms that satisfy the polyhedral condition, offering a rigorous and efficient way to test ML code for reliability. The authors conclude that this method provides a foundational technique for ML code testing and could lead to more comprehensive ML testing frameworks in the future.
