# 00_Student_chat-_Agent
# Student Agent

The Student Agent is a chatbot designed to assist students by providing solutions to common problems. It leverages conversational AI to offer personalized and helpful responses. The agent includes memory capabilities to maintain the context of conversations for better user interaction.

# Features

# 1. Submit Complaints

Students can submit complaints about various issues (e.g., library timing, cafeteria services).

The agent processes the complaints and confirms submission.

## 2. Study Plan Generator

Creates a customized study plan based on the subject and available study hours.

Divides the time equally between reviewing theory and solving problems.

## 3. Outfit Suggestions

Suggests appropriate outfits based on the type of event (e.g., party, interview).

Includes a fallback suggestion for unspecified events to ensure helpful responses.

## 4. Conversation Memory

Maintains context across the conversation to improve follow-up responses.

Uses LangGraph's memory features to persist state between steps.

## Technology Stack

LangChain Google GenAI: Provides conversational AI capabilities.

LangGraph: Manages the flow of conversation and memory.

Python: Core programming language for implementation.

## Usage

Running the Chatbot

Ensure all dependencies are installed, including LangChain and LangGraph.

Set up your API key for Google Generative AI (GEMINI_API_KEY).

Configure and run the chatbot using the provided Python script.

## Example Interaction

User Input:

I have a complaint about the library timing.

Bot Response:

Your complaint has been submitted: 'I have a complaint about the library timing.' Thank you for your feedback!

User Input:

Can you suggest an outfit for a party?

Bot Response:

Wear a stylish dress or a shirt with trousers and comfortable shoes.

Code Highlights

Tools

Functions such as submit_complaint, give_study_plan, and give_outfit_idea are registered as tools to handle specific user requests.

Graph and Memory

The conversation flow is managed through a state graph using LangGraph.

Memory checkpoints ensure the chatbot remembers the conversation context.

Customization

You can extend the functionality by:

Adding more tools for other student needs (e.g., exam reminders, mental health resources).

Integrating additional APIs for more sophisticated suggestions or automation.

Installation

Clone this repository:

git clone https://github.com/your-repo/student-agent

Navigate to the project directory:

cd student-agent

Install the required dependencies:

pip install -r requirements.txt

Set your GEMINI_API_KEY environment variable:

export GEMINI_API_KEY="your-api-key"

Run the script:

python student_agent.py

Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your enhancements.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Contact

For questions or support, please contact:

Email: maarikram786@gmail.com

GitHub: Student Agent Repository


