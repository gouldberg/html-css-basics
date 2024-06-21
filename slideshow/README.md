# Slideshow

This is totally from GeeksForGeeks.org HTML and CSS tutorials.
<br />

## CSS animation by @keyframes

- To use CSS animation, you must first specify some **@keyframes** for the animation. @keyframes will describe which styles that element will have at specific times.
- Here uses the approach of using **animation keyframes** to scroll through each of the slides by **modifying each of the slide's margin-left properties** during the animation. The animation type can be specified so that the slides can be animated as per the required duration and effect.
- The @keyframes property has **the option to divide the animation time into parts/percentage** and perform an activity that is specified for that part of the whole duration of the animation. the @keyframes property is given to each animation according to the name of that animation. It allows you to run the animation infinitely as well.

### HTML Code

- Use **separate div sections for each slide** to contain the text content. This allows for individual content definitions on each slide.

### CSS Code

- Employ the slide-wrapper class to encapsulate all slides, enabling consistent animation effects and easy application of CSS properties to each slide.-
- Utilize the **overflow property to clip excess content**, ensuring that the content within each slide remains visible, and any overflow is hidden.
- Apply the **float property to align contents to the left**, providing a structured layout for the slide elements.
  Apply the **:nth-child() selector to style elements based on their position in a group of siblings**. This allows for individualized styling, such as background color, based on the order of each slide.
