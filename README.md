# Title : Conference Paper Acceptance Prediction

## This project was done as a part of Georgia Tech's  CS 7641 - Machine Learning course, Spring 2020

### Summary
Academic research papers have several integral and peripheral aspects apart from the core content such as the authors’ professional affiliations, the number of references or the text readability, to name a few. While the methods and ideas presented in the core content are the most crucial and driving factor for the paper to be accepted by peer reviewers to a conference, it is possible that the aforementioned non-core aspects also influence or contribute to the decision unknowingly. It is possible that the presence of these factors in a certain measure is a subtle indication of a high-quality research paper. For example, it is possible that because the author belongs to one of the topmost universities, she already has a good history of accepted research papers, and her next research paper will have highly innovative ideas articulated well and thus, stand a good chance of acceptance.

Our project explores this idea, and aims to assess if these non-core-content factors could play a role in predicting the chances of a paper being accepted to a conference. It must be noted that we do not intend to say that peer-reviewers get biased or make decisions because of the presence of these factors. We hypothesize that research papers, potentially acceptable because of their merit, may have these factors in common.

Thus, while our primary motivation is to test the above hypothesis, the secondary motivation is to be able to assist academics in the peer reviewing process. While we do not mean to undermine the valuable role peer reviewers play in this process, it must be noted that the process of peer-reviewing has come under scrutiny in the recent years, [5] thanks to loopholes such as lack of qualified reviewers or lack of mechanisms to verify claims of the authors. For example, Walsh et al. (2000) [14] found differences in courtesy between signed and unsigned reviews. (Roberts and Verhoef, 2016) [18] and (Tomkins et al., 2017) [19] found single-blindreviews leading to increased biases towards male authors. Langford and Guzdial (2015) [20] pointed to inconsistencies in the peer review process.

With the huge volume of papers being churned out in any single area of computing (in 2020 alone, 7737 papers were submitted to the AAAI conference [2]), a tool to perform a preliminary analysis of papers could help highlighting potentially acceptable papers and recommending them to reviewers, thus expediting the process.

In order for the tool to have more capabilities for recommendation than relying on non-core factors, we also intend to use unsupervised methods to find patterns in the data and explore its underlying structure, through tasks like topic-modelling and clustering. This could help in detecting topic and domain trends over conferences over several years and or in ascertaining peculiarities of papers potentially acceptable papers. 

You can read more at : https://rohangoel.com/Acceptometer/
