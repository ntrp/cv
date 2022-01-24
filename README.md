# Personal CV

This is my personal CV as code using the [Awesome-CV](https://github.com/posquit0/Awesome-CV) template.

## Building

To build the PDF the use of `xelatex` is required, simply run:
```
xelatex -interaction nonstopmode cv.tex
```

## Live Edit

Editing and previewing the result live can be achieved by running:
```
find . -name "*.tex" | entr bash -c "xelatex -interaction nonstopmode cv.tex && pkill -HUP mupdf"
```
The command depends on two tools:
- [entr](https://eradman.com/entrproject)
- [mupdf](https://mupdf.com)

You can easily adapt the command to use the tool of your choice.
