# cbot

cbot is basic IRC bot written in C#.  Net code (connection, ping thread, stream setup) was graciously used from public locations around the internets.

Feel free to contribute, rip, comment, or provide feedback.  Feedback is always welcome and appreciated.

-- Adding Commands:

Addons should be declared in commands.cs and added to the Input() switch.

LineWrite = Used to write to datastream
serverInfo = server data (hostname, port, nickname, channel)
lineData[] = raw string array, format: nickname!username@hostname <RAW CODE> <#channel/nickname> :<chat message>

