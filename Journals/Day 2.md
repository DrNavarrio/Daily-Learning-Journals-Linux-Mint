Day 2 

_____

12/03/2024 - 9:19 AM
dr ///// paul // DrNavarrio // doc // callhimdoctor // nob

****
     Challenge: Spend at least 30 minutes a day learning Linux.
****
_____

Resources used: 
- Following the plan ChatGPT gave me
- Linux Mint on my ThinkPad
- Westside Gunn blasting on a Bose speaker

_____
 
Today I also followed the plan ChatGPT gave me. 

I ran ls -l on my Desktop (where I have test-folder) and it output:

total 4
drwxrwxr -x 2 nob nob 4096 Dec 3 09:26 test-folder

Not sure what that means so I will ask ChatGPT to explain it. I know d means directory, then rwx means read write execute, but I am not sure why it says that twice and then what all the rest after that means. 

Okay so the first rwx means that I (nob) has read write and execute permissions. The second rwx means that members of the group nob have the same permissions as nob (read write execute). And the r-x means that anyone that 
is not nob or in the nob group only has read and execute permissions, so e.g. they can list the folder's contents and navigate to it but can't modify the contents.

I used chmod +x test.txt to give myself execute permissions on the txt file. Then thought to do the same command, but do -x and see if that removes the permissions. It did. Cool

Was a good day today. Getting used to some of these commands and now can understand the output when I do ls -l. ChatGPT is amazing, such a great tool. It explains things very well. 

- dr
