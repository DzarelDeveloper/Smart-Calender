# Project-9: Smart Calendar

## Description
This project is a **Smart Calendar** built using Python's `tkinter` library and `tkcalendar` widget. It allows users to view a calendar, add events for specific dates, and view the events for a particular date. The events are stored in a JSON file and can be accessed even after closing the application.

## Prerequisites
Before running this project, ensure the following modules are installed:

- **Tkinter**: Typically included by default in most Python installations.
- **tkcalendar**: You can install it using pip:

    ```bash
    pip install tkcalendar
    ```
- **JSON**: A standard Python library, included by default.

## How to Run
1. Open a terminal or command prompt in the project directory.
2. Run the Python script:

    ```bash
    python project-9.py
    ```

3. The Smart Calendar GUI window will open. You can:
   - **Add Event**: Click "Add Event" to add a new event for the selected date.
   - **Show Events**: Click "Show Events" to view the events for the selected date.
   - **Quit**: Click "Quit" to close the application.

## Features
- **Calendar Display**: Displays a calendar with the option to select a date.
- **Add Event**: Allows users to add events for a specific date and save them.
- **View Events**: Displays all events associated with a selected date.
- **Event Storage**: Events are saved in a JSON file (`events.json`), which can be loaded the next time the application runs.
- **User-friendly Interface**: Simple and intuitive interface for interacting with the calendar and managing events.

## Limitations
- The events are saved in a plain JSON file, which can be accessed by anyone with access to the file system.
- The application does not support event editing or deletion.
- Only basic event storage and viewing functionality is provided.

## Future Enhancements
- Add support for editing or deleting events.
- Implement event reminders or notifications.
- Improve the GUI with additional features such as categorizing or prioritizing events.
- Encrypt the events file for added security.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you wish.

---

If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the [project repository](https://github.com/YourUsername/Project-9).
