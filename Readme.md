# Back-order Prediction

Backorders are unavoidable, but by anticipating which things will be backordered,
planning can be streamlined at several levels, preventing unexpected strain on production, 
logistics, and transportation. ERP systems generate a lot of data (mainly structured) 
and also contain a lot of historical data; if this data can be properly utilized,
a predictive model to forecast backorders and plan accordingly can be constructed. 
Based on past data from inventories, supply chain, and sales, classify the products 
as going into backorder (Yes or No). A hypothetical manufacturer has a data set that
identifies whether or not a backorder has occurred. The challenge is to accurately
predict future backorder risk using predictive analytics and machine learning and 
then to identify the optimal strategy for inventorying products with high backorder risk.

## Table Content ✏️

 - Demo
 - Overview
 - Dataset
 - Installation
 - Deployment
 - Documentation
 - Directory Tree
 - Technology Used
 - Bug/Feature Request
 - Future scope of project
 
  





## Demo ✔️
Heroku:- https://dashboard.heroku.com/apps/back-order-pred


AWS- Elastic Beanstalk:- 

![elastic beanstalk](https://i.imgur.com/VRg18nK.gif)

  
## Overview 📜

This is a Flask web app which predicts the count of the bikes available based on the user's input in which there are several 
categories to fill in like the national inventory,lead time,sales month,pieces past due,perfect 6 month average and other things by which
model will predict whether that particular order will be returned or not for that particular input and conditions.Data which user enters will 
be stored in DynamoDB for the future use,logging is done at every step.


## DataSet 📊

To Know more about data and its characterstics you can download dataset form https://github.com/rodrigosantis1/backorder_prediction/blob/master/dataset.rar

  
## Installation 🗄️

The Code is written in Python 3.8 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). 
If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. 
To install the required packages and libraries, run this command in the project directory after 
[cloning](https://github.com/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement
### Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.
[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on 
[Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

### AWS(Amazon Web Services)
Login or signup with free tier in order to create virtual amchine(Elastic beanstack) for free. 
Note:- In free trier virtual Machine will only give free service for 720hr almost a month after that you will be charged , so use carefully. 
I usally stop instance when it is not needed to avoid extra charge. so it may happen that deployment link for AWS might not work  
![](https://i.imgur.com/XMFtzYH.png)[![](https://i.imgur.com/cGvkZxw.png)](https://heroku.com)

Our next step would be to follow the instruction given on 
[AWS Elastic Beanstack](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-flask.html) to deploy a web app.


## DataBase

![App Screenshot](https://i.imgur.com/zYihnRR.jpg)
![App Screenshot](https://i.imgur.com/yWwLAWp.png)

## Directory Tree

```javascript
├── static 
│   |   |
│   |   ├── css
│   |   ├── forms
│   |   ├── img
│   |   ├── js
│   |   ├── vendor
├── template
│   ├── index.html
│   ├── result.html
│   ├── 500.html
│   ├── 404_error.html
|   ├── 405_error.html
│   ├── error.html
├── Procfile
|
├── README.md
├── application.py
├── RF_Back_order.pkl
├── requirements.txt


```



  
## Documentation

[Architecture](https://drive.google.com/file/d/1sp_UYlxHm4Y7CjXxX3dMEm6_S1iZLqOU/view)

[Low Level Documentation](https://drive.google.com/file/d/1U3bhMU0iuImoyYHYrDKhZgDD-jZjIDPe/view)

[High Level Documentation](https://drive.google.com/file/d/1toWy7ZtylAZRn3oogrnbs-5XjZ0faNoS/view)

[Wired Framed Diagram](https://drive.google.com/file/d/1yeH9xKe_6FZkwrdGG0fdJqesWSNoyrD4/view)

[DPR(Detail Documentation Report)](https://drive.google.com/file/d/174CdKcn_BNPgRClGy2V5FjrvcKF0hIAS/view)


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) 
[<img target="_blank" src="https://blog.vizuri.com/hs-fs/hub/342946/file-2231290146-png/Images/Logos/Partners/Amazon_Web_Services/aws_s3_logo.png" width=280>]()
[<img target="_blank" src="https://i.imgur.com/3mZlVf8.jpg" width=280>]()
[<img target="_blank" src="https://seeklogo.com/images/B/bootstrap-logo-69A1CCC10B-seeklogo.com.png" width=200>](https://getbootstrap.com/) 



## Bug/Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), 
kindly open an [issue](https://github.com/) here by including your search query and the expected result


## Contributors <img src="https://raw.githubusercontent.com/TheDudeThatCode/TheDudeThatCode/master/Assets/Developer.gif" width=35 height=25>


- [Priyam Trivedi](https://github.com/Priyam-Trivedi)
- [Sravanthi Shoroff](https://github.com/sravanthishoroff)
- [Prateek singh](https://github.com/Prat1997)

## Future Scope

* Use Deeplearning Algorithms
* Optimize Flask application.py
* Front-End 




