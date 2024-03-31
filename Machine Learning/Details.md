# Summary of machine learning models used in the project 

## Task Priority Predictor Model

### Overview
The Task Priority Predictor Model is a model trained to predict the priority level of tasks based on their titles and the number of people working on them. This model assists in task management by suggesting priority levels for better resource allocation and time management.

### Model Architecture
The model architecture consists of two main components:
1. Text Input Layer: Processes task titles using tokenization and embedding.
2. Numerical Input Layer: Scales the number of people working on a task for numerical input.

These components are combined into a neural network architecture for prediction.

### Usage
To use the Task Priority Predictor Model, follow these steps:

1. **Input Task Title**: Enter the title of the task you want to prioritize.
2. **Input Number of People**: Specify the number of people working on the task.

The model will then predict the priority level of the task based on the provided inputs.



________________________________________________________________


## Interactive Chat Box Virtual Assistant

### Overview
The Interactive Chat Box Virtual Assistant is a simple chat bot designed to engage in conversations with users, providing responses based on predefined intents. It utilizes natural language processing (NLP) techniques and a neural network model to understand user queries and generate appropriate responses.

### Implementation Details
The virtual assistant is implemented using Python and TensorFlow/Keras for building and training the neural network model. Here's a breakdown of the implementation steps:

1. **Data Preparation**: Load the intents data from a JSON file containing patterns and corresponding intent tags and responses.
2. **Text Preprocessing**: Tokenize input text and lemmatize words to prepare them for model input.
3. **Feature Extraction**: Convert text input into a bag-of-words representation, encoding each word as a binary feature.
4. **Model Training**: Train a neural network model using a Sequential architecture with Dense layers and Dropout regularization.
5. **Prediction**: Use the trained model to predict the intent class for user queries and select a response based on the predicted intent.
6. **User Interaction**: Enable users to input messages and interact with the virtual assistant in a chat-like interface.

### Dependencies
- Python: Programming language used for implementation.
- TensorFlow: Deep learning framework used for building and training the neural network model.
- NLTK: Natural Language Toolkit used for text preprocessing and tokenization.

### Usage
1. **Start the Chat Box**: Run the Python script containing the virtual assistant code.
2. **Enter Queries**: Type your queries or commands into the chat box interface.
3. **Receive Responses**: The virtual assistant will process your query and provide a response in the chat box.

### Customization
- Intents and responses can be customized by modifying the JSON file containing the intent data.
- Additional training data can be provided to improve the virtual assistant's understanding and response accuracy.

### Future Enhancements
- Integration with external APIs for accessing real-time information (e.g., weather forecasts, news updates).
- Support for more sophisticated natural language understanding techniques, such as intent classification with context awareness.
- Enhanced conversational capabilities, including multi-turn dialog management and memory of previous interactions.
