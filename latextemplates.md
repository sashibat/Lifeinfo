```

\documentclass[a4paper,sans]{moderncv}
\usepackage[9pt]{extsizes}

\usepackage{xcolor}
\usepackage{framed}
\usepackage{parcolumns}


\moderncvstyle{classic}
\moderncvcolor{blue}
\usepackage{tikz}
\usetikzlibrary{calc}

\firstname{Sachi}
\familyname{Shibata}
\usepackage{moderncvheadi}
\usepackage[top=1.2cm, bottom=1cm, left=1cm, right=1cm]{geometry}

\begin{document}
%Where the colored blocks are, size and placement
	\begin{tikzpicture}[remember picture,overlay]
		%Side block placement, color and size
		%% For left rectangle
		\fill[color1!10] ($(current page.north west)-(-15cm,3cm)$) rectangle (current page.south east);
		%%Above block size, placement, and color
		\fill[color1!30](current page.north west) rectangle ([yshift=11.5cm]current page.east);
	\end{tikzpicture}

	\noindent\Huge\textbf{Sachi Shibata} \null\vspace{2.8mm}

	\color{black}
	\noindent\Large\textbf{B.S. Bioengineering Junior}

	%\noindent\color{gray}\rule{18cm}{0.5mm}\color{black} \\
	\vspace{0.7cm}


	\begin{parcolumns}[colwidths={1=0.7\textwidth, 2=0.22\textwidth}]{2}
		\colchunk{
		\textbf{\LARGE{Education}} \\
  	\noindent\color{gray}\rule{13cm}{0.5mm}\color{black} \\
 	\Large\textbf{University of California San diego}
 	\hspace{4.5cm}\textcolor{gray}{2016-present}
 	\begin{itemize}
 		\item Coursework:
		\begin{itemize}
			\item Mechanics
			\begin{itemize}
				\item Worked with strain gauges, oscilloscopes, digital multimeters, breadboards, and wave generators
				\item Additional topics: biomechanics, computational methods, and linear circuitry
			\end{itemize}
		\end{itemize}
 		\begin{itemize}
 			\item Computers:
 			\begin{itemize}
 				%Might have to take out when specific to job
 				\item Used \textbf{linux systems} for 1 year and windows for 5 years
 				\item Experienced \textbf{command line} to process data for data analysis (genome to get specific data, bioinformatics) and basic commands
 				\item Used \textbf{Matlab} to process data points, equations, and other fundamental commands
 				\item Introduced to aws. (\textbf{jupyter notebooks, machine learning})
 				\item Additional items with background in: \textbf{Vim, github, \LaTeX, python}
 			\end{itemize}
 			\item Biology
 			\begin{itemize}
 				\item Presented projects on affect of heart rate, brain waves, and or breathing \  rate. Required: \textbf{EKG, EEG, respiratory monitor}
 			\end{itemize}
 		\end{itemize}
 	\end{itemize}
\null

 	\textbf{\LARGE{Project Experience}} \\
 	\noindent\color{gray}\rule{13cm}{0.5mm}
 	\color{black}\Large


 	\noindent\Large
 		 \noindent\textbf{Projects}
 		\begin{itemize}
 			\item  Created this resume entirely in LaTeX
			\item Processed dirt from native sage and invasive iceplants to find pH, nutrition consumption, and moisture differences.
			\begin{itemize}
				\item Extracted bacteria's DNA from soil and amplfied
				\item Transformed bacteria's DNA into e.coli to find nutrients bacteria in soil use
				\item Required: \textbf{PCR, electrophoresis, blast, centrifuge, ELISA}
			\end{itemize}
			\item Tested a person's emotions using an ECG
			\begin{itemize}
				\item Used before and after recordings of emotional video
				\item Processed ECG peaks and drops using matlab
			\end{itemize}
 		\end{itemize}
	\textbf{FIRST tech challenge robotics}\null\hspace{5.5cm}\textcolor{gray}{2012-2015}
 	\begin{itemize}
 		\item Drove robot during competitions
 		\item Brainstormed ideas and prototypes for robot design(arm and chassis of robot)
 		\item Discussed strategy with local, country-wide, and international teams
		\item Qualified for state championship, superregionals, and world championship in 2013
 	\end{itemize}
 	%skills
		\null

		 	%experience
		 	\textbf{\LARGE{Work Experience}} \\
		 	\noindent\color{gray}\rule{13cm}{0.5mm} \\
		 	\color{black}\Large
		 	\textbf{Caterer}
		 	\null\hspace{9.5cm}\textcolor{gray}{2014-2016} \\
		 	\textit{Hao Wah, Part-time}
		 	\begin{itemize}
		 		\item Prepped food, kitchens, and designated area for events
		 		\item Acted as liaison between manager and some staff to coordinate event details
		 	\end{itemize}

		 	\noindent\Large
		 \textbf{Packer}
		 \null\hspace{9.8cm}\textcolor{gray}{2015-2016}  \\
		 \textit{Yume, Part-time, family's business} %\vspace{3mm}
		 \begin{itemize}
		 	\item Packed, shipped and loaded products to be sold to customers
		 	\item Lead communications between manager and customers by handling questions and complaints
		 \end{itemize}
		 }


		\colchunk[2]{
		\flushleft\Large\textbf{Email Address: } \\
		Sachishibat@gmail.com

		%\null
		%\noindent\Large\textbf{Linkedin Account: } \\
		%www.linkedin.com/in/ \\
		%sachi-shibata

		\null
		\noindent813-735-0489

		\null
		\noindent\Large\textbf{Machinery: }

		\null

		\large\noindent Soldering \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3,0); \draw [lightgray, line width=10]
			(3,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced

		\null
		\flushleft\large\noindent 3-D printing \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (2.5,0); \draw [lightgray, line width=10]
			(2.5,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Well-acquainted


		\null
		\flushleft\Large\textbf{Tech Proficiency:}

		\null

		\large\noindent Java \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3,0); \draw [lightgray, line width=10]
			(3,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced

		\null

		\flushleft\large\noindent Matlab \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3.4,0); \draw [lightgray, line width=10]
			(3.4,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced

		\null

		\flushleft\large\noindent Microsoft office \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3.65,0); \draw [lightgray, line width=10]
			(3.65,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced

		\null
		\flushleft\large\noindent Command line \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (2,0); \draw [lightgray, line width=10]
			(2,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Well aquainted \\

		\null
		\flushleft\large\noindent Arduino \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (2,0); \draw [lightgray, line width=10]
			(2,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Well-acquainted

		\null
		\flushleft\Large\textbf{Biological processing:}

		\null

		\flushleft\large\noindent Electrophoresis
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3.4,0); \draw [lightgray, line width=10]
			(3.4,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced

		\null
		\flushleft\large\noindent PCR \\
		\begin{tikzpicture}
			\draw [blue, line width=10]
			(0,0) -- (3,0); \draw [lightgray, line width=10]
			(3,0) -- (0.2\textwidth,0);
		\end{tikzpicture}
		\small\flushright Advanced
}
	\end{parcolumns}

\end{document}

```
