## Welcome To HDE ( Html Discord Embeds )



### Instalation 


```
<link rel="stylesheet" href="https://small-hayoola.github.io/hde/main.css">
```
### Examples

# simple embed

wrap all your data in a `discord-embed` div .
image width is customizable . change it by changing your img width tag

```html
<div class="discord-embed">
        
        <p class="author">YouTube</p>
     
        <p href="#" class="embed-title">apple<p>
        <p class="embed-link">iPhone 12 showcase</p>
        <img src="https://i2.wp.com/arenait.ro/files/2020/06/iphone-12-pro-concept.jpg?fit=1200%2C675&quality=100&strip=all&ssl=1" class="embed-image" width="510px">
        
    </div>
```

![Image](https://small-hayoola.github.io/hde/simpleEmbed.png)

# author with image

to use it instead of `author` class use `embed-author`. you'll need an image and a p tag . ( img tag for author image and p tag for author content )

```html
<div class="discord-embed">
        <div class="embed-author">
            <img src="https://media-exp1.licdn.com/dms/image/C560BAQHdAaarsO-eyA/company-logo_200_200/0/1595530301220?e=2159024400&v=beta&t=IJmg_K1W7KCh6082rXN9V7gzlrD9GMwYqk_EjCrDxGw">
            <p>apple</p>
        </div>
        <p class="embed-title">YouTube<p></p>
     
        
        <p class="embed-link">iPhone 12 showcase</p>
        <img src="https://i2.wp.com/arenait.ro/files/2020/06/iphone-12-pro-concept.jpg?fit=1200%2C675&quality=100&strip=all&ssl=1" class="embed-image" width="510px">
        
    </div>
```
 ![Image](https://small-hayoola.github.io/hde/authorWimg.png)


# an embed with fields

to use fields in your embed you'll need a `fields` div
then you can put your fields in it by putting `field` divs
each field div should contain a `h4` and a `p` tag in it ( h4 is the feild title and p is the feild description )

```html
<div class="discord-embed">
        <div class="embed-author">
            <img src="https://media-exp1.licdn.com/dms/image/C560BAQHdAaarsO-eyA/company-logo_200_200/0/1595530301220?e=2159024400&v=beta&t=IJmg_K1W7KCh6082rXN9V7gzlrD9GMwYqk_EjCrDxGw">
            <p>apple</p>
        </div>
        <p class="embed-title">Apple Products<p>
        <div class="fields">
            <div class="field">
                <h4>iPhones</h4>
                <p>iPhone 12 , Our New iPhone</p>
            </div>
            <div class="field">
                <h4>iPhones</h4>
                <p>iPhone 12 , Our New iPhone</p>
            </div>
            <div class="field">
                <h4>iPhones</h4>
                <p>iPhone 12 , Our New iPhone</p>
            </div>
            <div class="field">
                <h4>iPhones</h4>
                <p>iPhone 12 , Our New iPhone</p>
            </div>
        </div>     
    </div>
```

![Image](https://raw.githubusercontent.com/small-Hayoola/hde/main/embedWfeild.png)


# Embed Color

to change your embed color put `color-<colorName>` after your `discord-embed` class
### all colors 
`color-blue` , `color-w` , `color-green` , `color-pink` , `color-yellow`
default color is red
