
\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Sushant Sinha} \\ \vspace{1pt}
    407-3421 Rue Durocher, Montreal, Quebec, Canada, H2X 2C6 \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +1 579-421-5791 ~ \href{mailto:mail.mcgill.ca}{\raisebox{-0.2\height}\faEnvelope\  \underline{sushant.sinha@mail.mcgill.ca}}  ~ 
    \href{https://linkedin.com/in//}{\raisebox{-0.2\height}\faLinkedin\ \underline{linkedin.com/in/sushant-sinha-1b30ab1bb/}}  ~
   % \href{https://github.com/}{\raisebox{-0.2\height}\faGithub\ \underline{github.com/username}}
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {McGill University}{Sep. 2022 -- Current}
      {Masters in Materials Engineering, CGPA: 3.87/4.0}{Montreal, Quebec}
  \resumeSubHeadingListEnd
  \resumeSubHeadingListStart
    \resumeSubheading
      {BIT Sindri}{Aug 2016 -- Oct 2020}
      {Bachelor of Technology in Metallurgical Engineering, CGPA: 8.27/10.0 }{Dhanbad, India}
  \resumeSubHeadingListEnd

    %------RELEVANT COURSEWORK-------
\section{Relevant Coursework}
    %\resumeSubHeadingListStart
        \begin{multicols}{2}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Quantum Materials (Density Functional Theory)
                \item Machine Learning for Engineers
                \item Physics of Metals
                \item Fundamentals of Programming Language
                \item Numerical Analysis and Programming
                \item Mathematics - I to IV
                \item Physics-I (Classical) \& II (Modern)
                \item Probability and Statistics
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------Research EXPERIENCE-----------
\section{Research Experience}
  \resumeSubHeadingListStart

   \resumeSubheading
      {McGill University}{Sep 2022 -- Current}
      {M.Sc. Research; Supervisor: Prof. Stephen Yue, Co-supervisor: Prof. Narges Armanfard }{Montreal, Quebec}
      \resumeItemListStart
        \resumeItem{Developed Deep Neural Networks to predict mechanical properties of Hot Rolled microalloyed steels. Used ExplainableAI techniques like SHAP to explain the models and further validated them with mean flow stress analysis.}
        \resumeItem{\textbf Multi-objective optimization using an elitist approach for alloy design to tackle the strength-ductility trade-off in microalloyed steels. Used low-dimensional embedding and unsupervised clustering techniques to screen Pareto optimal solutions.}       
        
        \resumeItem{\textbf Ongoing Work: Uncertainty quantification in predictive modelling of mechanical properties and thus a strategy to reduce manual sampling of products for quality control.}
        
      \resumeItemListEnd

    \resumeSubheading
      {BIT Sindri}{Oct 2019 -- Feb 2020}
      {B.Tech Project; Supervisor: Prof. Babul Das}{Dhanbad, India}
      \resumeItemListStart
        \resumeItem{Performed Tungsten Inert Gas Welding on commercial grade Aluminum 5083 alloy with S-AlMg5 as filler material. }
        \resumeItem{Studied the grain structure using an optical microscope and corrosive behavior using Nitric Acid Mass Loss Test (NAMLT). \textit{[Project could not be completed because of COVID-19]}} 
    
      \resumeItemListEnd

    \resumeSubheading
      {Institut de recherche sur l'hydrogène, UQTR}{June 2019 -- Sept 2019}
      {MITACS Globalink Research Intern; Supervisor: Prof. Jacques Huot}{Trois-Rivières, Quebec, Canada}
      \resumeItemListStart
    \resumeItem{Synthesized and studied the microstructure and hydrogenation Properties of arc-melted Ti(x)Zr(1-x)Fe(y)Cr(2-y) laves phase alloy systems.}
    \resumeItem{Examined the alloys using XRD, SEM, and EDX experiments along with a homemade Sievert's apparatus.}
    \resumeItem{Identified and successfully resolved a critical pressure measurement-related malfunction within the homemade Sievert's apparatus.}
    \resumeItemListEnd


  \resumeSubheading
  {National Metallurgical Laboratory (CSIR-NML)}{June 2018 -- August 2018}
  {Summer Research Intern; Supervisor: Dr. Jay Chakraborty}{Jamshedpur, Jharkhand, India}
  \resumeItemListStart
\resumeItem{Synthesized and studied the structure and magnetic properties of Cryo-milled Fe-Powder.}
\resumeItem{Examined the Fe- Nanopowder using XRD, SEM, PAS, and SQUID experiments.}
\resumeItem{Analyzed X-ray line broadening using profile fitting assuming the dislocation model of strain anisotropy.} 
  \resumeItemListEnd

  
\resumeSubHeadingListEnd 
\vspace{-16pt}
%---Industrial Experience---
\section{Industrial Experience}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Jindal Stainless Limited, Jajpur}{Jan 2021 -- August 2022}
      {Associate Manager; Supervisor: Mr. Deepak Agrawal}{Jajpur, Orrisa, India}
      \resumeItemListStart
        \resumeItem{Started as a Process Engineer in the Hot Rolling Mill, within six months, advanced to Lead Process Control in the Cold Rolling Mill, and then progressed to Technical Advisor for the Unit Head.}
        \resumeItem{Developed statistical tools/methodology to track process parameters deviation for processes in both Hot and Cold Rolling of Stainless Steel.} 
        \resumeItem{Studied surface defects in stainless steel surfaces especially due to oxidation scales leading to substantial reduction of Rolled-in-Scale defects in flat products.}

      \resumeItemListEnd
\resumeSubHeadingListEnd 
\vspace{-16pt}

 %------Teaching Experience-----------
 
\section{Teaching Experience}
  \resumeSubHeadingListStart

   \resumeSubheading
      {McGill University}  {Nov 2023}
      {Guest Lecturer, Hot Deformation of Materials (MIME 563)}{Montreal, Quebec}
      \resumeItemListStart
        \resumeItem{Application of Machine Learning in Materials Science, General understanding of an ML model and its explainability.}
        \resumeItem{ML-based models to predict Roll force, Mechanical Property, etc. in Hot Rolling of Steel for optimal process design.}        
      \resumeItemListEnd

  \resumeSubheading
      {McGill University}{Sep 2023 -- Dec 2023}
      {Teaching Assistant, Phase Transformation (MIME 360)}{Montreal, Quebec}
      \resumeItemListStart
        \resumeItem{Guided student groups to design experiments to study and analyze the effect of heat treatment on the properties of an everyday metal object (e.g. Knife, Spoon, Rope Cleat) of their choice.}
        \resumeItem{Trained students on various equipment like Polishing and grinding, Microscopy, Muffle Furnace, Rockwell Hardness, etc.} 
        
      \resumeItemListEnd
\resumeSubHeadingListEnd 
\vspace{-16pt}

%------Publications\Presentations-------

\section{Publications/Presentations}
\begin{itemize}[leftmargin=0.15in]
 % \small

   \item[\text] \textbf{Sinha, S.}, Guye, D., Ma, X., Rehman, K., Yue, S. and Armanfard, N.\textit{, 2024. Neural network prediction of the effect of thermomechanical controlled processing on mechanical properties.} Machine Learning with Applications, p.100531, DOI: https://doi.org/10.1016/j.mlwa.2024.100531

    \item[\text] Chakraborty, J., Sanket, K., Srikar, S.,Nambissan, P.M.G., Chandan A.K., Jena P.S.M., \textbf{Sinha, S.}, Dwarapudi, S. \textit{,  Lattice distortion and dislocation microstructure in nanocrystalline Fe: X-ray diffraction and positron annihilation lifetime spectroscopy study.} \textbf{[Under Peer Review]}

    \item[\text] \textbf{Sinha, S.}, Ma, X., Rehman, K., Yue, S. and Armanfard, N., \textit{Data-driven multiobjective optimization for strength-ductility trade-off in microalloyed steels.} \textbf{[Under preparation]}

    \item[\text] Sinodinos, D., \textbf{Sinha, S.}, NikPour, B.,  Wei, J., Ma, X., Rehman, K., Yue, S. and Armanfard, N., \textit{Multitask learning for process control in thermomechanical processing.} \textbf{[Under preparation]}
        
  \item[\text] \textbf{S.Sinha}, D.Guye, X.Ma, K.Rehman, S.Yue, N.Armanfard; \textit{Machine Learning-based Prediction of the Mechanical Properties of Microalloyed Steel Subjected to Thermomechanical Controlled Processing}; Materials Science and Technology 2023 Technical Meeting and Exhibition, Oct 01st- 04th, Columbus, Ohio, USA.



\end{itemize}
 \vspace{-16pt}

 %------Other Projects-----------
 
\section{Grad Course Projects}
  \resumeSubHeadingListStart

   \resumeSubheading
      {Machine Learning for Engineers}  {Winter 2023}
      {Instructor: Prof. Narges Armanfard}{}
      \resumeItemListStart
        \resumeItem{Utilized logistic regression for binary classification in benchmark datasets (Kidney Disease and White Wine Quality), optimizing model performance through hyperparameter tuning, cross-validation, and feature engineering.}
        \resumeItem{Explored diverse text classification methods, including a custom Bernoulli Naive Bayes model, and Multilayer Perceptron, to analyze comments from various subreddits. Improved accuracy through feature selection techniques like $\chi^2$ and $f\_classif$.}
        \resumeItem{Explored deep learning models like VGG16, AlexNet, and ResNet in PyTorch for image classification. Analyzed mixed fashion articles and Japanese integers images across 10 labels, implementing transfer learning and ensemble ResNet models to enhance accuracy.}
      \resumeItemListEnd

  \resumeSubheading
      {Quantum Materials}{Fall 2023}
      {Instructor: Prof. Kirk Bevan}{}
      \resumeItemListStart
        \resumeItem{Wrote several MATLAB codes from scratch as part of assignment projects covering the 'nuts and bolts" of density functional theory including the Hartree method, self-consistent field, local density approximation, Pseudopotentials, etc.}
        \resumeItem{For Ex: Used pseudopotential and sp-basis to solve for the electronic structure of polyyne and further computed the neutral atom potential and band structure.}        
      \resumeItemListEnd
\resumeSubHeadingListEnd 
\vspace{-16pt}

    %\resumeSubHeadingListEnd
%-----------SKILLS-----------
\section{Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
  %  \small
    {\item{
     \textbf{Languages/Tools}{: Python, PyTorch, SHAP, LaTeX, MATLAB, Origin, EndNote} \\
     \textbf{Laboratory}{: SEM(SU 3500), XRD(Brukers D8 Focus), STM} \\
    }}
 \end{itemize}
 \vspace{-16pt}

%------CERTIFICATE COURSEWORK-------

\section{Other Certification Courses}
 \begin{itemize}[leftmargin=0.15in, label={}]
    %\small
    {\item{
     \text{Chaos in Dynamical Systems (IIT Bhubaneshwar)} \\
     \text{Surface Engineering of Nanomaterials (NPTEL, IIT Roorkee)} \\
     \text{Structural Analysis of Nanomaterials (NPTEL, IIT Roorkee)}
    }}
 \end{itemize}
 \vspace{-16pt}

 %------Awards/Achivements-------

\section{Awards}
 \begin{itemize}[leftmargin=0.15in, label={}]
    %\small
    {\item{
     \text{McGill Engineering Graduate Excellence Fellowship (2023)}  \\
     \text{McGill Mining and Materials Engineering Graduate Excellence Fellowship (2022)} \\
     \text{MITACS Graduate Research Fellowship (2022) }\\
     \text{Best Graduate Engineer Trainee in the batch of 25 handpicked graduates across India (2022). }\\
     \text{BIT Sindri 1970 Alumni Merit cum Means Scholarship (2019-20)}\\
     \text{MITACS Globalink Research Fellowship (2019) }\\
     \text{Best Presentation and Best Poster at Dhatvika - Metallurgical Seminar of BIT Sindri (2017 \& 2018)}
    }}
 \end{itemize}
 \vspace{-16pt}
%-----------INVOLVEMENT---------------
\section{Community Involvement}
    \resumeSubHeadingListStart
        \resumeSubheading{New Student Mentorship Program}{Sept 2023 -- Present}{Mentor}{McGill University}
        \resumeSubheading{BIT Sindri Research and Development Effort}{Feb 2018 -- May 2020}{Student Representative}{BIT Sindri}
     \resumeSubheading{Workshop on Nanoscience and Surface Characterization (1 Week)}{Feb 2020}{Student Team Member}{BIT Sindri}
        \resumeSubheading{TEDxBIT Sindri 2019 }{Nov 2019}{Speaker Acquisition and Hospitality Head}{BIT Sindri}
        \resumeSubheading{Model Club, Official Technical Club of BIT Sindri}{Sept 2018 -- April 2019}{Technical Head}{BIT Sindri}
        \resumeSubheading{The Metallurgical Society of BIT Sindri}{March 2018 -- April 2019}{Secretary}{BIT Sindri}
        \resumeSubheading{National Conference on Special Steels \& Nanomaterials(STSSN-18)}{March 2018 }{Conference Secretariat Member \& Resource Mobilization Member}{BIT Sindri}
           
        
    \resumeSubHeadingListEnd

\section{References}
    \resumeSubHeadingListStart

\item \textbf{Dr. Stephen Yue}\\
    Distinguished James McGill Professor of Materials Engineering at the
    McGill University\\
    Email: \texttt{steve.yue@mcgill.ca}

%    \item \textbf{Dr. Narges Armanfard}\\
 %   Assistant Professor of Electrical and Computer Engineering at the McGill University\\
 %   Email: \texttt{narges.armanfard@mcgill.ca}

\item \textbf{Dr. Jay Chakraborty}\\
    Senior Principal Scientist at the MTE-Division, National Metallurgical Laboratory (CSIR-NML), Jamshedpur, India\\
    Email: \texttt{jay@nmlindia.org}
    
\item \textbf{Dr. Anil Kumar Rajak}\\
    Associate Professor of Metallurgical Engineering at BIT Sindri\\
    Email: \texttt{akrajak.met@bitsindri.ac.in}

    \item \textbf{Mr. Deepak Agrawal}\\
    Unit Head and Senior Vice President at Jindal Stainless Limited, Jajpur, India \\
    Email: \texttt{deepak.agrawal@jindalstainless.in}
\end{document}
# profile
