<h1 align="center">
  <a href="https://uptrain.ai">
    <img width="300" src="https://user-images.githubusercontent.com/108270398/214240695-4f958b76-c993-4ddd-8de6-8668f4d0da84.png" alt="uptrain">
  </a>
</h1>
<p align="center">
  <p align="center">Open-source, self-hosted, easy-to-configure tool to improve ML models in production.</p>
</p>

<h4 align="center">
  <a href="https://github.com/uptrainai/uptrain/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="UpTrain is released under the Apache 2.0 license." />
  </a>
  <a href="https://pypi.org/project/uptrain/">
    <img src="https://badge.fury.io/py/uptrain.svg" alt="PyPI version" />
  </a>
  <a href="https://uptrain-ai.gitbook.io/uptrain-documentation/">
    <img src="https://img.shields.io/badge/Read-Docs-blue" alt="Docs" />
  </a>
  <a href="https://discord.com/invite/gVvZhhrQaQ">
    <img src="https://img.shields.io/badge/Discord-Community-orange" alt="Community" />
  </a>
  <a href="https://uptrain.ai/">
    <img src="https://img.shields.io/badge/Website-Uptrain-green" alt="Website" />
  </a>
</h4>

<h4 align="center">
<img src="https://user-images.githubusercontent.com/108270398/215057294-91168020-49a8-424c-acf2-1f87020d8798.png" width="70%" alt="Performance" />
</h4>

<h4>
</h4>

**[UpTrain](https://uptrain.ai)** is an open-source, data-secure tool for ML practitioners to observe and refine their ML models by monitoring their performance, checking for (data) distribution shifts, and collecting edge cases to retrain them upon. It integrates seamlessly with your existing production pipelines and takes minutes to get started ⚡.

<h4>
</h4>
<h4> </h4>

# Features 💡

☑ **[Performance Monitoring](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - track the performance of your models in realtime and get alerted as soon as a dip is observed.

☑ **[Data Drift Checks](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - identify distribution shifts in your model inputs.

☑ **[Edge Case Signals](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - user-defined signals and statistical techniques to detect out-of-distribution data-points.

☑ **[Data Integrity Checks](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - checks for missing or inconsistent data, duplicate records, data quality, etc. 

☑ **[Customizable metrics](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - define custom metrics that make sense for your use case.

☑ **[Automated Retraining](https://uptrain.gitbook.io/docs/what-is-uptrain/key-features)** - automate model retraining by attaching your training and inference pipelines.

☑ **[Model Bias](https://github.com/uptrain-ai/uptrain/blob/main/examples/3_shopping_cart_rec/uptrain_recommendation_bias.ipynb)** - track popularity bias in your recommendation models.

☑ **Data Security** - your data never goes out of your machine.


## 🚨Coming soon🚨

☐ **Realtime Dashboards** - to visualize your model's health.

☐ **Embeddings Support** - specialized dashboards to understand model-inferred embeddings.

☐ **Slack Integration**

☐ **Label Shfit** to identify distribution shifts in your model predictions. Specially useful in cases when ground truth is unavailable.

☐ **Prediction Stability** 

☐ **AI Explainability**

☐ **Uncertainty Estimation**

☐ **Adversarial Checks**

And more.

<h4> </h4>

# Get started 🙌

### Install the package through pip:
```console
pip install uptrain
```

### Run your first example:
```console
git clone git@github.com:uptrain-ai/uptrain.git
cd uptrain/examples/1_orientation_classification
pip install jupyterlab
jupyter lab
```

For more info, visit our [get started guide](https://uptrain.gitbook.io/docs/get-started).


# 🤩 What makes this 🔥?

Machine learning (ML) models are widely used to make critical business decisions. Still, no ML model is 100% accurate, and, further, their accuracy deteriorates over time 😣. For example, Sales prediction becomes inaccurate over time due to a shift in consumer buying habits. Additionally, due to the black boxiness ⬛ nature of ML models, it's challenging to identify and fix their problems.

UpTrain solves this. We make it easy for data scientists and ML engineers to understand where their models are going wrong and help them fix them before others complain.

We are constantly working to make UpTrain better. Want a new feature or need any integrations? Feel free to [create an issue](https://github.com/uptrain-ai/uptrain/issues) or [contribute](https://github.com/uptrain-ai/uptrain/blob/main/CONTRIBUTING.md) directly to the repository.

# How to Integrate 🛠
After installing the UpTrain package, the user can define a config that tells the tool about the metrics to monitor and the signals to capture. An illustration is provided below. 

<h1 align="left">
<img alt="Integrate" width="60%" src="https://user-images.githubusercontent.com/108270398/213943297-0fbb2afb-908f-4a02-83ca-3e5926716001.png">
</h1>

UpTrain can be used for a wide variety of Machine learning models such as LLMs, recommendation models, prediction models, Computer vision models, etc.

# License 💻

This repo is published under Apache 2.0 license. We're currently focused on developing non-enterprise offerings that should cover most use cases. In the future, we will add a hosted version which we might charge for.

# Stay Updated ☎️
We are continuously adding tons of features and use cases. Please support us by giving the project a star ⭐!

# Provide feedback (Harsher the better 😉) 

We are building UpTrain in public. Help us improve by giving your feedback **[here](https://forms.gle/PXd89D5LiFubro9o9)**
<h1 align="left">
<img alt="Meme" width="40%" src="https://user-images.githubusercontent.com/108270398/215209245-4d6b1f47-7af9-4db8-8d8c-63dcc610571c.jpg">
</h1>
