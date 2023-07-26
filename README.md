# Whatsapp Chat Analyzer

"Whatsapp Chat Analyzer" is a Python-based project for analyzing and visualizing WhatsApp chat data with an interactive web interface.

## Live Demo
Experience the "Whatsapp Chat Analyzer" in action by checking out our Live Demo: [here](https://whatsapp-chat-analyzer-zgkf.onrender.com/).

## Overview

The aim of this project is to provide users with a convenient way to gain insights into their WhatsApp conversations. By parsing the chat data, the analyzer can extract various statistics and generate visualizations to help users understand their communication patterns.

## Features

- **Chat Data Parsing**: The analyzer can read and parse WhatsApp chat export files, extracting relevant information such as message timestamps, sender names, and message content.

- **Message Count**: It calculates the total number of messages exchanged in the chat and provides a breakdown of messages sent by each participant.

- **Top Contributors**: Identifies the most active participants in the conversation based on the number of messages sent.

- **Timeline Analysis**: Presents a timeline of message activity, allowing users to visualize when the chat was most active.

- **Word Clouds**: Generates word clouds to highlight the most frequently used words in the chat.

- **Emojis and Media Analysis**: Analyzes the usage of emojis and media (images, videos, etc.) in the conversation.

- **Interactive Web Interface**: Provides a user-friendly web interface to interact with and explore the chat analysis results.


## Usage

1. Export the WhatsApp chat you want to analyze as a .txt file:
- Open the WhatsApp conversation you want to analyze.
- Tap the three dots in the top-right corner.
- Select "More" and then "Export chat."
- Choose whether to export the chat "Without Media" or "Include Media."
- Select your preferred method to share the chat file (e.g., email, cloud storage).

2. Place the exported file in the "data" folder of the [project](https://whatsapp-chat-analyzer-zgkf.onrender.com/).

3. Run the chat analyzer script in your terminal or command prompt:

4. After the analysis is complete, the interactive web interface will be available at `http://localhost:5000` in your web browser. You can explore the various visualizations and statistics generated from the chat data.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open a pull request or submit an issue on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
