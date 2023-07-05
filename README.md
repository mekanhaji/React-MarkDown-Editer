# React Markdown Editor App

This project is a React-based Markdown editor application that allows users to write and preview Markdown text in real-time. It utilizes JavaScript, React, react-split, react-mde, showdown, Firebase, and Vite.

## Features

- Live Markdown preview as you type.
- Markdown syntax highlighting and formatting.
- Split view for simultaneous editing and previewing.
- User authentication using Firebase.
- Saving and loading Markdown documents using Firebase Firestore.

## Technologies Used

- JavaScript: The programming language used for the project.
- React: The JavaScript library used for building the user interface.
- react-split: A React component for creating resizable split views.
- react-mde: A React Markdown editor component.
- showdown: A JavaScript Markdown-to-HTML converter library.
- Firebase: A cloud-based platform used for authentication and data storage.
- Vite: A fast development build tool for JavaScript and React applications.

## Usage

To use the React Markdown Editor App, follow these steps:

1. Install the project dependencies by running `npm install` or `yarn install` in the project directory.
2. Configure your Firebase project and obtain the necessary credentials.
3. Replace the Firebase configuration placeholders in the code with your own Firebase credentials.
4. Run the application locally by executing `npm run dev` or `yarn dev`.
5. Access the app in your web browser at `http://localhost:3000`.
6. Sign in using your Firebase authentication credentials or create a new account.
7. Start writing Markdown in the editor and see the live preview on the right.
8. Save and load documents using the provided functionality.

## Project Structure

The project structure is as follows:

```
.
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── Editor.js
│   │   ├── Preview.js
│   │   └── SignIn.js
│   ├── firebase/
│   │   └── firebaseConfig.js
│   ├── App.js
│   ├── index.js
│   └── styles.css
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

- The `public` directory contains the static files for the application, such as the HTML template and favicon.
- The `src` directory contains the main source code for the React components, Firebase configuration, and styles.
- The `.gitignore` file specifies which files and directories should be ignored by Git.
- The `package.json` file lists the project dependencies and scripts.
- The `README.md` file provides information about the project.
- The `vite.config.js` file contains the configuration for the Vite build tool.

## Customization

You can customize the React Markdown Editor App according to your needs:

- Modify the styling by editing the `styles.css` file.
- Add additional features or components as per your requirements.

## Contributions

Contributions to the project are welcome. If you encounter any issues or have suggestions for improvements, feel free to submit a pull request or open an issue on the project repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This project utilizes various libraries and technologies such as React, Firebase, and Markdown processing libraries to provide a feature-rich Markdown editing experience.
- Special thanks to the developers and contributors of the JavaScript, React, Firebase, react-split, react-mde, showdown, and Vite libraries for their valuable tools and resources.