# nascell-automl
This code belongs to the "Simple implementation of Neural Architecture Search with Reinforcement Learning
" blog post.

# Requirements
- Python 3
- Tensorflow > 1.4

# Training
Print parameters:
```
python3 train.py --help
```
```
optional arguments:
  -h, --help            show this help message and exit
  --max_layers MAX_LAYERS
```
Train:
```
python3 train.py
```

# For evaluate architecture
Print parameters:
```
$ cd experiments/
$ python3 train.py --architecture "61, 24, 60,  5, 57, 55, 59, 3"
```
