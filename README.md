# Zoho-Cliq-Extension
## Quick Notes & Reminders Bot

A productivity extension for Zoho Cliq that helps you manage quick notes and set reminders directly from your chat interface.

## Features

### 📝 Quick Notes
- **Add Notes**: Quickly capture ideas, meeting notes, or important information
- **Categorize Notes**: Organize notes by category (Work, Personal, Ideas, Meeting Notes, To-Do, General)
- **View Notes**: Access all your saved notes with filtering options
- **Search**: Find notes by category or content

### ⏰ Reminders
- **Set Reminders**: Create one-time, daily, or weekly reminders
- **View Reminders**: See all your active and completed reminders
- **Smart Notifications**: Get notified when reminder time arrives

### 🤖 Bot Features
- **Interactive Bot**: Chat with the Quick Notes Bot for natural interactions
- **Command Support**: Use `/notes` command for quick access
- **Menu Integration**: Access features through bot menu options
- **Welcome Messages**: Personalized welcome experience

## Installation

1. Install the extension in your Zoho Cliq workspace
2. The bot will automatically send a welcome message
3. Start using by typing `/notes` or chatting with the bot

## Usage

### Commands
- `/notes` - View all available commands and options

### Bot Interactions
- **Add Note**: Type "add note" or click the "Add Note" button
- **View Notes**: Type "view notes" or click the "View Notes" button
- **Set Reminder**: Type "set reminder" or click the "Set Reminder" button
- **View Reminders**: Type "view reminders" or click the "View Reminders" button

### Menu Options
- **My Notes**: Access all your notes from the bot menu
- **My Reminders**: View all your reminders from the bot menu

## Functions

### addNote
Creates a new note with title, content, and optional category.

**Form Fields:**
- Title (required)
- Content (required)
- Category (optional)

### viewNotes
Displays all saved notes with filtering options.

**Form Fields:**
- Category filter (optional)

### setReminder
Creates a new reminder with date, time, and repeat options.

**Form Fields:**
- Title (required)
- Description (optional)
- Date (required)
- Time (required)
- Reminder Type (optional: once, daily, weekly)

### viewReminders
Shows all reminders with status filtering.

**Form Fields:**
- Status filter (optional: all, active, completed)
