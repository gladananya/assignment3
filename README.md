
# Learning a Probability Density Function from Data

## Overview
This project learns a **Probability Density Function (PDF)** from a given dataset using parameter estimation.  
The goal is to model the underlying data distribution and visually compare the learned PDF with the empirical data distribution.

---

## Methodology
- Input data samples `z` are collected  
- A parametric PDF is assumed  
- Model parameters are learned from the data  
- The learned PDF is compared with the data histogram  

---

## Results

### Learned Parameters
The following parameters were estimated from the data:

- **Mean (μ):** 25.8180  
- **Lambda (λ):** 0.0014617  
- **Scaling Constant (c):** 0.02157  

These parameters define the final learned probability density function.

---

## Conclusion
The learned probability density function successfully models the distribution of the data.  
The close alignment between the histogram and the learned PDF indicates effective parameter estimation and a good fit to the observed samples.

---

## Tools Used
- Python  
- NumPy  
- Matplotlib  

---

## Author
**Ananya**
