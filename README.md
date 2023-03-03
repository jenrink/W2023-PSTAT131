# Machine Learning 131 : Files/Homework for Cumulative Final Project

I want to analyze Pro-Tennis matches so that I can figure out what types of serves and shots are most effective at winning a point.
  
I am interested in predicting the outcomes for Serves and Rallies (**isAce**, **isRallyWinner**). The main questions I am interested in answering are:    
  
* Does the server have a better chance at winning the point regardless of direction, faults/second serves taken, or speed of their serve?  
* Does the first player to hit a volley in a rally have a better chance at winning the point in general?  
* If the rally is longer than 5 back-and-forth shots, is the receiver more like to win the point?  
* What type of shot is most often considered a winner?
  
My Response variable is **isAce** and/or **isRallyWinner**. They are boolean (TRUE or FALSE) variables that indicate if a serve is an Ace and if the player serving is the rally winner.  

My questions will be best answered with a classification approach.  

I think the most usefull predictors will be **1st** and **2nd** alongside some other descriptive variables like serve speed. **1st** and **2nd** describe the shots hit in the rally and which type of shot wins the point.
