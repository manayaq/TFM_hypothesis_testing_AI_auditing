## *Hypothesis Testing for Trustworthy AI Auditing*

### Author: *Martín Anaya Quesada*

### Supervisor: *Marios Kountouris*

****

## :question: Project Summary

Systems powered by artificial intelligence (AI) are routinely used to make decisions that have profound consequences for humans. Unlike conventional tools, failures in AI can affect people’s lives in ways that are neither transparent nor predictable, and in certain cases, they can lead to serious or even harmful outcomes. In this context, auditing emerges as a vital tool for the building of trustworthy AI.
 
This work addresses the urgent need for rigorous AI auditing frameworks by developing a theoretical and practical methodology grounded in hypothesis testing. The notebooks on this repository are used to validate our framework proposal based on the Sequential Probability Ratio Test and demostrate its potential.

Firstly, we simulate a probabilistic black-box model to validate the SPRT audit under controlled conditions, comparing results to a Neyman-Pearson fixed-sample approach. 
Secondly, a real-world audit is simulated using the German Credit dataset, training three classifiers, each of them under a different fairness-related approach, to later test them under our framework.
 
Our experiments confirm that sequential hypothesis testing yields a considerable saving in sample size compared to traditional fixed-sample approaches, without compromising the reliability of the audit. In this project, we have demonstrated that AI auditing supported by the SPRT constitutes a powerful tool for evaluating compliance across diverse applications. It enables auditors to efficiently detect biases or disparities that may remain hidden under limited or isolated observations, while also providing valuable insight into opaque or even black-box decision-making systems.


****

## :exclamation: Repository Guide
In order to download the files, navigate to your desired directory and execute the following command in a terminal:
~~~bash
$ git clone https://github.com/manayaq/TFM_hypothesis_testing_AI_auditing
~~~

Or just download the code as a `zip` file **[here](https://github.com/manayaq/TFM_hypothesis_testing_AI_auditing/archive/refs/heads/main.zip)**.

****

## :open_file_folder: Repository structure

- 01_sprt_simulation.ipynb: This notebook contains experiments with a controlled black-box model that we designed using synthetic data. These experiments aim to evaluate the Sequential Probability Ratio Test (SPRT) under reproducible and well-defined conditions, demonstrating its potential as a rigorous auditing tool.

- 02_credit_scoring_audit.ipynb: This notebook presents a simulation of a real-world audit using the German Credit Dataset, illustrating how the framework performs when auditing an actual dataset with unknown biases.


****
## :book: Documentation
The full documentation can be found in Appendix A.


****
## :memo: User guide
To run and explore the code, we recommend using Jupyter Notebook. A complete list of configurable parameters can be found in Appendix A

****

