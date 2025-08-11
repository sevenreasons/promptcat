<img width="1280" height="640" alt="promptcat" src="https://github.com/user-attachments/assets/e19b2cdf-79cb-4d16-8330-a6b5f0a5f770" />

# promptcat 😼

**promptcat** is a simple, powerful, and private prompt manager designed for simplicity and efficiency. It's a single HTML file with zero dependencies, making it incredibly easy to use and modify. Everything you create is stored locally in your browser's IndexedDB, ensuring your data remains completely private and secure.

Whether you're a writer, developer, or AI enthusiast, promptcat provides a clean and organized space to manage your prompts, notes, and ideas without any setup, servers, or dependencies.

## Key Features ✨

*   **Simplicity First**: The entire application is a single HTML file. No builds, no installations. Just download the file and open it in your browser to get started.

*   **Zero Dependencies**: Written in pure HTML, CSS, and vanilla JavaScript. This means it's fast, lightweight, and incredibly robust.

*   **Fully Local & Private**: All your data—prompts, folders, and tags—is stored directly in your browser's IndexedDB. Nothing is ever sent to a server, giving you complete privacy and offline access.

*   **Advanced Encryption**: For an extra layer of security, you can password-protect individual prompts or entire folders. The content (body and notes) is encrypted using the strong AES-GCM standard from the Web Crypto API. Passwords are never stored and are required for each session, ensuring only you can access your sensitive data.

*   **Responsive & Mobile-First UI**: The interface is designed to be beautiful and functional on any device. The mobile experience feels native with a morphing Floating Action Button (FAB), intuitive back-button navigation, and a dedicated search interface.

*   **Powerful Organization**:
    *   **Folders**: Group your prompts into folders. A settings menu (visible on hover) allows you to easily **Rename**, **Lock/Unlock**, **Export**, or **Delete** any folder.
    *   **Advanced Tag Management**: Add multiple tags for flexible organization. A dedicated manager lets you **globally rename or delete tags**, automatically updating them across all associated prompts.
    *   **Favorites**: Mark your most-used prompts for quick access.

*   **Robust Data Management**:
    *   **Flexible Import/Export**: You are always in control. Easily back up your entire database or import it to another device. You can also export just a single folder or a selection of multiple prompts.
    *   **Bulk Actions**: Select multiple prompts at once to move, delete, or export them in a single action, saving you time.

*   **Efficient Workflow**:
    *   **Drag & Drop**: Instantly move a prompt into a new folder by simply dragging it from the list and dropping it onto the folder in the sidebar.
    *   **Powerful Search**: Instantly find any prompt by searching its title, body, notes, or tags. The search even works on decrypted content during a session.
    *   **Sort & Find**: Sort your prompt list by creation date or title, and use the "Back to Top" button for long lists.
    *   **Resizable Layout**: Adjust the view by dragging the divider between the prompt list and the editor.
    *   **Quick Copy**: A convenient one-click button copies the prompt's body to your clipboard.
    *   **Character Counter**: Keep track of your prompt's length with a real-time character counter.
    *   **Fullscreen Editor**: Expand the prompt or notes fields into a distraction-free fullscreen editor for focused writing.

## How to Use 🚀

1.  **Download**: Download the `promptcat.html` file from this repository.
2.  **Open**: Open the file in your web browser.
3.  **Done!** That's it. You can start creating and organizing your prompts immediately.

Since all data is stored in IndexedDB, it is tied to the specific browser and device you are using. To move your data, click the **Settings** button in the sidebar, use the **Export** feature to save a backup file, and then **Import** it on the new browser or device.
