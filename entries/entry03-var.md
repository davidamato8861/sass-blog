## Variables/Tinkering
To preface this entry, I thought it would be important to simply go over what I have been doing, in terms of tinkering 
with Sass. Additionally, I would like to briefly go through the setup process of sass and some other things.

#### Setup
After realizing that the setup for sass is as simple as typing in a few commands: ```gem install sass``` and ```sass main.scss main.css```, I looked for resources online to help me better understand sass. One very valuable 
resource is codeacademy because it gives a lot of extra examples as well as examples of code that would be used in the real world. I then decided
to dive a little deeper into previously mentioned sass topics.
I narrowed it down to these two topics:
- Variables
- Nests

#### Nesting
I know that there is a lot of ground to cover in regards to the topic of nesting, so I will make it brief. Nesting is basically when you order certain selectors into a more readable/effiecient format.
Codeacademy's example of this was the parent and the child selectors. They showed examples of nesting with and without sass:

##### Without:
```
.parent {
  color: blue;
  .child {
    font-size: 12px;
  }
}
```

##### With:
```
.parent {
  color: blue;
}

.parent .child {
    font-size: 12px;
}

```
As you can see above, sass easily groups parents and childs together, so the user will not get confused.

#### Variables
We have seen countless examples of variables in software engineering. Variables are used to assign a value to something. For example: 
```
color: blue;
```

Sass works exactly the same way with any other variable in css. Nevertheless, variables are crucial in anty programming language. 















[Previous](entry02-Syntax.md)

Next

[All Entries](../README.md)