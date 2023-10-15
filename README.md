# When your Language Model cannot even do Determiners right: Probing for Anti-Presuppositions and the Maximize Presupposition! Principle

This is the code for our paper "When your Language Model cannot even do Determiners right: Probing for Anti-Presuppositions and the Maximize Presupposition! Principle" (BlackboxNLP 2023)

## Files
- **data**: contains the data from Schneider et al. 2019 that is used to generate the prompts for the models
  
- **scripts**: contains notebooks to replicate the experiments
  - **scripts/finetune_models_on_superglue.ipynb**: preprocess the SuperGlue datasets and fine-tune the language models with this data
  - **scripts/data_preproc_model_predictions_and_evaluation.ipynb**: preprocess the Schneider et al. 2019 data, get the model preditions for the masked tokens and evaluate the results

