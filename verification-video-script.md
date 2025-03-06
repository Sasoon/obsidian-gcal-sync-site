# Obsidian Google Calendar Sync - Verification Video Script

## Introduction (0:00-0:30)
- "Hello, I'm Sasoon Sarkisian, developer of the Obsidian Google Calendar Sync plugin."
- "This video demonstrates how our plugin uses Google Calendar API scopes to sync Obsidian tasks with Google Calendar."
- "Our plugin requires the following scopes: [list the specific scopes your app uses]"

## Plugin Overview (0:30-1:00)
- Brief explanation of what the plugin does
- Show the plugin interface in Obsidian
- Explain the core functionality: syncing tasks from Obsidian to Google Calendar

## Authentication Flow (1:00-2:00)
- Show the authentication process from start to finish
- Demonstrate both desktop and mobile authentication flows
- Explain how OAuth tokens are stored locally in plugin settings
- Emphasize that no user data is stored on our servers

## Scope Usage Demonstration (2:00-4:00)
For each scope requested, show exactly how it's used:

### Calendar Access Scope
- Show how the plugin reads calendar data
- Demonstrate creating a new task in Obsidian
- Show the task being synced to Google Calendar
- Show updating a task and how it updates in Google Calendar

### User Profile Scope (if applicable)
- Show how user information is used (e.g., to identify which calendar to use)
- Explain why this scope is necessary

## Data Security (4:00-4:30)
- Explain how user data is protected
- Show that OAuth tokens are stored locally
- Demonstrate that no unnecessary data is collected

## Conclusion (4:30-5:00)
- Recap of how the plugin uses Google API scopes
- Mention the privacy policy at obsidian-gcal-sync.netlify.app/privacy.html
- Thank viewers for watching

## Technical Notes for Recording
- Record at 1080p minimum
- Ensure text is clearly visible
- Blur out any personal information or tokens
- Keep the video under 5 minutes if possible
- Add captions for accessibility 