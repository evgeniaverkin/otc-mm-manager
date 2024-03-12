This is a quick fork of the original repo https://github.com/CreativeBuilds/otc-mm-manager
To run this, you need to have the .env file.
Example values:
```
DISCORD_TOKEN=MTIxNjYxODAyOTMyOTQxNjIxNA.GG9QMr.Tt_kvZUeF3ORM9-mnkl8S9AFuPZb4WWtrcJrDI
MIDDLEPERSON_ROLE=1216620076673794099
DEV_LOG=true
```

Note that we have removed the TICKET_CHANNEL because the original code in the repo was messy and broken. So we tried best to run this code with minimal changes.

The code expects a public 'tickets' channel to be present in the server. The code will create a new channel for each ticket and will move the ticket to the new channel. 
