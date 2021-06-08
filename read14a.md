# Transforms and Animation
_a general layout used for sizing and positions as well change elements by moveing it or make a difference that may dazzle the user , the transform come with two different sttings each have it's properties but the actual syntax includes a transform property followed by a value given to a scale or rotate or anything you wanted to add to ? and the 2d transform which have x and y axis , 3d transform provided by z axis in addition_


**things (properties) to do to add some move to elements**

-scale .
-rotate .
-translate:pushing and pulling an element .
-skew:to destort elements in the horizontal axis .

element{
transform:skew x(20deg);
}

**skewing element 20 degrees on x axis**
 
 ## combinig elements

 >it is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example .

In css
element{
transform:skew x(20deg) rotate(25deg);
}
_also it is possible to transform shapes as cubes_

## Animations
_more control to elements where transitions takes off and it is a great way of building out visual interactions for users , to make animation use keyframe rule that includes animation name and any breakpoints after that you should put duaration function and delay if needed using animation-time-function()_

>By default, animations run their cycle once from beginning to end and then stop. To have an animation repeat itself numerous times the animation-iteration-count property may be used. Values for the animation-iteration-count property include either an integer or the infinite keyword. Using an integer will repeat the animation as many times as specified, while the infinite keyword will repeat the animation indefinitely in a never ending fashion.

