## What is a Polygenic Risk Score (PRS)?

A Polygenic Risk Score (PRS) is a number that estimates a person’s inherited risk of developing a trait or disease based on various small genetic changes across their DNA.

Most diseases (like diabetes, cancer or heart disease) aren’t caused by a single gene. Instead, they’re influenced by hundreds or thousands of genetic variants, each adding small bit of risk. PRS combines these small effects into a single score.

**The final score gives an idea of someone’s overall genetic susceptibility toward a specific condition.**

**Important**: A PRS does not diagnose a disease. It only estimates risk and this risk can also depend on other factors like environment, lifestyle and ancestry.

---
## 📘 Module 1: From GWAS to PRS

>  Start here. Understand the science behind the scores

### What is GWAS?

| Title | Platform/ Channel | Link | Duration | Focus |
|---------|---------|------------|---------|------|
| **Genome-Wide Association Study - An Explanation for Beginners** | Nuno Carvalho | [Link](https://www.youtube.com/watch?v=sOP8WacfBM8&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9&index=10) | 7:35 | ...  |
| **Introduction to GWAS Part 1** | International Statistical Genetics Workshop | [Link](https://www.youtube.com/watch?v=Hjv_otXAkh0&list=PLHcpcW9ej-wKinl2WFb7c2OAFooExVxgt&index=10) | 6:29 | ...  |
| **Linkage Disequilibrium - Genome-Wide Association Studies (GWAS) Explained** | Behavioural Genomics | [Link](https://www.youtube.com/watch?v=_xbpGvQHQAA&list=PLHcpcW9ej-wKinl2WFb7c2OAFooExVxgt&index=12) | 4:05 | ...  |
| **20. Human Genetics, SNPs and Genome Wide Association Studies** | MIT OpenCourseWare | [Link](https://www.youtube.com/watch?v=KYQ2dPW5nEU&list=PLHcpcW9ej-wKinl2WFb7c2OAFooExVxgt&index=25) | 19:34 | ...  |
| **MIT CompBio Lecture 14 - GWAS (part 1)** | Manolis Kellis | [Link](https://www.youtube.com/watch?v=NvfiTLF37MM&list=PLHcpcW9ej-wKinl2WFb7c2OAFooExVxgt&index=30) | 15:26 | ...  |
| **MIT CompBio Lecture 14 - GWAS (part 2)** | Manolis Kellis | [Link](https://www.youtube.com/watch?v=u3oQWcwysLY&list=PLHcpcW9ej-wKinl2WFb7c2OAFooExVxgt&index=30) | 55:53 | ...  |


### Key Concepts Explained

* Summary statistics
* SNPs (Single Nucleotide Polymorphisms)
* Allele frequency
* Linkage Disequilibrium

---

## 📘 Module 2: Foundations of PRS

> Understand how PRS are built, why they work and the logic behind PRS.

### Beginner-Friendly Videos

These videos cover the basics and help build a strong foundation.

| Title | Platform/ Channel | Link | Duration | Focus |
|---------|---------|------------|---------|------|
| **Learn about polygenic risk scores and their game-changing potential** | Illumina | [Link](https://www.youtube.com/watch?v=3HjHSRjwiQk&list=PLHcpcW9ej-wLKarfGLusjudGN1OokDvZO) | 3:20 | ...  |
| **What are Polygenic Risk Scores and how can they be used in healthcare** | Cambridge Uni: Cardiovascular Epidemiology Unit | [Link](https://www.youtube.com/watch?v=BqR_G8DnPJw&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9&index=28) | 15:43 | ...  |
| **[Shing Wan Choi]Tutorial: Polygenic Risk Score (PRS) Analyses** | Open Box Science | [Link](https://www.youtube.com/watch?v=bgWWr2nWe3Q&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9&index=3) | 19:34 | ...  |
| **A quick guide to calculations of Polygenic Scores** | Giorgia bussu | [Link](https://www.youtube.com/watch?v=-QCAkLpnJQg&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9) | 4:05 | ...  |
| **Polygenic risk scores** | International Statistics Genetics Workshop | [Link](https://www.youtube.com/watch?v=FKw2XltZSpY&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9&index=10) | 22:21 | ...  |
| **Polygenic Scores - Genome-Wide Association Studies Explained Simply Part 5** | Behavioural Genomics | [Link](https://www.youtube.com/watch?v=5LtVbxgafy0&list=PLHcpcW9ej-wJfQyoXj9RxPUd1zBkGwUr9&index=2) | 12:28 | ...  |
| **Advanced methodologies polygenic risk scores, GxE interactions** | Wellcome Connecting Science Learning and Training | [Polygenic scores and G X E](https://www.youtube.com/watch?v=LRzv8COeTF8&list=PLHcpcW9ej-wI1egMyFjEQIVqK3GktiKpz&index=9) | 19:34 | ...  |


### 📖 Articles

* [A guide to performing Polygenic Risk Score analyses](https://pmc.ncbi.nlm.nih.gov/articles/PMC7612115/) by Choi et al. (2021)
* [How to: perform polygenic risk score analysis](hhttps://frontlinegenomics.com/how-to-perform-polygenic-risk-score-analysis/) by Gunn (2023)

* [Calculating Polygenic Risk Scores (PRS) in UK Biobank: A Practical Guide for Epidemiologists](https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2022.818574/full) by Collister et al. (2022)


### Key Concepts Explained

What makes a score “polygenic”

How PRS is derived from GWAS summary statistics

Risk alleles and their weights

Interpreting individual PRS values

---

## 📘 Module 3: Building a PRS

> Let’s get hands-on. Install tools, use sample data, run your first PRS.

### 🧰 Tools
This is a PRS calculation tutorial by Choi, Mak and O'Reilly. It provides a step-by-step guide on how to calculate Polygenic Risk Scores using various tools like PLINK, PRSice, LDpred2 and Lassosum.

Access the tutorial site [here](https://choishingwan.github.io/PRS-Tutorial/).


| Tool     | Language | Link                                                                                                         |
| -------- | -------- | ------------------------------------------------------------------------------------------------------------------ |
| PLINK| Command Line    | [Tutorial](https://choishingwan.github.io/PRS-Tutorial/plink/)    
| PRSice| R    | [Tutorial](https://choishingwan.github.io/PRS-Tutorial/prsice/)                              |
| LDpred2  | R        | [Tutorial](https://choishingwan.github.io/PRS-Tutorial/ldpred/) |
| Lassosum   | R   | [Tutorial](https://choishingwan.github.io/PRS-Tutorial/lassosum/)                                                                       |

---

## 🙌 Contribute or Star This Repo

This project is open-source and community-supported. If you found this helpful, please:

* 🌟 **Star** this repository
* 🔄 **Share** with someone who might need it
* 🧠 **Contribute** - Add new resources, correct typos, suggest content

Welcome to the world of PRS!
