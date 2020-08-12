# Boat-Race-Prediction
## Abstract
Predict No.1 boat racer in the races in Suminoe, in Japan by Using deep learning framework "TensorFlow.Keras".
<br><br>

## Explain about Boat-Race dataset
<img width="708" alt="スクリーンショット 2020-08-12 10 39 50" src="https://user-images.githubusercontent.com/58195776/89965724-69634d80-dc88-11ea-8212-30b383f1d452.png">

* Place: racer position. The range is from 1 to 6. "1" is the most advantageous and "6" is the most unfavorable. 
* Age: racer age
* Weight: racer weight
* Rank: there are "A1, A2, B1, B2". "A1" is the best rank (relatively strong), and "B2" is the worst rank.
* A_1st: national win rate.
* A_2nd: 1st or 2nd win rate in nationwide.
* B_1st: local win rate.
* B_2nd: 1st or 2nd win rate in local.
* Motor_No:　the motor that racer using.
* Motor_2nd: win rate by using the motor.
* Bote_No: the bote that racer using.
* Bote_2nd: win rate by racer using.
* y: answer label. winner's label is "1", otherwise "0".
