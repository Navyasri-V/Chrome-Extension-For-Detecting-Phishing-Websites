## Train and Export RandomForestClassifier

Before getting to this part, the dataset preprocessing has to be done and the `/backend/dataset/` directory should contain test and train `.npy` files.  
Incase you're not done with that, refer [here for preprocessing](../dataset/)

The RandomForestClassifier *(ensemble learner)* is fitted with the training set and then the accuracy and cross validation scores are printed.  
The parameters of the learned model, such as number of estimators, tree parameters such as thresholds for each estimators are dumped on to a file named `classifier.json`.

Change working directory to `/backend/classifier` and Run    
> `python3 training.py`

`classifier.py` is created in the `/static` directory.  
Serve this `classifier.py` over HTTP and update URL in the plugin settings.  
The same file is also hosted [here](https://github.com/navyasweet/Chrome-Extension-For-Detecting-Phishing-Websites/blob/239223b1cd0359b4d8f0f317db9e3fe6b68ea62d/static/classifier.json).
