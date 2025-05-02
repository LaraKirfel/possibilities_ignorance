# Representations of what’s possible reflect others’ epistemic states

This repository contains the experiment, data, analyses and figured for the CogSci 2025 paper <a href="XXX">""</a> by Lara Kirfel ([kirfel@mpib-berlin.mpg.de](mailto:kirfel@mpib-berlin.mpg.de)), Matthew Mandelkern (mandelkern@nyu.edu) and Jonathan Phillips (Jonathan.S.Phillips@dartmouth.edu).

## Abstract

People’s judgments about what an agent can do are shaped by various constraints, including probability, morality, and normality. However, little is known about how these representations of possible actions—modal space representations—are influenced by an agent’s knowledge of their environment. Across two studies, we investigated whether epistemic constraints systematically shift modal space representations and whether these shifts affect high-level force judgments. Study 1 replicated prior findings that the first actions that come to mind are perceived as the most probable, moral, and normal, and demonstrated that these constraints apply regardless of an agent’s epistemic state. Study 2 showed that limiting an agent’s knowledge changes which actions people perceive to be possible for the agent, which in turn affects whether people judged an agent as being ``forced'' to take a particular action. These findings highlight the role of Theory of Mind in modal cognition, revealing how epistemic constraints shape perceptions of possibilities.

## Pre-registrations 

<ul>
  <li>the pre-registrations for all experiments may be accessed via the Open Science Framework <a href="https://osf.io/9tm3f/">here</a>.</li> 
  <li>separate links for each experiment:</li>
   <ul>
      <li><a href="https://osf.io/79f8m">Experiment 1</a></li>
      <li><a href="https://osf.io/8dmr4">Experiment 2a</a></li>
      <li><a href="https://osf.io/cnuqb">Experiment 2b</a></li>
      <li><a href="https://osf.io/qdkhc">Experiment 3</a></li>
    </ul>
</ul> 


## Repository structure 

```
├── data and code
│   ├── R
│   ├── data
│   ├── experiments
│   └── python
├── materials
│   ├── study 1
│   ├── study 2
├── figures
│   └── plots
└── CogSci paper
```

### code 

Contains all code including the R code for analyzing data and generating figures, written in R. 
See the rendered file <a href="https://cicl-stanford.github.io/father-dont-forgive/">here</a>.


### docs

contains all the experiment code. You can preview the experiments below:

Experiment 1: <a href="https://cicl-stanford.github.io/father-dont-forgive/experiment1/index.html?condition=1">Click here!</a>

Experiment 2a (Ignorance Condition: Likelihood 50%) <a href="https://cicl-stanford.github.io/father-dont-forgive/experiment2a/index.html?condition=1">Click here!</a>

Experiment 2b (Ignorance Condition: Likelihood 20%): <a href="https://cicl-stanford.github.io/father-dont-forgive/experiment2b/index.html?condition=1">Click here!</a>

Experiment 3: <a href="https://cicl-stanford.github.io/father-dont-forgive/experiment3/index.html?condition=1">Click here!</a>


### data 

contains anonymized data from all experiments. For each experiment:

<code>[...]study_X-responses.csv</code> contains the response data (i.e. responsibilty judgments).

<code>[...]study_X-participants.csv</code> contains demographic information and post-experiment feedback/comments from participants.

### figures 

contains all the figures from the paper (generated using the script in code/R).
