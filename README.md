# Chef Claude

Chef Claude is a web-based application designed to assist users in generating creative and personalized recipes using AI. By leveraging the power of Anthropic's Claude API, Chef Claude provides users with unique culinary ideas tailored to their preferences.

## Features

- Generate custom recipes based on user input.
- Explore creative meal ideas with the help of AI.
- Simple and intuitive user interface built with React.

## Getting Started

Follow these steps to set up and run Chef Claude on your local machine.

### Prerequisites

1. **Node.js**: Ensure you have Node.js installed on your system. You can download it from [Node.js Official Website](https://nodejs.org/).
2. **Anthropic API Key**: Obtain an API key from [Anthropic](https://www.anthropic.com/). This is required to access the Claude API.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jacutlip/chef-claude.git
    cd chef-claude
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your Anthropic API key:
    ```plaintext
    VITE_ANTHROPIC_API_KEY=your_api_key_here
    ```

4. Start the development server:
    ```bash
    npm run dev
    ```

5. Open your browser and navigate to `http://localhost:5173` to use the application.

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you like.

## Acknowledgments

Special thanks to the React community for their excellent resources and tools.
