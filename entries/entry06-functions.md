## Functions

I began looking at examples/practicing functions because I have learned about for loops before. Additionally, I wanted 
to see how loops work in sass. The reason why I ultimately chose to go over functions though, is because I have already learned about lists and maps, which turns
out to be a big part of functions in sass. 

Even though my priority was loops, there was a couple of things I needed to know before I dove into functions. One topic I learned was arithmetics when dealing with colors. This 
involved working with rgb hex codes in order to add different functions to control objects. Some examples are fades, adjusting tints for a specific color etc.

#### Arithmetic

Sass arithmetic operations are exactly the same as operations in real life math. There are the regular operations: ```+```,```-```,```*```,```/```. Additionally, the user 
can use modulo(```%```) to find the remainder after dividing chosen numbers. The user can multiply as previously mentioned but, make sure to keep both numbers the same unit.
On codeacademy, they have multiple examples of operations just like this one:
``` SASS
height: $width/6;
line-height: $width/6;
``` 

The above example represents the height and line-height of a box. ```$width/6``` shows that the box is now set to have a height that is 1/6 the width and 
a line-height with the same properties. 

#### Color Functions

Just like normal operations, sass computes colors by using the standard red, green and blue codes. For example, the user can use this:
``` SASS
$color: #010203 + #040506;
```
in order to have a specific color that they want. This is mostly for website creation though, since there are many other ways to do things simliar to this.

#### For Loops

For loops are very interesting because they require a setup before variables can be added to them. Here is codeacademy's example of a for loop:

``` SASS
@for $i from $begin through $end {
   //some rules and or conditions
}

```
The ```i``` is just a placeholder for whatever the user decides to write there. The ```$begin``` and ```$end``` are also placeholders to let the program know when it will start and end.
The user can also style many different elements and assign multiple properties with for loops.

#### Takeaways

 - Make sure to go over lessons multiple times if you don't get it the first time.
 - Use the minimum-viable-product method. For example, for my project so far, I started planing first before jumping into the actual project.



[Previous](entry05-mixins.md)

[Next](entry07-sass_structure.md)

[All Entries](../README.md)
























