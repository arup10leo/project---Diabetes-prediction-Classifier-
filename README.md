# project-Diabetes-prediction_Classifier(SVM)

In this source code, one can predict whether the next person has diabetes or not on the basis of following parameters:
Pregnancies<br>	
Glucose	<br>
BloodPressure	<br>	
SkinThickness	<br>	
Insulin	<br>	
BMI	<br>	
Diabetes Pedigree Function<br>		
Age	<br>	
Outcome<br>	
The model first convert the input data in Numpy array then reshaping will be done as we are predicting for one instance then it will be transformed to standarized data using SKlearn's standard scaler then SVM classifier will do the trick i.e., prediction.
If 1 comes in form of a list then the person has(will have) diabetes if 0 comes no need to worry.
