# GNN Battle Royal

Rules are simple: No rules. You start with two identical tasks from the [Open Graph Benchmark](https://ogb.stanford.edu) from Stanford. Two tasks are selected: Node classification with [ogbn-arxiv](https://ogb.stanford.edu/docs/nodeprop/#ogbn-arxiv) and graph classification with [ogbg-molhiv](https://ogb.stanford.edu/docs/graphprop/#ogbg-mol). 

## Leaderboards
If first in one task, you'll earn a mystery legendary loot. Hence, two winners (or one) will be elected. Your final grade will simply be related to your participation to this challenge. Submission to this benchmark are simple as well, upload directory with your name on the corresponding folder *e.g. arxiv/parcollet-titouan*. Then, add your score to the corresponding table in the `Readme.md`!

**YOUR CODE MUST BE SELF-CONTAINED** I am fine with installing dependencies but basically, I do not expect to see more than 4 files in your submission: `requirements.txt` (for external dependencies), `train.py` (the trainer), `model.py` (definition of the model) and `data.py` (for any RELEVANT data preparation). 

**any entry to the leaderboard that isn't reproducible will be invalidated by myself (non-reproducible research sucks)!** 

## Advices
- Start small, explore the dataset, understand it.
- Do not blindly apply all the models from `torch_geometric`. Tuning a promising model instead of trying thousands of them will certainly lead you to the top-1. 
- Do not think that a custom model is a bad idea. Models implemented by default in `torch_geometric` are generic. It is most likely that a SotA handcrafted model will end-up being better !


|                |     ogbn-arxiv                     | ogbg-mol                         |
|----------------|-------------------------------|-----------------------------|
|Firstname Lastname|   xx       | xx           |



