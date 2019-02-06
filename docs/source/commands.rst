Commands
========

Introduction
------------

Starting and Stopping Your Show
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

To start a Hidden Cam show, type /startshow. End the show with /stopshow.

Commands for All Users
----------------------

+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| ``/cmds``		| * Displays a list of commands in the chat window.											|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| ``/pass``		| * Shows the user whether they have a pass or need to purchase one.									|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| ``/timeleft``		| * Displays the remaining time if a goal timer has been set.										|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| ``/showtime``		| * Displays the time elapsed since the Hidden Cam show started.									|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+

Commands for Broadcasters and Moderators
----------------------------------------

+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /add <user>		| * Manually adds a ticket for the specified user. 											|
|			| * If no user is specified, adds a ticket for the moderator who issued the command. 							|
|			| * Multiple users can be added by listing multiple space-separated usernames, e.g. /add user1 user2.					|
|			| * Note: If the output from /tickets is saved, it can be pasted after the /add command to restore tickets to users who purchased them. |
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /addtime <minutes>	| * Adds time to a running timer. A negative number will subtract time. 								|
|			| * Subtracting more time than remains will stop the timer with 1 minute remaining. 							|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /au <user>		| * Same as /add <user>															|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /check <user>		| * Checks whether or not a viewer has a ticket.											|
|			| * Multiple viewers may be checked at the same time by listing multiple space-separated usernames, e.g. /check user1 user2.		|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctb <text>		| * Sends a one-time, private notice to the broadcaster. 										|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctm <text>		| * Sends a one-time, private notice to all moderators.											|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctn <text>		| * Sends a one-time, public notice to the chat.											|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctsubject <text>	| * Changes the room subject to the text and adds a 'CrazyTicket:' leader and 'Type /cmds' trailer.					|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctt <text>		| * Sends a one-time, private notices to all ticket holders.										|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /del <user>		| * Removes a user's ticket.														|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /du <user>		| * Same as /del <user>															|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /email		| * Tells CrazyTicket to check for an email address in the tip note when a ticket is purchased.						|
|			| * Notifies the viewer, moderators, and broadcaster if the email address is missing.							|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /hilite		| * Toggles highlighted text for ticket holders.											|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /hl			| * Same as /hilite															|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /newshow		| * Restarts ticket sales after a show has been ended.											|
|			| * Does not affect ticket holder lists.												|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /plist		| * Displays a list of paid ticket holders.												|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /plistw		| * Displays a list of paid ticket holders in wide format.										|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /schat		| * ON/OFF toggle to suppress the public chat so it does not pollute the show chat.							|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /showend		| * Suspends ticket sales and clearly indicates to viewers entering the room that although the cam is still hidden, the show is over.	|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /showover		| * ON/OFF toggle to signal the show is nearing its end.										|
|			| * Viewers entering the room will receive a notice that the show is nearing its end and buying a ticket is not recommended.		|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /startshow		| * Starts a Hidden Cam show. Only ticket holders will be able to see the cam feed.							|
|			| * Chat can still be seen by users without tickets. Notices can be sent to the chat to advertise the ticket price to join the show.	|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /starttimer <minutes>	| * Starts a count down goal timer to indicate a timed ticket buying window to viewers.							|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /subject <text>	| * Changes the room subject to the text entered after the command.									|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /stopshow		| * Ends the Hidden Cam show and returns the feed to normal, public operation.								|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /tipsoff		| * ON/OFF toggle to suppress the display of total tips received during the ticket show.						|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+

Commands for Broadcasters Only
------------------------------

+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctprice <number>	| * Changes the price of tickets while CrazyTicket is running.										|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+
| /ctreset		| * Clears all ticket holder lists and prepares CrazyTicket to begin sales for a new show.						|
+-----------------------+---------------------------------------------------------------------------------------------------------------------------------------+

