\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym,fullpage,titlesec,marvosym,color,enumitem,hyperref,fancyhdr,tabularx,xcolor,microtype,babel,geometry}

\geometry{margin=0.35in} % Compact margins for one page

% Page style
\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\urlstyle{same}
\raggedbottom
\raggedright

\setlength{\tabcolsep}{6pt}

% Professional font setup
\usepackage{lmodern}
\usepackage[T1]{fontenc}

% Section formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\normalsize\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-2pt}]

% Commands
\newcommand{\tech}[1]{\textbf{#1}}
\newcommand{\resumeItem}[1]{\item #1}
\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{\textwidth}{@{\extracolsep{\fill}}l r}
      \textbf{#1} & \textbf{#2} \\
      \textit{#3} & \textit{#4} \\
    \end{tabular*}\vspace{-2pt}
}
\newcommand{\resumeProjectHeading}[3]{
    \item
    \begin{tabularx}{\textwidth}{X r}
      {\textbf{#1}} & {\href{#2}{\textbf{\underline{#3}}}} \\
    \end{tabularx}\vspace{-2pt}
}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.1in, label={}, itemsep=1pt, topsep=1pt]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{-2pt}}

\newcommand{\resumeItemListStart}{\begin{itemize}[leftmargin=0.2in, label={\textbullet}, itemsep=1pt, topsep=0pt, parsep=0pt]}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-2pt}}

%----------DOCUMENT----------
\begin{document}

%----------HEADER----------
\begin{center}
    {\LARGE \textbf{SUSHANT PAUDEL}} \\[1pt]
    {\large Backend Developer} \\[2pt]
    \href{mailto:sushantpaudel77@gmail.com}{sushantpaudel77@gmail.com} \textbar\ 
    +977-9844881513 \\[1pt]
    \href{https://www.linkedin.com/in/sushant-paudel-656767342/}{linkedin.com/in/sushant-paudel} \textbar\ 
    \href{https://github.com/sushantpaudel77}{github.com/sushantpaudel77}
\end{center}
\vspace{-2pt}

%-----------SUMMARY-----------
\section{Summary}
Backend Developer passionate about scalable microservices using \tech{Spring Boot}, \tech{Docker}, \tech{Kubernetes}, and \tech{AWS}. Experienced in REST APIs, secure authentication, and containerized deployment. Enthusiastic about cloud-native development and distributed systems.

%-----------EXPERIENCE-----------
\section{Professional Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Cloud Architecture Apprentice}{July 2025 -- Present}
    {Adex International}{On-site}
    \resumeItemListStart
      \resumeItem{Design secure, cost-optimized cloud architectures on \tech{AWS} following industry best practices}
      \resumeItem{Manage cloud infrastructure using \tech{EC2}, \tech{S3}, \tech{RDS}, \tech{VPC}, \tech{IAM}, and \tech{CloudFormation}}
      \resumeItem{Configure multi-tier network architectures with VPCs, subnets, NAT gateways, and security groups}
    \resumeItemListEnd
\resumeSubHeadingListEnd

\vspace{-2pt}

%-----------PROJECTS-----------
\section{Technical Projects}
\resumeSubHeadingListStart

\resumeProjectHeading
  {\textbf{LinkedIn Backend Microservices} | \tech{Kafka}, \tech{Docker}, \tech{Kubernetes}, \tech{Spring Boot}, \tech{Neo4j}}
  {https://github.com/sushantpaudel77/linkedin-backend-microservices}
  {GitHub}
\resumeItemListStart
  \resumeItem{Developed LinkedIn-inspired backend with 7+ microservices including API Gateway, User Management, Posts, and Notifications}
  \resumeItem{Implemented event-driven architecture using \tech{Apache Kafka} and deployed on \tech{Google Kubernetes Engine}}
\resumeItemListEnd

\resumeProjectHeading
  {\textbf{Banking Application Microservices} | \tech{MySQL}, \tech{Docker}, \tech{Spring Boot}, \tech{RabbitMQ}}
  {https://github.com/sushantpaudel77/Banking-application-microservices}
  {GitHub}
\resumeItemListStart
  \resumeItem{Built modular banking services for accounts, cards, and loans with centralized configuration and service discovery}
  \resumeItem{Implemented asynchronous messaging using \tech{RabbitMQ} and fault-tolerant architecture with circuit breakers}
\resumeItemListEnd

\resumeProjectHeading
  {\textbf{Property Rental Platform (AirBnB Clone)} | \tech{PostgreSQL}, \tech{Docker}, \tech{JWT}, \tech{Spring Boot}}
  {https://github.com/sushantpaudel77/myAirBnB-backend}
  {GitHub}
\resumeItemListStart
  \resumeItem{Developed property rental platform with user authentication, property listings, and booking system}
  \resumeItem{Implemented secure authentication using \tech{JWT} tokens and \tech{Spring Security} for authorization}
\resumeItemListEnd

\resumeSubHeadingListEnd
\vspace{-2pt}

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {Bachelor of Information Technology}{March 2021 -- October 2024}
    {Lincoln University}{Kathmandu, Nepal}
\resumeSubHeadingListEnd
\vspace{-2pt}

%-----------CERTIFICATIONS-----------
\section{Certifications}
\resumeSubHeadingListStart
  \resumeProjectHeading
    {\textbf{AWS Certified Solutions Architect – Associate (SAA-C03)}}
    {https://cp.certmetrics.com/amazon/en/public/verify/credential/c6b3ae1832c34cd19fe4387d75889b52}
    {Verify}
\resumeSubHeadingListEnd
\vspace{-2pt}

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, itemsep=1pt]
  \item \textbf{Programming Languages:} Java, Python, JavaScript
  \item \textbf{Frameworks \& Technologies:} Spring Boot, Spring Security, Spring Cloud, Spring Data JPA, NodeJs, ExpressJs
  \item \textbf{Databases:} PostgreSQL, MySQL, MongoDB
  \item \textbf{DevOps \& Containerization:} Docker, Kubernetes(Basics), Git, GitHub Actions, Linux 
  \item \textbf{Message Queues \& Streaming:} Apache Kafka(Basics), RabbitMQ(Basics)
  \item \textbf{Cloud Platforms:} Amazon Web Services (AWS)
  \item \textbf{Development Tools:} IntelliJ IDEA, VS Code, Vim, Maven, Chrome Dev Tools
  \item \textbf{Core Concepts:} OOP, Microservices Architecture, RESTful API Design
\end{itemize}

\end{document}
