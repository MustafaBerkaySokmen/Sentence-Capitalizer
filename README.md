# Sentence Capitalizer

## Overview
The **Sentence Capitalizer** is a Python-based program that capitalizes the first letter of sentences and ensures proper capitalization of names within a given text. It considers specific punctuation marks to determine sentence boundaries and a list of proper names to be capitalized correctly.

## Features
- Capitalizes the first letter of each sentence.
- Recognizes sentence boundaries based on punctuation marks.
- Ensures proper capitalization of given names.
- Handles multiple sentences in a single input string.

## Installation
To run this project, ensure you have **Python 3.x** installed on your system.

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/sentence-capitalizer.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd sentence-capitalizer
   ```
3. **Run the script:**
   ```bash
   python SentenceCapitalizer.py
   ```

## Usage
1. The program contains one primary function:
   - `capitalizer(sentences, punctuations, names)`: Capitalizes the first letter of each sentence and ensures that names are properly capitalized.
2. Users can modify the input string (`sentences`), punctuation list (`punctuations`), and names list (`names`) in the `main()` function to test different inputs.
3. Running the script prints the capitalized version of the input text.

## Example Output
```
Input:  "hello, my name is joe. what is your name? my name is john."
Output: "Hello, my name is Joe. What is your name? My name is John."
```

## License
This project is licensed under the **MIT License**.

## Contributions
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`feature-new-feature`).
3. Commit and push your changes.
4. Open a pull request.

## Contact
For any questions or support, please open an issue on GitHub.

