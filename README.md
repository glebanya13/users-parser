# 🧠 SubsParser Telegram
The Telegram Usernames Exporter is a powerful tool designed to fetch usernames from Telegram entities and save them to Excel files. This project aims to provide a simple and efficient way to manage and analyze Telegram user data. With its robust features and user-friendly setup, this tool is perfect for developers, researchers, and anyone looking to extract valuable insights from Telegram entities.

## 🚀 Key Features
- **Entity Resolution**: Resolve target entities, including groups, channels, and chats.
- **Username Fetching**: Fetch usernames from resolved entities, handling large datasets with ease.
- **Data Chunking**: Split fetched data into manageable chunks for efficient processing.
- **Excel Export**: Save usernames to separate Excel files, making it easy to analyze and visualize the data.
- **Error Handling**: Robust error handling to ensure the application remains stable and reliable.
- **Configuration Management**: Centralized configuration management using environment variables.

## 🛠️ Tech Stack
* Frontend: None
* Backend: Node.js
* Database: None
* AI Tools: None
* Build Tools: None
* Libraries:
  + `telegram` for interacting with the Telegram API
  + `dotenv` for loading environment variables
  + `qrcode-terminal` for generating QR codes
  + `xlsx` for creating and writing Excel files

## 📦 Installation
To get started with the Telegram Usernames Exporter, follow these steps:
1. **Prerequisites**: Ensure you have Node.js installed on your system.
2. **Clone the Repository**: Clone the Telegram Usernames Exporter repository using Git.
3. **Install Dependencies**: Run `npm install` to install the required dependencies.
4. **Create a `.env` File**: Create a `.env` file in the root directory and add your configuration settings, including API ID, API hash, session string, target entity, output file, maximum users per file, and excluded usernames.

## 💻 Usage
1. **Run the Application**: Run the application using `node src/index.js`.
2. **Follow the Prompts**: Follow the prompts to authorize the Telegram client, if necessary.
3. **Wait for the Process to Complete**: Wait for the application to fetch usernames and save them to Excel files.

## 📂 Project Structure
```markdown
.
├── src
│   ├── config
│   │   ├── index.js
│   ├── export
│   │   ├── excel.js
│   ├── telegram
│   │   ├── client.js
│   │   ├── participants.js
│   ├── index.js
├── .env
├── package.json
```

## 🤝 Contributing
Contributions are welcome and appreciated. If you have any suggestions, bug reports, or feature requests, please submit a pull request or issue.

## 📝 License
The Telegram Usernames Exporter is licensed under the MIT License.

## 📬 Contact
For any questions or concerns, please contact us at [glebanya.com@gmail.com](mailto:glebanya.com@gmail.com).
