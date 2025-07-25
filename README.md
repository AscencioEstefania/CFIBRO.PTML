# CFIBRO.PTML
PCRIF.PTML Models for Advancing Cystic Fibrosis Care 

# Authors
Estefanía Ascencio-Medinaa,b,#, María D. Pastor-Viveroc,#,*, Carmen Velázquezd,#, José Ángel Fernández-Higueroe, Maialen Zabala-Zearretad, Aliuska Duardo-Sánchezg, Ane Ibañez-Antolính, Jon Altuna-Alvarezd Amaia Gonzalez-Magañad,j  Itxaso Montañezf,Patricia Iraurgui-Arcarazoc, Ainhoa Gómez-Bonillac, Félix Baranda Garcíac, Shan Heh, Sonia Arrasateh*, David Albesa-Jové,d,i,j,*, Humberto González-Díaza,h,j

# Affiliations
a Department of Computer Science and Information Technologies, Faculty of Computer Science, CITIC-Research Center of Information and Communication Technologies, University of A Coruña, 15071 A Coruña, Spain.
b IKERDATA S.L., ZITEK, University of Basque Country UPVEHU, Rectorate Building, 48940 Leioa, Spain.
c Cruces University Hospital, Biobizkaia Health Research Institute, 48903 Barakaldo, Spain.
d Instituto Biofisika (CSIC, UPV/EHU), Fundación Biofísica Bizkaia/Biofisika Bizkaia Fundazioa, 48940 Leioa, Spain.
e Department of Immunology, Microbiology and Parasitology, University of the Basque Country, 48940 Leioa, Spain.
f Jesuitak Politeknikoa, 48010 Bilbao, Spain.
g Department of Public Law, University of the Basque Country (UPV/EHU), 48940 Leioa, Spain.
h Department of Organic and Inorganic Chemistry, University of the Basque Country (UPV/EHU), 48940 Leioa, Spain.
i Department of Biochemistry and Molecular Biology, University of the Basque Country (UPV/EHU), 48080 Bilbao, España.
j Ikerbasque, Basque Foundation for Science, 48013 Bilbao, Spain


# Abstract
Background
Cystic Fibrosis (CF) is a genetic disorder characterised by dysfunctional ion transport leading to thick mucus secretion and chronic pulmonary infections. Current treatment relies heavily on antibiotics, guided by antibiotic susceptibility testing, which often lacks correlation with clinical outcomes due to the complex multifactorial nature of CF pulmonary disease. 
Methods
In this longitudinal study, we analyse the sputum samples from 48 CF patients using Next Generation Sequencing to track microbial changes alongside clinical outcomes over six months. Additionally, we develop a predictive computational model that integrates multiple clinical variables, including bacteriome composition, to predict clinical outcomes. 
Results
Our findings underscore the potential of AI-driven approaches in CF clinical practice, offering insights into disease dynamics, treatment optimisation, and personalised medicine. Furthermore, we address data privacy concerns by introducing a Monte Carlo Synthetic Data methodology, ensuring compliance with the General Data Protection Regulation while preserving data robustness. 
Conclusion
Overall, our study enhances understanding of CF pathophysiology and highlights the potential of AI in improving patient outcomes.


# Personal Data Protection

All data management and analysis were in compliance with the General Data Protection Regulation (GDPR). GDPR defines pseudonymization in Article 4 (5) as: 'the processing of personal data in such a way that they can no longer be attributed to a data subject without the use of additional information, provided that such additional information is kept separately and is subject to technical and organizational measures intended to ensure that the personal data are not attributed to an identified or identifiable natural person'. In general terms, pseudonymization aims at protecting personal data by hiding the identity of individuals (data subjects) in a data set, for example by replacing one or more personal data identifiers with so-called pseudonyms and by adequately protecting the link between the pseudonyms and the initial identifiers. Consequently, all patient data was pseudonymized by the team of the Biocruces Foundation by using an internal code to identify the patients. These codes and the identities of patients were never shared with the other researchers in this paper or the public in general. 

# Data availability
Source data and code can be found at https://github.com/AscencioEstefania/CFIBRO.PTML. Source data can also be found as Supporting Data in the following Excel files: SI01_PCRIF.PTML-LDA-Results.xlsx (Patient data: including Euclidean distance values and moving averages calculated for all discrete and continuous input variables and PCR results for patients from interviews 0, 1, and 2, for CF patients); SI02_PCRIF.PTML-MCSD-model.xlsx (selected input variables to perform the LDA models). SI03_PCRIF.PTML-MC-Synthetic-Data.xlsx (input variables derived from Euclidean distances obtained from synthetic data, intended for subsequent LDA model generation). SI04_ PCRIF.PTML-LDA-heatmap.xlsx (patient data featuring diverse bacterial microbiomes vs output variables including FEV1, FVC, HD, ATBiv, and Shannon index, along with a specific mutation). Likewise, the OD (Observed Data) and its corresponding model can be found in the file Python Code_PCRIFPTML_OD_model.ipynb. Additionally, the SD (Synthetic Data) and its respective model are available in Python Code_PCRIFPTML_MCSD_model.ipynb. Finally, the combined dataset (OD + SD) and its corresponding model can be found in Python Code_IFPTML-OD+MCSD_model.ipynb.


# Acknowledgements 
The authors acknowledge financial support from the Basque Government's Department of Health (Research Projects 2022333042, 2020333031, and 2021333049). H.G.-D. thank the financial support of the Research Project AIMOFGIFT -KK-2022/00032- funded by the Basque Government, Department of Economic Development, Sustainability and Environment, through the program of aid for Collaborative Research in strategic areas. D.A.-J. acknowledges support by the Spanish Ministry of Science and Innovation (MCIN/AEI/10.13039/501100011033/ FEDER, UE project project PID2021-127816NB-I00), and IT1745-22 of the Basque Government. M.Z. and J.A. acknowledge support from the Basque Government predoctoral program. Workflow and figures were created using BioRender.com.





