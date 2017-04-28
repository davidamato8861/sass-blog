## Mixins

I originally started working on more of data types through lists in sass. I thought that was what I actually wanted to explore but, I decided
to shift gears and explore mixins a little bit more, since mixins are a very important topic under the umbrella that is sass.

To begin, a mixin is made up of a group of css selectors. Mixins hold multiple variables in minimal lines. Take a look at an example of a mixin:
``` SASS
@mixin .box {
  border-radius: 10px;
}

```
Additionally, mixins are responsible for sorting these variables. Mixins can be used/most often used to go hand-in-hand with 
html(webpages). Mixins are also capable of pairing parent and child selectors together. This is most likely due to sass having the ability
to pair selectors by default. 

#### Arguments/Parameters

Not only are mixins able to both sort and hold multiple variables in a few lines but, mixins are also able to 
take in a value. Think of when we wrote code for ruby and had to pair keys to values. Mixins basically do the same thing, just with one
"mixin" and a bunch of rules inside of it. 

Codeacademy has a lot of great examples of Mixins, like this one found on one of the sass lessons:

``` SASS
@mixin backface-visibility($visibility) {
  backface-visibility: $visibility;
  -webkit-backface-visibility: $visibility;
  -moz-backface-visibility: $visibility;
  -ms-backface-visibility: $visibility;
  -o-backface-visibility: $visibility;
}
```
#### Defaults

Mixins can take in whats called a default value, which is simply a placeholder for a previously created mixin that has not been given a value. 
There is a special notation that must be used when assigning a default value to a mixin. 

#### String Interpolation

String interpolation is very useful when creating something with a lot of different variables. The user inserts a variable string in between two other strings.
Mixins are also useful when using multiple variables in selectors. 

``` SASS
@mixin photo-content($file) {
  content: url(#{$file}.jpg); //string interpolation
  object-fit: cover;
}

.photo { 
  @include photo-content('titanosaur');
  width: 60%;
  margin: 0px auto; 
  }
```
##### After Interpolation:
``` SASS
.photo { 
  content: url(titanosaur.jpg);
  width: 60%;
  margin: 0px auto; 
}
```
#### Takeaways

- String Interpolation is a big part of learning sass, tinkering and practicing examples can help.
- Google is your best friend.



[Previous](entry04-data_maps.md)

Next

[All Entries](../README.md)