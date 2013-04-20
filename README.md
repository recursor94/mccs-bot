[[mccs-bot]]

This is the irc bot used by the Marist College Computer Society irc server
(mccs.stu.marist.edu).  The bot has the ability to parse and execute several
unique commands.  Commands are preceeded by a question mark and proceeded by a
space followed by any arguments. Commands can not be nested and are case 
sensitive.

The available commands are described bellow:
=======

?hello        Displays a welcome message addressed to the calling user

?summon [arg] Displays the hyperlink to the first google image result using
              the argument as a search query.

?resummon [arg] Has the same behavior as summon but will return the next
                search result if called again with the same argument.

?ligaf          Displays the hyperlink to one of two possible
                "Like I give a fuck" memes.

?++ [arg] [optional arg]  Adds a plus to the user specified in the first
                argument unless the specified user is the calling user
                in which case that user is penalized by losing a plus.
                If provided with the optional argument, that argument
                is displayed as the reason for having that plus awarded.

?pluses [arg] [optional arg] alias for ?++, but also displays the reasons
                             that were given for awarding that user
                             with pluses.

?plus_leaders   Displays the current leaders with the 10 greatest amount of
                pluses in order of the number of pluses each leader has.