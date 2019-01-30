# ml tags

## menu lists
These are for creating lists containing pictures which can then be used like a menu to make a selection. It's important that they each tag and content remain on the same line for each entry being made in the list.
(although it will of course wrap on the screen) with no carraige returns between them. All tags must be used, ie even if not using the Subtitle. 



```
(ml)Title(mlsub)Subtitle(mlimage)base64encoded(/ml) 
```

- Title is the Main title of the list item
- Subtitle is the smaller black lettering underneath the Title of the list menu item.
- base64encoded will be a base 64 encoded image as text or a variable cotaining the text



ml
mlsub
mlimage
mlnote
/ml

## mlcolors
mlcolors is a slightly different tags, it contains all the markup and images for a menu with a set of css colors with single names, selecting a color returns the css color name. It doesnt need any closing tag.

## Additional actions to add to your Shortcut for ml tags
Add the actions below to display the list menu in your Shortcut

```
Text 
Set Name : Menu.vcf
Get Variable : Set Name 
Choose From List
```
Text (should contain the ml tags youve made)
With Set Name (Use a magic variable to point to set name action above, and then select and change the type to contact)

### After a selection is made
If you are using the listmenu to make menus of options you will likely have to use IF Otherwise actions.

### Retrieving Values
You can get the variable of the selection, then set the variable as a contact if not already set, then set to NAME to retrieve the Title selected, or COMPANY for the subtitle selected.

get image from site, and edit text below fo rcontext

### Advanced
You can store additional information in VCARDS in other fields used by the CARDS for example if the menu had colour names in the Name field, you could have RGB/HEX values in other fields that you dont want displayed, but you want to retrieve later.

You can add variables in the text in side the tags, eg to add a count result to a subtitle

More information on menu lists here [here](https://nturpin0.github.io/appsupport/MenuBuilder/about.html) and [here](https://www.reddit.com/r/shortcuts/comments/aibvkg/creating_visually_appealing_menus/)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0825.png)








