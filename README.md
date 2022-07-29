# CSS-Shorthands
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
}
html{
    height: 100%;
    font-size: 16px;
}
body{
    min-height: 100vh;
}
------------------------------------------------------------------------------------------
box shadow shorthand -> none|h-offset v-offset blur spread color |inset|initial|inherit;
------------------------------------------------------------------------------------------
h-offset	Required. The horizontal offset of the shadow. A positive value puts the shadow on the right side of the box, a negative value puts the shadow on the left side of the box	
v-offset	Required. The vertical offset of the shadow. A positive value puts the shadow below the box, a negative value puts the shadow above the box	
blur	Optional. The blur radius. The higher the number, the more blurred the shadow will be	
spread	Optional. The spread radius. A positive value increases the size of the shadow, a negative value decreases the size of the shadow
color	Optional. The color of the shadow. The default value is the text color. Look at CSS Color Values for a complete list of possible color values.

Note: In Safari (on PC) the color parameter is required. If you do not specify the color, the shadow is not displayed at all.	
inset	Optional. Changes the shadow from an outer shadow (outset) to an inner shadow
------------------------------------------------------------------------------------------
#reusable wrapper container
.container{
    width: 100%;
    max-width: 960px;
    margin: 0 auto;
}
--------------------------------------------------------------------------------------------
#forms
<div class="inputSection"><input type="text" placeholder="Enter new todo"></div>
input[type='text'],input[type='button']{
    border: 1px solid lightgray;
    outline: none;
    font-size: inherit;
    padding: .3em .5em;
    border-radius: 10px;
}
ul li a{
    display: block;
    padding: 1rem .3rem;
    text-decoration: none;
    color: inherit;
}
