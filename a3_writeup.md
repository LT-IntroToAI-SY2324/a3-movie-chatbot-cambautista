# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
This function takes in a question input by the user and figures out if it can be matched to a question in the pa_list. The question could regard the name of an actor, title, or movie. If it finds a match to the question but doesnt have the answer to that specific question, it returns no answers. If the question the user entered does not match anything in the pa_list, it returns "I dont understand"

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added Breakfast at Tiffanys (1961) Its a classic

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
(str.split("what movies were produced in _"), title_by_year),
Its another way of writing "what movies were made in"

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would like to create a chatbot that keeps track of passwords created. When asked for the password or username for a speciic website the database searches through the information and returns it. I think it would be convienient for storing and keeping track of everypassword craeted.

5. What was the most difficult portion of this assignment?
The search_pa_list was the most difficult portion of the assignment. I didnt fully comprhend how the code works

6. Did you write a new assert for your pattern action?



