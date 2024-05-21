## Overview
Chatgpt clone where users can chat and receive response from Open Ai.

## Project Structure

### Server
Located in the `server/` directory:
- [server.js](/Massive-Code-AI/server/server.js#1%2C1-1%2C1): Main server file that handles API requests and integrates with OpenAI.
- [package.json](/Massive-Code-AI/server/package.json#1%2C1-1%2C1): Contains metadata and dependencies for the server.

### Client
Located in the `client/` directory:
- [index.html](/Massive-Code-AI/client/index.html#1%2C1-1%2C1): Main HTML file for the client interface.
- [style.css](/Massive-Code-AI/client/style.css#1%2C1-1%2C1): Styles for the client interface.
- [script.js](/Massive-Code-AI/client/script.js#1%2C1-1%2C1): JavaScript for handling UI interactions and API communication.
- [assets/](/Massive-Code-AI/client/index.html#20%2C41-20%2C41): Contains images and icons used in the client.

## Setup and Installation

### Prerequisites
- Node.js installed on your machine.
- An API key from OpenAI.

### Server Setup
1. Navigate to the [server](/Massive-Code-AI/server) directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the `server` directory and add your OpenAI API key:
   ```plaintext
   OPENAI_API_KEY=your_openai_api_key_here
   PORT=5000
   ```
4. Start the server:
   ```bash
   npm start
   ```

### Client Setup
1. Navigate to the `client` directory.
3. Open `index.html` in a web browser to access the client interface.

## Usage
- Open the client web interface.
- Type a query into the textarea and press the send button or hit enter.
- The query will be sent to the server, which processes it using OpenAI's API and returns a response.
- The response will be displayed in the client interface.

## Technologies Used
- **Backend**: Node.js, Express, OpenAI
- **Frontend**: HTML, CSS, JavaScript


