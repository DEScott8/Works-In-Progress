This is a Discord Bot I wrote a while back. On my own system, it's fully functional and does what it needs to do. This was based on a bot tutorial from Digital Trends which you can read here: https://www.digitaltrends.com/gaming/how-to-make-a-discord-bot/

You can see how I took out the original code in the switch/case statement and replaced it with some of my own code. The bot reads input from the chat and uses a regular expression to check the formatting. If the command is in a valid format, then it will proceed to run whatever test you specify it to in order to make certain skill checks. This is meant for Shadowrun campaigns.

A good friend of mine suggested adding a system where you can reroll dice. Shadowrun includes a mechanic called Edge where you can "burn" it to change the result of any rolls. I still need to set time aside to figure out how to implement this. One bottleneck I ran into was Discord's own response times for messages, but I'm also thinking of trying a different approach, so I'm open to suggestions.

You can modify the code as you wish, but bear in mind you will need to generate your own tokens using the Discord API. That can be found in the article posted in the first paragraph. Feedback is welcome!
