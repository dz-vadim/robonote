# React Redux TypeScript Note App

This is a simple Note App built using React.js, Redux (or Redux Toolkit), and TypeScript.

## Features

1. **Add, Edit, and Remove Notes:**
    - Users can create new notes, edit existing ones, and remove notes.

2. **Display Notes in Table:**
    - Notes are displayed in a table format.
    - Columns: Time of creation, Note's content, Note's category, Dates mentioned.

3. **Note Categories:**
    - Categories include "Task", "Random thought", and "Idea".

4. **Archiving Notes:**
    - Users can archive notes, and archived notes are not shown in the main notes list.
    - Users can view archived notes and unarchive them.

5. **Summary Table:**
    - Display a summary table counting notes by categories for both active and archived notes.
    - The summary table is updated dynamically.

6. **Redux Store:**
    - Data is stored in the Redux store.
    - Initial state is prepopulated with 7 notes.

7. **Bonus Tasks:**
    - Tables for "List of Notes" and "Summary" use the same table component.
    - Creation and editing of notes work through a custom modal component.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/dz-vadim/robonote.git
   ```

2. Install dependencies:

   ```bash
   cd robonote
   npm install
   ```

3. Run the app:

   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000`.

## Project Structure

The project structure follows a standard React-Redux TypeScript setup:

- `src/components`: React components.
- `src/store`: Redux-related files, including actions, reducers, and store configuration.
- `src/types`: TypeScript types/interfaces.
- `src/utils`: Utility functions.
- `src/App.tsx`: Main application component.
- `src/index.tsx`: Entry point of the application.

## Screenshots

![Note App](screenshots/note-app.png)

## Dependencies

- React.js
- Redux (or Redux Toolkit)
- TypeScript
- React-Redux
- React-Router
- Other dependencies as needed

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.MD) file for details.