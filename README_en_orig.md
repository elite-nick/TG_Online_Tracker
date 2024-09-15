# PostAai (aka Telegram Online Tracker) 😞
*modern problems require modern solutions.*

*- nobody 😵*
#### Telegram User Online Activity Tracker
This simple python based program allows a telegram user to know when other users he/she
wishes to know about gets online/offline, and more. 💣 You just need to know their usernames,
to get spying! 🤠 

````bash
X is online right now
X & Y are both online right now
.
.
.
X & Y are both online right now
X & Y are both offline right now
````

The project is implemented using the python3.10 based telethon library, and the Telegram API.
For running the project you would need to have an api_id and and api_hash, which can be 
generated at https://my.telegram.org/apps.

***PS: This project ain't a big deal of code 😏, nor am I learning python with this 😂. $ItHelps 😎***

### 🔪 Features
* 👪 Track if a given list of users are online
* 👫 Track if a given pair of users get online or offline
* 🕶 Works also **if that user's last seen is hidden (!), or you are not in his contacts**

### 🤿 How to Run
1. Git clone this repo or download ZIP
2. Create a python3 venv like `python3 -m venv .`, install `python3`, and `python3-venv` 
if already not done
3. Install project requirements from requirements.txt with pip - `pip install -r requirements.txt`
4. Update the main.py with the usernames, and your api keys
5. Run main.py `python3.10 main.py` or Start.bat! 🎉 (It will keep executing until you exit the program)

### 💉 Use Cases
1. 🤫 Get notified and track if your child is online late nights :P [WIP]
2. 🤔 Know when to start a group conversation, when members of your gang turn up online so that
you guys can start off a convo. at optimal times
2. 🤥 Get notified and track when your someone is online, or perhaps whether they
are lying to you

### ⚰ Known Issues
* There is an API limit for fetching the status, and if we track too frequently, telegram 
would ban the user for 24 hour from using this feature. Telegram App would still be accessible.

---
Made with 💔, during #Covid19 by [@aswinshenoy](https://github.com/aswinshenoy).
