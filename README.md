# GreenBank

## Description
GreenBank is a software application designed to manage payment information for clients. It allows users to input and store details about clients, payments, including their balance, completed payments, and awaiting payments. The system also retrieves client information from a separate file and displays payment details for each client.

## Features
1. Input and storage of payment information.
2. Retrieval of client information from a file.
3. Display of payment details for each client, including balance, completed payments, and awaiting payments.
4. Dynamic memory allocation for efficient storage of payment details.
5. Error handling for file operations and memory allocation to ensure robustness and reliability.

## Dynamic Programming
Dynamic programming is employed in this system for efficient memory allocation and management. Specifically, dynamic memory allocation is used to allocate memory for storing payment details such as completed payments and awaiting payments. This approach allows the system to allocate memory dynamically based on the number of payments, optimizing memory usage and improving performance.

## Project Structure
- `main.c`: Contains the main program logic, including functions for reading payment information from a file, retrieving client information, and displaying payment details.
- `newclient.h`: Header file containing function prototypes for adding new clients to the system.
- `payments.txt`: Input file containing payment information.
- `client_data.txt`: Input file containing client information.
- `README.md`: Readme file providing an overview of the project, its features, and structure.

## How to Use
1. Compile the program using a C compiler.
2. Ensure that `payments.txt` and `client_data.txt` files are present in the project directory and contain valid data in the expected format.
3. Run the compiled executable.
4. The program will read payment information and client data, display payment details for each client, and terminate.

## Dependencies
- Standard C libraries: `stdio.h`, `string.h`, `stdlib.h`
- Windows-specific libraries: `windows.h`, `conio.h`

## Contributors
- [Ilea Cosmin Ionut](https://github.com/pierpatrat)
- [Rus Ioan Vasile](https://github.com/ioanrus)

## Acknowledgements
- The developers of standard C libraries.
- OpenAI for providing the language model used to generate this readme.
