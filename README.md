# A Quasi-Experiment to Investigating the Impact of the Strategy Design Pattern on Maintainability

> GoF Design Patterns (DPs) are optimal solutions for several recurring problems in software development. However, recent reviews found limited and contradictory evidence on the impact of DPs on maintainability. As maintenance accounts for a massive amount of development costs, understanding the impact of DPs on maintainability is key to decide whether their benefits outweigh their costs. To test the hypothesis that the Strategy DP impacts maintainability, we carried out a quasi-experiment with 19 final-year undergraduate students. Participants performed enhancement tasks in two identical versions of Java classes that differed only in that a version implemented the Strategy DP whereas another version did not. As recommended in the literature, we used effectiveness as a representative proxy of maintainability and correctness as a measure of effectiveness. We found a statistically significant correctness change between treatments. Moreover, the effect size shows that a participant is 47.7 percentage points more likely to succeed when the Strategy DP is not used. Conversely, a participant is 5.5 times more likely to fail when the DP is introduced. Unlike most related studies, our findings suggest that DPs may reduce software maintainability although these findings need to be confirmed by independent and extended replications.

This repository stores additional material to support the paper submitted to the [35th Brazilian Symposium on Software Engineering (SBES 2021)](http://cbsoft2021.joinville.udesc.br/sbes-pesquisa.php).

Here, you are going to find:

- _Analysis.html_ shows R code used to generate the analyses presented in the paper. NOTICE that to see the analyses, you need to clone or download this repository, and open the file in your browser. This file does not render automatically from github;
- _Characterisation questionnaire.pdf_ shows the form model with questions used to characterise respondents (in Portuguese). The form used was created by using Google Forms;
- _Feedback form.pdf_ shows the form model with questions used to evaluate participants' satisfaction (in Portuguese). The form used was created by using Google Forms;
- _observations.csv_ consists of the observations evaluated in the experiment;
- _participants.csv_ consists of responses from the _Characterisation questionnaire_;
- _feedback.csv_ consists of responses from the _Feedback form_;
- _Tasks.pdf_ is the description of tasks performed by participants (in Portuguese);
- _Participant consent form.pdf_ is the informed consent form (in Portuguese);
- _Introduction script.pdf_ describes the experiment to participants (in Portuguese).
- _DAO Classes_ contains original DAO classes used in the experiment. These are both the original classes from the Sireata system and the re-engineered classes that use the Strategy pattern.
