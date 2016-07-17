# [TeleSeed](https://telegram.me/TeleSeed)

[![https://gitter.im/SEEDTEAM/TeleSeed](https://badges.gitter.im/SEEDTEAM/TeleSeed.svg)](https://gitter.im/SEEDTEAM/TeleSeed?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

**An advanced and powerful administration bot based on [yagop/telegram-bot](https://github.com/yagop/telegram-bot) licensed under the [GNU General Public License](https://github.com/SEEDTEAM/TeleSeed/blob/master/LICENSE)**.
# Features

* **A powerful antispam system with custom sensitivity for each group**
* **Multiple realms (admin groups)**
* **Recalcitrant to any kind of spamming (X/Y bots, name/photo changers, etc.)**
* **Global banning**
* **Broadcast to all groups**
* **Group and  links**
* **Kick, ban and unban by reply**
* **Groups, ban and global ban list**
* **Logging anything that happens in a group**
* **Invitation by username**
* **Group administration via private messages**
* **Only mods, owner and admin can add bots in groups**
* **Arabic lock**
* **Lock TgService**
* **Chat list**
* **And more!**

<<<<<<< HEAD

* * *

## Commands
TeleSeed has several commands that are only usable at certain ranks.


## General Commands
| Command | Description |
|:--------|:------------|
| [#!/]id | Returns group/SuperGroup ID or user id in pm. |
| [#!/]teleseed | Returns bot information. |


## Private Message Commands
| Command | Description |
|:--------|:------------|
| [#!/]help | Returns help text. |
| [#!/]superhelp | Returns SuperGroup help text. |
| [#!/]chats | Returns public chats in a message(s). |
| [#!/]chatlist | Returns public chats in a .txt document. |
| [#!/]join [GroupID] | Join a public chat by id |


## Moderator commands 

| Command | Description | Groups? | SuperGroups? |
|:--------|:------------|:--------|:-------------|
| [#!/]info | Returns general info about the SuperGroup. | N | Y |
| [#!/]admins | Returns SuperGroup admins list. | N | Y |
| [#!/]modlist | Returns Moderator list. | Y | Y |
| [#!/]owner | Returns group/SuperGroup owner. _Can be used by any user_| Y | Y |
| [#!/]bots | Lists bots in SuperGroup. | N | Y |
| [#!/]who | Lists all users in group *SuperGroup returns .txt document list. | Y | Y |
| [#!/]wholist | Lists all users in group in .txt document. | Y | N |
| [#!/]block | Kicks a user from SuperGroup **Adds user to blocked list**. | N | Y |
| [#!/]kick | kicks user from group. | Y | N |
| [#!/]ban | Bans user from the group/SuperGroup. | Y | Y |
| [#!/]unban | Unbans user from group/SuperGroup. | Y | Y |
| [#!/]id [username<html>&#124;</html>reply] | For userID's: !id @username (**ONLY IN SuperSroups**) or reply `!id` in any group. | Y | Y |
| [#!/]id from | Returns ID of user a message is forwarded from. | N | Y |
| [#!/]kickme | Kicks user from SuperGroup / In SuperGroup: **Must be unblocked by owner or use `#join` by pm to return** | Y | Y |
| [#!/]setowner | Sets group/SuperGroup owner. | Y | Y |
| [#!/]promote | Promote a group/SuperGroup moderator. | Y | Y |
| [#!/]demote | Demote a group/SuperGroup moderator. | Y | Y |
| [#!/]setname | Set group/SuperGroup name. | Y | Y |
| [#!/]setphoto | Set group/SuperGroup photo. | Y | Y |
| [#!/]setrules | Set group/SuperGroup rules. | Y | Y |
| [#!/]setabout |  Sets the about section in chat info(members list) | N | Y |
| [#!/]set about |  | Y | N |
| [#!/]save [value] <text> | Sets extra info for group/SuperGroup by value. | Y | Y |
| [#!/]get [value] | Returns extra info for group/SuperGroup by value. | Y | Y |
| [#!/]newlink | Generate a new group/SuperGroup link. | Y | Y |
| [#!/]setlink | Set a new SuperGroup link _If bot is not creator_. | N | Y |
| [#!/]link | Retrieves the group/SuperGroup link. | Y | Y |
| [#!/]rules | Retrieves the group/SuperGroup rules. | Y | Y |
| [#!/]lock [setting](#settings-settings) | Lock group/SuperGroup settings. | Y | Y |
| [#!/]unlock [setting](#settings-settings) | Unlock group/SuperGroup. | Y | Y |
| [#!/]mute [mute]#mutes-mutes) | mute group message types. | Y | Y |
| [#!/]unmute [mute](#mutes-mutes) | unmute group message types. | Y | Y |
| [#!/]setflood [value](#settings-settings) | Set [value] as flood sensitivity.| Y | Y |
| [#!/]muteuser [username<html>&#124;</html>id<html>&#124;</html>reply] | Mute and unmute a user in chat. ***If a muted user posts a message, the message is deleted automaically only owners can mute <html>&#124;</html> mods and owners can unmute*** | Y | Y |
| [#!/]mutelist | Returns list of muted users in group/SuperGroup. | Y | Y |
| [#!/]muteslist | Returns mutes for group/SuperGroup. | Y | Y |
| [#!/]settings | Returns a list of group/SuperGroup settings. | Y | Y |
| [#!/]stats | Returns simple message statistics in a .txt document. | Y | Y |
| [#!/]statslist | Returns simple message statistics in a message. | Y | Y |
| [#!/]banlist | Returns group/SuperGroup banlist. | Y | Y |
| [#!/]clean [rules<html>&#124;</html>about<html>&#124;</html>modlisthtml>&#124;</html>bots<html>&#124;</html>mutelist] | Clears rules, about, modlist, bots, or mutelist | Y | Y |
| [#!/]del | Deletes a message by reply. | N | Y |
| [#!/]res [username] | Returns users name and id by username. | Y | Y |
| [#!/]log | Returns group logs.***In SuperGroups:*** Search for kick reasons using [#RTL<html>&#124;</html>#spam<html>&#124;</html>#lockmember] | Y | Y |

## Owner commands

| Command | Description |   groups/SuperGroups? |  In private? |
|:--------|:------------|:----------------------|:-------------|
| [#!/]muteuser [username<html>&#124;</html>id<html>&#124;</html>reply] | Mute and unmute a user in chat.***If a muted user posts a message, the message is deleted automaically / only owners can mute / mods and owners can unmute*** |  | N |
| [#!/]all | Returns all available information about current group. | Y | N |
| [#!/]all [GroupID] | Returns all available information about group by GroupID. | Y | N |
| [#!/]owners [GroupID] [kick<html>&#124;</html>ban<html>&#124;</html>unban] [UserID] | Kick, ban, or unban a user from a group by GroupID and UserID. | N | Y |
| [#!/]owners [GroupID] clean  [modlist<html>&#124;</html>rules<html>&#124;</html>about] | Clear options by GroupID. | N | Y |
| [#!/]owners [GroupID] setflood [value] | Set flood for a group by GroupID and a value [1-5]. | N | Y |
| [#!/]owners [GroupID] lock [setting] | Lock settings for a group by GroupID. | N | Y |
| [#!/]owner [GroupID] unlock [setting] | Unlock settings for a group by GroupID. | N | Y |
| [#!/]owners [GroupID] new link | Create a new group link by GroupID.  | N | Y |
| [#!/]owners [GroupID] get link | Returns group link by GroupID. | N | Y |
| [#!/]changename [GroupID] [name] | Change a group's name by GroupID. | N | Y |
| [#!/]changrules [GroupID] [rules] | Change a group's rules by GroupID. | N  | Y |
| [#!/]changeabout [GroupID] [about] | Change a group's about by GroupID. | N | Y |
| [#!/]loggroup [GroupID] | get group logs by GroupID. | N | Y |

## Admin commands

| Command | Description | Groups? | SuperGroups? | Realms? |
|:--------|:------------|:--------|:-------------|:--------|
| [#!/]creategroup [Name] | Create a group and add it to moderation.json. | Y | Y | Y |
| [#!/]createrealm [Name] | Create a realm and remove it from moderation.json. | Y | Y | Y |
| [#!/]add | Add a group to moderation.json. | Y | Y | Y |
| [#!/]rem | Remove a group from moderation.json. | Y | Y | Y |
| [#!/]rem [GroupID] | Remove a group from moderation by GroupID. | Y | Y | Y |
| [#!/]setname [Name] | Set realm name. | N | -- | Y |
| [#!/]setabout [group<html>&#124;</html>sgroup] [GroupID] [Text] | Set a group's about text. | Y | Y | Y |
| [#!/]setrules [group<html>&#124;</html>sgroup] [GroupID] [Text] | Set a group's rules. | Y | Y | Y |
| [#!/]lock [GroupID] [setting] | Lock a group's setting. | Y | Y | Y |
| [#!/]lock [GroupID] [setting] | Lock a group's setting. | Y | Y | Y |
| [#!/]unlock [GroupID] [setting] | Unlock a group's setting. | Y | Y | Y |
| [#!/]who | Get a list of members in group/realm. | Y | Y | Y |
| [#!/]wholist | Get a .txt document list of members in group/realm. | Y | Y | Y |
| [#!/]type | Get group type. | Y | Y | Y |
| [#!/]addlog | Add a Log_SuperGroup for GBan log. | N | Y | N |
| [#!/]remlog | Remove a Log_SuperGroup for GBan log. | N | Y | N |
| [#!/]kill chat [GroupID] | Kick all users and remove a group from moderation. | Y | Y | Y |
| [#!/]kill realm [RealmID] | Kick all users and remove a realm from moderation. | Y | Y | Y |
| [#!/]banall [id<html>&#124;</html>usename] | Ban a user from all moderated groups where bot is an admin (#global_ban) | Y | Y | Y |
| [#!/]unbanall [id<html>&#124;</html>usename] | Unban a user from all moderated groups where bot is an admin (#global_ban) | Y | Y | Y |
| [#!/]gbanlist [id<html>&#124;</html>usename] | Returns a list of all globally banned user | Y | Y | Y |
| [#!/]list groups | Returns a list of all groups. | Y | Y | Y |
| [#!/]list realms | Returns a list of all realms. | Y | Y | Y |
| [#!/]whitelist | User/Bot will not be subject to message checks. | Y | Y | Y |
| [#!/]support | Promote user to support. | Y | Y | Y |
| [#!/]-support | deomote user from support. | Y | Y | Y |
| [#!/]pm [UserID] <text> | Sends a private message to a user by UserID. | Y | Y | Y |
| [#!/]import <GroupLink> | Bot joins a group by GroupLink. | Y | Y | Y |
| [#!/]pmblock [UserID] | Block a user from bot private message and bot photo. | Y | Y | Y |
| [#!/]pmunblock [UserID] | Unblock a user from bot private message and bot photo. | Y | Y | Y |
| [#!/]markread [on<html>&#124;</html>off] | Toggle bot to doubble check or not doubble check messages. | Y | Y | Y |
| [#!/]setbotphoto | Set bot photo. | Y | Y | Y |
| [#!/]contactlist | Bot will generate a list of all it's contacts***and send it by private message of command sender  | Y | Y | Y |
| [#!/]dialoglist | Bot will generate a list of all it's private message users***and send it by private message of command sender  | Y | Y | Y |
| [#!/]delcontact | Delete bot contact. | Y | Y | Y |
| [#!/]reload | Reloads all bot plugins | Y | Y | Y |
| [#!/]updateid | Adds long_id to moderation data for groups. | Y | Y | Y |
| [#!/]!bc [GroupID] [text] | This command will send text to [GroupID]| Y | Y | Y |
| [#!/]leave | Bot will leave that group and can only be re-invited by an admin with bot phone number | Y | Y | Y |
| [#!/]mp | (Mod Promote) Set user as a mod of supergroup. **TESTING** | N | Y | N |
| [#!/]md | (Mod demote) Removes user from mod of supergroup. **TESTING**| N | Y | N |

## Sudo Commands 

| Command | Groups? | SuperGroups? | Realms? |
|:--------|:--------|:-------------|---------|
| [#!/]addadmin [id<html>&#124;</html>username] | Set a user as bot admin. | Y | Y | Y |
| [#!/]removeadmin [id<html>&#124;</html>username] | Remove a user from bot admin. | Y | Y | Y |
| [#!/]sync_gbans | Sync your GBans with official @TeleSeed | Y | Y | Y |


## Settings 

| Command | Groups? | SuperGroups? |
|:--------|:--------|:-------------|
| <html>&#91;</html>#!/](un)lock links | Y | Y |
| <html>&#91;</html>#!/](un)lock flood | Y | Y |
| <html>&#91;</html>#!/]setflood [5-20] | Y | Y |
| <html>&#91;</html>#!/](un)lock bots | Y | N |
| <html>&#91;</html>#!/](un)lock spam | Y | Y |
| <html>&#91;</html>#!/](un)lock arabic | Y | Y |
| <html>&#91;</html>#!/](un)lock member | Y | Y |
| <html>&#91;</html>#!/](un)lock leave | Y | N |
| <html>&#91;</html>#!/](un)lock RTL | Y | Y |
| <html>&#91;</html>#!/](un)lock tgservice | N | Y |
| <html>&#91;</html>#!/](un)lock sticker | Y| Y |
| <html>&#91;</html>#!/]public [yes<html>&#124;</html>no] | Y | Y |
| <html>&#91;</html>#!/](un)lock strict | N | Y |

/lock [setting] and /unlock [setting]: sets allowed actions and content for groups/SuperGroups
	***/lock strict*** in a supergroup, if strict is locked users will be kicked for violations of settings or mutes

/public [yes|no]: Set group/SuperGroup visibility in pm `!chats` or `!chatlist` commands.


### Mutes

| Command |
|:--------|
| [#!/]mute audio |
| [#!/]mute video |
| [#!/]mute photo |
| [#!/]mute documents |
| [#!/]mute gifs |
| [#!/]mute text |
| [#!/]mute all |

**Groups: If "muted" message type: user is kicked if message type is posted**

**SuperGroups: A "muted" message type is auto-deleted if posted **

### Ranks 

| Rank | Description |
|:------|:------------|
| Banned | Cannot enter the group(s). |
| User | Default rank. |
| Moderator | Can set settings and kick/ban/unban users from a group. Can unmute users. |
| Owner | Can mute users. Can promote/demote moderators. Can set SuperGroup admins. |
| Support | Can globally unban users. Acts as owner of all groups. |
| Administrator | Can globally ban/unban users. Can promote/demote owners. |
| Sudo | Can add[#!/]remove groups. Can broadcast. Can promote/demote administrators. |

Each higher status inherits the privileges of the lower status.

**You can use "#", "!", or "/" to begin all commands

* * *
=======
**Table of Contents**
- [TeleSeed](#teleseed)
- [Features](#features)
- [Commands](#commands)
	- [Admins commands](#admins-commands)
		- [Realm creation](#realm-creation)
		- [Group creation](#group-creation)
		- [Adding and removing realms](#add-or-remove-realms)
		- [Adding and removing groups](#add-or-remove-groups)
		- [Leaving groups](#leaving)
		- [Everything about groups](#everything-about-groups)
		- [Setting descriptions in realm](#setting-description-in-realm)
		- [Setting group names in realm](#setting-group-name-in-realm)
		- [Setting rules in realm](#setting-rules-in-realm)
		- [Locking group names/photos/flood/members in realm](#lock-groups-namefloodphotomember-in-realm)
		- [Unlocking group names/photos/flood/members](#unlock-groups-namefloodphotomember)
	- [Group settings in realm](#group-setting-in-realm)
		- [Adding admins](#add-admin)
		- [Removing admins](#remove-admin)
		- [Admin/group listing in realm](#adminsgroup-list-in-realm)
		- [Broadcasting](#broadcast)
		- [Realm help](#realm-help)
	- [Global ban commands](#global-ban-commands)
		- [Set group owner](#set-group-owner)
		- [Bot stats](#bot-stats)
	- [Owner and mod commands](#owners-and-mods-commands)
		- [Hammer](#hammer)
		- [Locking a group's name/members/bots/arabic/flood](#group-namememberarabicfloodbots-lock)
		- [Unlocking a group's name/members/bots/arabic/flood](#group-namememberarabicfloodbots-unlock)
		- [Cleaning a group's modlist/rules/about/members](#group-modlistrulesaboutmember-clean)
		- [Seting a group's rules/about](#set-groups-rulesabout)
		- [Setting or changing a group's owner](#setting-or-changing-group-photo)
		- [Setting or changing a group's photo](#setting-or-changing-group-photo)
		- [Changing a group's name](#changing-group-name)
		- [Group links](#group-link)
		- [Promoting and demoting mods](#promote-and-demote-mods)
		- [Resolving usernames](#resolve-username)
		- [Flood sensitivity](#flood-sensitivity)
		- [Group rules and about](#group-rules-and-about)
		- [Group settings](#group-settings)
		- [Modlist](#modlist)
		- [Help](#help)
		- [Owner](#owner)
		- [Save and Get](#save-and-get)
		- [Id](#id)
		- [Group stats](#group-stats)
		- [Member list](#member-list)
		- [Group help](#group-help)
	- [In private commands](#in-private-commands)
		- [Hammer](#hammer)
		- [Cleaning](#cleaning)
		- [Setting flood sensitivity](#setting-flood-sensitivity)
		- [Locking a group's members/name](#lock-groups-membername)
		- [Unlocking a group's members/name](#unlock-groups-membername)
		- [Group link](#group-link)
		- [Changing name/rules](#change-namerulesname)
		- [Group log](#group-log)
		- [Join](#join)
- [Installation](#installation)
	- [One command](#one-command)
	- [Realm configuration](#realm-configuration)
- [Support and development](#support-and-development)
- [Special thanks to:](#special-thanks-to)
- [Our team!](#our-team)


# Commands
## Admins commands
**Only admins and sudo users can run these commands.**
### Group creation
>[!/]creategroup [group name]
>
>>[!/]creategroup SEED
>>>will create a group
>>>
>>>_Only works in realms for admins but, sudo users can use it everywhere_

### Realm creation
>[!/]createrealm [realm name]
>
>>[!/]createrealm SEED
>>>will create a realm
>>>
>>>_Only works in realms for admins but, sudo users can use it everywhere_

### Add or remove realms
>[!/]add realm
>>This command will add that group
>
>[!/]rem realm
>>This command will remove that group


### Add or remove groups
>[!/]add
>>This command will add that group
>
>[!/]rem
>>This command will remove that group

### Leaving
>[!/]leave
>>Bot will leave that group

### Everything about groups
>[!/]all
>>This command will return everything about that group
>
>[!/]all [group_id]
>>_Only onwer, admin and sudo users can use this command_


### Setting description in realm
> [!/]setabout [group_id] [text]
>>[!/]setabout 123456789 about
>>>This command will set [text] as description of [group_id]


### Setting group name in realm
> [!/]setname [group_id] [text]
>>[!/]setname 123456789 SEED
>>>This command will set [text] as name of [group_id]

### Setting rules in realm
> [!/]setrules [group_id] [text]
>>[!/]setrules 123456789 rules !
>>>This command will set [text] as rules of [group_id]


### Lock groups name|flood|photo|member in realm
> [!/]lock [group_id] [name|flood|photo|member]
>>[!/]lock 123456789 name
>>>This command will lock name|flood|photo|member of [group_id]


### Unlock groups name|flood|photo|member
> [!/]unlock [group_id] [name|flood|photo|member]
>>[!/]unlock 123456789 name
>>>This command will unlock name|flood|photo|member of [group_id]

## Group setting in realm
>[!/]setting [group_id]
>>[!/]setting 12345678
>>>This command will return settings of [group_id]

### Add admin
>[!/]addadmin [username]
>>[!/]addadmin @username
>>>This command will add username as admin
>>>
>>>_Only works in realms_

### Remove admin
>[!/]removeadmin [username]
>
>>[!/]removeadmin @username
>>>This command will add username as admin
>>>
>>>_Only works in realms_ [username]

### Admins|group list in realm
>[!/]list [admins|groups]
>>[!/]list groups
>>>This command will return admins|groups list

### Broadcast
>[!/]broadcast [text]
>>[!/]broadcast Hello !
>>>This command will send text to all groups
>>>
>>>_Only sudo users can run this command_
>
>[!/]bc [group_id] [text]
>>[!/]bc 123456789 Hello !
>>>This command will send text to [group_id]

## Global ban commands
>[!/]banall [id]
>>[!/]banall 123456789
>>>This commands will globally ban [id]
>
>/sync_gbans
>>Sync your global bans with teleseed
>
>[!/]unbanall [id]
>>[!/]unbanall 123456789
>>>This commands will remove [id] from global bans
>
>[!/]gbanlist
>>This command will return global bans ids
>
>[!/]banlist [group_id]
>>[!/]banlist 123456789
>>>This command will return banned user of [group_id]

### Set group owner
>[!/]setgpowner [group_id] [User_id]
>>[!/]setgpowner 123456789 987654321
>>>This command will set [User_id] as the owner of [group_id]

### Bot stats
>[!/]stats teleseed
>>This command will return bot stats

# Realm Help
>[!/]help
>>Get realm commands list




## Owners and mods commands

_Sudo users and admins can also use this commands in all groups_

### Hammer

>[!/]kick [username|id]
>>[!/]kick @useranme
>>[!/]kick 123456789
>>>This command will remove that user
>
>[!/]ban [username|id]
>>[!/]ban @username
>>[!/]ban 123456789
>>>this command will ban and remove that user
>
>[!/]unban [id]
>>[!/]unban 12345678
>>>This command will unban that user
>
>[!/]banlist
>>This command will return bans list

### Group name|member|arabic|flood|bots lock
>[!/]lock [name|member|arabic|flood|bots]
>>[!/]lock flood
>>>This command will lock name|member|arabic|flood|bots of groups

### Group name|member|arabic|flood|bots unlock
>[!/]unlock [name|member|arabic|flood|bots]
>>[!/]unlock flood
>>>This command will unlock name|member|arabic|flood|bots of groups

### Group modlist|rules|about|member clean
>[!/]clean [modlist|rules|about|member]
>>[!/]clean modlist
>>>This command will clean modlist|rules|about|member
>>>_/clean member will kick all users except owner,admins and bot and it's for owners only_

### Set groups rules|about
>[!/]set [rules|about] [text]
>>[!/]set rules don't spam!
>>
>>No NSFW
>>> This command will set [text] as the rules|about of groups

### Setting or changing group owner
>[!/]setowner [id]
>>[!/]setowner 123456789
>>>This command will set id as owner of that group

### Setting or changing group photo
>[!/]setphoto
>> This command will change or set group photo
>>_also locks photo_

### Changing Group name
>[!/]setname [name]
>>[!/]setname SEED
>>>This command will set [name] as name of groups

### Group link
>[!/]newlink
>>This command will revoke group link
>
>[!/]link
>>This command will return group link

### Promote and demote mods
>[!/]promote [username]
>>[!/]promote @username
>>>This command will promote @username as moderator
>
>[!/]demote [username]
>>[!/]demote @username
>>> This command will demote @username

### Resolve username
>[!/]res [username]
>>[!/]res @username
>>>This command will return info about that username

### Flood sensitivity
>[!/]setflood [value]
>>[!/]setflood 15
>>> will set flood sensitivity to [value]

### Group rules and about
>[!/]about
>>This command will return group description
>
>[!/]rules
>>This command will return group rules
>>>_normal users can use it too_

### Group settings
>[!/]setting
>>This command will return group settings

### Modlist
>[!/]modlist
>>This command will return group moderators
>>>_normal users can use it too_

### Help
>[!/]help

### Owner
>[!/]owner
>>This command will return owners id

### Save and get
>[!/]save [title] [text]
>>[!/]save spam Don't spam !
>>>This command will save text as that title
>
>[!/]get [title]
>>[!/]get spam
>>>This command will return text of that title

### Id
>[!/]id
>>This command will return user or group id
>>_can be triggered by reply_
>>
>>_Normal users can use it_

### Group stats
>[!/]stats
>>This command will return group message statistic in a .txt file
>
>[!/]statslist
>>This command will return group message statistic

### Member list
>[!/]who
>>This command will return member list in a .txt file
>
>[!/]wholist
>>This command will return member list

# Group Help
>[!/]help
>>Get commands list



## In private commands

**These commands only works in bots private**

### Hammer
>[!/]owners group_id [kick|ban|unban] user_id
>>[!/]owners 1234567 kick 1234567

### Cleaning
>[!/]owners group_id clean  [modlist|rules|about]
>>[!/]owners 1234567 clean modlist

### Setting flood sensitivity
>[!/]owners group_id setflood value
>>[!/]owners 1234567 setflood 17

### Lock groups member|name
>[!/]owners group_id lock [member|name]
>>[!/]owners 1234567 lock member

#### unlock groups member|name
>[!/]owner group_id unlock [member|name]
>>[!/]owners 1234567 unlock name

### Group link
>[!/]owners group_id get link
>>[!/]owners 1234567 get link
>
>[!/]owners group_id new link
>>[!/]owners 1234567 new link

### Change name|rules|name
>[!/]changename [group_id] [name]
>>[!/]changename 123456789 SEED
>
>[!/]changrules [group_id] [rules]
>>[!/]changrules 123456789 rules !
>
>[!/]changeabout [group_id] [about]
>>[!/]changeabout 123456789 about !

### Group log
>[!/]loggroup [group_id]
>>[!/]loggroup 123456789

### Join
>[!/]oin [group_id]
>> This command will add user in [group_id]


**U can use both "/" and "!"**
>>>>>>> refs/remotes/origin/master

# Installation

```sh
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
<<<<<<< HEAD
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
=======
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make autoconf unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev
>>>>>>> refs/remotes/origin/master

# Let's install the bot.
cd $HOME
git clone https://github.com/SEEDTEAM/TeleSeed.git -b supergroups
cd TeleSeed
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command (useful for VPS deployment) on Debian-based distros, use:
```sh
#https://github.com/yagop/telegram-bot/wiki/Installation
<<<<<<< HEAD
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev libjansson* libpython-dev make unzip git redis-server g++ autoconf -y --force-yes && git clone https://github.com/SEEDTEAM/TeleSeed.git -b supergroups && cd TeleSeed && chmod +x launch.sh && ./launch.sh install && ./launch.sh
=======
sudo apt-get update; sudo apt-get upgrade -y --force-yes; sudo apt-get dist-upgrade -y --force-yes; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev libjansson* libpython-dev make autoconf unzip git redis-server g++ -y --force-yes && git clone https://github.com/SEEDTEAM/TeleSeed.git && cd TeleSeed && chmod +x launch.sh && ./launch.sh install && ./launch.sh
>>>>>>> refs/remotes/origin/master
```

* * *

### Realm configuration

After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
```
  sudo_users = {
    110626080,
    103649648,
    111020322,
    0,
    YourID
  }
```
Then restart the bot.

Create a realm using the `!createrealm` command.

* * *

**Creating a LOG SuperGroup**
	-For GBan Log

	1. Create a group using the `!creategroup` command.
	2. Add two members or bots, then use `#Tosuper` to convert to a SuperSroup.
	3. Use the `#addlog` command and your ***LOG SuperGroup(s)*** will be set.
	Note: you can set multiple Log SuperGroups

* * *

# Support and development

Check out this [tutorial by Telegram Geeks](http://telegramgeeks.com/2016/01/teleseed-tutorial/) for further assistance with setup and installation.

**Do not contact us** in private for support.
Join our bot development group by sending `/join 1047524697` to [@TeleSeed](https://telegram.me/TeleSeed)

# Special thanks to
[@seyedan25](https://telegram.me/seyedan25)

For managing [@teleseed](https://telegram.me/TeleSeed) on Telegram.

[@Vamptacus](https://telegram.me/Vamptacus)

For graphic designs.

[topkecleon](https://github.com/topkecleon)

[Juan Potato](https://github.com/JuanPotato)

* * *

# Our team!

[Alphonse](https://github.com/hmon) ([Telegram](https://telegram.me/iwals))

[I M /-\ N](https://github.com/imandaneshi) ([Telegram](https://telegram.me/imandaneshi))

[Siyanew](https://github.com/Siyanew) ([Telegram](https://telegram.me/Siyanew))

[Rondoozle](https://github.com/Rondoozle) ([Telegram](https://telegram.me/POTUS))

### Our Telegram channels:

English: [@TeleSeedCH](https://telegram.me/teleseedch)

Persian: [@IranSeed](https://telegram.me/iranseed)
