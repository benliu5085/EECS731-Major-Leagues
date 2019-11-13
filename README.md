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

To study the factors affecting spi, first I use linear regression, SVM and NN to find the relation of off, def and league, to the spi of the club, it turns out that the spi of the club is irrelevent to league. Then I use the linear regression to learn the relation of off and def, to spi of national team. The result verified my observation.
