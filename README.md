# AirBnb Pricing Prediction using Regression

### Software and Tools used

1. [Github](http://www.github.com) -- Version Control
2. [VS Code](https://code.visualstudio.com) -- IDE
3. [Vercel](https://vercel.app) -- Deployment


## Setting up conda environment
```
 
conda create -p venv python==3.10 -y

```

### Feature Engineering
* Calculate distance of each AirBnb property to the nearest MRT (Mass Rapid Transit) in Singapore as of Feb 2020

### Regression Models Used (each model is trained with 10-fold cross-validation)
* Support Vector Regression
* Random Forest Regression
* XG Boost Regression
* Light GBM Regression
* Stacked Regression

### Pickling of components for deployment
* Save and load the scaling algorithm
* Save and load the XG Boost model 

### Docker Setup
* Created a Procfile to create steps in developing the CI/CD pipeline
