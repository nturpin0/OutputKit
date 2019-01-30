## Component tags
Most web tags need to be closed off ie /jumbotron, /bar, youll often find this is why something doesnt look the way it does, and tags will nest inside each other, if you know a small amount of html it will be helpful.




### Bars
- bar /bar
Bars are simple percentage lines. The first number you put is the text displayed, the second one inside the tags is the number used to work out what is shown.

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0832.jpg)

### Jumbotron
A Jumbotron is a big banner usually used at the top of your page.
- jumbotron    /jumbotron

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0827.png)

### Lists

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0839.jpg)

Groups of list items should be enclosed in a listgroup tag.
- listitem    /listitem
- listgroup   /listgroup


<listgroup>
  <listitem>Apples</listitem>
  <listitem>Pears</listitem>
</listgroup>


### Cards
All elements for a card, header, text etc should be containted within the <card> </card> tags. All cards, no matter which color should be closed with the /card tag.


```
<card>
<cardheader>Card Title</cardheader>

</card>
```

![](https://github.com/nturpin0/OutputKit/raw/master/Images/Cards.jpg)

- card      /card  
- cardbody   /cardbody
- cardtext   /cardtext
- cardheader   /cardheader
- card link?

#### Color Cards
- cardred /card
- cardblue /card
- cardyellow /card
- cardblack /card


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

Example of a button with a badge inside.

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0828.png)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0836%202.jpg)


```
<buttonblue>Unread Mail <badgegray>4</badge></button>
```

### Tables
The table tag will make your table responsive, ie works better on mobile screens of variable sizes. You wont need the normal table html tag, you can use the thead tbody th tr html mark up to make your table, or you can use Markdown to generate your table first. If you're just making a static table you might find [this site](https://www.tablesgenerator.com/html_tables) useful for generating tables. 

- table    /table


### Media
Any media needs to be a base 64 encoded text/variable, Video creates a very large piece of Base64 text and you wont work well with large videos.

- Images imgb64  /imgb64
- Video vidb64  /vidb6
- Audio audb64  /audb64

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0829.png)


### Icons
If using Material Design, or Font Awesome icons, you must remember to make sure you set the includes in the html template using the OutputKit Build.

#### [Material Design](https://material.io/tools/icons/)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0830.png)

#### [Font Awesome](https://fontawesome.com)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0831.png)


### Links
Three tags can be needed for link, you can use html if you prefer.
```
<link>https://www.apple.com<linkname>Apple</link>
```
