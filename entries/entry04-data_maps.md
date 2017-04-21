## Data Types/Maps and Lists
At first, I didn't really know where to begin because I just had finished going over variables and nesting, and while
there is more to learn about nesting, I wanted to branch off and learn about two new interesting topics:

 - Data Types
 - Maps and Lists
 
Since I have used both google and codeacademy as a reference, I decided to see if there were any lessons on codeacademy for data types.
Sure enough, there were lessons that teach the user to assign the different variables that they had already wrote in css.

Furthermore, Data Types hold different properties that can be used in a many ways. For example, there is number 
data types that might be used when creating an image and it's dimensions, a string data type used when assigning that string to a specific variable, a boolean 
data type simply for true or false, as well as a null data type used to set an empty value.

##### Data Types Examples:
- Numbers: ```1px...10px```
- Colors: ```blue,orange```

On the [sass reference page](http://sass-lang.com/documentation/file.SASS_REFERENCE.html#data_types) they have more examples of when to use data types, like the one below:

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

Additionally, I tried to find information on maps and lists on google and stumbled across a tutorial on [tutsplus](https://webdesign.tutsplus.com/tutorials/an-introduction-to-sass-maps-usage-and-examples--cms-22184). 
They made me realize how simple maps really are. Also, how easy it is to order maps in sass. Tutsplus even had an example of what maps may look
like in a real world scenario:

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
- If you are using codeacademy, make sure to go over the lessons you pass because they could be helpful later on.
- For those studying sass, a really helpful tool is the sass [documentation](http://sass-lang.com/documentation/) page. Refer back to it if you do not understand something.

[Previous](entry03-var.md)

Next

[All Entries](../README.md)