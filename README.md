# BERT Pre-trained Model

We pre-trained the BERT transformer architecture on sequences of strategies. A strategy sequence is the intentional rather than randomized step-actions performed by a student while solving a problem. These student-problem interaction are present in the log data of MATHia. The BERT model has been pre-trained using the following important hyper-parameters:
-  __L (#Transformers)__: 4
- __A (#Attention Head)__: 8
- __Sequence length__: 128
- __Learning rate__: 2e^{-05}


> Pre-trained model can be found at:
- __pretrained_model/bert_pretrained_model__

# Fine-tuned model (FT)

We fine-tuned the BERT pre-trained model using various features and compared the performances of such fine-tuned models.

> Model fine-tuned on skills (FT + skills)
- __finetuned_model/bert_fine_tuned_model_wskills__

>  Model fine-tuned on temporal features (FT + time)
- __finetuned_model/bert_fine_tuned_model_wtime__

> Model fine-tuned on both skills and temporal features (FT + skills + time)
- __finetuned_model/bert_fine_tuned_model_wskills_wtime__
