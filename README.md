# Playing With GPT

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)
![Flask](https://img.shields.io/badge/Flask-2.0.2-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

## Overview
**Playing With GPT** is a playful yet secure project that interacts with OpenAI's GPT-4 API. The project is built using Python, JavaScript, HTML, and CSS, providing a simple and cohesive interface for generating text based on user input. 

## Project Structure
playingWithGPT/<br>
├── backend/<br>
│ ├── app.py<br>
│ ├── requirements.txt<br>
│ └── utils.py<br>
├── frontend/<br>
│ ├── index.html<br>
│ ├── stlyes<br>
│     └── styles.css<br>
│ ├── scripts<br>
│     └── script.js<br>
├── .gitignore<br>
└── README.md<br>

## Features
- **Backend**: Powered by Flask, it handles API requests and communicates with the GPT-4 API.
- **Frontend**: A simple HTML/CSS/JS interface for users to input prompts and display generated text.
- **Security**: Adheres to security standards, including the use of environment variables for sensitive information.

## Getting Started

### Prerequisites
- Python 3.8+
- Node.js (for potential future enhancements)
- OpenAI API Key

### Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/your-username/playingWithGPT.git
    cd playingWithGPT
    ```

2. **Set up the backend**
    ```sh
    cd backend
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3. **Create a `.env` file in the backend directory**
    ```sh
    echo "OPENAI_API_KEY=your-openai-api-key" > .env
    ```

4. **Run the Flask application**
    ```sh
    python app.py
    ```

5. **Open the frontend**
    - Open `index.html` in your browser.

## Usage

1. Navigate to the frontend directory:
    ```sh
    cd frontend
    ```

2. Open `index.html` in your browser.

3. Enter a prompt in the textarea and click "Generate" to receive a response from GPT-4.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Luis Giovanni Ruiz - [@your_twitter_handle](https://twitter.com/your_twitter_handle) - your_email@example.com

Project Link: [https://github.com/your-username/playingWithGPT](https://github.com/your-username/playingWithGPT)

## Acknowledgments
- [OpenAI](https://www.openai.com/)
- [Flask](https://flask.palletsprojects.com/)
- [GitHub Markdown Badges](https://shields.io/)

