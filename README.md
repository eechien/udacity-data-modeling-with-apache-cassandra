# Sparkify

Sparkify is a music streaming app that's interested in what songs users are listening to. This project
takes CSV data and transforms it into three tables in Apache Cassandra to answer three types of queries.

- Get the artist, song title and song's length in the music app history that was heard during a specific session and the nth song in the session.
- Get the name of artist, song (sorted by itemInSession) and user (first and last name) for a specific userid and sessionid.
- Get every user name (first and last) in the music app history who listened to a specific song.
- 
