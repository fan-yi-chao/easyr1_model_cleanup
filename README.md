# Model Checkpoint Retention Policy

## Scenario
Our storage is full! The training cluster is accumulating too many checkpoint files.
You need to write a cleanup script (`cleanup.py`) to delete old checkpoints while keeping critical ones.

## Directory Structure
checkpoints/
  model_bert_v1_dev.pt
  model_bert_v2_prod.pt
  ...

See Task Description for the retention rules.
