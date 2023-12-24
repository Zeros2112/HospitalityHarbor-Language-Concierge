# HospitalityHarbor Language Concierge

Welcome to the HotelBot Flask Application! This Flask application uses OpenAI's GPT-3.5 language model to create a chatbot that simulates interaction with a hotel assistant.

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.x
- [pip](https://pip.pypa.io/en/stable/installation/)
- [virtualenv](https://virtualenv.pypa.io/en/latest/installation/) (optional but recommended)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Zeros2112/hotel_assistant_langchain_chatbot.git


2. Navigate to the project directory
   cd hotelbot-flask

3. Create a virtual environment
   python -m venv venv

4. Activate the virtual environment
   * On windows: venv\Scripts\activate
   * On macOS/Linus: source venv/bin/activate

5. Install dependencies
   pip install -r requirements.txt

6. Create a .env file in the project directory and add your OpenAI API key
   OPENAI_API_KEY=your_openai_api_key_here

7. Run the Flask application
   python app.py

8. Open your web browser and navigate to http://127.0.0.1:5000/.

## Customization 
Feel free to explore the app.py file to understand the implementation details and customize the application to meet your specific requirements.

## Future Enhancements 
Potential future enhancements for HotelBot could include integrating a database for real hotel data, improving the user interface, and expanding the conversation context for more complex interactions.

## License 
This project is licensed under the MIT License.
