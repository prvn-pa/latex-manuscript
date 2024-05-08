# Manuscript Sections

Followed by preamble the document section begins. The general template is as follows:

```
\begin{document}


\end{document}
```

Inside this, abstract, sections, figures and tables has to be nested. Like,

```
\begin{document}

    \begin{abstract}
    Some text goes here.
    \end{abstract}

    \section{Introduction}
    Some text goes here.

    \section{Results and Discussion}
    Some text goes here.

        \begin{figure}
        Figure Details Here
        \end{figure}

        \begin{table}
        Table Details Here
        \end{table}

    ...


\end{document}
```

- though mentioned seprately (will be discussed seprately) the references should also be nested in the documents part, prior to `\end{document}` as:

```
...

\bibliography{ref}
\end{document}
```

## Special Sections

Usually 