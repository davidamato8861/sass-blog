### Preprocessing:
Stylesheets are harder to learn(more complex)
- Stylesheets are larger
- Stylesheets are harder to mantain
- Stylesheets are more complex
 
Sass is really helpful in that anyone who plans on using Sass in the future can simply write css
css = Sass

You can use html with markdown, which is good because html and css go hand and hand

Sass allows you to view multiple files/watch multiple files with one command:    ```sass --watch app/sass:public/stylesheets```
Additonally, css syntax is virtually the same as sass, only with sass you don't need these symbols: ```{},```

css or scss are virtaully the same because both can store variables. Sass has the ability to store variables. Sass takes the users code, then
changes and displays it as normal css syntax like this:

```
body {
  font: 100% Helvetica, sans-serif;
  color: #333;
}
```