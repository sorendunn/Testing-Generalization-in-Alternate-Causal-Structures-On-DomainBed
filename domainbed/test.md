b\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 71.5 $\pm$ 0.0       & 73.5 $\pm$ 0.0       & 9.8 $\pm$ 0.0        & 51.6                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
CORAL                     & 56.6 $\pm$ 10.6           & 56.6                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 72.4 $\pm$ 0.0       & 77.8 $\pm$ 0.0       & 48.9 $\pm$ 0.0       & 66.4                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
CORAL                     & 67.9 $\pm$ 3.2            & 67.9                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 71.5 $\pm$ 0.0       & 72.2 $\pm$ 0.0       & 9.8 $\pm$ 0.0        & 51.2                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
CDANN                     & 40.9 $\pm$ 21.9           & 40.9                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 74.9 $\pm$ 0.0       & 74.4 $\pm$ 0.0       & 30.2 $\pm$ 0.0       & 59.8                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
CDANN                     & 52.4 $\pm$ 15.7           & 52.4                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}
combine these two latex codes

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 72.7 $\pm$ 0.0       & 73.7 $\pm$ 0.0       & 10.1 $\pm$ 0.0       & 52.2                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
GroupDRO                  & 52.2 $\pm$ 0.0            & 52.2                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredMNIST}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 73.7 $\pm$ 0.0       & 73.6 $\pm$ 0.0       & 49.0 $\pm$ 0.0       & 65.4                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredMNIST}     & \textbf{Avg}              \\
\midrule
GroupDRO                  & 65.4 $\pm$ 0.0            & 65.4                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 89.2 $\pm$ 0.0       & 35.5 $\pm$ 0.0       & 9.7 $\pm$ 0.0        & 44.8                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CDANN                     & 36.0 $\pm$ 18.6           & 36.0                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 89.9 $\pm$ 0.0       & 67.2 $\pm$ 0.0       & 14.5 $\pm$ 0.0       & 57.2                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CDANN                     & 46.5 $\pm$ 22.6           & 46.5                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 15.9 $\pm$ 0.0       & 71.5 $\pm$ 0.0       & 50.5 $\pm$ 0.0       & 45.9                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CORAL                     & 38.4 $\pm$ 16.0           & 38.4                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 49.6 $\pm$ 0.0       & 74.7 $\pm$ 0.0       & 51.6 $\pm$ 0.0       & 58.6                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CORAL                     & 56.3 $\pm$ 4.8            & 56.3                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 89.2 $\pm$ 0.0       & 78.3 $\pm$ 0.0       & 10.2 $\pm$ 0.0       & 59.3                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
GroupDRO                  & 59.3 $\pm$ 0.0            & 59.3                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST1}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 89.3 $\pm$ 0.0       & 79.6 $\pm$ 0.0       & 49.5 $\pm$ 0.0       & 72.8                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
GroupDRO                  & 72.8 $\pm$ 0.0            & 72.8                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 98.4 $\pm$ 0.0       & 50.5 $\pm$ 0.0       & 21.7 $\pm$ 0.0       & 56.9                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CDANN                     & 48.1 $\pm$ 18.6           & 48.1                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CDANN                & 98.5 $\pm$ 0.0       & 90.1 $\pm$ 0.0       & 49.0 $\pm$ 0.0       & 79.2                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CDANN                     & 71.7 $\pm$ 16.0           & 71.7                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 98.2 $\pm$ 0.0       & 72.6 $\pm$ 0.0       & 19.0 $\pm$ 0.0       & 63.3                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CORAL                     & 72.0 $\pm$ 18.5           & 72.0                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
CORAL                & 98.4 $\pm$ 0.0       & 84.1 $\pm$ 0.0       & 21.0 $\pm$ 0.0       & 67.9                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
CORAL                     & 75.5 $\pm$ 16.2           & 75.5                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}

**Enter**

### Noah

![Noah Fischer](https://scontent-ord5-2.xx.fbcdn.net/v/t1.6435-1/75242175_144347880299321_7380324578557427712_n.jpg?stp=dst-jpg_p100x100&_nc_cat=100&ccb=1-7&_nc_sid=7206a8&_nc_ohc=p-0vdN_5Zp0AX-bB8x1&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent-ord5-2.xx&oh=00_AfDCE_TYU6KwDUO-ThX_qKmmim4oYJOTLl3ZySCz-BwVpA&oe=6495D957)

\documentclass{article}
\usepackage{booktabs}
\usepackage{adjustbox}
\begin{document}
\section{Full DomainBed results}
% Total records: 153

\subsection{Model selection: training-domain validation set}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 9.2 $\pm$ 0.0        & 100.0 $\pm$ 0.0      & 18.9 $\pm$ 0.0       & 42.7                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
GroupDRO                  & 42.7 $\pm$ 0.0            & 42.7                      \\
\bottomrule
\end{tabular}}
\end{center}

\subsection{Model selection: test-domain validation set (oracle)}

\subsubsection{ColoredRotatedMNIST2}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcccc}
\toprule
\textbf{Algorithm}   & \textbf{+90\%}       & \textbf{+80\%}       & \textbf{-90\%}       & \textbf{Avg}         \\
\midrule
GroupDRO             & 50.3 $\pm$ 0.0       & 100.0 $\pm$ 0.0      & 50.5 $\pm$ 0.0       & 66.9                 \\
\bottomrule
\end{tabular}}
\end{center}

\subsubsection{Averages}

\begin{center}
\adjustbox{max width=\textwidth}{%
\begin{tabular}{lcc}
\toprule
\textbf{Algorithm}        & \textbf{ColoredRotatedMNI & \textbf{Avg}              \\
\midrule
GroupDRO                  & 66.9 $\pm$ 0.0            & 66.9                      \\
\bottomrule
\end{tabular}}
\end{center}
\end{document}
