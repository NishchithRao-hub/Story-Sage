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


