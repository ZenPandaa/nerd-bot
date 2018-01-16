const Discord = require('discord.js');
const bot = new Discord.Client();

bot.on('messsage', (message) => {

    if(message.content == 'hey') {
        //message.reply('Hello!');
        message.channel.sendmessage('hello');

    }

});

bot.login('NDAxNTU1MTA2MTcwMDExNjYx.DTr44g.Bl3LyTeGscBFMe5dgRC_fJxCnvk');
