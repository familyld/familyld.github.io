---
title: "DeepCF: A Unified Framework of Representation Learning and Matching Function Learning in Recommender System"
collection: publications
permalink: /publication/2019-07-17-AAAI_DeepCF
excerpt: 'This paper is about incorporating representation learning-based methods and matching function learning-based methods in collaborative filtering. Python code is available.'
date: 2019-07-17
venue: 'AAAI'
paperurl: 'https://familyld.github.io/files/19AAAI_DeepCF.pdf'

---
Authors: **Zhi-Hong Deng**, Ling Huang, Chang-Dong Wang, Jian-Huang Lai, Philip S. Yu.

In general, recommendation can be viewed as a matching problem, i.e., match proper items for proper users. However, due to the huge semantic gap between users and items, it’s almost impossible to directly match users and items in their initial representation spaces. To solve this problem, many methods have been studied, which can be generally categorized into two types, i.e., representation learning-based CF methods and matching function learning-based CF methods. Representation learning-based CF methods try to map users and items into a common representation space. In this case, the higher similarity between a user and an item in that space implies they match better. Matching function learning-based CF methods try to directly learn the complex matching function that maps user-item pairs to matching scores. Although both methods are well developed, they suffer from two fundamental flaws, i.e., the limited expressiveness of dot product and the weakness in capturing low-rank relations respectively. To this end, we propose a general framework named DeepCF, short for Deep Collaborative Filtering, to combine the strengths of the two types of methods and overcome such flaws. Extensive experiments on four publicly available datasets demonstrate the effectiveness of the proposed DeepCF framework.

[Download paper here](https://familyld.github.io/files/19AAAI_DeepCF.pdf)

[Code](https://github.com/familyld/DeepCF)

