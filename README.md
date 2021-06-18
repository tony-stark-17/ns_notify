<img src="https://forum.cfx.re/uploads/default/optimized/4X/d/f/d/dfd72d5104c19c2635d49cdde62df6465fa16ad1_2_690x324.png">

To use this script in your own resource you need to trigger either from the client or server side. I provide you the code for both sides


# Client side

exports['ns_notify']:sendNotify("MY TITLE", "MY MESSAGE", 5000, 'success')


# Server side
TriggerClientEvent('ns_notify:sendNotify', src, "MY TITLE", "MY MESSAGE", 5000, 'success')

# Preview
<img src="https://media.discordapp.net/attachments/849140680038416465/855501941726380072/unknown.png">

# Support
You can either write me a personal message or join my discord server: https://discord.gg/HaYe9kNDHK
