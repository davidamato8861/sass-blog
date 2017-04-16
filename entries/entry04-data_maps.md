## Data Types/Maps and Lists
At first, I didn't really now where to begin because I just had finished going over the basics of variables and nesting, and while
there is more to learn about nesting, I wanted to banch off and learn about two new topics in sass that looked interesting:
 - Data
 - Maps and Lists

Since I have been using both google and codeacademy as a reference, I decided to see if there were any lessons on codeacademy for data types.
Sure enough, there were lessons on data types that the user can assign to different variables that they had already wrote in css.

Furthermore, Data Types hold different properties that can be used in a variety of ways. For example, there are number 
data types that might be used when creating an image and it's dimensions, a string data type used when assigigning that string to a specific variable, a boolean 
data type simply for true or false, as well as a null data type used to set an empty value.

On the [sass reference page](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#data_types), they have good examples of when to use data types and why it would be helpful:

#### Strings

##### Css:
```
@mixin firefox-message($selector) {
  body.firefox #{$selector}:before {
    content: "Hi, Firefox users!";
  }
}

@include firefox-message(".header");
```

##### Sass:
```
body.firefox .header:before {
  content: "Hi, Firefox users!"; }
```

Additionally, I tried to find information on maps and lists on google and stumbled accross a tutorial about sass maps/lists on [tutsplus](https://webdesign.tutsplus.com/tutorials/an-introduction-to-sass-maps-usage-and-examples--cms-22184). 
They made me realize how simple maps really are. Also, how easy it is to order maps in sass. Tutsplus even had an example of what maps may look
like in a real world scenarion:

##### Input:
```
/* Define the Sassy Map called $icons */
$icons: (
  checkmark: a,
  plus: b,
  minus: c
);
```

##### Output:
```
/* For each key in the map, created an own class */
.icon--checkmark {
  content: "a";
}
 
.icon--plus {
  content: "b";
}
 
.icon--minus {
  content: "c";
}
```
As you can see, sass makes it very simple and efficient in that it takes the user's coupled code and turns it into seperate categories, that can be easily 
changed. 

#### Takeaways
- If you are using codeacademy, make sure to go over the lessons you pass and not just pass them because they could be helpful later on.
- For those studying sass, its good to use the sass [documentation](http://sass-lang.com/documentation/) if you forget something.

[Previous](entry03-var.md)

Next

[All Entries](../README.md)