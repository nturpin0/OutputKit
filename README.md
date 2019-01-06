# OutputKit
For making nicer looking Shortcuts

## OutputKit Showcase
Shortcuts that use OutputKit
- [PowR](https://routinehub.co/shortcut/1430) - A shortcut to add text, audio, image, video and more content to your reminders!
- [EXIF Details](https://routinehub.co/shortcut/913) - Displays EXIF data for a photo sent from a share sheet, or if no photo is sent will use the photo selected.
- [Short Weather](https://www.reddit.com/r/shortcuts/comments/abn8mp/i_wanted_to_play_around_with_outputkit_so_i_made/) - Weather Shortcut
- [Tatort](https://www.reddit.com/r/shortcuts/comments/9ze26m/tatort_viewer/) - for Tatort fans, a traditional german crime tv show from public television
- [Trello Status](https://routinehub.co/shortcut/1243) - For visualising the status of all your Trello boards
- [News Search](https://routinehub.co/shortcut/836) - Will search several news sources for any articles matching the keyword.
- [Rain](https://routinehub.co/shortcut/1222) - Check the probability of rain for the day

## OutputKit Getting Started
OutputKit is a bit of JSON (a dictionary in the form of text) that contains the markup for Bootstrap componnents, you put into a variable at the start of your Shortcut. You can then refer to the different elements with the tags listed below. It's best to look at the [OutputKit Examples](https://routinehub.co/shortcut/1219) Shortcut to get an idea of how it works, then to start with the [OutputKit Template](https://routinehub.co/shortcut/1220) to start making your own. Once you have a better idea, you can create you're own html templates, or update to the latest set of tags using the [OutputKit Build](https://routinehub.co/shortcut/1221) Shortcut.

## How to set tags
Shown here is choosing the variable you've assigned the OutputKit json to, and entering the corresponding key/OutputKit tag.

![Video](https://github.com/nturpin0/OutputKit/raw/master/Images/OKDIctionary.gif) 

## Menu Lists
These are for creating lists containing pictures which can then be used like a menu to make a selection. It's important that they all remain on the same line (although it will of course wrap on the screen) with no carraige returns between them. All tags must be used, ie even if not using the Subtitle.
You might notice that another dictionary item is used Media. It's sometimes a good idea to have a dictionary at the beginning of your Shortcut contatining a dictionary with any media items like an image, or sounds at the beginning of your Shortcut.

- ml.   mlsub (required even if not using.  /ml. no images currently (exp)

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0825.png)

## Bars
- bar /bar
Bars are simple percentage lines. The first number you put is the text displayed, the second one inside the tags is the number used to work out what is shown.
![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0832.png)

## CSS/html
### Tags
A Jumbotron is a big banner usually used at the top of your page.
- jumbotron    /jumbotron

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0827.png)

### Lists
Groups of list items should be enclosed in a listgroup tag.
- listitem    /listitem
- listgroup   /listgroup

### Cards
- card      /card  
- cardbody   /cardbody
- cardtext   /cardtext
- cardheader   /cardheader
- card link?

Different color cards are all closed by 
- cardred /card
- cardblue /card
- cardyellow /card
- cardblack /card

### Links
- link    linkname   /link 

### Badges
- badgeblue    /badge
- badgegray     /badge
- badgegreen   /badge
- badgered      /badge
- badgeyellow    /badge
- badgelight     /badge
- badgeblack    /badge
- topbar   /topbar

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0826.png)

### Buttons
- button /button
- buttonblue  /button
- buttondark     /button
- buttongreen  /button
- buttonyellow    /button
- buttonred    /button 
- buttonblack  /button

Example of a button with a badge inside.

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0828.png)

### Tables
The table tag will make your table responsive, ie works better on mobile screens of variable sizes. You wont need the normal table html tag, you can use the thead tbody th tr html mark up to make your table, or you can use Markdown to generate your table first. If you're just making a static table you might find this site useful. https://www.tablesgenerator.com/html_tables

- table    /table


### Media
- Images imgb64  /imgb64
- Video vidb64  /vidb6
- Audio audb64  /audb64

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0829.png)


### Icons
MD & FA ?
Example of how to show an icon using Material Design

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0830.png)

Example of how to show an icon using Font Awesome

![Picture](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0831.png)

### inc:
These are used mostly by the template builder, and you dont need to know them, unless you've rolled your sleeves up to get a look under the hood.
- viewport - sets up the page
- bootstrapminimal - for including the bootstrap files
- webapp - for when creating a page with no address bar, eg like a home screen launcher
- topbarspace - adds space needed for a navbar
- fa:icon - The includes for Font Awesome icons
- md:icon - The includes for Material Design
- disableselection - Disables selection of text in the web page
- disablezoom - Disables zooming of web page


![Made with OutputKit](https://raw.githubusercontent.com/nturpin0/OutputKit/master/Made%20with%20OutputKit%20Logo.png)
