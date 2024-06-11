# Knowledge Owl File Exporter

This is a personal project written in Javascript (Node) to export files located at the files endpoint of Knowledge Owl.

I ran into an issue where I needed to download files from their database but there was no way to do it, and with thousands of files, manually doing it was not going to happen.

So I wrote a little program. Don't ask me why it's in Javascript, I just felt like it.

To use this program: 
1. Donload and install Node JS.
2. Download the KODownloader Script and run it. It will create a folder with text files.
3. Enter your info into the files.
4. Run the script again.

By default it will only create a data.json file in your current directory. If you would like to download files you will need to make sure you've defined the location in the exportPath.txt file and uncomment the DownloadFiles() function in the script.
Additionally, the api call is filtered to only download active files and to name them with the name and extention of the file on the server.
