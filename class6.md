## **Read 06:**

### Colors in CSS :
There are three ways to select a color in CSS: *RGB*, *HSL* and color name. As for the color name, you just have to write the color name to the attribute, there is 147 predefined colors that browsers can recognize. 


The term **RGB** refers to (red,green,blue). You just have to know the mixture of the colors, each color degree is between 0 and 255. There are lots of tools online that you can find to pick the right color, and get the rgb values. RGB color example :
* rgb(142,37,255)
*This will show color near to purple.*


**Hexa codes** are a hexadecimal code consisting of 6 hexadecimal degits. First two are for red, second two are for green and the last two are for blue. Here is an example :
* #F3FF1A
*This will show color near to yellow.*


As for the **HSL**, it stands for (hue, saturation, lightness).  The hue is the color degree, from 0 to 360. The saturation is the degree of grey that's in the color, it is written as a percentage. Lightness is the degree of white or black that's in the color. So if it was 0, then it's all black, and if it was 100%, then it's all white. And it also comes as a percentage. Here is an example :
* hsl(120,100,55)
*This will show color near to light-green*


You can also use the **Alpha** to control the opacity of the color. And it is available for both rgb and hsl. **RGBA** & **HSLA might** not be supported by some old browsers, so you can put another rule before them that is in rgb or in hsl, so the HTML can make a callback when the other color is not recognized.
* rgb(142,37,255)
*This will show color near to purple with high opacity.*
* hsl(120,100,55)
*This will show color near to light-green with low opacity.*


It is important to choose the right colors. When choosing a background, try to make some **contrast** between it's color, and the color of the text. Because text without contrast between the colors is not east to read, and it affects people that have issues with their eyes. But don't make the contrast too high, so the colors be so shiny and annoying to the human eye.



[Home Page](README.md)