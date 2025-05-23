# EducationPerfectAUTO
This is a remixed version of https://github.com/s1dny/epbot by s1dney. Updated, Auto Answer (Text-Based Language) and made for Microsoft Edge.
This only works for text-based language questions but it **DOES NOT WORK FOR AUDIO QUESTIONS**.
By using my files and codes you acknowledge that I am not responsible for any trouble or consequences for your actions. **USE AT YOUR OWN RISK**.

**Dependencies:** Node.js, Puppeteer, Dotenv, Microsoft Edge (if Node.js is blocked from dowload Node.js see, Node.js alternatives)

# Download Links

These files were too large to upload to GitHub so I have to share them through MediaFire links:

**epbot (classic with auto login):** https://www.mediafire.com/file/6r5pvxerzk8dewd/epbot.zip/file

**epauto (for non-auto login:** https://www.mediafire.com/file/46unmd3q1qj594u/epauto.zip/file

# Set Up Guide (with auto login)

**Step 1:** Download the .zip file named "epbot" in the MediaFire link and extract it to your local disk **DO NOT DOWNLOAD EPAUTO**

**Step 2:** Open the epbot folder and right-click index.js -> select "Edit in Notepad". Locate the; "const USERNAME = 'YourUsername/EmailHERE'
const PASSWORD = 'YourPasswordHERE'" section and edit the section inside the '' with your EP username and Password to set up the Auto Login, 
then save the edited file. **I cannot access your password through this, if you are not comfortable with inputing your credentials see: Set up 
guide without auto-login**

**If you need help with the above step refer to the image attached below**

![Screenshot 2025-05-22 181345](https://github.com/user-attachments/assets/64c3c39d-3e8d-4196-a4cf-93caf122dd71)

**Step 3:** Open the file and do SHIFT + RIGHT-CLICK -> select "Open command window here". This will open that folder in command prompt. **OR**
Open your Node.js command prompt and run the command "cd [paste the path of epbot]".

**Step 4:** Run the command, "npm i puppeteer" to install puppeteer, "npm i dotenv" to install dotenv and then run the command, "node index.js" 
and it will open Mircosoft Edge.

**See Operation/Controls Guide**

# Set up guide without auto-login

Do the same as the with auto-login but download "epauto" instead of "epbot" (you do not need to do the add username step) and do the command,
"node indext.js" instead of "node index.js".

**See Operation/Controls Guide**

# Operation/Controls Guide

If you are using auto login, let it type in your credentials **DO NOT TOUCH OR IT WILL BREAK (including the login button)** and then wait.

**Word List Refresh:** On the word list you want to auto answer do **Alt + R** to save the word lsit (do for every new page and list). Make
sure the "🔁 Refreshing word list (Alt+R)..." alert appears, if not continue trying (sometiem take few tries).

**Auto answer toggle:** Press start on the list (make sure you have previously do a "Word List Refresh" for that list) then in the answer
box (make sure you have selected it and the typing cursor is visible) do **Alt + S** to toggle auto answer on and off. Make sure the
"🌀 Toggling auto-answer (Alt+S)..." alert appears (if not keep retrying).

# Node.js Alternatives
If you do not want to install node.js use https://replit.com/ and create a node.js Repl and then import the files.

