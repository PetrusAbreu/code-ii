# CODE-II: A large-scale dataset for artificial intelligence in ECG analysis

> **Note:** This repository is currently under construction. Information and links will be updated as they become available.

---

## Overview

This repository provides information and resources related to the **CODE-II** dataset, described in the following manuscript:

> Abreu, P. E. O. G. B. et al. CODE-II: A large-scale dataset for artificial intelligence in ECG analysis. *npj Digital Medicine* (2026). https://doi.org/10.1038/s41746-026-02704-4

CODE-II is a large-scale, real-world dataset of 12-lead ECG exams collected and annotated by the Telehealth Network of Minas Gerais (TNMG) from January 2019 to December 2022. After quality-control procedures, the curated dataset comprises approximately **2.7 million exams from 2.1 million unique patients**, annotated with **66 expert-defined CODE diagnostic classes**.

---

## Datasets

### CODE-II (Full Dataset)

The full CODE-II dataset is restricted. Requests for access are considered on an individual basis by the Telehealth Network of Minas Gerais.

Contact: telessaude.hc-ufmg@ebserh.gov.br (with the corresponding authors in copy)

Any data use is restricted to non-commercial research purposes and requires the execution of appropriate data use agreements.

---

### CODE-II-open

A publicly available subset comprising **15,000 unique-patient ECG exams** annotated with the 66 expert-defined CODE diagnostic classes. Pre-defined clinically stratified training (12,000 exams) and validation (3,000 exams) splits are included to mitigate sampling bias and enable fair algorithmic comparisons.

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

PhysioNet: *coming soon*

---

### CODE-II-test

A non-overlapping test set comprising **8,475 unique-patient ECG exams**, annotated by multiple cardiologists under standardized criteria, designed for blind evaluation of AI algorithms. ECG signals are publicly available under CC BY-NC-SA 4.0. Expert annotations are reserved for benchmarking and are not publicly released; however, any user may submit model predictions for evaluation under controlled access.

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

PhysioNet: *coming soon*

---

## Citation

If you use this dataset in your research, please cite:

```
Abreu, P. E. O. G. B., Paixão, G. M. M., Li, J., Gomes, P. R., Macfarlane, P. W.,
Oliveira, A. C. S., Carvalho, V. T., Schön, T. B., Ribeiro, A. L. P. & Ribeiro, A. H.
CODE-II: A large-scale dataset for artificial intelligence in ECG analysis.
npj Digital Medicine (2026). https://doi.org/10.1038/s41746-026-02704-4
```

---

## Related Resources

Code for ECG signal preprocessing: https://github.com/antonior92/ecg-preprocessing

---

## Contact

For questions regarding data access or the dataset, please contact the corresponding authors:

- petrusabreu@ufmg.br
- antonio.ribeiro@ebserh.gov.br
- antonio.horta.ribeiro@it.uu.se
