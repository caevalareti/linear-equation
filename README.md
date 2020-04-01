# linear-equation
A simple method to solve linear systems with Python
\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{setspace}
\usepackage{amsmath}
\usepackage{indentfirst}

\title{How to solve a Linear System Equation using Python}
\author{caevalareti}
\date{April 2020}

\begin{document}

\maketitle

\section{Problem}
Consider the system of linear equations below:

\begin{center}
$\left\{\begin{array}{ll}x + y = 6\\ -3x + y =2\end{array}\right$
\end{center}

A system with linear equations is equivalent to a matrix equation of the form:

\begin{center}

\textbf{AX = B}

\end{center}

\begin{center}

\begin{bmatrix} 1 & 1 \\ -3 & 1\end{bmatrix}\times\begin{bmatrix} x \\ y\end{bmatrix} = \begin{bmatrix} 6 \\ 2\end{bmatrix}$

\end{center}

So, to solve a system of linear equations, we need to define the 3 elements:

\begin{equation*}
\textbf\texttt{A = }
\begin{bmatrix}
1 & 1\\
-3 & 1\\

\end{bmatrix}
\end{equation*}

\begin{equation*}
\textbf{X = }
\begin{bmatrix}
x\\
y\\

\end{bmatrix}
\end{equation*}

\begin{equation*}
\textbf{B = }
\begin{bmatrix}
6\\
2\\

\end{bmatrix}
\end{equation*}

Using some matrix properties, we can isolate the vector with unknown variables and solve the product between the inverse of matrix A and matrix B.

\begin{center}

AX = B

A^{-1}AX = A^{-1}B

\textbf{X = A^{-1}B}

\end{center}

























\end{document}
