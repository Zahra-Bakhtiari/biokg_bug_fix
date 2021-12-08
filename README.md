# ogbl-biokg

This code includes implementation of TransE, DistMult, ComplEx and RotatE with OGB evaluator. It is based on this [repository](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding).

## Training & Evaluation

```
# Run with default config
bash examples.sh
```# biokg_bug_fix: the run.py file has a bug when it is running on linux which essentially stops the model from reporting the train/valid/test results gradual report at each step which is confusing for user
