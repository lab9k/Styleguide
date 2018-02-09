# Styleguide

## Colors

|**Primary color**|**Sub color**|**Light**|**Darkgray**<br>(for texts, don't use black! :o)|
|---	|---	|---	|---	|
|```#026495```|```#4a92b8```|```#dae5ea```|```#252525```|
|![alt text](https://raw.githubusercontent.com/lab9k/Styleguide/master/colors/primary.png "Primary color")|![alt text](https://raw.githubusercontent.com/lab9k/Styleguide/master/colors/sub.png "Sub color")|![alt text](https://raw.githubusercontent.com/lab9k/Styleguide/master/colors/light.png "Light")|![alt text](https://raw.githubusercontent.com/lab9k/Styleguide/master/colors/darkgray.png "Darkgray")

## Logo

|**Default logo**|**Default white logo**|
|---	|---  |
|||
|![Default logo](https://raw.githubusercontent.com/lab9k/Styleguide/master/assets/logo-lab9k.svg?sanitize=true)|![Default white logo](https://raw.githubusercontent.com/lab9k/Styleguide/master/assets/logo-white-lab9k.svg?sanitize=true)|

```html
  <img src="path/to/logo-lab9k.svg" alt="Lab9K white" height="50">
```
*OR*
```html
<div id="logo"></div>
```

```css
#logo {
  height: 50px;
  width: auto;
  background-image: url('path/to/logo-lab9k.svg');
  background-repeat: no-repeat;
}
```


## Partners
**Partner - Digipolis**<br>
![Default white logo](https://raw.githubusercontent.com/lab9k/Styleguide/master/assets/digipolis.png)

**Partner - stad.gent**<br>
![Default white logo](https://raw.githubusercontent.com/lab9k/Styleguide/master/assets/stadgent.png)

## Typography
[Google Fonts](https://fonts.google.com) is your best friend!<br>
### Usage
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Title</title>
    <link href="https://fonts.googleapis.com/css?family=Ubuntu" rel="stylesheet">
</head>
<body>
    
</body>
</html>
```
```css
body {
  font-family: 'Ubuntu', sans-serif;
}
```
OR
```css
@import url('https://fonts.googleapis.com/css?family=Ubuntu');

body {
  font-family: 'Ubuntu', sans-serif;
}
```

## Basic grid system with responsive container
See the code in [codepen.io](https://codepen.io/ismakutl/pen/EQZqRo)<br>
Example video: https://i.gyazo.com/ab28831709d3dc71b431b2700136f791.mp4


> [Lab9K](https://lab9k.github.io/).
