# UnitGen: Automated Unit Test Generation With LLMs and RAG

UnitGen leverages Large Language Models (LLMs) and Retrieval-Augmented Generation (RAG) techniques to automatically generate unit tests for your software projects. This tool aims to enhance code quality and development efficiency by providing an automated means to create rigorous, context-aware unit tests.

## Features

- **Automatic Test Generation:** Generate unit tests automatically for specific functions within your codebase.
- **Language Agnostic:** Tested on Python and Java. Should work for most languages.
- **Feedback Driven:**: Uses human and automated LLM feedback to guide test generation.  
- **RAG Driven:** Utilizes LangChain and ChromaDB to understand and create tests that are contextually relevant to the provided source code.

## Installation

1. Clone the repository
2. ...

## Usage

To generate unit tests, run the following command:

```bash
python generate.py --repo_path <path_to_repository> --tests_path <path_to_tests_directory> --language <programming_language>
```

### Parameters

- `repo_path`: Path to the local repository where the source code is located.
- `tests_path`: Directory where the generated tests will be saved and executed.
- `language`: Programming language of the source code (e.g., Python, JavaScript).

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

Distributed under the MIT License. See LICENSE for more information.
