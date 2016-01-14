---
title: A Sample Set of Slides
author: Jonah Langlieb
date: Totally Not the Last Minute
color: light
---

# An flowery fjord fire *ordinary* slide


## And a block
With some text.

And some text underneath.


\note{

[ Here ](http://google.com) **are** my notes.

}

## Another slide

- With a
- list.

### WITH SOME MORE
TESTING

#### and some test8ing
*again*
\note{

A note on my list.

}


# Overlay Tricks

## A slide to show overlay tricks

\only{<1,3>}{This text appears on the first and third versions of the slide, but not the second.}

This uses beamer's highlighting command to \alert{<2>}{draw attention here}, but only on the second slide.

\note{<1>}{

Notes can also have overlay specs. First slide version note.

}

\note{<2>}{

Second.

}

\note{<3>}{

And third. Use \LaTeX\ macros in notes, like \emph{emphasis}.

}

## TeX-LOGO

\begin{textblock}{4}(0,1)
Grid demo UL
\end{textblock}

\begin{textblock}{4}(7,1)
Grid demo UR
\end{textblock}

\begin{textblock}{4}(0,5)
Grid demo LL
\end{textblock}

\begin{textblock}{4}(7,5)
\only<2>{Grid demo LR}
\end{textblock}

\note{<2>}{

To get overlay effects with materials placed using \texttt{textpos}, you have to specify the overlay within the \texttt{textblock} environment.

}

#another section

##testing
 - hello list
 - again
