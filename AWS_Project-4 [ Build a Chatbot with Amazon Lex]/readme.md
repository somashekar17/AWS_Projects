# Banking Chatbot Using Amazon Lex

## Introduction
This project is a banking chatbot built using Amazon Lex. It allows users to interact with banking services through natural language processing.

## Features
- **Natural Language Understanding**: Understands user queries and responds appropriately.
- **Voice and Text Interaction**: Supports both voice and text inputs.

## Getting Started

1. **AWS Account**: 
   - Create an AWS account if you don’t have one. Go to the [AWS Signup Page](https://aws.amazon.com/) and follow the instructions to create an account.

2. **Set Up Amazon Lex** 🌱 : 
   - Access the Amazon Lex console by navigating to the AWS Management Console.
   - In the services menu, search for and select **Amazon Lex**.
   - Click on **Create Bot** to start setting up your chatbot.
   - Choose a bot type (e.g., BankerBot) and fill in the required information, including the bot name and output voice settings.
    ![Task4 0](https://github.com/user-attachments/assets/9ccf6452-e71e-4e1c-88d6-a137990d3f84)

3. **Create Your First Intent** 💬 : 
   - After creating your bot, go to the **Intents** section.
   - Click on **Create Intent** and provide a name (e.g., `WelcomeIntent`).
   - Add sample utterances that users might say to invoke this intent (e.g., "What is my balance?" or "Check my balance").
   - Define any necessary slot types if your intent requires specific information (e.g., account type).
   
    ![Task4 1](https://github.com/user-attachments/assets/3fd6476d-6fbf-49a6-ad4a-35d20cf5f074)


4. **Manage Fallback Intent** 🤚: 
   - Navigate to the **Fallback Intent** within the intents section.
   - This intent is triggered when the bot does not understand user input.
   - Add a response that politely informs users that their input was not recognized (e.g., "Hmm could you try rephrasing that? I can help you find your account balance, transfer funds and make a payment.").

     ![Task4 2](https://github.com/user-attachments/assets/ef9c5af5-ca13-42de-a87f-4d87b24eab12)


5. **Test the Chatbot**: 
   - Use the test functionality in the Lex console to interact with the bot.
   - Enter sample phrases to ensure your intents are recognized and responses are appropriate.
   - Adjust intents and responses based on test results for improved accuracy.


