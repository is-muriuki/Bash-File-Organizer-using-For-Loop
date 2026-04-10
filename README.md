# Bash-File-Organizer-using-For-Loop
This project uses a Bash for loop to automatically organize files  in the Downloads folder into categories like Images, PDFs, and Videos.  It demonstrates automation, scripting, and basic cybersecurity file handling.
# features
- Automatically detects file types
- Moves files into categorized folders
- Uses for loop + if/elif logic
- Handles multiple files at once
# how it works
1. Loops through all files in Downloads
2. Checks file type (.jpg, .pdf, .mp4)
3. Moves each file into the correct folder
# example
Before:
file1.jpg
notes.pdf

After:
Images/file1.jpg
PDFs/notes.pdf
# how to run
chmod +x organize.sh
./organize.sh
