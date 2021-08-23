# project-Diabetes-prediction_Classifier

In this source code, one can predict whether the next person has diabetes or not on the basis of following parameters:
Pregnancies	
Glucose	
BloodPressure	
SkinThickness	
Insulin	
BMI	
Diabetes Pedigree Function	
Age	
Outcome
The model first convert the input data in Numpy array then reshaping will be done as we are predicting for one instance then it will be transformed to standarized data using SKlearn's standard scaler then SVM classifier will do the trick i.e., prediction.
If 1 comes in form of a list then the person has(will have) diabetes if 0 comes no need to worry.
