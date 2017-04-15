# APEX D3 Liquid Gauge

This plugin is a replica of the D3 Liquid Fill Gauge. 

Based on the D3 Javascript Library, this plugin has its own little taste of APEX and can run on a SQL Query. 

It is also sensitive to the click event. 

Clicking on the gauge will cause it to run the query again and update its displayed value. 

You can also take a look at the plugin documentation altogether on my website. 

## Demo
[APEX D3 Liquid Gauge Item Plugin - Click Here](https://apex.oracle.com/pls/apex/f?p=9468:11)

## Installation
Just import the 
```html
item_type_plugin_com_jafr_apexgauge.sql
```
file into your application.

Choose this plugin as your item type and change the settings to get the desired result.

For more documentation visit this link : [APEX D3 Liquid Gauge Item Plugin - Click Here](http://farzadsoltani.com/2017/04/15/gauges-apex-look-gaugaustic/)

## Usage

Type:
```html
Define the type of source used for the value shown on the gauge. 
Options include “From Input” and “From Query”.
```


Percent (Input):
```html
You see this option when you set Type to “From Input”. 
You can enter a number to be shown on the gauge.
```

Percent (SQL Query):
```html
You see this option when you set Type to “From Query”. 
You can enter a SQL query that returns a single value.
```

Height:
```html
Set the height of the gauges. 
The value is based on pixels, therefore an integer will suffice.
```

Theme:
```html
Choose from 3 preset themes. 
Theme 3 is the default theme. 
Setting the colours will override any colours in the themes.
```

Circle Colour:
```html
Set the colour of the circle. 
Using the color picker simplifies the process of choosing a colour.
```

Text Colour:
```html
Set the colour of the text. 
Using the color picker simplifies the process of choosing a colour.
```

Wave Text Colour:
```html
Set the colour of the wave text inside the gauge. 
Using the color picker simplifies the process of choosing a colour.
```

Wave Colour:
```html
Set the colour of the wave. 
Using the color picker simplifies the process of choosing a colour.
```

## Additional Settings

Note that this plugin is a dynamic plugin reacts to the click event. 
To use this functionality all that you need to due is specify a SQL query 
that returns a single value in the List of Values property of the plugin. 
Clicking on the item will fetch new data from the query you define and update the plugin using AJAX.

## Author

[Farzad Soltani - Github](https://github.com/farzadso)

[Farzad Soltani - My Website](http://www.farzadsoltani.com/blog)

[Twitter - @farzadso](https://twitter.com/@farzadso)
