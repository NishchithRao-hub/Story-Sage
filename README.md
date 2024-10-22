# STORY SAGE
Story Sage : Short-Story ending prediction model based on a given theme. 

## Using the model :
All models used for theme extraction, summarization and ending prediction have been fine-tuned, trained and uploaded to [Hugging Face](https://huggingface.co) website. We did this so that the model doesn't need to be trained each time before use.

In order to access the trained models from Hugging Face, follow the below steps.
1. Create a new account.
2. Request for User Access Tokens. Please follow this link to request for [Access tokens](https://huggingface.co/docs/hub/en/security-tokens).
3. Update the Llama_For_Story Ending Prediction.ipynb file under model directory with the user access tokens when prompted.

```
from huggingface_hub import login
login()
```
Llama2-7B developed by Meta is available for use publically only upon request. Therefore before use, you need to request for access on Hugging Face. 
Please follow the below steps to request for access: 
1. Visit [this](https://huggingface.co/meta-llama/Llama-2-7b) page on Hugging Face, fill the application to request for Llama 2 access.
2. You will receive an email to the registered email ID once the access has been granted.
3. We can then use the model freely and load it into our project.

In order to view the logs while training the models, we have made use of **wandb**. Before using it, we need to request access. 
Please follow the below steps to request access for wandb.
1. Create an account with [Weights & Biases](https://wandb.ai/site).
2. Follow the steps written in the documentation [here](https://docs.wandb.ai/quickstart) to set up wandb in your coding environment. Enter your API keys when prompted.

```
pip install wandb
wandb login
```
