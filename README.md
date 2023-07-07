# Error Correcting Encoder Decoder

This program emulates errors occurred in data transmission at the random bit level and corrects the errors that occurred. It uses the Hamming code to encode and decode the data, ensuring reliable data transfer. Hamming code is a set of error-correction codes designed to detect and correct single-bit errors during data transmission.

## Usage

1. Save the data to be encoded in the `send.txt` file.
2. Open the terminal or command prompt.
3. Navigate to the project directory.
4. Run the program using the following command:

   ```bash
   java ECED.java
   ```

5. After the application starts running, you can enter commands in the console to perform different operations:

   - To encode the data, type `encode` and press Enter. The Hamming encoded file will be created as `encoded.txt`.

   - To emulate bit-level errors, type `send` and press Enter. It will use the previously created `encoded.txt` file, emulate errors, and save it as `received.txt`.

   - To decode the corrupted file, type `decode` and press Enter. It will create a file named `decoded.txt` by using the previously created `received.txt` file.

## Prerequisites

- Java 17

## GitHub Repository

The source code for this project is available on GitHub at [Error-Correcting-Encoder-Decoder-Java](https://github.com/Just3a3Cat12/Error-Correcting-Encoder-Decoder-Java).

## Developer

This project was developed by PANKAJ AMBEKAR.

- Email: ambekarpankaj@outlook.com
