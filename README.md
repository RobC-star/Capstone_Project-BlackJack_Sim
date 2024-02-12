Blackjack Simulator
________________________________________
User Guide


Team 4
Robert Carswell
Jordan DeLaGarza
Jose Reyes
Patrick Smith
Samuel Hudgins

 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/a0b2e0a1-01a0-4387-9d6b-eacae78d51e1)


 Image 1: Startup Screen



28 November 2023
Table of Contents
1.0 What is the Blackjack Simulator Game?	2
2.0 Minimum System Requirements	2
3.0 How to Create a User Account	2
4.0 How to Log Into The Game	4
5.0 Delete User Account	5
6.0 Game Play	6
6.1 Bank Balance	6
6.2 Betting	7
6.3  Cards dealt to the Player and Dealer	8
6.3.1 What is a HIT?	8
6.3.2 What is a Stand?	8
6.3.3 What is a Double?	9
6.3.4 What is a Split?	10
6.3.5 What is insurance?	10
6.3.6 What is a Push?	11
6.3.7 How do you Win or Lose?	12
7.0 View Stats	13
8.0 Tutorial	14
9.0 Additional Help	14
























1.0 What is the Blackjack Simulator Game?
The Blackjack Simulator game was created by Dynamic Gaming to educate users who want to learn blackjack in a fun and safe environment. The game is loaded with features that help the user understand the basics of blackjack and how to read the game to achieve the best results in a real-world environment. Many of our users have no intention of using the knowledge gained from our game in the real world. No worries, this game also provides plenty of competition by allowing multiple players to use the application to keep track of individual success and rank each user. This game is Player vs CPU, but after each player logs into the system, their scores are kept locally, allowing each player to be ranked on their local machine.
2.0 Minimum System Requirements
1.	Requires Windows 10.
2.	Java Version 8.
3.0 How to Create a User Account
To create a user account, select the link "Create User Account" on the Login Screen. At this point, the user will be directed to the "Create User Login page”.  Enter the username and password and select Confirm to create a user account.

 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/5b5752a5-6123-4d76-b262-a308983ff30f)

Image 1: Startup Screen

Once the user is directed to the “Create Account” screen they can enter their Username and password.  If matching passwords are not entered, the message “The Passwords do not Match” will be displayed on the screen.  If the passwords match the user will be directed to the “Main Menu”.	
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/1e4a4877-6c8d-4c19-be78-ebff93b4c4bf)

Image 2:  Passwords do not match


4.0 How to Log Into The Game
On the “Login Screen,” the user can type their Username and Password to gain access to the system.  The user will be prompted with a message if the username or password is incorrect; otherwise, the user will be directed to the main menu screen.
![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/ff41ee33-d782-4aaf-9ed1-48775af2c15e)

 Image 3: Login Screen with incorrect login information

![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/39a88fe2-34ff-4aaa-827a-1a195dbc85a4)

 
Image 4: Main Menu after successful login

The user can also play as a guest.  When the user plays as a guest no data will be saved to the database.
5.0 Delete User Account
	Once a user has determined they no longer want to use a specific profile, they do have the option to delete an account. The user must select the link “Delete Account” on the login screen. On this screen, the user must enter their username and password and type “delete”. Once they select the submit button, the entire user profile will be removed from the database.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/b073280f-805f-4eb5-bef0-59ba1dfd94fc)

Image 5:Wrong username or password entered




6.0 Game Play	
6.1 Bank Balance
	Once the user has created a profile, the user will start with a balance of $1000.00. Any earnings and losses will be reflected in the user's bank account balance and carried over when the user logs into the system for future play.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/1d788cc5-2b33-41a6-9fbe-30d8b49b12e3)

Image 4: Main Menu after successful login with bank balance in upper left corner.

6.2 Betting
	Once the user selects “Play Blackjack” from the main menu, they will be directed to the betting screen.  At this point, the user can use the slider to bet any amount up to the maximum amount.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/54aed30f-6858-4b11-b805-3c0bcf7b835a)

Image 5: Betting Screen

6.3  Cards dealt to the Player and Dealer
	The dealer will automatically deal two cards to the player and themselves. The player will be responsible for asking for another card, known as a HIT, or deciding not to take a card, known as a STAND. The dealer, however, will take a HIT until they have at least enough cards valued at 17.
6.3.1 What is a HIT?
HIT is a term used to tell the dealer you want another card. Once you select HIT, the dealer will give you another card, and your new total card value will be displayed on the screen.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/28c2d3ef-7d82-4d8e-b645-bd5235921d7f)

