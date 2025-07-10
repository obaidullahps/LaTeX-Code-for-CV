# LaTeX-Code-for-CV

\documentclass[letterpaper,11pt]{article}
\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref} % Enable breaking URLs
\usepackage{fancyhdr}
\usepackage{tabularx}
\usepackage{lmodern}
\usepackage{multicol}
\usepackage{ragged2e}
\usepackage[margin=0.8in, top=0.8in, bottom=0.7in]{geometry}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.0 in}
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}
\renewcommand{\baselinestretch}{0.8}

\urlstyle{same}
\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Enable line breaking in URLs
\usepackage{xurl}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-4pt}]

% Custom commands
\newcommand{\resumeSubheading}[4]{
  \vspace{-1pt}\item
    \begin{tabularx}{\textwidth}[t]{X@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabularx}\vspace{-7pt}
}

\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{document}

%----------HEADING----------
\begin{center}
    \textbf{\Huge \scshape Md. Obaidullah} \\ \vspace{1pt}
    +1-601-307-9751 $|$ \href{mailto:buobaidullah@gmail.com}{buobaidullah@gmail.com} $|$ 
    \href{https://www.linkedin.com/in/md-obaidullah-14322b154/}{LinkedIn} $|$
    \href{https://mdobaidullah.com/}{Website} \\
    

\end{center}

%-----------EDUCATION-----------
\section{Education}
\begin{itemize}[left=0pt,label={},topsep=1pt,partopsep=0pt,itemsep=2pt,parsep=0pt]

  \resumeSubheading
    {MA in Political Science} {2024--2026}
    {University of Southern Mississippi (USM)}{USA}
    \resumeItemListStart
      \resumeItem{Thesis: \textit{Authoritarian Foreign Policy}}
    \resumeItemListEnd

  \resumeSubheading
    {MSS in Public Administration}{2020--2021}
    {University of Barishal}{Bangladesh}

  \resumeSubheading
    {BSS in Public Administration}{2017--2020}
    {University of Barishal}{Bangladesh}
    \resumeItemListStart
      \resumeItem{Monograph: \textit{Determinants of Citizen Satisfaction: A Quantitative Analysis of Local Governance in Barishal Sadar, Bangladesh}}
    \resumeItemListEnd

\end{itemize}


%----------- SKILLS-----------
\section{Skills}
\begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{Technical Skills}{: SPSS, R, NVivo, Mendeley, Zotero} \\
     \textbf{Writing Tools}{: MS Office, Google Workspace, LaTeX } \\
     \textbf{Languages}{: Bengali (Native), English (Fluent)} 
    }}
\end{itemize}


%-----------RESEARCH INTERESTS-----------
\section{Research Interests}
\vspace{-1\baselineskip}
\begin{multicols}{2}
\noindent\textbf{Substantive}
\vspace{-0.1\baselineskip}
\begin{itemize}[noitemsep, topsep=0pt, partopsep=0pt, parsep=0pt, leftmargin=*]
  \item International Relations
  \item Great Power Competition
  \item Middle Powers
  \item Foreign Policy
  \item Asian Politics
  \item Migration and Refugee Studies
\end{itemize}

\columnbreak

\noindent\textbf{Methods}
\vspace{-0.1\baselineskip}
\begin{itemize}[noitemsep, topsep=0pt, partopsep=0pt, parsep=0pt, leftmargin=*]
  \item Mixed Methods
  \item Quantitative Text Analysis
  \item Regression Analysis
  \item NLP/ML
  \item Content Analysis
  \item Thematic Analysis
\end{itemize}
\end{multicols}

%-----------WORK EXPERIENCE-----------
\section{Work Experience}

%-----------RESEARCH EXPERIENCE-----------
\subsection*{Research Experience:}
\begin{itemize}[left=0pt,label={},topsep=1pt,partopsep=0pt,itemsep=2pt,parsep=0pt]

\resumeSubheading
  {Editorial Board Member}{2025--Present}
  {Canadian Journal of Business, Economics and Health Management (CJBEHM)}{Canada}
  \resumeItemListStart
    \resumeItem{Reviewed and provided detailed feedback on submitted manuscripts related to political economy and global health management.}
    \resumeItem{Advised on journal policy development and strategic direction to enhance international visibility and impact.}
    \resumeItem{Collaborated with fellow board members to identify emerging trends and potential special issue topics.}
  \resumeItemListEnd

