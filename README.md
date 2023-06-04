# Stream Chat App
This is a Flutter chat app that utilizes the Stream API and the stream_chat_flutter package to enable real-time messaging functionality. Users can connect, create channels, and send messages using the Stream Chat service.

# Getting Started
To run the app, follow these steps:

Make sure you have Flutter installed on your machine.
Clone the repository: git clone https://github.com/your-username/chat-app.git
Navigate to the project directory: cd chat-app
Run flutter pub get to install the required dependencies.
Replace the API_KEY and TOKEN values in the main() function with your own Stream Chat API credentials.
Run the app: flutter run

# Features
Channel List Page: Displays a list of chat channels. The list is filtered to show channels where the current user is a member, sorted by the last message timestamp.
Channel Page: Shows the messages of a selected channel. Users can view and send messages in real-time.
Thread Page: Displays a thread of replies to a specific message.
User Authentication: Connects users to the Stream Chat service using a user ID, name, and profile image URL.

# Dependencies
stream_chat_flutter: The official Flutter package for integrating the Stream Chat service into your app.
stream_chat: The underlying package that provides the core functionality for Stream Chat.
# Documentation
Flutter: https://flutter.dev
Stream Chat Flutter Package: https://pub.dev/packages/stream_chat_flutter
Stream Chat API: https://getstream.io/chat/docs
# Contributing
Contributions are welcome! If you find any issues or want to add new features, please submit a pull request.
