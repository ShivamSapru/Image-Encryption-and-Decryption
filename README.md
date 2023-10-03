# Image-Encryption-and-Decryption

The project "Image Encryption and Decryption“ is a Java Swing application that aims to provide a simple and interactive user interface for encrypting and decrypting image files using XOR-based encryption techniques. The application allows users to select an image file, enter a secret key, and then perform encryption or decryption operations on the selected image file. The encrypted image can be saved as a new file, while the decrypted image is displayed on the screen.

# Project Objectives
The main objectives of the project are as follows:
1. Develop a user-friendly GUI using Java Swing for image encryption and decryption operations.
2. Implement a simple XOR-based encryption technique for securing the images.
3. Allow users to select an image file from the file system using a file chooser dialog.
4. Enable users to enter a secret key for encryption and decryption operations.
5. Provide options to save the encrypted image as a new file and display the decrypted image on the screen.
6. Handle exceptions and errors effectively during file I/O operations and input validation.


# Technologies Used
1. Python: As the core programming language for developing the application logic.
2. Java Swing: For creating the graphical user interface (GUI) components, such as buttons, text fields, and dialogs.
3. File I/O: For reading and writing image files from/to the file system.
4. XOR Encryption: For implementing the encryption and decryption operations using a simple XOR-based technique.

# System Design
The system design of the project involves the following components:
1. User Interface: The GUI is designed using Java Swing components, including a JFrame window, buttons, text fields, and dialogs. The layout manager is used to arrange the components in a visually appealing and responsive manner.
2. Encryption and Decryption Logic: The encryption and decryption operations are implemented using a simple XOR-based technique, where each byte of the image data is XORed with the corresponding byte of the key. The encryption and decryption logic is encapsulated in methods that are invoked by event handlers when the user interacts with the GUI.
3. File I/O Operations: The application uses File I/O operations, such as FileInputStream and FileOutputStream, to read and write image files from/to the file system. Exception handling is done to handle potential errors, such as file not found, I/O errors, and invalid input.

# Project WorkFlow
1. The user launches the application and the main window is displayed.
2. The user selects an image file from the file system using the "Open" button and the file chooser dialog.
3. The selected image file is displayed on the screen.
4. The user enters a secret key in the text field.
5. The user clicks the "Encrypt" or "Decrypt" button to perform the respective operation.
6. The application reads the image data from the selected file using FileInputStream and performs XOR-based encryption or decryption on the data.
7. The encrypted or decrypted data is written back to the same file using FileOutputStream.
8. The decrypted image is displayed on the screen.
9. The user can perform multiple encryption and decryption operations in the same session.

# Testing and Validation
The project is thoroughly tested to ensure its functionality, reliability, and robustness. Various test cases are designed and executed to validate the following aspects:

1. Proper handling of user input, including invalid key values and file selection.
2. Correct encryption and decryption operations, verifying the integrity of the image data.
3. Accurate display of the encrypted and decrypted images on the screen.
4. Correct saving of the encrypted image as a new file without data loss.

## Thank You

