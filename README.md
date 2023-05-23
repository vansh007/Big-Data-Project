# Big-Data-Project

Project Plan
Enhancing Counterterrorism Efforts: A Fusion of Global Terrorism Database and HFI Report for Machine Learning-Driven Predictive Analysis

         Vansh Sharma, MSDA, SJSU



Course: DATA 228

Professor: Andrew H Bond

















1 Introduction	3
1.1 Purpose of this document	3
1.2 Intended Audience	3
1.3 Scope	3
2 Background and Objectives	4
3 Architecture & High Level Design	5
4 Organization	6
4.1 Project group	6
5 Development process	7
6 Communication	8
6.1 Collaboration	8
6.2 Git	8
7 Project plan	9
7.1 Time schedule	9
8 References	10












1 Introduction
1.1 Purpose of this document
The purpose of this document is to provide a detailed project Enhancing Counterterrorism Efforts: A Fusion of Global Terrorism Database and HFI Report for Machine Learning-Driven Predictive Analysis. This project aims to spread awareness among people, especially students at SJSU, about terrorism and the factors that contribute to terrorist activities. By leveraging the Global Terrorism Database and the HFI Report, this project utilizes machine learning techniques to analyze and predict terrorist events. Through the dissemination of this information, the document seeks to enhance understanding of terrorism and empower individuals to contribute to counterterrorism efforts. It serves as a valuable resource for students, researchers, and professionals interested in studying and addressing the complex issue of terrorism.

1.2 Intended Audience
This document shall be used in all phases of the project as a guideline. Intended audiences of this project are all project stakeholders: 
team member

 1.3 Scope
           The scope of this project is to develop a machine learning-driven predictive analysis model that can enhance counterterrorism efforts by identifying potential terrorist activities and predicting their likelihood of occurrence. The model will be developed using the Global Terrorism Database and the Human Freedom Index report, and will take into account various factors such as geographical location, socio-economic conditions, political instability, and religious extremism. The project will focus on the use of machine learning algorithms to analyze and interpret large volumes of data from multiple sources, and to provide actionable insights to law enforcement agencies and policy makers. The scope of the project also includes the development of a user-friendly web-based interface to facilitate access and use of the model









2 Background and Objectives

In an era marked by persistent global threats of terrorism, there is an increasing need to enhance counterterrorism efforts through the utilization of advanced technologies and comprehensive analysis. The Cato Institute's Global Terrorism Database and the Human Freedom Index report provide valuable insights into the patterns, causes, and impacts of terrorist activities worldwide. Building upon this wealth of information, the objective of this project is to develop a machine learning-driven predictive analysis model that integrates the Global Terrorism Database and the HFI report. By leveraging machine learning algorithms and predictive analytics, this fusion of data aims to identify key factors that contribute to terrorist activities and enable more accurate predictions regarding their occurrence. The ultimate goal is to create a valuable resource for individuals and organizations, particularly students at SJSU, by spreading awareness about terrorism and empowering stakeholders with actionable intelligence to support counterterrorism efforts effectively.
                                                           The primary goal of this project is to enhance counterterrorism efforts through the development and implementation of a comprehensive fusion of the Global Terrorism Database and the HFI report using machine learning-driven predictive analysis. By leveraging the power of advanced algorithms and predictive modeling techniques, the aim is to uncover meaningful patterns, correlations, and insights from the vast amount of data available in these sources. Through the fusion of these datasets, the project seeks to identify the key factors and indicators that contribute to terrorist activities and enable the generation of accurate predictions regarding their occurrence. The ultimate objective is to provide a valuable tool for policymakers, security agencies, and other stakeholders to better understand, prevent, and respond to terrorist threats. By bridging the gap between data analysis and counterterrorism efforts, this project aims to contribute to the global fight against terrorism and promote a safer and more secure world.

3 Architecture & High Level Design

The architecture design for this project involves a multi-step process. Firstly, data is extracted from the Global Terrorism Database and the HFI report by filling their respective forms on the Cato Institute website. Once access is granted, the data is ingested into two separate Amazon S3 buckets, each dedicated to storing the specific dataset. Subsequently, AWS Glue is employed to merge and transform the data from both buckets, ensuring compatibility and consistency. Machine learning algorithms are then applied to the merged dataset, leveraging the power of AWS's machine learning services. The results and conclusions derived from these algorithms are visualized using Tableau, creating an interactive dashboard that enables users to explore and analyze the findings effectively. This architecture design enables a seamless flow of data, efficient data processing, and insightful visualization, ultimately facilitating enhanced counterterrorism efforts through the fusion of data sources and advanced analytics.


5 Development process
The project development consists of four sections: data ingestion, data processing, data analysis, and dashboard development

For data preprocessing, the following steps will be undertaken: mean imputation of missing values to ensure completeness of the dataset, dropping duplicates to eliminate redundant information, and removing noise and outliers to improve data quality and accuracy.

In the data analysis phase, exploratory data analysis (EDA) will be performed to gain insights into the dataset, identify patterns, and uncover trends related to terrorism. Various statistical techniques and visualizations will be employed to understand the characteristics and distributions of the data. Furthermore, machine learning algorithms such as Random Forest and Decision Tree will be applied to analyze the data and derive meaningful predictions and classifications.

Finally, based on the outcomes of the data analysis, a dashboard will be developed using Tableau. This interactive dashboard will serve as a user-friendly interface, presenting the results and insights derived from the machine learning algorithms. Users will be able to explore the trends, predictions, and classifications related to counterterrorism efforts, providing a comprehensive view of the project's findings in a visually appealing and intuitive manner.
6 Communication









































7
Compile Project Report
VS


5/9/2023


5/9/2023




8
Compile Project Presentation
VS


5/9/2023


5/7/2023































































































9 References

Choi, W., & Choi, W. S. (2008). Economic sanctions, poverty, and international terrorism. Journal of Conflict Resolution, 52(1), 96-116. doi:10.1177/0022002707310447

Krueger, A. B., & Malečková, J. (2003). Terrorism and poverty: Evidence from the Middle East. Journal of Economic Perspectives, 17(4), 119-144. doi:10.1257/089533003772034925

Smith, J., Nair, R., & Salerno, J. (2019). Machine learning approaches for counterterrorism. Security Informatics, 8(1), 3. doi:10.1186/s13388-019-0019-0

Bandyopadhyay, S., & Younas, J. (2011). Terrorism and foreign direct investment: An empirical analysis of regional differences in India. Review of Development Economics, 15(3), 504-516. doi:10.1111/j.1467-9361.2011.00607.x








