## Sass Structure

I started this week finishing a few things from the last topic I covered, functions, and felt that there were a few things that 
could be adressed in terms of sass' structure. Additionally, I will be going over a few mini topics that are an essential part of sass' file structure.

One of the highlights of sass is that it is really easy to order pretty much any selector. This is because ordering/organizing files is built into the sass
library. Here is a rundown of sass' basic file structure found on codeacademy:

``` 
- Sass
   - layout
      - grid.scss        # Grid System
      - header.scss      # Header
      - footer.scss      # Footer
   - pages               
      - home.scss        # Home specific styles
      - contact.scss     # Contact specific styles
``` 
The above file structure example shows four different categories inside of the sass directory, and inside of those four categories are important files. The files correspond to the
category they are in. For example, in the layout category there are files named grid or header, because they are part of the pages "layout". Now, each persons layout will be different
than the next but, anyone can follow this type of structuring method when building something using the sass language.

#### @Import

In CSS, there is a rule already in the library called '@Import'. So...sass took this rule from css and made it usable in .scss files, as well as other sass files.
What happens is that sass files are imported or carried over into a main.scss file, which is usually/mostly found in sass directories. Then, the code written in main.scss is compiled into
the ouput, which is just css. Additionally, the main.scss file will always have access to any variables found in other imported files. 

Furthermore, importing files can save you a lot of trouble since you won't have to write the same lines over and over again for a new selector. All you have
to do is import files with variables already written, then your good to go.

#### Partials

Partials are mostly used for importing different variables found in other files. One of these files are usually your `main.scss` file because that is where your sass would be stored. Furthermore,
importing variables using partials is simple, just remember to include `_` before the file name, or sass will automatically compile it into css. Lastly, if you are going to import a partial into your main file, drop
the underscore.

#### @Extend

@Extend allows the user to apply styling to an object or element on a web page. Specifically, it takes styling for one class 
and distributes it to another class. @Extend makes it super easy to style multiple HTML elements, while maintaining all of the classes and styling from
the first element.

#### %Placeholders

Placeholders are simply class selectors that allow the user to add rules to their styling choices. They make it easy for the user to 
write the rules they want and use them when styling multiple elements.

#### Takeaways

 - For the people studying sass, be sure to study @Import because it can be really useful when using it in conjuction with HTML to make a webpage/webapp.

[Previous](entry06-functions.md)

Next

[All Entries](../README.md)

