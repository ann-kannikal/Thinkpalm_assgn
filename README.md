# Python coding assignment
Here, I provide a brief explanation for each of the 4 tasks.

Task 1: The goal was to perform data anlysis on a dataset of choice using the Pandas library. 
The read_csv function was used to read in a comma separated file.
The average, minimum and maximum vales of the Pulse variable was computed. The top 5 records of the dataset were also printed.
These results were written into a csv file names output.csv

Task 2: The goal was to practice API integration using Python. OpenWeatherMap, a public API was used to get weather data of cities. A function was specified using an API ID generated from the website and its url. The requests.get() function from the requests library was used. The status code of the request was checked to see if everything wemt well. The city name, temperature and weather conditions were fetched and printed out. In order to handle API errors and to make the code more user friendly, we used exception handling. The code catches errors such as HTTP errors, connection errors and timeout. A keyerror is caught to handle code when the data the user asked for is not available.

Task 3: The goal was to demonstrate understanding of OOP concepts in python. A class called BankAccount was created with attributes such as account number, account holder and available balance. Three methods were created. Instances of the class were created to see the methods in action. Exception handling was implemented to see how the class would handle invalid transactions. 

Task 4: The goal of the task was to write a function that takes a string and finds the length of the longest substring without repeating characters. We use two nested for loops that loop through every possible substring. We use an empty set called repeated_char to keep track of characters in the substring. The inner for loop checks if the current character is already in the repeated_char set, and if yes, the loop breaks. We update the 'length' variable with the lenth of the longest substring found.  
  
  In order to optimise this solution to perform better, we make sure that the algorithm runs in linear time. Update the 'start' position only when we encounter a repeated character. The longest length of substring is calculated by taking the maximum of current length of substring and the length of the previously recorded longest substring length.
