## Syntax

I began reading on google about sass because I wanted to see what the syntax is and more importantly, if it was similiar 
to css or could be used with html. I had found the learn sass tab and it was good but, basic. So I decided to search
on google to see if there were any easier or more effiecient ways of writing sass. I then stumbled accross some documentation on the sass-website, and it basically
gives you a cheatsheet where you can look at any topic and it will give you a whole description:

<img src="https://github.com/davidamato8861/sass-blog/blob/master/images/Pic2.png" style="width: 395px;"/>

One big change from the normal css syntax is that you do not need to 
include any beginning or closing tags:
``{};``
Here's a bit of code just to see the syntax:
```
$font-stack:    Helvetica, sans-serif
$primary-color: #333

body
  font: 100% $font-stack
  color: $primary-color
```

#### Variables
Very similiar to css/scss, Sass has the ability to store variables. The way it works is that the user places a ```$```sign in front of the
variable name, then simply write the content inside of that variable:

```$font-color: blue```

#### Nesting
Html is different than css because it has a way of ordering lists and other things that relate to navigation for websites.
Sass is similiar to html in that it takes the user's pre written css selectors and turns them into html navigation. Additonally, you can use the li, ul and a selectors
to organize your css.
Here is an example of nesting with sass:

```
nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

nav li {
  display: inline-block;
}

nav a {
  display: block;
  padding: 6px 12px;
  text-decoration: none;
}
```

[All Entries](../README.md)