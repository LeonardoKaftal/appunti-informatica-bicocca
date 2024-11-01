 Siano $A_n$ e $B_n$ due serie tali che $A_n \leq B_n$ per ogni $n$. Allora:

\begin{enumerate}
    \item **Convergenza:** Se la serie $\sum_{n=1}^{\infty} B_n$ converge, allora anche la serie $\sum_{n=1}^{\infty} A_n$ converge.
    \item **Divergenza:** Se la serie $\sum_{n=1}^{\infty} A_n$ diverge, allora anche la serie $\sum_{n=1}^{\infty} B_n$ diverge.
\end{enumerate}

Casi negativi:

\begin{enumerate}
    \item[3.] **Divergenza della maggiorante:** Se la serie $\sum_{n=1}^{\infty} B_n$ diverge, **non possiamo concludere nulla** sulla convergenza o divergenza della serie $\sum_{n=1}^{\infty} A_n$.
    \item[4.] **Convergenza della minorante:** Se la serie $\sum_{n=1}^{\infty} A_n$ converge, **non possiamo concludere nulla** sulla convergenza o divergenza della serie $\sum_{n1}^{\infty} B_n$.
\end{enumerate}

Esempi:

Esempio 1:

Consideriamo la serie $\sum_{n=1}^{\infty} \frac{1}{n - \ln(n)}$. Osserviamo che per $n$ sufficientemente grande, $n - \ln(n) \leq n$. Quindi:

$$\frac{1}{n - \ln(n)} \geq \frac{1}{n}$$

Poiché la serie armonica $\sum_{n=1}^{\infty} \frac{1}{n}$ diverge, per il punto 2 del teorema, anche la serie $\sum_{n=1}^{\infty} \frac{1}{n - \ln(n)}$ diverge.

Esempio 2:

Consideriamo la serie $\sum_{n=1}^{\infty} \frac{\sin^2(n)}{n^2}$. Osserviamo che $0 \leq \sin^2(n) \leq 1$ per ogni $n$, quindi:

$$\frac{\sin^2(n)}{n^2} \leq \frac{1}{n^2}$$

Poiché la serie armonica generalizzata $\sum_{n=1}^{\infty} \frac{1}{n^2}$ converge (con esponente maggiore di 1), per il punto 1 del teorema, anche la serie $\sum_{n=1}^{\infty} \frac{\sin^2(n)}{n^2}$ converge.

