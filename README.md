# Fine-Tuning-multiple-labels
Fine-tune RoBERTa to classify toxic online comments.



1. Use the Unhealthy Comment Corpus dataset (already included in
Fine_tuning_RoBERTa_Unhealthy_Comment_Corpus.ipynb).
2. Modify training settings:
o Experiment with diJerent batch sizes (16, 32, 64).
o Test diJerent learning rates (1e-5, 3e-5, 5e-5).
o Implement gradient clipping to avoid exploding gradients.
3. Evaluate the model on Precision, Recall, F1-score, and AUROC.
4. Plot:
o Training loss over time
o Validation accuracy over time
o Precision-Recall curves for diJerent classes
