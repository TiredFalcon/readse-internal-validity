# Dump of changes

## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af22379bf  
Flesch reading ease: +0.832690794649892  
Flesch—Kincaid grade level: +2.368135326514558  

| **Version 5eb233ebdeb70a6af22348f6** | **Version 5eb233ecdeb70a6af2234a07** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| After obtaining all the commits with refactoring operations, we filtered out commits involved in more than one refactoring type, to avoid the impact of irrelevant refactorings when assessing the naturalness change. | After obtaining all the commits with refactoring operations, we filtered out commits involved in which more than one refactoring type was applied, again to better isolate and study the effect of a single type of refactoring operation on the code naturalness. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237957  
Flesch reading ease: -15.102346014492781  
Flesch—Kincaid grade level: +2.272092391304346  

| **Version 5eb233f0deb70a6af22354c7** | **Version 5eb233f1deb70a6af2235617** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *csaba.nagy@unamur.be* |
| ------------------ | ------------------ |
| Threats to construct validity concern the relation between theory and observation. In this work, we use RMiner{.smallcaps} to detect refactorings. While the precision achieved by this tool is very high, we are aware that our results can be affected by the presence of false positives. | Threats to construct validity concern the relation between theory and observation. In this work, we use RMiner{.smallcaps} to detect refactorings. While the precision achieved by this tool is very high, we are aware that our results can be affected by the presence of false positives. Also, RMiner{.smallcaps} can identify a specific set of refactoring operations, while the definition of refactoring is broader. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237903  
Flesch reading ease: -17.61749740124739  
Flesch—Kincaid grade level: +2.892035689535689  

