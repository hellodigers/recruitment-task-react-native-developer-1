# Digers React Native Developer Recruitment Assignment

**A simple, RN based assignment assessing your React Native development skills.** 



### Requirements/perequisites:
* Working on Android **or** iOS
* Data source to be used in the game (list of countries with corresponding flags) available at https://github.com/linssen/country-flag-icons/blob/master/countries.json
* Use local storage to store country/flag data


### Rules and gameplay:
A simple True/False game - displays pairs of country flag and country name. Pairs can be correct or incorrect. Player's role is to confirm whether flag/name pair is correct or not.



 ### Gameplay
*  Upon launch the app downloads the aforementioned .json dataset.
*  When new game is started, prepare a set of 10 pairs, 5 of which are correct, 5 of which are incorrect. Download image data.
*  When completed, display first pair (name, flag) and start timer
*  Answering by swyping left (incorrect), swype right (correct)
*  If answered correctly - display 'Correct!' messsage, proceed to next pair
*  Limited time to answer - 3 seconds. If time is exceeded - game over - display 'Time's up!' message and proceed to summary screen.
*  If answered incorrectly - game over, display 'Incorrect!' message and proceed to summary screen.
*  When 10 pairs are answered correctly - game ends, proceed to summary screen.


### Design/screen breakdown ###  
 * welcome screen ('Play' button, rules), 
 * answering screen (flag image, country name, time counter, number of answered/number of all pairs), 
 * summary screen (number of correct answers
 

**Once completed, upload code to your github account and share.**
