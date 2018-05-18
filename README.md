# orange-cat
Monstercat Reddit CSS

## Compilation Instructions:

1: visit http://www.cssdrive.com/index.php/main/csscompressor/  
2: Click Advanced Mode  
3: Switch "Replace Multiple Spaces", "remove tabs", and "remove all newlines"  
4: Open Notepad++ and copy advanced output into it  
5: Use Replace tool to replace '{ ' with '{', ' }' with '}', ';}' with '}', ' {' with '{', ', ' with ',', and '; ' with ';'  
6: Check using a testing platform subreddit, verify that extreme compression didn't break anything. 

## Compilation Order:

**hector.css**

**misc.css**

**golden-names.css**

**flairs.css**

**other.css*


## Notes

**hector.css** cannot be replaced with updated versions of the theme for a few reasons:

1: The theme has *very* few users, and has never been updated.  
2: The theme has an incredible amount of bugs that I had to fix  
3: Many of the customization changes to the theme were done via overwriting hector.css, and replacing those changes with the stock theme would break our current one. 

**misc.css** needs to come directly after hector.css. I cannot verify hierarchy issues until I either debug the entire theme or rewrite it. With new.reddit looming on the horizon, neither of those are likely. 

**golden-names.css** has unrecognizable selectors at the beginning. I earlier began, in an effort to save a few hundred characters, to use a different selector to get the artist names. It was too tedious to do for the sake of ~50 characters. Do not remove these. 

**flairs.css** is not my responsibility. Discuss this with /u/dyl__ on reddit. 

**other.css** contains the code I don't see a need for referencing in the future. Additionally, it contains code that changes on a daily basis. This might possibly be sorted in the future, but doing so would be completely unnecesary 
