# EncryptDecryptCode
 
# Caesar Cipher GUI
The Caesar Cipher GUI is a Java-based graphical user interface application that allows users to encrypt and decrypt text using the Caesar cipher encryption technique. It provides an intuitive and interactive way to perform text encryption and decryption operations.

## Features
- **User-Friendly Interface**: The GUI features a well-designed user interface with separate sections for input, output, and control buttons.
- **Shift Selection**: Users can select the desired shift value from a dropdown menu to determine the level of encryption or decryption.
- **Encryption and Decryption**: The application supports both text encryption and decryption. Users can input text in the provided text field and choose to either encrypt or decrypt it.
- **Real-Time Updates**: The output field provides real-time updates as the user interacts with the application. Encrypted or decrypted text is displayed instantly.

## Getting Started
To run the Caesar Cipher GUI application, follow these steps:
1. **Download the Code**: Clone or download the code from the repository to your local machine.
2. **Prerequisites**: Ensure that you have a Java Development Kit (JDK) installed on your computer.
3. **Import the Project**: If you're using an Integrated Development Environment (IDE) such as Eclipse, import the project into your workspace.
4. **Run the Application**: Execute the `Executor.java` class to launch the GUI.
5. **Select Shift Value**: Choose the desired shift value from the dropdown menu.
6. **Input Text**: Enter the text you want to encrypt or decrypt in the input text field.
7. **Perform Encryption/Decryption**: Click the "Encrypt" or "Decrypt" button to process the text.
8. **View Results**: The results of the encryption or decryption operation will be displayed in the output text field.

## Usage
The Caesar Cipher GUI is a useful tool for learning about the Caesar cipher encryption technique and experimenting with different shift values. You can use it to:
- Encrypt sensitive information for added security.
- Decrypt Caesar cipher messages when you know the shift value.
- Understand how changes in the shift value affect the encryption or decryption process.

# TestCaesarCipher Class
The `TestCaesarCipher` class is a Java program that serves as the entry point for running the Caesar Cipher GUI application. It initializes the GUI and displays it to the user, allowing them to perform text encryption and decryption using the Caesar cipher encryption technique.

## Usage
To run the Caesar Cipher GUI application using the `TestCaesarCipher` class:
1. **Execution**: Execute the `TestCaesarCipher` class, either from an Integrated Development Environment (IDE) or by running it through the command line with the appropriate Java command.
2. **GUI Initialization**: The `TestCaesarCipher` class creates an instance of the `CaesarCipherGui` class, initializing the graphical user interface.
3. **Display the GUI**: The `displayFrame()` method of the `CaesarCipherGui` instance is called to display the GUI to the user.
4. **Interaction**: Once the GUI is displayed, users can interact with it to perform text encryption and decryption as described in the Caesar Cipher GUI README.

## Integration with Caesar Cipher GUI
The `TestCaesarCipher` class is an essential component for launching and testing the Caesar Cipher GUI. It allows users to interact with the GUI and utilize its features seamlessly.
