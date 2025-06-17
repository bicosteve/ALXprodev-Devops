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

''' 2. Batch Pokémon Data Retrieval

Objective: Automate the retrieval of data for multiple Pokémon and store it in separate files.

Instructions:

    Create a script that loops through a list of Pokémon [Bulbasaur, Ivysaur, Venusaur, Charmander, Charmeleon]

    For each Pokémon, retrieve its data from the API and save it to a separate file named after the Pokémon (e.g., pikachu.json, bulbasaur.json…).

    Handle any potential rate-limiting issues by adding a delay between requests.

'''

''' 3. Summarize Pokémon Data

Objective: Create a report that summarizes data for multiple Pokémon.

Instructions:

    Write a shell script that reads all the JSON files generated in Task 2 and extracts the name, height, and weight of each Pokémon.

    Generate a CSV file containing the Pokémon’s name, height, and weight.

    Use awk to calculate the average height and weight of all Pokémon in the report.

'''

''' 4. Error Handling and Retry Logic

Objective: Add robust error handling and retry logic for API requests.

Instructions:

    Modify the script from Task 2 to handle potential errors (e.g., network issues, invalid Pokémon names).

    If an API request fails, implement a retry mechanism that attempts the request up to 3 times before logging the error and skipping to the next Pokémon.

'''

''' 5. Parallel Data Fetching

Objective: Speed up data retrieval using parallel processing.

Instructions:

    Write a script that fetches data for these Pokémon[Bulbasaur, Ivysaur, Venusaur, Charmander, Charmeleon ] in parallel by leveraging background processes and process management tools.

    Ensure that the script handles background processes properly and waits for all processes to complete before moving to the next step.

'''
