# The Art and Science of Empirical Computer Science

## Logistics

+ **Semester**: Fall 2022
+ **Instructor**: [Jimmy Lin](https://cs.uwaterloo.ca/~jimmylin/)
+ **Time & Location**: Mondays 12:30-02:50, DC 2568

## Course Description

Graduate students in computer science aspire to "do computer science" (research), but what exactly does that mean?
It involves, among a multitude of activities, reading papers, learning the "state of the art", advancing knowledge, writing papers, and (hopefully) getting them published.
Graduate students learn how to do these things under tutelage of professors, but rarely is there explicit or deliberate instruction on these myriad activities.
With a focus on _empirical_ computer science, this course covers elements that comprise the research enterprise, synthesizing both "art" &mdash; personal experiences I have accumulated over the years &mdash; as well as "science" &mdash; insights derived from quantitative analyses.
The hope is that knowledge and actionable advice from this course will help graduate students better understand research, hopefully leading to more productive and fulfilling careers.

Material for this course will draw from ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási, academic papers, as well as other sources on the web.

## Scope

Context is important.
Most of the questions and issues we grapple with in this course have no simple answer.
Nearly always, it depends on context.
As such, it is important to properly scope the coverage of this course.

Wang and Barabási attempt to paint broad strokes with their work, encompassing all of science.
However, some of their findings and recommendations may seem at odds with realities in computer science.
Much of the "art" (e.g., advice, best practices, etc.) covered in this course is drawn from my personal experience, which will of course be colored by my own background.
I am a computer scientist (actually, also a formal linguist) by training, and I work presently at the intersection of natural language processing (NLP) and information retrieval (IR), although over the years I have dabbled in other sub-disciplines of computer science as well.

For lack of a better term, I characterize the focus of this course as "empirical computer science", but it really is a shorthand for "stuff that I have worked on" and "stuff that I am familiar with".
NLP and IR can be characterized as "applied machine learning", so perhaps that's a more accurate scope.
The contents of this course will certainly be relevant to graduate students wishing to pursue these topics, and I suspect for related sub-disciplines in computer science such as data mining, or even perhaps computer vision (although I don't work in those fields).
However, I am quite certain that portions of this course will _not_ apply to, for example, theoretical machine learning and complexity.
All findings, advice, recommendations, etc. need to be properly contextualized.

## Syllabus

| Week | Date | Type | Description |
|:-----|:-----|:-----|:------------|
| [1](#week-1) | 9/12 | - | Introduction [[Slides](slides/week1.pdf)] |
| [2](#week-2) | 9/19 | "science" | The Science of Career [[Slides](slides/week2.pdf)] |
| [3](#week-3) | 9/26 | "science" | The Science of Collaboration [[Slides](slides/week3.pdf)] |
| [4](#week-4) | 10/3 | "science" | The Science of Impact [[Slides](slides/week4.pdf)] |
| [5](#week-5) | 10/17 | - | Presentation of Visualization Projects |
| [6](#week-6) | 10/24 | "science" | The Science of Impact (Still) [[Slides](slides/week6.pdf)] |
| [7](#week-7) | 10/31 | "art" | Research as a Social Process [[Slides](slides/week7.pdf)] |
| [8](#week-8) | 11/7 | "art" | Working With Your Advisor [[Slides](slides/week8.pdf)] |
| [9](#week-9) | 11/14 | "art" | On Writing Papers [[Slides](slides/week9.pdf)] |
| [10](#week-10) | 11/21 | "art" | Responsible Research |
| [11](#week-11) | 11/28 | "science" | Paper Presentations (I) |
| [12](#week-12) | 12/5 | "science" | Paper Presentations (II) |

## Grades

| Weight | Component |
|:-------|:----------|
| 15% | [Debate participation](debates.md) |
| 15% | [Paper presentation](paper-presentation.md) |
| 20% | [Visualization project](project-vis.md) |
| 40% | [Final project](project-final.md) |
| 10% | Class participation |

## Assignments

In addition to weekly preparation (readings and other material), the course will have the following assignments:

+ [Preparation and participation in a debate.](debates.md) These debates will be scattered throughout the semester, where the debate topics will be complementary to the topic of that week.
+ [Presentation of a paper on meta-research](paper-presentation.md) (Weeks 11 and 12).
+ [Visualization project](project-vis.md) due in mid-October.
+ [Final project](project-final.md) due at the end of the semester.

## Detailed Schedule

### Week 1: Introduction

**Slides:** [[PDF](slides/week1.pdf)]

For more details on normative vs. positive approaches, Wikipedia provides a good starting point: [Positivism](https://en.wikipedia.org/wiki/Positivism) and [Normativity](https://en.wikipedia.org/wiki/Normativity).

### Week 2: The Science of Career

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási, Part 1: The Science of Career (pages 5-80).

**Slides:** [[PDF](slides/week2.pdf)]

We'll be having our debate on Topic 1: How should we evaluate excellence? Quality _only_ or quality _and_ quantity?

+ Position A: Researchers should be evaluated _solely_ on the quality of their publications. Quantity is irrelevant and we shouldn't even bother counting.
+ Position B: Researchers should be evaluated on _both_ the quality _and_ quantity of their publications. High-quality publications are of course important, but quantity is also an important component of excellence.

### Week 3: The Science of Collaboration

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási, Part 2: The Science of Collaboration (pages 81-158).

**Slides:** [[PDF](slides/week3.pdf)]

We'll be having our debate on Topic 2: Should you collaborate or not?

+ Position A: Early-stage researchers should actively seek out collaborations beyond their research group. Participation in multiple research projects across many different groups builds breadth.
+ Position B: Early-stage researchers should _not_ actively seek out collaborations beyond their research group. Focusing on depth is more important than breadth.

### Week 4: The Science of Impact

**Readings** (to be completed prior to the class session): ["The Science of Science"](https://www.dashunwang.com/book/the-science-of-science) by Wang and Barabási, Part 1: The Science of Impact (pages 159-219).

**Slides:** [[PDF](slides/week4.pdf)]

We'll be having our debate on Topic 3: How should you approach open-sourcing computational artifacts associated with your work?

+ Position A: Early-stage researchers should do the minimal in open-sourcing computational artifacts that arise from their work. Doing anything more than the community norm is a waste of time and effort that could be better spent writing more papers.
+ Position B: Early-stage researchers should actively promote the adoption of computational artifacts that arise from their work, for example, contributing to popular open-source libraries. Even if this requires a lot of time (e.g., refactoring code into a production-ready state), such efforts are worthwhile.

### Week 5: Presentation of Visualization Projects

Presentation of visualization projects!

### Week 6: The Science of Impact (Still)

**Slides:** [[PDF](slides/week6.pdf)]

We'll be having our debate on Topic 4: Is social media a waste of time?
  + Position A: Early-stage researchers should actively incorporate social media use as a component of their career development. This means appropriate use of sites like Twitter, Facebook, and LinkedIn to build professional reputation, engage with the community, hear about recent work by others, etc.
  + Position B: Early-stage researchers should stay off social media. It's a complete waste of time.

Links to the case studies of impact that we discussed in class:

+ [LUCENE-2959: Implementing State of the Art Ranking for Lucene](https://issues.apache.org/jira/browse/LUCENE-2959)
+ [LUCENE-4100: Maxscore - Efficient Scoring](https://issues.apache.org/jira/browse/LUCENE-4100)
+ [LUCENE-8135: Implement Block-Max WAND](https://issues.apache.org/jira/browse/LUCENE-8135)
+ [Lucene v8.0.0 Release Notes](https://lucene.apache.org/core/8_0_0/changes/Changes.html#v8.0.0.improvements)

### Week 7: Research as a Social Process

**Slides:** [[PDF](slides/week7.pdf)]

Links to content discussed in class:

+ [LEADERSHIP LAB: The Craft of Writing Effectively](https://www.youtube.com/watch?v=vtIzMaLkCaM)
+ [Report by the ACL 2022 PC Chairs](https://docs.google.com/document/d/1NMuyNOMQD4Xt-tqh4CgiTYEkyhFAQBGFwcyfUCi2obc/edit)

Supplemental readings:

+ Becerra et al. [Maximizing the Conference Experience: Tips to Effectively Navigate Academic Conferences Early in Professional Careers.](https://link.springer.com/article/10.1007/s40617-019-00406-w), _Behavior Analysis in Practice_, 13(3):479-491, 2020.
+ Leininger et al. [Ten Simple Rules for Attending Your First Conference.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009133) _PLoS Computational Biology_, 17(7):e1009133, 2021.

### Week 8: Working With Your Advisor

**Slides:** [[PDF](slides/week8.pdf)]

Links to content discussed in class:

+ [The illustrated guide to a Ph.D.](https://matt.might.net/articles/phd-school-in-pictures/)
+ [Marriage v. The Ph.D.](https://phdcomics.com/comics/archive.php?comicid=1296)
+ [Average time spent writing one e-mail](https://phdcomics.com/comics/archive.php?comicid=1047)

### Week 9: On Writing Papers

**Slides:** [[PDF](slides/week9.pdf)]

Papers used in the abstract analysis exercise:

+ Deng et al. [ImageNet: A Large-Scale Hierarchical Image Database.](https://ieeexplore.ieee.org/document/5206848) _CVPR 2009_. (45k citations)
+ Krizhevsky et al. [ImageNet Classification with Deep Convolutional Neural Networks.](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html) _NIPS 2012_. (119k citations)
+ Devlin et al. [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.](https://aclanthology.org/N19-1423/) _NAACL 2019_. (53k citations)
+ Radford et al. [Improving Language Understanding by Generative Pre-Training.](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) (4k citations)
+ Peters et al. [Deep Contextualized Word Representations.](https://aclanthology.org/N18-1202/) _NAACL 2018_. (11k citations)

Links to content discussed in class:

+ [Writing Is Thinking](https://www.insidehighered.com/blogs/higher-ed-gamma/writing-thinking)
+ Mensh and Kording. [Ten simple rules for structuring papers](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005619) _PLoS Computational Biology_, 13(9):e1005619, 2017.
+ Baquero. [Picking Publication Targets.](https://cacm.acm.org/magazines/2022/3/258896-picking-publication-targets/fulltext) _CACM_, 65(3):10-11, 2022.

### Week 10: Responsible Research

### Week 11: Paper Presentation (I)

### Week 12: Paper Presentation (II)


