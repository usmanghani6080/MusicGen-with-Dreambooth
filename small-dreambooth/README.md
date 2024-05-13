---
license: cc-by-nc-4.0
library_name: peft
tags:
- text-to-audio
- ylacombe/tiny-punk
- generated_from_trainer
base_model: facebook/musicgen-small
model-index:
- name: musicgen-melody-lora-punk-batch3
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

[<img src="https://raw.githubusercontent.com/wandb/assets/main/wandb-github-badge-28.svg" alt="Visualize in Weights & Biases" width="200" height="32"/>](https://wandb.ai/resanddev/huggingface/runs/njbjznpw)
# musicgen-melody-lora-punk-batch3

This model is a fine-tuned version of [facebook/musicgen-melody](https://huggingface.co/facebook/musicgen-melody) on the YLACOMBE/TINY-PUNK - DEFAULT dataset.
It achieves the following results on the evaluation set:
- Loss: 4.7352
- Clap: 0.0386

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 3
- eval_batch_size: 1
- seed: 456
- gradient_accumulation_steps: 8
- total_train_batch_size: 24
- optimizer: Adam with betas=(0.9,0.99) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 4.0
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.10.0
- Transformers 4.41.0.dev0
- Pytorch 2.3.0+cu121
- Datasets 2.19.1
- Tokenizers 0.19.1