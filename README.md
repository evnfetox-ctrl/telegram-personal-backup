# Telegram Personal Backup

This repository contains a comprehensive solution for backing up your Telegram data across multiple devices. The tool ensures that you never lose your important conversations, media, and files. 

## Features
- **Multi-Device Usage**: Seamlessly back up data from multiple devices.
- **Comprehensive Data Backup**: Includes messages, media files, and documents.
- **User-Friendly Interface**: Easy to set up and use.
- **Scheduled Backups**: Automate your backup process to ensure regular data backups.
- **Data Security**: Utilize encryption to secure your data during the backup process.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/evnfetox-ctrl/telegram-personal-backup.git
   cd telegram-personal-backup
   ```
2. Install the required dependencies:
   ```bash
   npm install
   ```
3. Set up your Telegram API keys as environment variables. Refer to the [Telegram API documentation](https://core.telegram.org/api) for more information.

## Configuration
1. Create a `.env` file in the root of the project:
   ```
   TELEGRAM_API_ID=your_api_id
   TELEGRAM_API_HASH=your_api_hash
   ```
2. Customize any additional settings in the configuration file as needed.

## Multi-Device Usage
- This tool allows you to log in with multiple accounts and back up data from each independently. Simply run the script with the respective API keys and follow the prompts.

## Future Enhancements
- Integration with cloud storage services for automatic backup saves.
- Option to restore backups directly to Telegram.
- Support for additional messaging platforms.

## Author Information
- **Name**: evnfetox-ctrl
- **GitHub Profile**: [evnfetox-ctrl](https://github.com/evnfetox-ctrl)
- **Contact**: [Email](mailto:your-email@example.com)  

This project aims to contribute to the convenience of Telegram users, ensuring that their valuable conversations and files are backed up and preserved. Please feel free to reach out for any questions or suggestions for improvements!  
