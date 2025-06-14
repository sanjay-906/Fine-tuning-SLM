## Fine-tuning-SLM

Supervised fine-tuning and Direct preference optimization

Dataset: (https://huggingface.co/datasets/truthfulqa/truthful_qa)<br>
model: https://huggingface.co/Qwen/Qwen2.5-3B<br>
Training stage: Pre-training<br>
Dataset length = 817 fields

### Stage 1: Supervised Fine-tuning

Trained for 30 epochs<br>
Results:
- BLEU score: 0.176618 -> 0.294391 (~ +66.68%)
- Rouge 1: 0.484373 -> 0.613024 (~ +26.56%)
- Rouge L: 0.445929	-> 0.582446	(~ +30.61%)
- BERTScore F1: 0.863016 -> 0.884849 (~ +2.53%)

#### Train loss
![train_loss-sft](https://github.com/user-attachments/assets/f41dc1e1-bdd6-43f3-8cb8-06d1e7e36d02)

#### Eval loss
![eval_loss-sft](https://github.com/user-attachments/assets/f7784ac1-4a60-49c6-ad36-7ef5385f6b90)


### Stage 2: Direct Preference Optimization
Work in progress
