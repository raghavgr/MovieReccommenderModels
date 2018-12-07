# MovieReccommenderModels

Implementation of models was inspired from the resources provided in this course:
https://www.udemy.com/building-recommender-systems-with-machine-learning-and-ai/ 

Code distribution:
- EDA, Content-Recommendation: Sai
- User-User CF, Item-item CF, Results: Keng, Andreas
- Matrix SVD, Debugging, Refactoring: Yifei, Andreas

Instructions:
- Install the required libraries listed in pip3req.txt using pip3
- Run KNNRecs.py for Content Recommendation, SVD results
- Run CF.py for collaborative filtering algorithms
- change  testSubject from User 75 to other users at line 212 of evaluator.py
    -`    def SampleTopNRecs(self, ml, testSubject=75, k=10):`
