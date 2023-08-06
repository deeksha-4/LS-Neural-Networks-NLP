# Final Project

Welcome to the last part of this LS course, the final project.

### Your task: **To fine-tune a pre-trained model for a specific downstream task, and create a simple demo app to interact with it**

Roughly, the project can be split into 3 parts:

- **Finalizing the details** of your project. This includes deciding which model to use as you base, the task you will train it on, and what dataset to use.
- **Writing** the **script to train your model**, and then saving the model locally after training it
- Using Gradio, **making a simple demo application** that will let people interact with your fine-tuned model.

What task your model will perform and the dataset you will use is completely up to you.

You can find some datasets on [**Kaggle**](https://www.kaggle.com/datasets), [**Hugging Face**](https://huggingface.co/docs/datasets/index) or from one of the [example projects](#examples).

[**Hugging Face 🤗 Tranformers**](https://huggingface.co/docs/transformers/index)  
[**Hugging Face Guide on fine-tuning using 🤗 Tranformers**](https://huggingface.co/docs/transformers/training)

If you are using a Colab notebook to train your model, you will have to choose a model such that can run on the limited resources Google provides in the free tier (ex. GPT-2, DistilBERT, ALBERT).  
Remember to change runtime types to leverage GPU hardware acceleration.

## Submission Guidelines

You are expected to submit:

- The file you have used for training the model, be it a notebook or just a Python file. **The file should be well documented** (with comments/text cells), and should **explain the purpose of each block of code**. **Failure** to do so will lead to **rejection of your submission**.
- The saved model's file
- The file for running the demo Gradio application
- A README containing details on your project: the model, task and dataset. Include any unique challenges you faced whilst doing the project (.txt or .md, either words).

#### You can submit the files via a Drive folder or Hugging Face repository.

[**Hugging Face Guide on saving models on 🤗 repos**](https://huggingface.co/docs/transformers/model_sharing)

If you have any doubts/queries regarding the submission, please reach out to one of the course moderators

## Examples

Here are a few examples on fine-tuning a pre-trained model.

- [**Oversimplified model of transformer to implement Named Entity Recognition**](https://github.com/karndeepsingh/Named-Entity-Recognition/blob/main/NAMED%20ENTITY%20RECOGNITION.ipynb)
- [**Poetry generation transformer model**](https://medium.com/mlearning-ai/automatic-generation-of-emotionally-expressive-poetry-by-fine-tuning-gpt-2-using-pytorch-68dace59fca0)
- [**Another poem generation transformer model**](https://www.kaggle.com/code/michaelarman/poem-generation-with-transformers)
