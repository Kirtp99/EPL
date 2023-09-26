# EPL
English Premier League Data Analysis

I use jupyter notebook / python

Questions to be investigated:
- Is home ground advantage a thing?
- Which teams have the most potent home ground advantage?
- Does home ground referee bias exist?

Summary

- Acquire the data using web scrapping and append it to a CSV file for further investigation.
- Look at the home ground edge. Overall home/away win rates, win rates of the big 6 teams. Calculating the home game advantage and see which team has the best.
- Looking at referee bias by extracting the top 20 referees and looking at their home and away win records along with fouls, yellow and red cards awarded to both teams (on average).
- Using Variable correlation to reaffirm or disprove what we may have already found.


Conclusion

- Is home ground advantage a thing?
We saw on average a home team has a 0.456676, 0.245760 to draw and 0.297564 to lose. Since the 06/07 season home teams have always had a higher chance to win at home disregarding the covid season where the odd were similar for win/loss.
    
- Which teams have the strongest home ground advantage?
Nott'm Forest and Charlton had the strongest home game advantage. 

- Does home ground referee bias exist?
Referee bias does exist to some level in the game. They are more likely to be more lenient towards the home team awarding more fouls and giving more yellow and red cards to the away side. This maybe due to the pressure felt by the outnumbering home team fans in the stadiums.
 (look at EPL Data Acquisition and Analysis.ipynb to see graphs, tables and heatmaps) 

Improvement that can be made :
- VAR is fairly new but looking at VAR decision data would help identify referee bias.
- Seeing how top players from certain teams perform at home and away to see the home ground effect more clearly.
- Potentially machine learning to predict the outcome of games along with fouls/yellow/red cards given.
  
