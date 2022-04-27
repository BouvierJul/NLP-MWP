<h2 align="center">
  NLP-MWP
</h2>

This repository contains the code to train the modified Graph2Tree model (augmented by a dependency graph) which yields the best performance on the SVAMP dataset.

The repository also contains a notebook to pretrain RoBERTa according to Task Adaptive PreTraining.

The results presented in the report were obtained by training on 1 NVIDIA T4 GPU. We have observed that it can happen that the results are slightly different if the training is done on another hardware. Some operations, like dropout, can also cause discrepancies due to their nondetermistic nature. Nevertheless, we have done our best to ensure that the results are easily reproducible.

Please follow the instructions in `MWP_training.ipynp` notebook.