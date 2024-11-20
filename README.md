# Caesar Cipher Decryption Tool

A simple web-based tool to decrypt Caesar Cipher text. The tool tries all possible shifts (from 1 to 25) and returns all potential decrypted texts, sorted by the number of matching words from a provided word list.

## Features
- **Caesar Cipher Decryption**: Automatically decrypts the cipher text by trying all possible shifts.
- **Word Matching**: Compares decrypted text against a word list to find the best matching results.
- **Interactive UI**: Easy-to-use web interface where users can enter cipher text and view results.

## Demo
You can view the live tool [here](https://abdulsaheel.github.io/caesar-cipher-decryption-tool).

## How It Works
1. **Enter Cipher Text**: Input the Caesar cipher text into the provided text box.
2. **Decrypt**: Click the "Decrypt" button to automatically attempt all 25 shifts and display the possible decrypted results.
3. **Word Matching**: The tool will compare the decrypted text with a word list and show the results with the highest match count first.

## Prerequisites

Before running the tool, ensure you have the following:

- A web server or local server environment (e.g., using `live-server` for local testing).
- A valid word list (`words.txt`) containing a large number of words, which will be used to match and validate the decrypted outputs.

## Getting Started

To use the tool locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/abdulsaheel/caesar-cipher-decryption-tool.git
    cd caesar-cipher-decryption-tool
    ```

2. Make sure to have a `words.txt` file in the root directory of the project or update the `wordListUrl` in the `script.js` file to point to a valid word list URL.

3. Open the `index.html` file in your browser
      ```

## Files in the Project

- `index.html`: The main HTML structure and styling of the Caesar Cipher Decryption Tool.
- `style.css`: Embedded CSS for styling the tool.
- `script.js`: JavaScript code that handles decryption, word matching, and fetching the word list.
- `words.txt` (optional): A word list file containing a list of words for comparison in lowercase (ensure it's in the same directory or update the URL to point to its location).

## How to Use the Tool

1. Open the page in your browser.
2. Input your cipher text into the provided text box (e.g., "BYCYJ IQBJ QCEDW SQIX").
3. Press the **Decrypt** button.
4. View all possible decryptions with matching word counts under the “Possible Decryptions” section.

## Customizing the Word List
You can update the word list (`words.txt`) by adding or removing words. Make sure each word is separated by a newline and is in lowercase for accurate matching.

To update the list:
1. Edit the `words.txt` file with your desired words.
2. Ensure the list is accessible via the URL or hosted locally as described above.

## Contribution

If you'd like to contribute to this project, feel free to open a pull request. Here are a few ways you could help:
- Adding more features (e.g., support for other ciphers).
- Improving the UI or adding accessibility features.
- Fixing bugs or enhancing performance.



## Acknowledgments

- **Caesar Cipher**: For the cryptography algorithm used in this tool.
- **Google Fonts**: For providing the fonts used in the UI.


