This File gives you an overview on how to translate (or improve) the German Translation.

To start, there is always an id. The id looks like this usually "lepsius_something:".
Don't change anything about the id. It is necessary for Vicky 3 to find
the right localizations.

The id is followed by a string. The String usually looks like this "Something something somethin".
As you might have noted, everything in the " belongs to the string.
The Strings are your workspace.

There are some special things in those Strings that might confuse you.
[ ] mark parts that get replaced with something else by the game, e.g. a character.
You usually don't have to care about them. One exception:
Concepts can be renamed by you by creating a new string with an id. E.g. like this:
akademischen_mission: "Akademischen Mission"
[Concept('concept_academics_academic_mission','$akademischen_mission$')]
Now the game will display "Akademischen Mission" instead of "Akademische Mission".
Note that the everything in [] is case sensitive. So Concept has to be written exactly that case, otherwise
our example will show an error.

