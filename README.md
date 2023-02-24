# LaTeX-cheat-sheet
These are just some of the most commonly used LaTeX commands and environments. For more information and a more comprehensive list of commands, refer to the LaTeX documentation or online resources.

## Basic Document Structure

`\documentclass{class}    % Defines the type of document`\
`\usepackage{package}    % Imports packages`\
`\begin{document}        % Begins the document`\
`% Document contents go here`\
`\end{document}          % Ends the document`

## Typesetting Text

`\textbf{text}            % Boldface`\
`\textit{text}            % Italics`\
`\underline{text}         % Underline`\
`\emph{text}              % Emphasized`\
`\textsuperscript{text}   % Superscript`\
`\textsubscript{text}     % Subscript`\
`\texttt{text}            % Typewriter font`\
`\textsc{text}            % Small caps`

## Environments

`\begin{environment}    % Begins an environment`\
`% Contents of the environment go here`\
`\end{environment}      % Ends the environment`

## Lists

`\begin{itemize}       % Unordered list`\
`\item Item 1`\
`\item Item 2`\
`\end{itemize}`

`\begin{enumerate}     % Ordered list`\
`\item Item 1`\
`\item Item 2`\
`\end{enumerate}`

## Tables 

`\begin{tabular}{format}  % Creates a table`\
`% Table contents go here`\
`\end{tabular}`

`\hline           % Horizontal line`\
`|                % Vertical line`\
`&                % Separates columns`\
`\\               % Starts a new row`

## Images

`\begin{figure}[h]              % Begins a figure environment and h refers "here" but use "htbp" to fix alginment issues`\
`\centering                % Centers the image`\
`\includegraphics{image}   % Includes the image`\
`\caption{Caption}         % Adds a caption`\
`\label{fig:label}         % Adds a label for cross-referencing`\
`\end{figure}`

## Mathematical Equations

`$equation$             % Inline equation`\
`\[ equation \]         % Displayed equation`\
`\begin{equation}       % Numbered equation`\
`equation`\
`\end{equation}`

`\frac{numerator}{denominator}   % Fraction`\
`\sqrt{expression}              % Square root`\
`\sum_{i=1}^{n} expression      % Summation`\
`\int_{a}^{b} expression dx     % Integral`\
`\alpha, \beta, \gamma, \delta  % Greek letters`

## References and Citations

`\label{marker}               % Labels an element for cross-referencing`\
`\ref{marker}                 % Prints the value of a labeled element`\
`\cite{key}                   % Cites a reference`\
`\bibliographystyle{style}    % Sets the style for the bibliography`\
`\bibliography{bibfile}       % Imports the bibliography`
