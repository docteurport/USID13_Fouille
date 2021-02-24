\documentclass{article}
\usepackage[utf8]{inputenc}

\title{USID13 Fouille de donnees}
%\date{}


\begin{document}

\maketitle

\section*{Distance}
\subsection*{Exercice 1}
Prouvons que les trois axiomes $A1$ à $A3$ impliquent la condition de non-négativité: 
$$d(x,y) \geq 0.$$

\textit{Preuve}
On a d'après $A3$ : $$d(x,z)\leq d(x,y)+d(y,z) $$
ce qui implique que :    $$d(x,y) \geq d(x,z) - d(y,z)$$
et d'après $A2$ , $$d(x,y) \geq d(z,x) - d(z,y)$$
donc 
 $$d(x,y) \geq d(z,x) - d(z,y) \geq -d(z,z)=0$$
 d'où  
 $$d(x,y) \geq 0.$$
\end{document}
