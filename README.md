Download Link: https://assignmentchef.com/product/solved-comp248-assignment-4-one-dimensional-array
<br>
<h1>One Dimensional Array</h1>

Write a program that asks a user for names of 8 soccer teams and outputs a possible road map of 4 quarter finals, 2 semifinals, 1 final and the final winner of a tournament.

Your program should proceed as follows:

<ol>

 <li>Ask the user for a name for the soccer tournament followed by the names of the 8 participating teams. (You can assume that each name, which can be more than 1 word, will be correctly entered on a separate line.) The participating teams are to be stored in a one-dimensional array.</li>

</ol>




<ol start="2">

 <li>Generate the output roadmap by choosing at random combinations of teams and a winner for each combination at each level to produce a final winner. Of course a team can only be in one quarter final game. Figure1 illustrates how teams are matched for the semi-finals and finals.</li>

</ol>




Use the random number generator from the Math class or Random class to randomly pick the original combination of the 8 teams in the quarter finals and the winner of each game.

<ol start="3">

 <li>Your program output should be displayed in the format below.</li>

</ol>




<ol start="4">

 <li>The user should be able to request for a different outcome until he receives an output that he likes. This involves shuffling the teams in the array to determine who plays against whom in the quarter finals. (You can usenextInt(bound) in a loop to randomize the array- in other words to shuffle the array entries.)</li>

</ol>




<ol start="5">

 <li>When a user chooses to stop, your program should display a closing message like:</li>

</ol>

‘Thank you for using the JAVA Tournament Winner Predictor Program.’




Here are a few sample outputs to illustrate the expected behavior of your program.

<u>Note</u>: user input is highlighted in grey.




<table width="622">

 <tbody>

  <tr>

   <td width="622"><em> </em>—————————————————–<strong>       </strong>Welcome to Tournament Outcome Predictor Program—————————————————–Please enter a name for the soccer tournament la liga Please enter the 8 participating teamsAtlético MadridBarcelonaGetafeLevanteReal BetisReal MadridSevillaValencia —– la liga Outcome Predictions —–Quater Final 1: Real Betis Vs Valencia Valencia Wins !!! Quater Final 2: Atlético Madrid Vs Sevilla Atlético Madrid Wins !!! Quater Final 3: Real Madrid Vs Barcelona Barcelona Wins !!! Quater Final 4: Getafe Vs Levante Getafe Wins !!! Semi-Final 1: Valencia Vs Getafe Getafe Wins !!! Semi-Final 2: Atlético Madrid Vs Barcelona Atlético Madrid Wins !!! Final: Getafe Vs Atlético Madrid Getafe Wins !!! Do you want a different outcome? y or n y —– la liga Outcome Predictions —– Quater Final 1: Getafe Vs Sevilla Getafe Wins !!! Quater Final 2: Atlético Madrid Vs Real Betis Real Betis Wins !!! Quater Final 3: Valencia Vs Levante Valencia Wins !!! Quater Final 4: Barcelona Vs Real Madrid Real Madrid Wins !!! Semi-Final 1: Getafe Vs Real Madrid Real Madrid Wins !!! Semi-Final 2: Real Betis Vs Valencia Valencia Wins !!! Final: Real Madrid Vs Valencia Real Madrid Wins !!! Do you want a different outcome? y or n nThank you for using the JAVA Tournament Winner Predictor Program</td>

  </tr>

 </tbody>

</table>

<h1>Question 2 (2-dimensional Arrays)</h1>

Write a program that implements a card magic game where you accurately predict a user’s card from a randomly generated 4×4 card matrix.  Your program should proceed as follows:




<ol>

 <li>Generate a random 4×4 card matrix and print it on the screen.</li>

</ol>

<strong>Tips</strong>: You could use a 1D index array for card numbers, 4×4 matrix for cards with one row each for 4 card types. You can randomize rows and columns independently using a loop to swap values at random or use the randomizeArray() method.




<ol start="2">

 <li>Ask a user to pick a card and to enter the corresponding column number for that card. (You have to make sure that the user enters a number between 1 and 4 and nothing else.)</li>

</ol>




<ol start="3">

 <li>Transpose the 4×4 card matrix (i.e. rows matrix becomes column matrix) and print it on the screen. Ask user for the new column number for his chosen card. (Simply swap loop variables.)</li>

</ol>







<ol start="4">

 <li>Make use of the two inputs from the user to predict his card. Your program output should be displayed in the format below. The user should be able to request for another try until he is satisfied that program correctly predicts the card every single time.</li>

</ol>




<ol start="5">

 <li>When a user chooses to stop, your program should display a closing message like:</li>

</ol>

‘Thank you for using the JAVA Magic 101 Program.’




Here is an example of the output to illustrate the expected behavior of your program.




<u>Note</u>: user input is highlighted in grey. <sub> </sub>

