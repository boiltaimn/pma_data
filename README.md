# User Manual for PM Assistant 1.0
PM Assistant is structured based on the repository: https://github.com/JushBJJ/Mr.-Ranedeer-AI-Tutor/tree/main. Authorization has been obtained from the author of Mr. Ranedeer.

## Commands

**/sol <Case>**: Offers solutions for a specific case.

Example:
```bash
/sol
In the loan application process, after the client submits their loan application, the clerk performs three checks in a random order: identity check, verification, and creditworthiness check. If any of these checks fail, the application is rejected. However, since there is no predefined order for conducting the checks, it leads to an issue of overprocessing.
```

**/heu <List of Heuristics>**: Utilizes lesser-used GPT heuristics to generate solutions from alternate viewpoints.

Example:
```bash
/heu https://raw.githubusercontent.com/boiltaimn/pma_data/main/test_txt.txt
```

**/imp <number>**: Implements the selected solution, identified by its number.

Example:
```bash
/imp 2
```

**/pre <number or solution>**: Predicts the potential outcome of a solution.

Example:
```bash
/pre # Predict the outcome of the current solution
/pre 2 # Predict the solution with number 2
/pre Process Standardization # Predict the result of "Process Standardization"
```

**/sug**: Invites GPT to suggest questions based on the current conversation.

Example:
```bash
/sug
```

**/que <question>**: Presents a question. Questions can also be asked without using the command, but it's recommended to use the command as GPT might occasionally lose its personality without it.

Example:
```bash
/que How about adding missing system functionalities for this case?
```

**/goto <number i>**: Each round of conversation gets assigned a number. Using this command, you can return to a specific conversation and continue from there. This command enables GPT to forget the conversation that happened after the i-th conversation.

Example:
```bash
/goto 3 
/imp 1
```

**/config <configuration>**: Used to set configurations.

Example: 
```bash
/config Tone Style = Humorous
```

**/language**: Used to switch languages.

Example: 
```bash
/language Deutsch
```
