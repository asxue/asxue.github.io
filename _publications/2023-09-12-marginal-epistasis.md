---
title: "A biobank-scale test of marginal epistasis reveals genome-wide signals of polygenic epistasis"
collection: publications
category: manuscripts
permalink: /publication/marginal-epistasis
excerpt: 'We learn marginal epistasis in the UK Biobank.'
date: 2023-09-12
venue: 'biorxiv'
paperurl: 'https://www.biorxiv.org/content/10.1101/2023.09.10.557084v1.abstract'
citation: 'Boyang Fu, Ali Pazokitoroudi, <b>Albert Xue</b>, Akarsh Anand, Prateek Anand, Noah Zaitlen, and Sriram Sankararaman (2023). &quot;A biobank-scale test of marginal epistasis reveals genome-wide signals of polygenic epistasis.&quot; <i>biorxiv</i>.'
---

New assays such as Perturb-seq link parallel CRISPR interventions to transcriptomic readouts, providing insight into gene regulatory networks. Causal regulatory networks can be represented by directed acyclic graphs (DAGs), but lack of identifiability and a combinatorial solution space complicate learning DAGs from observational data. Score-based methods have improved the practical scalability of inferring DAGs, but are sensitive to error variance structure. Furthermore, correction for error variance is difficult without prior knowledge of structure. We present dotears [doo-tairs], a continuous optimization framework leveraging observational and interventional data to infer causal structure, assuming a linear Structural Equation Model. dotears exploits structural consequences of hard interventions to estimate and correct for error variance structure. dotears is a provably consistent estimator of the true DAG under mild assumptions and outperforms other state-of-the-art methods in varied simulations. In real data, differential expression tests and high-confidence protein-protein interactions validate dotears-inferred edges with higher precision and recall than others.