# CODSOFT 
CHATBOT WITH RULE-BASED RESPONSES


This project is part of Task 1 for the CodSoft AI Internship, where we build a simple rule-based chatbot using Python and ipywidgets in Google Colab. 
The chatbot provides interactive text-based communication with basic natural language understanding using regular expressions.

 Objective
 
- To develop an interactive chatbot that can simulate a simple conversation with users and respond to specific keywords or patterns in the input. The chatbot also displays the current time in India when requested and ends the conversation on command.

 Technologies Used
 
- Python

- Regular Expressions (re) – Pattern matching in user input

- Datetime & Pytz – To fetch current time in India

- IPyWidgets – For interactive user input

- IPython.display – For displaying real-time chat history

Features

- Responds to greetings like hello, hi, and hey
- Can tell its name when asked (your name)
- Displays the current time in India using pytz
- Handles polite expressions like thank you
- Ends the chat gracefully when the user types bye
- Maintains and displays conversation history
- Uses a text box UI to simulate chat in Google Colab

 How It Works
 
1. User Input
- Typed using ipywidgets.Text() box
- Monitored via an event handler that triggers on submit

2. Pattern Recognition
- User input is analyzed using re.search() for predefined patterns

3. Response Generation
- Based on pattern match, a response is generated from a set of rules

4. Chat History
- User input and bot responses are stored in a list
- Displayed dynamically using IPython.display

Conclusion

This project showcases a simple yet functional chatbot built using Python and ipywidgets.
It responds to basic user inputs, displays the current time, and maintains a conversation flow.
While basic, it provides a solid foundation for developing more advanced AI-driven chat applications.


Author:

JEEVIKA R

Codsoft Artificial Intelligence Intern

#codsoft #artificialintelligence #internship
