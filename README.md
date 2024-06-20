# [ECAI 2024 Tutorial - A Multi-View Panorama of Data-Centric AI: Techniques, Tools, and Applications](https://miriamspsantos.github.io/dcai-ecai-tutorial-2024/)

## Speakers

* [Miriam Seoane Santos](https://scholar.google.pt/citations?user=isaI6u8AAAAJ&hl=pt-PT), University of Porto
* [Pedro Henriques Abreu](https://scholar.google.pt/citations?user=nfIVXcMAAAAJ&hl=pt-PT), University of Coimbra
* [Alberto Fernández Hilario](https://scholar.google.pt/citations?user=FI0eA8kAAAAJ&hl=pt-PT), University of Granada

## Overview and Motivation
Over the past decade, Artificial Intelligence (AI) solutions have been driven by the model-centric paradigm, which to some extent neglects the power of data and its role in the data science lifecycle.Models learn from data, and when applied to real-world domains, are inevitably faced with data properties that naturally compromise their behavior (e.g., missing data, class overlap, imbalanced data, biased data, noisy data, leaky data). Therefore, an important part of the success of AI solutions is their ability to **transform imperfect data into intelligent data**, data of sufficient quality to allow classifiers to draw accurate and reliable inferences on the domains.This process of moving from imperfect to intelligent data in a systematic and continuous manner has given rise to the **Data-Centric AI** paradigm, where data became the center-piece for successful AI applications both in research and the industry alike.

With the recent breakthroughs in the EU AI Act, the shift towards Data-Centric AI becomes all the more crucial, since unchecked AI systems may have harmful consequences across several contexts (e.g., criminal justice, healthcare, finance). The development of trustworthy, fair, secure, explainable, and responsible AI solutions is therefore data-centric by nature, and especially critical in solutions deployed in high-stakes domains.


## Main Goals and Approach
In this tutorial, we will provide a complete panorama of the Data-Centric AI paradigm. The tutorial is developed with a hands-on approach, where each topic is accompanied by a tool, focusing on the following problems: 

- Data Complexity (exploring [pymfe](https://pymfe.readthedocs.io/en/latest/index.html), [pyhard](https://ita-ml.gitlab.io/pyhard/), and [problexity](https://problexity.readthedocs.io/en/latest/))
- Missing Data (exploring [mdatagen](https://pypi.org/project/mdatagen/) and [scikit-learn]())
- Imbalanced data (exploring [imbalanced-learn](https://imbalanced-learn.org/stable/))
- Data fairness (exploring [aif360](https://aif360.res.ibm.com) and [fairml](https://github.com/adebayoj/fairml))

To demonstrate the techniques and tools we will focus on healthcare and finance applications, among others. 


## Pre-Requisites
- Python Programming.
- Data Science / Machine Learning Background (basic understanding of building and evaluating ML models)

## Outline
1. **Introduction to Data-Centric AI**
    - Model-Centric AI versus Data-Centric AI
    - Overview of Imperfect Data (Imbalanced Data, Inconsistent Data, Redundant Data, Shifted Data, Irrelevant Data, Noisy Data, Redundant Data, Small Data, Overlapped Data, Missing Data)
    - **Hands-on:** Virtual environments with [conda](https://docs.conda.io/en/latest/) and [pip](https://pypi.org/project/pip/)

2. **Data Complexity**
    - Meta-learning and Meta-features
    - Data Complexity Measures and Data Difficulty Factors
    - **Hands-on:** [pymfe](https://pymfe.readthedocs.io/en/latest/index.html), [pyhard](https://ita-ml.gitlab.io/pyhard/), [problexity](https://problexity.readthedocs.io/en/latest/)

3. **Missing Data**
    - Introduction to Missing Data theory
    - Motivation for Missing Data Imputation
    - **Hands-on:** [mdatagen](https://pypi.org/project/mdatagen/), [scikit-learn]() for imputation

4. **Imbalanced Data**
    - Introduction to Imbalanced Data Learning
    - Strategies for Data Resampling: Oversampling vs. Undersampling
    - **Hands-on:** [imbalanced-learn](https://imbalanced-learn.org/stable/)

5. **Data Fairness**
    - Introduction to Data Fairness
    - Sources of Bias and Fairness Metrics
    - **Hands-on:** [aif360](https://aif360.res.ibm.com), [fairml](https://github.com/adebayoj/fairml)

6. **Conclusion and Take-Home Message**:
    - Summary of the key concepts covered
    - Incorporating Data-Centric AI techniques in monitoring and deployment
    - Best practices in versioning and reproducibility
    - Open avenues in Ethical, Trustworthy, and Responsible AI development

## Speaker Bios
<img style="float:left;width:100px;height:110px;  padding-right:10px" src="img/MS.png">

**Dr. Miriam Seoane Santos** (ORCID 0000-0002-5912-963X) concluded her Ph.D. in Informatics Engineering in 2022 and is currently an Assistant Professor at the Department of Computer Science of the University of Porto, Portugal. She is a member of the Laboratory of Artificial Intelligence and Decision Support (LIAAD) at INESC TEC and her research spans several topics within data complexity, data difficulty factors, and data intrinsic characteristics with particular implications for AI Ethics and Responsible AI. She has published her research across several high-impact journals, currently holding 26 publications, 1185 citations, and a h-index of 12. In 2023, she received the Award for Best Ph.D. Thesis in Artificial Intelligence 2022, promoted by the Portuguese Association in Artificial Intelligence.

<img style="float:left;width:100px;height:120px;  padding-right:10px" src="img/PA.jpeg">

**Dr. Pedro Henriques Abreu** (ORCID ID 0000-0002-9278-8194) is an Associate Professor at the Department of Informatics of the University of Coimbra in Portugal, full member of the Cognitive and Media Systems of CISUC, one of the area editors of the Information Fusion journal and one of the editors of the Data Science and Analytics journal. His research interests include the development of Data-Centric AI approaches especially related to missing, imbalance data, and data fairness. He is the author of more than 100 publications, which have been nominated and awarded multiple times as best papers. He currently holds 2490 citations, an h-index of 25, and an i10-index of 47. Over the years, he was a member of the Programme Committee and Editorial Board of some of the leading conferences and journals in these fields and participated as a researcher in 8 international and international projects.

<img style="float:left;width:100px;height:100px;  padding-right:10px" src="img/AF.jpg">

**Dr. Alberto Fernández Hilario** (ORCID ID 0000-0002-6480-8434) is a Full Professor at the Department of Computer Science and Artificial Intelligence of the University of Granada, Spain. His research spans Data Science, Computational Intelligence, Ethics, and Trustworthy Artificial Intelligence, with a particular emphasis on interdisciplinary, applied, and problem- oriented approaches. With over 60 publications, he has received over 10,000 citations, achieving an H-index of 37. He has edited a monograph titled “Learning from Imbalanced Datasets” (2018, Springer Ed.) and received awards such as the "Lofti A. Zadeh" prize from IFSA for the Best Article in 2009-2010, two awards from the University of Granada for Best Publication in Engineering (2013 and 2014), and the "Excellence in Knowledge" award in 2017. Acknowledged as a Highly Cited Researcher in Computer Science in 2017, Dr. Fernández ranks within the top 2% of the most influential researchers globally according to the Stanford ranking. 


## Acknowledgements
This work is financed by National Funds through the Portuguese funding agency, FCT - Fundação para a Ciência e a Tecnologia, within project LA/P/0063/2020.
DOI 10.54499/LA/P/0063/2020 | https://doi.org/10.54499/LA/P/0063/2020