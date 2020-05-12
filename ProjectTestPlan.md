# The Pixel Wizard
<br>

## Prepared by: Thomas Kenny
### 09/05/2020
<br>


# Table of Contents
## 1.0 Introduction
<br>

## 2.0 Objectives and Tasks 
### 2.1 Objectives 
### 2.2 Tasks
<br>

## 3.0 Scope
<br>

## 4.0 Testing Strategy
### 4.1 Unit Testing
### 4.2 System and Integration Testing 
### 4.3 Performance and Stress Testing 
### 4.4 User Acceptance Testing
### 4.5 Batch Testing 
### 4.6 Automated Regression Testing 
### 4.7 Beta Testing
<br>

## 5.0 Test Schedule
<br>

## 6.0 Control Procedures
<br>

## 7.0 Features to be Tested
<br>

## 8.0 Features Not to Be Tested 
<br>

## 9.0 Resources/Roles & Responsibilities
<br>

## 10.0 Schedules 
<br>

## 11.0 Risks/Assumptions
<br>

## 12.0 Tools
<br>

# 1.0 Introduction
The game that is under testing is called The Pixel Wizard. This game will be a 2D side-scrolling platformer that will be developed for PC and Mobile users. The game is will see the player navigate progressively difficult levels with a wizard type character that uses magic as its form of attack.

 ## Functions
 
 ### In Game
* There will have atleast three levels.
* Each level will have several enemies.
* Also a boss that the player will have to defeat to progress. 
* Each level will also have pickups that the player can collect to replenish the players's health.
* The game will use generic controls, these controls include using the mouse left click to attack, arrow keys and ASWD to move or     onscreen arrows for mobile users. 
* The user will be able to pause the game at any moment using the space button or for mobile players a button.
* From the pause menu the player can save the game , exit the game , restart the game or go to settings.
* Player can adjust the sound from the settings.

### Menu
* From  the main menu the player can choose options such as "Play Game" , "Settings" , "Load Game" , "Delete Game" and "Exit Game".
* If the player presses "Play Game" they will be brought to the first level.
* If the save game function is implemented, the player can load into the the last save point by pressing "Load Game".
* Player can change sound level for the game in the settings.
<br>

# 2.0 OBJECTIVES AND TASKS

## 2.1 Objectives
Each task will be handled by teams made up of three, these tasks will be outlined in section 2.2.<br> Each team will be responsible for there own task.<br> Due to Covid-19 meetings will be held on a zoom call on Thursdays at 1:00 pm.<br> We will also be using Github to track the progress of our testing. Each member will be added as a contributor. <br> We have agreed to a service-level agreement to deliver this test plan to Game Development International Ltd by the 14th of May 2020.

## 2.2 Tasks
###  Tasks include 
   * Testing  - includes unit testing , system and integration testing , performance and stress testing.
   * Post-Testing - includes user Acceptance Testing.
   * Problem reporting - includes incident reports and summary reports.
  <br>
 
# 3.0 Scope

## General
We will be mainly focusing on certain aspects of the game to test.<br>
These include.. 

### In Game
* Player spawn is correct not glitching.
* Player movement is working correctly.
* Player's attack is working and can defeat the enemies.
* Enemies are not to overpowered on levels so the player can progress. 
* Enemies's are spawning in correct locations.
* Enemies are getting harder to defeat when the player progresses.
* Health pickups increase the players health. 
* Player must stay inbound of the screen.
* Game is easy to understand and learn if a new player attempts the game.
* Hit box for player and enemy are correct , only takes damage if they enemy/player s directly hit.
* Pause menu working with player being allowed to change settings, exit level , restart the game and save game.

### Menu
* Once the player presses "Play Game" they are brought to the first level.
* Player can change the sound via the settings.
* If they wish to load the game it lets them choose which save game they would like to play.
* Option to delete game, once button is pressed the chosen game is deleted. 
* Exit game button closes the game.

## Tactics
Since we have four teams, two teams will take in game testing and two teams will take menu testing. We will also use User Acceptance Testing. Each team will have three to four days to test with meetings everyday between teams. The overall meeting will be on Thursdays at 1:00 pm where we will all discuss progress made. After every feature is tested we will write a report on what worked/didn't work. 

# 4.0 TESTING STRATEGY 
We will ensure that this product is tested thoroughly. Since we have the product split into two parts testing can be finished more smoothly.<br>
With 4 teams taking on in game testing and menu testing we can assure that this product is adequately tested.<br>
User acceptance testing will be a big factor in this product. We will need to make sure this product is easy for a new player to pick up and play straight away. We will perform this test 3/4 times to make sure we have multiple sets of data on what could improve.
We will be using the following testing strategies to ensure that we have checked the product works without a chance of fault.
* Unit Testing
* System and Integration Testing 
* Performance and Stress Testing 
* User Acceptance Testing
* Batch Testing 
* Automated Regression Testing 
* Beta Testing

## 4.1 Unit Testing 
### Definition
Testing will be started with unit testing. 
We will first look at the requirements we are given and break these up into smaller components to test.<br> Rather then testing big parts at once if we focus on smaller components it will make life easier. By doing unit testing we can identify early the components that are working and not working. If we catch any bugs early it will make the testing phase run smoother and cheaper.<br>


### Participants
Developers <br>
John <br>
Mary <br>
Thomas <br>


