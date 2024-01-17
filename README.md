# Club_Managment_System
This is a simple console-based Club Management System written in C language. It allows you to manage the members and events of a club. The system requires a password for access, and it provides options for adding, deleting, searching, viewing, and editing member information. Additionally, it includes functionality for managing events.

**Features:**
1. **Password Protection:** The system requires a password for access to ensure security.

2. **Member Management:**
   - **Add Member:** Allows adding new members with their details.
   - **Delete Member:** Enables deleting a member based on their ID.
   - **Search Member:** Allows searching for a member by their ID.
   - **View Members:** Displays a list of all members along with their details.
   - **Edit Member Information:** Allows editing the information of a specific member.

3. **Event Management:**
   - **Add Event:** Allows adding events with details such as date, event name, and description.
   - **View Events:** Displays a list of all events along with their details.
   - **Delete Event:** Enables deleting an event based on its date.

4. **Additional Functions:**
   - **Date and Time:** Displays the current date and time.
   - **Graceful Exit:** Provides an option to close the application gracefully.

**How to Run:**
1. Ensure you have a C compiler installed on your system (e.g., GCC).
2. Copy and paste the code into a text file and save it with a ".c" extension (e.g., `club_management_system.c`).
3. Open a terminal or command prompt and navigate to the directory containing the file.
4. Compile the code using the command: `gcc club_management_system.c -o club_management_system`.
5. Run the executable: `./club_management_system` (on Linux/Mac) or `club_management_system.exe` (on Windows).

**Usage:**
1. Upon running the program, a password prompt will appear. Enter "admin" as the password to access the system.

2. Once logged in, the main menu will be displayed, providing options to perform various operations related to member and event management.

3. Follow the on-screen instructions to navigate through the system, add/edit members, manage events, and perform other operations.

4. To exit the application, select the "Close application" option from the main menu.

**Note:**
- This program uses a simple file-based storage system (`record_nxt.txt` and `record.dat`) to store member and event data. Ensure that the program has the necessary file permissions to read and write these files.

- This is a console-based program, so interaction is text-based. Use the keyboard to navigate and input data.

- The password for accessing the system is hardcoded in the code for simplicity. In a real-world scenario, a more secure authentication mechanism should be implemented.
