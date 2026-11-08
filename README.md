# Banking SLM Finetuning project
- The scope of the project is to finetune an SLM for Banking Customer Support chatbot.
- The project is implemented on kaggle jupyter notebooks.
- The dataset for finetuning is prepared in 2 notebooks
-   slm-finetuning-dataset: loads the Customer Complaint dataset, shortlists selective parameters and prepares a simplified dataset for use in finetuning.
-   alpaca_generation notebook loads the simplified dataset and prepares it for finetuning in alpaca format. Additionally, synthetically prepared refusal dataset and Banking FAQ dataset are added
- banking_alpaca_dataset.json is the final dataset prepared with 1260 data samples of customer complaint response, refusal and banking FAQs.
- The final dataset will be used in slm-finetuning notebook to finetune the Qwen_2.5_1.5b-instruct model.
