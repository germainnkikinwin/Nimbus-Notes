# Nimbus Notes

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![GitHub followers](https://img.shields.io/github/followers/germainnkikinwin?label=Follow%20@germainnkikinwin&style=social)](https://github.com/germainnkikinwin)


## Overview

Nimbus Notes is a modern, lightweight note-taking application designed for users who want to effortlessly capture ideas, organize content, and sync their notes across devices. With full markdown support and the ability to embed images, links, and code snippets, Nimbus Notes brings clarity and creativity into your workflow.

---

## Features

- Real-time cloud synchronization across multiple devices
- Full support for Markdown formatting
- Embed images, links, code snippets, and videos
- Tagging and categorization for easy organization
- Offline mode with automatic sync upon reconnection
- Intuitive and clean user interface

---

## Tech Stack

- **Frontend:** React.js with TypeScript
- **Backend:** Node.js with Express
- **Database:** MongoDB Atlas
- **Authentication:** JWT with OAuth integration
- **Deployment:** Dockerized containers on AWS

---

## Installation

1. Clone the repository:
   
   ```bash
   git clone https://github.com/germainnkikinwin/NimbusNotes.git
   cd NimbusNotes
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure environment variables:

   Create a `.env` file in the root directory and add:
   
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   OAUTH_CLIENT_ID=your_oauth_client_id
   OAUTH_CLIENT_SECRET=your_oauth_client_secret
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

---

## Usage

- Open your web browser and navigate to `http://localhost:3000`.
- Register a new account or login with existing credentials.
- Create new notes using the rich markdown editor.
- Organize notes with tags and folders.
- All your notes automatically sync to the cloud.

---

## Screenshots

![Dashboard Placeholder](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Editor Placeholder](https://via.placeholder.com/800x400?text=Markdown+Editor+Screenshot)

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please make sure to update tests as appropriate.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

Created and maintained by [germainnkikinwin](https://github.com/germainnkikinwin)

Connect with me on GitHub: [https://github.com/germainnkikinwin](https://github.com/germainnkikinwin)
