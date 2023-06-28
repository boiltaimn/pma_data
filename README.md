# User Manual for PM Assistant 1.0
based on the structure of this repository:https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/tree/main. Already authorized by the author of Mr. Ranedeer.

## All commands

**/sol <Case>**: Provide solutions for a specific case.
    
Example:
    /sol 
    In the loan application process, after the client submits their loan application, the clerk performs three checks in a random order: identity check, verification, and creditworthiness check. If any of these checks fail, the application is rejected. However, since there is no predefined order for conducting the checks, it leads to an issue of overprocessing.

**/heu <List of Heuristics>**: Utilize rarely used heuristics by GPT to generate solutions from a different perspective.
    
Example:
    https://raw.githubusercontent.com/boiltaimn/pma_data/main/test_txt.txt

**/imp <number>**: Implement the selected solution identified by its number.
    
Example:
    /imp 3
    
**/pre <number or solution>**: Predict the potential outcome of a solution.
    
Example:
    /pre # predict the outcome of current solution
    /pre 2 # Predict the solution with number 2
    /pre Process Standardization # Predict the result of "Process Standardization"
    
**/sug**: Allow GPT to suggest questions based on the current conversation.
    
Example:
    /sug
    
**/que <question>**: Pose a question. You can also ask questions without using the command, but it is recommended to use the command as GPT might occasionally lose its personality without it.
    
Example:
    How about adding missing system functionalities for this case? # Ask a question without the command
    /que How about adding missing system functionalities for this case?

**/goto <number i>**: Each round of the conversation is assigned a number. Using this command, you can revisit a specific conversation and continue from there. This command enables GPT to forget the conversation that occurred after the i-th conversation.
    
Example:
    # Go to the third conversation and implement the first solution
    /goto 3 
    /imp 1

**/config <configuration>**: Used for configuring settings.
    
Example: 
    /config Tone Style = Humorous
    
**/language**: Used to change the language.
    
Example: 
    /language Deutsch
