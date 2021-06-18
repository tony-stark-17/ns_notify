To use this script in your own resource you need to trigger either from the client or server side. I provide you the code for both sides


# Client side

exports['ns_notify']:sendNotify("MY TITLE", "MY MESSAGE", 5000, 'success')


# Server side
TriggerClientEvent('ns_notify:sendNotify', src, "MY TITLE", "MY MESSAGE", 5000, 'success')