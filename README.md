# Open-Source Discord Bot

This bot is an easy-to-use, beginner-friendly Discord bot built using **Discord.js**. It features a comprehensive command handler, a full database integration, music commands, and more. Whether you're looking to customize it for your own Discord server or just want to learn how to build bots, this bot is a perfect starting point!

### Key Features:
- **Full Command Handler**: Easily manage and organize commands with a modular system.
- **Database System**: Store and retrieve data using a built-in database for persistence.
- **Music Commands**: Play, queue, and control music in your Discord server with ease.
- **Beginner-Friendly**: Simple setup and clear structure, designed specifically for new developers.

### How to Install:
1. **Clone the Repository**:  
   ```
   git clone https://github.com/AnushK-Fro/Discord.JS-Bot-with-Full-Command-Handler-Database-System-and-More
   cd Discord.JS-Bot-with-Full-Command-Handler-Database-System-and-More
   ```

2. **Install Dependencies**:  
   For each required module, run the following command in PowerShell or your terminal:
   ```
   npm install <module name>
   ```
   You can find the list of required modules in the `package.json` file.

3. **Configure Settings**:  
   Create a `settings.json` file in the root directory with the following structure:
   ```json
   {
     "ownerid": "YOUR_DISCORD_USER_ID",
     "friendids": ["FRIEND'S_DISCORD_USER_ID"],
     "prefix": "-",
     "token": "YOUR_DISCORD_BOT_TOKEN"
   }
   ```

4. **Prepare for Images**:  
   Make sure to create a folder called `images` to store any necessary image files for commands.

5. **Run the Bot**:  
   After installing the required modules and configuring the settings, you can run the bot using:
   ```
   node index.js
   ```

### Why this?
Unlike other open-source Discord bots like **Bastion** or **Xiao**, FroSkid is designed to be simple and straightforward, making it an excellent choice for beginners. Its minimal complexity allows for easy customization, and you are free to modify or rename it for personal use!
