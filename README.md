# HomeWork 1

Screen shots of linux commands that are used to complete the levels are shown below.

**Bandit Level 0**

The goal of this level is to log into the game using SSH. The host to which need to connect is bandit.labs.overthewire.org. The username is bandit0 and the password is bandit0. Then using ls and cat command I was able to get the password for the next level.

![level 0](https://cloud.githubusercontent.com/assets/18345069/14378936/4c24ab78-fd95-11e5-82d5-25c5853f2294.png)

**Bandit Level 1**

In this level 1 there was a file called “-” in the home directory and it contains the password for the level 2.I used “./” to the absolute path of the file.

![level 1](https://cloud.githubusercontent.com/assets/18345069/14378935/4c218560-fd95-11e5-94e5-6bf25f60a107.png)

**Bandit Level 2**

Level 3 password was stored in a file called "spaces" "in" "this" "filename" located in the home directory in level 2. As the above example I gave the path as "spaces\ in\ this\ filename".

![level 2](https://cloud.githubusercontent.com/assets/18345069/14378933/4c2127a0-fd95-11e5-9447-7bad1f7d6494.png)

**Bandit Level 3**

The password for the level 4 was stored in a hidden file in the inhere directory in level 3. So I added the “a” switch, it displayed all files including hidden files and by using “.” as part of the filename in Linux specifies that the file is a hidden file.

![level 3](https://cloud.githubusercontent.com/assets/18345069/14378932/4c210cc0-fd95-11e5-96f5-d640d4e92c61.png)

**Bandit Level 4**

The password for the level 5 was stored in the only human-readable file in the inhere directory in level 4. Using file command, I found that -file07 is the only file with ASCII text.

![level 4](https://cloud.githubusercontent.com/assets/18345069/14378934/4c215b44-fd95-11e5-97b0-877db8017960.png)

**Bandit Level 5**

The password for the level 6 was stored in a file somewhere under the inhere directory and has all of the following properties: human-readable, 1033 bytes in size, not executable. And also file containing the password is 1033 bytes, so I used the find command to find a file of a specific size.

![level 5](https://cloud.githubusercontent.com/assets/18345069/14378937/4c381b40-fd95-11e5-9a7d-06c0f77dfa13.png)

**Bandit Level 6**

The password for the level 7 was in a file somewhere on the server and have the following characteristics: owned by user bandit7, owned by group bandit6, 33 bytes in size. So I used the find command to find the password.

![level 6](https://cloud.githubusercontent.com/assets/18345069/14378938/4c4def38-fd95-11e5-89af-7bb91901b7c2.png)

**Bandit Level 7**

Password for the level 8 was in the file called “data.txt” which was next to the word “millionth”, time to pipe the output from cat of the file into grep searching for “millionth”.

![level 7](https://cloud.githubusercontent.com/assets/18345069/14378939/4c4e0400-fd95-11e5-9658-29bec13166b5.png)

**Bandit Level 8**

The goal was to the find the password instead the file “data.txt”, the password line only occurs once in the file. So I used the command “sort” and then pipe the output from sort into the command “uniq” with the switch operator “-u” to find the unique string.

![level 8](https://cloud.githubusercontent.com/assets/18345069/14378940/4c4ea996-fd95-11e5-942e-b39be697ac40.png)

**Bandit Level 9**

The password for the level 10 was stored within the file called “data.txt” which contains only a few lines of human-readable strings starting with the character “=”. I used the “strings” command and pipe the output to grep searching for the “=” character.

![level 9](https://cloud.githubusercontent.com/assets/18345069/14378942/4c544a2c-fd95-11e5-83eb-2c0bdf1cfd39.png)

**Bandit Level 10**

The password for the level 11 was stored in the file “data.txt” which contains base64 encoded data. For this I used the “base64” command in Linux to decode the string.

![level 10](https://cloud.githubusercontent.com/assets/18345069/14378941/4c502974-fd95-11e5-86d6-92202251ea3e.png)

**Bandit Level 11**

The password was stored in the data.txt file and all lowercase and uppercase letters have been rotated by 13 potions. For this one, using the "tr" command I was able to reverse it.

![level 11](https://cloud.githubusercontent.com/assets/18345069/14378943/4c5e36ea-fd95-11e5-9d7a-f8e5de49248d.png)

**Bandit Level 12**

![level 12-1](https://cloud.githubusercontent.com/assets/18345069/14378946/4c7ad8b8-fd95-11e5-84d1-2ead484403c2.png)

![level 12-2](https://cloud.githubusercontent.com/assets/18345069/14378944/4c7a8a3e-fd95-11e5-9029-041691a462e4.png)

**Bandit Level 13**

![level 13-1](https://cloud.githubusercontent.com/assets/18345069/14378945/4c7abf72-fd95-11e5-9505-d7bccb898092.png)

![le vel 13-2](https://cloud.githubusercontent.com/assets/18345069/14378931/4c11a622-fd95-11e5-9864-fbf421742c02.png)

**Bandit Level 14**

![level 14](https://cloud.githubusercontent.com/assets/18345069/14378947/4c7bf446-fd95-11e5-868b-e775a174152e.png)

**Bandit Level 15**

![level 15-1](https://cloud.githubusercontent.com/assets/18345069/14378948/4c80bbca-fd95-11e5-9508-640a91c430df.png)
![level 15-2](https://cloud.githubusercontent.com/assets/18345069/14378949/4c86184a-fd95-11e5-816d-0b11b3b0dc3f.png)

**Issues faced** : To complete some levels I had to do additional google searches and refer more reading materials. 
