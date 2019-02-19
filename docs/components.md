## Component tags
Most web tags need to be closed off ie /jumbotron, /bar, youll often find this is why something doesnt look the way it does, and tags will nest inside each other, if you know a small amount of html it will be helpful. When you nest things, you can do things like put sounds inside a card.



### Bars
Bars are simple percentage lines. The first number you put is the text displayed, the second one inside the tags is the number used to work out what is shown.

- bar /bar


![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0832.jpg)


### Badges
![](https://github.com/nturpin0/OutputKit/raw/master/Images/Badges.jpg)

- badgeblue    /badge
- badgegray     /badge
- badgegreen   /badge
- badgered      /badge
- badgeyellow    /badge
- badgelight     /badge
- badgeblack    /badge


### Buttons
![](https://github.com/nturpin0/OutputKit/raw/master/Images/Buttons.jpg)

- button /button
- buttonblue  /button
- buttondark     /button
- buttongreen  /button
- buttonyellow    /button
- buttonred    /button 
- buttonblack  /button

#### Example of a button with a badge inside.
Buttons are usually used to activate an action or a link, but they can also be used to display information.
```
<buttonblue>Unread Mail <badgegray>4</badge></button>
```

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0828.png)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0836%202.jpg)


### Cards
You can put icons in the title, or use html tags like ```<h1>``` to set the size.
![](https://github.com/nturpin0/OutputKit/raw/master/Images/Cards.jpg)

- card      /card  
- cardbody   /cardbody
- cardtext   /cardtext
- cardheader   /cardheader
- card link?

All elements for a card, header, text etc should be containted within the card tags. 
```
<card>
<cardheader>Card Title</cardheader>

</card>
```



#### Color Cards
All cards, no matter which color should be closed with the /card tag.

- cardred /card
- cardblue /card
- cardyellow /card
- cardblack /card

### Icons
If using [Material Design](https://material.io/tools/icons/), or [Font Awesome](https://fontawesome.com) icons, you must remember to make sure you set the includes in the html template using the OutputKit Build Shortcut.

- Material Design
![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0830.png)

- Font Awesome
![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0831.png)

### Lists
![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0839.jpg)
Groups of list items should be enclosed in a listgroup tag.

- listitem    /listitem
- listgroup   /listgroup

use li if your comfortable with the html or use some markdown (if you convert it) 

'''
<listgroup>
  <listitem>Apples</listitem>
  <listitem>Pears</listitem>
</listgroup>
'''





### Links
Three tags can be needed for link, you can use html if you prefer.
```
<link>https://www.apple.com<linkname>Apple</link>
```

### Media
Any media needs to be a base 64 encoded text/variable, Video creates a very large piece of Base64 text and you wont work well with large videos.

- Images imgb64  /imgb64
- Video vidb64  /vidb6
- Audio audb64  /audb64

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0829.png)


### Tables
The table tag will make your table responsive, ie works better on mobile screens of variable sizes. You wont need the normal table html tag, you can use the thead tbody th tr html mark up to make your table, or you can use Markdown to generate your table first. If you're just making a static table you might find [this site](https://www.tablesgenerator.com/html_tables) useful for generating tables. 

- table    /table




### Depreciated Tags
Jumbotron - card can be used, and is more flexible.
