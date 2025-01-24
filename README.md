# Rasa Chatbot for Personalized Learning in AI and ML

**Description:**  
This project is a conversational AI chatbot developed using Rasa Open Source. It is designed to assist users in the AI and machine learning educational domain by understanding user intents and providing appropriate responses. The chatbot aims to help learners by answering questions, providing explanations, and guiding them through various AI-ML concepts and topics. For more details, visit the [GitHub repository](https://github.com/Thrinadh-13/Chatbot_for_Personalized_Learning).

---

## Features

- **Custom Trained Model**: Uses machine learning to understand user intents and extract entities.  
- **Domain-Specific Knowledge**: Tailored for [specific domain or use case].  
- **Multi-Intent Handling**: Capable of understanding and responding to complex queries.  
- **Integration Ready**: Easily integrates with platforms like Telegram, Slack, or a custom website.  

---

## Installation

### Prerequisites:
1. Python 3.8 or later  
2. Rasa Open Source  
3. Virtual environment (recommended)

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Thrinadh-13/AI-ML-CHATBOT
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-ML-CHATBOT
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # For Linux/Mac
   .venv\Scripts\activate  # For Windows
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Train the Model

1. Edit your `nlu.yml`, `stories.yml`, and `domain.yml` files as needed.  
2. Train the model:
   ```bash
   rasa train
   ```
3. The trained model will be saved in the `models/` directory.

---

## Running the Bot

### In Shell:
Run the bot on the command line:  
```bash
rasa shell
```

### As a Server:
Run the bot as a server:  
```bash
rasa run
```

---

## Files and Directories

- **`data/`**: Contains training data for intents and stories.  
- **`domain.yml`**: Defines the intents, entities, actions, and responses.  
- **`models/`**: Stores the trained models.  
- **`actions/`**: Contains custom action scripts.  
- **`config.yml`**: Configuration for pipelines and policies.  

---

## Future Enhancements

1. Add support for feature enhance.  
2. Improve training data for better intent classification.  
3. Extend functionality to include integration with external APIs.  

---

## License

Include the relevant licensing information for your project.

---

## Contributors

List the contributors, including yourself. Example:  
- LEAD DEV- Ch.Thrinadh

