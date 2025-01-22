# Chrome Extenstion For Detecting Phishing Websites

This lightweight Chrome plugin is designed to detect phishing websites and alert users accordingly. Built with a strong focus on privacy, it ensures that no browsing data is collected for classification. The classification process occurs on the client side, with a one-time download of the classifier model, ensuring a seamless and secure browsing experience.

**Dataset:** [UCI Repository](https://archive.ics.uci.edu/ml/datasets/phishing+websites)  
**Technique:** Random Forest Classifier

## Requirements
```
Python3.7
sklearn==0.19.2
numpy==1.15.0
liac-arff==2.2.2
```

## Documentation
* [Wiki - Complete reference](https://github.com/navyasweet/Chrome-Extension-For-Detecting-Phishing-Websites.wiki.git)
* [Prepare the dataset](backend/dataset/)
* [Train and Export the model](backend/classifier/)
* [Install plugin](frontend)

## Screenshot
<img src="https://github.com/navyasweet/Chrome-Extension-For-Detecting-Phishing-Websites/blob/001a4355afb9f538a39f3d2ed39736f6504694ca/artifacts/pluginUI.png" alt="UI" height="400" width="650"></img>

**F1 score:** 0.905

Links to few phishing sites: [PDF](artifacts/url_list.pdf)

### References
[Intelligent phishing website detection using random forest classifier](https://ieeexplore.ieee.org/abstract/document/8252051/)
