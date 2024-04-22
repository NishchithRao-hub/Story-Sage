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
Llama2-7B developed by Meta is available for use publically upon request. Therefore before you can use, you need to request for access on Hugging Face. 
Please follow the below steps to request for access: 
1. Visit [this](https://huggingface.co/meta-llama/Llama-2-7b) page on Hugging Face, fill the application to request for Llama 2 access.
2. You will receive an email to the registered email ID once the access has been granted.
3. We can then use the model freely and load it into our project.

