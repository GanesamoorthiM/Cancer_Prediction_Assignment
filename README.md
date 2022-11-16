# Multiclass Classification Model Using a Custom Convolutional Neural Network in TensorFlow 

# Bike Sharing Case Study

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.





## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)

* [Conclusions](#conclusions)

* [Acknowledgements](#acknowledgements)



<!-- You can include any other section that is pertinent to your problem -->


## General Information

- CNN based model which can accurately detect melanoma.
- Evaluate images and alert dermatologists about the presence of melanoma. 

## Conclusions

Accuracy Before applying Augumentation :
-   Traning DS:89%
-   Validation DS:52%
-   Based on this model we can conclude it's a overfit model
-   We may add another few layers to increase the accuracy of the model
-   We need to remove the BatchNormalization layers.
-   it indicates Overfit in the model.

Accuracy After applying Augumentation
-   Training: More than90% 
-   Validation:Nearly 80%
-   model accuracy has improved
-   the class rebalance has helped treat the overfitting to some extent.

- more epochs and more layers can be used to build much better model
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Technologies Used

- library - numpy

- library - pandas
- library - matplotlib
- library - tensorflow
- library - google.colab


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Acknowledgements

- This project was based on live uprgrad session on Case Study Anaylsis



## Contact
'
Created by [@GanesamoorthiM] - feel free to contact me! - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->