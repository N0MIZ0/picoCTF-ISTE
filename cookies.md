***Flag:*** <br>
picoCTF{3v3ry1_l0v3s_c00k135_064663be} <br>
***Approaching the Challenge:*** <br>
I first typed snickerdoodle but nothing happened. <br>
Then opened the inspect page on the website and checked if there were any hidden comments. <br>
Checked if there was some *fishy* file at the source tab and moved on to cookies in the application tab. <br>
After opening cookies from storage, I had one cookie named "name" and value 0. <br>
I tried to change the name and reload the site but it didnt work instead just created another cookie. <br>
Then changed the values few times, and the text on the webpage changed to different types of cookies. <br>
The console tab was empty/showing error. <br>
No other leads. <br>
-x-x-x-x-x-x-x-x-x-x-x- <br>
Instead of random values, doing it one by one kept changing the types of cookies and finally on the value 18, the webpage displayed the flag.
<br>
***Proof:***
1. <br>
![{79195412-63FC-4854-B00C-18EAC4499E2B}](https://github.com/user-attachments/assets/1acbad5c-7636-476d-a102-be387a06482b)
<br>
2. <br>
![{3C4B3987-DF2A-48DB-BA9B-3CD586AEEB45}](https://github.com/user-attachments/assets/fcd8842a-cdd9-4e24-844c-97b8ef808991)
