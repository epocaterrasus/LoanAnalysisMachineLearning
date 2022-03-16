# Loan Analysis using Machine Learning

In this analysis we are looking into lending data which contains the following parameters (loan size, interest rate, borrower's income, debt-to-income ratio, number of accounts and derogatory marks), these parameters determine the creditworthiness of the loan. We created a model for predicting the quality of the loan, using two logistic regression algorithms, and training them with different samples of data (one of them being oversampled).

The steps for using a machine learning model are:
* Create the model
* Fit the model
* Predict using the model

We also followed additional steps to allow us to better understand the analysis and accuracy of our model.
* Calculating the balanced accuracy of the model
* Creating Confusion Matrixes
* Creating Classification Tables

## Results

* Machine Learning Model 1:
  * 95% accuracy 
  * Class 0 (Good Loan) - 100% precision - 99% recall
  * Class 1 (Bad Loan) - 85% precision - 91% recall
  * Confusion Matrix shows us that 56 loans were wrongly categorized/predicted

* Machine Learning Model 2:
  * 99% accuracy 
  * Class 0 (Good Loan) - 100% precision - 99% recall
  * Class 1 (Bad Loan) - 84% precision - 99% recall
  * Confusion Matrix shows us that 4 loans were wrongly categorized/predicted

## Summary

After doing both models, we can see that we acchieve a higher accuracy (99%) after oversampling our data. I recommend generally using the oversampled model but if you have the time and resources doing both models and seeing which model performs best is my preferred option. In this case I believe that it is most important that our model correctly predicts the 1
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* Path (from pathlib)
* Pandas
* sklearn
* imblearn

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda and required dependencies

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

For installing Anaconda, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

For installing sklearn, you can follow the following link for guidance
* [sklearn Installation Guide](https://scikit-learn.org/stable/install.html "sklearn Installation Guide")

### 3. Downloading the Loan Analysis using Machine Learning Repository

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```https://github.com/epocaterrasus/LoanAnalysisMachineLearning.git```

### 4. Opening the file on Jupyter Notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the ```credit_risk_resampling.ipynb``` which contains all steps and notes followed to analyze this dataset pair.

---

## Contributors

Edgar Pocaterra - epocaterra@protonmail.ch / +1 806 283 5455

---

## License

MIT License

Copyright (c) 2022 epocaterrasus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.