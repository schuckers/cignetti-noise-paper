Abstracts must contain fewer than 500 words, including title and body.
Abstracts may include up to two tables or figures combined (e.g.  1 figure and 1 table, or 2 tables). 

## Cignetti and The Noise


### **Introduction**
Hiring of a Division I football coach is among the most consequential decisions an Athletic Director and a University can make. Using data on 101 recent P4 college football hires, we built a statistical model for predicting a coach’s success at their new school. For each hire, we collected data about their background and experiences, the previous success as a head coach or coordinator and their success since hiring. Over 50 variables on these factors were recorded though we used 29 of these in building our predictive model.

### **Methods**
We consider two measures of coaching success; each is based upon Bill Connelly’s SP+ team ratings (measured in points above or below an average team) relative to the performance on the same metric of the school in the 15 year prior to their selection as head coach.  The first is the raw difference in SP+ and the second is a normalized version to account for the difficulty of improving a team into the upper tiers of college football.  Using a cross-validated regularized linear regression, we obtain a predictive model for coaching success.

### **Results**
Among the important factors for predicting a successful hire are having been a previous college head coach, leaving a job as an Offensive Coordinator and quality of the hiring school's team in the previous 15 years. Specifically, the model indicates that having prior college head coaching experience or taking a job at a school with a higher quality in the last 15 years produces a negative effect on coaching success. However, the model also finds that leaving an offensive coordinator job has a positive impact on coaching success. In other words, schools with poor performance over the last 15 years should hire an offensive coordinator with no prior head coaching experience. 

  While we do find these factors to be important for the prediction of a successful coaching hire, the trends are weak. With 66% (ZZZ) accuracy, the model identifies coaching hires that will outperform team performance in the 15 years before the hire. The results should be interpreted cautiously as they are likely produced via regression to the mean of the past 15 years at the given school. 
  
  Unsurprisingly, Curt Cignetti's performance as the coach at Indiana is an outlier. Although an outlier is not a trend, his performance is another example of unpredictability in college coaching performance.

### **Conclusion**
No combination of these factors leads to high predictability of identifying a successful coaching hire. The data is noisy and presents mild patterns at best, indicating the many nuances of college football coaching. There are no magic coaching attributes that guarantee future success among the factors we investigated. Hiring a coach is hard; hiring a really successful coach is unlikely at best.

**NOTE about Figures:**

Use Figure 3 with just:
- Previous job as hc
- Previous job as dc
- Side of the ball
- Won Natl. Champ. as HC any level
- Won Conf. Champ. as Coord any level
- Has NFL coaching experience

Use Figure 4:
- Maybe add one more plot (if applicable and there is room).
