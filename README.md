# latex_template
Template(s) used for latex documents of my own

## empty_template

You will find in *empty_template* the basic template to use. Make sure that the 
\input{headfile.tex} in the template.tex file can read the headfile.tex file from
the correct directory.

The main content of the document should be in the template.tex file.

You can rename the latter for your own convenience.

## Example_of_use

You will find an example of use (not necessarily up to date) of my latex template,
in the directory *example_of_use*.


The example is pretty basic, and in french (and latin for the \lipsum parts) only to give
an idea of what it can look like.

The template is still quite simple and there still needs some fixes to be done.

## Common usage

I personnaly use this template using nvim with the texlab lsp and the vimtex plugin with latexmk for compiling.
A lot of commands are actually derived from nvim snippets so the newcommands section is quite short.

