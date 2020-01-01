# Notes on interfacing sphinx with `jupyter` notebooks

- we use the `nbsphinx` extension from conda
- use no spaces in latex math, it won't render properly

~~~~
% renders incorrectly !!
\begin{equation}
  some indented math
\end{equation}

% renders correctly.
\begin{equation}
some non-indented math
\end{equation}
~~~~
