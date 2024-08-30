# python_code_assistant

- finetuned Salesforce/codegen-350M-mono model into a python code assistant using peft.

- Dataset used : iamtarun/python_code_instructions_18k_alpaca

- Base model size : 350 Million 

- Total tokens Trained for 6 epochs : 23 Million 

- Trainable parameters of the peft model : 2,621,440


# Metrics 
- RogueL : 0.43 on 150 test samples
- Training loss - 0.51

# Training 
- 17k samples for Training.
- 3.5 Hours on Tesla P100 -16 GB (Free kaggle GPU support)
- Dataset : https://huggingface.co/datasets/iamtarun/python_code_instructions_18k_alpaca

# Test the model Yourself

Notebook link : https://colab.research.google.com/drive/1vs94XnCnolhfwvYmgEhZrR_1UqcHmBzg
