![](https://github.com/nturpin0/OutputKit/raw/master/Images/OutputKit%20Logo%20No%20Message.png)
# OutputKit
For making nicer looking Shortcuts


OutputKit is a bit of JSON (a dictionary in the form of text) that contains the markup for [Bootstrap components](https://getbootstrap.com/docs/4.0/components/alerts/)  , you put into a variable at the start of your Shortcut.


## Getting started

### Using the template shortcut
To get started its best to take the [OutputKit Template](https://routinehub.co/shortcut/1220) Shortcut and just start a shortcut from there. It already has all the actions in that you need to use and create something with OutputKit. You can always update the tags, or make a different html template with [https://routinehub.co/shortcut/1221](OutputKit Build).


### Adding OutputKit to your Shortcut
Using the [https://routinehub.co/shortcut/1221](OutputKit Build) Shortcut, you can create your own html template or copy the json text to include at the top of your Shortcut. The json text should be copied into a text box, then Get Dictionary from Input, then a variable name, examples are all in a variable called OutputKit. 
The html template should be copied into a text box and then displayed, there are several ways of doing this, quickview, View Web Page or opening in Safari using a data URI. You will need to insert the output you want to refer to into the heml template, you'll find its often better to split your content into several text boxes to make it easier to edit.


## tags
Once youve have a template Shortcut, or have added the json to your own Shortcut, you can then refer to the different elements with the tags.


#### How to set tags
Tags are put in a Text action along with other output. You can mix in html tags, or even use Markdown, as long as you convert it first. Its often useful to use several text boxes to split things up.

Choose the variable you've assigned the OutputKit dictionary to, and enter a tag.

![](https://github.com/nturpin0/OutputKit/raw/master/Images/OKDIctionary.gif) 


### Adding images and other media
It's often useful to put any base64 encoded images/sounds and other big/reused items in dictionary at the top of your shortcut, and it keeps the text window clear of long strings. So when it comes to adding an image you can just type it's name.
Copy and paste the strings into a Dictionary or the Shortcut [Asset Builder](https://routinehub.co/shortcut/1760) can be used to add Base 64 Encoded items as a text json string, just like OutputKit.

