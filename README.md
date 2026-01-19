# AI & Individual Life Insurance Challenge

## 1 Overview

The SOA had a competition in 2026 where the participants were to demonstrate how AI can complement traditional actuarial techniques, enhance understanding of experience data, and contribute to better decision-making across pricing, valuation, and risk management.

The dataset was the [ILEC 12-19 dataset](https://cdn-files.soa.org/research/ilec/ilec-mort-text-data-dict-2012-2019.zip)

**Research Objectives**
Submissions should balance attention to methodological approach and practical insights. Specifically, participants are expected to:

- Justify the choice of AI techniques, including considerations of model design, transparency, interpretability, and appropriateness for actuarial practice.
- Demonstrate what practitioners can learn from the application of these methods, highlighting strengths and limitations compared to traditional actuarial techniques.
- Communicate insights drawn from the dataset, including trends, anomalies, or actionable findings that could inform real-world actuarial decision-making.
- Present results in a way that is understandable to both technical and non-technical stakeholders.

## 2 Notes

### 2.1 Local Install
To install, download this repository and run the following command in 
the environment of choice.

```
conda create --name soa python=3.12
pip install .
```

### 2.2 Jupyter Lab Usage

To have conda environments work with Jupyter Notebooks a kernel needs to be 
defined. This can be done defining a kernel, shown below.

`python -m ipykernel install --user --name=soa`

