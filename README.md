# Chat GPT Flutter

## Overview

**Chat GPT Flutter** is an innovative mobile application that seamlessly integrates Flutter with the APIs of Chat GPT. This powerful application allows users to engage in natural language conversations with Chat GPT, providing a smooth and intuitive chat experience. Leverage the capabilities of Chat GPT to enhance your app's communication and interaction.

<img src="assets/image/images.jpg" width="100%">

## Features

- **Chat Interface:** Utilizes the `dash_chat_2` library for a feature-rich and customizable chat interface.
- **Chat GPT Integration:** Leverages the `chat_gpt_sdk` library (version 2.2.5) to seamlessly connect Flutter with Chat GPT APIs.
- **Natural Language Processing:** Engage in natural, human-like conversations with Chat GPT for a more interactive user experience.

## Getting Started

### Prerequisites

- Ensure you have Flutter and Dart installed on your development environment.

### Installation

1. Add dependencies to your `pubspec.yaml` file:

    ```yaml
    dependencies:
      dash_chat_2: ^0.0.18
      chat_gpt_sdk: ^2.2.5
    ```

2. Run the following command in your terminal:

    ```bash
    flutter pub get
    ```

### Usage

1. Import the libraries in your Dart file:

    ```dart
    import 'package:dash_chat_2/dash_chat_2.dart';
    import 'package:chat_gpt_sdk/chat_gpt_sdk.dart';
    ```

2. Initialize the Chat GPT SDK with your API key:

    ```dart
    ChatGPT.initialize(apiKey: 'YOUR_API_KEY');
    ```

3. Implement the chat interface using `DashChat` from the `dash_chat_2` library:

    ```dart
    DashChat(
      messages: _messages,
      onSend: _onSend,
      user: _user,
    )
    ```

4. Use the `chat_gpt_sdk` to send and receive messages:

    ```dart
    // Sending a message to Chat GPT
    final response = await ChatGPT.sendMessage(message: 'Hello, Chat GPT!');

    // Receiving a response from Chat GPT
    final chatGPTResponse = response['message'];
    ```

## Customization

### Dash Chat 2

Customize the chat interface using the extensive customization options provided by the `dash_chat_2` library. Refer to the [dash_chat_2 documentation](https://pub.dev/packages/dash_chat_2) for details.

### Chat GPT SDK

Explore additional functionalities and customization options available in the `chat_gpt_sdk` library. Refer to the [chat_gpt_sdk documentation](https://pub.dev/packages/chat_gpt_sdk) for detailed usage instructions.

## Contributing

We welcome contributions! If you have ideas for improvement, open an issue or submit a pull request. For major changes, please discuss them first in an issue to ensure they align with the project's goals.

## Happy Chatting! 🚀

### <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"> Follow me :

<div id="badges">
<a href="https://abdurlahmanhatem.vercel.app/">
    <img src="https://img.shields.io/badge/Website-9cf?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Profile "/>
  </a>
  
  <a href="https://www.linkedin.com/in/abdulrahman-hatem-64780a210">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://twitter.com/Abdelra87827997">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
   <a href="https://www.youtube.com/@AlHatemSoftware">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  
</div>


