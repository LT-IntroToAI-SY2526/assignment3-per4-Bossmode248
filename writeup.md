# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
Through this assignment, I have learned how to effectively swift through data bases to find specific things using certain variables like time and actors. I've also learned to use code I myself am just experiencing, and how to make my own functions and asserts better. 


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
When the user types in a query, the  system firsts searches to see if what the user gave is in the data base. If its not found, nothing is done. Once its found, it searches with in the relalted movies to find the information the user wanted out of their query, then returns it in its own list. 


3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use? 
This could be used any where, as Data bases are a commonly used thing to store lots of data for a specific thing. When you have so much data, you need an effective way to be able to search through all the data. To improve this system, I would make it so we have a better search funtion. its too specific, so we need a search funtion that can search through the data base only using things like keywords like "in (year)" or "from (year)" and more. 