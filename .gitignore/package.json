const Discord = require('discord.js');
const bot = new Discord.Client();

var prefix = ("*")

bot.on('ready', function() {
    bot.user.setGame("Command: *help");
    console.log("Connectedç");
});

bot.login("NDUxMDUwOTE2MTkyMTkwNDc0.De8Zgg.sj8B6KpobA5-0jz65tGq7lT3_hw");


bot.on('message', message => {
    if (message.content === prefix + "help"){
        message.channel.sendMessage("Liste des commandes: \n -*help");
    }

    if (message.content === "Yo Dieu"){
        message.reply("Yo mon pote !");
        console.log("Commande Yo effectué");
    }
});

bot.on('message', message => {
    if (message.content === prefix + "help"){
        message.channel.sendMessage("Liste des commandes: \n -*help");
    }

    if (message.content === "Yo dieu"){
        message.reply("Yo mon pote !");
        console.log("Commande Yo effectué");
    }
});

