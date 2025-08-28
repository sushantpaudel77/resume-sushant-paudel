\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym,fullpage,titlesec,marvosym,color,enumitem,hyperref,fancyhdr,tabularx,xcolor,microtype,babel,geometry}

\geometry{margin=0.35in} % slightly tighter margins

% Page style
\pagestyle{fancy}
\fancyhf{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\urlstyle{same}
\raggedbottom
\raggedright

\setlength{\tabcolsep}{4pt}

% Increase font weights throughout
\usepackage{lmodern}
\usepackage[T1]{fontenc}

% Section formatting with bolder fonts
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\normalsize\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-4pt}]

% Commands with increased weight
\newcommand{\tech}[1]{\textbf{\fontseries{b}\selectfont #1}}
\newcommand{\resumeItem}[1]{\item \fontseries{m}\selectfont #1}
\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabular*}{\textwidth}{@{\extracolsep{\fill}}l r}
      \textbf{\fontseries{b}\selectfont #1} & \small #2 \\
      \textit{\small #3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-3pt}
}
\newcommand{\resumeProjectHeading}[3]{
    \item
    \begin{tabularx}{\textwidth}{X r}
      {\small \textbf{\fontseries{b}\selectfont #1}} & {\small \href{#2}{\textbf{\fontseries{b}\selectfont \underline{#3}}}} \\
    \end{tabularx}\vspace{-3pt}
}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.05in, label={}, itemsep=0pt]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}\vspace{-4pt}}

% No bullets, just clean indentation
\newcommand{\resumeItemListStart}{\begin{itemize}[leftmargin=0.15in, label={}, itemsep=1pt]}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-3pt}}

%----------DOCUMENT----------
\begin{document}

%----------HEADING----------
\begin{center}
    {\LARGE \textbf{\fontseries{b}\selectfont SUSHANT PAUDEL}} \\[2pt]
    {\large \textbf{Backend Developer}} \\[2pt]
    \normalsize 
    \textbf{Email:} \href{mailto:sushantpaudel77@gmail.com}{sushantpaudel77@gmail.com} \textbar\ 
    \textbf{Phone:} 9844881513 \\[1pt]
    \textbf{LinkedIn:} \href{https://www.linkedin.com/in/sushant-paudel-656767342/}{sushant-paudel} \textbar\ 
    \textbf{GitHub:} \href{https://github.com/sushantpaudel77}{sushantpaudel77}
\end{center}

%-----------SUMMARY-----------
\section{Summary}
\small \textbf{\fontseries{m}\selectfont Backend Developer passionate about scalable microservices using \tech{Spring Boot}, \tech{Docker}, \tech{Kubernetes}, and \tech{AWS}. Experienced in REST APIs, secure authentication, and containerized deployment. Enthusiastic about cloud-native development and distributed systems.}

%-----------PROJECTS-----------
\section{Projects}
\resumeSubHeadingListStart

\resumeProjectHeading
  {\textbf{LinkedIn Backend Microservices} | \tech{Kafka}, \tech{Docker}, \tech{Kubernetes}, \tech{SpringBoot}, \tech{Neo4j}, \tech{Spring Cloud}, \tech{PostgreSQL}, \tech{JWT}, \tech{GCP}}
  {https://github.com/sushantpaudel77/linkedin-backend-microservices}
  {GitHub}
\resumeItemListStart
  \resumeItem{\small LinkedIn-inspired backend with 7+ microservices including API Gateway, User, Posts, and Notifications for comprehensive social networking functionality.}
  \resumeItem{\small Event-driven architecture using \tech{Kafka} for async communication, deployed on \tech{Kubernetes} cluster (GCP GKE).}
  \resumeItem{\small \tech{Neo4j} graph database for user connections; \tech{PostgreSQL} for transactional data with optimized queries.}
\resumeItemListEnd

\resumeProjectHeading
  {\textbf{Banking App Microservices} | \tech{MySQL}, \tech{Docker}, \tech{SpringBoot}, \tech{RabbitMQ}, \tech{Spring Cloud}, \tech{Swagger}}
  {https://github.com/sushantpaudel77/Banking-application-microservices}
  {GitHub}
\resumeItemListStart
  \resumeItem{\small Modular banking services for accounts, cards, loans with centralized config server and service discovery.}
  \resumeItem{\small Asynchronous communication using \tech{RabbitMQ}; automated CI/CD builds and API docs with \tech{Swagger}.}
  \resumeItem{\small Fault-tolerant architecture with circuit breakers and retry mechanisms for enhanced reliability.}
\resumeItemListEnd

\resumeProjectHeading
  {\textbf{AirBnB Backend Clone} | \tech{PostgreSQL}, \tech{Docker}, \tech{JWT}, \tech{SpringBoot}, \tech{Spring Security}}
  {https://github.com/sushantpaudel77/myAirBnB-backend}
  {GitHub}
\resumeItemListStart
  \resumeItem{\small Property rental platform with user authentication, property listings, booking system, and role-based access control.}
  \resumeItem{\small Secure endpoints using \tech{JWT} authentication and \tech{Spring Security} for authorization and user management.}
  \resumeItem{\small Optimized \tech{PostgreSQL} queries and efficient schema for concurrent booking requests and property searches.}
\resumeItemListEnd

\resumeSubHeadingListEnd

%-----------EXPERIENCE-----------
\section{Experience}
\resumeSubHeadingListStart
  \resumeSubheading
    {Cloud Architecture Apprentice}{July 2025 -- Present}
    {Adex International}{On-site}
    \resumeItemListStart
      \resumeItem{\small Designing secure, resilient, cost-optimized cloud architectures on \tech{AWS} following industry best practices.}
      \resumeItem{\small Working with \tech{EC2}, \tech{S3}, \tech{RDS}, \tech{VPC}, \tech{IAM}, \tech{CloudFormation} for infrastructure as code.}
      \resumeItem{\small Configured VPCs, subnets, NAT gateways, security groups for secured multi-tier network architectures.}
      \resumeItem{\small Developing cloud security, auto-scaling, cost optimization aligned with AWS SAA-C03 certification objectives.}
    \resumeItemListEnd
\resumeSubHeadingListEnd

%-----------EDUCATION-----------
\section{Education}
\resumeSubHeadingListStart
  \resumeSubheading
    {Bachelor of Information Technology}{March 2021 -- October 2024}
    {Lincoln University}{}
\resumeSubHeadingListEnd

%-----------TECHNICAL SKILLS-----------
\section{Technical Skills}
\begin{itemize}[leftmargin=0.15in, itemsep=1pt]
  \item \textbf{Programming Languages:} Java, Python, JavaScript
  \item \textbf{Frameworks \& Technologies:} Spring Boot, Spring Security, Spring Cloud, Spring Data JPA
  \item \textbf{Databases:} PostgreSQL, MySQL, MongoDB
  \item \textbf{DevOps \& Containerization:} Docker, Kubernetes(Basics), Git, GitHub Actions, Linux 
  \item \textbf{Message Queues \& Streaming:} Apache Kafka(Basics), RabbitMQ(Basics)
  \item \textbf{Cloud Platforms:} Amazon Web Services (AWS)
  \item \textbf{Development Tools:} IntelliJ IDEA, VS Code, Vim, Maven, Chrome Dev Tools
  \item \textbf{Core Concepts:} OOP, Microservices Architecture, RESTful API Design
\end{itemize}

\end{document}