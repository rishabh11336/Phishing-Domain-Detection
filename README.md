# Phishing Domain Detection Project

## Project Overview
This project focuses on developing a machine learning solution for detecting phishing domains. Phishing, a prevalent form of cyber fraud, involves attackers impersonating reputable entities to obtain sensitive information. The primary goal is to predict whether domains are real or malicious, thereby enhancing cybersecurity measures.

### Problem Statement
The challenge lies in differentiating between legitimate and malicious domains. Traditional machine learning tasks such as data exploration, cleaning, feature engineering, model building, and testing are employed to address this issue.

### Dataset
- **Paper Link:** [Phishing Websites Dataset](https://www.sciencedirect.com/science/article/pii/S2352340920313202)
- **Dataset Link:** [Mendeley Dataset](https://data.mendeley.com/datasets/72ptz43s9v/1)

### Approach
The project employs various machine learning algorithms tailored to the problem at hand. Feature engineering includes URL-based, domain-based, page-based, and content-based features later decided to used Random Forest.

### Technologies Used
- [**Machine Learning Technology scikt-learn**](https://scikit-learn.org/stable/index.html)
- [**Python**](https://www.python.org/)

### Database
- Cassandra database is utilized for this project saving every transaction as history and saving datbase for safe and phising url.

### Cloud Platform
- Cloud platform Azure is used for hosting the solution.

### Logging
- Python logging library is employed for logging every action performed by the code. finally logs are being saved in GitHub Repository [Logging](https://github.com/rishabh11336/Log-Phishing-Detection.git).

### Wireframe
- [WireFrame](https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/WireFrame.pdf)

### Solution Design
![Architecture Diagram](https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/Architecture%20Diagrams.svg)
- Complete solution design strategies [**High-Level Design (HLD)**](https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/High-Level%20Design%20(HLD).pdf) and [**Low-Level Design (LLD)**](https://www.example.com) documents.

<div align=center>
<a href="#"><img src="https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/README/azure_logo.png" title="Azure" alt="Azure" width="100"/></a>
<a href="#"><img src="https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/README/Python_logo.png" title="Python" alt="Python" width="170"/></a>
&ensp;<a href="#"><img src="https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/README/Flask_restful_logo.png" title="Flask" alt="Flask" width="350"/></a><br>
<a href="#"><img src="https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/README/sklearn_logo.png" title="sklearn" alt="sklearn" width="350"/></a>
<a href="#"><img src="https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection/blob/main/README/Cassandra_logo.png" title="Cassandra" alt="Cassandra" width="180"/></a>
</div>

### To Build this project
```
git clone https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection.git
```
#### create virtual enviroment
```
python -m venv venv
```
#### Learn more about virtual enviroment refer to
```
https://medium.com/@asusrishabh/requirements-txt-in-python-947b0b43bbe6
```
#### use requirement.txt in Phishing Domain Detection App to install compatible packages
```
pip install -r requirement.txt
```
```
python app.py
```

For more details, refer to the [GitHub repository](https://github.com/rishabh11336/iNeuron-Internship-Phishing-Domain-Detection) for the project.
