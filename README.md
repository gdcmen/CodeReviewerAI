# AI Assisted Software Testing Tool

Welcome to the AI Assisted Software Testing Tool repository! This tool is designed to help developers analyze their code for syntax errors and receive AI-driven suggestions for improvement.

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- Python 3
- [Transformers library](https://github.com/huggingface/transformers)
- [Tkinter library](https://docs.python.org/3/library/tkinter.html)
- [G++ compiler](https://gcc.gnu.org/)

You can install the required Python libraries using the following command:

```bash
pip install transformers
```

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/ai-testing-tool.git
cd ai-testing-tool
```

## Usage

1. Run the `Interpreter.py` file to launch the graphical user interface (GUI).
2. Enter your code in the provided text area or load it from a file using the "Load Code from File" button.
3. Click the "Analyze Code" button to perform a syntax check and receive AI recommendations.
4. Save the analyzed code or make necessary corrections based on the provided suggestions.

## Components

### 1. Interpreter

The `Interpreter.py` file contains the GUI implementation using the Tkinter library. It allows users to input code, analyze it, and view the results.

### 2. CodeChecker

The `CodeChecker.py` module includes the `CodeChecker` class responsible for analyzing code for syntax errors and providing AI-driven suggestions. It utilizes the Microsoft CodeReviewer model from the Transformers library.

### 3. FileHandler

The `FileHandler.py` module contains functions for reading code from a file. It is used by the `Interpreter.py` file to load code for analysis.

## Example

```python
# Analyzing code...
# Syntax error: temp.cpp:6:5: error: 'cout' was not declared in this scope; did you mean 'std::cout'?
# AI Suggestion for error at line 6: Review and fix the code based on the reported syntax error.
# AI analysis completed.
# Analysis completed.
```

## Requirements

The AI Assisted Software Testing Tool streamlines code analysis, detecting syntax errors and offering intelligent suggestions for improvement. With an intuitive Tkinter-based interface, it enhances the coding experience by providing quick and actionable insights.

Requirements
Ensure your environment is set up with the necessary dependencies. Install the required Python modules using the provided requirements.txt file:

```bash
pip install -r requirements.txt
```
Here is the list of modules included in the requirements.txt file:

```bash
aiohttp==3.8.6
aiosignal==1.3.1
async-timeout==4.0.3
attrs==23.1.0
certifi==2023.7.22
charset-normalizer==3.3.0
colorama==0.4.6
filelock==3.13.1
frozenlist==1.4.0
fsspec==2023.12.0
huggingface-hub==0.19.4
idna==3.4
multidict==6.0.4
numpy==1.26.2
openai==0.28.1
packaging==23.2
pandas==2.1.1
protobuf==4.25.1
python-dateutil==2.8.2
pytz==2023.3.post1
PyYAML==6.0.1
regex==2023.10.3
requests==2.31.0
safetensors==0.4.1
sentencepiece==0.1.99
six==1.16.0
tensorboardX==2.6.2.2
tokenizers==0.15.0
tqdm==4.66.1
transformers==4.35.2
typing_extensions==4.8.0
tzdata==2023.3
urllib3==2.0.7
yarl==1.9.2
```

## Contributing

We welcome contributions from the community! If you find any issues or have suggestions for improvements, please open an [issue](https://github.com/your-username/ai-testing-tool/issues) or submit a [pull request](https://github.com/your-username/ai-testing-tool/pulls).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding! 🚀
