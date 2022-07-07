# Federated-anderson-acceleration

The experiment is aimed to find the effectiveness of anderson acceleration while using Fedavg algorithm. In this experiment, first the feature 'age' which is linearly related to the medical coverages for the non-smokers is discovered while doing EDA on the data.

Data is available at "https://www.kaggle.com/code/hely333/eda-regression/data". Some of the EDA is taken from "https://www.kaggle.com/code/hely333/eda-regression/notebook".

Firstly, it is shown how anderson acceleration can improves the performance by speeding up the convergenece time and it is even better than the SGD regressor of the sklearn package. Then the data is trained using fedavg algorithm and is shown that the anderson acceleration improves the convergence time even while using fedavg algorithm. Finally, a comparison of the performances for different memory sizes is made and is shown it improves as we improve the memory buffer size
