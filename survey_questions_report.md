# Analysis of survey responses on all pairs of paragraphs

We consider only the pairs for which there were 10 or more responses.  
The survey respondents were asked how much they agreed with the following statement:  
> Paragraph A is more readable than paragraph B.

To simplify analysis of the results, each pair in the results dataset has been swapped (if needed) so that Paragraph A is indeed more readable than paragraph B, meaning that there has been a readability decrease between the two versions. Survey responses have of course been swapped too when necessary.

This means that for all questions, we expect the respondents to agree with the statement (and thus select "Strongly agree" or "Somewhat agree").

## Paragraph pair 5eb233fadeb70a6af2237939
### Paragraphs
**Paragraph A**  
After obtaining all the commits with refactoring operations, we filtered out commits involved in which more than one refactoring type was applied, again to better isolate and study the effect of a single type of refactoring operation on the code naturalness. In the end, we obtained 1,448 refactoring operations from 619 projects, while no relevant refactorings are detected in the other 881 projects.  

*Flesch reading ease*: 11.415000000000019  
*Flesch&mdash;Kincaid grade level*: 19.120000000000005  

**Paragraph B**  
After obtaining all the commits with refactoring operations, we filtered out commits involved in which more than one refactoring type was applied, again to better isolate and study the effect of a single type of refactoring operation on the code naturalness.  

*Flesch reading ease*: 4.273658536585401  
*Flesch&mdash;Kincaid grade level*: 22.84878048780488  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -7.141341463414619 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +3.7287804878048765 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 1 |
| Somewhat agree | readability decreased | 2 |
| Neither agree nor disagree | readability did not change | 3 |
| Somewhat disagree | readability increased | 4 |
| Strongly disagree | readability increased | 1 |

## Paragraph pair 5eb23431deb70a6af2247fa8
### Paragraphs
**Paragraph A**  
The evaluator also had to assign a negative, neutral, or positive sentiment to the reported opinion and, finally, she had to identify in the selected part of the sentence the lexical tokes (e.g., noun, pronoun, adjective, etc.) referring to: (i) the linked library, and (ii) the quality aspect(s).  

*Flesch reading ease*: 2.1129999999999995  
*Flesch&mdash;Kincaid grade level*: 25.386000000000006  

**Paragraph B**  
The evaluator also had to assign a negative or positive sentiment to the reported opinion (this information will be used in the context of the opinion miner) and, finally, she had to identify in the selected part of the sentence the lexical tokes (e.g., noun, pronoun, adjective, etc.) referring to: (i) the linked API, and (ii) the quality aspect(s).  

*Flesch reading ease*: -6.250491803278662  
*Flesch&mdash;Kincaid grade level*: 29.285245901639342  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -8.363491803278661 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +3.8992459016393433 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 3 |
| Somewhat agree | readability decreased | 5 |
| Neither agree nor disagree | readability did not change | 3 |
| Somewhat disagree | readability increased | 1 |

## Paragraph pair 5eb23451deb70a6af224dc9a
### Paragraphs
**Paragraph A**  
Rodriguez-Perez et al. conducted two case studies and studied the Time To Notify (TNN) metric which describes how much time it takes for a bug to be notified/reported since the bug was introduced into the source code. They examine how this metric is related to software maintenance and evolution. Interestingly, they found relatively high mean values of TTN in the projects: 312 and 431 days.  

*Flesch reading ease*: 52.378173076923076  
*Flesch&mdash;Kincaid grade level*: 9.990576923076924  

**Paragraph B**  
Rodriguez-Perez et al. conducted two case studies to introduce a metric Time To Notify(TNN) which describe how much time it takes for a bug to be notified/reported since the bug was introduced into the source code and examine how this metric is related to the software maintenance and evolution.  

*Flesch reading ease*: 43.78346153846158  
*Flesch&mdash;Kincaid grade level*: 13.611538461538462  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -8.594711538461496 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +3.620961538461538 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 3 |
| Somewhat agree | readability decreased | 2 |
| Neither agree nor disagree | readability did not change | 2 |
| Somewhat disagree | readability increased | 4 |

## Paragraph pair 5eb23451deb70a6af224dcd2
### Paragraphs
**Paragraph A**  
Sliwerski et al. studied the day of the week and the size of commits on two completely different projects, Eclipse and Mozilla. They found that the commits on Friday were the buggiest, and large commits were more likely to contain bugs.  

