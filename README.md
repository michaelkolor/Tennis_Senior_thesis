# Tennis_Senior_thesis
Exploration and Work on my senior undergraduate thesis.  Exploring questions in the field of tennis


Notes for 10/13/20 Meeting

using a glicko-based model as baseline for tennis.  Have a pre-match baseline model to predict winner of match. 

Then, have at each point, the likelihood of a player winning the match update each time after a point.  This may be too high dimensional, consider pruning features.  

This could be inferential: 

  So: goal is two things a) try and beat "first model" try and beat betting odds 

I want to beat the notion that points are i.i.d.
See link:
https://www.jstor.org/stable/2670288?seq=1

Find points that have biggest change (besides last ones), find features that have biggest change

POINTS DEPENDENCE SUMMARY:
https://www.jstor.org/stable/2670288?seq=1

good tennis research paper link:
https://www.tandfonline.com/doi/abs/10.1198/016214501753168217

GOOD SUMMARY OF PREVIOUS RESEARCH:
http://gamesetmap.com/?page_id=2

RACQUET SPORTS PATTERNS
https://www.researchgate.net/publication/220801985_Tactical_Analysis_Modeling_through_Data_Mining_-_Pattern_Discovery_in_Racket_Sports
geospatial
THEMES in OTHER WORK: Bayesian, betting odds, independence, likelihood of winning serve and return, real-time

this project for betting odds:
https://databuckets.org/databucket/real-time-point-by-point-tennis-forecast

sources: 
https://rss.onlinelibrary.wiley.com/doi/full/10.1111/rssa.12464

markov:
https://rss.onlinelibrary.wiley.com/doi/pdf/10.1111/j.1740-9713.2015.00799.x

ibm performing poorly:
  on.wsj.com/1E21mkq 
"Despite Advanced Stats, Tennis Has A Data Problem"

 
example repo:
basically what i want to do
https://github.com/haroldmli/04-Tennis-Point-by-Point-Project


University of Swinburne (PhD thesis?)
not really regression-based
https://researchbank.swinburne.edu.au/file/b693026c-94cf-46d5-9180-158972955b53/1/geoff_pollard_thesis.pdf


many models assume iid, really try and challenge the notion:
http://nessis.org/nessis17/Ingram.pdf

Kovalchik: the GOAT of Models
http://nessis.org/nessis17/Ingram.pdf


