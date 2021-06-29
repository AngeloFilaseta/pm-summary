# How to Use
To import the layout you need to:    
1. Clone this repository.  
2. Add the obtained folder to you LaTeX Project.  
3. Insert in your main *.tex* the following line of code after your ``\documentclass{[...]}``:
```
\input{layangelo-latex/layout}
```
# Commands

## Highliting
``\hly{text}`` and ``\hlY{text}`` are the commands used to highlight.   
Both use the stock yellow highlighter, but ``\hlY{text}`` is a bit darker.  

## Enviroments
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