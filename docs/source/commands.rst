Commands
========

Introduction
------------

Starting and Stopping Your Show
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To start a Hidden Cam show, type /startshow. End the show with /stopshow.

Commands for All Users
----------------------

/cmds
	* Displays a list of commands in the chat window.
/pass
	* Shows the user whether they have a pass or need to purchase one.
/timeleft
	* Displays the remaining time if a goal timer has been set.
/showtime
	* Displays the time elapsed since the Hidden Cam show started.

Commands for Broadcasters and Moderators
----------------------------------------

/add <user>
	* Manually adds a ticket for the specified user.
	* If no user is specified, adds a ticket for the moderator who issued the command.
	* Multiple users can be added by listing multiple space-separated usernames, e.g. /add user1 user2.
	* Note: If the output from /tickets is saved, it can be pasted after the /add command to restore tickets to users who purchased them.

/au <user>
	* Same as /add <user>

/check <user>
        * Checks whether or not a viewer has a ticket.
        * Multiple viewers may be checked at the same time by listing multiple space-separated usernames, e.g. /check user1 user2.

/ctn <text>
	* Sends a one-time, public notice to the chat.

/ctb <text>
	* Sends a one-time, private notice to the broadcaster.

/del <user>
	* Removes a user's ticket.

/du <user>
	* Same as /del <user>

/email
	* Tells CrazyTicket to check for an email address in the tip note when a ticket is purchased and notifies the viewer, moderators, and broadcaster if the email address is missing.

/hilite
	* Toggles highlighted text for ticket holders.

/hl
	* Same as /hilite

/plist
	* Displays a list of paid ticket holders.

/plistw
	* Displays a list of paid ticket holders in wide format.

Commands for Broadcasters Only
------------------------------
