🔹 How Your The Works:

chatbot_response() function
Converts user input to lowercase (user_input.lower()).
Uses if-elif-else conditions to check for keywords.
Returns pre-defined responses based on matching patterns.
main() function
Prints an introduction message.
Runs an infinite loop until the user types "bye" or "exit".
Takes input from the user, passes it to chatbot_response(), and prints the reply.
Program Execution
Runs main() if the script is executed directly (if __name__ == "__main__":).


🔹 Skills Used in the Above Chatbot Code:

Python Programming Basics
Use of functions (chatbot_response, main)
Use of conditionals (if-elif-else)
Loops (while True) to keep conversation going
String operations (lower(), keyword search using "in")
Rule-Based Logic Building
Designing a decision-making system where responses depend on keywords.
Basic intent recognition (greetings, exit, help, etc.).
User Interaction / I/O Handling
Taking input using input()
Printing chatbot responses using print()
Clear conversation flow (input → processing → response).
Program Structure & Flow Control
Using if __name__ == "__main__": for script execution.
Breaking loops gracefully when user types "bye" or "exit".
Text Preprocessing
Normalizing text with .lower() so that input is case-insensitive.
(Simple form of NLP preprocessing).
