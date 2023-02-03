# Books and Tutorials of Causal Inference 

Causal inference is a process of obtaining scientific understanding of **why** beyond simple descriptions or associations. 
What causal inference tries to build is an interpreter of cause and effect 
instead of a direct predictor. 
Causal inference is actively studied in many disciplines, 
including statistics, computer science, epidemiology, economics, social science, and engineering. 
Here are some really useful material I found for beginners. Most of them are available on the Internet. 

> This list will be continuingly updated. Feel free to contact me if you have better resources :)

## Textbooks by Statisticians and Economists 

These textbooks are written by prestigious scholars from statistics, economics and other fields with prominent causal applications. Some books are technical and theoretical for professional use, while others provide accessible and intuitive introductions on causality aimed at elementary readers. 

- **"Causality: Models, Reasoning, and Inference"** by Judea Pearl. Judea Pearl is a professor of computer science and statistics at the University of California, Los Angeles, who received ACM Turing Award in 2011 "for fundamental contributions to artificial intelligence through the development of a calculus for probabilistic and causal reasoning". He presents a comprehensive theory of causality, known as causal diagrams or causal graphs, to unify probabilistic, counterfactual, and structural approaches of causation. In 2018, Judea Pearl and the writer Dana Mackenzie published a nonfiction book titled **"The Book of Why: The New Science of Cause and Effect"** for a general audience. 

