
## The Cignetti and the Noise: 

### Introduction
 Using data  on 103 recent P4 college football hires, we built a statistical model for predicting a coach’s success at their new school.   For each hire, we collected data about their background and experiences, the previous success as a head coach or coordinator and their success since hiring.  Over 50 variables on these factors were recorded though we used 29 of these in building our predictive model.     
 
### Methods
Our measure of success is based upon Bill Connelly’s SP+ team ratings relative to the performance on the same metric of the school in the 15 year prior to their selection as head coach.  Using a cross-validated regularized linear regression, we obtain a predictive model for coaching success.

### Results
Among the important factors for predicting a successful hire are having been a previous college head coach, leaving a job as an Offensive Coordinator, age and quality of the hiring school's team in the previous 15 years. While we do find these factors are important for the prediction of a successful coaching hire, the trends here are weak.  With 66\% accuracy, the model does identify coaching hires that will outperform team performance in the 15 years before the hire.

### Conclusion
 However, no combination of these factors leads to high predictability of identifying a successful coaching hire. 
