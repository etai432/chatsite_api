# Chat Blog Site API

Welcome to the Chat Blog Site API repository! This API serves as the backend for the Chat Blog Site project, providing fast and efficient data processing for the chat-like interface.

## Features

- Real-time messaging: Handle and process messages in real-time.
- Database interaction: Manage interactions with the MySQL database for message storage.
- Rust implementation: Built with Rust for high performance and reliability.

## Technologies Used

- Backend: Rust
- Database: MySQL

## Getting Started

1. Clone the repository: `git clone https://github.com/your-api-repo.git`
2. Install dependencies: `cd your-api-repo && cargo build`
3. Start the API: `cargo run`
4. The API will start and listen for requests on the specified port.

## API Endpoints

- `/messages`: POST to send a new message.
- `/messages/<index>`: GET to retrieve all messages sent after `<index>`
