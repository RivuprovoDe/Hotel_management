# Hotel_management
This project is a Hotel Management application designed to handle operations such as maintaining customer records, booking rooms across four categories, managing food orders for specific rooms, canceling room bookings, and generating bills. It also provides information on room features and current availability.

The system uses a menu-driven interface and continues running until the user chooses to exit. To preserve hotel data—such as customer information, room bookings, and food orders—the program writes all current details to a file upon exit. When launched again, it reads from this file to restore the previous state. File writing is handled in a separate thread to improve performance by running concurrently with other tasks.

A custom exception is raised if a user attempts to book a room that is already occupied, and the program incorporates proper exception handling to manage unexpected errors gracefully.

Key Concepts Used:
Classes and Objects, Inheritance, File Handling with Objects, ArrayList, Interfaces, Custom Exceptions, and Exception Handling.
