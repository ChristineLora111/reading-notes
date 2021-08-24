## Read: 14a - CSS Transforms, Transitions, and Animations:
[Go back to Reading Notes home](README.md)

<b><h3>CSS Transforms:</h3></b>
- The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

- Browser support for the transform property isn’t great, but it is getting better every day. For the best support vendor prefixes are encouraged, however you may need to download the nightly version of Chrome to see all of these transforms in action.

Transform Syntax#transform-syntax:
- The value specifies the transform type followed by a specific amount inside parentheses.

2D Transforms: 
- Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. 

2D Rotate:
- The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.

2D Translate:
- The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

2D Skew:
- Used to distort elements on the horizontal axis, vertical axis, or both. The syntax is similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.


<b><h3>Transitions & Animations</h3></b>
For a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

Transitional Property:
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

Other properties:
- Transitional Properties:
It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another.

- Transition Duration
The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms)

- Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

- Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. 

Animations:
- Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. 

Animations Keyframes:
- To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

Animation Duration, Timing Function, & Delay
- Once you have declared the animation-name property on an element, animations behave similarly to transitions. They include a duration, timing function, and delay if desired. To start, animations need a duration declared using the animation-duration property. As with transitions, the duration may be set in seconds or milliseconds.

Animation Iteration
- By default, animations run their cycle once from beginning to end and then stop. To have an animation repeat itself numerous times the animation-iteration-count property may be used. Values for the animation-iteration-count property include either an integer or the infinite keyword. Using an integer will repeat the animation as many times as specified, while the infinite keyword will repeat the animation indefinitely in a never ending fashion.

Animation Direction
- On top of being able to set the number of times an animation repeats, you may also declare the direction an animation completes using the animation-direction property. Values for the animation-direction property include normal, reverse, alternate, and alternate-reverse.

Animation Play State
- The animation-play-state property allows an animation to be played or paused using the running and paused keyword values respectively. When you play a paused animation, it will resume running from its current state rather than starting from the very beginning again.

Animation Fill Mode
The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run. The animation-fill-mode property accepts four keyword values, including none, forwards, backwards, and both.

Shorthand Animations
- Fortunately animations, just like transitions, can be written out in a shorthand format. This is accomplished with one animation property, rather than multiple declarations. The order of values within the animation property should be animation-name, animation-duration, animation-timing-function, animation-delay, animation-iteration-count, animation-direction, animation-fill-mode, and lastly animation-play-state.


<b><h3>8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS</h3></b>
1) Fade In:
- Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.
2) Change the Color:
- Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them
3) Grow & Shrink:
- To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.
4) Rotate Elements:
- CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.
5) Square to Circle:
- Transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.
6) 3D Shadow:
- This effect is achieved by adding a box shadow, and then moving the element on the x axis using the transform and translate properties so that it appears to grow out of the screen.
7) Swing:
8) Inset Border:
- One of the hottest button styles right now is the ghost button; a button with no background and a heavy border. We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.

For the code examples, visit: https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users

<b><h3>6 Buttons animated</h3></b>
https://codepen.io/retyui/pen/ByoaXV

<b><h3>CSS3 Animations: Keyframes</h3></b>
https://codepen.io/akshaychauhan/pen/oAfae

<b><h3>404:</h3></b>
https://codepen.io/kieranfivestars/pen/MYdQxX

<b><h3>Pure CSS Bounce Animation:</h3></b>
https://codepen.io/dp_lewis/pen/gCfBv
