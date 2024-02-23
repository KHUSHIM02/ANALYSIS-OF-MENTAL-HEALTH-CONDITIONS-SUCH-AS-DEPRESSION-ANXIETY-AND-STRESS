
# ANALYSIS OF MENTAL HEALTH CONDITIONS SUCH AS DEPRESSION, ANXIETY AND STRESS USING MACHINE LEARNING ALGORITHM

The research contributes to advancing mental health diagnosis, treatment, and intervention, underscoring the importance of machine learning advancements in addressing global mental health challenges. The paper has been accepted in International Journal Of Novel and Research (IJNRD 2023)

[![portfolio](https://img.shields.io/badge/Research%20Paper%20-8A2BE2)](https://www.ijnrd.org/papers/IJNRD2312244.pdf)


## ABSTRACT

This review paper examines the role of machine learning algorithms in predicting and differentiating mental health conditions, specifically depression, anxiety, and stress. Traditional diagnostic approaches face limitations in subjectivity and resource constraints, prompting the exploration of machine learning as a tool for early detection and intervention.
Following the PRISMA protocol, our methodology involves meticulous source identification from authoritative journals and conferences, repository selection from reputable publishers, and strategic queries to navigate vast information. The performance assessment phase scrutinizes the efficacy of machine learning approaches in diagnosing mental health problems.
Results from prominent research papers demonstrate the application of various machine learning algorithms, including tree-based models, artificial neural networks, random forests, support vector machines, CatBoost, and XGBoost.
This review contributes to the ongoing effort to enhance mental health diagnosis, treatment, and intervention, emphasizing the significance of machine learning advancements in addressing global mental health challenges.

    Index Terms - Mental Health, Mental Health Analysis Disorder, Anxiety, Depression, Stress, F1 score, Machine Learning Algorithms.

## I.	INTRODUCTION

The impact of mental health conditions, including depression, anxiety, and stress, has gained significant attention in recent years. These conditions affect millions of people worldwide, leading to substantial personal suffering, impaired quality of life, and increased healthcare costs. Early detection, accurate diagnosis, and timely intervention are vital for effective management and treatment of these mental health disorders. However, traditional diagnostic approaches often rely on subjective assessments and limited clinical resources, which can lead to delays in diagnosis and inadequate personalized treatment.

In recent years, the field of mental health research has witnessed the emergence of machine learning algorithms as promising tools for analysing and predicting mental health conditions. Machine learning techniques leverage large datasets and computational power to uncover complex patterns and relationships within the data, enabling the development of predictive models that can assist in the early detection and differentiation of mental health disorders. This approach holds the potential to transform mental healthcare by providing objective and data-driven insights.

This review paper aims to provide a comprehensive analysis of mental health conditions such as depression, anxiety, and stress using machine learning algorithms. By surveying the existing literature, we will explore the application of various machine learning techniques and data sources in the prediction and differentiation of these mental health disorders. The primary objective is to evaluate the efficacy and limitations of machine learning algorithms in accurately identifying and distinguishing between depression, anxiety, and stress.
The paper will delve into the diverse range of data sources that have been utilized in mental health analysis, including self-reported surveys, physiological signals, social media data, electronic health records, and other relevant sources. 

Furthermore, we will investigate the performance of different machine learning algorithms, such as support vector machines, random forests, deep learning models, and ensemble methods, in the context of mental health prediction and classification.
Moreover, this paper will explore potential future directions for advancing the analysis of mental health conditions using machine learning algorithms.

By providing a comprehensive analysis of the current state of research, challenges, and future directions, this review paper aims to contribute to the growing body of knowledge on using machine learning algorithms for mental health analysis. 
Ultimately, the goal is to pave the way for more effective and personalized approaches to mental health diagnosis, treatment, and intervention, thereby improving the lives of individuals affected by depression, anxiety, and stress.
This flowchart serves as a visual roadmap, guiding researchers and enthusiasts through the rich landscape of machine-learning algorithms featured in prominent research papers. 

By providing a structured overview, it encourages a deeper understanding of the algorithmic choices made in the pursuit of knowledge, innovation, and scientific advancement.

## II.	NEED OF STUDY

The exploration of mental health conditions, including depression, anxiety, and stress, through the lens of machine learning algorithms holds paramount significance for various compelling reasons. Firstly, these algorithms excel in efficiently analysing extensive datasets, facilitating the early detection of mental health conditions. This early identification, in turn, enables timely intervention and support, potentially averting the escalation of mental health issues. Moreover, machine learning provides an objective and data-driven approach to mental health assessment, offering a valuable complement to traditional subjective evaluations and reducing the risk of bias. By scrutinizing patterns in mental health data, machine learning contributes to the creation of personalized treatment plans, tailoring interventions to individual needs and thereby enhancing the overall effectiveness of mental health care. Additionally, these algorithms play a pivotal role in resource optimization by identifying high-risk individuals and prioritizing interventions, especially vital in healthcare environments with limited resources. The objective, data-driven nature of machine learning assessments also contributes to reducing the stigma associated with mental health conditions, encouraging individuals to seek help without fear of judgment. Furthermore, machine learning's ability to discern complex relationships and patterns aids in a more profound understanding of risk factors linked to mental health conditions, informing preventive measures and public health strategies. Large-scale analysis of mental health data using machine learning provides valuable insights into the prevalence and distribution of these conditions within populations, informing public health planning and policy development. The continuous monitoring capabilities of machine learning offer a dynamic view of individuals' mental health status, facilitating ongoing support and adjustment of treatment plans as needed. Finally, the application of machine learning to mental health research fosters advancements in the field, providing researchers with deeper insights into the complexities of mental health conditions and paving the way for innovative diagnostic tools and therapeutic approaches. In summation, the study of mental health conditions through machine learning is indispensable for advancing understanding, improving early intervention, and ultimately enhancing the overall quality of mental health care.

## III.	RESEARCH METHODOLOGY

The research methodology for exploring the use of machine learning in predicting mental health problems is based on a meticulous and systematic approach, guided by the PRISMA protocol. The carefully selected authoritative sources such as journals and conferences and utilized renowned repositories to ensure reliability. The exploration involved strategic queries and performance assessment of machine learning approaches in diagnosing and predicting mental health problems.

### 2.1 Planning Phase:     

    1. Source Identification: 
Careful selection of respected journals and conferences, including the Journal of Psychiatric Research and the International Conference on Computational Intelligence and Data Science.

    2. Repository Selection: 
Ensured reliability through renowned publishers.

    3. Searching and Analysis Exploration:
Initiated a knowledge quest through in-depth exploration of targeted publishers' websites.

    4. Strategic Queries:
Employed strategic queries like "Machine Learning Algorithms in Mental Health" to navigate through a vast sea of chronic disease-related disability.

    5. Performance Assessment: 
Study the performance of machine learning approaches, with a specific focus on diagnosing and predicting mental health problems.

### 2.2	Data Collection Phase:

Data collection is a crucial part of the research as the machine learning models are trained on the data, inconsistencies in data might lead to incorrect results. This process includes the selection of sources, collecting data, removing errors and inconsistencies, and making data suitable for machine learning models.

There are four types of data collection in the field of psychology to analyse mental health issues, they are as follows:

    2.2.1. Clinical Data: 
This data is collected by healthcare professionals in professional settings.

    2.2.2 Behavioural Data: 
Behavioural data refers to the actions/behaviour of an individual in a particular setting.

    2.2.3 Neuroimaging Data:
It refers to structural and functional data of the brain gathered through imaging devices.

    2.2.4 Biomarker Data: 
This data refers to the genes and genetics of an individual.

| Source | Data Examples | Advantages | Limitations |
| :---: | :---: | :---: | :---: | 
| Electronic Health Records (EHRs) | Clinical notes, diagnoses, medication information | Rich clinical data, longitudinal records. | Privacy concerns, data quality inconsistencies |
| Wearable Devices & Sensors | Heart rate, sleep patterns, activity levels | Real-time physiological data, objective measurements | Limited data types, user compliance |
| Social Media Data | Language patterns, sentiment analysis | Insights into mood, behavior changes | Ethical considerations, data bias |
| Self-Reported Surveys | Symptom assessments, questionnaires | Standardized data collection, individual perspectives | Subjectivity, potential bias |

    Categorization: 
Systematically broke down mental health problems into distinct categories, setting the stage for a comprehensive discussion.

    Algorithmic Insights:
 Examined the machine learning algorithms employed by researchers, revealing their roles in predicting various facets of mental health.

    Performance Evaluation:
Meticulously described and analysed each algorithm's performance.

| Metric | Definition | Importance |
| :---: | :---: | :---: |
| Accuracy | Proportion of correct predictions | Overall performance measure |
| Precision | Proportion of true positives among all positive predictions | Measures specificity |
| Recall | Proportion of true positives among all actual positive cases | Measures sensitivity |
| F1-score | Harmonic mean of precision and recall | Balanced measure of performance |

## CONCLUSION

Topic-

Centric Conclusions: Drew nuanced conclusions, weaving together findings and discussions related to predicting mental health problems using machine learning.

Generalization: Provided a holistic summary, offering a bird's-eye view of the predictive capabilities of machine learning in the realm of mental health.

PRISMA Protocol: The Gold Standard
Database Exploration: Following the PRISMA protocol, meticulously curated research articles and papers through database searching.

Screening and Inclusion: Rigorously removed duplicate records, ensuring the inclusion of only the most relevant and high-quality studies.

Eligibility Evaluation: Evaluated full-text articles for eligibility, with stringent criteria ensuring the inclusion of studies meeting appropriate conditions.

Final Inclusion: A total of meticulously chosen research studies found their place in this paper, enriching it with diverse perspectives.

Conclusion: In conclusion, this methodology serves as a guiding framework, systematically navigating readers through the complex landscape of machine learning in mental health prediction, providing a nuanced understanding of the state of the art in this dynamic field.


![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/65dbff62f9afec61fb1479538833d6fde82cae94/IMAGES/METHODOLOGY%20ADOPTED%201.png)

![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/65dbff62f9afec61fb1479538833d6fde82cae94/IMAGES/METHODOLOGY%20ADOPTED%202.png)
![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/65dbff62f9afec61fb1479538833d6fde82cae94/IMAGES/PERCENTAGE%20CHART.png)

## IV.	RESULTS AND DISCUSSION

![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/429a3ac446346df20f69962c351b694fc17475f5/IMAGES/TABLE%20ANALYSIS.jpg)

In a series of diverse studies aimed at understanding and predicting mental health issues using machine learning, Study 1 focuses on predicting barriers to treatment for depression. Utilizing a tree-based machine learning algorithm, the study achieved an accuracy of 70.6% ± 0.9% and an area under the curve (AUC) of 0.79. Study 2, addressing affective states in patients with anxiety disorders, employs various machine learning algorithms, reporting varied accuracies for methods like Fischer Projection, Artificial Neural Networks (ANN), Support Vector Machines (SVM), Canonical Correlation Analysis, and Neuro-Fuzzy System (NFS). In Study 3, screening seafarers for anxiety and depression involves methods such as CatBoost, Logistic Regression, Naïve Bayes, Random Forest, and SVM, achieving a CatBoost accuracy of 82.6% with a precision of 84.1%. Study 4 utilizes XGBoost, Random Forest, SVM, K-nearest-neighbor, and neural networks to predict depression and anxiety based on electronic health records, measuring success through the area under the curve for Major Depressive Disorder (MDD) and Generalized Anxiety Disorder (GAD). Study 5 predicts anxiety, depression, and stress in modern life using Decision Trees, Random Forests, Naïve Bayes, SVM, and KNN, evaluating accuracy for each category. In Study 6, behavioral differentiation between anxiety and depression is explored, achieving accuracies of 68% for the HD group and 74% for the HA group using Bagging Decision Trees and Random Forests. Study 7 assesses anxiety, depression, and stress through various algorithms, reporting accuracy for each category using Radial Basis Function Networks (RBFN). Study 8 investigates the prevalence of anxiety, depression, and stress among adults using a 2-stage cluster sampling process, measuring accuracy through the cluster sampling method. Study 9 analyzes mental health issues among employees, employing multiple algorithms such as Logistic Regression, KNN, Decision Trees, and Random Forest, with KNN achieving an accuracy of 84.23%.  Lastly, Study 10 conducts a comparative analysis of mental health disorders in higher education students, using Decision Trees, Logistic Regression, SVM, and Naive Bayes, with Logistic Regression achieving an accuracy of 88.76%. These studies collectively showcase the diverse approaches and successes in applying machine learning to mental health prediction and assessment.

![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/429a3ac446346df20f69962c351b694fc17475f5/IMAGES/ML%20ALGO%20USED.png)

![App Screenshot](https://github.com/KHUSHIM02/ANALYSIS-OF-MENTAL-HEALTH-CONDITIONS-SUCH-AS-DEPRESSION-ANXIETY-AND-STRESS/blob/da14abf3e8da9d48d25530616ef42c2c0f5c3181/IMAGES/MODEL%20SELECTION.png)

## V.	CONCLUSION

In summary, this review systematically investigated the use of machine learning (ML) algorithms in predicting and distinguishing depression, anxiety, and stress. Traditional diagnostic methods face limitations, prompting the exploration of ML for early detection. Following the PRISMA protocol, our methodology involved source selection from reputable journals and conferences, repository choices, and strategic queries. The performance assessment demonstrated the efficacy of diverse ML approaches, including tree-based models, neural networks, and ensemble methods.

Results from prominent research papers showcased the application of ML algorithms, such as tree-based algorithms achieving 70.6% accuracy in predicting depression and integrated systems using physiological signals achieving accuracies ranging from 61.8% to 96.0% for anxiety. The paper explored various data sources, including surveys and health records, and discussed the performance of ML algorithms, emphasizing their roles in mental health prediction.

The review highlighted potential future directions for advancing ML-based mental health analysis, contributing to the ongoing efforts to enhance global mental health diagnosis and intervention. By adhering to the PRISMA protocol, this paper offers a nuanced understanding of the current state of research and encourages continued innovation in leveraging ML for mental health challenges.

In essence, this review aims to guide stakeholders through the complex landscape of ML algorithms in mental health prediction, paving the way for more effective and personalized approaches to diagnosis, treatment, and intervention. The work underscores the importance of ML advancements in addressing global mental health challenges and promotes ongoing research in this critical field.

## VI.	DRAWBACKS

These common points highlight the multidimensional challenges in implementing machine learning-based approaches for predicting mental health conditions or behaviours in various contexts. Addressing these drawbacks is essential to ensure responsible, ethical, and effective utilization of predictive algorithms in healthcare and educational settings.

#### 5.1 Generalization Issues:

The reliance on machine learning may lead to challenges in generalizing findings to diverse populations, affecting tool effectiveness across different demographic groups or healthcare settings.

#### 5.2 Ethical Concerns:

Privacy, informed consent, and data security issues arise, posing ethical challenges related to the responsible handling of sensitive health data.

#### 5.3 Resource Intensiveness:

Implementing real-time pre-emptive tools in healthcare or educational settings may require significant resources, both in terms of technology infrastructure and personnel training.

#### 5.4 Subjectivity and Bias:

Relying on self-reported or biased data introduces subjectivity and potential bias, impacting the accuracy of predictions and risking the misinterpretation of motivations or barriers.

#### 5.5 Dynamic Nature:

Predictive models may struggle to capture the dynamic nature of mental health conditions, missing evolving barriers or changes in patients' or students' circumstances.

#### 5.6 Interpretability:

Complex machine learning models, perceived as "black boxes," pose challenges in understanding and interpreting predictions, impacting trust among users, clinicians, or educators.

#### 5.7. Limited Understanding of Mental Health:

The subjective and nuanced nature of mental health may not be fully captured by predictive algorithms, necessitating a more holistic approach.

#### 5.8 Unintended Consequences:

Implementing predictive efforts may lead to unintended consequences, such as overburdening certain groups, neglecting unique circumstances, or contributing to the medicalization of normal variations in mental health.

#### 5.9 False Positives and Negatives:

Predictive algorithms are prone to errors, including false positives (incorrectly identifying issues) or false negatives (missing issues), with potentially significant consequences.

#### 5.10 Access and Equity:

Disparities in access to interventions identified by predictive algorithms can exacerbate existing inequalities among individuals or students.

#### 5.11 Legal and Regulatory Compliance:

Compliance with legal and regulatory standards, including data protection laws, is crucial to avoid legal consequences and maintain institutional reputation.

#### 5.12 Human Interaction and Support:

Lack of human interaction in mental health analyses may miss the empathetic and supportive aspects, necessitating a balanced approach combining algorithmic insights with human interventions.

## VII.	FUTURE SCOPE

The future scope of analysis of mental health illnesses is vast and boundless. Due to the ever-evolving nature of technology, there are endless possibilities for the development of more efficient algorithms, data collection techniques, and different approaches. Machine learning can also help in the development of new therapies, medication, self-help devices, applications, etc.
After conscientious study and research, we can conclude the future scope of this research through the following key points.

#### 6.1 Timely detection and assessment of mental health conditions:

The machine learning algorithms can be used to recognize and identify changes in behavioural patterns, social media contribution, and other activities to identify possible mental health conditions, suicidal and self-harm tendencies, etc. Which can allow early and timely detection.

#### 6.2 Forecasting treatment outcomes:

Machine learning algorithms can be trained and fed through data and then can be used for predicting possible outcomes and understanding how a patient might respond to a treatment/procedure.

#### 6.3 Formulation of New Treatments:

The ability to predict machine learning algorithms can be used in the development of new drugs, medications, and other possible treatments.

#### 6.4 Technology-enabled monitoring of mental health:

The technological advancements can be utilized in the development of tech-enabled applications that monitor the mental health of an individual periodically, which can be further used by mental health experts for a better understanding of mental health conditions.

#### 6.5 Virtual mental health care/Online therapy and counselling:

The development of virtual platforms provides a more accessible, economical, healthy, and safe environment for users and also works towards reducing stigma towards mental health illnesses.
Other than these future developments, more work also needs to be performed on the existing methods and techniques, which includes: better data collection, data organization, working on current algorithms, a better understanding of medical and technical terms, and standardization at different levels for comparison.

## VIII.	IMPROVISATIONS

7.1. The data set that is used in the generation of the machine learning model should take into account the various diverse backgrounds so that the results are more effective and fulfil the real-world requirements.

7.2. The data collection and storage system should be secure because the personal data gathered from the patient raises a high concern for privacy and confidentiality so that mis usage can be avoided.

7.3. It is vital to promote and train psychologists/mental health experts in the field of technology in order to lead to the integration of technological advancements in the study of psychology.

7.4. Development of models that understand the complex nature of mental health illnesses, and give accurate results including the subtypes to prevent misdiagnoses.
     
7.5. Working on the development of trust of both patients and medical professions in technology, and providing an accessible and trustworthy environment to increase participation.

7.6. Working towards establishing a standardized data collection and storing system/format in order to avoid inconsistencies and incomplete and sparse data.

7.7. It is predominant to integrate the new models with traditional approaches, although we can rely on machine learning models for diagnosis in the future it is important to seek help from mental health professionals, this advancement is focused on making the diagnosis process easier and not to replace the professionals.

7.8. Working towards removing machine biases, since the model works on the data it is fed upon, it may lead to biased results or misdiagnosis.

## IX.	REFERENCES


[1] S. Swain and M. R. Patra, “Analysis of Depression, Anxiety, and Stress Chaos Among Children and Adolescents Using Machine Learning Algorithms,” Communications in computer and information science, Jan. 01, 2022. 

[2] S. BH et al., “Mental Health Analysis of Employees using Machine Learning Techniques,” 2022 14th International Conference on COMmunication Systems & NETworkS (COMSNETS), Jan. 2022, Published.

[3] “Human Verification.” https://www.semanticscholar.org/paper/The-Depression-Anxiety-Stress-Scale-21%3A-Spanish-and-Daza-Novy/c2f7eed68b3c676de749f09e0586040d92de239d

[4] “APA PsycNet.” https://psycnet.apa.org/journals/pas/10/2/176.html?uid=1998-02891-012

[5] T. Zhang et al., “The impact of maternal 
depression, anxiety, and stress on early neurodevelopment in boys and girls,” Journal of Affective Disorders, vol. 321, pp. 74–82, Jan. 2023.

[6] H. Güdül Öz and E. Nazik, “The relationship between fear of COVID-19 and depression, anxiety and stress in persons with disabilities: A cross-sectional study,” Archives of Psychiatric Nursing, vol. 43, pp. 15–21, Apr. 2023.

[7] U. Rehman, M. Yıldırım, and M. G. Shahnawaz, “A longitudinal study of depression, anxiety, and stress among Indians during COVID-19 pandemic,” Psychology, Health & Medicine, vol. 28, no. 1, pp. 60–68, Jan. 2022.

[8] N. Singewald, S. B. Sartori, A. Reif, and A. Holmes, “Alleviating anxiety and taming trauma: Novel pharmacotherapeutics for anxiety disorders and posttraumatic stress disorder,” 
Neuropharmacology, vol. 226, p. 109418, Mar. 2023.

[9] Ç. Aksu and D. Ayar, “The effects of visualization meditation on the depression, anxiety, stress and achievement motivation levels of nursing students,” Nurse Education Today, vol. 120, p. 105618, Jan. 2023.

[10] T. A. Brown, B. F. Chorpita, W. Korotitsch, and D. H. Barlow, “Psychometric properties of the Depression Anxiety Stress Scales (DASS) in clinical samples,” Behaviour Research and Therapy, vol. 35, no. 1, pp. 79–89, Jan. 1997.

[11] “APA PsycNet.” https://psycnet.apa.org/record/2015-54039-001

[12] “Anxiety in College Students: Signs, Symptoms &#038; Treatments,” Choosing Therapy, Oct. 24, 2023. https://www.choosingtherapy.com/anxiety-in-college-students/#:~:text=If%20a%20student%20is%20having,many%20other%20self%2Dcritical%20thoughts.

[13] N. J. LeBlanc, “Anxiety in college: What we know and how to cope,” Harvard Health, Aug. 27, 2019. https://www.health.harvard.edu/blog/anxiety-in-college-what-we-know-and-how-to-cope-2019052816729

[14] S. Verma and A. Mishra, “Depression, anxiety, and stress and socio-demographic correlates among general Indian public during COVID-19,” International Journal of Social Psychiatry, vol. 66, no. 8, pp. 756–762, Jun. 2020.

[15] “Depression Anxiety Stress Scale-21 (DASS21),” Addiction Research Center. https://arc.psych.wisc.edu/self-report/depression-anxiety-stress-scale-21-dass21/

[16] J. Brownlee, “Python Machine Learning Mini-Course,” MachineLearningMastery.com, Oct. 12, 2021. https://machinelearningmastery.com/python-machine-learning-mini-course/

[17] P. C. Austin, J. V. Tu, J. E. Ho, D. Levy, and D. S. Lee, “Using methods from the data-mining and machine-learning literature for disease classification and prediction: a case study examining classification of heart failure subtypes,” Journal of Clinical Epidemiology, vol. 66, no. 4, pp. 398–407, Apr. 2013.

[18] A. S. Yasin and M. A. Dzulkifli, “Differences in depression, anxiety and stress between low-and high-achieving students,” ResearchGate,Jun.01, 2011. https://www.researchgate.net/publication/287751683_Differences_in_depression_anxiety_and_stress_between_low-and_high-achieving_students

[19] S. H. Hamaideh, H. Al‐Modallal, M. Tanash, and A. Hamdan‐Mansour3, “Depression, anxiety and stress among undergraduate students during COVID‐19 outbreak and ‘home‐quarantine,’” Nursing Open, vol. 9, no. 2, pp. 1423–1431, May 2021.

[20] J. K, “The F1 score | Towards Data Science,” Medium, Oct. 11, 2022. https://towardsdatascience.com/the-f1-score-bec2bbc38aa6

[21] A. A. Mir, N. G. G. Jerome, R. Akshara, S. K. Reddy, S. K. Mohapatra, and J. Mohanty, “Comparative Analysis of Mental Health disorder in Higher Education Students using Predictive Algorithms,” 2023 International Conference on Applied Intelligence and Sustainable Computing (ICAISC), Jun. 2023, Published.

[22] A. Sau and I. Bhakta, “Screening of anxiety and depression among seafarers using machine learning technology,” Informatics in Medicine Unlocked, vol. 16, p. 100228, 2019.

[23] M. D. Nemesure, M. V. Heinz, R. Huang, and N. C. Jacobson, “Predictive modeling of depression and anxiety using electronic health records and a novel machine learning approach with artificial intelligence,” Scientific Reports, vol. 11, no. 1, Jan. 2021.

[24] A. Priya, S. Garg, and N. P. Tigga, “Predicting Anxiety, Depression and Stress in Modern Life using Machine Learning Algorithms,” Procedia Computer Science, vol. 167, pp. 1258–1267, 2020.

[25] T. Richter, B. Fishbain, A. Markus, G. Richter-Levin, and H. Okon-Singer, “Using machine learning-based analysis for behavioural differentiation between anxiety and depression,” Scientific Reports, vol. 10, no. 1, Oct. 2020.

[26] P. Kumar, S. Garg, and A. Garg, “Assessment of Anxiety, Depression and Stress using Machine Learning Models,” Procedia Computer Science, vol. 171, pp. 1989–1998, 2020.

[27] M. Mirzaei, S. M. Yasini Ardekani, M. Mirzaei, and A. Dehghani, “Prevalence of Depression, Anxiety and Stress among Adult Population: Results of Yazd Health Study,” Iranian Journal of Psychiatry, May 2019, Published.

[28] A. M. Chekroud et al., “Predicting Barriers to Treatment for Depression in a U.S. National Sample: A Cross-Sectional, Proof-of-Concept Study,” Psychiatric Services, vol. 69, no. 8, pp. 927–934, Aug. 2018.

[29] C. D. Katsis, N. S. Katertsidis, and D. I. Fotiadis, “An integrated system based on physiological signals for the assessment of affective states in patients with anxiety disorders,” Biomedical Signal Processing and Control, vol. 6, no. 3, pp. 261–268, Jul. 2011.



## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://khushimishprofile.netlify.app/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/khushimish26)


