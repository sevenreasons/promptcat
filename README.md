

<p align="center">
  <img width="1280" alt="promptcat" src="https://github.com/user-attachments/assets/ec879fb2-af98-4dc1-a60a-a7f490f89a0d" />
</p>

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

## Screenshots 📸

<table align="center">
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/13f12f94-b6e5-4fc4-9801-27a3e8a32870" alt="promptcat"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/daadd0c6-7bc7-43be-840c-56b0b2fedfc9" alt="promptcat_2"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/018170fd-d6e5-47f1-b5c2-5dfe6856132a" alt="promptcat_3"/></td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/31eed986-15e5-42a5-8592-0a5da70eff94" alt="promptcat_4"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/f863d608-f118-4909-89ea-52f5233f2727" alt="promptcat_5"/></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/f2d30365-034e-4814-a317-74da1a00536a" alt="promptcat_6"/></td>
  </tr>
  <tr>
    <td align="center" colspan="3"><img src="https://github.com/user-attachments/assets/627aac34-96bd-45f7-b2bb-288aa2c1dfe2" alt="promptcat_8"/></td>
  </tr>
</table>

## Screenshots (Mobile) 📱

<table align="center">
  <tr>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/7e10dd1c-6a82-4c44-9d31-197dfbcd8104" alt="promptcat-mobile_8"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/193a1bb4-022d-431c-bf85-c4e99dac87a5" alt="promptcat-mobile_7"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/c7c4d211-d6df-4571-801f-8016041b3c6a" alt="promptcat-mobile_6"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/63352c3a-1f75-4102-97a3-7aa77f44efe9" alt="promptcat-mobile_5"/></td>
  </tr>
  <tr>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/5f8525f1-f501-4a9c-975b-952e7a3f0acd" alt="promptcat-mobile_4"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/d3f465b7-0ad3-43bc-ab7c-781cb51163e3" alt="promptcat-mobile_3"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/5a954b60-d4d2-4b2e-9bf5-5ad9c6679ca2" alt="promptcat-mobile_2"/></td>
    <td align="center"><img width="200" src="https://github.com/user-attachments/assets/716bc2ee-f8cf-4bce-b400-7de3665182ee" alt="promptcat-mobile_1"/></td>
  </tr>
</table>

## Demo 🎥
<p align="center">
  <video src='https://github.com/user-attachments/assets/f84970fc-b3d4-4b36-9e1c-19b26ac9f114' width='720'/>
</p>
