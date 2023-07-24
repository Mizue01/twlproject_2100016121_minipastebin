# CodeBin

CodeBin is a mini pastebin-like web application that allows users to post and share their code snippets with others who have registered on the site. It provides a platform for developers to easily share and discover code examples, collaborate, and learn from each other.

## Technologies Used

- Backend Framework: Express.js
- Database: MongoDB

## Features

- User Registration and Authentication
- Create, Edit, and Delete Code Snippets
- View and Search Code Snippets Posted by Other Users

## Prerequisites

Before running CodeBin locally, make sure you have the following installed:

- Node.js
- MongoDB

## Installation

1. Clone the repository:

2. Navigate to the project directory:

3. Install the dependencies:

- `npm i express`
- `npm i hbs`
- `npm i mongoose`
- `npm i nodemon`
- `npm i express-session`
- `npm i multer`
- `npm i jsonwebtoken`
  (i think thats all lol i forgot)

4. Set up the MongoDB database:

- Install MongoDB if not already installed: [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/)
- Start the MongoDB service: `mongod`
- Create a new MongoDB database named "CodeBin"
- Update the MongoDB connection URL in the project's `mongo.js` file with your database credentials

5. Start the server:

6. Access the CodeBin application in a web browser:

## Usage

1. Register a new account or log in if you already have an account.
2. Once logged in, you can create a new code snippet by providing a title and the code content.
3. View and search for code snippets posted by other users.
4. Edit or delete your own code snippets.
5. Log out when finished.

## Contributing

Contributions to CodeBin are welcome! If you have any bug reports, feature requests, or suggestions, please open an issue or submit a pull request. Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions, feedback, or need support regarding CodeBin, you can reach out to the project maintainer:

- Name: Encrypted
- Email: encryptedscriptss@gmail.com
- GitHub: [https://github.com/EncryptedScripts]
- Discord: encrypted0166

## Screenshots

![Screenshot 1](https://cdn.discordapp.com/attachments/1115267387953000459/1128751325371437086/image.png)
![Screenshot 2](https://cdn.discordapp.com/attachments/1115267387953000459/1128751325694402684/image.png)
![Screenshot 3](https://cdn.discordapp.com/attachments/1115267387953000459/1128751325958647858/image.png)
![Screenshot 4](https://cdn.discordapp.com/attachments/1115267387953000459/1128751326269018122/image.png)
![Screenshot 5](https://cdn.discordapp.com/attachments/1115267387953000459/1128751326583595079/image.png)
![Screenshot 6](https://cdn.discordapp.com/attachments/1115267387953000459/1128751326852034620/image.png)
![Screenshot 7](https://cdn.discordapp.com/attachments/1115267387953000459/1128751327086907572/image.png)
