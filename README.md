# Durham Remark theme

A [remark](https://remarkjs.com/) theme for
[Durham ARC](https://www.dur.ac.uk/arc/).

Also includes a more general theme adding mechanism.

First include the remark JavaScript into your HTML as well as this

```HTML
<script src="https://remarkjs.com/downloads/remark-latest.min.js"></script>
<script src="https://durhamarc-training.github.io/remark_theme/latest.js"></script>
```

Then before you create the remark slideshow, install the theme, and
then create the slides as normal.

```
durham.install();
var slideshow = remark.create({sourceUrl: 'README.md'});
```



## DU corporate colour scheme

### Core colours

- Pantone 255 - DU Purple - rgb(104,36,109)
- Pantone 7548 - DU Yellow - rgb(255,213,58)
- Pantone Pro Blue - DU Cyan - rgb(0,174,239)
- Pantone 187 - DU Red - rgb(190,30,45)
- Pantone 10108 - DU Gold - rgb(175,169,97)

### Secondary colours

- Pantone 5155 - DU Heather - rgb(203,168,177)
- Pantone 615 - DU Stone - rgb(218,205,162)
- Pantone 543 - DU Sky - rgb(165,200,208)
- Pantone 435 - DU Cedar - rgb(182,170,167)
- Pantone 429 - DU Concrete - rgb(179,189,177)

### Type colours

- Pantone 7546 - DU Ink - rgb(0,42,65)
- Pantone Black - DU Black - rgb(51,49,50)
