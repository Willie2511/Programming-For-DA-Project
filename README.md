# Programming-For-DA-Project

This readme will explain the choice of subject and the thought process into the creation of the datasets.


This project focuses on third level education, and analyses the impact that Covid19 has had on third level students. The Covid19 pandemic has removed, or at least limited, the entire student life as we know it. Attending lectures, student nights, social clubs, sports clubs and group study sessions can no longer be carried out due to restrictions throughout the year, but how much has the removal of social interaction had an affect on students academic performance. The project brief specified that you should:

• Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.

• Investigate the types of variables involved, their likely distributions, and their relationships with each other.

• Synthesise/simulate a data set as closely matching their properties as possible.

• Detail your research and implement the simulation in a Jupyter notebook – the data set itself can simply be displayed in an output cell within the notebook.

The real-world phenomenon selected for this project was to investigate the impact Covid19 restrictions have had on third level students motivation levels. Four variables were selected which we believe would be correlated to students motivation levels and overall performance. The variables selected were: Sex, Grade, Activity Hours and Social Media Use. Students motivation levels would be measured in terms of Grade. A highly motivated student would generally be expected to achieve consistently higher grades than an unmotivated student, therefore for experimental purposes we will directly associate students grades with levels of motivation. Each variable is thoroughly analysed and an accurate data distribution is selected to create the arrays. 

Once the variables are created, they are added to a data frame using the pandas function '.DataFrame'. This '.DataFrame' function then outputs our desired dataframe including and index, variable names, and the variable data created. Basic analyses of the data set is provided using simple code, and visual representations of both the numerical and categorical data is provided. Finally, covariance and correlation functions are used to analyse any correlations which may exist between the variables, and we compare the results to what we expected to see after the initial research. 

The project was extremely valuable in my development as a Data Analyst, as it provided the opportunity to synthesise a data set based on a real-world phenomenon. The tasks set out in the brief required me to broaden my skills and learn new code, yet through consistent work and carefully following the brief, each task was successfully completed. Added to the 'Notes' section at the end of the project is an alternative data set which was created early in the project development stage. Included below is a list of the research papers and online articles which helped shape my work. 


Aucejo, E., French, J., Araya, M., and Zafar, B. (2020) 'The impact of COVID-19 on student experiences and expectations: Evidence from a survey' Science Direct. Available at: https://www.sciencedirect.com/science/article/pii/S0047272720301353 Accessed on: 11/12/2020.

Barile, N. (2020) 'Exercise and the Brain: How Fitness Impacts Learning' Western Governors University. Available at: https://www.wgu.edu/heyteach/article/exercise-and-brain-how-fitness-impacts-learning1801.html Accessed on: 19/12/2020.

Curtin, D. (2020)'Businesses have adapted fast and moved online. April's .IE registrations were up a third' The Journal. Available at: https://www.thejournal.ie/readme/business-matters-thejournal-ie-5100696-May2020/ Accessed on: 11/12/2020.

CSO (2020) 'Women and Men in Ireland 2016' Central Statistics Office. Available at: https://www.cso.ie/en/releasesandpublications/ep/p-wamii/womenandmeninireland2016/education/ Accessed on: 14/12/2020.

Edwards, E., Fox, M. (2018) 'More teens addicted to social media, prefer texting to talking' NBC News. Available at: https://www.nbcnews.com/health/health-news/more-teens-addicted-social-media-say-they-re-wise-distractions-n908126 Accessed on: 20/12/2020.

Faller, G. (2014) 'How To Make The Grade' Irish Times. Available at: https://www.irishtimes.com/news/education/how-to-make-the-grade-1.1642295 Accessed on: 15/12/2020.

Gilsenan, K. (2019) '2019 in Review: Social Media is Changing, and It’s Not a Bad Thing' Global Web Index. Available at: https://blog.globalwebindex.com/trends/2019-in-review-social-media/ Accessed on: 20/12/2020.

Gonzalez, T., De la Rubia, M., Hincz, K., Comas-Lopez, M., Subirats, L., Fort, S., Sacha, G. (2020) 'Influence of COVID-19 confinement on students’ performance in higher education' Plos One. Available at: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0239490 Accessed on: 12/12/2020.

