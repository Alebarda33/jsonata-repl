# JSONata Web Application

This project is a simple web application that allows users to input JSON data and JSONata queries, and see the results immediately. It is built using HTML, CSS, and JavaScript with the help of the CodeMirror library for syntax highlighting and the JSONata library for query processing.

## Features

- **Real-Time Evaluation**: Automatically processes JSONata queries and displays results as you type or modify the JSON data.
- **Syntax Highlighting**: Uses the CodeMirror library to provide syntax highlighting for JSON and JSONata queries.
- **Responsive Design**: The layout is designed to be flexible and adjust to different screen sizes.

## Getting Started

### Prerequisites

You need a web browser to run this application. There are no other dependencies or installations needed.

### Running the Application

1. **Clone the Repository**: Download the source code to your local machine.

    ```bash
    git clone https://github.com/albarulin/jsonata-repl.git
    cd jsonata-repl
    ```

2. **Open the Application**: Open the `index.html` file in your web browser.

    You can simply double-click the `index.html` file, or right-click and choose "Open with" and select your preferred web browser.

### Using the Application

- **JSON Input**: Enter your JSON data in the left panel.
- **JSONata Query**: Write your JSONata query in the middle panel.
- **Result**: The result of the query will be displayed in the right panel.

The application will automatically process the input and display the result as you type.

## Built With

- **[CodeMirror](https://codemirror.net/)** - A versatile text editor implemented in JavaScript for the browser.
- **[JSONata](https://jsonata.org/)** - A lightweight query and transformation language for JSON data.

## Contributing

Feel free to submit issues or pull requests for bug fixes and improvements. For major changes, please open a discussion first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the [try.jsonata.org](https://try.jsonata.org/) online tool.