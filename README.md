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

Now we get a direct intuition to replace them with their ASCII values and finally we arrived at a reddit link : https://www.reddit.com/r/858A/
This way the stage 2 is completed

<b><h3>The search in A858 reddit</h3></b>
