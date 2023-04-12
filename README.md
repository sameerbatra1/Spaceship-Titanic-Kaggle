# Spaceship-Titanic-Kaggle

https://www.kaggle.com/competitions/spaceship-titanic

## Intro
This is a kaggle competition where you are in year 2912, where your data science skills are needed to solve a cosmic mystery. We've received a transmission from four lightyears away and things aren't looking good.

The Spaceship Titanic was an interstellar passenger liner launched a month ago. With almost 13,000 passengers on board, the vessel set out on its maiden voyage transporting emigrants from our solar system to three newly habitable exoplanets orbiting nearby stars.

While rounding Alpha Centauri en route to its first destination—the torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension!

To help rescue crews and retrieve the lost passengers, you are challenged to predict which passengers were transported by the anomaly using records recovered from the spaceship’s damaged computer system.

## Data
To work on this project, we were given 3 data files: train.csv, test.csv, and sample_submission.csv.
* train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data:
  * `PassengerId` - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.
  * `HomePlanet` - The planet the passenger departed from, typically their planet of permanent residence.
  * `CryoSleep` - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.
  * `Cabin` - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.
  * `Destination` - The planet the passenger will be debarking to.
  * `Age` - The age of the passenger.
  * `VIP` - Whether the passenger has paid for special VIP service during the voyage.
  * `RoomService`, `FoodCourt`, `ShoppingMall`, `Spa`, `VRDeck` - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.
  * `Name` - The first and last names of the passenger.
  * `Transported` - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
* test.csv - Personal records for the remaining one-third (~4300) of the passengers, to be used as test data. Your task is to predict the value of `Transported` for the passengers in this set. 
* sample_submission.csv - A submission file in the correct format.
  * `PassengerId` - Id for each passenger in the test set.
  * `Transported` - The target. For each passenger, predict either `True` or `False`.

https://www.kaggle.com/competitions/spaceship-titanic/data

## Evaluation
Submissions are evaluated based on their classification accuracy, the percentage of predicted labels that are correct.

https://www.kaggle.com/competitions/spaceship-titanic/overview/evaluation

## Result
As of 12/04/2023, a total of 2,657 competitors have participated in this competition and 17,900 entries are made. On the leaderboard, I stand on 1534 rank with the best score of 0.78512.
![image](https://user-images.githubusercontent.com/83417365/231373037-5396f628-b88e-4869-b037-16bd3d4d02da.png)

https://www.kaggle.com/competitions/spaceship-titanic/leaderboard#
