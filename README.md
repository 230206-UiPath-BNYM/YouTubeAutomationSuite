# YouTubeAutomationSuite

## The Team

- Gavin Gilbert (Team Lead)
- Irving Gonzalez Islas
- Justin Quach

## Project Overview

Youtube is a vast online video library that virtually unlimited content for free but with this vast library keeping track of the videos you want to watch is a challenge and using playlists to track videos is somewhat limited with Youtube current playlist mamangement options. The solution, the Youtube Automation Suite (YAS).YAS will allow you to manage your YouTube playlists automatically using the automation power of UIPATH's automation abilities combined with Azure SQL Server to store user's data to lower the costs of API calls to Youtube. YAS can also provide updates for each each via email updates using Google integration. 

### Completed MVP Features
- OAUTH2.0 and API integration with Youtube API to limit on browser inactions.
- Create Playlists using Youtube's POST Playlist API to create a new empty playlist and add the new playlist information to a database.      
- Delete Playlists using Youtube's DELETE Playlist API to delete an existing playlist in the AZURE SQL Database.
- Rename Playlists using Youtube's UPDATE Playlist API to modify an existing playlist name in Youtube's Servers and on YAS's AZURE SQL Database.
- Edit Playlist Descriptions uses Youtube's UPDATE Playlist API to modify an existing playlist description in Youtube's Servers and on YAS's AZURE SQL Database.
- Edit Playlist Privacy Levels uses Youtube's UPDATE Playlist API to modify an existing playlist privacy in Youtube's Servers and on YAS's AZURE SQL Database.
- Add Videos to Playlists using Youtube's POST Playlist API to add a new playlist to Youtube's and YAS's database servers.  
- Remove Videos from Playlists using Youtube's DELETE Playlist API to delete a video in the AZURE SQL Database and Youtube database.
- Like a Video using Youtube's POST Playlist API to like a selected video. 
- Subscribe to a Channel using Youtube's POST Channel API to subscribe to a certain Subscribe to a channel using their Channel ID. 
- Send Email to user whenever YAS updates playlists such as creating, deleting, renaming, description edits, etc using GMAIL access token.
- Copy Videos from One Playlist to Another using GET, POST, AND REMOVE Youtube APIs to copy videos from one playlist to another while deleting a playlist.  

### Stretch Goals 
- Pattern matching(?)
- Integrate Voice Actions
  
 ### Project Conventions
- Git/Github
    - Issues & Branches for Features using the Youtube Automation Suite project board. Issues create tickets, tickets become branches to be worked on.
    - Pull Requests & Reviews 
    - Main Branch Protection -> Branches that are completed will be reviewed and merged with Main after testing of each branch. Main cannot be updated directly without review and acceptance from non-branch creator/worker.

- UiPath
    - camelCase for Variables
    - in_/out_/io_ prefix for Arguments
    - PascalCase for Files

### Communication Standards
- Discord 
- Weekday Daily Standups @ 2pm Eastern, Monday thru Friday, communication outside of work hours are not required but often all team members response within 5 minutes regardless of time. 
- Kanban Board managed by Gavin
