![alt text](logo.png "Color.es")
## Color.es
---
#### Gorgeous Color Palettes :bowtie:
##### Colores
Color.es is a small css library packed with the most used colors used this season. The idea behind this is to explore new palettes, while keeping track of what was once claimed and admire by many!

We will start with material design palette references, and move forward as the research moves along, asides from that we will implement custom libraries that reference famous painters, singers, and even world events.

![alt text](Showcase.png "Background colors & Font Colors based on Popular Palettes for 2017. (CSS Only)")

### Installation
* Download [ZIP](https://github.com/misterzik/Colores/archive/master.zip) or Clone Project
* Bower
`bower install colores`


### Usage
Color.es comes with a built-in demo, Please refer to folder `/public`. If you would like to skip the demo, all you have to do is:

1. Include the `css` files located in the `dist` folder on your root folder.
2. Include this new files on your `index.html`.
```
<link rel="stylesheet" href="color.es.min.css">
<link rel="stylesheet" href="color.es-artsy.min.css">
```
3. Use the Class name `colores` to get the ball rolling, follow up with the color from the default palette.

Example )
For this example, I am going to use the color yellow in default/primary color.

 `colores yellow` - This will change the color of the container or background.

 `cls-text yellow` - This will change the color of the text font.

#### HTML:
1. ```
<div class="colores yellow">
  This is a Yellow Box
</div>
```
2. ```
<span class="cls-text yellow">
  This is a Yellow Text
</span>
```

###### Put it together:
```
<div class="colores yellow">
  This is a Yellow Box
  This is a <span class="cls-text yellow-dark">Dark Yellow</span> Text
</div>
```
###### Colores Variations:
`cls-text` or `colores yellow` `yellow-dark` - This will change the base color to a different tone. [light, dark, darker]



### Default Color Palette

| Class Name  |  Color Name   | Extra Option      |
| ------------|:-------------:| -----------------:|
| colores     | yellow        | light,dark,darker |
| colores     | blue        | light,dark,darker |
| colores     | red       | light,dark,darker |
| colores     | pink       | light,dark,darker |
| colores     | orange        | light,dark,darker |
| colores     | mz-orange        | light,dark,darker |
| colores     | purple        | light,dark,darker |
| colores     | cyan        | light,dark,darker |
| colores     | grey        | light,dark,darker |
| colores     | brown       | light,dark,darker |
| colores     | green       | light,dark,darker |


### Artsy Legends - Color Palette

| Class Name  |  Color Name   | Extra Option      |
| ------------|:-------------:| -----------------:|
| colores     | night        | light,dark,darker |
| colores     | mona        | light,dark,darker |
| colores     | scream       | light,dark,darker |
| colores     | heaven       | light,dark,darker |
| colores     | grande        | light,dark,darker |
| colores     | metrist        | light,dark,darker |
| colores     | wave        | light,dark,darker |