\resumeSubheading
  {Editorial Board Member}{2024--Present}
  {Journal of Emerging Global Health}{Dhaka, Bangladesh}
  \resumeItemListStart
    \resumeItem{Led peer review coordination and oversaw quality assurance for submitted articles in the global health domain.}
    \resumeItem{Contributed to expanding the journal’s indexing and outreach through academic networking and conference representation.}
  \resumeItemListEnd

\resumeSubheading
  {Commissioning Editor}{2024--Present}
  {E-International Relations}{United Kingdom}
  \resumeItemListStart
    \resumeItem{Curated and edited scholarly pieces on global international relations topics.}
    \resumeItem{Ensured thematic coherence and academic quality across commissioned content.}
  \resumeItemListEnd

\resumeSubheading
  {Research Assistant}{2022--2023}
  {BRAC James P Grant School of Public Health}{Dhaka, Bangladesh}
  \resumeItemListStart
    \resumeItem{Transcribed and translated 25 interviews and focus group discussions (approx. 1,000 minutes).}
    \resumeItem{Contributed to five research projects, including the ARISE initiative on informal settlements.}
    \resumeItem{Assisted with thematic coding and qualitative data analysis.}
  \resumeItemListEnd

\resumeSubheading
  {Research Assistant}{2021--2022}
  {Centre for Advanced Research}{Dhaka, Bangladesh}
  \resumeItemListStart
    \resumeItem{Managed four research projects on undocumented migration.}
    \resumeItem{Conducted 15 in-depth interviews and 7 structured surveys.}
    \resumeItem{Performed qualitative analysis using NVivo and statistical analysis using SPSS.}
  \resumeItemListEnd

\end{itemize}

%-----------TEACHING EXPERIENCE-----------
\subsection*{Teaching Experience:}
\begin{itemize}[left=0pt,label={},topsep=1pt,partopsep=0pt,itemsep=2pt,parsep=0pt]

\resumeSubheading
  {Graduate Teaching Assistant to Dr. Bob Press}{Fall 2024 -- Spring 2025}
  {School of Social Science \& Global Studies, University of Southern Mississippi}{USA}
  \resumeItemListStart
    \resumeItem{Led discussion sessions and graded assignments for undergraduate courses: \textit{PS 101 American Government}, \textit{PS 306 Race \& Ethnic Politics}, and \textit{PS 453 Politics \& Protests}.}
    \resumeItem{Held office hours and provided mentorship on student research projects.}
  \resumeItemListEnd

\resumeSubheading
  {Lecturer}{Spring 2024}
  {Department of Development Studies, Daffodil International University}{Dhaka, Bangladesh}
  \resumeItemListStart
    \resumeItem{Taught "Introduction to Bangladesh Studies" to 300 students; developed curriculum and assessment materials.}
  \resumeItemListEnd

\end{itemize}

%-----------PUBLICATIONS-----------
\section{Publications}

\textbf{Peer-Reviewed Articles:}
\begin{itemize}

