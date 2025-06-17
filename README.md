# ALXprodev-Devops

''' 0. API Request Automation

Objective: Automate the process of making API requests to the Pokémon API and saving the results to a file

Instructions:

    Write a shell script that makes a request to the Pokémon API and retrieves data for a specific Pokémon Pikachu.

    It should save the response to a json file: data.json

    If the request fails, it should log the error to an error file: errors.txt '''

''' 1. Extract Pokeman Data
Objective: Use advanced text manipulation tools (jq, awk, sed) to extract specific data from the API response.

Instructions:

    Write a script that extracts the Pokémon’s name, height, weight, and type from the JSON file created in Task 0.

    Format the output in a human-readable way,“Pikachu is of type Electric, weighs 6kg, and is 0.4m tall.”

    You should only use these commands: jq, awk, sed

Sample Output:

ghostmode@GhostMode:~$ ./parse_pikachu
Pikachu is of type Electric, weighs 6kg, and is 0.4m tall.
ghostmode@GhostMode:~$

'''
