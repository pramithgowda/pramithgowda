- 👋 \documentclass[11pt, a4paper, sans]{moderncv}

\moderncvstyle{banking}
\moderncvcolor{blue}

\usepackage[scale=0.75]{geometry}
\usepackage{xcolor}

% Change border lines to grey
\definecolor{color1}{RGB}{0,0,0} % Text color
\definecolor{color2}{RGB}{128,128,128} % Line color

\renewcommand*{\sectionstyle}[1]{{\color{color1}\textbf{#1}}}
\renewcommand*{\subsectionstyle}[1]{{\color{color1}\textit{#1}}}
\renewcommand*{\hintfont}{\color{color2}}

% Personal Information
\firstname{Your}
\familyname{Name}
\title{Software Engineer}
\address{Your Street}{Your City, ZIP Code}
\phone{Your Phone Number}
\email{Your Email}
\social[linkedin]{your-linkedin}
\social[github]{your-github}
\extrainfo{Portfolio: your-portfolio-link}

\begin{document}

\makecvtitle

\section{Education}
\cventry{Year--Year}{B.Tech in Computer Science}{Your University}{Your City}{\textit{GPA: X.X/4.0}}{Relevant coursework: List of courses}

\section{Experience}
\cventry{Year--Present}{Software Engineer}{Your Current Company}{City}{}{Description of your responsibilities and achievements.}

\section{Projects}
\cventry{Project Title}{Description}{Technologies Used}{}{}{Results/Achievements}

\section{Skills}
\cvitem{Programming}{List of programming languages and technologies you are proficient in.}
\cvitem{Tools}{List of relevant tools and software.}
\cvitem{Soft Skills}{List of soft skills, e.g., communication, teamwork, problem-solving.}

\section{Achievements and Awards}
\cventry{Year}{Award Name}{Organization}{}{}{Description of the award or achievement.}

\section{Languages}
\cvitemwithcomment{Language 1}{Proficiency Level}{Comments}
\cvitemwithcomment{Language 2}{Proficiency Level}{Comments}

\section{References}
\cvitem{}{Available upon request.}

\end{document}
