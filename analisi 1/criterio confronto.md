\documentclass[12pt]{article} % Imposta la dimensione del carattere
\usepackage{amsmath} % Per simboli matematici e funzioni

\usepackage{geometry} % Per margini più ampi
\geometry{a4paper, margin=1.2in}

\begin{document}

\title{\textbf{Teorema del Confronto tra Serie}}
\author{}
\date{}
\maketitle

Siano $A_n$ e $B_n$ due serie tali che $A_n \leq B_n$ per ogni $n$. Allora:

\begin{enumerate}
    \item \textbf{Convergenza:} Se la serie $\sum_{n=1}^{\infty} B_n$ converge, allora anche la serie $\sum_{n=1}^{\infty} A_n$ converge.
    \item \textbf{Divergenza:} Se la serie $\sum_{n=1}^{\infty} A_n$ diverge, allora anche la serie $\sum_{n=1}^{\infty} B_n$ diverge.
\end{enumerate}

\section*{Casi Negativi}

\begin{enumerate}
    \item[3.] \textbf{Divergenza della Maggiorante:} Se la serie $\sum_{n=1}^{\infty} B_n$ diverge, \textbf{non possiamo concludere nulla} sulla convergenza o divergenza della serie $\sum_{n=1}^{\infty} A_n$.
    \item[4.] \textbf{Convergenza della Minorante:} Se la serie $\sum_{n=1}^{\infty} A_n$ converge, \textbf{non possiamo concludere nulla} sulla convergenza o divergenza della serie $\sum_{n=1}^{\infty} B_n$.
\end{enumerate}

\section*{Esempi}

\subsection*{Esempio 1}

Consideriamo la serie $\sum_{n=1}^{\infty} \frac{1}{n - \ln(n)}$. Per $n$ sufficientemente grande, si ha che $n - \ln(n) \leq n$, quindi:

\[
\frac{1}{n - \ln(n)} \geq \frac{1}{n}.
\]

Poiché la serie armonica $\sum_{n=1}^{\infty} \frac{1}{n}$ diverge, secondo il punto 2 del teorema, anche la serie $\sum_{n=1}^{\infty} \frac{1}{n - \ln(n)}$ diverge.

\subsection*{Esempio 2}

Consideriamo la serie $\sum_{n=1}^{\infty} \frac{\sin^2(n)}{n^2}$. Osserviamo che $0 \leq \sin^2(n) \leq 1$ per ogni $n$, quindi:

\[
\frac{\sin^2(n)}{n^2} \leq \frac{1}{n^2}.
\]

Poiché la serie armonica generalizzata $\sum_{n=1}^{\infty} \frac{1}{n^2}$ converge (essendo l’esponente maggiore di 1), in base al punto 1 del teorema, anche la serie $\sum_{n=1}^{\infty} \frac{\sin^2(n)}{n^2}$ converge.

\end{document}
