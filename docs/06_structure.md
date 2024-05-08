# Manuscript Structure

Usually a Latex manuscript contains three parts: (a) preamble (b) sections and (c) references.

## Preamble

Preamble can be further divided into two parts (a) formatting part (b) details part. Formatting part carries the style file details, margins, paper sizes kind details. The details part contains manuscript specific information such as title, author and their address.

Lets start with a very simple format. This is the official template from ACS. It preamble looks like this:

```
\documentclass[12pt]{article}
\usepackage{amsmath}
\usepackage{graphicx}

\title{Getting started}
\author{Type Your Name}
\date{\today}

\begin{document}
\maketitle

\end{document}
```

```
\documentclass[journal=jacsat,manuscript=article]{achemso}
\usepackage[version=3]{mhchem} % Formula subscripts using \ce{}
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{graphicx}
\usepackage[symbolgreek]{mathastext}
\usepackage{xcolor}
\usepackage[parfill]{parskip}
\usepackage{booktabs}
\usepackage{multirow}
\usepackage{longtable}
\usepackage{lineno}
\usepackage{subcaption}
\linenumbers
\newcommand*\mycommand[1]{\texttt{\emph{#1}}}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\author{Author 1 Name}
\email{author1@email.address}
\affiliation[Address1_ID]
{Add actual address, separated by comas and text}

\author{Author 2 Name}
\email{author2@email.address}
\affiliation[Address2_ID]
{Add actual address, separated by comas and text}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\title[ ]
  {Add a suitable title here}

\keywords{keyword 1, keyword 2, etc.}
```

- this is ACS specific template, however in most cases you can simply submit with this template and can be edited by journal office at the proofing stage or you can simply replace preamble matching journal template

[ToDo] **Explain things here**