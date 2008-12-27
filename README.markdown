# ExpressionEngine Espresso Sugar

This sugar gives you access to the EE template syntax within Espresso, giving you codesense, itemizers and more. 

## Known Bugs

- The syntax is broken if a } is placed inside an attribute value. For example {exp:weblog:entries title="{title}" weblog="blog"} - The syntax will be cut short at the {title} closing bracket.


## To Dos

- Behaviours (Autocomplete after codesense) is a bit dodgy. Make these more usable.
- Snippets
- Text Actions
- File Actions
- Specific Parameter Behaviours **Mostly Done**
- Context-sensitive single variables
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