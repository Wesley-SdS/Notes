
# Notes Application

This is a note-taking application built with Vite and Tailwind CSS, designed for users to create, manage, and organize notes. 
The app offers additional features like a search filter and voice-to-text note creation.

**[Leia esta documentação em Português](README_pt.md)**

## Features

- **Note Creation**: Add new notes with a text or via voice-to-text.
- **Local Storage Persistence**: Notes are saved in local storage, keeping them available even after refreshing the page.
- **Search Functionality**: Filter through notes based on their content.
- **Responsive UI**: Designed with Tailwind CSS for a mobile-first, responsive experience.
- **Modals for Note Details**: Notes can be viewed in modals/dialogs using Radix UI.
- **Notifications**: Toast notifications for successful actions like adding or deleting notes.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or above)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd notes-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the application:
    ```bash
    npm run dev
    ```

4. Open [localhost:5173/](http://localhost:5173/) in your browser to view the app.

## Planned Improvements

The following enhancements are planned for future updates:

1. **Validation and Note Cleanup**: Limit note length, remove trailing spaces, and prevent duplicates or empty notes.
2. **Delete Confirmation**: Add a confirmation step before permanently deleting notes.
3. **Categories and Tags**: Organize notes with categories or tags to enhance searching and filtering.
4. **Rich Text Editor**: Integrate a text editor like `react-quill` for basic text formatting.
5. **Backup and Synchronization**: Export and import notes in JSON format or synchronize notes using Firebase.
6. **Animations and Visual Feedback**: Add subtle animations for note addition and deletion, using Tailwind CSS or Framer Motion.
7. **Unit Tests**: Ensure functionality integrity by implementing unit and integration tests, especially for core logic like note creation and deletion.

---


