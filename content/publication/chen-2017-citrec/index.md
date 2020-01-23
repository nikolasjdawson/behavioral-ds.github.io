---
title: "Revisiting revisits in trajectory recommendation"
date: 2017-01-01
publishDate: 2019-12-29T23:55:04.490773Z
authors: ["Aditya Krishna Menon", "Dawei Chen", "Lexing Xie", "Cheng Soon Ong"]
publication_types: ["1"]
abstract: "Trajectory recommendation is the problem of recommending a sequence of places in a city for a tourist to visit. It is strongly desirable for the recommended sequence to avoid loops, as tourists typically would not wish to revisit the same location. Given some learned model that scores sequences, how can we then find the highest-scoring sequence that is loop-free? This paper studies this problem, with three contributions. First, we detail three distinct approaches to the problem -- graph-based heuristics, integer linear programming, and list extensions of the Viterbi algorithm -- and qualitatively summarise their strengths and weaknesses. Second, we explicate how two ostensibly different approaches to the list Viterbi algorithm are in fact fundamentally identical. Third, we conduct experiments on real-world trajectory recommendation datasets to identify the tradeoffs imposed by each of the three approaches. Overall, our results indicate that a greedy graph-based heuristic offer excellent performance and runtime, leading us to recommend its use for removing loops at prediction time."
featured: false
publication: "*International Workshop on Recommender Systems for Citizens (CitRec)*"
doi: "10.1145/3127325.3127326"
---

