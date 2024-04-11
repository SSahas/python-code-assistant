# python_code_assistant

- finetuned Salesforce/codegen-350M-mono model into a python code assistant 

- Dataset used : iamtarun/python_code_instructions_18k_alpaca

- Base model size : 350 Million parameters 

- Total tokens Trained for 6 epochs : 25 Million 

- Trainable parameters of the peft model : 1,310,720


# Metrics 
- RogueL : 0.41 on 150 test samples
- Training loss - 0.55

# Training 
- 7 Hours on Tesla P100 -16 GB (Kaggle)
