This project is a dual-format clock application that supports both 12-hour and 24-hour time displays. It was developed to meet the international standard (ISO 8601) required by Chada Tech, providing a flexible tool for a global user base. The program features a user-friendly menu for adding time (hours, minutes, seconds) and updating the display in real-time.

# Key Features in This project:
* Object-Oriented Design: Implemented a robust Clock class to encapsulate time-keeping logic, ensuring modularity and code reusability.
* Dual Time Formats: Simultaneously displays time in both 12-hour (with AM/PM) and 24-hour formats to serve a diverse user base.
* Interactive User Interface: Provides a menu-driven interface, allowing the user to add time or exit the program via simple input.
* Adaptable Architecture: Separates display logic from manipulation logic, which simplifies future modifications and feature additions.

# Technical Skills that were Demonstrated:
* Object-Oriented Programming (OOP): Designed and implemented a Clock class with dedicated member functions, demonstrating strong principles of encapsulation.
* Control Flow and Complex Logic: Managed program flow using loops and conditional logic to process user input and correctly update the clock's time.
* String Manipulation: Formatted and presented the time output cleanly for both 12-hour and 24-hour displays.
* Maintainable Code: Wrote modular code with clearly defined, single-purpose functions (addOneSecond, formatTime), and used constants for menu options to improve readability.
* UI/UX Design: Implemented a command-line user interface that is intuitive and easy to navigate

# Lessons Learned in This Project: 
* Challenge: Implementing robust user input handling for menu navigation, which required correctly parsing a user's choice and linking it to the appropriate function.
* Solution: Broke down the problem into smaller, manageable pieces and leveraged online resources to understand effective input handling patterns. This approach allowed me to build the feature incrementally and successfully integrate it with the program's core logic.
* Future Improvement: In a future version, I would implement operator overloading (++ or +=) for adding time. This would provide a more concise and logical way to increment time values, further refining the object-oriented design
