# Assignment Title

## (1) Problem Statement
The problem is to perform sentiment analysis on tweets related to the CDM tournament in Call of Duty Mobile. The goal is to classify tweets into positive, neutral, and negative sentiments using machine learning techniques.

## (2) Objective
- To analyze user opinions about the CDM tournament
- To classify tweets into positive, neutral, and negative categories
- To compare performance of different machine learning models

## (3) Dataset
- Source: Manually created tweets based on CDM tournament and CODM gameplay
- Features:
  - tweet (text data)
  - label (positive / neutral / negative)
- Size: 100 tweets (80 training, 20 testing)

## (4) Methodology
1. Data Preprocessing  
   - Text cleaning and formatting  
   - Conversion to lowercase  

2. EDA  
   - Basic understanding of sentiment distribution  

3. Model Building  
   - Naive Bayes  
   - Logistic Regression  
   - Support Vector Machine (SVM)  

4. Evaluation  
   - Precision  
   - Recall  

## (5) Results
- Naive Bayes → Precision: 0.48, Recall: 0.58  
- Logistic Regression → Precision: 0.50, Recall: 0.61  
- SVM → Precision: 0.47, Recall: 0.51  

- Logistic Regression performed best among all models.

## (6) How to Run
```bash
pip install -r requirements.txt
python main.py
```
## (7) Conclusion

The project successfully demonstrates sentiment analysis using machine learning techniques. Logistic Regression performed better than Naive Bayes and SVM due to better generalization on the dataset.

##(8) Student's details
Name: Abdullah Shaikh
Roll No: 57
Class: TE (AI & DS)
