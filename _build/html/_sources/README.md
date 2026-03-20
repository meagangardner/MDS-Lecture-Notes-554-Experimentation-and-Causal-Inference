Welcome to DSCI 554: Experimentation and Causal Inference
============================

This frequentist course focuses on statistical evidence from randomized experiments versus observational studies along with applications of randomization, e.g., A/B testing for website optimization.

## High-Level Goals

By the end of the course, students are expected to:

- Distinguish between experimentally-generated data and observational data, with particular reference to the strength of ensuing statistical conclusions regarding causality.
- Fit and interpret regression models for observational data, with particular reference to adjustment for potential confounding variables.
- Apply the principle of “block what you can, randomize what you cannot” in designing an A/B testing experiment.

## Teaching Team

| Position | Name | Slack Handle | 
| :---:    | :---:| :---:        | 
| Lecture/Lab Instructor | [Payman Nickchi](https://pnickchi.github.io/) | `@Payman Nickchi` | 
| Teaching Assistant | Anne-Sophie Fratzscher | `@Anne-Sophie Fratzscher (TA)` |
| Teaching Assistant | Haley Oleynik | `@Haley Oleynik (TA)` | 
| Teaching Assistant | Mahdi Asmae | `@Mahdi (TA)` | 
| Teaching Assistant | Tony Liang | `@Tony Liang (TA)` | 
| Teaching Assistant | Jared Connoy | `@Jared Connoy (TA)` | 
| Teaching Assistant | Ailar Mahdizadeh | `@Ailar Mahdizadeh` | 

## Lecture Schedule

This course occurs during **Block 6** in the 2024/25 school year.

Course notes can be accessed [**here**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/README.html). **Typically, you should review these notes before each lecture.** Moreover, there is optional reading material.

| Lecture | Topic | Optional Reading Material |
|:---------:|--------|-----------------|
| 1 | [**Multiple Comparisons**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture1_multiple_comparisons.html) | <ul><li>[This chapter](http://www.biostathandbook.com/multiplecomparisons.html) from Handbook of Biological Statistics by McDonald |
| 2 | [**Confounding and Randomized versus Non-randomized Studies**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture2_simpson_confounding.html) | <ul><li>section 1.3.5 - 1.5.2, inclusive (pages 19 - 26), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Improving Library User Experience with A/B Testing: Principles and Process](https://quod.lib.umich.edu/w/weave/12535642.0001.101?view=text;rgn=main)</li></ul> |
| 3 | [**Randomization and Blocking**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture3_randomization_and_blocking.html) | <ul><li>[Refresher on ANOVA](http://www.biostathandbook.com/twowayanova.html) from Handbook of Biological Statistics</li><li>section 1.4 Experiments from [OpenIntro Statistics](https://leanpub.com/openintro-statistics)</li></ul> |
| 4 | [**More Blocking and Power**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture4_more_blocking_and_power.html) | <ul><li>section 5.4 (pages 239 - 245), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Stopping rules and regression to the mean](https://www.statisticsdonewrong.com/regression.html)</li></ul> |
| 5 | [**More Power and Early Stopping in A/B Testing**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture5_more_power_early_stopping.html) | <ul><li>[Peeking in A/B testing at Etsy](https://codeascraft.com/2018/10/03/how-etsy-handles-peeking-in-a-b-testing/)</li></ul> |
| 6 | [**Observational Data: Stratifying and Modelling**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture6_obs_stratifying_modelling.html) |  <ul><li>[Confounding in Observational Studies Explained](https://benthamopen.com/contents/pdf/TOEPIJ/TOEPIJ-5-18.pdf)</li><li>section 8.4 (pages 386 - 395)  from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li></ul> |
| 7 | [**Observational Data: Different Sampling Schemes**](https://pages.github.ubc.ca/MDS-2024-25/DSCI_554_exper-causal-inf_students/notes/lecture7_obs_sampling_schemes.html) | <ul><li>[BU SPH on case-control sampling](https://sphweb.bumc.bu.edu/otlt/MPH-Modules/EP/EP713_Case-Control/EP713_Case-Control_print.html)</li><li>[Basics of observational study design](reading-resources/sampling-designs-bmj.pdf)</li></ul> |
| 8 | [**Matched Case-Control Scheme, Ordinal Regressors, and Final Wrap-Up**](https://pages.github.ubc.ca/MDS-2024-25/lecture8_match_constrasts_wrapup.html) | |

See the **lecture learning objectives** for a detailed breakdown of lecture-by-lecture learning objectives.

## Deliverables

This is an **assignment-based course**. The following deliverables will determine your course grade:

| Assessment       | Weight  | 
| :---:            | :---:   |
| Lab Assignment 1 | 12.5%     |
| Lab Assignment 2 | 12.5%     |
| Lab Assignment 3 | 12.5%     |
| Lab Assignment 4 | 12.5%     |
| Quiz 1           | 25%     |
| Quiz 2           | 25%     |

> **Note:** A +1% final bonus mark will be granted to everybody if the class reaches a 60% response rate (or above) in the final teaching evaluations.

## Lectures

Refer to the [MDS calendar](https://ubc-mds.github.io/calendar/) for lecture times and room numbers.

### Lab Topics and Due Dates

|      | **Lab Topic**        | **Due Date**         |
| :---:| :---:            | :---:            |
| **1**    | Simpson's Paradox, Multiple Testing, and A/B Testing<br>(Lectures 1 and 2) | 2025-03-29 06:00 p.m. |
| **2**    | Statistical Questions, Experimental Terminology, A/B Testing Communication, and Three-Way ANOVA with Blocking<br>(Lectures 3 and 4) | 2025-04-05 06:00 p.m. |
| **3**    | Power Analysis, Early Stopp ing in A/B Testing, and Causality Through Observational Studies<br>(Lectures 5 and 6) | 2025-04-13 06:00 p.m. |
| **4**    | Practicum of Causality Through an Observational Study<br>(Lectures 7 and 8) | 2025-04-20 6:00 p.m. |

## Quizzes

Refer to the [MDS calendar](https://ubc-mds.github.io/calendar/).

## Office hours

Refer to the [MDS calendar](https://ubc-mds.github.io/calendar/).

## Communication 

**Slack Channel:** [https://ubc-mds.slack.com/messages/554_exper-causal-inf](https://ubc-mds.slack.com/messages/554_exper-causal-inf)

- We will use Slack as the main communication channel.
- If you have any questions regarding the course content, lectures, labs, autograders, or any other course-related matters, we kindly request that you avoid direct messaging (DM) the instructor or TAs. Instead, please post your question on this Slack channel. This approach not only enables our TAs to respond promptly but also benefits other students who might have similar questions.
- **Response time:** We will try our best to reply to your inquiries as soon as possible during the normal working hours (9:00 a.m.- 5:00 p.m. Mon-Fri). If you send us a message outside of regular working hours, please expect a response on the next working day.


## Reference Material

* Seltman HJ, [Experimental Design and Analysis](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf), 2015.
* Oehlert GW, [A First Course in Design and Analysis of Experiments](http://users.stat.umn.edu/~gary/book/fcdae.pdf), 2010.
* O’Neil, Cathy and Schutt, Rachel. "Causality," Ch. 11 of Doing Data Science: Straight Talk from the Frontline, O’Reilly Media, 2013.
* Tang, Diane, et al. "Overlapping Experiment Infrastructure: More, Better, Faster Experimentation." Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, ACM, 2010.

Further reading:

* Work by Judea Pearl, such as "The Book of Why".

## Recommended Course Reviews

This course is taught in `R` (we will follow the [`tidyverse` style guide](https://style.tidyverse.org/index.html)) with a reasonable mathematical, statistical, and programming basis. We strongly recommend reviewing the following courses:

- *DSCI 551: Descriptive Statistics and Probability for Data Science*, for basic statistical and probabilistic concepts, and familiarity with the mathematical notation.
- *DSCI 552: Statistical Inference and Computation I*, for statistical inference concepts with a frequentist approach.
- *DSCI 561: Regression I*, for ordinary ordinary least-squares (OLS).
- *DSCI 562: Regression II*, for generalized linear models (GLMs).
- *DSCI 531: Data Visualization I*, for plotting tools using the package `ggplot2`.

## Policies

See the general [MDS policies](https://ubc-mds.github.io/policies/).

## Attribution
    
The course is built upon previous years' materials developed by previous instructors.

## License

© 2025 G. Alexi Rodríguez-Arelis, Daniel Chen, Benjamin Bloem-Redd, Tiffany Timbers, and Vincenzo Coia

Software licensed under [the MIT License](https://spdx.org/licenses/MIT.html), non-software content licensed under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See the [license file](LICENSE.md) for more information.
