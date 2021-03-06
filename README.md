# A Mention-Ranking Model for Abstract Anaphora Resolution
Resolution of anaphors that refer to propositions, facts, events or properties 

Ana Marasovic, Leo Born, Juri Opitz, and Anette Frank (2017): [A Mention-Ranking Model for Abstract Anaphora Resolution](https://arxiv.org/abs/1706.02256). In Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (EMNLP). Copenhagen, Denmark.

<p align="center"><img src="figs/mr_lstm.png" width="400" align="middle" alt="LSTM-Siamese mention-ranking model"></p>

## Requirements

- [tensorflow 0.12](https://www.tensorflow.org/versions/r0.12/)
- [nltk](http://www.nltk.org) 
- [gensim](https://radimrehurek.com/gensim/)
- [matplotlib](https://matplotlib.org)
- [scikit-learn](http://scikit-learn.org/stable/)
- [hyperopt](https://github.com/hyperopt/hyperopt)


## Instructions

- use `main.py`, `train.py`, `models.biLSTM_SiameseMR.py` to train the model for shell noun or abstract anaphora resolution 
- use `main_tuner.py`, `train_tuner.py`, `models.biLSTM_SiameseMR.py` to tune HPs
- use `eval.py` to get figures

## Data

Coming soon. 

## Reference

If you make use of the contents of this repository, please cite [the following paper](https://arxiv.org/abs/1706.02256):

```
@inproceedings{marasovic2017aar,
  title={{A Mention-Ranking Model for Abstract Anaphora Resolution}},
  author={Marasovi\'{c}, Ana and Born, Leo and Opitz, Juri and Frank, Anette},
  booktitle={Proceedings of the 2017 Conference on Empirical Methods in Natural Language Processing (EMNLP)},
  year={2017}
}
```

