ts3anticrash
============

Lua plugin for TS3 to prevent the TS3 client from crashing due to abuse of [img] tags

Setup
-----

For a normal user setup just copy the directory 'ts3anticrash' to 'TS3 base directory/plugins/lua_plugin'.

Just in case you are an admin you may want to take a look at the two config options provided via the variables 'autoban' and 'sendbanmsg'.
If you set the variable 'autoban' to true users trying to abuse [img] tags will be banned automatically.
Additionally you can set 'sendbanmsg' to true to inform other users that the user has been banned.