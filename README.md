# EECS731-Major-Leagues
This is the project of EECS 731 Data science.

(1) Content

|-READ.ME 
|-regression.ipynb 
|-data 
| |-spi_global_rankings_intl.csv
| |-spi_global_rankings.csv

(2) Ideas 
I am interested in spi of national team and the spi of first ranking league of some countries. So first I plot the spi of each club of the league in the country, choose the best league if more than one league exists, because we naturally want the best player in the national team, who are more likely to serve in the best league. Then I showed the spi of the national team. 
The result is interesting, because Brazilian league is okay but the Brazilian national team is one of the best, and we know the fact that most of the Brazilian players are serving European club.

To study the factors affecting spi, I used linear regression, SVM and neural networks. My result showcases that linear regression is the easiest one to implement but surprisingly performs best. And NN has too many hyperparameters to tune.
