## Text Reflection

This is totally from GeeksForGeeks.org HTML and CSS tutorials.
<br />

The approach is to create a **rotated string** at the bottom of the original string and then **changing its opacity and background** to make it look like the reflection of the original string.
<br />

### HTML Code

- "h2" tag is created with the text wrapped in it.

### CSS Code

- Step 1: Apply a **radial background** which is lighter at the center and darker at the corners.
- Step 2: Apply some basic styling like size, color, etc to the heading.
- Step 3: Now use the **after selector** and **rotate** the original text on X-axis keeping the origin as bottom.
- Step 4: Apply **"webkit" property** to **cut** the rotated text into cuts. It will make the upper portion of the text visible, as shown in the output image.
- Step 5: Now apply the **transparent color and decrease the opacity** of the rotated text.
- Note: Make sure to decrease the opacity according to your background. If you are using a darker background, decrease the opacity by 0.1-0.2 and if you are using a lighter background then decrease it by 0.6-0.8.
