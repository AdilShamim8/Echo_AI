# Echo AI

Echo AI is an interactive, web-based chatbot designed to engage users in natural conversations. Built with HTML, CSS, and JavaScript, it offers a seamless chat experience and can be easily customized and deployed.

## Demo

Check out the live demo: [echoai-iota.vercel.app](https://echoai-iota.vercel.app)

## Features

- **Natural Conversations**: Mimics human-like responses for engaging interactions.
- **Customizable UI**: Easily modify colors, fonts, and layout in `style.css`.
- **Flexible Logic**: Chat logic implemented in `script.js` allows for adding new response patterns and integrating APIs.
- **Responsive Design**: Works on desktop and mobile devices.

## Technology Stack

- **HTML5**: Structure of the chatbot interface.
- **CSS3**: Styling and responsive design.
- **JavaScript**: Chat logic and user interaction.

## File Structure

```
Echo_AI/
├─ assets/           # Images, icons, and other static assets
├─ index.html        # Main HTML file
├─ style.css         # Stylesheet for the chatbot UI
├─ script.js         # JavaScript for chat functionality
└─ README.md         # Project documentation
```

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AdilShamim8/Echo_AI.git
   cd Echo_AI
   ```
2. **Open `index.html`**
   - You can simply double-click `index.html` in your file explorer, or
   - Serve it via a local server:
     ```bash
     npx http-server .
     ```
3. **Start chatting!**

## Usage

1. Type your message in the input box.
2. Press **Enter** or click **Send**.
3. The chatbot will respond based on predefined logic in `script.js`.

### Customizing Responses

- Open `script.js`.
- Modify the response patterns and add new ones:
  ```js
  const responses = {
    hello: "Hi there! How can I help you today?",
    // Add your own patterns and responses here
  };
  ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature/YourFeatureName`.
3. Make your changes and commit: `git commit -m "Add your feature"`.
4. Push to your branch: `git push origin feature/YourFeatureName`.
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: adilshamim696@gmail.com
- **GitHub**: [AdilShamim8](https://github.com/AdilShamim8)
