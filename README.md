# MP3_TAG_READER
🎧 MP3 Tag Reader & Editor (C Project)

A lightweight MP3 metadata reader & editor built in C, capable of displaying and updating ID3 tag information such as Title, Artist, Album, Year, Genre, Track etc.
Works through a terminal-based menu for viewing and editing tags.

📌 Features

View MP3 ID3 tag details
Edit & update metadata fields
Simple command-line interface
Updates values by rewriting file

📁 Project Structure
MP3-Tag-Editor
├── main.c
├── view.c
├── edit.c
├── update.c
└── tag.h

🧾 Sample Output
🎵 MP3 TAG VIEWER
Title   : Perfect
Artist  : Ed Sheeran
Year    : 2017
Genre   : Pop


Edit Example

Enter new title: Perfect Remix
✔ Tag updated successfully

⚙ Run Program

gcc main.c edit.c open.c -o mp3_editor
./mp3_editor

🚀 Future Scope

GUI version
Multiple tag editing
Backup restore support

⭐ Feel free to use, contribute and enhance!
