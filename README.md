# shun.github.io
Shun Zhang's Home Page 


% Welcome to the simple Undergraduate Complexity Research CV-resume template!
% Please delete any sections that do not apply to your past experiences. We do not expect that applicants will have itmes for all of the sections included here. You can also rename or revise sections to best fit with your personal accomplishments.

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
\usepackage{multicol}
\input{glyphtounicode}

\usepackage{baskervillef}
\usepackage[T1]{fontenc}

\pagestyle{fancy}
\fancyhf{} 
\fancyfoot{}
\setlength{\footskip}{10pt}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

\addtolength{\oddsidemargin}{0.0in}
\addtolength{\evensidemargin}{0.0in}
\addtolength{\textwidth}{0.0in}
\addtolength{\topmargin}{0.2in}
\addtolength{\textheight}{0.0in}


\urlstyle{same}

%\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

\titleformat{\section}{
  \it\vspace{3pt}
}{}{0em}{}[\color{black}\titlerule\vspace{-5pt}]

\pdfgentounicode=1

\newcommand{\resumeItem}[1]{
  \item{
    {#1 \vspace{-4pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small #3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-10pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-3pt}}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-2pt}}



%----------------------------------------------------------------------------------------
%	PACKAGES
%----------------------------------------------------------------------------------------
\usepackage{url}
\usepackage{parskip} 	

%other packages for formatting
\RequirePackage{color}
\RequirePackage{graphicx}
\usepackage[usenames,dvipsnames]{xcolor}
\usepackage[scale=0.9]{geometry}

%tabularx environment
\usepackage{tabularx}

%for lists within experience section
\usepackage{enumitem}

% centered version of 'X' col. type
\newcolumntype{C}{>{\centering\arraybackslash}X} 

%to prevent spillover of tabular into next pages
\usepackage{supertabular}
\usepackage{tabularx}
\newlength{\fullcollw}
\setlength{\fullcollw}{0.47\textwidth}

%custom \section
\usepackage{titlesec}				
\usepackage{multicol}
\usepackage{multirow}

%CV Sections inspired by: 
%http://stefano.italians.nl/archives/26
\titleformat{\section}{\Large\scshape\raggedright}{}{0em}{}[\titlerule]
\titlespacing{\section}{0pt}{10pt}{10pt}

%for publications
\usepackage[style=authoryear,sorting=ynt, maxbibnames=2]{biblatex}

%Setup hyperref package, and colours for links
\usepackage[unicode, draft=false]{hyperref}
\definecolor{linkcolour}{rgb}{0,0.2,0.6}
\hypersetup{colorlinks,breaklinks,urlcolor=linkcolour,linkcolor=linkcolour}
\addbibresource{citations.bib}
\setlength\bibitemsep{1em}

%for social icons
\usepackage{fontawesome5}



\begin{document}


\begin{tabularx}{\linewidth}{@{} C @{}}
\Huge{Shun Zhang} \\[7.5pt]
%\href{https://github.com/username}{\raisebox{-0.05\height}\faGithub\ username} \ $|$ \ 
\href{https://www.linkedin.com/in/shun-zhang-b3aaa026/}{\raisebox{-0.05\height}\faLinkedin\ Professional Profile} \ $|$ \ 
%\href{https://mysite.com}{\raisebox{-0.05\height}\faGlobe \ mysite.com} \ $|$ \ 
\href{https://scholar.google.com/citations?user=GwRcQyYAAAAJ}{\raisebox{-0.05\height}{\faGlobe} \ Google Scholar} $|$ 
\href{mailto:email@mysite.com}{\raisebox{-0.05\height}\faEnvelope \ Lonver126@hotmail.com} \ $|$ \ 
\href{tel:+000000000000}{\raisebox{-0.05\height}\faMobile \ (817)896-7968} \\
\end{tabularx}


\section{Summary}
\resumeItemListStart
\resumeItem{Data Strategy and BI Architecture Leader: Expert in scalable BI and AI solutions, translating complex data into actionable insights with generative AI, real-time analytics, and modern data architectures.}
\resumeItem{Innovator in Data Visualization: Proficient in creating data visualizations and semantic models that drive user understanding and enable self-service analytics across data ecosystems.}
\resumeItem{Mentor and Strategic Advisor: Skilled in guiding technical talent, shaping product roadmaps, and fostering innovation to deliver impactful BI and data solutions.}
\resumeItemListEnd

%-----------WORK EXPERIENCES-----------
\section{Work Experiences}
% if you have been employed, do volunteer activities, or have held other formal or informal jobs, you can list them here.   

\resumeSubHeadingListStart

    \resumeSubheading
      {Director of AI and Data Science}{Oct, 2023 -- Present}
      {AstraZeneca} {South San Francisco, CA}
      \resumeItemListStart
        \small\resumeItem{AZ Brain Application Development and Advanced Data Solutions: Led the design and development of highly predictive models for healthcare professional (HCP) targeting in treatments like Lokelma, Tezspire, and Sipavibart, driving dynamic outreach strategies. Leveraged AI and machine learning to deploy scalable, self-service tools, empowering business stakeholders with data-driven insights and real-time engagement. Focused on integrating generative AI to enhance agility in strategy adjustment, thus elevating sales performance and enabling rapid, actionable insights across diverse data ecosystems.}\resumeItem{Generative AI-Driven Commercial Intelligence for Oncology: Spearheaded the development of AstraZeneca's pioneering generative AI solution for lung cancer, creating a production-level framework to generate advanced data architectures, patient journeys, and insights from claims and medical data. This enterprise-grade solution enables Looker-style data visualization and insight generation, fostering deep-dive exploration of oncology intelligence. Built a scalable and compliant infrastructure, ensuring seamless integration across business lines and adherence to strict governance protocols. Established a human-in-the-loop feedback pipeline to optimize and refine content relevance and accuracy continuously, enhancing both enterprise and field intelligence.}
        \resumeItem{Technical Leadership and Culture of Innovation: Directed and transformed a high-performing technical team, promoting a culture of innovation and experimentation across AstraZeneca. Fostered mentorship and collaboration, advancing the technical skills of senior team members and developing a robust talent pipeline. Championed the adoption of advanced data tools and practices, aligning with modern data architectures and embedding innovation as a core organizational value, to drive scalable AI solutions and future-forward analytics capabilities.}   
        \resumeItemListEnd






\resumeSubHeadingListStart
    \resumeSubheading
      {Sr. Director of Digital Health and Life Science}{Sept, 2021 -- June, 2023 (Affected by company layoff)}
      {Alibaba Cloud} {Bellevue, WA and Hangzhou, China}
      \resumeItemListStart
        \small\resumeItem{Healthcare Large Language Model (LLM) Applications for Advanced Medical Insights: Led the deployment of Alibaba Cloud's advanced LLM (Qwen) in healthcare, creating solutions that streamline medical coding processes, generate comprehensive patient overviews, and provide actionable insights to healthcare professionals. Integrated these models into Clinical Decision Support Systems (CDSS) within hospital Electronic Health Records (EHR) systems, enabling seamless access to medical knowledge, which enhances diagnostic accuracy and treatment quality. By deploying robust data governance and compliance safeguards, I ensured the model's reliability, scalability, and compliance with healthcare standards, contributing to the growth of intelligent data-driven solutions in primary care settings.}
        \resumeItem{High-Performance Computation Platform (HPC) for Accelerated Drug Discovery: Directed the development and deployment of a high-performance computing (HPC) platform, implementing GPU-driven parallel processing for advanced drug discovery. By leveraging cutting-edge tools like AlphaFold2, ESMFold, and RoseTTA Fold, this platform enabled protein structure predictions and functional annotations at unprecedented speeds. Collaborated with prominent bioinformatics tools such as GROMACS, AMBER, and NAMD, optimizing the HPC infrastructure to support large-scale molecular dynamics simulations that have significantly enhanced drug discovery workflows and efficacy.}
        \resumeItem{City Brain Data Platform for Population Health and Urban Intelligence: Led the implementation of a comprehensive data platform for Hangzhou City Brain, serving a population of 12 million. This project involved end-to-end management of data warehousing, ETL, data modeling, and data visualization solutions across multiple data platforms (Alibaba Cloud, Oracle, SQL Server, Hadoop) to support high-scale data processing. The platform facilitates real-time health data sharing, patient triage, and chronic disease management, optimizing resources for population health management. My work has been pivotal in creating scalable, impactful applications and advancing the city’s digital transformation.}
        \resumeItem{Pharmaceutical Enterprise Data Solutions for Roche: Built and managed enterprise data storage, retrieval, and analytics solutions, designing and implementing a robust data warehousing and data lake infrastructure. Developed ETL processes to support scalable analytics and crafted a data quality framework to ensure accuracy and consistency. Documented knowledge-sharing resources and best practices through white papers, fostering collaboration between internal and external teams on high-priority data initiatives.}
        \resumeItem{Strategy Leadership in Digital Transformation for Healthcare: Directed AI-driven digital transformation strategies across payers, providers, and pharmaceutical companies, with a focus on enriching the customer experience through business intelligence solutions. Managed a team of 45+ professionals, including data scientists, engineers, and product teams, to deliver advanced AI products. Leveraging a blend of machine learning, cloud architecture, and API integration, I provided thought leadership and fostered innovation, driving successful AI product deployments across diverse healthcare and life science environments.}
        \resumeItemListEnd





    \resumeSubheading
      {Director of AI for Health}{Jan, 2020 -- Sept, 2021}
      {Microsoft}{Redmond,WA}
     \resumeItemListStart
     \small\resumeItem{Technical Strategy and Data Platform Development: Spearheaded the design and deployment of enterprise-grade Azure platforms across hospitals, universities, and non-profit organizations, delivering secure, compliant, and scalable data solutions. Played a key role in shaping the strategic roadmap to enhance data accessibility, advanced analytics, and business intelligence applications.}
     \resumeItem{Architectural Oversight and Compliance: Directed cross-functional teams in data architecture, data engineering, informatics, and data science to support advanced clinical and research data needs. Provided essential legal and compliance leadership to ensure data integrity and protect client confidentiality, including contractor negotiations and governance for Microsoft AI for Health projects.}
     \resumeItem{AI and Data-Driven Insights: Developed machine learning models and data pipelines for predictive analytics and clinical diagnostics, contributing to impactful initiatives like Microsoft’s COVID-19 global response data platform, which utilized real-time analytics for pandemic management. Leveraged generative AI for advanced data modeling and insight generation in healthcare applications.}
     \resumeItem{Key projects include:}
        \resumeItemListStart
        \resumeItem{COVID-19 HPC Consortium: Enhanced pandemic response through advanced analytics and HPC, leading real-time insights for a global initiative.}
        \resumeItem{Machine Learning for Clinical Imaging: Built and deployed ML models for prostate cancer detection in PET/CT scans for the British Columbia Cancer Research Center, demonstrating the potential of predictive diagnostics at scale.}\resumeItem{AI for Public Health and Disease Prediction: Contributed to Novartis Foundation’s AI-driven leprosy risk assessment and cardiovascular risk stratification models, integrating advanced data visualization and semantic modeling to drive actionable insights.}
        \resumeItem{CGenetic Database Platform: Developed a secure genetic data-sharing portal for Seattle Children’s Hospital, optimizing data architecture for collaborative research on sudden infant death syndrome.}
        \resumeItem{Business Intelligence Enhancement through AI: Integrated AI-enhanced data processing with external partners like SRL Diagnostics, transforming pathology diagnosis workflows and elevating Looker’s potential for real-time data exploration and insight generation.}
    \resumeItemListEnd
    \resumeItemListEnd

    \resumeSubheading
      {Sr. Director of Data Science}{Jul, 2016 -- Dec, 2019}
      {Health Care Services Corporation (Blue Cross Blue Shield, TX,IL,MT,OK,NM)}{Chicago, IL}
    \resumeItemListStart
    \small\resumeItem {Provider Quality Evolution}
        \resumeItemListStart
        \resumeItem{Provider Quality Evolution and Advanced Analytics Strategy: Spearheaded the design and execution of an enterprise-wide quality measurement matrix, anchored in NCQA, HEDIS, and clinical guidelines, driving strategic, data-driven support for clinical operations and business intelligence initiatives. Led quality measure reporting and A/B testing, leveraging claims and EHR data to elevate data-driven insights across the organization.}
        \resumeItem{Business Intelligence and Data-Driven Decision Support: Oversaw enterprise BI processes and quality measurement activities that supported high-impact clinical operations and performance improvement. Directed key initiatives, including Medicare Advantage Quality Improvement and STARS rating projects, aligning analytics with strategic business goals. Conducted population health data integration, using census and HRSA data to strengthen data quality and insights for diverse user groups.

}
        \resumeItemListEnd
    \resumeItemListEnd
    
   
    \resumeItemListStart
    \small\resumeItem{Provider and Network Decision Analysis (PANDA)}
        \resumeItemListStart
        \resumeItem{Data Architecture and Predictive Modeling: Developed patient-level risk adjustment models using advanced ML techniques, integrating claims, external socioeconomic, and comorbidity data to enhance data insights for provider and network teams.}
        \resumeItem{Machine Learning-Driven Provider Insights: Built and deployed clustering models to segment diseases based on treatment and cost patterns, creating comparative analytics for physician benchmarking. Developed ensemble models to accurately classify provider specialties and assess underrepresented providers in the insurance network using minimal claims data.}
        \resumeItem{Cross-Functional Data Strategy: Expanded PANDA's BI impact by collaborating across business teams to enhance both internal and external decision support. Innovated static and dynamic data visualizations, combining usability with detailed attributions to ensure maximum impact on provider and network teams.}
        \resumeItemListEnd
    \resumeItemListEnd
    
    \resumeItemListStart
    \resumeItem{Provider Social Network Visualization Tool Development}
    \resumeItemListStart
        \resumeItem{Provider Social Network Visualization Tool: Built a powerful BI tool in Python Bokeh, providing users with interactive insights into provider referral patterns and collaboration networks, thereby enhancing contracting and network optimization decisions.}
        \resumeItem{Data Visualization and BI Reporting: Optimized provider data visualizations to reveal network dynamics and strengthen provider relationships, supporting strategic partnerships and decision-making across the organization.}
        \resumeItemListEnd
    \resumeItemListEnd
        
    \resumeSubheading
      {Statistician III}{Nov, 2014 -- Jul, 2016}
      {NORC at The University of Chicago}{Chicago,IL}
      \resumeItemListStart
        \small\resumeItem{Academy Health and OPTUM(United Health Group) - Rheumatoid Arthritis Data Challenge (2016 Health Datapalooza):I crafted a comprehensive proposal, earning the opportunity to participate in the esteemed 2016 Health Datapalooza Data Challenge. Utilizing an amalgamation of data sources, including Electronic Medical Records (EMR), claims data, and free text provider notes, I developed a predictive model to estimate medication persistence in patients with Rheumatoid Arthritis. This innovative approach resulted in securing the first prize at the final competition. Subsequently, I presented the findings and proposed solutions to a distinguished committee, contributing to a broader understanding of treatment adherence in Rheumatoid Arthritis patients.}
        \resumeItem{Medicare and Medicaid Beneficiary Survey: I conducted a comprehensive assessment of disclosure risk associated with the release of public use data. Utilizing a hybrid data approach, I amalgamated claims data with survey data to generate insightful analytical reports for Medicare Fee-for-Service patients. Further, I managed the entire data delivery pipeline, overseeing multi-round data collections and maintaining rigorous quality control to ensure the accuracy, consistency, and reliability of the data assets.}
        \resumeItem{Multiple System Utilization for Tricare Beneficiaries Project: I managed an extensive longitudinal claims database, encompassing 9.6 million active-duty personnel, military retirees, and dependents. My responsibilities involved the meticulous examination and monitoring of migration behavior and payment patterns among Tricare beneficiaries transitioning between the direct care and purchased care systems. I conducted comparative analyses of the quality of care - measured through care processes and outcomes - between military facilities and civilian providers. For comprehensive payment comparisons, I utilized the sophisticated Medical Episode Group (MEG) tool, developed by Thomson Reuters.}
        \resumeItemListEnd
        
    \resumeSubheading
      {Biostatistician}{Jun, 2011 -- Nov, 2014}
      {National Center for Primary Care}{Atlanta, GA}
      \small\resumeItemListStart
        \resumeItem{Social Network Analysis: Breast Cancer Patient-Provider Network: Conducted social network analysis on the breast cancer patient-provider network to measure social network properties and identify important nodes in the healthcare network. Compared communities with different network properties to explain differences in health outcomes.}
        \resumeItem{Medical Model Simulation and Decision-making Project: Developed a systematic framework for medical decision-making using TreeAge software. Created Markov models, Monte Carlo simulations, and decision tree analyses to evaluate available options and develop strategies that maximize success while minimizing risk. Conducted cost-effectiveness analysis for adherence to long-term controller medications in children with asthma.}
        \resumeItemListEnd
\resumeSubHeadingListEnd



%-----------EDUCATION-----------
% Please list your current institution first and then past schools in reverse chronology. No need for GPA, etc. You do not need to include high school but may do so if there are accomplishments you would like to highlight.
\section{Education}
\resumeSubHeadingListStart

    \resumeSubheading
        {MASSACHUSETTS INSTITUTE OF TECHNOLOGY}{Jun, 2014 -- Jul, 2014}
        {Summer Courses}{Cambridge, MA}
      \resumeSubheading
        {UNIVERSITY OF NORTH TEXAS HEALTH SCIENCE CENTER}{Aug, 2009 -- May, 2011}
        {Master of Public Health with concentration in Biostatistics}{Fort Worth, TX}

      \resumeSubheading
        {ANHUI MEDICAL UNIVERSITY}{Sept, 2002 -- Jul, 2007}
        {MBBS}{Hefei, China}
\resumeSubHeadingListEnd






%-----------AWARDS & HONORS-----------
\section{Awards \& Honors} 
% This section can include academic achievements – things like scholarships, Dean's list, honors societies – as well as recognition in your community - community service, religious study, volunteerism, military service, or anything else. You can remove or add sections as needed.
\resumeSubHeadingListStart
    \resumeSubheading
    {Digital Edge 50 Award in US for Project of Provider Efficiency and Quality Measurement}{}
    {CIO magazine}{2018}
    \resumeSubheading
    {Outstanding Employee Award}{}
    {Health Care Services Corporation }{2016}
    \resumeSubheading
    {First Prize Winner of Health Datapalooza Data Challenge Competition}{}
    {Academy Health \& United Health Group(Optum)}{2016}
\resumeSubHeadingListEnd


%-----------Licensure & Certification-----------
\section{License \& Certification}
% Also an optional section, for any hobbies, sports, artistic and musical pursuits, etc. that you would like to include. You can include as many or as few as you like: delete or add as needed. 
\begin{itemize}[leftmargin=0.15in, label={}]
    \normalsize{\item{
     \textbf{Azure Data Fundamentals \& Azure AI Fundamentals \& Developing AI Application on Azure}{: {Microsoft} } \\
     \textbf{Machine Learning Specialization}{: {Coursera} } \\
     \textbf{Deep Learning Specialization}{: {Coursera} } \\
     \textbf{Certified Base Programmer for SAS®9}{: {(License BP000759v9)} } \\
     \textbf{Certified Advanced Programmer for SAS®9}{: {(License AP000202v9)} } \\
     \textbf{SAS Certified Clinical Trials Programmer Using SAS®9}{: {(License CTP000539v9)} } \\
     \textbf{Certified in Public Health for The National Board of Public Health Examiners }{: {(License 6622)} } \\
    }}    
 \end{itemize}

%-----------RESEARCH PRESENTATIONS-----------
\section{Research Presentations} 
% It is not expected that applicants will have items for this section, but if you have presented or published research findings at, for example, a student research conference, please list those here.
\begin{itemize}[leftmargin=0.15in, label={}]
    \normalsize{\item{
\begin{enumerate}
    \item Xin Hou, Yong He, Pan Fang, Shun Zhang, et al. \textit{Using artificial intelligence to document the hidden RNA virosphere}, Cell, Oct, 2024. \url{https://www.cell.com/cell/fulltext/S0092-8674(24)01085-7}
    \item Yong He, Cheng Wang, Shun Zhang, Nan Li, Zhaorong Li, Zhenyu Zeng. \textit{KG-MTT-BERT: Knowledge Graph Enhanced BERT for Multi-Type Medical Text Classification}, arXiv preprint arXiv:2210.03970.
    \item Yixi Xu, Raquel R Barbieri, Lucy Setian, Shun Zhang, et al. \textit{Reimagining leprosy elimination with AI analysis of a combination of skin lesion images with demographic and clinical data}, The Lancet Regional Health-Americas, 2022/5, (9).
    \item Shun Zhang, George Rust, Kathryn Cardarelli, Jesus Felizzola, Mesfin Fransua, Harold G. Stringer, Jr. \textit{Adherence to highly active antiretroviral therapy impact on clinical and economic outcomes for Medicaid enrollees with HIV and hepatitis C co-infection}, AIDS Care, 2015, 27 (7), 829-835.
    \item Shun Zhang, Shanell L. McGoy, Daniel Dawes, Mesfin Fransua, George Rust, David Satcher. \textit{The Potential for Elimination of Racial-Ethnic Disparities in HIV Treatment Initiation in the Medicaid Population among 14 Southern States}, PLOS One, Apr 25, 2014.
    \item Shun Zhang, Charles Senteio, Jesus Felizzola, Rust George. \textit{Disparities in Antiretroviral treatment among Medicaid HIV-infected pregnant women, 2005-2007}, American Journal of Public Health, December 2013, Vol. 103, No. 12, pp. e46-e53.
    \item Shun Zhang, Kathryn Cardarelli, Ruth Shim, Jiali Ye, Karla L. Booker, Rust George. \textit{Racial disparities in economic and clinical outcomes of pregnancy among Medicaid recipients}, Maternal and Child Health Journal, 2012; 15:45-54.
    \item Dominic Mack, Shun Zhang, Megan Douglas, Charles Sow, Harry Strothers, George Rust. \textit{Disparities in primary care Electronic Health Record (EHR) adoption rates}, Journal of health care for the poor and underserved, 27 (1), 327.
    \item RS Shim, MT Compton, S Zhang, K Roberts, G Rust, BG Druss. \textit{Predictors of Mental Health Treatment Seeking and Engagement in a Community Mental Health Center}, Community Mental Health Journal, 2017, 53 (5), 510-514.
    \item George Rust, Shun Zhang, Zhongyuan Yu, Lee Caplan, Sanjay Jain, Turgay Ayer, Luceta McRoy, Robert Levine. \textit{Counties eliminating racial disparities in colorectal cancer mortality}, Cancer, 2016, March.
    \item Dominic Mack, Shun Zhang, Megan Douglas, Charles Sow, Harry Strothers, George Rust. \textit{Disparities in Primary Care EHR Adoption Rates}, Journal of Health Care for the Poor and Underserved, Volume 27, Number 1, February 2016, pp. 327-338.
    \item Wonsuk Yoo, George Rust, Shun Zhang, James Lillard. \textit{Health disparity characteristics on growth patterns of breast cancer mortality trends among the US Counties, 1989-2010}, Cancer Research, 75 (15 Supplement), 3701-3701.
    \item George Rust, Shun Zhang, Khusdeep Malhotra, Leroy Reese, Luceta McRoy, Peter Baltrus, Lee Caplan, Robert S Levine. \textit{Paths to Health Equity – Local Area Variation in Progress Toward Eliminating Breast Cancer Mortality Disparities, 1990-2009}, Cancer, 2015, August, Volume 121, Issue 16, pp. 2765–2774.
    \item George Rust, Shun Zhang, Luceta McRoy, Maria Pisu. \textit{Potential Savings from Increasing Adherence to Inhaled Corticosteroid Therapy in Medicaid-enrolled Children}, The American Journal of Managed Care, 2015, March 21 (3), pp. 173-180.
    \item Abara, Winston E., Lerissa Smith, Shun Zhang, Amanda J. Fairchild, Harry J. Heiman, and George Rust. \textit{The Influence of Race and Comorbidity on the Timely Initiation of Antiretroviral Therapy Among Older Persons Living With HIV/AIDS}, American Journal of Public Health, 2014: e1-e7.
    \item George Rust, Shun Zhang, Kelvin Holloway, Yasmin Tyler-Hill. \textit{Timing of Emergency Department Visits for Childhood Asthma after Initial Inhaled Corticosteroid Use}, Population Health Management, July 2014.
    \item Khusdeep Malhotra, Peter Baltrus, Shun Zhang, Luceta McRoy, Lilly Cheng Immergluck, George Rust. \textit{Geographic and Racial Variation in Asthma Prevalence and Emergency Department Use among Medicaid-Enrolled Children, in Fourteen Southern States}, Journal of Asthma, June 2014, No. 10, pp. 1-24.
    \item Ruth S. Shim, Benjamin G. Druss, Shun Zhang, Giyeon Kim, Adesoji Oderinde, Sosunmolu Shoyinka, George Rust. \textit{Emergency Department Utilization among Medicaid Beneficiaries with Schizophrenia and Diabetes: The Consequences of Increasing Medical Complexity}, Schizophrenia Research, November 20, 2013.
    \item George Rust, Shun Zhang, Reynolds Joshua. \textit{Inhaled Corticosteroid Adherence and Emergency Department Utilization Among Medicaid-enrolled Children with Asthma}, Journal of Asthma, September 2013, Vol. 50, No. 7, pp. 769-775.
    \item Fang Fang Zhang, Roberto Cardarelli, Joan Carroll, Shun Zhang, Kimberly G. Fulda, Karina Gonzalez, Jamboor K. Vishwanatha, Alfredo Morabia, Regina M. Santella. \textit{Physical activity and global genomic DNA methylation in a cancer-free population}, Epigenetics, 6:3, pp. 293-9, March 2011.
    \item Charles Senteio, Summer Wright Collins, Rachael Jackson, Stacy Welk, Shun Zhang. \textit{Effective Resources Supporting Healthy Sexual Behavior in Formerly Incarcerated Persons}, American Journal of Sexuality Education, 2010, 5: pp. 362–376.
    \item Zhang Shun, Ding Xiaocang, Wang Haimin. \textit{The survey and analysis of impact on the financial crisis on the private medical services industry in Jing'an District, Shanghai}, Chinese Health Services Management, No.7, July 2009, pp. 475-476.
    \item Zhang Shun, Ding Xiaocang, et al. \textit{The dynamic monitoring survey of collected garbage spots in earthquake attacked area, Xuankou Township, Wenchuan County}, Chinese Primary Health Care, Vol.22, No.275, Nov. 2008, pp. 22-23.
    \item Zhang Shun, Zhu Xiaozhen. \textit{The survey on AIDS related knowledge among women who have work in the club of downtown Shanghai}, Chinese Journal of Public Health, Vol.24, Suppl., Aug. 2008, pp. 94-95.
    \item Zhang Shun, Zhu Xiaozhen, et al. \textit{Survey on attitude and behavior of sexual intercourse and knowledge of AIDS prevention among theatre academy students}, Chinese Journal of School Health, Vol. 29, No.7-B, 2008, pp. 15-16.
    \item Zhu Xiaozhen, Zhang Shun, et al. \textit{100 Questions on AIDS}, ISBN 978-7-5072-1333-1.
    \item Wang Liangfeng, Zhang Shun, et al. \textit{Current Status of self-esteem of middle school students and influential factors in the rural area of Anhui Province}, Modern Preventive Medicine, Vol.34, No.1, Jan. 2007, pp. 25-27,35.
    \item Zhang Shun, Wang Liangfeng, et al. \textit{Epidemiological survey on the current situation of social anxiety of left-behind children in primary school}, Modern Preventive Medicine, Vol.34, No.3, Feb. 2007, pp. 441-443.
    \item Zhang Shun, Wang Liangfeng, Sun Yehuan, et al. \textit{Current status and its influential factors of children’s feelings of loneliness in the rural area of Anhui province}, Chinese Journal of Disease Control and Prevention, Vol.11, Jan. 2007, pp. 61-64.
    \item Zhang Shun, Wang Liangfeng, Sun Yehuan, et al. \textit{Life Events and Self-esteem of Middle School Students in Rural Area of Anhui Province}, Chinese Mental Health Journal, Vol.20, No.11, November 2006, pp 730-732.
 \end{itemize}
\end{document}

