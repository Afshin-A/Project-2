# Project-2
This program calculates compund interest earned based on user entry

The program intakes 4 data variables from the user: initial investment amount, additional monthly deposits, interest rate percentage, and the number of years.
Using this data, the program calculates the balance and interest year by the end of each year (through the number of years entered by the user) twice: once with the additional monthly deposits, and another time with 0 monthly deposits. The program then displays both outcomes for comparison.

I believe the class design and the use of pointers to access members of the said class is well done in this class.
One area of code that requires improvement is handling run-time errors concerning user inputs. The program already implements exception-handling techniques should the user enters a number outside of acceptable range. However, there are no means of handling entries of incorrect data types (e.g., if the user enters a string instead of an integer),

I would say the most difficult part of this project, and other projects I have worked on thus far, is creating a plan (pseudocode and flow charts). The biggest mistake I have done is jumping into a project without pre-planning, only to end up staring at my screen for hours before getting disgruntled about my code not functioning properly.
Otherwise, the void InterestPlan::ShowResult() function was the most difficult to design. It was a challenge to find a relationship between the number of months, years, and vector elements to the two for-loop index variables.

C++ is an object-oriented language. The skills of creating and using classes and objects will definitely be used in future programs.
The code is mostly straightforward and self-explanatory. However, there are in-line comments along that provide descriptions for elements of the code. In addition, standard naming and indenting practices are utilized in this project for further readability.
