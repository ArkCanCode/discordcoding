# discordcoding
Code With Glitch! A Coding Website On Browser!!
Go to glitch.com
Start A New Project, Click on any you want. Suggest glitch-hello-node

Delete evrything except server.js. Click 'New File' type in discord.js press 'Add New File'

Coding
Making your bot online


const Discord = require('discord.js');
const client = new Discord.Client();

client.once('ready', () => {
    console.log('Ready!');
});

client.login('Your Bot Token')

Bot Status


client.on("ready", () => {
client.user.setPresence({activity: { name: 'Put your status here' }, status: '**the status as in idle,Online and Do Not Disturb**' })
});

Make Bot Send Messages

client.on("message", message =>{
if (message.content === "trigger message here") {
  message.channel.send("bot message here")
                       
