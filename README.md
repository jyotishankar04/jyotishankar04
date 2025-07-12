\documentclass[11pt, a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
\usepackage{geometry}
\geometry{left=1in, right=1in, top=1in, bottom=1in}
\usepackage{enumitem}
\usepackage{hyperref}
\usepackage{xcolor}
\usepackage{fontawesome5}
\usepackage{titlesec}
\usepackage{parskip}
\usepackage{amsmath}
\usepackage{noto}
\usepackage[default]{sourcesanspro}

% Define colors
\definecolor{linkcolor}{HTML}{0A66C2}
\definecolor{headercolor}{HTML}{181717}
\definecolor{subheadercolor}{HTML}{555555}

% Hyperlink setup
\hypersetup{
    colorlinks=true,
    linkcolor=linkcolor,
    urlcolor=linkcolor,
    pdftitle={Jyotishankar Patra Resume},
}

% Title format for sections
\titleformat{\section}{\Large\bfseries\color{headercolor}}{\thesection}{1em}{}
\titleformat{\subsection}{\large\bfseries\color{subheadercolor}}{\thesubsection}{1em}{}

% Custom commands
\newcommand{\contactline}[2]{\small #1 \textbf{#2}\par}
\newcommand{\project}[3]{\item \textbf{#1} \textendash\ #2 \\ \small #3}

% Remove default page numbers
\pagestyle{empty}

\begin{document}

% Header
\begin{center}
    {\Huge \textbf{Jyotishankar Patra (Suvam)}} \\
    \vspace{2mm}
    {\large Full Stack Developer | Computer Science Graduate} \\
    \vspace{4mm}
    \contactline{\faMapMarkerAlt}{\ Balasore, Odisha, India}
    \contactline{\faEnvelope}{\ \href{mailto:jyotipatra.subham@gmail.com}{jyotipatra.subham@gmail.com}}
    \contactline{\faPhone}{\ +91-9861250893} \\
    \vspace{2mm}
    \contactline{\faLinkedin}{\ \href{https://linkedin.com/in/jyotishankar-patra}{linkedin.com/in/jyotishankar-patra}}
    \contactline{\faGithub}{\ \href{https://github.com/jyotishankar04}{github.com/jyotishankar04}}
    \contactline{\faMedium}{\ \href{https://medium.com/@devsuvam}{medium.com/@devsuvam}}
\end{center}

% Education
\section*{Education}
\textbf{Fakir Mohan Autonomous College, Balasore} \hfill 2022--2025 \\
Bachelor of Science in Computer Science \\
CGPA: 7.02/10.00 \\
\vspace{2mm}
\textbf{Ramarani Institute of Technology, Balasore} \hfill 2020--2022 \\
12th in Science \\
Percentage: 79\%

% Professional Experience
\section*{Professional Experience}
\textbf{Full Stack Developer Intern} @ \href{https://ansmake.com}{Ansmake Technology} (Remote) \hfill Present
\begin{itemize}[leftmargin=*, labelsep=5mm]
    \item Optimized RESTful APIs using FastAPI, improving response times by 30\%
    \item Developed frontend components with Next.js, Tanstack Query, and Radix UI
    \item Collaborated in Agile environment to deliver SaaS product features
\end{itemize}

% Technical Stack
\section*{Technical Stack}
\subsection*{Programming Languages}
JavaScript \textbullet\ TypeScript \textbullet\ Python \textbullet\ C++ \textbullet\ SQL

\subsection*{Frontend Development}
React \textbullet\ Next.js \textbullet\ Tailwind CSS \textbullet\ ShadCN UI \textbullet\ Radix UI \textbullet\ Redux \textbullet\ React Query \textbullet\ Vite

\subsection*{Backend Development}
Node.js \textbullet\ Express \textbullet\ FastAPI \textbullet\ REST API \textbullet\ WebSocket

\subsection*{Databases \& ORM}
PostgreSQL \textbullet\ MongoDB \textbullet\ Redis \textbullet\ Prisma

\subsection*{DevOps \& Cloud Services}
Docker \textbullet\ AWS \textbullet\ NGINX \textbullet\ Cloudflare \textbullet\ Git \textbullet\ GitHub \textbullet\ Linux

\subsection*{AI/ML Technologies}
LangChain \textbullet\ Pinecone \textbullet\ Gemini AI

% Featured Projects
\section*{Featured Projects}
\begin{itemize}[leftmargin=*, labelsep=5mm]
    \project{QuickBrain AI}{AI-Powered Quiz Generator}
    {Tech Stack: React 19, Vite, Express.js, Prisma, Redis, LangChain, Gemini AI, Pinecone \\ Developed AI-driven quiz platform with vector-based question retrieval \\ Reduced API response time by 40\% through optimization}
    \project{Quizzify}{Interactive Quiz Platform}
    {Tech Stack: Next.js, PostgreSQL, Prisma, JWT Authentication \\ Implemented social login and real-time feedback system \\ Achieved 95\%+ test coverage with Jest}
    \project{Watch E-commerce}{Online Store}
    {Tech Stack: Next.js, Express, PostgreSQL, PhonePe, Cloudinary \\ Integrated payment gateway and media management \\ Improved page load speed by 60\%}
\end{itemize}

% Achievements & Certifications
\section*{Achievements \& Certifications}
\begin{itemize}[leftmargin=*, labelsep=5mm]
    \item \textbf{100xDevs Full Stack Development} Certification (2024)
    \item Ranked top 5\% in CodeChef competition (2023)
    \item GDSC Lead Interview Candidate (2023)
    \item Technical Writer (10k+ Medium views)
\end{itemize}

% GitHub Stats
\section*{GitHub Stats}
\begin{center}
    \includegraphics[height=4.5cm]{https://github-readme-stats.vercel.app/api?username=jyotishankar04&show_icons=true&count_private=true&hide_border=true&theme=default} \quad
    \includegraphics[height=4.5cm]{https://github-readme-stats.vercel.app/api/top-langs/?username=jyotishankar04&layout=compact&hide_border=true&theme=default} \\
    \vspace{2mm}
    \includegraphics[height=4.5cm]{https://github-readme-streak-stats.herokuapp.com/?user=jyotishankar04&hide_border=true&theme=default}
\end{center}

% Let's Connect
\section*{Let's Connect!}
I'm open to collaborations and new opportunities: \\
\vspace{2mm}
\contactline{\faEnvelope}{\ \href{mailto:jyotipatra.subham@gmail.com}{jyotipatra.subham@gmail.com}} \\
\contactline{\faLinkedin}{\ \href{https://linkedin.com/in/jyotishankar-patra}{linkedin.com/in/jyotishankar-patra}} \\
\contactline{\faTwitter}{\ \href{https://twitter.com/dev_suvam}{twitter.com/dev_suvam}}

\end{document}
