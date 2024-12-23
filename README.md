**Injury Zone Prediction Using Muscle Imbalances**

This project was part of the Orange Hoops Challenge organised by the Syracuse Orange Men's Baksetball Team in conjunction with the School of Information Studies, Syracuse University. Data for the 2023-2024 season regarding muscle imbalance for each player, injury history of each player and training session metrics was provided and our task was to come up with an actionable way to predict and manage injuries. 
Our end goal was to find ranges for each muscle imbalance (Quadricep, Hamstring, Groin and Calf) in which the chace of injury was the lowest (safe zones). These safe zones were calulated based on the data gathered from player training sessions. This data consisted of metrics such as distance covered, maximum and average speed, maximum and average heart rate, anaerobic activity, number of steps, maximum jump load etc. To analyse the impact of each muscle imbalance on its own and in different combinations, we conducted correlation analysis. Once the relationships were found, we fit a semi-supervised model in the form of a BaggingRegressor from the sci-kit earn library. This output safe zones for each muscle imbalance. We verified results by plotting each imbalance of all players on different plots, and saw that all players who were injured lied outside our safe zone. In addition, all players who wer not injured lied inside our safe zone.

Contrbutors to this project were:
* Saketh Kilaru [GitHub Link](https://github.com/sakethkilaru)
* Luis Riviere
* Akshaj Salvi
* Michael D'Amore
