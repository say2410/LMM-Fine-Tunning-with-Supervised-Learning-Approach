# Generate Headlines

<a name="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Fine-Tuning Large Language Models</h3>

  <p align="center">
    How Vertex AI Takes LLMs to the Next Level!!
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About This Repository</a>
      <ul>
        <li><a href="#Why fine-tunning matters">Why fine-tunning matters</a></li>
        <li><a href="#Dataset">Dataset</a></li>
        <li><a href="#Model Used">Model Used</a></li>
        <li><a href="#Steps">Steps </a></li>
      </ul>
    </li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About This Repository

This repository was created to document the work done in the session 6 of Code Vipassana Season 6. We'll automatically generate headlines for news articles using Vertex AI. We'll see how to perform fine-tuning using the supervised tuning approach for an LLM model. Supervised tuning helps make a model better by teaching it a new skill. We use a dataset with lots of labeled examples to show the model how to perform a specific task or behave in a certain way. By providing input text (prompt) and output text (response) examples, we teach the model how to give the kind of responses we want for our specific needs.

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>

### Why fine-tunning matters

Foundation models are designed to handle general tasks, but they might not always perform well on specific tasks. This can happen because specialized tasks are hard to teach just by adjusting prompts. To improve a model's performance on these tasks, you can use model tuning. This method can also help meet specific output requirements when instructions alone aren't enough. Large language models (LLMs) have a lot of information and can do many tasks, but they work best with specialized training. Fine-tuning helps train an LLM to better meet your specific needs by adapting a pre-trained model.

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>

### Dataset

We'll start with a dataset of news articles and their corresponding headlines, like the BBC News dataset used in the example code made available by BigQuery Public Dataset.

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>

### Model Used

We choose a base model like "text-bison@002" and fine-tune it with your news data using Vertex AI SDK for Python. Compare the performance of this fine-tuned model with the base model to see the improvement in headline generation quality.

<p align="right">(<a href="#readme-top">Back to Top</a>)</p>

### Steps

1. Create a project on Google cloud and enable the billing.
2. Run the installations in the colab notebook in this repo.
3. Replace project id with your project id on the google cloud console.
4. Make sure to enable Vertex AI by simply searching it and enabling it.
5. Upload the TRAIN.jsonl on the cloud storage bucket. Give edit access.
6. Run the complete ipynb file.
<p align="right">(<a href="#readme-top">Back to Top</a>)</p>
