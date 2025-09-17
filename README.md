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

*Many posts in this subreddit were distracting such as [this post](https://www.reddit.com/r/858A/comments/1ndptax/click_if_you_are_not_gay_direct_answers/ "hover text") 
had some crazy thing(which we later found is called Obfuscated Javascript), I pasted it in chatgpt😈 and it was rick roll 😢💀.

<img width="1920" height="1048" alt="image" src="https://github.com/user-attachments/assets/65ad029b-9841-48a9-a2d3-2243e1022138" />

, but [this_one](https://www.reddit.com/r/858A/comments/1nff30a/help_needed/ "hover text") was very special. Nothing special at first glance, just a screen shot but the crazy part is the tabs opened. The first tab shows [Subreddit Ali3n1nva5i0n](https://www.reddit.com/r/Ali3n1nva5i0n/ "hover text")

Over here QR-3 is simply given in this [post](https://www.reddit.com/r/Ali3n1nva5i0n/comments/1nfejil/there_you_go/)

<img width="750" height="666" alt="image" src="https://github.com/user-attachments/assets/a0217b53-bd70-4097-a55f-f73819ac4eff" />

*Now we went back to A858, where [this post](https://www.reddit.com/r/858A/comments/1ndpj1u/messi_better/ "hover text") looked funny because it says Messi is better with Ronaldo photo. HOWEVER the mods were fighting in the comment and one of them had QR-2 as their profile pic 💀

<img width="252" height="170" alt="image" src="https://github.com/user-attachments/assets/6f13d65b-de8f-469e-b2b3-88fc2f00fab6" />
<img width="280" height="281" alt="image" src="https://github.com/user-attachments/assets/029ca312-3220-43fa-bfab-6ff12791c044" />

*After scanning through the posts, we came across this [post](https://www.reddit.com/r/858A/comments/1nfgnao/i_love_4chan/ "hover text")

<img width="418" height="226" alt="image" src="https://github.com/user-attachments/assets/b514118a-fdc7-459a-8414-8d4f1c14559d" />

This comment indicated us to join the clash of clans clan. In clan description we found [latitudinal coordinate](https://github.com/Vsquare07/A858-write-up/blob/main/longitude_line.html "hover text") for our next hint.

<img width="238" height="334" alt="image" src="https://github.com/user-attachments/assets/bd93d4ff-567c-4209-b86f-e7960f6b020f" />

Out of all the possible places, we guessed that ABLT is the place and we found the link for QR-4 on the wall

<img width="387" height="516" alt="image" src="https://github.com/user-attachments/assets/b1e0e80d-324a-409e-96c6-d9acbeac2586" /> <img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/e7696f1f-379c-46ce-a250-5539a3b8359f" />

<b><h3>Finding the QR-1 😢(took 80% of the total time)</h3></b>
Continuing our research in Alieninvasion subreddit, a [pokemon post](https://www.reddit.com/r/Ali3n1nva5i0n/comments/1n4di1x/pokemon_is_cool/) had something in its comments. I had no idea but our teammate Pranshu was familiar with ctfs and applied some decoding algorithms on the strings in comments like base64 and we got the following output

<img width="577" height="186" alt="image" src="https://github.com/user-attachments/assets/3cb4976a-ad2d-4590-89e4-37650707158b" />

Notice that all the outputs had 858 in them, moreover one of them says 8:58 is related to the `KEY` _this part is useful later_

After this we were clueless what to do!!!! VERY FRUSTATING

This part was so much time taking that we had to ask for a hint from a senior, he told us to stick to A858 reddit :)

After spending even more time [this post](https://www.reddit.com/r/858A/comments/1nffqdm/found_a_new_cipher_the_game_of_secrets_just_got/ "hover text") was our lead after a long time 🥳

The pastebin txt in its comments had a code which lacked the string key which had to be decoded. We tried putting the previously found strings but it didnt work. Soon we came across [another post](https://www.reddit.com/r/858A/comments/1nfgc00/my_brain_is_fried/ "hover text") which had a comment as follows

<img width="744" height="256" alt="image" src="https://github.com/user-attachments/assets/41ebe722-c372-433b-a388-e1cd24b5d419" />

Our teammate Pranshu combined the code and the string which gave us the googledrive link that contained this picture : 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/ba3838c2-536d-4600-88ea-9d845917384e" />

It didnt took us much time to realise this place is near LC, we went to this tree and a qr code that took us to QR-1!!!!
<img width="277" height="277" alt="image" src="https://github.com/user-attachments/assets/5607d07c-a1c9-47d2-9f92-35ff69d19cbb" /><img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/9a4f631f-8bab-46ad-bc6b-b0eeb848efeb" />

We had all the QR CODES!!!!!
We put them together using Whatsapp 💀 like this

<img width="549" height="544" alt="image" src="https://github.com/user-attachments/assets/31dee72a-5ba9-4675-8ac3-8c79dd7a4cc6" />

After scanning we got the final string and the challenge was completed.