HEA (2020) 'Gender Action Plan 2018-2020' Higher Education Authority. Available at: https://hea.ie/assets/uploads/2018/11/Gender-Equality-Taskforce-Action-Plan-2018-2020.pdf Accessed on: 21/12/2020.

HESA (2020) 'Higher Education Student Statistics: UK, 2018/19 - Qualifications achieved' Higher Education Student Statistics. Available at: https://www.hesa.ac.uk/news/16-01-2020/sb255-higher-education-student-statistics/qualifications Accessed on: 11/12/2020.

Hewitt, R. (2020) 'Mind the gap: gender differences in higher education' HEPI. Available at: https://www.hepi.ac.uk/2020/03/07/mind-the-gap-gender-differences-in-higher-education/ Accessed on: 21/12/2020.

Hilliard, M. (2017) 'More women hold third-level qualifications than men, Census shows' Irish Times. Available at: https://www.irishtimes.com/news/education/more-women-hold-third-level-qualifications-than-men-census-shows-1.3302634#:~:text=When%20it%20comes%20to%20the,40.7%20per%20cent%20of%20men. Accessed on: 21/12/2020.

Kissel, R., Poserina, J. (2017) 'Poisson Distribution' Science Direct. Available at: https://www.sciencedirect.com/topics/mathematics/poisson-distribution Accessed on: 20/12/2020.

Kuhfeld, M., Soland, J., Tarasawa, B., Johnson, A., Ruzek, E., Lewis, K. (2020) 'How is COVID-19 affecting student learning?' Brookings. Available at: https://www.brookings.edu/blog/brown-center-chalkboard/2020/12/03/how-is-covid-19-affecting-student-learning/ Accessed on: 14/12/2020.

Lin, Y. (2020) '10 COVID-19 ECOMMERCE STATISTICS YOU SHOULD KNOW IN 2020 ' Oberlo. Available at: https://ie.oberlo.com/blog/covid-19-ecommerce-statistics Accessed on: 20/12/2020.

Mohsin, M. (2020) '10 SOCIAL MEDIA STATISTICS YOU NEED TO KNOW IN 2021' Oberlo. Available at: https://www.oberlo.com/blog/social-media-marketing-statistics Accessed on: 20/12/2020.

O'Brien, C. (2019) 'Significant gender gap in number completing college courses' Irish Times. Available at: https://www.irishtimes.com/news/education/significant-gender-gap-in-number-completing-college-courses-1.3792769 Accessed on: 20/12/2020.

Padulo, J., Bragazzi, N., De Giorgio, A., Grgantov, Z., Prato, S., Ardigo, L. (2019) 'The Effect of Physical Activity on Cognitive Performance in an Italian Elementary School: Insights From a Pilot Study Using Structural Equation Modeling' Frontiers. Available at: https://www.frontiersin.org/articles/10.3389/fphys.2019.00202/full Accessed on: 16/12/2020.

Palmer, K. K., Miller, M. W., and Robinson, L. E. (2013). Acute exercise enhances preschoolers’ ability to sustain attention. J. Sport Exerc. Psychol. 35, 433–437.

RTE (2017) 'Data shows gender gaps persist across third-level roles' RTE. Available at: https://www.rte.ie/news/education/2017/0719/891511-gender-third-level/ Accessed on: 22/12/2020.

RTE (2020) 'Internet usage increased during March Covid-19 lockdown - CSO' RTE. Available at: https://www.rte.ie/news/business/2020/0619/1148430-cso-internet-usage/ Accessed on: 21/12/2020.

Wold, S. (2020) 'COVID-19 is changing how, why and how much we’re using social media' Digital Commerce 360. Available at: https://www.digitalcommerce360.com/2020/09/16/covid-19-is-changing-how-why-and-how-much-were-using-social-media/ Accessed on: 21/12/2020.

World Health Organisation (2020) 'Physical activity' WHO. Available at: https://www.who.int/news-room/fact-sheets/detail/physical-activity Accessed on: 19/12/2020.

World Health Organisation (2020) 'IRELAND PHYSICAL ACTIVITY FACTSHEET' Euro WHO. Available at: https://www.euro.who.int/__data/assets/pdf_file/0004/288112/IRELAND-Physical-Activity-Factsheet.pdf?ua=1 Accessed on: 20/12/2020.