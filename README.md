# Customer Support Chatbot with Sentiment Analysis and Question Answering

## Overview

This solution implements an advanced customer support chatbot that combines sentiment analysis and question answering capabilities to provide more empathetic and accurate responses to user queries. The chatbot utilizes two pre-trained models:

1. **DistilBERT** for sentiment analysis: This model analyzes the emotional tone of the user's input, allowing the chatbot to tailor its responses accordingly.

2. **RoBERTa** for question answering: This model generates accurate answers to user questions based on a provided context.

The chatbot's workflow is as follows:

1. The user inputs a question or statement.
2. The sentiment analysis model determines the emotional tone of the input.
3. The question answering system searches for an answer in a predefined dataset.
4. If no matching answer is found, the RoBERTa model generates a response based on the available context.
5. The final response is adjusted based on the detected sentiment, adding empathetic phrases for negative sentiments or enthusiastic ones for positive sentiments.
6. The interaction is added to the dataset for future reference.

This approach allows for a more natural and context-aware conversation, improving the user experience in customer support scenarios. The solution is implemented using Python and popular libraries such as Transformers and Gradio, making it easily deployable and customizable for various customer support needs.

## Key Features

- Sentiment-aware responses
- Dynamic question answering
- Expandable knowledge base
- User-friendly Gradio interface
- Easily adaptable to different domains

By combining these technologies, this chatbot provides a more sophisticated and empathetic customer support experience, potentially improving customer satisfaction and reducing the workload on human support staff.
