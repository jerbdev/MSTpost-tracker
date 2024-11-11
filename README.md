# MSTpost Tracker

A quick tool to display post information by specific user(s) in Microsoft Teams.

## Quickstart
In order to run the process you will need to be in a web browser console. 

To access the console, select the three lines (or dots or Chrome) at the top right hand side of browswer window. Then select the "More Tools" option. There you will see the option to access the console. In Chrome, you will click "Developer tools" and in Firefox, "Web Developer Tools".

At this point, another window should appear from the bottom of your screen. The current tab is on the "Inspector", but to run this code, we will need to be in the "Console" tab. Within the Console tab there is a terminal where the code will be pasted and ran. 

Copy and paste the code from "main.js" into the terminal. Remember to replace 'John Doe' with your own name.

You should see the results in the other pane of the window.

## Word Cloud
When you have at least a few dozen entires, you can generate a word cloud. You'll need the "all-text-content.json" file too which is created by running `import.py`.

Once that is completed, the word cloud can be generated by simply running `word.py`. A window should appear with the cloud. To save the image click the save icon at the bottom of the window.

There are also two other charts displaying the most frequently used words and a co-occurrance heatmap. These can be saved in the same way.

## About the `data` folder
- After running `app.js` this folder contains the collected replies.
- After running `import.py` this folder contains "all-text-content.json" which is required to run `word.py` successfully.

## Troubleshooting
### there's no data showing
- Check if you're in the correct Teams chat
- Verify your name matches in the script
- Scroll up to load older messages

### the scripts aren't running
- Install packages with: pip install -r requirements.txt
- Ensure you have Python installed.
- Ensure you're in the web browser console
- Update to Python 3.7 or newer
  
### word cloud not working
Run import.py first
Check if you have enough messages collected
Make sure your packages are installed

Need more help? Check Issues or create a new one.

Any issues feel free to contribute. 👍
