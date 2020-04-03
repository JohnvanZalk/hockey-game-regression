# hockey-game-regression

The Jupyter Notebook in this respository contains an analysis of factors contributing to game outcomes in the National Hockey League.

The statistical test used for this analysis is a multiple logistic regression because game outcomes are binary (win or loss) and there are several explanatory variables.

Some explanotry variables include:
* **FO%:** A face-off is the method used to begin and restart play. FO% is the percentage that a team wins the face-off.
* **BS:** Blocked shots
* **PP%:** If one team incurs a penalty, the other team get's a power-play (more players on ice). PP% is that percentage that a team scores on their power-play.

## Future Development
The model developed from this analysis is not currently being used to predict games due to the absence of an API with reliable documentation. Rather than try to retrieve data from an API, a future approach could involve scraping data from the NHL's website.
