## components
Most web tags need to be closed off ie /jumbotron, /bar, youll often find this is why something doesnt look the way it does, and tags will nest inside each other, if you know a small amount of html it will be helpful.




### bars
- bar /bar
Bars are simple percentage lines. The first number you put is the text displayed, the second one inside the tags is the number used to work out what is shown.

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0832.jpg)

### jumbotron
A Jumbotron is a big banner usually used at the top of your page.
- jumbotron    /jumbotron

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0827.png)

### lists

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0839.jpg)

Groups of list items should be enclosed in a listgroup tag.
- listitem    /listitem
- listgroup   /listgroup


<listgroup>
  <listitem>Apples</listitem>
  <listitem>Pears</listitem>
</listgroup>


### cards
![](https://github.com/nturpin0/OutputKit/raw/master/Images/Cards.jpg)

- card      /card  
- cardbody   /cardbody
- cardtext   /cardtext
- cardheader   /cardheader
- card link?

Different color cards are all closed by /card
- cardred /card
- cardblue /card
- cardyellow /card
- cardblack /card

```
<card>
<cardheader>Card Title</cardheader>

</card>
```

### badges
![](https://github.com/nturpin0/OutputKit/raw/master/Images/Badges.jpg)

- badgeblue    /badge
- badgegray     /badge
- badgegreen   /badge
- badgered      /badge
- badgeyellow    /badge
- badgelight     /badge
- badgeblack    /badge


### buttons
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

### tables
The table tag will make your table responsive, ie works better on mobile screens of variable sizes. You wont need the normal table html tag, you can use the thead tbody th tr html mark up to make your table, or you can use Markdown to generate your table first. If you're just making a static table you might find [this site](https://www.tablesgenerator.com/html_tables) useful. 

- table    /table


### media
- Images imgb64  /imgb64
- Video vidb64  /vidb6
- Audio audb64  /audb64

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0829.png)


### icons
Example of how to show an icon using [Material Design](https://material.io/tools/icons/)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0830.png)

Example of how to show an icon using [Font Awesome](https://fontawesome.com)

![](https://github.com/nturpin0/OutputKit/raw/master/Images/IMG_0831.png)


### links
Three tags can be needed for link, you can use html if you prefer.
```
<link>https://www.apple.com<linkname>Apple</link>
```