<table width="634">

 <tbody>

  <tr>

   <td width="634">——————————–Welcome to Card Magic 101——————————–Nine of Diamonds     Ace of Diamonds       Ten of Diamonds      King of DiamondsNine of Hearts       Ace of Hearts        Ten of Hearts        King of HeartsNine of Clubs        Ace of Clubs         Ten of Clubs         King of ClubsNine of Spades       Ace of Spades        Ten of Spades        King of SpadesPlease pick a card and enter the column number (1-4) where it appears 1Nine of Diamonds      Nine of Hearts       Nine of Clubs        Nine of SpadesAce of Diamonds      Ace of Hearts        Ace of Clubs         Ace of SpadesTen of Diamonds      Ten of Hearts        Ten of Clubs         Ten of SpadesKing of Diamonds      King of Hearts       King of Clubs        King of SpadesPlease indicate which column number (1-4) it is in now xPlease enter an integer value between 1 and 4 5Please indicate which column number (1-4) it is in now3Your card is Nine of ClubsDo you want to try one more time? y or n yFour of Diamonds     Six of Diamonds       Jack of Diamonds      Nine of DiamondsFour of Clubs        Six of Clubs         Jack of Clubs        Nine of ClubsFour of Spades       Six of Spades        Jack of Spades       Nine of SpadesFour of Hearts       Six of Hearts        Jack of Hearts       Nine of HeartsPlease pick a card and enter the column number (1-4) where it appears 3Four of Diamonds      Four of Clubs        Four of Spades       Four of HeartsSix of Diamonds      Six of Clubs         Six of Spades        Six of HeartsJack of Diamonds      Jack of Clubs        Jack of Spades       Jack of HeartsNine of Diamonds Nine of Clubs  Nine of Spades  Nine of Hearts  Please indicate which column number (1-4) it is in now4Your card is Jack of HeartsDo you want to try one more time? y or n nThank you for using the JAVA Magic 101 Program</td>

  </tr>

 </tbody>

</table>

<h1>Question 3 (Simple Class Exercise)</h1>

Define a class named Car that stores information about a car. It should comprise of the following:




<ol>

 <li>Private instance variables to store age of the car, its type (sedan or suv) and its cost.</li>

 <li>4 constructors:

  <ol>

   <li>No argument (sets age to 0, type to sedan and cost to 32000).</li>

   <li>one argument constructor (sets cost to a value, age to 0 and type to sedan).</li>

   <li>two argument constructor (sets age to a value, cost to a value, and type to sedan).</li>

   <li>three argument constructor (sets age to a value, cost to a value, and type to value sedan or suv).</li>

  </ol></li>

</ol>




<ol start="3">

 <li>3 Accessor methods: – methods to return age, type and cost respectively.</li>

 <li>5 Mutator methods: – 3 methods for setting the three values independently, a method to set all three values and a method to set only age and cost of the car.</li>

 <li>A public method called estimatePrice() that returns the cost of a car based on type and age. A sedan costs $32000, depreciates 10% every year in first five years and 5% every year afterwards. An SUV costs $45000, depreciates 8% every year in the first five years and 4% every year afterwards.</li>

 <li>A toString() method that returns the type of the car as well as it’s age and</li>

 <li>An equals() method to test for equality of two objects of class car based on type and age.</li>

 <li>isLessThan() and isGreaterThan() method to compare between the prices of two objects of class car.</li>

</ol>




<ol>

 <li>b) Write a driver class</li>

</ol>




<ol>

 <li>Which declares 4 car objects using 4 different constructors and outputs the description of the 4 cars.</li>

 <li>Test your accessor methods.</li>

 <li>Calculate the estimated price of the cars given the type and age (include 1 sedan and 1 SUV)</li>

 <li>Test out all 5 mutator methods to modify car attributes.</li>

 <li>Test methods toString(), equals() , isLessThan() and isGreaterThan() for different car objects.</li>

</ol>




Here is an example of the output to illustrate the expected behavior of your program.




<table width="634">

 <tbody>

  <tr>

   <td width="634">Car C1: This car is type Sedan. Its age is 0 and costs $32000.0Car C2: This car is type Sedan. Its age is 0 and costs $32000.0Car C3: This car is type Sedan. Its age is 4 and costs $18000.0Car C4: This car is type SUV. Its age is 2 and costs $36000.0Accessor Method: The cartype for car C4 is SUV, its age is 2, and it costs $36000.0The estimated price of car C3 is $24800.0The estimated price of car C4 is $39240.0Mutator Method: The new age for car C3 is 5Mutator Method: The new cartype for car C3 is SUVMutator Method: The new cost for car C3 is 14000.0Mutator Method: The new car age is 9 and its new cost is 9000.0Mutator Method: The new cartype for car C3 is Sedan, its new age is 14and its cost is 5000.0 toString: This car is type Sedan. Its age is 14 and costs $5000.0Cars C1 and C2 are equal is trueCars C1 and C4 are equal is falseCar C4 is less than C3 is falseCar C1 is greater than C3 is true</td>

  </tr>

 </tbody>

</table>