*Flesch reading ease*: 67.09504065040652  
*Flesch&mdash;Kincaid grade level*: 7.296097560975612  

**Paragraph B**  
Sliwerski et al., studied the day of the week and size of commits for two totally different projects, Eclipse and Mozilla, and found that the commits on Fridays are buggiest and large commits are more likely to contain bugs.  

*Flesch reading ease*: 41.43461538461538  
*Flesch&mdash;Kincaid grade level*: 17.168717948717948  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -25.66042526579113 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +9.872620387742339 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 2 |
| Somewhat agree | readability decreased | 5 |
| Neither agree nor disagree | readability did not change | 3 |
| Somewhat disagree | readability increased | 2 |

## Paragraph pair 5eb23455deb70a6af2250d84
### Paragraphs
**Paragraph A**  
In most cases, a change occurred in a comment update (113), while in a few cases (12) a new comment was added. For updates, which were in most cases closely related to an inconsistency, we observed three main reasons why developers updated comments: (i) the comment was wrong before (35) (i.e., it was already wrong when it was first added, or it became outdated after a change), (ii) they updated the comment together/following a new implementation (25), (iii) they wanted to explain the actual implementation (53) in more detail.  

*Flesch reading ease*: 17.599302325581423  
*Flesch&mdash;Kincaid grade level*: 21.486976744186048  

**Paragraph B**  
In most cases, the change occurred in the form of a comment update (113), while in a few cases (12) a new comment was added. We observed three main reasons why developers update comments: (i) the comment wrongly describes the application logic (35), due to an error done when the comment was written in the first place or to an inconsistency introduced during the code evolution (in these cases we were not able to trace back to the specific cause of the problem); (ii) the comment needs to be updated as a consequence of a new implementation logic (25); (iii) the comment is improved to explain the actual implementation in more details (53).  

*Flesch reading ease*: 12.591666666666667  
*Flesch&mdash;Kincaid grade level*: 24.918148148148152  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -5.007635658914751 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +3.431171403962104 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 2 |
| Somewhat agree | readability decreased | 2 |
| Somewhat disagree | readability increased | 6 |
| Strongly disagree | readability increased | 1 |

## Paragraph pair 5eb23455deb70a6af2251726
### Paragraphs
**Paragraph A**  
Although these types of changes are typically not due to code-comment inconsistencies, we found cases where the comment contained references to other source code elements, or links to, for instance, bug reports. These cases can be considered dangerous from the inconsistency point of view, hence, we marked these as well in the taxonomy.  

*Flesch reading ease*: 38.43000000000001  
*Flesch&mdash;Kincaid grade level*: 14.60666666666667  

**Paragraph B**  
Although these types of changes are usually not performed because of code-comment inconsistencies, we found cases where the comment contained references, for example, to other source code elements or bug reports. These cases can be considered dangerous from an inconsistency point of view, as invalid/outdated references can be disturbing in the code. For example in Google Guava a commit says: "Updated a comment in ListenerCallQueue to point at SequentialExecutor instead of the deprecated SerializingExecutor wrapper interface".  

*Flesch reading ease*: 7.991153846153878  
*Flesch&mdash;Kincaid grade level*: 18.60384615384616  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -30.438846153846132 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +3.9971794871794866 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 1 |
| Somewhat agree | readability decreased | 3 |
| Neither agree nor disagree | readability did not change | 3 |
| Somewhat disagree | readability increased | 5 |

## Paragraph pair 5eb234b5deb70a6af225dbd8
### Paragraphs
**Paragraph A**  
Moreover, since our goal is to further research in the context of documentation recommender systems, the second contribution of this paper is an insight into the types of documentation that practitioners perceive as useful when confronted with specific software engineering tasks. Therefore, we formulate our second RQ as:.  

*Flesch reading ease*: 11.512500000000017  
*Flesch&mdash;Kincaid grade level*: 17.615833333333335  

**Paragraph B**  
Moreover, since our goal is to further research in the context of documentation recommender systems, the second contribution of this paper is a study with practitioners to understand what types of documentation they perceive as useful when confronted with specific software engineering tasks, to answer our second RQ:.  

*Flesch reading ease*: -9.322499999999991  
*Flesch&mdash;Kincaid grade level*: 26.48416666666667  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -20.835000000000008 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +8.868333333333332 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 2 |
| Somewhat agree | readability decreased | 5 |
| Strongly disagree | readability increased | 3 |

