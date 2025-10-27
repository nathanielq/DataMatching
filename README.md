# DataMatching
This file was originally created to solve a problem in our district. We use parentsquare for various safe communications between staff, students and parents. An issue with our instance was that in Qmlativ (where our data was taken from to populate ParentSquare) staff members who are also parents were having their district email address set as their personal. To Solve this I created this script to take a file of staff guardians and match their userID in that file to the same userID in another file and then using that index replace their existing personal email address (Which was storing their work email at this point) with their true personal email address. Paramiko is then used to upload that updated file to a ParentSquare sftp server. 

This script could ulitmately be used as a jumping off point for any data validation between two diferent csvs. Find the key for mapping user to user (or any form of data that matches across two csvs) and enter the value into the correct column. Then upload to a server if needed.

Any variables or referneces to specific data or locations has been replaced with generic text.

I put this ReadME in the wrong spot initially. Still figuring out the nuances of GitHub Repos :^)
