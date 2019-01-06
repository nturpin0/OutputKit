# OutputKit
For making nicer looking Shortcuts

OutputKit is a json file that makes marking up difficult things a bit easier. In order to use it you need to refer to the variable that you put the json into eg OutputKit, change the variable into a dictionary, then enter one of the tags as the key.

## OutputKit Shortcuts
[OutputKit Build](https://routinehub.co/shortcut/1221) - For getting the latest tags, copying them and html templates to your project

[OutputKit Template](https://routinehub.co/shortcut/1220) - A template of actions you can use as a starting point to build your Shortcuts with 

[OutputKit Examples](https://routinehub.co/shortcut/1219) - Commented examples of how to use different OutputKit components

## OutputKit Showcase
Shortcuts that use OutputKit
- [PowR](https://routinehub.co/shortcut/1430) - A shortcut to add text, audio, image, video and more content to your reminders!
- [EXIF Details](https://routinehub.co/shortcut/913) - Displays EXIF data for a photo sent from a share sheet, or if no photo is sent will use the photo selected.
- [Short Weather](https://www.reddit.com/r/shortcuts/comments/abn8mp/i_wanted_to_play_around_with_outputkit_so_i_made/) - Weather Shortcut
- [Tatort](https://www.reddit.com/r/shortcuts/comments/9ze26m/tatort_viewer/) - for Tatort fans, a traditional german crime tv show from public television
- [Trello Status](https://routinehub.co/shortcut/1243) - For visualising the status of all your Trello boards
- [News Search](https://routinehub.co/shortcut/836) - Will search several news sources for any articles matching the keyword.
- [Rain](https://routinehub.co/shortcut/1222) - Check the probability of rain for the day

## How to set tags
![Video](https://imgur.com/a/vwme7Ov)

## List Menus

- mlcolors for putting in a list and sending to a choose from list
- ml.   mlsub (required even if not using.  /ml. no images currently (exp)

## Bars


## CSS/html
### Tags
- jumbotron    /jumbotron

### Lists
- listitem    /listitem
- listgroup   /listgroup

### Cards
- card      /card
- cardbody   /cardbody
- cardtext   /cardtext
- cardheader   /cardheader
- card link?

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

### Buttons
- button /button
- buttonblue  /button
- buttondark     /button
- buttongreen  /button
- buttonyellow    /button
- buttonred    /button 
- buttonblack  /button

### Unsupported currently
- responsivetable    /responsivetable
- badgewarning    /badgewarning

### Media
- imgb64  /imgb64
- vidb64  /vidb6
- audb64  /audb64

### Icons
MD & FA ?

### inc:
These are used mostly by the template builder, and you dont need to know them, unless you've rolled your sleeves up to get a look under the hood.
- viewport - sets up the page
- bootstrapminimal - for including the bootstrap files
- webapp - for when creating a page with no address bar, eg like a home screen launcher
- topbarspace
- fa:icon
- md:icon
- disableselection
- disablezoom
