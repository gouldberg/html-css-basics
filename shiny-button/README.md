# Shiny Button

This is totally from GeeksForGeeks.org HTML and CSS tutorials.
<br />

A button should be designed in such a way that it stands out of the other component so that it is becoming clear to the user where to click and what is the button used for.
<br />

The approach is to use **pseudo selectors before and after selectors.** Using before we will be making strip kind of effect and using after we will make sure it move back and forth give it a reflection kind of look which makes our button look shinny.
<br />

### HTML Code

- Create a button.

### CSS Code

- Step 1: First do some basic styling of button like a background some and border-radius.
- Step 2: Now use **inset shadow property** to give a shadow to the inside of the border of button.
- Step 3: Now use before selector to create a **strip**. The trick is to use width less than the actual width of the button and height equal to the actual height of the button. The use of **skew** function is completely optional, you can skip if you want to. We have used it to have a slightly skewed strip.
- Step 4: Now use **hover** to move the strip to the left.
- Step 5: Repeat step 3 and 4 with after selector just change the width to negative value to move the strip back to it’s original position.
- Tip: You can use some line and length spacing to make some room around the text of the button to give it a more clear look.
