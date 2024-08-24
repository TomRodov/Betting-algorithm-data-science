# Betting-algorithm-data-science


This repository contains a data science project focused on developing a predictive algorithm for FIFA World Cup matches. The project utilizes statistical techniques such as the Poisson distribution and the Elo ranking system to estimate the outcomes of soccer matches, particularly for betting purposes.

Project Structure
DATA2010_Final_Report.pdf: The main research paper that outlines the methodology and findings of the project. This includes an analysis of historical FIFA World Cup data, testing the distribution of goals scored, and applying the Elo ranking system to improve predictions.

Data Processing: Scripts to clean and process World Cup data. Includes adjustments for teams that have changed over time (e.g., Germany before and after unification, Czechoslovakia, and the split into the Czech Republic and Slovakia).

Elo Ranking Algorithm: The Elo ranking system was implemented to rank teams based on match outcomes. Elo scores are continuously updated based on new match results.

Predictive Modeling:

Poisson Distribution: Applied to predict the number of goals scored in a match.
Kolmogorov-Smirnov Test: Used to confirm the distribution of data and guide the selection of statistical methods.
Maximum Likelihood Estimation (MLE): Calibrates the logistic function used in the Elo ranking system.
Methodology
Data Collection: Historical FIFA World Cup data was compiled and filtered to focus on the most relevant variables for match prediction, such as goals scored and match outcomes.

Poisson Distribution: This distribution was used to model the number of goals scored, as goals in soccer are relatively rare events within a fixed interval.

Elo Ranking System: Elo rankings were applied to determine team strengths and adjust match predictions. The model accounts for differences in team strengths when predicting match outcomes.

Logistic Function & MLE: The logistic function helps convert differences in Elo rankings into probability values. The MLE process was used to optimize parameters for the best predictive performance.

Results
Our findings suggest that the combination of the Poisson distribution and Elo rankings offers a more accurate prediction model for FIFA matches, enhancing betting strategies. Future work will involve refining the model further, incorporating more variables, and expanding the dataset.