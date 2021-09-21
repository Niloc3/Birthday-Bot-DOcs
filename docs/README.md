# Birthday Bot Docs

#### [Invite Link](https://discord.com/oauth2/authorize?client_id=797279656595947531&permissions=346176&scope=bot)

## Why does the bot not announce birthdays?

**1st thing to check, have you set the birthday channel.**  
If not the bot has no idea where to wish you a happy birthday and will not send it. Use `b!setchannel <#channel>` to set that channel.

**2nd, has that user set their birthday?**  
Have the user run `b!getbday` and if the bot responds with "You have not set your birthday yet." Look at [Commands](commands.md#setting-your-birthday) to do so.

## When does the bot announce birthdays?

All birthdays will be announced at 12:00 noon in UTC. Once you set your birthday in one server with the Birthday Bot it will be announced in all servers the bot and you share.

<br>

<a class="btn" href="/#/commands">Go to Commands</a>

<style>
    .btn {
	color: white;
	display: inline-block;
	box-sizing: border-box;
	padding-top: 0.3em;
	padding-right: 1em;
	padding-bottom: 0.3em;
	padding-left: 1em;
	margin: 0;
	cursor: pointer;
	border-width: 0;
	border-radius: 4px;
	box-shadow: 0 1px 2px rgba(0,0,0,0.12),0 3px 10px rgba(0,0,0,0.08);

}