### Methodology
We will start of testing the navigation of the game.<br> We will see if the player can navigate between pages for example, can the player go from the menu to settings or from menu to the game. Once this is finished it will make testing the other parts much easier.<br> After this we will look at the in game features. We want to make sure that the assests have the correct z coordinates. This needs to be checked to make sure no parts are overlapping.<br> Also we need to test if the player can shoot, once this is complete then hit detection will be the focus. We can use log statements to check if the hit detection is working. Once we have the player shooting we can then test the enemies. We will need to make sure that the enemies are firing with a break inbetween. This needs to be done to make sure the enemies are not shooting constantly to give the player a fair chance. We can also test to make sure the health system is working and displaying. This can be only be done if the hit detection is working first. The health pickups need to be tested also. The pickups need to spawned after a certain period of time. We also need to test if the pause menu and see if it works if the player presses the pause button.Thomas will write the test scripts for unit testing.





## 4.2 System and Integration Testing
### Definition
System and Integration Testing is vital for this game. We need to make sure that all the separate components we have tested are working together. With this testing we can see the behavior between components, if this is done correclty we can view what components need to be tuned down or turned up. 


### Participants
Testers <br>
Joe <br>
Sarah <br>
Jack <br> 

### Methodology
We wll conduct this testing by seeing how these components behave with eachother. 
* We will first look at can the player go from the menu straight into the game and the game starts.
* If this is working we can then see if the combat between the player and enemy is working. 
* If the player gets hit a heart will disappear. 
* If the enemy gets hit the enemy will disappear. 
* If the player picks up a pickup then the health will go up by one.
* We need to see if the pause menu works correctly with the in game. If the navigation is working correclty the menu should be working. 
* Also we need to make sure when the player loads a save game they are brought to the right game.





## 4.3 Performance and Stress Testing 
### Definition
This is testing to be carried out to check the system's performance under varying loads.<br> Stress testing is carried out by testing the behavior of the system under the sudden increase load. This needs to be carried out to make sure the game wont crash or get glitches if the system is stressed. We also need to check the point at which the game will crash to make sure it does not happen when it is released.





### Participants
Performance Test Engineer





### Methodology
We will use an outside Performance Test Engineer to conduct this testing phase to make sure it is tested without inside bias towards the game. This phase needs to be carried to make sure that game will not crash suddenly under stress. This needs to be done to make sure enemies spawning and shooting does not slow down. For the more difficult levels this testing is required to make sure when multiple enemies are shooting at the player the game will still perform perfectly. If we find that the game slows down we can adjust the fire rate or the amount of enemies that are spawned.



## 4.4 User Acceptance Testing 
### Definition
User Acceptance Testing is needed to make sure that the system is ready for operational use. We also need this phase of testing to make sure the game has met all the requiremnts that were set out at the start.




### Participants
Users <br>
Mary Brown <br>
Thomas Kenny 




### Methodology
We have chosen two userrs to test the game. We did this to make sure we have different feedback. This testing will be conducted by letting them play the game without prior knowledge to the game. This is required to make sure the game is easy to understand and play. We can also make sure we have met all requirements that were set out at the start. From the feedback if the controls or layout of the game is hard to understand we will be able to tweak the game so it will be more suitable when it is released.







## 4.5 Batch Testing
### Definition
This phase of testing is done to test multiple parts to make sure they all work. We execute the scripts one at a time with the other scripts waiting till the previous one is complete. These tests are then shown on a graph so we can view the results.




### Participants
Test engineers



### Methodology

This testing is required to show the how accurate the game is by running it multiple times. If the game repeatedly fails at a certain location we can find the bug and fix it. This testing it make sure the game can run multiple times without having to worry about it crashing.  





## 4.6 Automated Regression Testing 
### Definition
This testing is performed to make sure that recent changes or bug fixes do not break or affect existing features that work.




### Participants

software quality assurance team




### Methodology
After user acceptance testing and stress testing there will have been changes added in to the game. These changes might have been small or they could have been a major change. This phase of testing is required to make sure that these changes have not affected working features. This testing is carried out by the software quality assurance team.


## 4.7 Beta Testing 

### Definition

This is the final stage of testing. We will distribute the game to individual users outside of the company for a period of time. 



### Participants
Users

### Methodology
This is one of the important phases of testing. If the beta is successful we can release the game for use. During the game we can monitor the feedback that we are given. The feedback can give us an insight into small tweaks we can fix with the game.


# 5.0 TEST SCHEDULE
  Times are estimated
  <br>
* Planning - 3 days
* Unit Testing - 2 days
* meeting - 1 day
* System and Integration Testing - 3 days
* meeting - 1 day
* Performance and Stress Testing - 2 days
* User Acceptance Testing - 1 day 
* meeting - 1 day
* Batch Testing - 2 days
* Automated Regression Testing - 1 day 
* meeting - 1 day
* Beta Testing - 4 days
* meeting - 1 day

### Resouces
* Facilities - 30 days 
* Tools - 30 days
* staff - 30 days 


#  6.0 CONTROL PROCEDURES

## Problem Reporting 
If a problem occurs in the testing phase of the game we can log these incidents. This is done so we can keep a record of what the incident was, what the problem caused and what was done to fix it. This is helpfull to keep logs of these problems incase the same problem has occures it will be easy to fix as we have a log of the previous incident.

## Change Requests 
If a change needs to happen it first has to be signed of by the Test Leader. The modification has to pass certain criteria to be added to the game. For example what the change is, how big is the change, will it affect another feature and is it a required change. 
If we the change does affect existing code it will go through Automated Regression Testing to fix the issue.


# 7.0 FEATURES TO BE TESTED

   
