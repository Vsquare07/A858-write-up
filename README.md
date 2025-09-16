This is the write-up for A858 challenge conducted in IIT-BHU

Team id : cosmic-dragon-656 | Team name : ratlamichatoras

Team members : Pranshu Goyal, Vatsal Varenya, Snehil Soumya, Rajdeep Ghosh, Saumil Yadav

Ok so lets see how the solution goes....

<b><h3>The AAA.txt file on infosec discord</h3></b>

The start is the [AAA.txt](https://github.com/Vsquare07/A858-write-up/blob/main/AAA.txt "hover text"), at first glance it is very annoying but if we count the number of As in each block of As and replace it with the number we get to see a clean bunch of these numbers : `112 97 115 116 101 98 105 110 46 99 111 109 47 107 75 84 120 103 122 70 110`

It is very intuitive to replace the numbers with their respect ASCII charachter and BOOM! we get a pastebin link that contains a [txt file](https://github.com/Vsquare07/A858-write-up/blob/main/Tujhe%20Dikh%20Nahi%20Raha%20Hai.txt "hover text")
This way the stage 1 is completed

<b><h3>The TujheDIkhNahiRaha.txt file</h3></b>

It is just blank code with a dot at the end, what could possibly be the logic behind? If we just go through the lines we will observe that the number of spaces are different. Now we opened this txt file in VScode because it has a feature to show number of spaces and this is a small part of what we saw  
<img width="360" height="500" alt="image" src="https://github.com/user-attachments/assets/28ec247e-ff7a-48f1-ae90-a6f47362c1b0" />

The `->` represents tab and `.` represents space in the above picture. What do we think of when we see things which are classified into two types? BINARY!
Replace `->` with 1 and `.` with 0 and lets see what we get

<img width="240" height="588" alt="image" src="https://github.com/user-attachments/assets/3a95b9d7-a92b-47de-a2f5-79381fca9e5d" />

Hmmmmm, interesting, what if we find the decimal number corresponding to these binary numbers. The next text goes like this

<img width="72" height="476" alt="image" src="https://github.com/user-attachments/assets/a530adb8-b8ca-40b4-be47-9d75adecc8b4" />

The 1s in between looks like garbage, lets ignore it. Now we get a direct intuition to replace them with their ASCII values and finally we arrived at a reddit link : https://www.reddit.com/r/858A/
This way the stage 2 is completed

<b><h3>The search in A858 reddit</h3></b>

*Many posts in this subreddit were distracting, but [this one](https://www.reddit.com/r/858A/comments/1nff30a/help_needed/ "hover text") was very special. Nothing special at first glance, just a screen shot but the crazy part is the tabs opened. The first tab shows [Subreddit Ali3n1nva5i0n](https://www.reddit.com/r/Ali3n1nva5i0n/ "hover text")

Over here QR-3 is simply given in this [post](https://www.reddit.com/r/Ali3n1nva5i0n/comments/1nfejil/there_you_go/)

<img width="750" height="666" alt="image" src="https://github.com/user-attachments/assets/a0217b53-bd70-4097-a55f-f73819ac4eff" />

*Now we went back to A858, where [this post](https://www.reddit.com/r/858A/comments/1ndpj1u/messi_better/ "hover text") looked funny because it says Messi is better with Ronaldo photo. HOWEVER the mods were fighting in the comment and one of them had QR-2 as their profile pic :skull:

<img width="252" height="170" alt="image" src="https://github.com/user-attachments/assets/6f13d65b-de8f-469e-b2b3-88fc2f00fab6" />
<img width="280" height="281" alt="image" src="https://github.com/user-attachments/assets/029ca312-3220-43fa-bfab-6ff12791c044" />

*After scanning through the posts, we came across this [post](https://www.reddit.com/r/858A/comments/1nfgnao/i_love_4chan/ "hover text")

<img width="418" height="226" alt="image" src="https://github.com/user-attachments/assets/b514118a-fdc7-459a-8414-8d4f1c14559d" />

This comment indicated us to join the clash of clans clan. In clan description we found [latitudinal coordinate](https://github.com/Vsquare07/A858-write-up/blob/main/longitude_line.html "hover text") for our next hint.

<img width="238" height="334" alt="image" src="https://github.com/user-attachments/assets/bd93d4ff-567c-4209-b86f-e7960f6b020f" />

Out of all the possible places, we guessed that ABLT is the place and we found the link for QR-4 on the wall

<img width="387" height="516" alt="image" src="https://github.com/user-attachments/assets/b1e0e80d-324a-409e-96c6-d9acbeac2586" /> <img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/e7696f1f-379c-46ce-a250-5539a3b8359f" />




