# Convolutional Neural Network for Pneumonia Patients 

<img src="https://miro.medium.com/max/612/1*7OObzMi5WbGiY4QprfJ3Lw.jpeg" width="300"><img src="https://img2.pngio.com/business-growth-chart-png-transparent-growth-charts-transparent-business-growth-png-820_387.png" width="500">

*Author: John Paul Hernandez Alcala*

## Description 
This project uses a data derived method for classifying patients that have pneumonia or normal lungs. A presentation that covers the consturction of the Convolutional Neural Network models, importance of metric selection (e.g. accuracy vs. sensitivity), and impact of these models on healthcare.



## Where to Start First:

### 1. Access the [Convolutional Neural Network for Pneumonia Patients ](https://www.kaggle.com/johnpaulhernandez/convolution-neural-network-for-pneumonia-patients/edit) first.
### 2. Follow along with the coding narrative and comments.
### 3. Preview the uploaded presentation, [Convolutional Neural Network for Pneumonia Patients ](https://github.com/JohnPaulHernandezAlcala/Bank-Targeted-Marketing/blob/master/Bank%20Targeted%20Marketing.pdf).

### Original Model
![](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/ROC-Initial-Model.pngg)

### Model with Custom Threshold
![](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/ROC-Initial-Model-w-threshold.png)

### Model with Custom Threshold Confusion Matrix
![Confusion Matrix](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/ConfusionMatrix-Initial-Model.PNG)

Here we see our model with and without a threshold implemented. This threshold makes our model more specific, but less sensitive than the default threshold of 0.5; that is, our threshold model allows for more false negatives in order to reduce false positives so an optimal accuracy can be achieved. With the threshold model, we are able to classify ~85% of patients with pneumonia who were indeed infected, and it also classified 95% of patients without pneumonia who were indeed not infected. This is compared to our original model that was able to classify ~89% of patients with pneumonia as who were indeed infected and 91% of patients without pneumonia who were indeed not infected.


### ROC-AUC Graph of Second Model and Initial Model with Custom Threshold
![](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/initial-and-second-model-ROC.png)

### Second Model Confusion Matrix
![Confusion Matrix](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/Second-model-Confusion-Matrix.PNG)

## Loss and Recall Graphs
![](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/Second-model-loss.png)
![](https://github.com/JohnPaulHernandezAlcala/Image-Classification-with-Deep-Learning-of-Pneumonia/blob/main/Second-model-recall.png)


## Conclusion
From the above, we see that the best model is the second model because it has the least amount of loss and high recall. With this model and our total analysis, we can produce three business recommendations:

1. **Paves the way for efficient diagnosis**
2. **Allows for quick insurance validation**
3. **Promotes accessibility to high quality medical care**

Now that we have proposed our three business recommendations, we know there are ways we can improve our current model. We can use drop rate and different optimizers which change weights and learning rate in order to reduce the losses. We can build a model that has more than 2 layers so more features can be extracted. Finally, we can get more data to train and test against our current model which will allows us to work towards a better model.


## Support
If you need any help, please email me at johnhdz1023@gmail.com.

## Acknowledgments
I want to thank my girlfriend, Haley, [Flatiron School](https://flatironschool.com/), my cohort, and my technical advisor, [Eli](http://linkedin.com/in/jacob-eli-thomas-4377037), and Lindsey Berlin

## Contribution
See [CONTRIBUTING.md](https://github.com/JohnPaulHernandezAlcala/House_Sale_Prices/blob/master/CONTRIBUTING.md)

# License
See [LICENSE.md](https://github.com/JohnPaulHernandezAlcala/House_Sale_Prices/blob/master/LICENSE.md)

# Relevant Papers:

[S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014](http://media.salford-systems.com/video/tutorial/2015/targeted_marketing.pdf)

[S. Moro, R. Laureano and P. Cortez. Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology. In P. Novais et al. (Eds.), Proceedings of the European Simulation and Modelling Conference - ESM'2011, pp. 117-121, Guimaraes, Portugal, October, 2011. EUROSIS. [bank.zip]](https://www.semanticscholar.org/paper/Using-data-mining-for-bank-direct-marketing%3A-an-of-Moro-Laureano/a175aeb08734fd669beaffd3d185a424a6f03b84)

# Image Sources:
https://cdn.wallethub.com/wallethub/posts/76002/banking-landscape-report.png

https://img2.pngio.com/business-growth-chart-png-transparent-growth-charts-transparent-business-growth-png-820_387.png

https://acrobatant.com/wp-content/uploads/2018/09/Target_Marketing.jpg

#### -- Project Status: [Completed]
