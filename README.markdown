# ExpressionEngine Espresso Sugar

This sugar gives you access to the EE template syntax within Espresso, giving you codesense, itemizers and more. 

## Download and Install

If you're unsure about GitHub, you can download the latest release from:

http://anthonyshort.com.au/projects/details/ee-sugar/

You can also download the latest release by using the download button above, or run this in terminal:

	cd ~/Library/Application\ Support/Espresso/Sugars 
	git clone git://github.com/anthonyshort/expressionengine.sugar.git
	
You can update the sugar at any time, by running this:

	cd ~/Library/Application\ Support/Espresso/Sugars/expressionengine.sugar/
	git pull
	
## Theme

You can get the theme I'm developing, which has ExpressionEngine specific highlighting, from 
	
## Latest Changes

- Finally got context-sensitive code complete. For example, while you are inside the exp:weblog:entries tag and you type '{' you'll be presented with a list of variables that can be used inside that tag. Simple autocomplete is nothing compared to this. It makes it extremely easy to find out what tags can be used in particular contexts.

## Known Bugs

- The syntax is broken if a } is placed inside an attribute value. For example {exp:weblog:entries title="{title}" weblog="blog"} - The syntax will be cut short at the {title} closing bracket.


## To Dos

- Behaviours (Autocomplete after codesense) is a bit dodgy. Make these more usable.
- Snippets
- Text Actions
- File Actions
- Specific Parameter Behaviours **Mostly Done**
- SAEF Forms
- Syntax naming on Conditionals *Mostly done* Need to fix up some syntax errors to make it more consistent
- Comment Preview Tag
- Autocomplete creates html for the comment submission form
- All the formatting dates
- Common Formatting dates in the codesense
- IP to Nation
- Referrer Tag
- RSS Tag
- Search Tag
- Stats Tag
- Trackback Tag
- Contact Form
- Tell a friend
- Photogallery
- Mailing List
- Query Tag
	- SQL sub-syntax mode
- Simple Commerce
- Common Plugins