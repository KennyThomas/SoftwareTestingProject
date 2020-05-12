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
   





## 4.3 Performance and Stress Testing 
### Definition





### Participants






### Methodology

































   
