### ml tags
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


### Additional actions to add to your Shortcut for ml tags
Add the actions below to display the list menu in your Shortcut

```
Text (containing the ml tags youve made)
Set Name : Menu.vcf
Get Variable : Set Name (Use a magic variable to point to set name action above, and then select and change the type to contact)
Choose From List
```

#### After a selection is made
If you are using the listmenu to make menus of options you will likely have to use IF Otherwise actions.

#### Retrieving Values
You can get the variable of the selection, then set the variable as a contact if not already set, then set to NAME to retrieve the Title selected, or COMPANY for the subtitle selected.

get image from site, and edit text below fo rcontext

#### Advanced
You can store additional information in VCARDS in other fields used by the CARDS for example if the menu had colour names in the Name field, you could have RGB/HEX values in other fields that you dont want displayed, but you want to retrieve later.

You can add variables in the text in side the tags, eg to add a count result to a subtitle

More information on menu lists here [here](https://nturpin0.github.io/appsupport/MenuBuilder/about.html) and [here](https://www.reddit.com/r/shortcuts/comments/aibvkg/creating_visually_appealing_menus/)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0825.png)








