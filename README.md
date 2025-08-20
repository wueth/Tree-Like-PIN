# Tree-Like-PIN
This repository provides the code and data of the article Tree-Like Pairwise Interaction Network (PIN)

Modeling feature interactions in tabular data remains a key challenge in predictive modeling, 
for example, as used for insurance pricing. This paper proposes the Tree-like Pairwise Interaction 
Network (PIN), a novel neural network architecture that explicitly captures pairwise feature 
interactions through a shared feed-forward neural network architecture that mimics the structure 
of decision trees. PIN enables intrinsic interpretability by design, allowing for direct inspection 
of interaction effects. Moreover, it allows for efficient SHapley’s Additive exPlanation (SHAP) 
computations because it only involves pairwise interactions. We highlight connections between 
PIN and established models such as GA²Ms, gradient boosting machines, and graph neural networks. 
Empirical results on the popular French motor insurance dataset show that PIN outperforms both 
traditional and modern neural networks benchmarks in predictive accuracy, while also providing 
insight into how features interact with each another and how they contribute to the predictions.
