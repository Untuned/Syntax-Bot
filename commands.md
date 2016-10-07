Commands:
=========

X specifies a number  
Arguments between ( ) are optional

Note: Commands are edited from the original bot.


Host
----

|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!kill | | shut down the bot |
|!logout | | logs out account bot is hosted on |
|!refresh | | refreshes the browser of whoever runs the bot |

Co-Host
-------
|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!reload | | reload the bot |

Manager
-------

|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!afklimit | X | sets the maximum afk time |
|!afkremoval | | toggles the afk check |
|!afkreset | @user | resets the afk time of user |
|!autodisable | | toggle the autodisable |
|!autoskip | | skips songs automatically when they're done (use when the circles-bug happens) |
|!botname | (botname) | change the default bot name |
|!bouncer+ | | toggle bouncer+ |
|!clearchat | |clears the chat |
|!commanddeletion | | toggles if bot commands gets deleted |
|!cycle | | toggle DJ cycle |
|!cycleguard | | toggles the cycleguard |
|!cycletimer | X | set the maximum DJ cycle time for when cycleguard is enabled |
|!historyskip | | toggles the history skip |
|!language | (language) | specify the language you would like the bot to use |
|!lock | | lock the waitlist |
|!lockdown | | lock down the room: only staff can chat |
|!lockguard | | toggle the lockguard |
|!locktimer | X | set the maximum time the waitlist can be locked if lockguard is enabled |
|!maxlength | X | specify the maximum length a song can be when timeguard is enabled |
|!motd | (X)/(message) | when no argument is specified, returns the Message of the Day, when X is specified, the MotD is given every X songs, when "message" is given, it sets the MotD to message |
|!restricteta | | toggles the restriction on eta: grey users can use it once an hour |
|!skippos | X | set the position to which skip and lockskip moves the dj |
|!songstats | | toggle song statistics |
|!timeguard | | toggle the timeguard |
|!togglebl | | toggle the blacklist |
|!togglemotd | | toggle the motd |
|!togglevoteskip | | toggle the voteskip |
|!unlock | | unlock the waitlist |
|!usercmdcd | X | set the cooldown on commands by grey users |
|!usercommands | | toggle user commands |
|!voteskip | (X) | when no argument is specified, returns the current voteskip limit, when X is specified, voteskip limit is updated to the new specified limit. |
|!welcome | | toggle the welcome message on user join |

Bouncer+
--------

|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!add | @user | add user to the waitlist |
|!dclookup / !dc | (@user) | do dclookup for user |
|!deletechat | @user | delete all the chats by a certain user |
|!filter | | toggles the chat filter |
|!forceskip | | forceskips the current song |
|!remove | @user | remove user from the waitlist |

Bouncer
-------

|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!active | (X) | shows how many users chatted in the past X minutes. If no X specified, 60 is set as default |
|!afktime | @user | shows how long user has been afk |
|!ban | @user | bans user for 1 day |
|!blacklist / !bl | blacklist name (OP, NSFW, BANNED are the default blacklists) | add the song to the specified blacklist |
|!blinfo | | get information required to blacklist a song |
|!english | @user | ask user to speak english (asked in the language they set plug to) |
|!eta | (@user) | shows when user will reach the booth |
|!jointime | @user | shows how long the user has been in the room |
|!kick | (X) | kicks user for X minutes, default is 0.25 minutes (15 seconds) |
|!lockskip | (reason) | skips, locks and moves the dj back up (the position can be set with !skippos) |
|!move | @user (X) | moves user to position X on the waitlist, default is position 1 |
|!mute | @user/(X) | mute user, for X minutes if X is specified, otherwise for an undefined period |
|!sessionstats | | display stats for the current session |
|!skip | (theme, op, history, mix, sounc, nsfw, unavailable) | skips the dj using smartskip. actions such as locking and moving user depends on various factors (the position the dj is moved to can be set with !skippos) |
|!status | | display the bot's status and some settings |
|!unban | @user | unban user |
|!unmute | @user/all | unmute user |
|!voteratio | @user | display the vote statistic for a user |
|!whois | @user | returns plug related information about user |

User
----

|Command | Arguments |  Description |
|:------:|:-------------:|:--------------------------------------:|
|!8ball | (message) | ask the bot a question, the bot will return random variations of a yes or no answer. |
|!autowoot | | links to RCS, the advised script/plugin to use for autowooting |
|!ba | | explains the Brand Ambassador rank |
|!commands | | gives a link to the commands |
|!cookie | (@user) | give a cookie to user |
|!dclookup / !dc | | use dclookup on yourself |
|!emoji | | a link to a list with emoji's |
|!eta | | shows how long before you reach the booth |
|!fb | | links to the room's Facebook page (if set in the settings) |
|!ghostbuster | @user | checks if user is ghosting |
|!gif | (message) | returns gif (from giphy) related to the tag provided. Returns a random gif if no tags are provided. |
|!help | | links to an image to help get people started on plug |
|!link | | give a link to the current song |
|!op | | links to the OverPlayed list (if set in the settings) |
|!ping | | pong! |
|!rules | | links to the rules (if set in the settings) |
|!theme | | links to the room's theme (if set in the settings) |
|!website | | links to the room's website (if set in the settings) |
|!youtube | | links to the room's youtube page (if set in the settings) |
