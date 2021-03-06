# Discovery of Energy Storage Materials via Bayesian optimization
## Background
Non-aqueous redox flow batteries (NRFBs) are a promising technology for stationary energy storage applications. However, after many charge/discharge cycles, the charge-carrying molecules, or redoxmers, can become damaged and thus reduce the longevity of NRFBs. One approach to circumvent such problem is to design recyclable redoxmers via mesolytic cleavage reactions. In a nutshell, mesolytic cleavage allows us trigger favorable bond breaking in a molecule at a specific applied potential, and therefore enables programmable destruction and subsequent regenertion of damaged redoxmers. As a first step toward designing sustainable NRFBs, this work aims to quickly and efficiently discover redoxmers, based on a homobenzylic ether scaffold, of desired redox potentials via Bayesian optimization
## Workflow
![alt text](https://github.com/AIScienceTutorial/Bayesian-optimization---case-study/blob/main/workflow.png?raw=true)
## File description
- **SMILES_BayesOpt.ipynb**: The Jupyter notebook to be run in this tutorial 
- _SMILES.csv_ : List of homobenzylic ether molecules using SMILES representation
- _features.csv_ : Generated physical and chemical descriptors of molecules in 'SMILES.csv' (RDKit package)
- _computedEox.csv_ : Computed oxidation potentials of molecules in 'SMILES.csv' (Density Functional Theory calculations)
## Quickstart
- Click [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AIScienceTutorial/Bayesian-optimization---case-study/blob/main/SMILES_BayesOpt.ipynb) to open and run the SMILES_BayesOpt.ipynb notebook in Google Colab
