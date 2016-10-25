# bash-scripts
My small collection of helper bash scripts for gdrive, youtube and others

<b>youtube</b> is a simple one-line script that uses Lynx text browser, Perl and VLC to create a local YouTube playlist that VLC can play. In order for this to work visit your prefered playlist on YouTube and copy, paste the whole URL of your list on top of the https://www.youtube.com/playlist?list=dwPLJqCwEpiz1GTK7KeSW7Ud9aKXEFlOsqI8 URL found on this script.
Keep in mind that you will have to make this file an executable by issuing the "$ chmod +x youtube" command on your terminal.

<b>gdd</b> is a bash script that uses the gdrive app found at https://github.com/prasmussen/gdrive in order to search for and download files from Google Drive. You can also upload files to a specific folder once you replace the uploadFolder variable on the top of the script with the id of your prefered upload folder found on GDrive URL after the https://drive.google.com/drive/folders/ path. 