Image 6: Hit button for another card 1st button to the left.

6.3.2 What is a Stand?
A STAND refers to a position the player takes when they decide they do not want another card. At this point, the dealer may take a HIT (the dealer must take a HIT if they are below 17).
![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/86313150-4eb7-4cfc-80c5-95170de7b046)
 
Image 6: Stand button 2nd button on the right.

6.3.3 What is a Double?

	You can Double your bet by selecting the DOUBLE BUTTON once the dealer hands out the initial cards and before hitting or standing.  Once you double, you will automatically take another card and stand.  When you double your bet, you must have enough money in the bank that is equal to the original bet.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/58dac837-eb29-4bec-a3d9-51695f19c8b3)

Image 6: Double button 2nd button from the left.
6.3.4 What is a Split?

	A split occurs when you have two cards of the same value.  You can split those cards and play additional hands at once.  You will play the first hand, take a stand, and then play the remaining hands.  Once you take a stand on the other hand, both hands will be matched against the dealer's hand as separate hands.  You can win both hands, lose one hand and win the next, or lose both hands.  This is risky but can pay off big.

 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/0a274b1c-eef9-4863-a9ff-5228937b7716)

Image 7: Split button 1st button from the left.

6.3.5 What is insurance?

	If the dealer has an Ace face up this gives you the opportunity to protect yourself in the event the dealer has a natural blackjack (natural blackjack is a 21 on the first two cards). If you select insurance, you will put up half the amount you bet.  For example, if you bet $500 on this hand, you will put up $250 in insurance.  If the dealer does not have a natural blackjack, you lose the insurance money.  If the dealer has a natural blackjack, you get your money back and do not lose any money.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/90370402-592e-42f7-aa9e-16f2a46d7e75)

Image 8: Insurance button 3rd button from the left.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/b066cf54-5d52-419d-8434-39574d58518f)

Image 8: Dealer wins player bank goes back to original amount

6.3.6 What is a Push?
	Push refers to a situation when both the dealer and the player have the same card value.  When this happens, neither the dealer nor the player wins, and as a result, the player does not win or lose any money.


6.3.7 How do you Win or Lose?
	There are a few conditions to win or lose the game.
6.3.7.1 How does a Player Win?	
1.	The Player has a hand of 21, and the Dealer does not.
2.	The Player has a higher hand than the Dealer.
3.	The Dealer Bust and the Player does not.
6.3.7.2 How does a Player Lose?
1.	The Player Bust if their hand is greater than 21.
2.	The Dealer has a higher hand than the Player.
3.	The Dealer has a hand of 21, and the Player does not.
6.3.7.3 Win and Loss amounts.
1.	If a player wins the hand, they receive double their original bet. For example, if you bet $500.00 and win, you will receive your $500.00 bet back, plus an additional $500.00 for a total of $1000.00, so your bank account will increase by $500.00.  
a.	$500.00 bet + $500.00 won = $1000.00
2.	If a player gets a natural blackjack (which is when the player's first two cards equal 21), they will earn 1.5 times what they bet.  
a.	$500.00 bet + 750.00 won = $1250.00.
3.	If the player doubles their bet, they will place an additional amount equal to their original bet.  In other words, if the player's original bet is $500.00, they will bet an additional $500.00 when they double, for a total of $1000.00.  If the player wins the hand, they will have $2000 in the bank.
a.	(2 x $500 original bet) + (2 x $500 won) = $2000 in bank
4.	If the player loses on a hand, they will lose their bet on that hand. If the player accepted insurance or even money, and the dealer had a natural blackjack, the player would lose their original bet but receive double their insurance bet and break even on the hand.
7.0 View Stats
	The stats view shows the player ranking by bank balance.  The screen can be accessed from the “Main Menu”.
 ![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/dc8b13bb-b97c-47b3-bc76-6d570943e99d)

Image 9: Player Stats 

8.0 Tutorial
	In-game instructions can be seen by selecting the “Tutorial” option in the “Main Menu”.  This gives the player information on how the game is played and the rules of the game.
![image](https://github.com/Khakipapi/CMSC495-Captsone/assets/74410806/99a7e067-0c1e-4ee1-a2e1-30de3ac74cf0)
 
Image 10: Player Stats 


9.0 Additional Help
	For more tips on Blackjack, you can search online resources which can give you more sophisticated techniques.  The additional techniques applied to the Blackjack Simulator will give you additional insight on how to navigate different 
strategies. 
