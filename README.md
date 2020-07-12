# Predict-recommendation-need
This repo contains data used in the paper "Predicting learners need for recommendation using dynamic graph-based knowledge tracing" in the International Conference on Artificial Intelligence in Education (AIED'20).

By Abdessamad Chanaa & Nour-eddine El Faddouli.

### Related Paper

Predicting learners need for recommendation using dynamic graph-based knowledge tracing.

```
https://link.springer.com/chapter/10.1007/978-3-030-52240-7_9
```

## Files

 
```
Data_compress.csv.xz
``` 

Contains data extracted from the ASSISTments learning platform, this new data aggregate eight different features that represent the learner:

**-Time spent.**

**-The number of correct answers.**

**-The hints count.**

**-The attempts count.**

**-The Frustration score.**

**-The Boredom score.**

**-The Confusion score.**

**-The Concentration score.**


Each learner is labelled with a binary value indicating whether the learner has low knowledge acquisition or not.

```
graph_skill.npz 
```
Contains an example of the generated dynamic graph ( we choose the concept "Addition and Subtraction Integers" for this graph)

The source code for generating a graph based on a selected concept will be shared soon.

## Citation

If you use those data please cite us:
```
@inproceedings{chanaa2020predicting,
  title={Predicting Learners Need for Recommendation Using Dynamic Graph-Based Knowledge Tracing},
  author={Chanaa, Abdessamad and El Faddouli, Nour-Eddine},
  booktitle={International Conference on Artificial Intelligence in Education},
  pages={49--53},
  year={2020},
  organization={Springer}
}
```

