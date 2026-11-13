# GenrePredict

Predicts a song's genre from its lyrics with a BERT-based classifier (`model.ipynb`).

## Weights and data

The trained weights and the dataset are attached to the [v1.0 release](https://github.com/dledbetter123/GenrePredict/releases/tag/v1.0) rather than kept in the repo:

| File | Size | What it is |
|---|---|---|
| [`model.pth`](https://github.com/dledbetter123/GenrePredict/releases/download/v1.0/model.pth) | 71 MB | trained PyTorch weights |
| [`sampled_songs.csv`](https://github.com/dledbetter123/GenrePredict/releases/download/v1.0/sampled_songs.csv) | 18 MB | the lyrics sample `model.ipynb` reads |

Download both into the repo root before running the notebook:

```
gh release download v1.0 -R dledbetter123/GenrePredict
```

or

```
curl -LO https://github.com/dledbetter123/GenrePredict/releases/download/v1.0/model.pth
curl -LO https://github.com/dledbetter123/GenrePredict/releases/download/v1.0/sampled_songs.csv
```

SHA-256:

```
2f638980e65af39e1fd5d6e906b74cce676aab8374e5b1bfcb47f7018599384c  model.pth
5cedd3ac36d05b7e8f621742ef850ff0a2eb0e26cda7917d3cd7a663eeae0c6d  sampled_songs.csv
```
