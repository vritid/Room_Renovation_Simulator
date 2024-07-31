# fav-project
Room Renovation Simulator 

Scenario: This program simulates the experience of purchasing paint, to renovate the user’s room, using mainly string and numeric
manipulation, as well as class methods with return values. It includes asking the user the dimensions of the room they want painted,
as well as whether or not they’re part of the PaintMania rewards program. The user is eligible to get a free paint job by the company if
they are a member of the rewards program by spinning a wheel. This program also prints the receipt of the purchase, including the dimensions and the
number of paint buckets required to complete the job.


Input:
- The name of the user’s room they want to paint
- Width of the wall in the room
- Height of the wall in the room
- Prompt to check if user is part of the rewards program
If eligible for the rewards program:
- Prompts user to enter a character to spin the wheel
- Word they would like to be displayed on the paint job
- First 3 letters of their name
- 2 digits user wants to be displayed on paint job


Algorithm:
1. Create the main method to start the program execution.
2. Display an introduction and program description.
3. Prompt the user to enter the name/identifier of the room.
4. Prompt the user to enter the width and height of the wall.
5. Calculate the surface area of the wall using the provided width and height.
6. Calculate the number of paint buckets needed based on the surface area.
7. Calculate the cost of the paint based on the number of buckets.
8. Calculate the tax on the paint cost.
9. Calculate the total cost by adding the paint cost and tax.
10. Ask the user if they are a member of the rewards program.

11. If the user is a rewards program member, offer a chance to win a free car paint job.
12. Spin the wheel to determine the outcome of winning a free paint job.
13. If the user wins, collect the necessary data for the car paint job (word, name, number) and process it to create a customized
name.
14. Print the customized name for the car paint job.
15. If the user does not win, display a message indicating they didn't win a free paint job.
16. If the user is not a rewards program member, inform them that they are not eligible to win a free paint job.
17. Print the wall dimensions, surface area, number of buckets, paint cost, tax, and total cost.
18. End the program.


Process/Predefined Methods used:
1. input.next(): Used to get the input from the user (string).
2. input.nextDouble(): Used to get the input from the user (double).
3. String substring(#,#): Used to extract a substring from a string, starting from beginIndex and ending at endIndex-1.
4. String toUpperCase(): Used to convert a string to uppercase.
5. String toLowerCase(): Used to convert a string to lowercase.
6. String replaceFirst(a, b): Used to replace the first occurrence of a substring in a string with another substring.
7. String compareToIgnoreCase(String str): Used to compare two strings whilst ignoring upper/lower case.
8. Math.random(): Used to generate a random number (used to spin the wheel)
9. Math.ceil(double a): Used to round up a double value to the nearest integer greater than or equal to it.
10. System.out.println(“ “): Used to print a string followed by a new line.
