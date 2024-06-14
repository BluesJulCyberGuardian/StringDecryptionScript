StringDecryptionScript

## Overview
This Ghidra script identifies and decrypts common encrypted strings in binaries. It supports multiple decryption algorithms, such as XOR and Base64.

## Features
- Automatically scans for potential encrypted strings.
- Attempts decryption using multiple algorithms.
- Displays decrypted strings within a text file.

## Usage
1. Install Ghidra 11.3 or 11.1 and set up the GhidraDev environment.
2. Download the script and place it in your Ghidra scripts directory.
3. Run the script from within Ghidra.

## Algorithms Supported
- XOR
- Base64

## Example
1. Load a binary in Ghidra.
2. Run the "String Decryption Script."
3. View decrypted strings in the console output.

## Tutorial Video
(https://www.youtube.com/watch?v=qlM6dWgRk0g)

## Contribution
Feel free to fork the project and submit pull requests. Your contributions are welcome!

## License
This project is licensed under the MIT License.
