# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:30/04/2025                                                                          
### REGISTER NUMBER : 212223223003
### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  
1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
3. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
4. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
5. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
6. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
7. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.

## Scenario
These professionals focus on building and implementing AI systems and chatbots. They are skilled in programming, machine learning, and natural language processing (NLP).Using Straightforward Prompts, Tabular Format Prompting and Preceding Question Prompting techniques

1. Straightforward Prompts
Definition: These are simple, direct prompts where the chatbot asks clear, specific questions. This is one of the most basic methods to guide the conversation.
Example in Chatbot Development:
•	Scenario: A user wants to troubleshoot a product.
•	Prompt Example:
o	Chatbot: “Please describe the issue with your product.”
o	Chatbot: “Can you provide the product ID for assistance?”
How the AI/Chatbot Developer Uses It:
•	The developer will program the chatbot with direct prompts to gather necessary information in a clear, concise manner. This ensures that the conversation doesn't overwhelm the user with unnecessary options or information. It’s perfect for situations where the user needs to provide simple, specific details.
Benefit: It keeps the interaction simple and efficient, especially for straightforward customer inquiries or tasks.
________________________________________
2. Tabular Format Prompting
Aspect	Details
Prompting Technique	Tabular Format Prompting
Definition	This method involves presenting multiple options in a table or list format, making it easy for the user to select an appropriate choice.
Scenario	The user wants to check the status of their order or report an issue.
Prompt Example	Chatbot: “Please select one of the following options to continue:
[1] Track my order
[2] Report a product issue
[3] Speak to customer support”
How Developer Uses It	- Structures chatbot responses using list/table format.
- Links each option to a specific response or action.
- Ensures clear navigation paths.
Benefit	- Simplifies complex choices.
- Reduces user confusion.
- Increases interaction efficiency by organizing choices clearly.
________________________________________
3. Preceding Question Prompting
Definition: This technique involves asking a question based on the user’s previous answer, guiding them to a more specific response. It’s a method of narrowing down options based on prior interactions.
Example in Chatbot Development:
•	Scenario: The user reports a product issue, and the chatbot needs to narrow down the possible causes.
•	Prompt Example:
o	Chatbot: “What seems to be the issue with your product?”
o	User: “The screen is cracked.”
o	Chatbot: “Was the product damaged during delivery?”
o	User: “Yes, it was.”
o	Chatbot: “We can assist you with a return. Would you like to initiate a return request now?”

How the AI/Chatbot Developer Uses It:
•	The developer ensures that the chatbot uses previous user responses to tailor its next question or action. This requires programming the chatbot to track the flow of the conversation and ask relevant follow-up questions based on context.
•	The chatbot needs to be able to dynamically adjust its questions based on the user’s responses, which requires implementing conditional logic and state management.
Benefit: It makes the conversation more personalized and efficient by gathering detailed context and narrowing down the possibilities. This technique also helps improve the accuracy of the chatbot’s response.

Conclusion:
By using these prompting techniques, an AI/Chatbot Developer ensures that the chatbot provides a smooth, efficient, and user-friendly experience. The combination of straightforward prompts for simplicity, tabular format prompting for clarity in options, and preceding question prompting for personalized conversation flow creates a highly functional chatbot capable of handling a wide range of customer queries with ease.

# Result: 
Thus the Prompts were exected succcessfully .

