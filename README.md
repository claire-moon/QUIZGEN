Generates quizzes. Kind of like magic.

===

# README.md for Quiz Generator

## Quiz Generator

This project is a simple terminal application that generates trendy and humorous quizzes for uQuiz.com using an open-source language model (LLM). The application prompts the user for the number of quizzes to generate, a topic, and a style/tone, and then produces formatted quizzes ready for use on uQuiz.com.

### Features

- Generate multiple quizzes based on user-defined parameters.
- Utilize an open-source LLM to create engaging quiz content.
- Automatically search for relevant images for each quiz question and main quiz image.
- Output each quiz into its own text file, formatted for easy copy/pasting into uQuiz.com.

### Project Structure

```
quiz-generator
├── src
│   ├── main.py          # Entry point of the application
│   ├── llm              # Package for LLM interaction
│   │   ├── __init__.py
│   │   └── model.py
│   ├── quiz             # Package for quiz generation
│   │   ├── __init__.py
│   │   ├── generator.py
│   │   └── formatter.py
│   ├── image            # Package for image searching
│   │   ├── __init__.py
│   │   └── searcher.py
│   └── utils            # Utility functions
│       ├── __init__.py
│       └── io.py
├── requirements.txt     # Project dependencies
├── .env                 # Environment variables
└── README.md            # Project documentation
```

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd quiz-generator
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables in the `.env` file as needed.

### Usage

To run the quiz generator, execute the following command in your terminal:
```
python src/main.py
```

Follow the prompts to input the number of quizzes, the topic, and the desired style/tone. The generated quizzes will be saved as text files in the project directory.

### Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.