# An Ordinal Severity Scale for COVID-19 Retrospective Studies Using Electronic Health Record Data 
JAMIA Open

## Authors
[Maryam Khodaverdi, MS MEng](https://directory.hsc.wvu.edu/Profile/61365); [Bradley S. Price, PhD](https://business.wvu.edu/faculty-and-staff/directory/profile?pid=273); [J. Zachary Porterfield, MD PhD](https://med.uky.edu/users/jpo284); [H. Timothy Bunnell, PhD](https://www.nemoursresearch.org/snap/user/5); [Michael T. Vest, MD](https://doctors.christianacare.org/provider/Michael+T.+Vest/844978); [Alfred J. Anzalone, MS](https://www.unmc.edu/bmi/current-students/student-bios/anzalone-jerrod-bio.html); [Jeremy Harper, MS](https://owlhealthworks.com/); [Wes D. Kimble, MPA](https://directory.hsc.wvu.edu/Profile/39623); [Hamidreza Moradi, PhD](https://umc.edu/facultyprofile/moradi_hamidreza/); [Brian Hendricks, PhD](https://directory.hsc.wvu.edu/Profile/52462); [Susan L. Santangelo, ScD](https://mmcri.org/?page_id=9111); [Sally L. Hodder, MD](https://directory.hsc.wvu.edu/Profile/41751)

## ABSTRACT
Objectives: Although the World Health Organization (WHO) Clinical Progression Scale for COVID-19 is useful in prospective clinical trials, it cannot be effectively used with retrospective Electronic Health Record (EHR) datasets. Modifying the existing WHO Clinical Progression Scale, we developed an ordinal severity scale (OS) and assessed its usefulness in the analyses of COVID-19 patient outcomes using retrospective EHR data.

Methods: An OS was developed to assign COVID-19 disease severity using the Observational Medical Outcomes Partnership common data model within the National COVID Cohort Collaborative (N3C) data enclave. We then evaluated usefulness of the developed OS using heterogenous EHR data from January 2020 to October 2021 submitted to N3C by 63 healthcare organizations across the United States. Principal Components Analysis (PCA) was employed to characterize changes in disease severity among patients during the 28-day period following COVID-19 diagnosis.

Results: The data set used in this analysis consists of 2,880,456 patients. PCA of the day-to-day variation in OS levels over the totality of the 28-day period revealed contrasting patterns of variation in disease severity within the first and second 14 days and illustrated the importance of evaluation over the full 28-day period.

Discussion: An OS with well-defined, robust features, based on discrete EHR data elements, is useful for assessments of COVID-19 patient outcomes, providing insights on progression of COVID-19 disease severity over time.

Conclusion: The OS provides a framework which can facilitate better understanding of the course of acute COVID-19, informing clinical decision-making and resource allocation.

## Highlights
We developed a generalizable COVID-19 severity scale to facilitate research on COVID-19 patient outcomes using real-world data.

Electronic health record data on 2,880,456 SARS-CoV-2-infected patients from 63 health centers across the United States were examined using National COVID Cohort Collaborative (N3C). Concept sets were identified and validated using standard medical terminologies necessary to assign a disease severity to each patient. 

Patterns of changes in disease severity among patients were characterized during the 28-day period following a SARS-CoV-2 diagnosis.

## National COVID Cohort Collaborative (N3C)
Base COVID-19 positive cohort called in this project involves shared logic used across all N3C project as described in the [N3C Cohort Paper](https://www.medrxiv.org/content/10.1101/2021.01.12.21249511v3.full-text). Additional coding was done by 
[Maryam Khodaverdi](https://directory.hsc.wvu.edu/Profile/61365).

[N3C GitHub page](https://github.com/National-COVID-Cohort-Collaborative/CS-Rural-Health/tree/main/ordinal-scale-EHR) contains codes developed in SQL/R with an Apache Spark backend for the project.

## License
[MIT](https://choosealicense.com/licenses/mit/)
