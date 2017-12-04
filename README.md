## Improving Diagnosis/Prognosis Accuracy in Alzheimer’s Disease Patients: Drugs, Supplements, and Tau Protein Levels Are Important Predictors

Final Project Report for AC209a - Introduction to Data Science

Official Group #46: Carlo Amadei, Hsiang Hsu, Rebecca Stern, Thomas Hsueh

### REPORT OVERVIEW 
This project aims to evaluate the interaction between taking Calcium supplements, Vitamin D supplements, and blood-thinning medications on the development of AD. We also examine the influence of tau protein levels on the development of AD. 

### MOTIVATION
Alzheimer’s Disease (AD) is a degenerative brain disease and the most common cause of dementia [1]. As of 2006, the global prevalence of AD was 26.6 million; this figure is expected to increase four-fold by 2050 [2]. In the United States in 2016, AD was the sixth leading cause of death [3]. This figure increased 71% between 2000-2013, deaths from AD increased 71% - an increase far greater than those from stroke (23%) and heart disease (14%) during the same time period. Given the debilitating nature of AD, the widespread prevalence of this disease, and the increasing lifespan of human population, understanding the risk factors associated with AD is an important step toward mitigating the harm caused by this devastating illness.<br /><br />

Previous studies have attempted to relate AD development to environmental (i.e., non-genetic) risk factors. One studied found that Vitamin K antagonists increase cognitive impairment [4]. Other efforts have focused on the role of diuretics and nutritional supplements in developing dementia [5]. However, little work has examined the interaction between Calcium, Vitamin D, and over-the-counter or prescription blood-thinning medications on AD development. This report presents our analysis of the relationship between taking Calcium, Vitamin D, and blood-thinners on AD development using data from the Alzheimer’s Disease Neuroimaging Initiative (ADNI) phase 2 program (ADNI2). <br /><br />

In addition, we also explore the role of CSB tau protein levels in association with AD. Previous studies have focused on the correlation between AD and CSB amyloid-beta levels, which has overshadowed the potential predictive power of tau. Importantly, tau exists inside the cell in “tangles” while amyloid-B presents in the extracellular matrix in plaques….[I need to improve this]. The results below conclude with our evaluation of the relevance of tau protein levels for improving predictive accuracy of AD patients based on the analysis of ADNI2 patient data. 
<br /><br />

### DATA DESCRIPTION
Our analysis of the ADNI2 data focuses on contributions related to diagnosis and progression of Alzheimer’s Disease (AD) properties. Importantly, the medications we examine are not on the list of medications that lead to exclusion from the ADNI cohort. We begin with the ADNIMERGE.csv as our primary data resource, with particular emphasis on the clinical components. ADNIMERGE is comprised of information on all patients from different ADNI phases (i.e., ADNI1, ADNI2, ADNIGO). To maintain consistency across our analyses and manageability of the data, we select only the patients who participated in the ADNI2 phase of the Initiative. In the ADNI2 observations, each row corresponds to an exam of a patient (“RID”, the patient identifier), and specific visit; multiple rows can refer to the same patient for different visits. It is possible to see a differentiation in baseline visit (‘bl’) predictors and predictors that refers to later visits. There are 94 columns in the dataset, the majority of which correspond to independent variables that could be assessed at each exam. There are two diagnosis features that correspond to diagnosis at baseline and diagnosis at a later visit. All diagnoses entries correspond to assignment into one of five diagnostic groups: Cognitively Normal (CN), Normal Control (NC), Subjective Memory Concern (SMC), MCI (Mild cognitive impairment), EMCI (Early Mildly Cognitively Impaired), Late Mildly Cognitively Impaired (LMCI, or classic MCI), and Alzheimer’s Disease (AD). We also interpret the meaning of each of the columns via consultation of the ADNIMERGE_DICT.csv, Data FAQs from the ADNI website, an ADNI training powerpoint, and the ADNI2 procedures manual. In addition to the data exploration, we also made qualitative observations about the dataset, including our concerns about potential limitations of the study, including the way the data was collected, potential collinearity, etc. 






### Reference

1. Loewenstein D, et al. Relative frequencies of Alzheimer’s disease, Lewy body, vascular and frontotemporal dementia, and hippocampal sclerosis in the State of Florida Brain Bank. Alzheimer Dis Assoc Disord 2002;16(4):203-12
2. Brookmeyer, R., Johnson, E., Ziegler-Graham, K., & Arrighi, H. M. (2007). Forecasting the global burden of Alzheimer’s disease. Alzheimer's & dementia, 3(3), 186-191.
3. Alzheimer's Association. (2016). 2016 Alzheimer's disease facts and figures. Alzheimer's & Dementia, 12(4), 459-509.
4. Annweiler, C., Ferland, G., Barberger-Gateau, P., Brangier, A., Rolland, Y., & Beauchet, O. (2014). Vitamin K antagonists and cognitive impairment: results from a cross-sectional pilot study among geriatric patients. Journals of Gerontology Series A: Biomedical Sciences and Medical Sciences, 70(1), 97-101.
5. DeBusk, R. M. (2000). Dietary supplements and cardiovascular disease. Current atherosclerosis reports, 2(6), 508-514.
6. https://adni.loni.usc.edu/wp-content/uploads/2008/07/adni2-procedures-manual.pdf
7. http://www.adni-info.org/Scientists/doc/ADNI2_Protocol_A3_17Oct2014_CLEAN.pdf
8. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3345787/







You can use the [editor on GitHub](https://github.com/hchsueh/AC209/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hchsueh/AC209/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
