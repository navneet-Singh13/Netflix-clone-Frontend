# Netflix Clone

A fully responsive Netflix Clone built with **React** and **native CSS**, featuring a functional login system powered by **Firebase Authentication**.

## Features

- 🎥 **Home Page**: Browse movies and TV shows with a sleek, Netflix-inspired UI.
- 🔍 **Movie Details**: View additional information for selected titles.
- 🔐 **Login System**: Secure login using Firebase Authentication.
- 💻 **Responsive Design**: Optimized for all screen sizes using native CSS.

---

## Tech Stack

### Frontend:
- React
- Native CSS for styling

### Backend:
- Firebase for authentication

---

## Demo Credentials (Test User)

You can test the login functionality using the following credentials:

- **Email**: `user@gmail.com`
- **Password**: `password`

---

## Getting Started

Follow these instructions to set up the project on your local system.

### Prerequisites

Ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn
- Firebase account (if deploying your own backend)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/netflix-clone.git
   cd netflix-clone
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Firebase:
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Enable **Email/Password Authentication** in your Firebase Authentication settings.
   - Copy your Firebase configuration and replace it in the `firebase-config.js` file.

4. Start the development server:
   ```bash
   npm start
   ```


## Folder Structure

```
netflix-clone/
├── public/              # Static assets
├── src/
│   ├── components/      # Reusable React components
│   ├── pages/           # Page-level components (e.g., Home, Login)
│   ├── styles/          # Native CSS files
│   ├── firebase-config.js  # Firebase configuration
│   ├── App.js           # Main app entry point
│   └── index.js         # React DOM render
├── package.json         # Project metadata
└── README.md            # Project documentation
```

---

## Scripts

Here are the scripts you can use in this project:

- **Start Development Server**:
  ```bash
  npm start
  ```
- **Build for Production**:
  ```bash
  npm run build
  ```
- **Lint and Fix Code**:
  ```bash
  npm run lint
  ```

---

## Deployment

### Deploy to Firebase Hosting:
1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```

2. Login to Firebase:
   ```bash
   firebase login
   ```

3. Initialize Firebase Hosting:
   ```bash
   firebase init
   ```

4. Deploy the app:
   ```bash
   firebase deploy
   ```

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for review.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Netflix for the inspiration
- Firebase for the seamless authentication services
