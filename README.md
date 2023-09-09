# DIREC

## Code

This is the source code for the Paper: _Exploring Substitutable and Complementary Relations for Dual-view Session-based Recommendation_.

## Requirements

- Python 3.9
- PyTorch 1.12

## Best Hyperparameter:
- Tmall: alpha=0.02, beta=100, num_coarse_sampling=90
- E-Commerce (CIKM19): alpha=0.02, beta=150, num_coarse_sampling=90
- Cosmetics: alpha=0.02, beta=100, num_coarse_sampling=90

## Datasets:
The datasets have been preprocessed and encoded with pickle, which can be downloaded from the [link](https://pan.baidu.com/s/1hSNgWucUN0DM6F5N2laFGg) (password: vtm5)

## Train:
- For Tmall and E-Commerce(CIKM19):
~~~~
python main.py --dataset Tmall --alpha 0.02 --beta 100
python main.py --dataset CIKM19 --alpha 0.02 --beta 150
~~~~
- For Cosmetics:
~~~~
python main_cosmetics.py --dataset Cosmetics --alpha 0.02 --beta 100
~~~~
