## Project idea: Sound Language interpreter

Who is in it:
* John Kilgo github.com/john-kilgo
* Tyler Bezuka github.com/tylerbezuka
* Tony Ventura github.com/tventura1337

Project concept:

Using several libraries, the project will be to build a windowed language editor. In one text input box will be the editable region, in the other will be a rendering of the inputted data.

1. The first milestone will roughly be getting this to work with a simple html object.
1. The second milestone will roughly be getting this to work with a sound library allowing the user to generate their own sounds via some sort of language we define (and a library like the rsound library).

If this proves to hard the milestones will be adjusted accordingly and we may have to drop either the html rendering or the custom sound language.

Potential breakdown of tasks amongst three people:
* Implementing a gui
* Parsing and storing html input (for milestone 1)
* Interpreting and displaying html (for milestone 1)
* Developing a sound and/or display syntax for the user input (for milestone 2)
* Interpreting and displaying/visualizing/playing output (for milestone 2)

Potential libraries:
* racket/gui
* html-parsing
* browser
* rsound
* others to be determined

