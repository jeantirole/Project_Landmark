# Project_Landmark

## Overview 
### (1) Topic: 
 Train CNN classification model using landmark images collected through web crawling and explore ways to improve performance



### (2) Dataset:
- The number of landmark categories : 17
- The number of image dataset through google crawling : 6800
- The number of editted image dataset : 4,426 

||||||
|--------------------|------------------------|----------------------|---------------------|----------------------|
| 01 Eiffel Tower    | 02 Cristo Redentor     | 03 Triumphal Arch    | 04 Wànlĭ Chángchéng | 05 Taj Mahal         |
| 06 Sungnyemun Gate | 07 Moai                | 08 Seokguram buddha  | 09 Golden Gate      | 10 Statue of Liberty |
| 11 Torre di Pisa   | 12 Colosseum           | 13 Santiago Bernabéu | 14 Sphinx           | 15 Burj Khalifa      |
| 16 London Eye      | 17 London Tower Bridge |----------------------|---------------------|----------------------|

### (3) Model Performance Improvement: 
- Keras Sequential Model 
- Hyper Parameter Set 
- Layer options (Convolution2D, Activation, MaxPooling, Dropout, etc.) 
- Other options (image augmentation, VGG-16, Evaluation criteria : top3 acc) 


## I. Dataset build 
- Data path check and designation
- Create image category list
- Training and testing
- Save image data inumpy form

## II. Model build
- Create data loading function
- Model construction function creation (Convolution2D, Activation, MaxPooling, Dropout, etc.)
- Model training function generation (batch_size, epochs)
- Model evaluation function creation (loss & accuracy)

## III. Model run
- Test image list
- Run prediction models using test images
- Result output


