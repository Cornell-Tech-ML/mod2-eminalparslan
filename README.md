[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

# Simple dataset

## Parameters

- Points: 50
- Hidden layer size: 2
- Learning rate: 0.5
- Epochs: 250

![Simple dataset](assets/simple.png)

![Simple loss](assets/simple_loss.png)

![Simple table](assets/simple_table.png)

Time per epoch: 0.049s.


# Diagonal dataset

## Parameters

- Points: 50
- Hidden layer size: 2
- Learning rate: 0.5
- Epochs: 250

![Diagonal dataset](assets/diagonal.png)

![Diagonal loss](assets/diagonal_loss.png)

![Diagonal table](assets/diagonal_table.png)

Time per epoch: 0.049s.

# Split

## Parameters

- Points: 50
- Hidden layer size: 4
- Learning rate: 0.5
- Epochs: 350

![Split dataset](assets/split.png)

![Split loss](assets/split_loss.png)

![Split table](assets/split_table.png)
![Split table 2](assets/split_table2.png)

Time per epoch: 0.101s.


# XOR

## Parameters

- Points: 50
- Hidden layer size: 5
- Learning rate: 0.5
- Epochs: 200

![XOR dataset](assets/xor.png)

![XOR loss](assets/xor_loss.png)

![XOR table](assets/xor_table.png)
![XOR table 2](assets/xor_table2.png)

Time per epoch: 0.132s.

