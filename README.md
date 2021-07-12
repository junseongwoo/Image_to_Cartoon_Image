# Image_to_Cartoon_Imag

## Introduction

이번 프로젝트는 Python과 OpenCV, 그리고 Jupyter를 이용하여 OpenCV의 Detail Enhancing Filter와 
Image to PencilSketch, Image to Cartoon Image를 공부한 것을 만들어 보았습니다.

---


## Dependencies

- Python 3.x, OpenCV 4.x, matplotlib, jupyter
- To install the required packages, run pip install -r requirements.txt.

---

## Description

### 1) Detail Enhancing Filter
- cv2.detailEnhance는 이미지의 디테일을 향상시켜주는 함수입니다. 
- cv2.detailEnhance ( InputArray src, OutputArray dst, float sigma_s, float sigma_r)의 구조로 사용합니다.
- sigma_s는 0 ~ 200 범위로 사용, 이미지가 얼마나 스무스할지 결정하는 파라미터이며 클수록 스무스해집니다.
- sigma_r은 0 ~ 1 범위로 사용, 이미지가 스무스해지는 동안 엣지를 얼마나 보존시키는지 결정하는 파라미터이며 작을수록 엣지가 많이 보존됩니다.


### 2) Image to PencilSketch


![Pencil](/results/desc1.png)


### 3) Image to Cartoon Image


![Pencil](/results/desc2.png)




--- 

## Output

### 1) Detail Enhancing Filter

<img src="/results/result1.png" width="480" height="400"/>

![result](/results/result2.png)

### 2) Image to PencilSketch
<img src="/results/result3.png" width="480" height="400"/>

![result](/results/result4.png)

### 3) Image to Cartoon Image
<img src="/results/result5.png" width="480" height="400"/>

![result](/results/result6.png)


---
 