- **"Causal Inference for Statistics, Social, and Biomedical Sciences: An Introduction"** [[PDF](http://library.fa.ru/files/Imbens.pdf)] by Guido W. Imbens and Donald B. Rubin. Gudio W. Imbens is a professor at Stanford University, who was awarded half of the Nobel Memorial Prize in Economic Sciences jointly with Joshua D. Angrist "for their methodological contributions to the analysis of causal relationships" from natural experiments, such as the instrumental variable and regression discontinuity designs. Donald B. Rubin is an emeritus professor at Harvard University, who proposed the well-known Rubin causal model based on the framework of potential outcomes. This book starts with the notion of potential outcomes, and is organized based on distinguished assignment mechanisms. 
  
- **"Mostly Harmless Econometrics: An Empiricist's Companion"** [[link](http://www.mostlyharmlesseconometrics.com/)] and **"Mastering 'Metrics: The Path from Cause to Effect"** [[link](http://www.masteringmetrics.com/)] by Joshua D. Angrist and Jörn-Steffen Pischke. Joshua D. Angrist is a professor of economics at the Massachusetts Institute of Technology, who shared the Nobel Memorial Prize in Economics in 2021 with Guido W. Imbens. Jörn-Steffen Pischke is a professor at the London School of Economics with research interests on labour economics and economics of education. The "Harmless" book presents many useful and comprehensible applied econometric methods to answer causal questions in contemporary social sciences, including instrumental variables, differences-in-differences, regression discontinuity designs, etc. The "Mastering" book provides a more intuitive, insightful, engaging introduction of key approaches in applied econometrics. There are webcast classes [[link](https://www.aeaweb.org/conference/cont-ed/2017-webcasts), [link](https://www.aeaweb.org/conference/cont-ed/2020-webcasts)] at the American Economic Association by Alberto Abadie, Joshua Angrist, and Christopher Walters. 

- **"Introductory Econometrics: A Modern Approach"** [[PDF](https://economics.ut.ac.ir/documents/3030266/14100645/Jeffrey_M._Wooldridge_Introductory_Econometrics_A_Modern_Approach__2012.pdf)] and **"Econometric Analysis of Cross Section and Panel Data"** [[PDF](https://ipcig.org/evaluation/apoio/Wooldridge%20-%20Cross-section%20and%20Panel%20Data.pdf)] by Jeffrey M. Wooldridge. Jeffrey M. Wooldridge is a professor at Michigan State University, who contributes to theoretical analysis of cross-sectional and panel data. The "Introductory" book illustrates introductroy econometrics from the perspective of professional users with moderate mathematics, interesting data sets, and exceptional supplements (e.g., slides and toolkits). 

- **"Causal Inference: What If"** by Miguel A. Hernán and James M. Robins. Miguel A. Hernán and James M. Robins are professors of epidemiology and biostatistics at the Harvard T.H. Chan School of Public Health. This book provides a cohesive presentation of concepts and methods for causal inference with some advanced topics (e.g., causal survival analysis, time-varying treatments). Relevant data sets and computer codes are available at [[link](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)].

- **"Explanation in Causal Inference: Developments in Mediation and Interaction"** by Tyler J. VanderWeele. Tyler J. VanderWeele is a professor of epidemiology at the Harvard T.H. Chan School of Public Health. This book describes various developments in methodology on mediation and interaction to answer questions of distributions (or heterogeneity) and determinants (or mechanisms) of diseases in epidemiology. 

## Other books 

- **"Causation, Prediction, and Search"** [[PDF](https://www.cs.cmu.edu/afs/cs.cmu.edu/project/learn-43/lib/photoz/.g/web/.g/scottd/fullbook.pdf)] by Peter Spirtes, Clark Glymour, and Richard Scheines. Peter Spirtes, Clark Glymour, and Richard Scheines are professors in the Department of Philosophy at Carnegie Mellon University. This book elucidates the graphical framework of causal interpretation in the context of statistical practice with intensive mathematics. 

- **"Elements of Causal Inference: Foundation and Learning Algorithms"** [[PDF](https://library.oapen.org/bitstream/id/056a11be-ce3a-44b9-8987-a6c68fce8d9b/11283.pdf)] by Jonas Peters, Dominik Janzing, and Bernhard Scholköpf. Jonas Peters is a professor of statistics at the University of Copenhagen. Dominik Janzing is a principal research scientist at Amazon Research. Bernhard Schölkopf is a director at the Max Planck Institute for Intelligent Systems. This book was built on the graphical approach to causality, with specific interests to multivariate models and connections to machine learning. 

- **"STATS 361: Causal Inference"** [[PDF](https://web.stanford.edu/~swager/stats361.pdf)] by Stefan Wager. Stefan Wager is an associate professor of operations, information, and technology at the Stanford Graduate School of Business. He is one of the authors of causal forests and generalized random forests. STATS 361 is a graduate level class focusing on randomized and observational studies, doubly robust estimation, instrumental variables, graphical modeling, dynamic policies, etc. 

- **"Causal Inference: the Mixtape"** by Scott Cunningham. Scott Cunningham is a professor of economics at Baylor University, who studies a wide variety of topics including mental healthcare, sex work and drug policy. This book popularizes non-experimental causal evaluation methods for practitioners with electronic books [[link](https://mixtape.scunning.com/)] and coding instructions for both the R and the Stata.  

- **"Trustworthy Online Controlled Experiments: A Practical Guide to A/B Testing"** by Ron Kohavi, Diane Tang, and Ya Xu. They are leading data scientists at AirBnb, Google, and LinkedIn. This book provides practical guides for students and industry professionals on accelerating trustworthy online controlled experiments. The authors share examples, pitfalls, and advice for elementary experiments, plus deeper dives into advanced topics like observational causal studies and long-term treatment effects.    

## Online Tutorials 

- **"Machine Learning & Causal Inference: A Short Course"** [[link](https://www.youtube.com/playlist?list=PLxq_lXOUlvQAoWZEqhRqHNezS30lI49G-)] by Susan Athey, Jann Spiess, and Stefan Wager. They are professors working at the Stanford Graduate School of Business. This course is a series of videos focusing on machine learning applications to measure heterogeneous impact of interventions. 

- **"Introduction to Causal Inference: from a Machine Learning Perspective"** by Brady Neal. Brady Neal is a PhD student at Mila co-advised by Yoshua Bengio and Ioannis Mitliagkas. This is an online causal inference course [[link](https://www.bradyneal.com/causal-inference-course)] organized by Brady Neal with step-by-step instructions in the textbook, self-contained slides, and online Youtube videos. Besides, Susan Athey, Alberto Abadie, Jonas Peters, and Yoshua Bengio are invited to give guest talks on wide topics of heterogeneous treatment effects, synthetic control, and causal representation.

- **"Tutorial on Causal Inference and Counterfactual Reasoning"** [[link](https://causalinference.gitlab.io/kdd-tutorial/)] presented by Amit Sharma and Emre Kiciman from Microsoft Research, at ACM SIGKDD 2018 International Conference on Knowledge Discovery and Data Mining, London, UK.

- **"Causal Inference and Machine Learning in Practice with EconML and CausalML: Industrial Use Cases at Microsoft, TripAdvisor, Uber"** [[link](https://causal-machine-learning.github.io/kdd2021-tutorial/)] presented by researchers from Uber, Facebook, Microsoft, and Toyota Research Institute, at ACM SIGKDD 2021 International Conference on Knowledge Discovery and Data Mining. 

- **"Uplift Modeling: From Causal Inference to Personalization"** [[link](https://booking.ai/uplift-modeling-f9759e3fb51e)] by Irene Teinemaa, Javier Albert, and Dima Goldenberg from Booking.com, at 30th The Web Conference 2021.

## Other Material 

- **"An index of causality algorithms"** [[link](https://github.com/rguo12/awesome-causality-algorithms)] surveyed by Ruocheng Guo hosted on GitHub. This list is a comprehensive collect of open-source toolboxes and academic articles, covering topics of causal estimations of individuals and populations, causal discovery, out-of-distribution generalization, offline policy evaluation, and counterfactual reinforcement learning.  

- **"Causal Inference for the Brave and True"** [[link](https://matheusfacure.github.io/python-causality-handbook/landing-page.html#)] by Matheus Facure Alves. Matheus Facure Alves is a data scientist working at the fintech industry. It is an open-source material to learn impact estimation and sensitivity analysis based in Python. 