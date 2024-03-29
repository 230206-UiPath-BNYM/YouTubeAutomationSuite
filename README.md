# YouTubeAutomationSuite

## The Team
- Gavin Gilbert (Team Lead)
- Irving Gonzalez Islas
- Justin Quach

## Project Overview
YouTube is a vast online video library that offers virtually unlimited free content. However, keeping track of the videos you want to watch can be challenging, and using playlists to track videos is somewhat limited with YouTube's current playlist management options. The solution is the YouTube Automation Suite (YAS). YAS will allow you to manage your YouTube playlists automatically using the automation power of UiPath combined with Azure SQL Server to store user data and lower the costs of API calls to YouTube. YAS can also provide email updates for each video using Google integration.

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