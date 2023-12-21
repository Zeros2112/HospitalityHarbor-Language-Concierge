# HotelBot Application Features

The HotelBot application is a Flask-based chatbot that simulates interaction with a hotel assistant. Below are the key features and functionalities of the application:

## 1. Conversation with HotelBot

Users can engage in a conversation with the HotelBot by entering text into the provided input box. The chatbot responds in a welcoming and persuasive manner, providing information about the hotel and encouraging visitors to book a stay.

## 2. Dynamic Display with Panel

The application dynamically displays the user's input and the corresponding assistant's response using Panel, allowing users to see the conversation history in a visually appealing and interactive format.

## 3. OpenAI GPT-3.5 Integration

HotelBot leverages OpenAI's GPT-3.5 language model to generate responses. The `get_completion_from_messages` function sends messages to the GPT-3.5 model, which then returns responses in a natural language format.

## 4. User Commands

HotelBot responds to various user commands related to the hotel, including inquiries about amenities, room rates, nearby attractions, best time to visit, special offers, room options, and more. The responses are designed to be concise, informative, and engaging.

## 5. Sample Hotel Details

The application includes sample hotel details such as the hotel name, location, description, contact information, room rates, amenities, special offers, additional information, and details about the on-site restaurant.

## 6. Interactive Web Interface

HotelBot provides an interactive web interface where users can input their queries and receive responses in real-time. The application uses Flask to handle HTTP requests and render dynamic content.

## Getting Started

To run the HotelBot application locally, follow the instructions in the [README](README.md) file. Make sure to set up your OpenAI API key and install the required dependencies.

Feel free to explore the code in the `app.py` file to understand the implementation details and customize the application to suit your specific needs.

## Future Enhancements

While the current version of HotelBot provides a basic chatbot experience, there are several opportunities for enhancement. Future updates could include:

- Integration with a database for storing real hotel data.
- Improved user interface with additional styling and responsiveness.
- Expansion of the conversation context to handle more complex interactions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

