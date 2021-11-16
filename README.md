# layangelo-latex

## How to use
To import the layout you need to:    
1. Clone this repository.  
2. Add the obtained folder to you LaTeX Project.  
3. Insert in your main *.tex* the following line of code after your ``\documentclass{[...]}``:
```
\input{layangelo-latex/layout}
```

## Commands

### Highliting
``\hly{text}`` and ``\hlY{text}`` are the commands used to highlight.   
Both use the stock yellow highlighter, but ``\hlY{text}`` is a bit darker.  

### Enviroments
#### File
Usage:
```md
\begin{file}[optional filename, defaults to "File"]
	File contents, for example, with a listings environment
\end{file}
```
#### Info
Usage:
```md
\begin{info}[optional title, defaults to "Info:"]
	Some info
\end{info}
```
#### Question
Usage:
``` md
\begin{question}[optional title]
	Question contents
\end{question}
```

#### Warning
Usage:
```md
\begin{warn}[optional title, defaults to "Warning:"]
	Some Warning
\end{warn}
```

## License 
This template originates from [LaTeXTemplates](http://www.LaTeXTemplates.com)
#### Started from:
__Lachaise Assignment__  
Original Authors:

- Marion Lachaise
- François Févotte
  
Vel (vel@LaTeXTemplates.com)

Changes from the original template are listed in the ```layout.tex``` file.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)