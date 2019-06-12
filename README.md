![alt text](colores-logo.png "Color.es by MisterZik")
## Color.es
---
#### Gorgeous Color Palettes for Web Enthusiast :bowtie:
##### Colores also known as Color.es

Color.es is a tiny bit CSS library fueled with the most exciting colors. No, We do not get to pick them, or randomly say, hey! let's release this color wave. We are Front-end developer with 10+ years, We based our Open-Source libraries out of studies and research made by our team here at www.vimedev.com

![alt text](Showcase-legacy.png "Background colors & Font Colors based on Popular Palettes for 2017. (CSS Only)")

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
<link rel="stylesheet" href="themes/cls-artsy.min.css">
```
3. Use the Class name `colores` to get the classes style properly place on your DOM, follow up with the color from the default palette.

Example )
For this example, I am going to use the color yellow in default/primary color.

 `colores yellow` - This will change the color of the container or background.


 How About RED?
 
 Pretty Simple, same idea behind, start by specifying the class name `colores` follow by the color `red`
 
 ``` 
 <div class="colores red"> IS MY BG RED? </div>
```


#### W00t! w00t!, Sweet, but how about if i want to change the text color,
It's okay, we got ya all cover, now since we only want the text color to change instead of the background color
we are going to replace the class name `colores` for `txt-cls` follow by the color

 ```
 txt-cls yellow
 ``` 
 
#### HTML:
```
<div class="colores yellow">
  This is a Yellow Box
</div>
```

```
<span class="txt-cls yellow">
  This is a Yellow Text
</span>
```

###### Put it together:
```
<div class="colores yellow">
  This is a Yellow Box
  This is a <span class="txt-cls yellow-dark">Dark Yellow</span> Text
</div>
```
###### Colores Variations:
Use the proper class to change the style desired `txt-cls` or
`colores yellow`

Asides from that we have also included three tones asides from library primary tone in order to use it
you just have to specify the tone, if left blank the tone will go instantly to primary, you have three options light, dark, and darker
depending on the option you will get the right property, per example.

 ```
 colores yellow = Default Tone
 colores yellow-light = Lighter tone from Default 
 colores yellow-dark = Dark tone from Default
 colores yellow-darker =  Darker tone from Dark Tone
 ```


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
