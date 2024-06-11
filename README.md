# Knowledge Owl File Exporter

This is a personal project written in Javascript (Node) to export files located at the files endpoint of Knowledge Owl.

I ran into an issue where I needed to download files from their database but there was no way to do it, and with thousands of files, manually doing was not going to happen.

So I wrote a little program. Don't ask me why it's in Javascript, I just felt like it.

To use this program, <B>download the KODownloader Script and run it</b>

It will create a folder with text files. Enter your info into the files and run the script again.

By default it will only create a data.json file in your current directory. If you would like to download files you will need to make sure you've defined the location in the exportPath.txt file and uncomment the DownloadFile() function in the script.
Additionally, the api call is filtered to only download active files and to name them with the name and extention of the file on the server.
