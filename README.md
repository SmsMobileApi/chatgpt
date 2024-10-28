ChatGPT SMS Integration with SMS Mobile API

Effortlessly connect ChatGPT to your mobile phone using the SMS Mobile API. This integration enables ChatGPT to respond directly to incoming SMS messages on your device, making it easy to automate SMS-based customer support, personal assistant services, and much more, leveraging ChatGPT's conversational AI capabilities.
Features

    Automated SMS Responses: ChatGPT responds to incoming SMS messages on your device, allowing for seamless, real-time conversation.
    Personal Assistant Capability: Set up ChatGPT as a personal assistant via SMS, enabling 24/7 response availability.
    Enhanced Customer Engagement: Use ChatGPT’s AI-driven responses to manage customer inquiries, support tickets, and general interactions efficiently.
    International Service: This integration works worldwide, perfect for businesses with a global audience.

Prerequisites

    SMS Mobile API Account: Install the SMS Mobile API app (available for Android and iOS) and create an account. The app will automatically generate your API key, linking it to your phone for secure SMS access.
    OpenAI API Key: Obtain an API key from OpenAI to access ChatGPT's API.

This will continuously listen for incoming SMS messages and forward them to ChatGPT, which will process the messages and respond via SMS.
Configuration

Adjust the max_tokens and temperature parameters in config.py for more control over response length and creativity.

    max_tokens: Limits the response length.
    temperature: Adjusts creativity; lower values make responses more deterministic.

Example

After connecting your SMS Mobile API account and configuring your environment, ChatGPT can respond to SMS messages with human-like, AI-driven responses. Each SMS reply will also include a small note (optional) indicating it's AI-generated for transparency.
Future Enhancements

    Question/Answer Bot: Create automated Q&A bots via SMS.
    Survey/Feedback Collection: Gather customer feedback through conversational SMS interactions.
    Personalized Notifications: Send personalized, AI-generated notifications based on SMS input.

License

This project is licensed under the MIT License. See the LICENSE file for details.