| **Version 5eb233e9deb70a6af2234337** | **Version 5eb233e9deb70a6af223439a** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| During software development, developers often perform refactoring operations to enhance the maintainability of source code as low-quality code usually leads to more changes and faults in the software. One interesting question here is whether refactoring is a process of improving the naturalness of source code. Intuitively, we might think the source code is easier to maintain if it is more natural, as there are much fewer "surprising" and "unfamiliar" code fragments for developers. In fact, that researchers have already disclosed that buggy code is less natural and managed to support bug localization by analyzing the code naturalness. If we can also find such type of relation between code naturalness and refactored code, we might be able to indicate which part of the code is more likely to need refactoring. | One interesting unanswered question is whether software refactoring (i.e., the activity of improving code quality without modifying the system's external behavior) can be seen as a process implicitly aimed at improving the naturalness of source code. Intuitively, we might think the source code is easier to maintain if it is more natural, as there are fewer "surprising" and "unfamiliar" code fragments for developers. Thus, it can be conjectured that developers focus their refactoring attentions on code exhibiting a low naturalness. If such a conjecture is confirmed, information about the naturalness of code components could be leveraged to support refactoring operations (e.g., by identifying code components in need of refactoring). |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af223796d  
Flesch reading ease: -11.81029370629372  
Flesch—Kincaid grade level: +2.782969030969035  

| **Version 5eb233eddeb70a6af2234bcc** | **Version 5eb233eddeb70a6af2234d71** |
| :------ | :------ |
| *b.lin@live.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| In our study, only 49.7% of the total refactorings increase the code naturalness, which is much higher in their case (67.9%). The reason behind this can be resulted by the datasets. First of all, since their dataset is very small, the difference might simply be a bias. Second, in their study, they only adopted one well-known project -- JUnit 4, while in our study, we did not consider the quality of projects. Since JUnit 4 has a huge community and is well-maintained, therefore, the refactorings might have better quality, thus resulting more naturalness increases than the projects used in our dataset. Of course, this is only an assumption, which needs to be verified carefully. However, this assumption also indicates a direction to work with: we might need to better understand the association between code quality and naturalness, which is not fully disclosed in the research community. | In our study, only 49.7% of the total refactorings increase the code naturalness, which is much lower than what has been observed in (67.9%). The reason behind this different finding could be explained by the different datasets employed in the two studies. First, the dataset used in is composed by only XX refactorings (as compared to the 1,305 considered in our study), thus possibly indicating peculiarities of the specific refactoring operations considered. Second, the XX refactorings used in have all been mined from a single, well-known project, namely JUnit 4, while in our study we extracted the studied refactorings from a variegate set of XX projects. It is possible that the "quality" of the refactorings applied in JUnit 4 is higher, thus resulting in a naturalness increase that we did not observe in our dataset. Clearly, this is only an assumption, which needs to be carefully verified. However, this assumption also indicates a direction to work with: We might need to better understand the association between code quality and naturalness, which is not fully disclosed in the research community. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237a20  
Flesch reading ease: -36.44935698447895  
Flesch—Kincaid grade level: +6.077664449371769  

| **Version 5eb233ebdeb70a6af22348f6** | **Version 5eb233ecdeb70a6af2234a07** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Our goal is to understand whether refactoring can improve the naturalness of code. For this reason, here we assess how the code naturalness is impacted by both overall and specific types of refactorings. | Our goal is to investigate whether refactoring operations increase the naturalness of the refactored code. We assess how the code naturalness is impacted (i) overall, meaning when considering all types of refactoring operations together, and (ii) by specific types of refactoring. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237917  
Flesch reading ease: -6.586032258064506  
Flesch—Kincaid grade level: +1.8626451612903203  

| **Version 5eb233e9deb70a6af223448b** | **Version 5eb233eadeb70a6af223455e** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *b.lin@live.com* |
| ------------------ | ------------------ |
| The most relevant work is the empirical study conducted by Arima et al., which uses the code naturalness as a metric to evaluate whether a refactoring operation is effective. With the assumption that appropriate refactoring should raise the naturalness of code, the authors examined 28 refactoring operations extracted from JUnit4^1 by searching for the keywords "refactor" and "clean" in commit logs and manually filtering out those commits containing more than one refactoring. As a result, 19 out of the 28 refactorings have been used in the study. Our study, while having a similar objective (i.e., studying the impact of refactoring operations on code naturalness) is performed on a much larger dataset composed of XXX refactorings extracted from XX systems. Also, we investigate the impact of refactoring operations on the code naturalness by considering the type of implemented refactoring (e.g., move method) as an independent variable to study (possibly having an effect on the "naturalness" dependent variable). | The most relevant work is the empirical study conducted by Arima et al., which uses the code naturalness as a metric to evaluate whether a refactoring operation is effective. With the assumption that appropriate refactoring should raise the naturalness of code, the authors constructed a gold set of 28 refactoring operations extracted from JUnit4^1 by searching for the keywords "refactor" and "clean" in commit logs and manually filtering out those commits containing more than one refactoring. As a result, the code naturalness increases after 19 out of the 28 refactorings, which indicates that naturalness might be a potential valid metric for evaluating the quality of refactoring. Our study, while having a similar objective (i.e., studying the impact of refactoring operations on code naturalness) is performed on a much larger dataset composed of XXX refactorings extracted from XX systems. Also, we investigate the impact of refactoring operations on the code naturalness by considering the type of implemented refactoring (e.g., move method) as an independent variable to study (possibly having an effect on the "naturalness" dependent variable). |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237939  
Flesch reading ease: +7.141341463414619  
Flesch—Kincaid grade level: -3.728780487804876  

| **Version 5eb233eddeb70a6af2234d71** | **Version 5eb233eedeb70a6af2234f10** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *b.lin@live.com* |
| ------------------ | ------------------ |
| After obtaining all the commits with refactoring operations, we filtered out commits involved in which more than one refactoring type was applied, again to better isolate and study the effect of a single type of refactoring operation on the code naturalness. | After obtaining all the commits with refactoring operations, we filtered out commits involved in which more than one refactoring type was applied, again to better isolate and study the effect of a single type of refactoring operation on the code naturalness. In the end, we obtained 1,448 refactoring operations from 619 projects, while no relevant refactorings are detected in the other 881 projects. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af223789e  
Flesch reading ease: -13.450967741935472  
Flesch—Kincaid grade level: +5.31864055299539  

| **Version 5eb233e9deb70a6af223439a** | **Version 5eb233e9deb70a6af223448b** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| The most relevant work is a empirical study conducted by Arima et al., which uses the code naturalness as a metric to evaluate whether a refactoring operation is good. With the assumption that appropriate should raise the naturalness of code, the authors examined 28 refactorings. These refactorings are extracted from JUnit4^1 by searching "refactor" and "clean" in commit logs and manually filtering out those commits containing more than one refactoring. As a result, 19 out of the 28 refactorings are considered appropriate by the naturalness metric. The generability is the major limitation of this study. Only one project and 28 refactorings are considered, thus not guaranteeing naturalness can be still valid for other refactorings. Also, the impact of the refactoring types is not investigated. | The most relevant work is the empirical study conducted by Arima et al., which uses the code naturalness as a metric to evaluate whether a refactoring operation is effective. With the assumption that appropriate refactoring should raise the naturalness of code, the authors examined 28 refactoring operations extracted from JUnit4^1 by searching for the keywords "refactor" and "clean" in commit logs and manually filtering out those commits containing more than one refactoring. As a result, 19 out of the 28 refactorings have been used in the study. Our study, while having a similar objective (i.e., studying the impact of refactoring operations on code naturalness) is performed on a much larger dataset composed of XXX refactorings extracted from XX systems. Also, we investigate the impact of refactoring operations on the code naturalness by considering the type of implemented refactoring (e.g., move method) as an independent variable to study (possibly having an effect on the "naturalness" dependent variable). |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af22379b6  
Flesch reading ease: +18.25448295635556  
Flesch—Kincaid grade level: -3.695999817958402  

| **Version 5eb233e7deb70a6af2234022** | **Version 5eb233e7deb70a6af223404a** |
| :------ | :------ |
| *b.lin@live.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| *abstract*: Recent studies have demonstrated that software is natural, that is, its source code is highly repetitive and predictable like human languages. This characteristic has been leveraged to support many software development activities, such as code completion and defect prediction. Given the promising results achieved in this area, one might wonder if refactoring operations have a positive effect on the naturalness of the source code, or whether the naturalness information can be useful for locating refactoring opportunities. With the ultimate goal of supporting refactoring activities leveraging the naturalness information, in this paper, we take the first step to investigate whether refactoring operations indeed improve the naturalness of refactored code. With a large amount of refactoring operations inspected, we observed a different effect on naturalness change for different refactoring types, and interestingly, we found that code refactoring does not necessarily increase the naturalness of the refactored code. | *abstract*: Recent studies have demonstrated that software is natural, that is, its source code is highly repetitive and predictable like human languages. Also, previous studies suggested the existence of a relationship between code quality and its naturalness, presenting empirical evidence showing that buggy code is "less natural" than non-buggy code. In this paper, we investigate this quality-naturalness relationship from a different perspective: We analyze if refactoring can improve the naturalness of code. The ultimate goal is to verify whether naturalness information could be used, in future, to support refactoring activities (*e.g.,* to locate source code areas in need of refactoring). We started by using state-of-the-art tools to mine a large dataset of refactoring operations performed in open source systems. Then, we investigate the impact of different types of refactoring operations on the naturalness of the impacted code. We found that (i) code refactoring does not necessarily increase the naturalness of the refactored code; and (ii) different refactoring operations have a different impact on the code naturalness. |


## Change in research-bin-saner2019-era
id: 5eb233fadeb70a6af2237a94  
Flesch reading ease: +22.26315789473682  
Flesch—Kincaid grade level: -3.1052631578947363  

| **Version 5eb233f5deb70a6af223621a** | **Version 5eb233f5deb70a6af22364f3** |
| :------ | :------ |
| *b.lin@live.com* | *b.lin@live.com* |
| ------------------ | ------------------ |
| ::: {#tab:statistics}
| Refactoring type    |  P-Value| Effect Size    |
|:------------------------|------------:|:-------------------|
| Extract Method          |        0.444| 0.004 (negligible) |
| Inline Method           |        0.414| 0.018 (negligible) |
| Pull Up Method          |        0.010| 0.482 (large)      |
| Rename Method           |        0.484| 0.001 (negligible) |
| Move Method             |        0.360| 0.033 (negligible) |
| Extract and Move Method |        0.260| 0.035 (negligible) |
| Pull Up Field           |        0.346| 0.165 (small)      |
| Move Field              |        0.431| 0.009 (negligible) |
| Overall                 |        0.444| 0.004 (negligible) |. | ::: {#tab:statistics}
| Refactoring type    |  P-Value| Effect Size    |
|:------------------------|------------:|:-------------------|
| Extract Method          |     < 0.001| 0.180 (small)      |
| Inline Method           |        0.202| 0.119 (small)      |
| Pull Up Method          |     < 0.001| 0.414 (medium)     |
| Rename Method           |        0.177| 0.044 (negligible) |
| Move Method             |        0.029| 0.138 (small)      |
| Extract and Move Method |     < 0.001| 0.213 (small)      |
| Pull Up Field           |        0.122| 0.258 (small)      |
| Move Field              |        0.727| 0.030 (negligible) |
| Overall                 |        0.453| 0.003 (negligible) |. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2247f58  
Flesch reading ease: -8.164838593974196  
Flesch—Kincaid grade level: +2.0083285509325677  

| **Version 5eb233f4deb70a6af2235fb8** | **Version 5eb233f5deb70a6af223633c** |
| :------ | :------ |
| *dipenta@unisannio.it* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| RQ$_2$: What is the best approach for detecting the sentiment from mined opinions? Our second RQ evaluates the accuracy of pattern-based approach in comparison with six state-of-the-art sentiment analysis tools. | RQ$_2$: What is the best approach for detecting the sentiment from mined opinions? Our second RQ evaluates the accuracy of the polarity analyzer component when exploiting (i) a pattern-based approach, or (ii) six state-of-the-art sentiment analysis tools. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2247ff6  
Flesch reading ease: +3.0397101449275397  
Flesch—Kincaid grade level: +1.3978260869565204  

| **Version 5eb233f4deb70a6af2235fb8** | **Version 5eb233f5deb70a6af223633c** |
| :------ | :------ |
| *dipenta@unisannio.it* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| RQ$_1$: What is the best approach for identifying opinion aspects in Stack Overflow discussions? This RQ aims at comparing the performance of different possible aspect identification implementations among the pattern-based approach, machine learning approaches and approaches combining patterns and machine learning. In particular, RQ$_1$ assesses how good POME is in (i) discriminating between sentences reporting/not reporting opinions, (ii) classifying opinions according to the quality attribute they refer to. | RQ$_1$: What is the best approach for identifying opinion aspects in Stack Overflow discussions? This RQ aims at comparing the performance of different implementations of the aspect classifier, and in particular those previously described and exploiting the pattern-based approach, the machine learning approach, or a combination of both (i.e., machine learning exploiting the patterns as predictor variables). RQ$_1$ assesses how good the different variations of the aspect classifier are in (i) discriminating between sentences reporting/not reporting opinions, and (ii) classifying opinions according to the quality attribute they refer to. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2248142  
Flesch reading ease: +19.223560606060573  
Flesch—Kincaid grade level: -8.353737373737374  

| **Version 5eb233eadeb70a6af22346b0** | **Version 5eb233ecdeb70a6af2234a51** |
| :------ | :------ |
| *dipenta@unisannio.it* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| The opinion miner is in charge of analyzing the sentences stored by fine-grained liker in the database to identify the ones reporting opinions and classify the quality aspect(s) discussed in them (e.g., performance) and the sentiment of the opinion (i.e.,positive, neutral, or negative). Based on what discussed in Section 2 (i.e., sentiment analysis tools are unsuitable for our purpose), we decided to follow a totally different path for the implementation of the opinion miner (but then also compare it with state-of-the-art sentiment analysis tools, as it will be shown in Section 5). | The opinion miner is in charge of analyzing the sentences classified as relevant of the APIs opinion mining (i.e., those assigned to an aspect by the aspect classifier to identify the sentiment of the opinion (i.e.,positive or negative). Based on what discussed in Section 2. Also in this case we investigated two different options for the implementation of the opinion miner, and we evaluate their performance as described in Section 4 to pick the best one for our approach. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af224816b  
Flesch reading ease: +21.874772727272727  
Flesch—Kincaid grade level: -7.150151515151515  

| **Version 5eb233efdeb70a6af2235099** | **Version 5eb233f0deb70a6af22353eb** |
| :------ | :------ |
| *dipenta@unisannio.it* | *bin.lin@usi.ch* |
| ------------------ | ------------------ |
| Finally, for RQ$_{3}$ we report and compare the percentage of opinions mined by POME and by Opiner for which the participants agreed/disagreed with the aspects and sentiments automatically assigned by the tools. | Finally, for RQ$_{3}$ we compare the results assigned by POME and Opiner with the ground truth identified by evaluators. We report the percentage of correctly identified aspects and sentiment for both both tools. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2248161  
Flesch reading ease: -18.640000000000043  
Flesch—Kincaid grade level: +2.8483333333333327  

| **Version 5eb233fddeb70a6af223837c** | **Version 5eb233fedeb70a6af22385de** |
| :------ | :------ |
| *fiorella.zampetti@unisannio.it* | *bin.lin@usi.ch* |
| ------------------ | ------------------ |
| ::: {#tab:datasetRQ3}
|               |            |            |            |            |            |            |
|:--------------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|
|               |            |            |            |            |            |            |
|               |  # pos|  # neg|  # sum|  # pos|  # neg|  # sum|
| documentation |          13|           3|          16|           9|           4|          13|
| functional    |         134|          10|         144|          23|          14|          37|
| performance   |          15|           4|          19|           5|           2|           7|
| reliability   |           5|          10|          15|           2|          26|          28|
| usability     |           7|          16|          23|         102|          45|         147|
| community     |           1|           0|           1|           2|           0|           2|
| total         |         175|          43|         218|         143|          91|         234|. | ::: {#tab:datasetRQ3}
|               |            |            |            |            |            |            |
|:--------------|-----------:|-----------:|-----------:|-----------:|-----------:|-----------:|
|               |            |            |            |            |            |            |
|               |  # pos|  # neg|  # sum|  # pos|  # neg|  # sum|
| compatibility |           7|           3|          10|           3|           0|           3|
| documentation |          13|           3|          16|           9|           4|          13|
| functional    |         134|          10|         144|          21|          14|          35|
| performance   |          15|           4|          19|           5|           2|           7|
| reliability   |           5|          10|          15|           2|          24|          26|
| usability     |           7|          16|          23|         101|          39|         140|
| community     |           1|           0|           1|           2|           0|           2|
| total         |         175|          43|         218|         143|          83|         226|. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2248294  
Flesch reading ease: -16.506289473684205  
Flesch—Kincaid grade level: +4.836260233918129  

| **Version 5eb233f4deb70a6af2235fb8** | **Version 5eb233f5deb70a6af223633c** |
| :------ | :------ |
| *dipenta@unisannio.it* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| Concerning RQ$_{2}$, we compare the accuracy of POME in assessing the sentiment of opinions with that of six state-of-the-art sentiment analysis tools: SentiStrength, NLTK, SentiStrength-SE, Stanford CoreNLP, EmoText, and Senti4SD. Note that we only conduct the comparison on 193 out of 520 sentences containing opinions, from which POME can detect the existence of opinions. The rationale behind this choice is the following. In our manual analysis we discarded sentences not reporting opinions related to API and, as a consequence, we did not label the sentiment of these sentences. However, this does not mean that all discarded sentences are neutral in terms of sentiment. Besides, we only compare the results of 193 sentences which POME can detect the existence of opinions from because our main goal is to guarantee that the sentiment of opinion related sentences extracted by the tool is correctly assigned. | Concerning RQ${2}$, we compare the accuracy of POME in assessing the sentiment of opinions with that of six state-of-the-art sentiment analysis tools: SentiStrength, NLTK, SentiStrength-SE, Stanford CoreNLP, EmoText, and Senti4SD. Note that we only conduct the comparison on the subset of 520 sentences containing opinions for which the best configuration of the aspect classifier (output of RQ${1}$) can detect the existence of opinions. The rationale behind this choice is the following. First, in our manual analysis we discarded sentences not reporting opinions related to APIs and, as a consequence, we did not label the sentiment of these sentences (thus leaving us with the 520 sentences labeled with sentiment polarity). Moreover, when envisioning POME as a tool deployed to mine opinions and assign a polarity to them, our priority is to identify the polarity analyzer implementation that is better suited for the sentences identified by the aspect classifier as opinions, since the ones discarded (i.e., do not identified as opinions) will not be shown to the POME user. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2248291  
Flesch reading ease: +5.750546265328893  
Flesch—Kincaid grade level: -1.9614158305462652  

| **Version 5eb233f6deb70a6af2236b5f** | **Version 5eb233f7deb70a6af2236e5f** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *dipenta@unisannio.it* |
| ------------------ | ------------------ |
| RQ$_1$: What is the best approach for identifying opinion aspects in Stack Overflow discussions? This RQ aims at comparing the performance of different implementations of the aspect classifier, and in particular those previously described and exploiting the pattern-based approach, the machine learning approach, or a combination of both (i.e., machine learning exploiting the patterns as predictor variables). RQ$_1$ assesses how good the different variations of the aspect classifier are in (i) discriminating between sentences reporting/not reporting opinions, and (ii) classifying opinions according to the quality attribute they refer to. | RQ$_1$: What is the best approach for identifying opinion aspects in Stack Overflow discussions? This RQ aims at comparing the performance of different implementations of the aspect classifier, i.e., the pattern-based approach or the machine learning approach, including a version employing patterns as features. RQ$_1$ assesses how good the different variations of the aspect classifier are in (i) discriminating between sentences reporting/not reporting opinions, and (ii) classifying opinions according to the quality attribute they refer. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af224806d  
Flesch reading ease: -15.53311827956992  
Flesch—Kincaid grade level: +2.8290322580645224  

| **Version 5eb233efdeb70a6af2235099** | **Version 5eb233f0deb70a6af22353eb** |
| :------ | :------ |
| *dipenta@unisannio.it* | *bin.lin@usi.ch* |
| ------------------ | ------------------ |
| RQ$_1$: How accurate is POME in mining opinions from Stack Overflow? This RQ evaluates the overall accuracy of POME in performing opinion mining on Stack Overflow. In particular, RQ$_1$ assesses how good POME is in (i) discriminating between sentences reporting/not reporting opinions (ii) classifying opinions according to the quality attribute they refer to, and (iii) assessing the sentiment of the opinion. | RQ$_1$: What is the best approach for identifying opinion aspects in Stack Overflow discussions? This RQ aims at comparing the performance of different possible aspect identification implementations among the pattern-based approach, machine learning approaches and approaches combining patterns and machine learning. In particular, RQ$_1$ assesses how good POME is in (i) discriminating between sentences reporting/not reporting opinions, (ii) classifying opinions according to the quality attribute they refer to. |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af2247fa8  
Flesch reading ease: -8.363491803278663  
Flesch—Kincaid grade level: +3.8992459016393433  

| **Version 5eb233eadeb70a6af22346b0** | **Version 5eb233ecdeb70a6af2234a51** |
| :------ | :------ |
| *dipenta@unisannio.it* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| The evaluator also had to assign a negative, neutral, or positive sentiment to the reported opinion and, finally, she had to identify in the selected part of the sentence the lexical tokes (e.g., noun, pronoun, adjective, etc.) referring to: (i) the linked library, and (ii) the quality aspect(s). | The evaluator also had to assign a negative or positive sentiment to the reported opinion (this information will be used in the context of the opinion miner) and, finally, she had to identify in the selected part of the sentence the lexical tokes (e.g., noun, pronoun, adjective, etc.) referring to: (i) the linked API, and (ii) the quality aspect(s). |


## Change in research-bin-ase2018
id: 5eb23431deb70a6af22482d2  
Flesch reading ease: -7.928088235294126  
Flesch—Kincaid grade level: -0.6331862745098036  

| **Version 5eb233efdeb70a6af2235099** | **Version 5eb233f0deb70a6af22353eb** |
| :------ | :------ |
| *dipenta@unisannio.it* | *bin.lin@usi.ch* |
| ------------------ | ------------------ |
| RQ$_2$: How does POME assess the sentiment of sentences as compared to state-of-the-art sentiment analysis tools? Our second RQ aims at comparing the accuracy of POME in identifying the sentiment of the mined opinions with that of six state-of-the-art sentiment analysis tools. | RQ$_2$: What is the best approach for detecting the sentiment from mined opinions? Our second RQ evaluates the accuracy of pattern-based approach in comparison with six state-of-the-art sentiment analysis tools. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224df24  
Flesch reading ease: -20.128220889555223  
Flesch—Kincaid grade level: +5.6229985007496275  

| **Version 5eb233f9deb70a6af223767f** | **Version 5eb233fadeb70a6af223786a** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Some subcategories include the simple removal of code that was only temporary implemented in $c_{i}$ (i.e.,Cleaup/Remove Debugging Code) or that become unnecessary after $c_{i}$'s changes (i.e.,Remove Unnecessary Code). Also, in 2 cases developers changed the code implemented in $c_{i}$ to improve its performance. For example, in the $\mathtt{project}$ project,. | Some subcategories include the simple removal of code that was only temporary implemented in $c_{i}$ (i.e.,Cleaup/Remove Debugging Code) or that become unnecessary after $c_{i}$'s changes (i.e.,Remove Unnecessary Code). Also, in 2 cases developers changed the code implemented in $c_{i}$ to improve its performance. An examples can be seen in project $\mathtt{rzwitserloot/lombok}$ where a developer fine tunes a cache clearing mechanism implemented in a previous commit by turning a variable volatile and moving the invocation for the cache clearing after a conditional check. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224e429  
Flesch reading ease: +10.301025498891363  
Flesch—Kincaid grade level: -4.542134762256712  

| **Version 5eb2341bdeb70a6af223d61d** | **Version 5eb2341cdeb70a6af223d93b** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| However, the main purpose of those code refactoring/clean up tasks is to improve the code comprehensibility without touching any documentation. Variable and method renaming refactoring (i.e., renaming a variable or method to better fit its functionality) is the most common way to make the code easier to understand. Also, variable and method extract refactoring (i.e., replacing literal values or inner method code blocks by introducing new variables or methods) is a standard approach to not only avoid existing or potential redundant code, but also better present and explain the implementation logic of the extracted code snippets. | However, the main purpose of those code refactoring/clean up tasks is to improve the code understandability. Variable and method renaming refactoring (i.e., renaming a variable or method to better reflect its functionality) is the most common way to make the code easier to comprehend. Also popular are code transformations aimed at replacing literal values with variables or splitting long functions through extract method refactoring. The latter allows not only to foster comprehensibility, but also the reusability of small code snippets. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224d977  
Flesch reading ease: -25.210000000000008  
Flesch—Kincaid grade level: +4.51  

| **Version 5eb2341bdeb70a6af223d61d** | **Version 5eb2341cdeb70a6af223d93b** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| ::: {#tab:dataset}
|                   |             |         |        |           |
|------------------:|------------:|--------:|-------:|----------:|
|                   |             |         |        |           |
|                   |             |     Mean|  Median|  Std. Dev.|
|     Java files|    1,599,323|    1,068|     360|      2,838|
|  Effective LOC|  162,243,714|  108,379|  31,392|    305,704|
|          Stars|    2,895,219|    1,930|     762|      3,455|
|        Commits|    3,323,198|    2,215|     832|      5,089|. | ::: {#tab:dataset}
|                   |             |         |        |
|------------------:|------------:|--------:|-------:|
|                   |             |         |        |
|                   |             |     Mean|  Median|
|     Java files|    1,599,323|    1,068|     360|
|  Effective LOC|  162,243,714|  108,379|  31,392|
|          Stars|    2,895,219|    1,930|     762|
|        Commits|    3,323,198|    2,215|     832|. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224dc9a  
Flesch reading ease: +8.594711538461496  
Flesch—Kincaid grade level: -3.620961538461538  

| **Version 5eb233f1deb70a6af2235653** | **Version 5eb233f1deb70a6af223587b** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Rodriguez-Perez et al. conducted two case studies to introduce a metric Time To Notify(TNN) which describe how much time it takes for a bug to be notified/reported since the bug was introduced into the source code and examine how this metric is related to the software maintenance and evolution. | Rodriguez-Perez et al. conducted two case studies and studied the Time To Notify (TNN) metric which describes how much time it takes for a bug to be notified/reported since the bug was introduced into the source code. They examine how this metric is related to software maintenance and evolution. Interestingly, they found relatively high mean values of TTN in the projects: 312 and 431 days. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224e17b  
Flesch reading ease: +28.50158639933855  
Flesch—Kincaid grade level: -5.483710801393729  

| **Version 5eb2340fdeb70a6af223b5ce** | **Version 5eb23410deb70a6af223b873** |
| :------ | :------ |
| *lanza@Lightforce2019.mobile.usilu.net* | *lanza@Lightforce2019.mobile.usilu.net* |
| ------------------ | ------------------ |
| Given the goal of our work, we considered the author date. After analyzing the distribution of these time intervals (shown in Fig. 1 with "minutes" on the x-axis), we considered the first quartile, which is exactly five minutes, as a candidate threshold to identify remedy commits: $c_{i+1}$ commits performed as quick fixes for their predecessor $c_{i}$ commit. | Then, given the commit history, our goal was to identify all pairs of subsequent commits $(c_i, c_{i+1})$ in which $c_{i+1}$ has been performed by the developer as a quick remedy fix for $c_i$. In other words, $c_{i+1}$ must (i) have been performed within a relatively short time interval from $c_{i}$; (ii) clearly be a "compensatory" fix for $c_i$. To identify the $(c_i, c_{i+1})$ pairs of interest, we adopt the following heuristic-based procedure. First, we compute the time interval between all adjacent (subsequent) commits in each system, by using the author date of each commit. In git it is possible to retrieve the author date (i.e., the date in which the change has been implemented by the author) or the committer date (i.e., the date in which the change has been committed). Given the goal of our work, we considered the author date. We analyzed the distribution of these time intervals (see Fig. 1). |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224d76a  
Flesch reading ease: -13.529761904761926  
Flesch—Kincaid grade level: +6.855687830687835  

| **Version 5eb23402deb70a6af22391ac** | **Version 5eb23403deb70a6af223948a** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| While in the cases we analyzed the issue was spotted and fixed quickly by the developer, there might be non-trivial cases in which only a subset of the test suite is executed for regression testing (e.g., due to a limited testing budget) and a non-executed broken test is not identified by the developer. For researchers, this is an opportunity to study test breaking-changes and to develop techniques able to alert the developer when a change she implemented might require a double check of (part of) the test suite. For practitioners, continuous integration practices can help in timely spotting these issues in most of cases. | While in the cases we analyzed the issue was spotted and fixed quickly by the developer, there might be non-trivial cases in which only a subset of the test suite is executed for regression testing (e.g., due to a limited testing budget) and a non-executed broken test is not identified by the developer. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224d789  
Flesch reading ease: +24.218636363636392  
Flesch—Kincaid grade level: -6.607575757575756  

| **Version 5eb23405deb70a6af22398e1** | **Version 5eb23405deb70a6af2239b92** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| While the lexical pattern defined to automatically identify remedy commits can return false positives, these have been excluded in our study through manual validation, thus do not influencing our findings in any way. | In addition to that, we used lexical patterns to identify candidate remedy commits. While these lexical patterns can return false positives, these have been excluded in our study through manual validation, thus do not influencing our findings in any way. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224df16  
Flesch reading ease: +20.862401639344284  
Flesch—Kincaid grade level: -8.77278415300546  

| **Version 5eb2341bdeb70a6af223d61d** | **Version 5eb2341cdeb70a6af223d93b** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| While these techniques cover most of the inconsistencies fixed in the Code Refactoring/Clean up category (e.g.,Rename Method for Consistency, Fix Improper Exception Name), others are left uncovered (e.g.,Fields Ordering), indicating more potential for additional research in the area of recommending coding convention fixes. |  The inconsistencies fixed with simple refactorings point to the possibility for the software engineering research community to investigate techniques able to learn coding conventions used in a given system and recommend fixes for possible violations. To the best of our knowledge, the only attempt at date has been made by Allamanis et al. with their NATURALIZE tool able to recommend meaningful identifier names and formatting guidelines. Other approaches focus only on rename refactoring suggestions. While these techniques cover most of the inconsistencies fixed in the Code Refactoring/Clean up category (e.g.,Rename Method for Consistency, Fix Improper Exception Name), others are left uncovered (e.g.,Fields Ordering), indicating more potential for additional research in the area of recommending coding convention fixes. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224dcd2  
Flesch reading ease: +25.660425265791133  
Flesch—Kincaid grade level: -9.872620387742339  

| **Version 5eb233e8deb70a6af223425c** | **Version 5eb233e9deb70a6af22342e0** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Sliwerski et al., studied the day of the week and size of commits for two totally different projects, Eclipse and Mozilla, and found that the commits on Fridays are buggiest and large commits are more likely to contain bugs. | Sliwerski et al. studied the day of the week and the size of commits on two completely different projects, Eclipse and Mozilla. They found that the commits on Friday were the buggiest, and large commits were more likely to contain bugs. |


## Change in research-fengcai-icpc2020
id: 5eb23451deb70a6af224df39  
Flesch reading ease: -19.052714741398944  
Flesch—Kincaid grade level: +5.721414900888583  

| **Version 5eb23405deb70a6af22398e1** | **Version 5eb23405deb70a6af2239b92** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Threats to construct validity concern the relation between the theory and the observation, and in this work are mainly due to the manual analysis we performed to identify the reasons behind the quick remedy changes performed by developers. To mitigate subjectivity bias in such a process, every commit was assigned to two authors who manually analyzed it independently. Then, in the case of a disagreement, a third author was assigned to the commit to solve the conflict. | Threats to construct validity concern the relation between the theory and the observation, and in this work are mainly due to the manual analysis we performed to identify the reasons behind the quick remedy changes performed by developers. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224fb08  
Flesch reading ease: +4.400142217335315  
Flesch—Kincaid grade level: -2.110509493670886  

| **Version 5eb233f5deb70a6af223647b** | **Version 5eb233f6deb70a6af2236c1b** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *dipenta@unisannio.it* |
| ------------------ | ------------------ |
| What are the characteristics of SO posts that have been reused by developers? We focus on three types properties that can be objectively measured in SO answers and, thus, compared in reused and non-reused answers. First, community aspects including, e.g., the reputation of the user who posted the answer, whether the answer has been marked as the "accepted answer" by the user who asked the question, etc. Second, the quality of the code snippet included in the answer, assessed using state-of-the-art quality metrics that can be measured on a (possibly incomplete) code snippet (e.g., cyclomatic complexity). Third, the quality of the answer's textual content, mainly assessed through metrics capturing its readability.

What is the accuracy of a machine learner-based predictor in identifying posts that are likely to be reused by developers? We use the knowledge acquired as output of RQ$_1$ to devise a machine learning approach using the factors studied in RQ$_1$ as independent variables to predict whether a given SO answer will be reused or not (dependent variable). In the context of RQ$_2$ we also investigate how the performance of the prediction approach are influenced by (i) the choice of the machine learning algorithm, (ii) the balancing of the training set, and (iii) the amount and temporal recency of the posts used to build the training set. Finally, we analyze the importance for the prediction of each independent variable. | We focus on three types properties that can be objectively measured in SO answers and, thus, compared in reused and non-reused answers. First, community aspects including, the reputation of the user who posted the answer, whether the answer has been marked as the "accepted answer" by the user who asked the question, etc. Second, the quality of the code snippet included in the answer, assessed using state-of-the-art quality metrics that can be measured on a (possibly incomplete) code snippet (e.g., cyclomatic complexity). Third, the quality of the answer's textual content, mainly assessed through metrics capturing its readability. The complete list of features is described in detail below and reported in Table [tab:factors]. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224f401  
Flesch reading ease: -36.46399166549935  
Flesch—Kincaid grade level: +14.252983471074383  

| **Version 5eb233f9deb70a6af223739f** | **Version 5eb233f9deb70a6af2237683** |
| :------ | :------ |
| *rocco.oliveto@unimol.it* | *rocco.oliveto@unimol.it* |
| ------------------ | ------------------ |
| We focus on three types properties that can be objectively measured in SO answers and, thus, compared in reused and non-reused answers. First, community aspects including, the reputation of the user who posted the answer, whether the answer has been marked as the "accepted answer" by the user who asked the question, etc. Second, the quality of the code snippet included in the answer, assessed using state-of-the-art quality metrics that can be measured on a (possibly incomplete) code snippet (e.g., cyclomatic complexity). Third, the quality of the answer's textual content, mainly assessed through metrics capturing its readability. The complete list of features is described in detail below and reported in Table [tab:factors]. | We focus on three kinds of properties that can be objectively measured in SO answers and, thus, we compared them in reused and non-reused answers: (i) community aspects including, the reputation of the user who posted the answer, whether the answer has been marked as the "accepted answer" by the user who asked the question, etc.; (ii) the quality of the code snippet included in the answer, assessed using state-of-the-art quality metrics that can be measured on a (possibly incomplete) code snippet (e.g., cyclomatic complexity); (iii) the quality of the answer's textual content, mainly assessed through metrics capturing its readability. The complete list of features is described in detail below and reported in Table [tab:factors]. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224fc1f  
Flesch reading ease: -39.02887463549706  
Flesch—Kincaid grade level: +13.80748290818202  

| **Version 5eb233f3deb70a6af2235c41** | **Version 5eb233f3deb70a6af2235de1** |
| :------ | :------ |
| *dipenta@unisannio.it* | *salgeremia@gmail.com* |
| ------------------ | ------------------ |
| # Words in Answer: number of words in the answer text; # Sentences in Answer: number of sentences in the answer text; # Characters in Answer: number of characters in the answer text; # Syllables in Answer: number of syllables in the answer text; # Complex Words in Answer: the number of words composed of at least 3 syllables; The ARI (Automated Readability Index), SMOG (Simple Measure of Gobbledygook, SMOG Index (easier version of SMOG), Flesch Kincaid, Coleman Liau, and Gunning Fog are different readability metrics to estimate the grade level needed to understand the text. The Flesch Reading Easy (also called Flesch Reading-Ease Score -- FRES) provides an index of simplicity in reading the text. A simpler text will have a higher FRE index and vice versa. | We analyzed...
Is Accepted: boolean value, 1 if the answer is accepted, 0 otherwise;
Answer Score: answer upvotes minus answer downvotes;
Comment Count: number of the answer comments;
Creation Date: date when the answer was created;
User Reputation: it is a trust measure of the crowd;
User Up Votes: number of upvotes received by a user;
User Down Votes: number of downvotes received by a user;
Is Referenced: boolean value, 1 if there is an explicit link to the answer from a GitHub file, 0 otherwise;
# GitHub Links: number of GitHub links for an answer;
Snippet LOC: number of snippet lines of code;
Snippet Complexity: calculates the cyclomatic complexity of the snippet;
Snippet Readability: @Gabriele;
# Words: number of words in the answer text;
# Sentences: number of sentences in the answer text;
# Characters: number of characters in the answer text;
# Syllables: number of syllables in the answer text;
# Complex Words: the number of words composed of at least 3 syllables;
The ARI (Automated Readability Index), SMOG (Simple Measure of Gobbledygook, SMOG Index (easier version of SMOG), Flesch Kincaid, Coleman Liau, and Gunning Fog are different readability metrics to estimate the grade level needed to understand the text. The Flesch Reading Easy (also called Flesch Reading-Ease Score -- FRES) provides an index of simplicity in reading the text. A simpler text will have a higher FRE index and vice versa. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224f700  
Flesch reading ease: +13.964782608695657  
Flesch—Kincaid grade level: -5.425797101449277  

| **Version 5eb233fbdeb70a6af2237e57** | **Version 5eb233fcdeb70a6af22380bf** |
| :------ | :------ |
| *salgeremia@gmail.com* | *salgeremia@gmail.com* |
| ------------------ | ------------------ |
| ::: {#tab:rq2-gini}
| Feature                |            MDI|
|:---------------------------|------------------:|
| Comment Count              |  0.403 $\pm$ 0.010|
| Answer Score               |  0.398 $\pm$ 0.007|
| User Reputation            |  0.393 $\pm$ 0.005|
| User Up Votes              |  0.380 $\pm$ 0.000|
| Is Accepted                |  0.376 $\pm$ 0.086|
| Snippet LOC                |  0.350 $\pm$ 0.007|
| User Down Votes            |  0.350 $\pm$ 0.007|
| # Words in Answer         |  0.310 $\pm$ 0.007|
| Snippet Readability        |  0.302 $\pm$ 0.007|
| # Sentences in Answer     |  0.286 $\pm$ 0.010|
| # Complex Words in Answer |  0.281 $\pm$ 0.003|
| Flesch Kincaid             |  0.277 $\pm$ 0.007|
| Snippet Complexity         |  0.277 $\pm$ 0.022|
| Flesch Reading Easy        |  0.269 $\pm$ 0.006|
| Coleman Liau               |  0.257 $\pm$ 0.007|
| Creation Date              |  0.239 $\pm$ 0.006|. | ::: {#tab:rq2-gini}
| Feature         |            MDI|
|:--------------------|------------------:|
| Is Accepted         |  0.502 $\pm$ 0.020|
| Comment Count       |  0.416 $\pm$ 0.006|
| Answer Score        |  0.396 $\pm$ 0.003|
| User Reputation     |  0.372 $\pm$ 0.004|
| LOC                 |  0.356 $\pm$ 0.003|
| User Down Votes     |  0.351 $\pm$ 0.002|
| Snippet Complexity  |  0.323 $\pm$ 0.009|
| Snippet Readability |  0.322 $\pm$ 0.005|
| # Words            |  0.304 $\pm$ 0.006|
| # Sentences        |  0.296 $\pm$ 0.005|
| Flesch Kincaid      |  0.284 $\pm$ 0.005|
| Flesch Reading Easy |  0.268 $\pm$ 0.003|
| Coleman Liau        |  0.260 $\pm$ 0.007|
| Creation Date       |  0.243 $\pm$ 0.006|. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224f4d2  
Flesch reading ease: +4.951202507929878  
Flesch—Kincaid grade level: -4.644737268639549  

| **Version 5eb233f9deb70a6af2237683** | **Version 5eb233fadeb70a6af22377fd** |
| :------ | :------ |
| *rocco.oliveto@unimol.it* | *rocco.oliveto@unimol.it* |
| ------------------ | ------------------ |
| Given the well-known reuse of SO posts in open source projects, we start from the assumption that posts useful in the past for somebody are likely to be useful in future, and we empirically investigate what the characteristics of SO posts that have been previously "reused" by developers are, and compare them with that of "non-reused" posts. Note that in this paper we adopt a loose definition of reuse of a post: We assume a post to have been reused if it has been mentioned (i.e., linked) at least once in the source code of an open source project hosted on GitHub. Such a link might indicate the willingness of a developer to (i) indicate the reuse of the post's code snippets, (ii) document the rationale of an implementation choice, or (iii) to simply refer the post as an interesting source of information. | Given that many SO answers have inspired solutions in open source projects, we conjecture that answers useful in the past for somebody are likely to be useful in future. Thus, we empirically investigate which are the characteristics of SO answers that have been previously "leveraged" by developers, and compare them with that of "non-leveraged" answers. In this paper we assume an answer to have been leveraged if it has been mentioned (i.e., linked) at least once in the source code of an open source project hosted on GitHub. Such a link might indicate the willingness of a developer to (i) indicate the reuse of the answer's code snippets, (ii) document the rationale of an implementation choice, or (iii) to simply refer the answer as an interesting source of information. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224f45e  
Flesch reading ease: +37.01938311688312  
Flesch—Kincaid grade level: -14.35529220779221  

| **Version 5eb233f9deb70a6af223739f** | **Version 5eb233f9deb70a6af2237683** |
| :------ | :------ |
| *rocco.oliveto@unimol.it* | *rocco.oliveto@unimol.it* |
| ------------------ | ------------------ |
| To keep into account the strong unbalancing of our dataset (i.e., we have many more not-reused than reused answers), we experimented each model when (i) not balancing the training sets, (ii) balancing the training sets by under-sampling the majority class by means of the Weka implementations of the SpreadSubSample filter, and (iii) balancing the training sets by generating artificial instances of the minority class by means of the Weka implementation of the SMOTE filter. | In our dataset we have many more not-reused than reused answers. In order to keep into account such a strong unbalancing, we experimented each machine learning technique when (i) not balancing the training sets; (ii) balancing the training sets by under-sampling the majority class by means of the Weka implementations of the SpreadSubSample filter; and (iii) balancing the training sets by generating artificial instances of the minority class by means of the Weka implementation of the SMOTE filter. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224face  
Flesch reading ease: -21.320979437229425  
Flesch—Kincaid grade level: +4.857759740259741  

| **Version 5eb233e9deb70a6af2234300** | **Version 5eb233e9deb70a6af22343ac** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *salgeremia@gmail.com* |
| ------------------ | ------------------ |
| Sojer and Henkel focused on the legal and economic risks of code reuse from the Internet. They surveyed . They found that "as is" or ad-hoc reuse is a common practice in commercial software development. | Sojer and Henkel focused on the legal and economic risks of code reuse from the Internet. They surveyed 869 professional software developers to investigate if the reuse of code snippets from internet is a common practice in commercial software development. They found that the 88% developers reuse internet code and the 19% of them consider reuse as a very important activity for their work. Furthermore, the analysis shows a growth in the importance of internet code reuse in recent years. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224f3df  
Flesch reading ease: +28.758999999999986  
Flesch—Kincaid grade level: -10.221999999999998  

| **Version 5eb23415deb70a6af223c538** | **Version 5eb23416deb70a6af223c768** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *dipenta@unisannio.it* |
| ------------------ | ------------------ |
| Figures 2 and 3 report the MCC and the Precision$_l$, respectively, obtained by the Random Forest (i) on the five different datasets, containing SO answers characterized by different recency (see the five lines having different colors), and (ii) when using different buckets for training (i.e., oldest 10%, 20%, etc., see $x$-axis). | Fig. 2 and 3 report the MCC and the Precision$_l$, respectively, obtained by the Random Forest (i) on the five different datasets, containing SO answers characterized by different recency (see the five lines having different colors), and (ii) when using different buckets for training (i.e., oldest 10%, 20%, etc., see $x$-axis). |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224fba6  
Flesch reading ease: +26.80154411764707  
Flesch—Kincaid grade level: -8.458406862745097  

| **Version 5eb23413deb70a6af223bf56** | **Version 5eb23414deb70a6af223c20b** |
| :------ | :------ |
| *dipenta@unisannio.it* | *dipenta@unisannio.it* |
| ------------------ | ------------------ |
| Since the analysis involves multiple comparisons, we adjust $p$-values using the Benjamini-Hochberg procedure , which ranks $p$-values, keeping the largest $p$-value unaltered, multiplying the second largest by the number of $p$-values divided by the rank (i.e., two), and treating the remaining ones similarly to the second. | As detailed later, these datasets (i.e., first 10%, first 20%, etc.) are also the training sets used in RQ$_2$ where, obviously, we test the machine learning models on unseen data. Therefore, when performing statistics to address RQ$_1$, we do not consider the last bucket (most recent 10%). Since the analysis involves multiple comparisons, we adjust $p$-values using the Benjamini-Hochberg procedure , which ranks $p$-values, keeping the largest $p$-value unaltered, multiplying the second largest by the number of $p$-values divided by the rank (i.e., two), and treating the remaining ones similarly to the second. |


## Change in research-msr2019-stackoverflow-reuse
id: 5eb23452deb70a6af224fd92  
Flesch reading ease: -15.08118637110016  
Flesch—Kincaid grade level: +5.126061850027369  

| **Version 5eb23429deb70a6af2245048** | **Version 5eb23429deb70a6af2245255** |
| :------ | :------ |
| *salgeremia@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Table 1 shows the number of identified clones. We found that, out of the 500 snippets considered as non-leveraged, only 30 (4%) have at least one detected clone in the considered GitHub files. Thus, while we acknowledge a certain level of noise in our analysis (i.e., misclassification of leveraged snippets as non-leveraged), such a noise should be quite limited. | We found that, out of the 500 snippets considered as non-leveraged, only 30 (4%) have at least one detected clone in the considered GitHub files. Thus, while we acknowledge a certain level of noise in our analysis (i.e., misclassification of leveraged snippets as non-leveraged), we believe that the findings reported in the following are unlikely to be substantially influenced by such a noise. |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af225135a  
Flesch reading ease: -19.081305084745765  
Flesch—Kincaid grade level: +3.2079999999999984  

| **Version 5eb233f3deb70a6af2235d74** | **Version 5eb233f4deb70a6af2235eca** |
| :------ | :------ |
| *fengcai.wen@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| The remainder of the paper is structured as follows. We review related work in Section 2. In Section 3 we describe our study design to investigate the research questions. Then our results are present in Section 4. We declare the threats to validity in Section 5 and conclude our findings in Section 6. | The remainder of the paper is structured as follows. We review related literature in Section 2. In Section 3 we describe the study design we adopted to answer our research question. The achieved results are presented in Section 4. Section 5 discuss the threats that could affect the validity of our study, while Section 6 summarizes our observations and outlines directions for future work. |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af22509a3  
Flesch reading ease: -25.180817384370016  
Flesch—Kincaid grade level: +4.050478468899524  

| **Version 5eb233ffdeb70a6af2238a69** | **Version 5eb23400deb70a6af2238d60** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| More interesting for the aim of our study are the cases in which the distributions of $MCC$ and $CCC$ are quite low, indicating possible code-comment inconsistencies introduced during software evolution. The first two change categories that leap to the eye from this perspective are Literal and Name, both with a median $MCC$ and $CCC$ lower than 10%. The literal category groups changes related to "values" in source code (e.g., boolean values, String values, etc.) while the name category represents changes to identifiers or to the names of object types. In these categories, developers rarely update comments as consequence of code changes. While updating comments when changing literal values and identifiers might not always be needed (e.g., the comment does not document the changed literal value or a renamed identifier), we found several cases of code-comment inconsistencies introduced in these situations. Concerning the Literal category, one example is from the. | While the importance of code comments is undisputed, developers do not always have the chance to carefully commenting new code and/or to update comments as consequence of code changes. This latter scenario might result in the introduction of code-comment inconsistencies, manifesting when the source code does not co-evolve with the related comments. For example, if a method comment is not updated after major changes to the method's application logic, the comment might provide misleading information to developers comprehending the method, hindering program comprehension rather than fostering it. Given the potential harmfulness of code-comment inconsistencies, several researchers studied the co-evolution of code and comments, while others proposed techniques and tools able to detect code-comment inconsistencies automatically. These techniques are able to identify specific types of code-comment inconsistencies. For example, @TCOMMENT detects inconsistencies between Javadoc comments related to null values and exceptions with the behavior implemented in the related method's body, while Fraco focuses on inconsistencies introduced as result of rename refactoring operations. Still, more research is needed in this area to increase the types of code-comment inconsistencies that can be automatically identified. Also, the empirical evidence provided by studies that pioneered the investigation of code-comment evolution is limited to the analysis of the change history of a few software systems (less than 10). |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2250ab9  
Flesch reading ease: -65.50401960784315  
Flesch—Kincaid grade level: +23.29688453159042  

| **Version 5eb233fedeb70a6af223852b** | **Version 5eb233ffdeb70a6af22387f4** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| We present the results in the form of a hierarchical taxonomy that can be seen in Figure [fig:taxonomy]. The different types of comment changes are represented either as grouping nodes or leaves in the taxonomy, and changes related to code-comment inconsistencies are marked with . The 59 different types are grouped into six main categories: (i) Comment changes related to the application logic are grouped in a separate category; (ii) code design/quality groups together changes related to source code quality or to the structure/design of the code (e.g., refactoring related to class hierarchy); (iii) process category contains changes to comments related to development/maintenance processes; (iv) formatting/wording are fixes of the style or phrasing of comments; (v) copyright/license comments are also separated into another category; (vi) finally others group together cases originating from deletion of outdated comments or addition of missing comments in order to document new code. | The different change types are grouped into six main categories: (i) Comment changes related to the Application Logic are grouped in a separate category; (ii) Code Design/Quality groups together changes related to source code quality or to the structure/design of the code (e.g., refactoring related to class hierarchy); (iii) Maintenance category contains changes to comments related to development/maintenance processes; (iv) Formatting/Readability are fixes of the style or phrasing of comments; (v) Copyright/License comments are also separated into another category; (vi) finally Others group together cases originating from deletion of outdated comments or addition of missing comments in order to document new code. |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2250d84  
Flesch reading ease: -5.007635658914751  
Flesch—Kincaid grade level: +3.4311714039621037  

| **Version 5eb23400deb70a6af2238d60** | **Version 5eb23401deb70a6af2238fcd** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| In most cases, a change occurred in a comment update (113), while in a few cases (12) a new comment was added. For updates, which were in most cases closely related to an inconsistency, we observed three main reasons why developers updated comments: (i) the comment was wrong before (35) (i.e., it was already wrong when it was first added, or it became outdated after a change), (ii) they updated the comment together/following a new implementation (25), (iii) they wanted to explain the actual implementation (53) in more detail. | In most cases, the change occurred in the form of a comment update (113), while in a few cases (12) a new comment was added. We observed three main reasons why developers update comments: (i) the comment wrongly describes the application logic (35), due to an error done when the comment was written in the first place or to an inconsistency introduced during the code evolution (in these cases we were not able to trace back to the specific cause of the problem); (ii) the comment needs to be updated as a consequence of a new implementation logic (25); (iii) the comment is improved to explain the actual implementation in more details (53). |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2250f94  
Flesch reading ease: +20.39138568896766  
Flesch—Kincaid grade level: -4.458969871510856  

| **Version 5eb23405deb70a6af2239a13** | **Version 5eb23406deb70a6af2239c61** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Categories exhibiting low values of both $MCC$ and $CCC$ and showing statistically significant lower chance to trigger comment updates when compared to most of the other categories are Array, Lambda Expression, Iteration, Literal, Method Invocation, and Name. | Categories exhibiting low values of both $MCC$ and $CCC$ and showing statistically significant lower chance to trigger comment updates when compared to most of the other categories are Array, Lambda Expression, Iteration, Literal, Method Invocation, and Name. Due to the lack of space, we only discuss two exemplar cases from these categories, while more qualitative analysis will be reported in RQ$_2$. |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af22507c3  
Flesch reading ease: -14.917948155558975  
Flesch—Kincaid grade level: +3.7783446205941225  

| **Version 5eb23400deb70a6af2238d60** | **Version 5eb23401deb70a6af2238fcd** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| For instance, in a commit of QR Code generator a comment describing how an array element of the QR code is calculated was fixed (following a copy-paste mistake). In WordPress for Android, the previously misleading comment of the "getPath()" method was replaced from "descendants must implement this to send their specific request to the stats api" to "descendants must implement this to return their specific path to the stats rest api". We also observed interesting cases when the fix was in an example code inside the comment (see). | In WordPress for Android, the previously misleading comment of the "getPath()" method was replaced from "descendants must implement this to send their specific request to the stats api" to "descendants must implement this to return their specific path to the stats rest api". We also observed interesting cases in which the comment was fixed to update a code usage example reported in the comment and not aligned with the actual code implementation (see). |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2251726  
Flesch reading ease: -30.43884615384613  
Flesch—Kincaid grade level: +3.997179487179487  

| **Version 5eb233fedeb70a6af223852b** | **Version 5eb233ffdeb70a6af22387f4** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Although these types of changes are typically not due to code-comment inconsistencies, we found cases where the comment contained references to other source code elements, or links to, for instance, bug reports. These cases can be considered dangerous from the inconsistency point of view, hence, we marked these as well in the taxonomy. | Although these types of changes are usually not performed because of code-comment inconsistencies, we found cases where the comment contained references, for example, to other source code elements or bug reports. These cases can be considered dangerous from an inconsistency point of view, as invalid/outdated references can be disturbing in the code. For example in Google Guava a commit says: "Updated a comment in ListenerCallQueue to point at SequentialExecutor instead of the deprecated SerializingExecutor wrapper interface". |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2250a67  
Flesch reading ease: +12.375021175945136  
Flesch—Kincaid grade level: -3.173974823619064  

| **Version 5eb233f1deb70a6af22355d6** | **Version 5eb233f1deb70a6af2235826** |
| :------ | :------ |
| *fengcai.wen@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Other authors focused on the evolution of code comments. Jiang and Hassan conducted a study on the evolution of comments in PostgreSQL. They investigated the trend of the percentage of commented functions in PostgreSQL over time. They divided comments into header comments and non-header comments according to the relative location of a comment with its associated function. By investigating how many header comments and non-header comments were added and deleted during the evolutionary history of PostgreSQL, their result reveals the proportion of commented functions remains constant over time. Fluri et al. conducted an empirical research on three open source systems (ArgoUML, Azureus, and JDT Core) to study how comments and source code co-evolved over time. They observed that 97% of comment changes triggered by source code changes were done in the same revision as the associated source code change, but newly added code barely got commented. In this study, an algorithm called ChangeDistiller was proposed to track fine-grained code changes down to the statement level as well as the comment changes. In Fluri's other paper, an similar approach was proposed to investigate the co-evolution between code and comment with experiments on multiple revisions of eight different software systems. They found that the ratio between the growth of code and comments is constant, however, newly added code still barely trigger the addition of comments in half of the investigated systems. The type of code entity highly influences whether the entity is commented or not. For example, if-statements are commented more often than simple statements. They also found that over 50% of the comment changes are related to source code changes and 90% of these comment changes co-evolve with the code changes simultaneously on the observed systems. Arafat et al. looked at the density of comments, which is defined as the number of comment lines divided by the number of lines of code of the same code body, in 5,229 open source projects in different programming languages. Their research indicated that successful open source projects follow a consistent practice of documenting their source code and it has led to an average comment density of about 19%. Indeed, the average comment density is dependent with programming language (the highest mean density is 25% on Java projects) but remains constant on two other dimensions such as projects size and team size. | Fluri et al. conducted an empirical research on three open source systems (ArgoUML, Azureus, and JDT Core) to study how comments and source code co-evolved over time. They observed that 97% of code changes triggered comment changes within the same revision. However, newly added code barely got commented. Fluri et al. used ChangeDistiller to track (i) fine-grained code changes down to the statement level and (ii) changes implemented in code comments. In a follow-up paper, Fluri et al. investigated the co-evolution between code and comment in eight software systems. They found that the ratio between the growth of code and comments is constant bug confirmed the previous observation about the frequent lack of comment updates for newly added code. They also found that the type of code entity impacts its likelihood of being commented (e.g.,if statements are commented more often than other types of statements). They also found that 90% of comment changes represent a simultaneous co-evolution with code changes (i.e., they change in the same revision). |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af225180e  
Flesch reading ease: -28.566224165341822  
Flesch—Kincaid grade level: +4.729697933227349  

| **Version 5eb23404deb70a6af22397c3** | **Version 5eb23405deb70a6af2239a13** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Categories exhibiting low values of both $MCC$ and $CCC$ and showing statistically significant lower chance to trigger comment updates when compared to most of the other categories are Array, Lambda Expression, Name, and Type. Since changes to the Name and Type categories are much more frequent in our dataset as compared to Array and Lambda Expression (hundreds of thousands vs hundreds), we focus our qualitative discussion on them. | Categories exhibiting low values of both $MCC$ and $CCC$ and showing statistically significant lower chance to trigger comment updates when compared to most of the other categories are Array, Lambda Expression, Iteration, Literal, Method Invocation, and Name. |


## Change in research-fengcai-icpc2019
id: 5eb23455deb70a6af2251617  
Flesch reading ease: -17.346176470588205  
Flesch—Kincaid grade level: +4.655294117647056  

| **Version 5eb23405deb70a6af2239a13** | **Version 5eb23406deb70a6af2239c61** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Code changes to the Literal and Name categories are the ones less frequently triggering comment updates. This is also confirmed by the statistical analysis (Fig. [fig:rq1-component-stats]), in which these two categories exhibit, as compared to other categories, statistically significant lower values of $MCC$ and $CCC$ accompanied by at least a "small" and in most cases by a "large" effect size^3. However, as we also observed through manual inspection, these type of changes can be responsible for the introduction of code-comment inconsistencies. The Constructor also exhibits extremely low values but, as said, only for the $MCC$ metric. | Code changes to the Array, Lambda Expression, Iteration, Literal, Method Invocation, and Name categories are the ones less frequently triggering comment updates. This is also confirmed by the statistical analysis (Fig. [fig:rq1-component-stats]), in which these categories exhibit, as compared to other categories, statistically significant lower values of $MCC$ and $CCC$ accompanied by at least a "small" and in most cases by a "large" effect size. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225c6c9  
Flesch reading ease: +22.11330404645932  
Flesch—Kincaid grade level: -5.841911202697636  

| **Version 5eb2340edeb70a6af223b1a0** | **Version 5eb2340fdeb70a6af223b545** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *m.linaresv@uniandes.edu.co* |
| ------------------ | ------------------ |
| Then, in all sentences the description standardizer (iii) converts each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and (iv) converts each gerund verb following a conjunction in third person (2nd description in Table 1). Once the descriptions are standardized, they are stored together with the related code in the ADANA knowledge base (see Figure [fig:architecture]). | The description standardizer starts by splitting the description into sentences. Then, it converts all the instances of how-to and howto (if any) to how to. For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.), it: (i) removes the first two words (e.g.,how to, how do, etc.) and (ii) removes the 3rd word if it is a personal pronoun (I, you, he, etc.). Then, in all sentences the description standardizer (iii) converts each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and (iv) converts each gerund verb following a conjunction in third person (2nd description in Table 1). Once the descriptions are standardized, they are stored together with the related code in the ADANA knowledge base (see Figure [fig:architecture]). |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225b916  
Flesch reading ease: -22.8642307692308  
Flesch—Kincaid grade level: +7.909230769230771  

| **Version 5eb23404deb70a6af223977e** | **Version 5eb23405deb70a6af2239b0f** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| We answer RQ$_{2}$ by reporting the percentage of true and false positives classified by the participants^3 as well as by discussing example cases of true and false positives, to highlight strengths and weaknesses of the ASIA clone detector. See Section 3.2. | We answer RQ$_{2}$ by reporting the percentage of true and false positives classified by the participants^1 as well as by discussing example cases of true and false positives, to highlight strengths and weaknesses of the ASIA clone detector (Section 3.2). |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225bc94  
Flesch reading ease: -108.5931680161943  
Flesch—Kincaid grade level: +43.09470310391362  

| **Version 5eb233f9deb70a6af223755b** | **Version 5eb233fbdeb70a6af2237dea** |
| :------ | :------ |
| *emad.aghajani@usi.ch* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| The description standardizer then converts the descriptions in a suitable "code comment format". For all sentences starting with "how" (e.g.,how to implement [...], how do you manage [...], etc.): (i) we remove the first two words (e.g.,how to, how do, etc.); (ii) if the 3rd word is a personal pronoun (I, you, he, etc.) we remove it; (iii) we convert each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and (iv) we convert each gerund verb following a conjunction in third person (2nd description in Table 1). | replacing all how-to and howto with how to (if the description has it);

Splitting the description into sentences (See Table  [tab:standardizer]);

For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.):

we remove the first two words ( e.g.,how to, how do, etc.);

if the 3rd word is a personal pronoun (I, you, he, etc.) we remove it;

we convert each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and

we convert each gerund verb following a conjunction in third person (2nd description in Table  1)

For other types of sentences ( e.g.,Utils for Android views, Theme and Style customization, etc.):

We find first word which is either a verb or noun or determiner and discard words before it.

We do the same we do in steps "c" and "d" for "how [...]" sentences.
:::. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225bded  
Flesch reading ease: +18.383304287208063  
Flesch—Kincaid grade level: -7.532659463227603  

| **Version 5eb23400deb70a6af2238b94** | **Version 5eb23401deb70a6af2239049** |
| :------ | :------ |
| *emad.aghajani@usi.ch* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| replacing all how-to and howto with how to (if the description has it);

Splitting the description into sentences (See Table  [tab:standardizer]);

For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.):

we remove the first two words ( e.g.,how to, how do, etc.);

if the 3rd word is a personal pronoun (I, you, he, etc.) we remove it;

we convert each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and

we convert each gerund verb following a conjunction in third person (2nd description in Table  1)

For other types of sentences ( e.g.,Utils for Android views, Theme and Style customization, etc.):

We find first word which is either a verb or noun or determiner and discard words before it.

We do the same we do in steps "c" and "d" for "how [...]" sentences.
:::. | replacing all how-to and howto with how to (if any);

Splitting the description into sentences ^2;

For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.):

we remove the first two words ( e.g.,how to, how do, etc.);

if the 3rd word is a personal pronoun (I, you, he, etc.) we remove it;

For other types of sentences ( e.g.,Utils for Android views, Theme and Style customization, etc.):

We find the first word which is either a verb, noun, or determiner and remove all words before it.

we convert each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and

we convert each gerund verb following a conjunction in third person (2nd description in Table  1)
:::. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225b830  
Flesch reading ease: -10.789007270693503  
Flesch—Kincaid grade level: +5.893742542878446  

| **Version 5eb23404deb70a6af223977e** | **Version 5eb23405deb70a6af2239b0f** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| The participants to the study have been identified using convenience sampling among personal contacts of the authors. We invited developers and CS students/professors to take part in our study by using a Web application we developed to perform the following steps. First, we collected demographic data about participants (years of experience in programming, in Java, and in Android, their current position, etc.). Each participant was then required to assess the correctness of all clones identified by ASIA for eight snippets randomly selected from the 40 object of this study. The Web application was designed to automatically balance the number of evaluations for each of the 40 snippets (i.e., the number of participants assessing the correctness of each identified clone was roughly the same). In total, we collected 501 evaluations across the 182 clones of the 39 snippets (2.78(??) evaluations per clone on average). The eight snippets were presented individually (i.e., each snippet in a different page) to participants, and each clone identified by ASIA for it was shown below the snippet with two radio buttons allowing the participant to express her assessment as: it is a clone or it is not a clone. We instructed participants to consider a clone as a true positive not only if it represented an exact copy of the related snippet (type-1 clone), but also if it differed for variable renaming (type-2), for the addition/deletion of few lines of code do not changing the main feature implemented in the snippet (type-3), or even if it represented a totally different implementation of the same functionality (type-4). Indeed, given the main goal of ADANA(i.e., documenting a piece of code to explain what it implements), any type of code clone represents a valuable source of information. | The eight snippets were presented individually (i.e., each snippet in a different page) to participants, and each clone identified by ASIA for it was shown below the snippet with two radio buttons allowing the participant to express her assessment as: it is a clone or it is not a clone. We instructed participants to consider a clone as a true positive not only if it represented an exact copy of the related snippet (type-1 clone), but also if it differed for variable renaming (type-2), for the addition/deletion of few lines of code do not changing the main feature implemented in the snippet (type-3), or even if it represented a totally different implementation of the same functionality (type-4). Indeed, given the main goal of ADANA(i.e., documenting a piece of code to explain what it implements), any type of code clone represents a valuable source of information. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225ccc7  
Flesch reading ease: +18.93789473684214  
Flesch—Kincaid grade level: -7.113157894736844  

| **Version 5eb233f1deb70a6af22357b1** | **Version 5eb233f3deb70a6af2235b96** |
| :------ | :------ |
| *emad.aghajani@usi.ch* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| We answer RQ$_{2}$ by reporting the percentage of true and false positives classified by the participants^1 as well as by discussing example cases of true and false positives, to highlight strengths and weaknesses of the ASIA clone detector. | We answer RQ$_{2}$ by reporting the percentage of true and false positives classified by the participants^1 as well as by discussing example cases of true and false positives, to highlight strengths and weaknesses of the ASIA clone detector. See Section 3.2. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225bc6a  
Flesch reading ease: -21.853249999999974  
Flesch—Kincaid grade level: +5.221833333333336  

| **Version 5eb23418deb70a6af223cb69** | **Version 5eb23419deb70a6af223cf64** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| This clearly represents a case of "false positive" comment. We did not observe any strong impact of this comment on the participants performance, likely due to the fact that it was compensated by other injected useful comments and by the still useful context hint (i.e., parsing a web page). | This clearly represents a case of "false positive" comment. We did not observe any strong impact of this comment on the participants performance, likely due to the fact that it was compensated by other injected useful comments and by the still useful context hint (i.e., parsing a web page). In addition the results show that ADANA group participants for this code snippet performed overall better (*i.e.,*17% increase in average understandability and 112 seconds on average faster in terms of speed). We also observed another similar case (see code snippet #16 in replication package) where the injected comment ( "// Runs YouTube Video.") provided only the context (i.e., showing a resource loaded from a URL in a WebView) correctly, but helped participants to perform better by increasing the correctness measure 28% and reducing the spent time by half. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225c32f  
Flesch reading ease: +112.67983167770419  
Flesch—Kincaid grade level: -44.84474307088545  

| **Version 5eb23404deb70a6af223977e** | **Version 5eb23405deb70a6af2239b0f** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| replacing all how-to and howto with how to (if any);

Splitting the description into sentences ^2;

For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.):

we remove the first two words ( e.g.,how to, how do, etc.);

if the 3rd word is a personal pronoun (I, you, he, etc.) we remove it;

For other types of sentences ( e.g.,Utils for Android views, Theme and Style customization, etc.):

We find the first word which is either a verb, noun, or determiner and remove all words before it.

we convert each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and

we convert each gerund verb following a conjunction in third person (2nd description in Table  1)
:::. | The description standardizer starts by splitting the description into sentences. Then, it converts all the instances of how-to and howto (if any) to how to. For all sentences starting with how (e.g.,how to implement [...], how do you manage [...], etc.), it: (i) removes the first two words (e.g.,how to, how do, etc.) and (ii) removes the 3rd word if it is a personal pronoun (I, you, he, etc.). Then, in all sentences the description standardizer (iii) converts each infinitive verb not following a modal verb in third person, to give the developer the feeling that the description is referring to "the code" she selects in the IDE (see e.g., the first description in Table 1); and (iv) converts each gerund verb following a conjunction in third person (2nd description in Table 1). |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225bf9c  
Flesch reading ease: +33.04596320820471  
Flesch—Kincaid grade level: -11.391329383650305  

| **Version 5eb2341cdeb70a6af223d955** | **Version 5eb2341ddeb70a6af223dd12** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| We also found a case which both adana and uncommented group performed equally (see code snippet #8 in replication package), although the injected comment ("// Reads Distinct Contacts with Contact Number and Names") describe the snippet correctly. Although we did not find any clear evidence to explain the case, we believe the complexity of code snippet (two while-structure and three if-statements and one switch-case statement) is a potential factor that persuaded participants to review the code snippet manually, skipping the code comment, which is reasonable reason considering the fact that the average spent time on this code snippet for both groups was virtually equal ($\sim$200 seconds) and relatively higher in comparison to other similar LOC code snippets in the study. | This clearly represents a case of "false positive" comment. We did not observe any strong impact of this comment on the participants performance, likely due to the fact that it was compensated by the still useful context hint (i.e., parsing a web page). A case in which the participants performed equally both with and without the comments injected by ADANA is represented by code snippet #8 (see replication package). This case is interesting since, despite the fact that the injected comment ("//Reads Distinct Contacts with Contact Number and Names") correctly describes the snippet, it did not benefit the correctness achieved by participants nor the time they spent comprehending the code. Our conjecture is that the complexity of the code snippet, including two while loops, three if statements, and one switch-case statement, probably pushed the developers to carefully inspect the whole code in both scenarios, thus reaching a similar comprehension level in roughly the same amount of time ($\sim$200 seconds) when working with the two treatments. |


## Change in research-emadpres-adana-tse
id: 5eb23476deb70a6af225bfbd  
Flesch reading ease: -27.58777508090614  
Flesch—Kincaid grade level: +10.017233009708738  

| **Version 5eb23409deb70a6af223a5cd** | **Version 5eb2340adeb70a6af223a8e8** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *michele.lanza@usi.ch* |
| ------------------ | ------------------ |
| SO documentation was a straightforward resource from where to mine code snippets and their description since it included pages related to a given topic (e.g.,device display metrics) showing snippets (and related descriptions) aimed at dealing with common tasks related to the topic (e.g., programmatically capturing the size of the device display). The code miner scraped all Android-related topics that were already grouped together in the SO documentation. Each topic contained one or more examples (i.e., pairs of $\langle code, description\rangle$), showing how to deal with tasks related to the topic (e.g., the "Intent" topic, contained 19 pairs). Some preprocessing was needed to identify in each example the related code and description. As for the code, we identify it as the text delimited by the $\mathtt{}$ HTML tags. These tags are used in SO to format the code elements in the questions/answers and, in this case, in the examples reported in the SO documentation. | SO documentation is a straightforward resource from where to mine code snippets and their description since it includes pages related to a given topic (e.g.,device display metrics) showing snippets (and related descriptions) aimed at dealing with common tasks related to the topic (e.g., programmatically capturing the size of the device display).
The code miner scrapes all Android-related topics that were already grouped together in the SO documentation. Each topic contains one or more examples (i.e., pairs of $\langle code, description\rangle$), showing how to deal with tasks related to the topic (e.g., the "Intent" topic, contained 19 pairs). |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225d63e  
Flesch reading ease: +31.74955102040815  
Flesch—Kincaid grade level: -10.390693877551023  

| **Version 5eb2341fdeb70a6af223e5f1** | **Version 5eb23420deb70a6af223e908** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *michele.lanza@usi.ch* |
| ------------------ | ------------------ |
| To overcome this deadlock, recent research initiatives have advocated for the development of automated context-aware recommender systems that automatically generate high-quality documentation, contextual to any given task at hand; and exemplified by a first wave of automated approaches for the generation and recommendation of documentation (e.g.,). | To overcome this deadlock, recent research initiatives have advocated for the development of automated context-aware recommender systems that automatically generate high-quality documentation, contextual to any given task at hand. This has led to a first wave of automated approaches for the generation and recommendation of documentation (e.g.,). |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225f65a  
Flesch reading ease: -30.841623376623374  
Flesch—Kincaid grade level: +14.487330447330443  

| **Version 5eb233fcdeb70a6af2238100** | **Version 5eb233fddeb70a6af22383bd** |
| :------ | :------ |
| *lmorenoc@colostate.edu* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| (Empirical) Studies. A variety of empirical studies have targeted software documentation artifacts aiming at (i) investigating its importance and impact in software life cycle, (ii) describing developers issues and concerns when dealing with software documentation, (iii) investigating the quality attributes required in documentation artifacts, (iv) providing guidelines and recommendations for constructing it, and (v) proposing frameworks and tools for assessing developers' concern in this context (such as cost, benefit and quality attributes). | The empirical studies in the literature can be classified based on their main goal into five broad categories: Studies (i) investigating the importance and impact of documentation in the software life cycle; (ii) describing developers issues and concerns when dealing with software documentation; (iii) investigating the quality attributes required in documentation artifacts; (iv) providing guidelines and recommendations on how to write and maintain documentation; and (v) proposing frameworks and tools for assessing developers' concerns in this context. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225d7d1  
Flesch reading ease: -27.932371794871813  
Flesch—Kincaid grade level: +7.001353276353278  

| **Version 5eb233efdeb70a6af22351b6** | **Version 5eb233f0deb70a6af2235486** |
| :------ | :------ |
| *emadpres@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Previous studies have investigated software documentation from different aspects, mainly focusing on tools & approaches and (empirical) studies. In the following, we summarize the closest ones to ours. | Previous studies have investigated software documentation from different aspects, mainly focusing on tools & approaches for manual and automated documentation, and (empirical) studies aimed at investigation different aspects such as documentation issues, developer concerns, among other. In the following, we summarize the closest ones to our with special emphasis on the empirical studies. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225dbd8  
Flesch reading ease: +20.835000000000008  
Flesch—Kincaid grade level: -8.868333333333332  

| **Version 5eb2342adeb70a6af224544c** | **Version 5eb2342bdeb70a6af2245662** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| Moreover, since our goal is to further research in the context of documentation recommender systems, the second contribution of this paper is a study with practitioners to understand what types of documentation they perceive as useful when confronted with specific software engineering tasks, to answer our second RQ:. | Moreover, since our goal is to further research in the context of documentation recommender systems, the second contribution of this paper is an insight into the types of documentation that practitioners perceive as useful when confronted with specific software engineering tasks. Therefore, we formulate our second RQ as:. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225edbf  
Flesch reading ease: +25.815647226173553  
Flesch—Kincaid grade level: -8.569321953532484  

| **Version 5eb23404deb70a6af2239559** | **Version 5eb23404deb70a6af2239808** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| The two principal lines of research in the software documentation field are devoted to (i) the development of tools & approaches to automatically generate or recommend pieces of documentation, and (ii) (empirical) studies aimed at investigating different aspects such as documentation issues and developer concerns, among others. Concerning the automated approaches, representative examples are (i) software summarization techniques providing abstractive and extractive summaries of software artifacts, such as bug reports, classes and methods, unit tests, commit messages, release notes, user reviews, code snippets, and user stories; (ii) recommender systems supporting developers in finding APIs and code usage examples, code fragments implementing specific features or, more in general, useful crowdsourced knowledge for a given implementation task. | Concerning the development of automated approaches, representative examples are the software summarization techniques that provide abstractive and/or extractive summaries of software artifacts such as bug reports, classes and methods, unit tests, code changes, user reviews, code snippets, and user stories. Equally important are the recommendation systems that support developers in finding APIs and code usage examples, code fragments implementing specific features or, more in general, useful crowdsourced knowledge for a given implementation task. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225d2ab  
Flesch reading ease: -44.55499999999998  
Flesch—Kincaid grade level: +7.456666666666667  

| **Version 5eb23437deb70a6af224af7e** | **Version 5eb23437deb70a6af224b059** |
| :------ | :------ |
| *michele.lanza@usi.ch* | *michele.lanza@usi.ch* |
| ------------------ | ------------------ |
| ::: {#tab:participantExprience}
|                  Role| <3 years | 3-5 years | 5-10 years | >10 years |         |
|-------------------------:|:-------------:|:-------------:|:--------------:|:--------------:|--------:|
|             Developer|       12      |       8       |       10       |       25       |       55|
|             Architect|       1       |       1       |        2       |       22       |       26|
|        Technical Lead|       0       |       0       |        6       |       13       |       19|
|  Tester/Test Engineer|       1       |       0       |        7       |        3       |       11|
|                Others|       4       |       2       |        4       |       25       |       35|
|                          |       18      |       11      |       29       |       88       |  146|. | ::: {#tab:participantRolePopulation}
| Role                              |  Population|  <3y|  3-5y|  5-10y|  >10y|
|:--------------------------------------|---------------:|---------:|---------:|----------:|----------:|
| Developer                         |              55|        12|         8|         10|         25|
| Architect/Technical Engineer      |              26|         1|         1|          2|         22|
| Technical Lead                    |              19|         0|         0|          6|         13|
| Test Analyst/Tester/Test Engineer |              11|         1|         0|          7|          3|
| Others                            |              35|         4|         2|          4|         25|
|                                       |         146|        18|        11|         29|         88|. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225f79b  
Flesch reading ease: +27.45450980392158  
Flesch—Kincaid grade level: -7.762794117647061  

| **Version 5eb23449deb70a6af224c8d5** | **Version 5eb2344adeb70a6af224c9c2** |
| :------ | :------ |
| *emadpres@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| In this work, we conducted two large-scale surveys with a diversified population of 146 professional software practitioners with the goal of identifying (i) documentation issues relevant to practitioners, together with the solutions that they apply when these issues arise; and (ii) documentation types useful in the context of specific software engineering tasks. For both surveys, we manually inspected the responses and qualitatively discussed our findings with the goal of highlighting lessons learned, recommendations for researchers, and confirmation/refutation of previous findings reported in the literature. | Moreover, since our goal is to further research in the context of documentation recommender systems, the second contribution of this paper is an insight into the types of documentation that practitioners perceive as useful when confronted with specific software engineering tasks. Therefore, we formulate our second RQ as:
RQ$_2$: What types of documentation are perceived as useful by practitioners in the context of specific software engineering tasks?
To answer these two research questions, we performed two surveys with 146 professional software practitioners. In the first survey, we focused on the documentation issues that practitioners perceive as more severe, together with the solutions that they apply when these issues arise. In the second survey, we studied the types of documentation that practitioners consider important given specific tasks. Most participants (125) are from a multinational corporation active in automation technology, others (21) have been recruited in specialized online forums. The result is a diversified population of practitioners acting in various roles (e.g., developers, testers). |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225f6fd  
Flesch reading ease: +18.969550342130987  
Flesch—Kincaid grade level: -8.442521994134895  

| **Version 5eb233efdeb70a6af22351b6** | **Version 5eb233f0deb70a6af2235486** |
| :------ | :------ |
| *emadpres@gmail.com* | *gabriele.bavota@gmail.com* |
| ------------------ | ------------------ |
| Software summarization techniques and tools with the goal of providing abstractive and extractive summaries has been studied for a diverse set of software artifacts, such as bug reports, classes and methods, unit tests, commit messages, release notes, user reviews, code examples and user stories. | Tools & Approaches. A plethora of works have been focused on supporting the automated generation and retrieval. For example, software summarization techniques and tools with the goal of providing abstractive and extractive summaries has been porposed for a diverse set of software artifacts, such as bug reports, classes and methods, unit tests, commit messages, release notes, user reviews, code snippets, and user stories. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225f837  
Flesch reading ease: +25.674912850307578  
Flesch—Kincaid grade level: -10.909757347915239  

| **Version 5eb23404deb70a6af2239559** | **Version 5eb23404deb70a6af2239808** |
| :------ | :------ |
| *gabriele.bavota@gmail.com* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| The empirical studies in the literature can be classified based on their main goal into five broad categories: Studies (i) investigating the importance and impact of documentation in the software life cycle; (ii) describing developers issues and concerns when dealing with software documentation; (iii) investigating the quality attributes required in documentation artifacts; (iv) providing guidelines and recommendations on how to write and maintain documentation; and (v) proposing frameworks and tools for assessing developers' concerns in this context. | Closer to our work is the empirical research on software documentation aspects, particularly the studies that directly interview or survey software practitioners. These empirical studies can be broadly classified into five categories: (i) studies investigating the importance and impact of documentation in the software life cycle; (ii) studies describing developers' issues and concerns when dealing with software documentation; (iii) studies investigating the quality attributes required in documentation artifacts; (iv) studies providing guidelines and recommendations on how to write and maintain documentation; and (v) studies proposing frameworks and tools for assessing developers' concerns in this context. |


## Change in research-emadpres-icse2020
id: 5eb234b5deb70a6af225f9a4  
Flesch reading ease: +21.593513740618334  
Flesch—Kincaid grade level: -8.806441928360478  

| **Version 5eb233fcdeb70a6af2238100** | **Version 5eb233fddeb70a6af22383bd** |
| :------ | :------ |
| *lmorenoc@colostate.edu* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| Although previous studies such as have investigated documentation issues and documentation types, there is still a gap when determining which are the more relevant ones --- both issues and documentation types --- for practitioners and their rationale. Some of previous studies are focused on the issues experienced with specific types of documentation, or only during a certain development phase; in other cases, the purpose of the study was not to find the most relevant issues but to be comprehensive when reporting all the documentations issues experienced by developers; and while there are studies reporting the usefulness of certain types of documentation based on studies with developers, those studies involved a small sample of participants, doesn't take practitioners' perspective into account, covered few documentation types or quality attributes, or focused on listing documentation preferences of developers during a certain development phase and did not provide rationale for the preferences. In this study we address those limitations of previous studies by analyzing what are the most relevant documentation issues and the most useful documentation types for developers, while trying to be comprehensive in terms of the issues, documentation types, and developers activities. We not only report the issues and documentation types, but also the developers reasons for their choices. Besides, we also present the common solutions that practitioners adopt when dealing with each documentation issue. | Finally, a number of studies exploited a mining-based strategy for identifying documentation issues discussed by practitioners, by developers or by application users. In the most recent one, Aghajani et al. presented an extensive taxonomy of 162 types of issues faced by developers and users of software documentation, defined through the manual analysis of 878 documentation-related artifacts from four different sources (e.g., Stack Overflow discussions, pull requests). We start from the work by Aghajani et al. to assess the relevance of the documentation issues presented in their taxonomy, something completely neglected in their work. In other words, while Aghajani et al. main target was the definition of a comprehensive taxonomy of documentation issues, our goal is to understand whether (and which of) those issues are relevant for practitioners. As compared to previous work looking at documentation issues from the practitioners' perspective, while they focused on a specific type of documentation (i.e., API documentation), we consider a wide set of 51 documentation issues affecting several types of documentation. |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af225fee2  
Flesch reading ease: +15.107128205128191  
Flesch—Kincaid grade level: -6.744461538461536  

| **Version 5eb2343ddeb70a6af224b835** | **Version 5eb2343edeb70a6af224b919** |
| :------ | :------ |
| *lmorenoc@colostate.edu* | *lmorenoc@colostate.edu* |
| ------------------ | ------------------ |
| Referring to deprecated information is also one of the main reasons for up-to-dateness issues, and can affect several types of documentation in different ways: It includes having deprecated information in the project's website (e.g.,**"homepage recommends deprecated commands"), outdated copyright information and version numbers in the code base, as well as outdated references (e.g., links to old versions of the system in the documentation), which was the most prevalent issue within this category. For example, one user reported that "the example linked in the documentation is using the 3.x version of the API, and that may be confusing to readers". | Referring to deprecated information is another reason for up-to-dateness issues and can affect several types of documentation in different ways. It includes having deprecated information in the project's website (e.g.,**"homepage recommends deprecated commands"), outdated copyright information and version numbers in the code base, as well as outdated references (e.g., links to old versions of the system in the documentation), which was the most prevalent issue within this category. For example, one user reported that "the example linked in the documentation is using the 3.x version of the API, and that may be confusing to readers". |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af225fed1  
Flesch reading ease: +53.9942759295499  
Flesch—Kincaid grade level: -18.710371819960862  

| **Version 5eb23452deb70a6af224eb1f** | **Version 5eb23452deb70a6af224fe86** |
| :------ | :------ |
| *lmorenoc@colostate.edu* | *michele.lanza@usi.ch* |
| ------------------ | ------------------ |
| On the other side, documentation has been analyzed with a diversity of empirical studies that (i) report evidence of its importance and impact in the software cycle development, (ii) describe problems developers face when dealing with it, (iii) list quality attributes required in software documentation, (iv) provide recommendations for constructing it (including standards) , or (v) propose frameworks and tools for evaluating documentation concerns such as cost, benefit and quality attributes of software documentation. | (Empirical) Studies. Software documentation has been analyzed in diverse empirical studies that (i) report evidence of its importance and impact in the software life cycle, (ii) describe problems that developers face when dealing with it, (iii) list quality attributes required in documentation, (iv) provide recommendations for constructing it (including standards), and (v) propose frameworks and tools for evaluating documentation concerns such as cost, benefit and quality attributes. Due to space limitations we summarize the closest ones to our study in Table [tab:related_SwTechDocWorks]. |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af2261c0c  
Flesch reading ease: +12.787941176470582  
Flesch—Kincaid grade level: -6.503790849673205  

| **Version 5eb233efdeb70a6af2235219** | **Version 5eb233f0deb70a6af2235577** |
| :------ | :------ |
| *olvegam@unillanos.edu.co* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| Common Solution: Writing script is the most adopted solution regarding the automatic documentation deployment, while regarding the missing features there was no common solution (if any) and individuals usually points to different possible alternatives (e.g.,). | Common Solution: Writing script was the most adopted solution regarding the automatic documentation deployment. Concerning the missing features there was no specific solution and individuals usually were pointed to different possible alternatives (e.g.,). |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af2260571  
Flesch reading ease: +35.3009984984985  
Flesch—Kincaid grade level: -13.246114447781117  

| **Version 5eb233fddeb70a6af2238317** | **Version 5eb233fedeb70a6af22384a6** |
| :------ | :------ |
| *emad.aghajani@usi.ch* | *emad.aghajani@usi.ch* |
| ------------------ | ------------------ |
| Example: We observed different causes of incompleteness such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported"). | Completeness accounts for %53 of issues in this section. We observed different causes of incompleteness such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported"). |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af225fe6f  
Flesch reading ease: +64.62333333333333  
Flesch—Kincaid grade level: -22.760000000000005  

| **Version 5eb233f3deb70a6af2235c0b** | **Version 5eb233f4deb70a6af2235f41** |
| :------ | :------ |
| *olvegam@unillanos.edu.co* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Common Solution: Besides solutions such as updating doc along code changes, updating outdated documentation when reported (e.g., removing outdated links if the target no longer exists or removing description of upcoming features or updating source code to match documentation) and rewriting documentation for a major new version, we observed other preventative solutions (such as putting documentation up-to-dateness as one of the items in contribution todo-list or making javadoc update mandatory for pull request acceptance) and hot fixes (e.g.,putting notice about outdated part of documentation. | Common Solution: Typical solutions were updating the documentation according to the code changes, or fixing outdated parts of it (e.g., removing outdated links if the target no longer exists, removing the description of upcoming features. In some cases, it was necessary to update the source code to match the documentation , or to rewrite the whole documentation for a major new version. Interestingly, we observed preventative solutions too, such as putting documentation up-to-dateness as one of the items in contribution todo-list or making javadoc update mandatory for pull request acceptance) and hotfixes (e.g.,putting notice about outdated part of documentation. |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af22619d2  
Flesch reading ease: -14.920349115255846  
Flesch—Kincaid grade level: +7.522842795654849  

| **Version 5eb2341fdeb70a6af223e3cd** | **Version 5eb23420deb70a6af223e6ff** |
| :------ | :------ |
| *gabriele.bavota@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| Besides the information content of documentation, the way how it is presented determines many quality attributes. Inspecting 803 discussions, we grouped these into Maintainability, Readability, Usability, and Usefulness issues, however, there are many other types of issues mentioned in the literature (e.g., see Zhi et al.). As our analysis reveals, a major part of the reported issues was related to simple typos or grammatical mistakes, but these were not considered harmful. Serious problems were these which affected the usefulness or the usability of the documentation, particularly those arising from lousy information organization or affecting the findability of the information. It is an unfortunate situation when the data is there, but the user is not able to find it or understand it. A recommendation for  icon practitioners is to adopt standard solutions and organize the documentation following best practices. While research  icon on investigating users' behavior on what and how they search a piece of information in the documentation could help to refine these practices. | Figure [fig:taxonomy] shows the hierarchical taxonomy of the 167 documentation issue types we defined. They are grouped into four main categories: problems related to the information content of the documentation describe issues arising from "what" is written in the documentation; issues classified in the content (how) category, are still related to the content of the documentation, but in this case the focus is on "how" the content is written and organized; the process-related category groups together issues related to the documentation process; finally, tool-related matters originate from the usage of a documentation tool. For each of these three categories, we describe in a dedicated subsection representative examples of issues we identified, and at the end of each subsection, discuss implications for researchers (indicated with the  icon) and/or practitioners ( icon) derived from our findings. |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af2260959  
Flesch reading ease: +45.55201492537313  
Flesch—Kincaid grade level: -15.545422885572142  

| **Version 5eb23409deb70a6af223a652** | **Version 5eb2340bdeb70a6af223a94a** |
| :------ | :------ |
| *emad.aghajani@usi.ch* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| However, we found one case in Apache httpd documentation mailing list where the traceability information between translations of a document was still managed manually, e.g., by adding a line of comment at top of translations referring to original document and more particularly "The whole point of the comment is to see which exact revisions of the original file you have to diff to see the changes.". | Interestingly, in another thread of the Apache httpd mailing list they discuss an issue of harmful warning messages originating from meta-information they also use to enforce up-to-dateness of different translations. As they conclude, "The whole point of the comment is to see which exact revisions of the original file you have to diff to see the changes.". |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af2261837  
Flesch reading ease: -19.26142857142858  
Flesch—Kincaid grade level: +6.661428571428573  

| **Version 5eb2344adeb70a6af224ca42** | **Version 5eb2344bdeb70a6af224cb2d** |
| :------ | :------ |
| *lmorenoc@colostate.edu* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| Interestingly, we observed that developers adopt preventative solutions to ensure the up-to-dateness of the project's documentation. For example, some projects have added documentation up-to-dateness as one of the items to check in the contribution to-do list, and others have pushed this forward by making Javadoc update mandatory for pull request acceptance. | Some developers adopt preventative solutions to ensure the documentation up-to-dateness, adding documentation up-to-dateness as one of the items to check in the contribution to-do list, or even pushing this forward by making Javadoc update mandatory for pull request acceptance. |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af225fbb3  
Flesch reading ease: -34.41262548262546  
Flesch—Kincaid grade level: +12.74956241956242  

| **Version 5eb233f3deb70a6af2235c0b** | **Version 5eb233f4deb70a6af2235f41** |
| :------ | :------ |
| *olvegam@unillanos.edu.co* | *csaba.nagy@usi.ch* |
| ------------------ | ------------------ |
| Example: The incompleteness could raise from different things such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported"). Fig 4.4 illustrate other type of missing information we observed. | Example: We observed different causes of incompleteness such as missing explanation (e.g.,**"is there any idea what "frequently used" might mean?"), a component in a library (e.g.,**"The documentation on [...] is missing information about the toolbar buttons"), API behavior clarification (e.g.,**"I think that we should add documentation ensuring that the user passes a tree with reset bounds"), or compatibility information (e.g.,**"Explicitly mention if clang 4.x, 5.x are supported"). |


## Change in research-emadpres-icse2019
id: 5eb234c6deb70a6af2260bfa  
Flesch reading ease: -17.882272256728783  
Flesch—Kincaid grade level: +6.013612836438924  

| **Version 5eb233ffdeb70a6af223890c** | **Version 5eb23400deb70a6af2238af3** |
| :------ | :------ |
| *csaba.nagy@usi.ch* | *gabriele.bavota@usi.ch* |
| ------------------ | ------------------ |
| Referring to deprecated information was another case of this issue which was fixed in a case when a user opened an issue and wrote "Homepage recommends deprecated command"). This category of issues also affects other types of information, such as copyright information, version numbers in the code base and even outdated references (22%) which was the most prevalent issue within current category. In one example the outdated link was updated after a user opened an issue and wrote "the example linked in the documentation is using the 3.x version of the API, and that may be confusing to readers", and in another example the outdated link was removed by developers since the target no longer existed. | Referring to deprecated information is also one of the main reasons for up-to-dateness issues, and can affect different types of documentation in different ways: It includes having deprecated information in the project's website (e.g.,"Homepage recommends deprecated command"), to outdated copyright information and version numbers in the code base, as well as outdated references (e.g., links to old versions of the system in the documentation), which was the most prevalent issue within this category. For example, one user reported that "the example linked in the documentation is using the 3.x version of the API, and that may be confusing to readers". |


