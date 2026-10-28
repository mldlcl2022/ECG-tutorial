# ECG tutorial code

This repository provides introductory tutorial code for new researchers joining the Medical AI Lab and those interested in electrocardiogram (ECG) research. It is designed to help beginners get started with ECG data processing and deep learning-based classification.<br>

The tutorial code was developed by **Chan Lee (이찬)** and **Seokhyeon Ha (하석현)**.<br>

For more information about our research and laboratory, please visit the [Medical AI Lab (MAIL) website](https://www.k-medai.com/).<br>

<br>

## Contact

For questions, bug reports, or issues related to the tutorial code, please contact:<br>
* Code Inquiries: mldlcl2022@gmail.com<br>

If you are interested in joining the Medical AI Lab, please contact the professor directly.
* Research Opportunities: sy.kwon@pusan.ac.kr<br>

<br>

## Installation
```bash
pip install numpy==1.26.4
pip install torch==1.13.1

pip install wfdb
pip install pandas==2.2.3

pip install tqdm
pip install scikit-learn==1.5.2
pip install matplotlib
```
</br>

## Training
To ECG classification using simple CNN model, run the code below. ⬇️</br>
```python
!python main.py
```
</br>

## Results
Result of testset  
AUC: 0.9054, F1-score: 0.6782
<p align="center">
  <img src="https://github.com/user-attachments/assets/7d57cd3f-8620-49a8-b60f-bc8291ab7035" width="400">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e5d34a0b-75ee-432c-b171-fd29efb11066" alt="Image 1" width="400"/>
  <img src="https://github.com/user-attachments/assets/985fa270-00b3-44c6-b562-8d194b2f16c0" alt="Image 2" width="400"/>
</p>
</br>

</br>

# Acknowledgements
This tutorial was developed as part of the research and educational activities at the Medical AI Lab (MAIL), Pusan National University.

We would like to thank the members of the Medical AI Lab for their support and contributions to our research environment.

We hope this repository serves as a useful starting point for researchers interested in ECG analysis and deep learning.