## Paragraph pair 5eb234b5deb70a6af225f6fd
### Paragraphs
**Paragraph A**  
Tools & Approaches. A plethora of works have been focused on supporting the automated generation and retrieval. For example, software summarization techniques and tools with the goal of providing abstractive and extractive summaries has been porposed for a diverse set of software artifacts, such as bug reports, classes and methods, unit tests, commit messages, release notes, user reviews, code snippets, and user stories.  

*Flesch reading ease*: 23.48091397849464  
*Flesch&mdash;Kincaid grade level*: 15.118387096774196  

**Paragraph B**  
Software summarization techniques and tools with the goal of providing abstractive and extractive summaries has been studied for a diverse set of software artifacts, such as bug reports, classes and methods, unit tests, commit messages, release notes, user reviews, code examples and user stories.  

*Flesch reading ease*: 4.511363636363655  
*Flesch&mdash;Kincaid grade level*: 23.56090909090909  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -18.969550342130987 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +8.442521994134895 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Somewhat agree | readability decreased | 3 |
| Neither agree nor disagree | readability did not change | 3 |
| Somewhat disagree | readability increased | 2 |
| Strongly disagree | readability increased | 2 |

## Paragraph pair 5eb234c6deb70a6af225fbb3
### Paragraphs
**Paragraph A**  
Example: The incompleteness could raise from different things such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported"). Fig 4.4 illustrate other type of missing information we observed.  

*Flesch reading ease*: 6.083571428571446  
*Flesch&mdash;Kincaid grade level*: 22.844761904761906  

**Paragraph B**  
Example: We observed different causes of incompleteness such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported").  

*Flesch reading ease*: -28.329054054054012  
*Flesch&mdash;Kincaid grade level*: 35.594324324324326  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -34.41262548262546 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +12.749562419562421 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Somewhat agree | readability decreased | 4 |
| Neither agree nor disagree | readability did not change | 2 |
| Somewhat disagree | readability increased | 4 |

## Paragraph pair 5eb234c6deb70a6af2261837
### Paragraphs
**Paragraph A**  
Interestingly, we observed that developers adopt preventative solutions to ensure the up-to-dateness of the project's documentation. For example, some projects have added documentation up-to-dateness as one of the items to check in the contribution to-do list, and others have pushed this forward by making Javadoc update mandatory for pull request acceptance.  

*Flesch reading ease*: 12.236428571428606  
*Flesch&mdash;Kincaid grade level*: 18.50857142857143  

**Paragraph B**  
Some developers adopt preventative solutions to ensure the documentation up-to-dateness, adding documentation up-to-dateness as one of the items to check in the contribution to-do list, or even pushing this forward by making Javadoc update mandatory for pull request acceptance.  

*Flesch reading ease*: -7.024999999999977  
*Flesch&mdash;Kincaid grade level*: 25.17  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -19.261428571428578 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +6.661428571428572 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 3 |
| Somewhat agree | readability decreased | 4 |
| Neither agree nor disagree | readability did not change | 2 |
| Somewhat disagree | readability increased | 2 |
| Strongly disagree | readability increased | 2 |

## Paragraph pair 5eb234c6deb70a6af2261c0c
### Paragraphs
**Paragraph A**  
Common Solution: Writing script was the most adopted solution regarding the automatic documentation deployment. Concerning the missing features there was no specific solution and individuals usually were pointed to different possible alternatives (e.g.,).  

*Flesch reading ease*: -11.967058823529385  
*Flesch&mdash;Kincaid grade level*: 19.151764705882357  

**Paragraph B**  
Common Solution: Writing script is the most adopted solution regarding the automatic documentation deployment, while regarding the missing features there was no common solution (if any) and individuals usually points to different possible alternatives (e.g.,).  

*Flesch reading ease*: -24.754999999999967  
*Flesch&mdash;Kincaid grade level*: 25.65555555555556  

### Readability deltas
| Metric | Delta | Meaning |
| --- | ---: | --- |
| *Flesch reading ease* | -12.787941176470582 | readability decreased |
| *Flesch&mdash;Kincaid grade level* | +6.503790849673206 | readability decreased |

### Survey responses
| Response | Meaning | Count |
| --- | ---: | --- |
| Strongly agree | readability decreased | 4 |
| Somewhat agree | readability decreased | 3 |
| Neither agree nor disagree | readability did not change | 2 |
| Somewhat disagree | readability increased | 1 |

