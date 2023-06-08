# ETS Orgin Discord Bot

This is a Discord bot built using Discord.py library. The bot has several features including moderation commands, reaction roles, status updates, and bot information.

## Features
-Embed Feature 
-Create 
-Send embed messages with custom titles
-Descriptions
-Add Custom Colors(with hex codes)
- Moderation commands:
  - Kick members from the server
  - Ban members from the server
  - Unban members from the server
  - Warn members

- Reaction roles:
  - Assign roles to users based on their reaction to a message

- Status updates:
  - Set the bot status (online, streaming, dnd)
  - View the history of bot status updates

- Bot information:
  - Display bot information including RAM usage, operating system, ping, and storage usage

## Usage
Invite the bot to your Discord server using the following link: Invite Bot
Set up the necessary permissions for the bot in your server to use the moderation and reaction role features.
Use the available commands to manage your server, assign reaction roles, and get bot information. See the command list below:

    .kick <member> [reason]: Kick a member from the server
    .ban <member> [reason]: Ban a member from the server
    .unban <member>: Unban a member from the server
    .warn <member> <reason>: Warn a member
    .reactionrole <message_id> <role_name> <emoji>: Create a reaction role assignment
    .setstatus <status_type> <status_message>: Set the bot status
    .statushistory: Show the history of bot status updates
   
   ## Installation
   pip install -r requirements.txt
   run - py bot.py
