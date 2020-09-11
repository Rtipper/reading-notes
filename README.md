# reading-notes

## Growth Mindset is keeping the door to your subconscious open at all times
- Giving up is *easier* with more *excuses*
- Remember there are always a million reasons not to do something
- Always allow your creativity to **flourish**

### My name is Ryan. Some of my favorite hobbies are writing, baseball, art and the outdoors. [GitHub](https://github.com/Rtipper)

### Reading Assignment | Notes
* Markdown: A basic way to structure and layout the text of a web page - [Link](https://guides.github.com/features/mastering-markdown/)
* Referencing a markdown cheat sheet is incredibly useful
* Bolding words can be done by placing double asterisks on either side of a word
* Italicizing words can be done by placing single asterisk on either side of a word
* GitHub.com uses its own version of the Markdown syntax called **Flavored Markdown**
* Using an "@mention" by including someone's name after the "@" symbol will tag them directly
* GitHub supports emjois and even includes their own cheat sheet - [Link](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

### Professional Competencies
#### Areas of Strength
- **Creative** - Being creative is one of my biggest goals in life. Everything I get to put my hands on, digitally or physically, I love taking and changing to match my own imagination and desire for it to stand out and be unique to myself.
- **Writing** - Having worked as a professional and self-published writer, I feel this is my number two area of strength. Writing has not only come very natural to me since a young age, but it has turned into one of my most passionate hobbies and professional skills.
- **Ambition and Initiative** - As someone who has too many hobbies to count, ambition and initiative drive me through my current stages of life with ease. I usually always have to be working on a task or project and often bounce between them at multiple times, all the while only looking to achieve them for myself.
#### Areas of Growth
- **Confidence** - I tend to not be the most confident person in the world. While I continue to always push myself to experience new things, I sometimes tend to find comfort in what is familiar. If I struggle learning or understanding something, it is easy for me to snowball on myself and feel my confidence dwindle.
- **Technical** - Being almost fully right brained, math and "exact science" never seems to fully agree with me. While technology in general is something I am very comfortable with, really following exact steps to achieve an end goal and not let my creativity take over can be a struggle at times. Also, specific to this definition, I have yet to learn to code, so I won't claim to deliver high quality software that is written with pride, great skill and careful attention (yet).
- **Speaking** - In tandem with my confidence struggles, speaking is one that take a lot of extra effort for me. As an introvert, I am far more comfortable listening than speaking, but it something I always remind myself to do, even if its outside of my usual box.

### Cheat Sheet for Commands
- ls - (list) see inside a folder - ex. *ls **folder name*
- pwd - locate exact file path / location within terminal
- cd - change directories
- cd.. - back up one level
- cd../cc - back up two levels
- mkdir - create new folder - ex. *mkdir home*
- touch - create new file - ex. *touch homefile*

### Revisions and the Cloud
- Localized Version Control (VCS) - A Local VCS entails one database on your hard disk that stores changes to files.
- Centralized Version Control (CVS) - This system entails a single server storing all changes and file versions, which can be accessed by various clients, allowing programmers to have more knowledge of team members’ activities with certain files
- Distributed Version Control - If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.
- Snapshots - Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it.
- Local Operations - Git mostly relies on local operations allowing one to continue work on a project even when not online or on a VPN.
- Tracking Changes - Git will always detect file corruption or loss of information in transit.
- States - Files in Git can reside in three main states: committed (Data is securely stored in a local database), modified (File has been changed but not committed to the database) and staged (Flagged a file’s changed version to be committed in the next snapshot).
- Local Repository Structure - The local Git repository has three components: Working Directory (The actual files reside here), Index (The area used for staging) and Head (Points to the most recent commit)
- Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
- Untracked files were not in the last snapshot and do not currently reside in the staging area.
- To determine the state of files, utilize the git status command: $ git status
- Track one file only by using the following format: git add filename
- Track all files in a repository by using the following command: $ git add *
- After staging one or multiple files, you should commit the changes and record what you did within the commit message: $ git commit -m “made change x,y,z”
- Committing All Changes: $ git commit -a
- Push changes to a remote repository: $ git push origin master


