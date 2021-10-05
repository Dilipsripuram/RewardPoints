# RewardPoints
 Spring Boot app that will return total reward points of a customer and show the results month by month
 
 
# Technical Details
---------------------------------------------------------------------------------------------------------------
- Spring Boot
- Maven
- H2
--------------------------------------------------------------------------------------------------------------

This will calculate the reward points and create dataset information in H2 DB.

- http://localhost:8080/createData

![This is an image](https://github.com/Dilipsripuram/RewardPoints/blob/master/git_images/img1.png)

-------------------------------------------------------------------------------------------------------------

Get the customer total earning points and monthly wise total earning points

- http://localhost:8080/getRewardPoints?customerName=customer1

![This is an image](https://github.com/Dilipsripuram/RewardPoints/blob/master/git_images/img2.png)

-------------------------------------------------------------------------------------------------------------

Get the customer total earning points and monthly wise total earning points

- http://localhost:8080/getRewardPoints?customerName=customer2

![This is an image](https://github.com/Dilipsripuram/RewardPoints/blob/master/git_images/img3.png)
-------------------------------------------------------------------------------------------------------------

Testing:
- There is a test file located at test/java/com/rewards
