# Gladoire-FullStack
GA P3 project for JC North and Tom Erickson

## Concept
This is an extension of JC's P2 (Gladoire) which leverages React on the front end and 
an Express API/MongoDB on the back end.
It is a continuation of the original Gladoire, though starts from a completely new code base on both the front and back 
ends.
In addition to the journaling feature that was core to OG Gladoire, this new version adds:

- Customizable user fields for the journal.  Users can specify as many text fields as they like to make Gladoire truly 
  their own!
- Meditation Timer.  During P2 testing, my focus group drew a lot of comparisons with Insight Timer, and this was an 
  obvious feature to add
- Forum style discussions.  Users will able to post and comment on posts on a variety of topics 
  (topics determined by admins and adjustable via admin interface)
- Gladoire users can connect with other meditators via the "Also Meditating" feature, which allows users to connect based on their meditation schedules
  - Also, connected users can exchange private messages
  
## Design

- ### Home Page
![](assets/gladoire2-HomePage.png)

- ### Profile Page
![](assets/galdoire2-profilepage.png)

- ### Journal
![](assets/Gladoire2-Journal.png)

- ### Timer
![](assets/Gladoire2-Timer.png)

- ### ERD
![](assets/gladoire2-ERD.png)


## User Stories
- As a Gladoire User, ISBAT:
  - ### User Stuff
  - create a profile with a username, password, and other relevant information
  - login with a password
  - logout
  - create custom text fields for my meditation journal that are personal to me
      - (Stretch)AND I should only have to enter a thing for those things one time (I want to select previous values, or choose from a list)
  - manage my own profile
  - make myself "hidden" (so I don't show up in the "also meditating" list for other users if I don't want to...Privacy please!)
  - change my password (if google oauth is not used)
  - use Rich Text in the body of my journal entry 
  - (Stretch, if time allows) encrypt my journal entries
  - (Stretch, if time allows) authenticate via Google
    
  - ### Meditation Stuff
  - have a timed meditation session with simple sound loops or a youtube video in the background
  - see a list of other users who were active (unless I am hidden)
  - have a new journal entry with date, time, duration, and background at the end of the session that I can edit if I want to
  - make journal entries for sessions that did not use the timer
  - see and use my custom fields for journal entries
  - see my previous entries
  - edit my previous entries 
  - (Stretch, if time allows) do a group meditation session with users I am connected to
  - ### Social Stuff
  -form connections with other users via the "handshake" (send thanks and get acknowledgement from other user)
  - send and receive messages with users that I am connected to
  - end a connection with another user
  - participate in message board style discussions on various topics
  - see the most popular and newest message in each category on the home page (and click to go to that thread)
  - see what/how many users I am connected to are also meditating on the home page (mouseover to see list?)
  - see if I have new messages on the home page  (and click to see my new messages)
  - exchange youtube links with my connections that they can directly import those links into their saved list for later use (click, not have to copy/paste a link)