\item \justifying Sohel, M. S., Sifullah, M. K., Zaman, N. T., Hossain, B., \textbf{Obaidullah, M.} (2025). Beyond borders: Mapping out the difficulties, stress, and coping strategies in transnational irregular (illegal) labor migration from Bangladesh. \textit{International Journal of Community Well-Being}. \href{https://doi.org/10.1007/s42413-025-00243-6}{DOI link}. \textbf{SCOPUS Q2, SCImago, IF= 1.8}

\item \justifying \textbf{Obaidullah, M.}, Howlader, M. R. (2025). Assessing geopolitical and socio-economic consequences of India-Bangladesh water disputes. \textit{Discover Global Society}, 3(1). \href{https://doi.org/10.1007/s44282-025-00137-0}{DOI link}. \textbf{SCOPUS, DOAJ}

\item \justifying Sifullah, M. K., Sohel, M. S., Jamil, S., Ahmad, B., Hossain, M. A., \textbf{Obaidullah, M.}, Zaman, N. T., Faruk, O., Islam, M. T., \& Ali, N. (2025). WASH service accessibility and satisfaction among street informal workers in Dhaka City: A cross-sectional study. \textit{Discover Social Science and Health}, 5(45). \href{https://doi.org/10.1007/s44155-025-00187-4}{DOI link}. \textbf{SCOPUS, Web of Science, IF= 1.3}

\item \justifying \textbf{Obaidullah, M.}, Hossain, M., Raihan, M. S., Hossen, M. S. (2024). From humanitarian crisis to burden: understanding the Rohingya refugee crisis in Bangladesh. \textit{SN Social Sciences}, 4(8). \href{https://doi.org/10.1007/s43545-024-00942-5}{DOI link}. \textbf{SCOPUS, IF= 1.3}

\item \justifying Sohel, M. S., Sifullah, M. K., Hossain, B., Sarker, M. F. H., Zaman, N. T., \textbf{Obaidullah, M.} (2024). Exploring risky health behaviors and vulnerability to sexually transmitted diseases among transnational undocumented labor migrants from Bangladesh: a qualitative study. \textit{BMC Public Health}, 24(1), 1261. \href{https://doi.org/10.1186/s12889-024-18696-3}{DOI link}. \textbf{SCOPUS Q1, SCImago, PUBMED, SCIE, IF= 4.2}

\item \justifying Sohel, M. S., Alam, S., Rahman, M. M., \textbf{Obaidullah, M.}, Towhidul, A. a. S. M., Hossain, M. B., Hossain, M. A. (2024). Exploring the multifaceted vulnerabilities of female street child labor in the capital city of Bangladesh. \textit{Heliyon}, e37302. \href{https://doi.org/10.1016/j.heliyon.2024.e37302}{DOI link}. \textbf{SCOPUS Q1, SCImago, Web of Science, IF=3.6}

\item \justifying Sohel, M. S., Jamil, S., \textbf{Obaidullah, M.}, Hossain, B., Ali, H. M., Hossen, M. S., Uddin, M. S., Ahsan, T., Eva, N. F. (2024). Healthcare challenges in disaster-prone riverine islands: A study of Sirajgonj, Bangladesh. \textit{International Journal of Community Well-Being}. \href{https://doi.org/10.1007/s42413-024-00223-2}{DOI link}. \textbf{SCOPUS Q2, SCImago, IF= 1.8}

\item \justifying Sarker, M. F. H., Ahmed, S. F., Kawser, U., Hossen, M. S., \textbf{Obaidullah, M.}, Khan, S., Sifullah, M. K., Sohel, M. S. (2024). Is e-business breaking down barriers for Bangladesh’s young female entrepreneurs during the COVID-19 pandemic? A qualitative study. \textit{SN Social Sciences}, 4(6). \href{https://doi.org/10.1007/s43545-024-00911-y}{DOI link}. \textbf{SCOPUS, IF= 1.3}

\item \justifying Begum Mamy, M. M., \textbf{Obaidullah, M.}, Zaman, N. T., Saifullah, M. K., Sohel, M. S., Hossen, M., Horaira, G. A. (2024). Navigating vulnerabilities: The untold story of informal households in Dhaka, Bangladesh during the COVID-19 pandemic. \textit{New Zealand Journal of Asian Studies}, 26(2), 75–98. \href{https://www.researchgate.net/publication/387871977_Navigating_Vulnerabilities_The_Untold_Story_of_Informal_Households_in_Dhaka_Bangladesh_During_the_COVID-19_Pandemic}{DOI link}. \textbf{SCOPUS}

\item \justifying Jamil, S., \textbf{Obaidullah, M.}, Alam, M. (2023). Unusual increase of cesarean section delivery in Bangladesh: correspondence. \textit{Annals of Medicine and Surgery}, 85(5), 2242. \href{https://doi.org/10.1097/MS9.0000000000000488}{DOI link}. \textbf{SCOPUS, PUBMED, IF= 1.7}

\item \justifying \textbf{Obaidullah, M.}, Jamil, S., Mohammad A. H., Akhter, A. (2023). Burning up: How heatwaves pose a threat to public health. \textit{International Journal of Surgery – Short Report}, 8(3), e0067. \href{https://doi.org/10.1097/SR9.0000000000000068}{DOI link}. \textbf{SCOPUS, PUBMED, IF= 1.7}

\item \justifying Zaman, N. T., Sohel, M. S., \textbf{Obaidullah, M.}, Hossen, M. S., Rahman, M. T., Sifullah, M. K., Sarker, M. F. H. (2023). Factors shaping Bangladeshi students’ migration decision using push–pull theory: A focus group study. \textit{SN Social Sciences}, 4(1). \href{https://doi.org/10.1007/s43545-023-00797-2}{DOI link}. \textbf{SCOPUS, IF= 1.3}


    \end{itemize}
    
\textbf{Book Chapters:}
\begin{itemize}
    \item \justifying \textbf{Obaidullah, M.}, Hossain, M. (2025). China’s Soft Power Strategy in the Middle East and East Asia: A Comparative Analysis. In Ullah, A.A. (Ed.), \textit{Handbook of Migration, International Relations and Security in Asia.} Springer, Singapore. \href{https://doi.org/10.1007/978-981-99-8001-7_17-1}{DOI link}.

    \item \justifying \textbf{Obaidullah, M.}, Begum, R. (2025). The Rohingya Crisis and Its Effect on Bangladesh-Myanmar Bilateral Relations: A Historical Analysis. In Ullah, A.A. (Ed.), \textit{Handbook of Migration, International Relations and Security in Asia.} Springer, Singapore. \href{https://doi.org/10.1007/978-981-99-8001-7_14-1}{DOI link}.

    \item \justifying \textbf{Obaidullah, M.}, Hossain, M. (2024). Major Powers’ Approaches to the Rohingya Crisis and Their Impact on Bangladesh. In Ullah, A.A. (Ed.), \textit{Handbook of Migration, International Relations and Security in Asia.} Springer, Singapore. \href{https://doi.org/10.1007/978-981-99-8001-7_97-1}{DOI link}.

    \item \justifying \textbf{Obaidullah, M.}, Raihan, M. S. (2024). Soft Power Competition: A Comparative Analysis of China and the US in South Asia. In Zreik, M. (Ed.), \textit{Soft Power and Diplomatic Strategies in Asia and the Middle East.} IGI Global. \href{https://doi.org/10.4018/979-8-3693-2444-8.ch013}{DOI link}. \textbf{SCOPUS}

\item \justifying Sohel, M. S., Hossain, M. A., Sarker, M. F. H., Sifullah, M. K., \textbf{Obaidullah, M.}, Ullah, A. A. (2025). Bangladeshi Undocumented Migration Crisis in Europe: Implications of Security, Human Rights, and Policy. In: Ullah, A. A. (eds) \textit{Handbook of Migration, International Relations and Security in Asia}. Springer, Singapore. \href{https://doi.org/10.1007/978-981-99-8001-7_42-1}{DOI link}.


    
\end{itemize}


\textbf{Book Reviews:}
\begin{itemize}
    \item \justifying Hossain, M., \textbf{Obaidullah, M.} (2025). \textit{Power of Bonding and Non-Western Soft Power Strategy in Iran: Comparing China and India’s Engagement:} by Md. Nazmul Islam, Cham, Switzerland, Palgrave Macmillan, 2023, x+356 pp., \pounds129.99 (hardback), ISBN: 3031198662, 9783031198663. \textit{Contemporary South Asia}, 33(1), 145–146. \href{https://doi.org/10.1080/09584935.2025.2461404}{DOI link}.

    \item \justifying Hossain, M., \textbf{Obaidullah, M.} (2024). \textit{We had the Watches. They had the Time: A Witness Account of the War in Afghanistan:} edited by Carol Burke, Palgrave Macmillan Cham, 2024, 223 pp., \pounds109.99 (hardback), ISBN: 978-3-031-41303-2. \textit{Small Wars \& Insurgencies}, 36(1), 241–243. \href{https://doi.org/10.1080/09592318.2024.2410607}{DOI link}.

    \item \justifying \textbf{Obaidullah, M.}, Hossain, M. (2023). Book review: Kudret Bulbul, Md. Nazmul Islam and Md. Sajid Khan (Eds.), \textit{Rohingya Refugee Crisis in Myanmar: Ethnic Conflict and Resolution}. \textit{Society and Culture in South Asia}, 10(1), 142–145. \href{https://doi.org/10.1177/23938617231211430}{DOI link}.
\end{itemize}

%-----------CONFERENCE PRESENTATIONS-----------
\section{Conference Proceedings}
\begin{itemize}[left=0pt,label={},topsep=1pt,partopsep=0pt,itemsep=2pt,parsep=0pt]

  \resumeSubheading
    {The American Touch: Evaluating the Reach of U.S. Soft Power in India}{Apr 2025}
    {Midwest Political Science Association (MPSA) Annual Conference}{Chicago, IL, USA}

  \resumeSubheading
    {Bridging Worlds: Islamic Perspectives on International Relations and Comparative Insights with Western Theories}{Apr 2025}
    {Midwest Political Science Association (MPSA) Annual Conference}{Chicago, IL, USA}

\end{itemize}

%-----------NEWSPAPER / OP-EDS-----------

\section{Newspaper Publications / Opinion Editorials (Selected)}
\begin{itemize}
    \item \justifying \textbf{Obaidullah, M.} (2025). “Why Bangladesh should join ASEAN – and what stands in the way.” \textit{The Diplomat}. \href{https://thediplomat.com/2025/04/why-bangladesh-should-join-asean-and-what-stands-in-the-way/}{Link}.

    \item \justifying Mahmud, K. U., \& \textbf{Obaidullah, M.} (2025). “Will Trump 2.0 end the liberal international order?” \textit{The Daily Star}. \href{https://www.thedailystar.net/opinion/views/news/will-trump-20-end-the-liberal-international-order-3859616}{Link}.

    \item \justifying \textbf{Obaidullah, M.}, \& Hossen, M. S. (2025). “Where does the national political future lie?” \textit{New Age}. \href{https://www.newagebd.net/post/opinion/260324/where-does-the-national-political-future-lie}{Link}.

    \item \justifying \textbf{Obaidullah, M.} (2025). “A new chapter in Dhaka-Beijing ties? Why Chief Adviser Dr. Muhammad Yunus is visiting China.” \textit{The Diplomat}. \href{https://thediplomat.com/2025/03/a-new-chapter-in-dhaka-beijing-ties-why-chief-adviser-dr-muhammad-yunus-is-visiting-china/}{Link}.

    \item \justifying \textbf{Obaidullah, M.}, \& Hossen, M. S. (2024). “Border of blood.” \textit{New Age}. \href{https://www.newagebd.net/post/opinion/254138/border-of-blood}{Link}.
\end{itemize}

%-----------SERVICE-----------
\section{Service}

Reviewer for the following journals:

\vspace{-1\baselineskip}  % Adjust if necessary to tighten spacing before the list
\begin{multicols}{2}
\begin{itemize}[noitemsep, topsep=0pt, partopsep=0pt, parsep=0pt, leftmargin=*]
  \item \textit{International Journal of Community Well-Being}
  \item \textit{PLOS ONE}
  \item \textit{International Journal of Sociology and Social Policy}
  \item \textit{Southeast Asia: A Multidisciplinary Journal}
  
\end{itemize}
\end{multicols}



%-----------TRAINING EXPERIENCE-----------
\section{Training Experience, Workshops, and Certifications}
\resumeSubHeadingListStart
    \resumeSubheading
      {Data Analytics with R for Data Science}{2024}
      {Statistical Research Consultants in Bangladesh}{Dhaka, Bangladesh}
    \resumeSubheading
      {Qualitative Data Analysis Using NVivo}{2021}
      {Centre for Advanced Research}{Dhaka, Bangladesh}
\resumeSubHeadingListEnd

%-----------AWARDS & FUNDING-----------
\section{Awards \& Funding}
\resumeSubHeadingListStart

\resumeSubheading
  {Outstanding Graduate Student in Political Science}{2024--2025}
  {School of Social Science and Global Studies, USM}{USA}
  \resumeItemListStart
  \resumeItem{Awarded for achieving highest GPA in Fall 24 semester}
    \resumeItemListEnd

\resumeSubheading
  {CZM Genius Scholarship Recipient}{2018}
  {Center for Zakat Management (CZM)}{Bangladesh}
  \resumeItemListStart
  \resumeItem{Awarded \$600 in merit and need based funding; selected among the 10\% of applicants.}
    \resumeItemListEnd

\resumeSubHeadingListEnd

\end{document}
