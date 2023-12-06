# Paradox assignment
## In this task, I had to create a conversational AI assistant for parents interested in the fictional GenAI Summer Camp, using Large Language Model (LLM) technology
### The technical framework of my code consists of a series of function definitions that integrate with an AI model to manage and respond to user interactions for a summer camp. The run_router_prompt function acts as a classifier, utilizing the AI to discern the user's intent by analyzing their input and categorizing it into one of two possible outcomes: a general inquiry about the camp (0) or an intent to sign up a child (1). This binary classification is pivotal for the subsequent logic flow, directing the conversation down the appropriate response path.

### Once the user's intent is classified, the handle_user_input function delegates the input to either handle_question_prompt or handle_application_prompt, depending on the classification result. These functions craft responses by invoking the AI model with context-specific system messages that guide the AI's output. The handle_question_prompt function pulls information from a variable containing camp details, while the handle_application_prompt deals with the sign-up process guided by another set of pre-defined information. Each function returns a generated response that aligns with the user's original query or request, maintaining a streamlined interaction process.

### Additional information

Direct link to the collab notebook: https://colab.research.google.com/drive/1-HPk31zU_n2aL1SDPBkR0K3Yg4_3TAlj?usp=sharing
