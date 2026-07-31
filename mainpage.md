---
layout: default
title: ModRef 2026
show_manual_toc: true
redirect_from: "/"
---

ModRef 2026 is the 25th in a [series of workshops on Constraint Modelling and
Reformulation](https://archive.modref.org) (see [some past contributions]({% link past-papers.md %}), or the [full archive](https://archive.modref.org/contributions/)) and is
organized as part of [CP 2026](https://cp2026.a4cp.org/) the 32nd International
Conference on Principles and Practice of Constraint Programming, held this year
in Lisbon, Portugal.  ModRef will be held on July 19th 2026, which is the day
before the main CP conference begins.  ModRef and CP are part of [FLOC
2026](https://floc26.org), a four-yearly co-location of conferences and
workshops related to logic in computer science.

The importance of modelling and model reformulation is widely recognised in many
domains, such as for CP, MIP, SAT, SMT and other kinds of general-purpose
solvers. There has been significant research effort in recent years into
modelling and model reformulation, such as automating techniques used by expert
modellers, and developing tools and techniques to target multiple types of
solvers from one model.

The purpose of ModRef is to be a forum for all kinds of work in modelling,
including new models or new modelling ideas for any amenable problem (whether a
new application or a classic benchmark), reformulation techniques to improve the
performance of models when solved by general-purpose solvers, and automated
modelling techniques, tools, and languages. We solicit original papers that
contribute to the understanding of modelling or model reformulation.

Workshop topics include:

- Application papers describing interesting problems and interesting ways to
  model them;
- Contributions to understanding modelling that could guide the manual or
  automatic formulation of models;
- Identification of the criteria that should be used in evaluating models and
  the design of pragmatic techniques that facilitate the choice and possible
  combination among alternative models;
- Design of higher-level modelling languages;
- Automatic reformulation techniques; and
- Techniques which allow automatically targeting multiple kinds of solvers from
  a single declarative model.

## Registration
Registration will be available through the [FLoC 2026 registration
page](https://floc26.org/registration)


## Important Dates

|--------------------------------------|--------------:|
| Abstract Submission                  | ~~8 May 2026~~ **11 May 2026**    |
| Paper Submission                     | 15 May 2026   |
| Notification of acceptance/rejection | 25 May 2026   |
| Camera ready version                 | 5 July 2026   |
| Workshop day                         | 19 July 2026  |

## Call for Papers 

This year ModRef will again accept paper submissions. In addition to the
presentation of research results, we especially welcome submissions of novel
(ongoing) work, recent breakthroughs, future directions, and descriptions of
interesting aspects of existing systems.

There are three types of paper submissions: 
- **Extended abstracts:** at most two pages
- **Short papers:** at most eight pages.
- **Long papers:** at most fifteen pages. 

References and appendices are not part of the page limit. 
We also accept (and encourage) non-traditional electronic submissions, such as
interactive works/tool demonstrations. In this case, please contact the chairs
to discuss the suitability of your submission for ModRef.

Papers should be submitted
through [HotCRP](https://submissions.floc26.org/modref) as PDF files following [LIPIcs
guidelines](https://submission.dagstuhl.de/series/details/5#author). There is no
requirement for papers to be anonymised before submission.

All submissions will be reviewed, and those that are well-written and make a
worthwhile contribution to the topic of the workshop will be accepted for
publication in the workshop proceedings, which will be available electronically
on this website. Accepted contributions will be allowed a time slot for a
presentation at the workshop.

**Paper submission link:** [https://submissions.floc26.org/modref](https://submissions.floc26.org/modref)


## Invited Talk

**Carlos Ansótegui**, Universitat de Lleida

### Reformulation in MaxSAT: Resolution Rules and Gadgets


*Abstract:* Reformulation is a powerful tool in MaxSAT, transforming problems into equivalent forms that are easier to analyze or solve. This talk presents two examples illustrating how reformulation can lead to both new theoretical insights and more effective solving techniques.

The first part focuses on resolution-based reformulations for Core-guided MaxSAT solving. We revisit modern SAT-based MaxSAT algorithms and show that the evolution of relaxation variables and constraints can be understood through a set of Non-CNF MaxSAT resolution rules together with the Extension rule. This perspective provides a unified view of Core-guided solvers and naturally leads to alternative solving strategies, giving rise to new MaxSAT algorithms.

The second part presents a constructive methodology for reducing SAT to Max2SAT using gadgets. Rather than relying on intricate, problem-specific constructions, the approach systematically builds compact Max2SAT instances that faithfully encode arbitrary SAT formulas. Besides providing a clearer understanding of how such reductions can be derived, this construction has practical significance: experimental results show that solving the resulting Max2SAT instances with modern MaxSAT solvers is competitive with, and in some cases outperforms, state-of-the-art SAT solvers on challenging benchmark families.

## Schedule

|------------------------------------|-------------------------------------| 
|**09:00-09:10** | **Opening** <br /> *Chair: Jordi Coll*|
| 09:00-09:10      | Welcome and Introduction \[[slides](Opening.pdf)\] <br />  *Jordi Coll (Universitat de Girona)*|
|**09:10-10:30** | **Session 1: Constraint Modelling and Propagation**| 
|09:10-09:30 | [Defining Propagators in MiniZinc](https://archive.modref.org/files/papers/2026/ModRef2026-02-Defining-Propagators-in-MiniZinc.pdf) \[[slides](slides_01.pdf)\]  <br /> *Jip J. Dekker, Peter J. Stuckey, Guido Tack, Huu Quang Tran, Markus Wagner*|
|09:30-09:50 | [Propagation Algorithms for the Minimum-Distance Constraint over Selected Points](https://archive.modref.org/files/papers/2026/ModRef2026-03-Propagation-Algorithms-for-the-Minimum-Distance-Constraint-o.pdf) <br /> *Mikael Zayenz Lagerkvist*|
|09:50-10:10 | [Machine Learning-Based Generalization Queries for Constraint Acquisition](ModRef2026-04-ML-Based-Generalization-Queries-for-Constraint-Acquisition.pdf) <br /> *Dimos Tsouros, Senne Berden, Tias Guns*|
|10:10-10:30 | [Paramita: An Extensible Framework for SATisfiability Solving](https://archive.modref.org/files/papers/2026/ModRef2026-05-Paramita-An-Extensible-Framework-for-SATisfiability-Solving.pdf) <br /> *Josep Alòs, Carlos Ansótegui, Juan Luis Esteban, Eduard Torres*|
|**10:30-11:00** | **Coffee Break** |
|**11:00-11:40**| **Session 2: Puzzles**|
|11:00-11:20| [An Interactive Application to Solve Sudoku Variant Puzzles](https://archive.modref.org/files/papers/2026/ModRef2026-06-An-Interactive-Application-to-Solve-Sudoku-Variant-Puzzles.pdf) \[[slides](slides_06.pdf)\]  <br /> *Helmut Simonis, Luis Quesada* |
|11:20-11:40| [Scaling Sudoku as a Constraint Problem](https://archive.modref.org/files/papers/2026/ModRef2026-07-Scaling-Sudoku-as-a-Constraint-Problem.pdf) <br /> *Mikael Zayenz Lagerkvist* |
| **11:40-12:20**| **Invited Talk**| 
|11:40-12:20| Reformulation in MaxSAT: Resolution Rules and Gadgets<br /> *Carlos Ansótegui* (Universitat de Lleida) |
|**12:20-13:50**|**Lunch Break**|
|**13:50-14:30**|**Session 3: Automated Generation and Reformulation**| 
|13:50-14:10| [Computing Gadgets](https://archive.modref.org/files/papers/2026/ModRef2026-08-Computing-Gadgets.pdf) <br /> *Josep Alòs, Carlos Ansótegui, Supratik Chakraborty, Eduard Torres* |
|14:10-14:30| [Towards Automated Generation of Benchmark Instances with Diverse Solver Performance](https://archive.modref.org/files/papers/2026/ModRef2026-09-Towards-Automated-Generation-of-Benchmark-Instances-with-Div.pdf) <br /> *Tianchen Wu, Ian Miguel, Nguyen Dang* |
|**14:30-15:20**|**25th Anniversary Event: Retrospective and Quiz**|
|**15:20-15:50**|**Coffee Break**| 
|**15:50-17:00**|**Session 4: Applications**| 
|15:50-16:00| [Novel Pair- and Topic-Swapping](https://archive.modref.org/files/papers/2026/ModRef2026-10-Novel-Pair-and-Topic-Swapping.pdf) <br /> *Frej Knutar Lewander, Jennifer Jennifer Gross, María Andreína Francisco Rodríguez* |
|16:00-16:20| [No More Awkward Silences with Table Talk Tuning](https://archive.modref.org/files/papers/2026/ModRef2026-11-No-More-Awkward-Silences-with-Table-Talk-Tuning.pdf) <br /> *Martin Butler, Mikael Zayenz Lagerkvist*|
|16:20-16:40| [A Simple Yet Efficient Lifted Formulation for Hard-to-Ground Planning Problems](https://archive.modref.org/files/papers/2026/ModRef2026-12-A-Simple-Yet-Efficient-Lifted-Formulation-for-Hard-to-Ground.pdf) \[[slides](slides_12.pdf)\] <br /> *Miquel Bofill, Cristina Borralleras, Josu Oca*|
|16:40-17:00| [Solution Checking with CPMpy](https://archive.modref.org/files/papers/2026/ModRef2026-13-Solution-Checking-with-CPMpy.pdf) \[[slides](slides_13.pdf)\]  <br /> *Hendrik Bierlee, Tias Guns*|


## Program Committee

|---|---| 
| Jordi Coll (Chair)                 | Universitat de Girona               |
| Felix Ulrich-Oltean (Chair)        | University of York                  |
| Özgür Akgün                        | University of St Andrews | 
| Carlos Ansótegui                   | Universitat de Lleida| 
| Hendrik Bierlee                    | KU Leuven | 
| Mun See Chang                      | University of St Andrews | 
| Sami Cherif                        | Université de Picardie Jules Verne| 
| Jip Dekker                         | Monash University | 
| Emir Devirović                     | Delft University of Technology | 
| Joan Espasa Arxer                  | University of St Andrews | 
| María Andreína Francisco Rodríguez | Uppsala University | 
| Ian Gent                           | University of St Andrews |
| Ramiz Gindullin                    | Uppsala University | 
| Tias Guns                          | KU Leuven|
| Emmanuel Hebrard                   | Université de Toulouse| 
| Christopher Jefferson              | University of St Andrews| 
| George Katsirelos                  | INRAE | 
| Kevin Leo                          | Monash University |
| Peter Nightingale                  | University of York | 
| Justin Pearson                     | Uppsala University| 
| Gilles Pesant                      | Polytechnique Montréal | 
| Pierre Schaus                      | UC Louvain| 
| Christine Solnon                   | INSA Lyon | 
| Bernardo Subercaseaux              | Carnegie Mellon University |
| Mateu Villaret                     | Universitat de Girona | 
| Allen Zhong                        | Monash University |

